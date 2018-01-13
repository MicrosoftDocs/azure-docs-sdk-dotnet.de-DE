<Type Name="DocumentCollection" FullName="Microsoft.Azure.Documents.DocumentCollection">
  <TypeSignature Language="C#" Value="public class DocumentCollection : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DocumentCollection extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.DocumentCollection" />
  <TypeSignature Language="VB.NET" Value="Public Class DocumentCollection&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DocumentCollection = class&#xA;    inherit Resource" />
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
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Auflistung Dokument im Azure-Cosmos-DB-Dienst. Eine Auflistung ist ein benannter logischer Container für Dokumente. 
            </summary>
    <remarks>
            Eine Datenbank kann NULL oder mehr benannte Sammlungen enthalten, und jede Sammlung besteht aus null oder mehr JSON-Dokumente. Wird das Schema frei, die Dokumente in einer Auflistung müssen nicht die gleiche Struktur oder Felder freigeben. Da Sammlungen Anwendungsressourcen sind, können sie mit dem Hauptschlüssel oder / / Ressourcenschlüssel autorisiert werden.
            Verweisen auf <see>http://azure.microsoft.com/documentation/articles/documentdb-resources/#collections</see> für Weitere Informationen zu Sammlungen.
            </remarks>
    <altmember cref="T:Microsoft.Azure.Documents.IndexingPolicy" />
    <altmember cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />
    <altmember cref="T:Microsoft.Azure.Documents.Document" />
    <altmember cref="T:Microsoft.Azure.Documents.Database" />
    <altmember cref="T:Microsoft.Azure.Documents.Offer" />
    <example>
            Das folgende Beispiel erstellt eine neue partitionierte Sammlung mit 50000 Anforderungseinheit pro Durchsatz.
            Der Partitionsschlüssel ist die erste Ebene "Land"-Eigenschaft in allen Dokumenten in dieser Auflistung.
            <code language="c#"><![CDATA[
            DocumentCollection collection = await client.CreateDocumentCollectionAsync(
                databaseLink,
                new DocumentCollection 
                { 
                    Id = "MyCollection",
                    PartitionKey = new PartitionKeyDefinition
                    {
                        Paths = new Collection<string> { "/country" }
                    }
                }, 
                new RequestOptions { OfferThroughput = 50000} ).Result;
            ]]></code></example>
    <example>
            Das folgende Beispiel erstellt eine neue Sammlung mit OfferThroughput bis 10000 festgelegt.
            <code language="c#"><![CDATA[
            DocumentCollection collection = await client.CreateDocumentCollectionAsync(
                databaseLink,
                new DocumentCollection { Id = "MyCollection" }, 
                new RequestOptions { OfferThroughput = 10000} ).Result;
            ]]></code></example>
    <example>
            Das folgende Beispiel erstellt eine neue Sammlung mit einem benutzerdefinierten indizierungsrichtlinie.
            <code language="c#"><![CDATA[
            DocumentCollection collectionSpec = new DocumentCollection { Id ="MyCollection" };
            collectionSpec.IndexingPolicy.Automatic = true;
            collectionSpec.IndexingPolicy.IndexingMode = IndexingMode.Consistent;
            collection = await client.CreateDocumentCollectionAsync(database.SelfLink, collectionSpec);
            ]]></code></example>
    <example>
            Das folgende Beispiel erstellt ein Dokument vom Typ Book innerhalb dieser Auflistung.
            <code language="c#"><![CDATA[
            Document doc = await client.CreateDocumentAsync(collection.SelfLink, new Book { Title = "War and Peace" });
            ]]></code></example>
    <example>
            Im Beispiel unten Abfragen für eine Datenbank-Id, die SelfLink abzurufen.
            <code language="c#"><![CDATA[
            using Microsoft.Azure.Documents.Linq;
            DocumentCollection collection = client.CreateDocumentCollectionQuery(databaseLink).Where(c => c.Id == "myColl").AsEnumerable().FirstOrDefault();
            string collectionLink = collection.SelfLink;
            ]]></code></example>
    <example>
            Im folgenden Beispiel wird diese Auflistung gelöscht.
            <code language="c#"><![CDATA[
            await client.DeleteDocumentCollectionAsync(collection.SelfLink);
            ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.DocumentCollection.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
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
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> Klasse für den Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConflictsLink">
      <MemberSignature Language="C#" Value="public string ConflictsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConflictsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.ConflictsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConflictsLink As String" />
      <MemberSignature Language="F#" Value="member this.ConflictsLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.ConflictsLink" />
      <MemberType>Property</MemberType>
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
      <Docs>
        <summary>
            Ruft ab, der Self-link für Konflikte in einer Auflistung aus dem Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Der Self-link für Konflikte in einer Auflistung.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultTimeToLive">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DefaultTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DefaultTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultTimeToLive As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DefaultTimeToLive : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />
      <MemberType>Property</MemberType>
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="defaultTtl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Standardzeit für die Gültigkeitsdauer in Sekunden für die Dokumente in einer Auflistung aus dem Azure-Cosmos-DB-Dienst ab.
            </summary>
        <value>
            Es ist eine optionale Eigenschaft.
            Ein gültiger Wert muss entweder eine positive ganze Zahl ungleich NULL, "1", oder <c>null</c>.
            Standardmäßig wird die DefaultTimeToLive auf null Bedeutung festgelegt, der die Zeit Gültigkeitsdauer für die Auflistung deaktiviert ist.
            Die Maßeinheit ist Sekunden. Die zulässige Maximalwert ist 2147483647.
            </value>
        <remarks>
          <para>
            Die <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> gelten für alle Dokumente in der Auflistung als Standard Time-to-live-Richtlinie.
            Das Dokument konnte die Time-to-live Standardrichtlinie überschreiben, indem seine <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />.
            </para>
          <para>
            Wenn die <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> ist <c>null</c>, die Time-to-live werden ausgeschaltet für die Auflistung.
            Dies bedeutet, dass alle Dokumente nicht abläuft. Des einzelne Dokuments <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> wird ignoriert.
            </para>
          <para>
            Wenn die <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> ist '1', die Time-to-live werden aktiviert, für die Auflistung.
            Standardmäßig abläuft nie alle Dokumente. Das Dokument konnte einen bestimmten Time-to-live-Wert zugewiesen werden, durch Festlegen seiner <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />. Des Dokuments <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> wird berücksichtigt werden, und die abgelaufenen Dokumente im Hintergrund gelöscht werden.
            </para>
          <para>
            Wenn die <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> eine positive ganze Zahl ungleich NULL, wird die Time-to-live werden aktiviert, für die Auflistung.
            Und ein Standard Gültigkeitsdauer in Sekunden werden auf alle Dokumente angewendet werden. Ein Dokument abgelaufen sein wird nach dem angegebenen <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> Wert in Sekunden, die seit der letzten Schreibzugriffs.
            Das Dokument konnte die Time-to-live Standardrichtlinie überschreiben, indem seine <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />.
            Finden Sie in der <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> ausführliche Informationen zum Auswerten der endgültigen Time-to-live-Richtlinie eines Dokuments.
            </para>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.Document" />
        <example>
            Das folgende Beispiel deaktiviert Time-to-live, auf eine Auflistung.
            <code language="c#"><![CDATA[
                collection.DefaultTimeToLive = null;
            ]]></code></example>
        <example>
            Das folgende Beispiel aktiviert Time-to-live, auf eine Auflistung. Alle Dokumente sollen standardmäßig nie ablaufen.
            <code language="c#"><![CDATA[
                collection.DefaultTimeToLive = -1;
            ]]></code></example>
        <example>
            Das folgende Beispiel aktiviert Time-to-live, auf eine Auflistung. Standardmäßig wird das Dokument nach 1000 Sekunden ablaufen, seit der letzten Schreibzugriffs.
            <code language="c#"><![CDATA[
            collection.DefaultTimeToLive = 1000;
                ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="DocumentsLink">
      <MemberSignature Language="C#" Value="public string DocumentsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DocumentsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.DocumentsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DocumentsLink As String" />
      <MemberSignature Language="F#" Value="member this.DocumentsLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.DocumentsLink" />
      <MemberType>Property</MemberType>
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_docs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, der Self-link für Dokumente in einer Auflistung aus dem Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Der Self-link für Dokumente in einer Auflistung.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.IndexingPolicy IndexingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.IndexingPolicy IndexingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.IndexingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexingPolicy As IndexingPolicy" />
      <MemberSignature Language="F#" Value="member this.IndexingPolicy : Microsoft.Azure.Documents.IndexingPolicy with get, set" Usage="Microsoft.Azure.Documents.DocumentCollection.IndexingPolicy" />
      <MemberType>Property</MemberType>
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
        <ReturnType>Microsoft.Azure.Documents.IndexingPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <see cref="P:Microsoft.Azure.Documents.DocumentCollection.IndexingPolicy" /> der Auflistung aus dem Azure-Cosmos-DB-Dienst zugeordnet sind. 
            </summary>
        <value>
            Die indizierungsrichtlinie Sammlung zugeordnet wird.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.PartitionKeyDefinition PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.PartitionKeyDefinition PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As PartitionKeyDefinition" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : Microsoft.Azure.Documents.PartitionKeyDefinition with get, set" Usage="Microsoft.Azure.Documents.DocumentCollection.PartitionKey" />
      <MemberType>Property</MemberType>
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="partitionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.PartitionKeyDefinition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest <see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" /> Objekt in der Azure-Cosmos-Datenbank.
            </summary>
        <value>
          <see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />-Objekt
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProceduresLink">
      <MemberSignature Language="C#" Value="public string StoredProceduresLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoredProceduresLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.StoredProceduresLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredProceduresLink As String" />
      <MemberSignature Language="F#" Value="member this.StoredProceduresLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.StoredProceduresLink" />
      <MemberType>Property</MemberType>
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_sprocs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, der Self-link für gespeicherte Prozeduren in einer Auflistung aus dem Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Der Self-link für gespeicherte Prozeduren in einer Auflistung.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggersLink">
      <MemberSignature Language="C#" Value="public string TriggersLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TriggersLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.TriggersLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggersLink As String" />
      <MemberSignature Language="F#" Value="member this.TriggersLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.TriggersLink" />
      <MemberType>Property</MemberType>
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
      <Docs>
        <summary>
            Ruft ab, der Self-link für Trigger in einer Auflistung aus dem Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Der Self-link für Trigger in einer Auflistung.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UniqueKeyPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.UniqueKeyPolicy UniqueKeyPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.UniqueKeyPolicy UniqueKeyPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.UniqueKeyPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property UniqueKeyPolicy As UniqueKeyPolicy" />
      <MemberSignature Language="F#" Value="member this.UniqueKeyPolicy : Microsoft.Azure.Documents.UniqueKeyPolicy with get, set" Usage="Microsoft.Azure.Documents.DocumentCollection.UniqueKeyPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uniqueKeyPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.UniqueKeyPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die <see cref="P:Microsoft.Azure.Documents.DocumentCollection.UniqueKeyPolicy" /> gewährleisten, dass die Eindeutigkeit der Dokumente in der Auflistung in der Azure-Cosmos-DB-Dienst.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserDefinedFunctionsLink">
      <MemberSignature Language="C#" Value="public string UserDefinedFunctionsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserDefinedFunctionsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.UserDefinedFunctionsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserDefinedFunctionsLink As String" />
      <MemberSignature Language="F#" Value="member this.UserDefinedFunctionsLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.UserDefinedFunctionsLink" />
      <MemberType>Property</MemberType>
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
      <Docs>
        <summary>
            Ruft die Self-link für den Benutzer definierten Funktionen in einer Auflistung aus dem Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Der Self-link für den Benutzer definierten Funktionen in einer Auflistung.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>