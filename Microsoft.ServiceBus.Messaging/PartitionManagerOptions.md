<Type Name="PartitionManagerOptions" FullName="Microsoft.ServiceBus.Messaging.PartitionManagerOptions">
  <TypeSignature Language="C#" Value="public class PartitionManagerOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PartitionManagerOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.PartitionManagerOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class PartitionManagerOptions" />
  <TypeSignature Language="F#" Value="type PartitionManagerOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt die Optionen, die verschiedene Aspekte der Partition Verteilung, die innerhalb von steuern die <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> Instanz.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionManagerOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.PartitionManagerOptions" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireInterval">
      <MemberSignature Language="C#" Value="public TimeSpan AcquireInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AcquireInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.AcquireInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property AcquireInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AcquireInterval : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.PartitionManagerOptions.AcquireInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt das Zeitintervall fest, an dem die <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> Instanz startet eine Aufgabe, um zu bestimmen, ob Partitionen auf bekannte Hostinstanzen gleichmäßig verteilt sind.</summary>
        <value>Das Zeitintervall für das Abrufen der Partition.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultOptions">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.PartitionManagerOptions DefaultOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.ServiceBus.Messaging.PartitionManagerOptions DefaultOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.DefaultOptions" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DefaultOptions As PartitionManagerOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultOptions : Microsoft.ServiceBus.Messaging.PartitionManagerOptions" Usage="Microsoft.ServiceBus.Messaging.PartitionManagerOptions.DefaultOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.PartitionManagerOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Erstellt eine Instanz des <see cref="P:Microsoft.ServiceBus.Messaging.EventProcessorHost.PartitionManagerOptions" /> mit den folgenden Standardwerten:<see cref="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.RenewInterval" />: 10 Sekunden.<see cref="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.AcquireInterval" />: 10 Sekunden.<see cref="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.LeaseInterval" />: 30 Sekunden. </summary>
        <value>Partitions-Manager Standardoptionen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseInterval">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.LeaseInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseInterval : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.PartitionManagerOptions.LeaseInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt das Intervall an, an dem die Lease für eine Azure-Blob, eine Partition des Event Hubs darstellt, erstellt wird. Wenn die Lease ist innerhalb dieses Zeitraums nicht erneuert, Ablauf und übergibt den Besitz der Partition in eine andere <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> Instanz.</summary>
        <value>Gibt <see cref="T:System.TimeSpan" />zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceiveClients">
      <MemberSignature Language="C#" Value="public int MaxReceiveClients { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxReceiveClients" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.MaxReceiveClients" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceiveClients As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxReceiveClients : int with get, set" Usage="Microsoft.ServiceBus.Messaging.PartitionManagerOptions.MaxReceiveClients" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewInterval">
      <MemberSignature Language="C#" Value="public TimeSpan RenewInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RenewInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.RenewInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RenewInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RenewInterval : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.PartitionManagerOptions.RenewInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt das Erneuerungsintervall, das für alle Leases für Partitionen, die derzeit von aufrecht erhalten die <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> Instanz.</summary>
        <value>Das Intervall, das die Partition zu erneuern.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkipBlobContainerCreation">
      <MemberSignature Language="C#" Value="public bool SkipBlobContainerCreation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SkipBlobContainerCreation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.SkipBlobContainerCreation" />
      <MemberSignature Language="VB.NET" Value="Public Property SkipBlobContainerCreation As Boolean" />
      <MemberSignature Language="F#" Value="member this.SkipBlobContainerCreation : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.PartitionManagerOptions.SkipBlobContainerCreation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>