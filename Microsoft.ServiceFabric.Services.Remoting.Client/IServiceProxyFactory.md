<Type Name="IServiceProxyFactory" FullName="Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxyFactory">
  <TypeSignature Language="C#" Value="public interface IServiceProxyFactory" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceProxyFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxyFactory" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceProxyFactory" />
  <TypeSignature Language="F#" Value="type IServiceProxyFactory = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c7f6a-101">Gibt die Schnittstelle für die Factory, die Proxys für die Remotekommunikation an den angegebenen Dienst erstellt.</span><span class="sxs-lookup"><span data-stu-id="c7f6a-101">Specifies the interface for the factory that creates proxies for remote communication to the specified service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey = null, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector = Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxyFactory.CreateServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceProxy : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="iServiceProxyFactory.CreateServiceProxy (serviceUri, partitionKey, targetReplicaSelector, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TServiceInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TServiceInterface">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="targetReplicaSelector" Type="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TServiceInterface">To be added.</typeparam>
        <param name="serviceUri">To be added.</param>
        <param name="partitionKey">To be added.</param>
        <param name="targetReplicaSelector">To be added.</param>
        <param name="listenerName">To be added.</param>
        <summary>
            <span data-ttu-id="c7f6a-102">Erstellt einen Proxy zur Kommunikation mit den angegebenen Dienst mithilfe der Remote-Benutzeroberfläche TServiceInterface, die der Dienst implementiert.</span><span class="sxs-lookup"><span data-stu-id="c7f6a-102">Creates a proxy to communicate to the specified service using the remoted interface TServiceInterface that the service implements.</span></span>
            <span data-ttu-id="c7f6a-103"><typeparam name="TServiceInterface">Die Schnittstelle, die Remote ausgeführt wird. </typeparam> <param name="serviceUri">Der Uri des Diensts.</param> <param name="partitionKey">Die Partitionsschlüssel, der bestimmt, welche Dienstpartition zur Verarbeitung von Anforderungen von diesem Dienstproxy zuständig ist. </param> <param name="targetReplicaSelector">Bestimmt, welches Replikat oder eine Instanz von der Dienstpartition auf der Client muss eine Verbindung mit.</param> <param name="listenerName">Dieser Parameter ist Optional, wenn der Dienst über einen einzelnen Kommunikation Listener verfügt. Die Endpunkte des Diensts sind, im Format {"Endpunkte": {"Listener1": "Endpoint1", "Listener2": "Endpoint2"...}}. Wenn der Dienst mehrere Endpunkte verfügbar macht, identifiziert dieser Parameter die dieser Endpunkte für das Remoting-Kommunikation verwenden. </param><returns>Der Proxy, der die Schnittstelle implementiert, die Remote ausgeführt wird. Das zurückgegebene Objekt auch IServiceProxy-Schnittstelle implementieren.</returns></span><span class="sxs-lookup"><span data-stu-id="c7f6a-103"><typeparam name="TServiceInterface">The interface that is being remoted.</typeparam><param name="serviceUri">The Uri of the Service.</param><param name="partitionKey">The Partition key that determines which service partition is responsible for handling requests from this service proxy.</param><param name="targetReplicaSelector">Determines which replica or instance of the service partition the client should connect to.</param><param name="listenerName">This parameter is Optional if the service has a single communication listener. The endpoints from the service are of the form {"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}. When the service exposes multiple endpoints, this parameter identifies which of those endpoints to use for the remoting communication. </param><returns>The proxy that implement the interface that is being remoted. The returned object also implement IServiceProxy interface.</returns></span></span></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>