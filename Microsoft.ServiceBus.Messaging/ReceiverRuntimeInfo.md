<Type Name="ReceiverRuntimeInfo" FullName="Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo">
  <TypeSignature Language="C#" Value="public class ReceiverRuntimeInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ReceiverRuntimeInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class ReceiverRuntimeInfo" />
  <TypeSignature Language="F#" Value="type ReceiverRuntimeInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReceiverRuntimeInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastEnqueuedOffset">
      <MemberSignature Language="C#" Value="public string LastEnqueuedOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastEnqueuedOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.LastEnqueuedOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastEnqueuedOffset As String" />
      <MemberSignature Language="F#" Value="member this.LastEnqueuedOffset : string" Usage="Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.LastEnqueuedOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.LastEnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastEnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastEnqueuedTimeUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.LastEnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.LastSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.LastSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.RetrievalTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetrievalTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.RetrievalTime : DateTime" Usage="Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.RetrievalTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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