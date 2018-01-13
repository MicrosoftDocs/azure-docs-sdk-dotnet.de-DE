<Type Name="IPartitionResolver" FullName="Microsoft.Azure.Documents.Client.IPartitionResolver">
  <TypeSignature Language="C#" Value="public interface IPartitionResolver" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPartitionResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.IPartitionResolver" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPartitionResolver" />
  <TypeSignature Language="F#" Value="type IPartitionResolver = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for IPartitionResolver is now obsolete. It's recommended that you use partitioned collections for higher storage and throughput.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Dies stellt einen Partition-Konfliktlöser für eine Datenbank dar. Partitionsschlüssel, zurück Auflistung einem Abgleich den Partitionsschlüssel im Azure-Cosmos-DB-Dienst.
            </summary>
    <remarks>
      <para>
            Unterstützung für IPartitionResolver ist jetzt veraltet. Es wird empfohlen, die Verwendung von <a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">partitionierte Sammlungen</a> für höhere Speicher und den Durchsatz.
            </para>
      <para>
            DocumentClient ermöglicht das Erstellen und registrieren Sie IPartitionResolvers Implementierungen für jede Datenbank. Nach der Registrierung können Sie direkt an einer Datenbank statt einer Auflistung Dokumentenvorgänge ausführen. IPartitionResolvers verfügt über nur drei Methoden ExtractPartitionKey, ResolveForCreate und ResolveForRead.
            </para>
      <para>
            LINQ-Abfragen und ReadFeed Iteratoren mithilfe der ResolveForRead intern durchlaufen alle Sammlungen, die den Partitionsschlüssel für die Anforderung zu entsprechen. Erstellen Sie, verwenden Sie Vorgänge der ResolveForCreate zum Weiterleiten auf die richtige Partition erstellt. Es sind keine Änderungen erforderlich für ersetzen, löschen und lesen, da sie das Dokument verwenden, die bereits den Verweis auf die Auflistung enthält, die das Dokument enthält.
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetPartitionKey">
      <MemberSignature Language="C#" Value="public object GetPartitionKey (object document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object GetPartitionKey(object document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.IPartitionResolver.GetPartitionKey(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionKey (document As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetPartitionKey : obj -&gt; obj" Usage="iPartitionResolver.GetPartitionKey document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="document">Ein Document-Objekt.</param>
        <summary>
            Extrahiert den Partitionsschlüssel aus einem Dokument in der Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Der Partitionsschlüssel für das Dokument.</returns>
        <remarks>
            Typische Implementierungen rufen Sie den Wert einer einzelnen Eigenschaft aus dem Dokument (z. B. Benutzer-ID) oder eine zusammengesetzte Eigenschaft für z. B. Versions-ID extrahieren werden Gerät #) oder basierend auf dem Typ des Dokuments für z. B. Systemlogik implementieren, Wert der Id für Benutzer zu extrahieren, aber die UserId für UserMessages zu extrahieren.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveForCreate">
      <MemberSignature Language="C#" Value="public string ResolveForCreate (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string ResolveForCreate(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.IPartitionResolver.ResolveForCreate(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveForCreate (partitionKey As Object) As String" />
      <MemberSignature Language="F#" Value="abstract member ResolveForCreate : obj -&gt; string" Usage="iPartitionResolver.ResolveForCreate partitionKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="partitionKey">Der Partitionsschlüssel verwendet werden, um zu bestimmen, das Ziel Auflistung für Vorgänge zu erstellen.</param>
        <summary>
            Erhält einen Partitionsschlüssel eingeben, gibt dies die Auflistung Self-link für das Erstellen eines Dokuments in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Eine Self-link für die Auflistung zum Erstellen von Dokumenten im für den angegebenen Partitionsschlüssel.</returns>
        <remarks>
            Der Rückgabewert muss eine gültige Sammlung Self-link-Zeichenfolge in das Format Dbs/Db_rid/colls/Col_rid.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveForRead">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;string&gt; ResolveForRead (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; ResolveForRead(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.IPartitionResolver.ResolveForRead(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveForRead (partitionKey As Object) As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="abstract member ResolveForRead : obj -&gt; seq&lt;string&gt;" Usage="iPartitionResolver.ResolveForRead partitionKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="partitionKey">Der Partitionsschlüssel, bestimmen Sie die Zielsammlungen für Lesevorgänge, d. h., die Abfrage oder Read-Feed verwendet.</param>
        <summary>
            Erhält einen Partitionsschlüssel eingeben, gibt diese zurück, dass eine Liste der Sammlung Self-links, um gelesen werden.
            </summary>
        <returns>Die Self-links für die Auflistungen leseanforderungen für den angegebenen Partitionsschlüssel ausführen.</returns>
        <remarks>
            Der Rückgabewert muss ein IEnumerable von Self-link-Zeichenfolgen in die Format-Dbs/Db_rid/colls/Col_rid Auflistung sein.
            Im Gegensatz zu ResolveForCreate ist dies eine 1: n, wie ein einzelne Partitionsschlüssel in unterschiedlichen Sammlungen mit der Zeit erstellt werden kann, oder weil Sie die Datenmigration von Partitionsschlüssel zwischen Auflistungen in der Azure-Cosmos-DB-Dienst ausführen.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>