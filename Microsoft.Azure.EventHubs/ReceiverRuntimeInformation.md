<Type Name="ReceiverRuntimeInformation" FullName="Microsoft.Azure.EventHubs.ReceiverRuntimeInformation">
  <TypeSignature Language="C#" Value="public class ReceiverRuntimeInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ReceiverRuntimeInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class ReceiverRuntimeInformation" />
  <TypeSignature Language="F#" Value="type ReceiverRuntimeInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt die ungefähre Empfänger Laufzeitinformationen für eine logische Partition eines Event Hubs dar.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="LastEnqueuedOffset">
      <MemberSignature Language="C#" Value="public string LastEnqueuedOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastEnqueuedOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.LastEnqueuedOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastEnqueuedOffset As String" />
      <MemberSignature Language="F#" Value="member this.LastEnqueuedOffset : string" Usage="Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.LastEnqueuedOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Offset des letzten Ereignisses in die Warteschlange eingereiht.</summary>
        <value>Der Offset des letzten Ereignisses in die Warteschlange eingereiht.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastEnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastEnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastEnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.LastEnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastEnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastEnqueuedTimeUtc : DateTime" Usage="Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.LastEnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die in die Warteschlange eingereihten UTC-Zeit des letzten Ereignisses ab.</summary>
        <value>Die in die Warteschlange eingereihten Zeit des letzten Ereignisses.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.LastSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastSequenceNumber : int64" Usage="Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.LastSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die letzte Sequenznummer des Ereignisses innerhalb des Streams Partition des Event Hubs ab.</summary>
        <value>Die Anzahl der logischen Reihenfolge des Ereignisses.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Partitions-ID für eine logische Partition einen Event Hub ab.</summary>
        <value>Die Partitions-ID.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrievalTime">
      <MemberSignature Language="C#" Value="public DateTime RetrievalTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime RetrievalTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.RetrievalTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetrievalTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.RetrievalTime : DateTime" Usage="Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.RetrievalTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Zeitpunkt der bei der Laufzeitinformationen abgerufen wurde.</summary>
        <value>Die in die Warteschlange eingereihten Zeit des letzten Ereignisses.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>