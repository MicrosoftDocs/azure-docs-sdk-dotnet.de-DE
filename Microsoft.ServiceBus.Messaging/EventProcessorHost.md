<Type Name="EventProcessorHost" FullName="Microsoft.ServiceBus.Messaging.EventProcessorHost">
  <TypeSignature Language="C#" Value="public class EventProcessorHost : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventProcessorHost extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" />
  <TypeSignature Language="VB.NET" Value="Public Class EventProcessorHost&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type EventProcessorHost = class&#xA;    interface IPartitionObserver&lt;BlobLease&gt;&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>Stellt einen Host für die Verarbeitung von Ereignisdaten für Event Hubs dar.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (eventHubPath As String, consumerGroupName As String, eventHubConnectionString As String, storageConnectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventProcessorHost : string * string * string * string -&gt; Microsoft.ServiceBus.Messaging.EventProcessorHost" Usage="new Microsoft.ServiceBus.Messaging.EventProcessorHost (eventHubPath, consumerGroupName, eventHubConnectionString, storageConnectionString)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubConnectionString" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">To be added.</param>
        <param name="consumerGroupName">To be added.</param>
        <param name="eventHubConnectionString">To be added.</param>
        <param name="storageConnectionString">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string hostName, string eventHubPath, string consumerGroupName, Func&lt;Microsoft.ServiceBus.Messaging.EventProcessorOptions,Microsoft.ServiceBus.Messaging.MessagingFactory&gt; eventHubClientFactory, Func&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient&gt; storageClientFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string eventHubPath, string consumerGroupName, class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.EventProcessorOptions, class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; eventHubClientFactory, class System.Func`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient&gt; storageClientFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.#ctor(System.String,System.String,System.String,System.Func{Microsoft.ServiceBus.Messaging.EventProcessorOptions,Microsoft.ServiceBus.Messaging.MessagingFactory},System.Func{Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, eventHubPath As String, consumerGroupName As String, eventHubClientFactory As Func(Of EventProcessorOptions, MessagingFactory), storageClientFactory As Func(Of CloudBlobClient))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventProcessorHost : string * string * string * Func&lt;Microsoft.ServiceBus.Messaging.EventProcessorOptions, Microsoft.ServiceBus.Messaging.MessagingFactory&gt; * Func&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient&gt; -&gt; Microsoft.ServiceBus.Messaging.EventProcessorHost" Usage="new Microsoft.ServiceBus.Messaging.EventProcessorHost (hostName, eventHubPath, consumerGroupName, eventHubClientFactory, storageClientFactory)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubClientFactory" Type="System.Func&lt;Microsoft.ServiceBus.Messaging.EventProcessorOptions,Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" />
        <Parameter Name="storageClientFactory" Type="System.Func&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient&gt;" />
      </Parameters>
      <Docs>
        <param name="hostName">To be added.</param>
        <param name="eventHubPath">To be added.</param>
        <param name="consumerGroupName">To be added.</param>
        <param name="eventHubClientFactory">To be added.</param>
        <param name="storageClientFactory">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, eventHubPath As String, consumerGroupName As String, eventHubConnectionString As String, storageConnectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventProcessorHost : string * string * string * string * string -&gt; Microsoft.ServiceBus.Messaging.EventProcessorHost" Usage="new Microsoft.ServiceBus.Messaging.EventProcessorHost (hostName, eventHubPath, consumerGroupName, eventHubConnectionString, storageConnectionString)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubConnectionString" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">Der Name des der <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> Instanz. Dieser Name muss für jede Instanz des Hosts eindeutig sein.</param>
        <param name="eventHubPath">Der Pfad an den Event Hub aus dem Empfang von Ereignisdaten starten.</param>
        <param name="consumerGroupName">Der Name des Event Hubs-Consumer-Gruppe aus dem Empfang von Ereignisdaten starten.</param>
        <param name="eventHubConnectionString">Die Verbindungszeichenfolge für den Event Hub.</param>
        <param name="storageConnectionString">Die Verbindungszeichenfolge für das Azure-Blob-Speicherkonto für die Verteilung der Partition verwendet werden soll.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string hostName, string eventHubPath, string consumerGroupName, Func&lt;Microsoft.ServiceBus.Messaging.EventProcessorOptions,Microsoft.ServiceBus.Messaging.MessagingFactory&gt; eventHubClientFactory, Func&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient&gt; storageClientFactory, string leaseContainerName, string leaseBlobPrefix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string eventHubPath, string consumerGroupName, class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.EventProcessorOptions, class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; eventHubClientFactory, class System.Func`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient&gt; storageClientFactory, string leaseContainerName, string leaseBlobPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.#ctor(System.String,System.String,System.String,System.Func{Microsoft.ServiceBus.Messaging.EventProcessorOptions,Microsoft.ServiceBus.Messaging.MessagingFactory},System.Func{Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, eventHubPath As String, consumerGroupName As String, eventHubClientFactory As Func(Of EventProcessorOptions, MessagingFactory), storageClientFactory As Func(Of CloudBlobClient), leaseContainerName As String, Optional leaseBlobPrefix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventProcessorHost : string * string * string * Func&lt;Microsoft.ServiceBus.Messaging.EventProcessorOptions, Microsoft.ServiceBus.Messaging.MessagingFactory&gt; * Func&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient&gt; * string * string -&gt; Microsoft.ServiceBus.Messaging.EventProcessorHost" Usage="new Microsoft.ServiceBus.Messaging.EventProcessorHost (hostName, eventHubPath, consumerGroupName, eventHubClientFactory, storageClientFactory, leaseContainerName, leaseBlobPrefix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubClientFactory" Type="System.Func&lt;Microsoft.ServiceBus.Messaging.EventProcessorOptions,Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" />
        <Parameter Name="storageClientFactory" Type="System.Func&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient&gt;" />
        <Parameter Name="leaseContainerName" Type="System.String" />
        <Parameter Name="leaseBlobPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">To be added.</param>
        <param name="eventHubPath">To be added.</param>
        <param name="consumerGroupName">To be added.</param>
        <param name="eventHubClientFactory">To be added.</param>
        <param name="storageClientFactory">To be added.</param>
        <param name="leaseContainerName">To be added.</param>
        <param name="leaseBlobPrefix">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString, string leaseContainerName, string leaseBlobPrefix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString, string leaseContainerName, string leaseBlobPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, eventHubPath As String, consumerGroupName As String, eventHubConnectionString As String, storageConnectionString As String, leaseContainerName As String, Optional leaseBlobPrefix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventProcessorHost : string * string * string * string * string * string * string -&gt; Microsoft.ServiceBus.Messaging.EventProcessorHost" Usage="new Microsoft.ServiceBus.Messaging.EventProcessorHost (hostName, eventHubPath, consumerGroupName, eventHubConnectionString, storageConnectionString, leaseContainerName, leaseBlobPrefix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubConnectionString" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
        <Parameter Name="leaseContainerName" Type="System.String" />
        <Parameter Name="leaseBlobPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">To be added.</param>
        <param name="eventHubPath">To be added.</param>
        <param name="consumerGroupName">To be added.</param>
        <param name="eventHubConnectionString">To be added.</param>
        <param name="storageConnectionString">To be added.</param>
        <param name="leaseContainerName">To be added.</param>
        <param name="leaseBlobPrefix">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="eventProcessorHost.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="eventProcessorHost.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorHost.HostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string" Usage="Microsoft.ServiceBus.Messaging.EventProcessorHost.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Hostnamen, also einen eindeutigen Namen für die <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> Instanz.</summary>
        <value>Der Hostname.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionManagerOptions">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.PartitionManagerOptions PartitionManagerOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.PartitionManagerOptions PartitionManagerOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorHost.PartitionManagerOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionManagerOptions As PartitionManagerOptions" />
      <MemberSignature Language="F#" Value="member this.PartitionManagerOptions : Microsoft.ServiceBus.Messaging.PartitionManagerOptions with get, set" Usage="Microsoft.ServiceBus.Messaging.EventProcessorHost.PartitionManagerOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.PartitionManagerOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt ihn fest der <see cref="T:Microsoft.ServiceBus.Messaging.PartitionManagerOptions" /> Instanz verwendet werden, indem die <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> Objekt.</summary>
        <value>Die <see cref="T:Microsoft.ServiceBus.Messaging.PartitionManagerOptions" />-Instanz.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;T&gt; () where T : Microsoft.ServiceBus.Messaging.IEventProcessor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;(class Microsoft.ServiceBus.Messaging.IEventProcessor) T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.RegisterEventProcessorAsync``1" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorAsync(Of T As IEventProcessor) () As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorAsync : unit -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.ServiceBus.Messaging.IEventProcessor)" Usage="eventProcessorHost.RegisterEventProcessorAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceBus.Messaging.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">Implementierung von Ihrer anwendungsspezifischen <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</typeparam>
        <summary>Asynchron registriert die <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> schnittstellenimplementierung mit dem Host mit der <see cref="T:Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory`1" /> Factory. Diese Methode startet den Host auch und ihn auf Einbeziehung in die Partition Verteilungsprozess start ermöglicht.</summary>
        <returns>Eine Aufgabe zeigt an, dass die <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> wurde gestartet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;T&gt; (Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) where T : Microsoft.ServiceBus.Messaging.IEventProcessor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;(class Microsoft.ServiceBus.Messaging.IEventProcessor) T&gt;(class Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.RegisterEventProcessorAsync``1(Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorAsync(Of T As IEventProcessor) (processorOptions As EventProcessorOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorAsync : Microsoft.ServiceBus.Messaging.EventProcessorOptions -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.ServiceBus.Messaging.IEventProcessor)" Usage="eventProcessorHost.RegisterEventProcessorAsync processorOptions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceBus.Messaging.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="processorOptions" Type="Microsoft.ServiceBus.Messaging.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">Implementierung von Ihrer anwendungsspezifischen <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</typeparam>
        <param name="processorOptions">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> Objekt, das steuert verschiedene Aspekte der Datapump Ereignis erstellt, wenn es sich bei den Besitz für eine bestimmte Partition des Event Hubs abgerufen wird.</param>
        <summary>Asynchron registriert die <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> schnittstellenimplementierung mit dem Host mit der <see cref="T:Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory`1" /> Factory. Diese Methode startet den Host auch und ihn auf Einbeziehung in die Partition Verteilungsprozess start ermöglicht.</summary>
        <returns>Eine Aufgabe zeigt an, dass die <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> wurde gestartet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync (Microsoft.ServiceBus.Messaging.IEventProcessorFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync(class Microsoft.ServiceBus.Messaging.IEventProcessorFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.RegisterEventProcessorFactoryAsync(Microsoft.ServiceBus.Messaging.IEventProcessorFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorFactoryAsync (factory As IEventProcessorFactory) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorFactoryAsync : Microsoft.ServiceBus.Messaging.IEventProcessorFactory -&gt; System.Threading.Tasks.Task" Usage="eventProcessorHost.RegisterEventProcessorFactoryAsync factory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />
      </Parameters>
      <Docs>
        <param name="factory">Die Factory zum Registrieren.</param>
        <summary>Asynchron registriert die Ereignis-Prozessor-Factory.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync (Microsoft.ServiceBus.Messaging.IEventProcessorFactory factory, Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync(class Microsoft.ServiceBus.Messaging.IEventProcessorFactory factory, class Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.RegisterEventProcessorFactoryAsync(Microsoft.ServiceBus.Messaging.IEventProcessorFactory,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorFactoryAsync (factory As IEventProcessorFactory, processorOptions As EventProcessorOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorFactoryAsync : Microsoft.ServiceBus.Messaging.IEventProcessorFactory * Microsoft.ServiceBus.Messaging.EventProcessorOptions -&gt; System.Threading.Tasks.Task" Usage="eventProcessorHost.RegisterEventProcessorFactoryAsync (factory, processorOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />
        <Parameter Name="processorOptions" Type="Microsoft.ServiceBus.Messaging.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <param name="factory">Die Factory zum Registrieren.</param>
        <param name="processorOptions">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> Objekt, das steuert verschiedene Aspekte der Datapump Ereignis erstellt, wenn es sich bei den Besitz für eine bestimmte Partition des Event Hubs abgerufen wird.</param>
        <summary>Asynchron registriert die Ereignis-Prozessor-Factory.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAllConnections">
      <MemberSignature Language="C#" Value="public void ResetAllConnections ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResetAllConnections() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.ResetAllConnections" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResetAllConnections ()" />
      <MemberSignature Language="F#" Value="member this.ResetAllConnections : unit -&gt; unit" Usage="eventProcessorHost.ResetAllConnections " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetConnection">
      <MemberSignature Language="C#" Value="public void ResetConnection (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResetConnection(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.ResetConnection(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResetConnection (partitionId As String)" />
      <MemberSignature Language="F#" Value="member this.ResetConnection : string -&gt; unit" Usage="eventProcessorHost.ResetConnection partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterEventProcessorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnregisterEventProcessorAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnregisterEventProcessorAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.UnregisterEventProcessorAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function UnregisterEventProcessorAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.UnregisterEventProcessorAsync : unit -&gt; System.Threading.Tasks.Task" Usage="eventProcessorHost.UnregisterEventProcessorAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceBus.Messaging.EventProcessorHost/&lt;UnregisterEventProcessorAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Asynchron fährt die <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> Instanz. Diese Methode verwaltet die Leasedauer für alle Partitionen, die derzeit aufrecht erhalten werden und ermöglicht es, jede <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> Instanz zum ordnungsgemäßen Herunterfahren durch den Aufruf der <see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.CloseAsync(Microsoft.ServiceBus.Messaging.PartitionContext,Microsoft.ServiceBus.Messaging.CloseReason)" /> Methode mit einem <see cref="F:Microsoft.ServiceBus.Messaging.CloseReason.Shutdown" /> Objekt.</summary>
        <returns>Eine Aufgabe, die gibt an die <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> Instanz beendet wurde.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>