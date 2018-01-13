<Type Name="ServiceProxyFactory" FullName="Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory">
  <TypeSignature Language="C#" Value="public class ServiceProxyFactory : Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxyFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceProxyFactory extends System.Object implements class Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxyFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceProxyFactory&#xA;Implements IServiceProxyFactory" />
  <TypeSignature Language="F#" Value="type ServiceProxyFactory = class&#xA;    interface IServiceProxyFactory" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxyFactory</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Gibt an, die Factory, die Proxys für die Remotekommunikation an den angegebenen Dienst erstellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceProxyFactory (Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory.#ctor(Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory : Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" Usage="new Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory retrySettings" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="retrySettings">To be added.</param>
        <summary>
            Instanziiert die ServiceProxyFactory mit der angegebenen Retrysettings und Standard-remotingClientFactory
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceProxyFactory (Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient, class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory.#ctor(System.Func{Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory},Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createServiceRemotingClientFactory As Func(Of IServiceRemotingCallbackClient, IServiceRemotingClientFactory), Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory : Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient, Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" Usage="new Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory (createServiceRemotingClientFactory, retrySettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createServiceRemotingClientFactory" Type="System.Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt;" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="createServiceRemotingClientFactory">
            Gibt die Factorymethode, die Remoting-Client-Factory erstellt. Die Client-Remoting-Factory erhalten haben, von dieser Methode wird in der ServiceProxyFactory zwischengespeichert.
            </param>
        <param name="retrySettings">Gibt an, die wiederholungsrichtlinie für Ausnahmen, die bei der Verwendung der von dieser Factory erstellte Proxys verwenden</param>
        <summary>
            Instanziiert die ServiceProxyFactory mit dem angegebenen V1 Remoting-Factory und Retrysettings an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceProxyFactory (Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler, class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory.#ctor(System.Func{Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory},Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createServiceRemotingClientFactory As Func(Of IServiceRemotingCallbackMessageHandler, IServiceRemotingClientFactory), Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory : Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler, Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" Usage="new Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory (createServiceRemotingClientFactory, retrySettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createServiceRemotingClientFactory" Type="System.Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt;" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="createServiceRemotingClientFactory">
            Gibt die Factorymethode, die Remoting-Client-Factory erstellt. Die Client-Remoting-Factory erhalten haben, von dieser Methode wird in der ServiceProxyFactory zwischengespeichert.
            </param>
        <param name="retrySettings">Gibt an, die wiederholungsrichtlinie für Ausnahmen, die bei der Verwendung der von dieser Factory erstellte Proxys verwenden</param>
        <summary>
            Instanziiert die ServiceProxyFactory mit dem angegebenen V2 Remoting-Factory und Retrysettings an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNonIServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateNonIServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey = null, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector = Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica, string listenerName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!TServiceInterface CreateNonIServiceProxy&lt;TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory.CreateNonIServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String)" />
      <MemberSignature Language="F#" Value="member this.CreateNonIServiceProxy : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string -&gt; 'ServiceInterface" Usage="serviceProxyFactory.CreateNonIServiceProxy (serviceUri, partitionKey, targetReplicaSelector, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TServiceInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TServiceInterface" />
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
            Erstellt einen Proxy zur Kommunikation mit den angegebenen Dienst mithilfe der Remote-Benutzeroberfläche TServiceInterface, die der Dienst implementiert.
            <typeparam name="TServiceInterface">Schnittstelle, die Remote ausgeführt wird. Dienstschnittstelle muss nicht IService geerbt werden. </typeparam> <param name="serviceUri">Uri des Diensts.</param> <param name="partitionKey">Die Partitionsschlüssel, der bestimmt, welche Dienstpartition zur Verarbeitung von Anforderungen von diesem Dienstproxy zuständig ist</param><param name="targetReplicaSelector">bestimmt, welches Replikat oder eine Instanz von der Dienstpartition auf der Client muss eine Verbindung mit.</param> <param name="listenerName">Dieser Parameter ist Optional, wenn der Dienst über einen einzelnen Kommunikation Listener verfügt. Die Endpunkte des Diensts sind, im Format {"Endpunkte": {"Listener1": "Endpoint1", "Listener2": "Endpoint2"...}}. Wenn der Dienst mehrere Endpunkte verfügbar macht, identifiziert dieser Parameter die dieser Endpunkte für das Remoting-Kommunikation verwenden. </param><returns>Der Proxy, der die Schnittstelle implementiert, die Remote ausgeführt wird. Das zurückgegebene Objekt auch implementieren <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> Schnittstelle.</returns></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey = null, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector = Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory.CreateServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceProxy : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)&#xA;override this.CreateServiceProxy : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="serviceProxyFactory.CreateServiceProxy (serviceUri, partitionKey, targetReplicaSelector, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxyFactory.CreateServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String)</InterfaceMember>
      </Implements>
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
            Erstellt einen Proxy zur Kommunikation mit den angegebenen Dienst mithilfe der Remote-Benutzeroberfläche TServiceInterface, die der Dienst implementiert.
            <typeparam name="TServiceInterface">Schnittstelle, die Remoteausführung wird</typeparam><param name="serviceUri">Uri des Diensts.</param> <param name="partitionKey">Die Partitionsschlüssel, der bestimmt, welche Dienstpartition zur Verarbeitung von Anforderungen von diesem Dienstproxy zuständig ist</param><param name="targetReplicaSelector">bestimmt, welches Replikat oder eine Instanz von der Dienstpartition der Client eine Verbindung herstellen soll An. </param> <param name="listenerName">Dieser Parameter ist Optional, wenn der Dienst über einen einzelnen Kommunikation Listener verfügt. Die Endpunkte des Diensts sind, im Format {"Endpunkte": {"Listener1": "Endpoint1", "Listener2": "Endpoint2"...}}. Wenn der Dienst mehrere Endpunkte verfügbar macht, identifiziert dieser Parameter die dieser Endpunkte für das Remoting-Kommunikation verwenden. </param><returns>Der Proxy, der die Schnittstelle implementiert, die Remote ausgeführt wird. Das zurückgegebene Objekt auch implementieren <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> Schnittstelle.</returns></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>