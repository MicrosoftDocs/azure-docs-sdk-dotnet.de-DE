<Type Name="PartitionRuntimeInformation" FullName="Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation">
  <TypeSignature Language="C#" Value="public class PartitionRuntimeInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PartitionRuntimeInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class PartitionRuntimeInformation" />
  <TypeSignature Language="F#" Value="type PartitionRuntimeInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt die ungefähre Laufzeitinformationen für eine logische Partition eines Event Hubs dar.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionRuntimeInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation.#ctor" />
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
    <Member MemberName="BeginSequenceNumber">
      <MemberSignature Language="C#" Value="public long BeginSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 BeginSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation.BeginSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BeginSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.BeginSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation.BeginSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Begin-Sequenznummer ab.</summary>
        <value>Die Begin-Sequenznummer.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubPath">
      <MemberSignature Language="C#" Value="public string EventHubPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation.EventHubPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubPath As String" />
      <MemberSignature Language="F#" Value="member this.EventHubPath : string" Usage="Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation.EventHubPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Pfad des Event Hubs.</summary>
        <value>Der Pfad des Event Hubs.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastEnqueuedOffset">
      <MemberSignature Language="C#" Value="public string LastEnqueuedOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastEnqueuedOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation.LastEnqueuedOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastEnqueuedOffset As String" />
      <MemberSignature Language="F#" Value="member this.LastEnqueuedOffset : string" Usage="Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation.LastEnqueuedOffset" />
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
    <Member MemberName="LastEnqueuedSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastEnqueuedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastEnqueuedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation.LastEnqueuedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastEnqueuedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastEnqueuedSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation.LastEnqueuedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die End-Sequenznummer ab.</summary>
        <value>Die End-Sequenznummer.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastEnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastEnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastEnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation.LastEnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastEnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastEnqueuedTimeUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation.LastEnqueuedTimeUtc" />
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
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation.PartitionId" />
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
  </Members>
</Type>