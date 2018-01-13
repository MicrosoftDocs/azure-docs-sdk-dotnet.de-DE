<Type Name="IndexingMode" FullName="Microsoft.Azure.CosmosDB.IndexingMode">
  <TypeSignature Language="C#" Value="public enum IndexingMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed IndexingMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.IndexingMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum IndexingMode" />
  <TypeSignature Language="F#" Value="type IndexingMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary> 
            Gibt den unterstützten Modi für die Volltextindizierung im Azure-Cosmos-DB-Dienst an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Consistent">
      <MemberSignature Language="C#" Value="Consistent" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.IndexingMode Consistent = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.IndexingMode.Consistent" />
      <MemberSignature Language="VB.NET" Value="Consistent" />
      <MemberSignature Language="F#" Value="Consistent = 0" Usage="Microsoft.Azure.CosmosDB.IndexingMode.Consistent" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.IndexingMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Index wird mit einer CREATE-, Update- oder Delete-Operation synchron aktualisiert.
            </summary>
        <remarks>
            Mit konsistenten Indizierung entspricht Abfrage Konsistenz der Konsistenz Standardebene für das Konto der Datenbank. Der Index wird immer mit den Daten auf dem neuesten Stand gehalten.
            
            Die Standardeinstellung IndexingMode ist konsistent.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Lazy">
      <MemberSignature Language="C#" Value="Lazy" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.IndexingMode Lazy = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.IndexingMode.Lazy" />
      <MemberSignature Language="VB.NET" Value="Lazy" />
      <MemberSignature Language="F#" Value="Lazy = 1" Usage="Microsoft.Azure.CosmosDB.IndexingMode.Lazy" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.IndexingMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Index wird in Bezug auf eine CREATE-, Update- oder Delete-Vorgang asynchron aktualisiert.
            </summary>
        <remarks>
            Bei der verzögerten Indizierung sind Abfragen letztendlich konsistent. Der Index wird aktualisiert, wenn die Auflistung unterhalb vollständige Durchsatzkapazität (anforderungseinheiten pro Sekunde) ausgeführt wird. 
            
            Schreibvorgänge belegt weniger anforderungseinheiten (RequestCharge) zum Zeitpunkt der schreiben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.IndexingMode None = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.IndexingMode.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 2" Usage="Microsoft.Azure.CosmosDB.IndexingMode.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.IndexingMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Es ist kein Index bereitgestellt.
            </summary>
        <remarks>
            Festlegen von IndexingMode auf "None" löscht den Index. Verwenden Sie diese Option, wenn nicht der Index für eine Dokumentsammlung sparen die Speicherkosten für oder verbessern den Durchsatz beim Schreiben beibehalten werden sollen. Die Abfragen werden an Scans der gesamten Auflistung degenerierte.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>