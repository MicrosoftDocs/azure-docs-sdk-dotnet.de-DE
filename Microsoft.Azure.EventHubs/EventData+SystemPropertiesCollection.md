<Type Name="EventData+SystemPropertiesCollection" FullName="Microsoft.Azure.EventHubs.EventData+SystemPropertiesCollection">
  <TypeSignature Language="C#" Value="public sealed class EventData.SystemPropertiesCollection" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit EventData/SystemPropertiesCollection extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventData.SystemPropertiesCollection" />
  <TypeSignature Language="F#" Value="type EventData.SystemPropertiesCollection = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine Auflistung verwendet, um Eigenschaften zu speichern, die von Event Hubs-Dienst festgelegt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt Datum und Uhrzeit der gesendeten Zeit in UTC.</summary>
        <value>Die in die Warteschlange einzureihen Zeit in UTC. Dieser Wert stellt die tatsächliche Zeit des einreihen der Nachricht.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offset">
      <MemberSignature Language="C#" Value="public string Offset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.Offset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Offset As String" />
      <MemberSignature Language="F#" Value="member this.Offset : string" Usage="Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.Offset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Offset der Daten relativ zu den Event Hub-Partition-Stream ab. Der Offset ist eine Marke oder einen Bezeichner für ein Ereignis innerhalb des Event Hubs-Streams. Der Bezeichner ist eindeutig innerhalb einer Partition des Event Hubs-Streams.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string" Usage="Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Partitionsschlüssel der entsprechenden Partition, die gespeicherten der<see cref="T:Microsoft.Azure.EventHubs.EventData" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Anzahl der logischen Reihenfolge des Ereignisses innerhalb des Streams Partition des Event Hubs ab.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>