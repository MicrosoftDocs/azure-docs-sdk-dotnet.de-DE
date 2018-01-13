<Type Name="ServiceProxy" FullName="Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxy">
  <TypeSignature Language="C#" Value="public abstract class ServiceProxy : Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase, Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceProxy extends Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase implements class Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxy" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceProxy&#xA;Inherits ProxyBase&#xA;Implements IServiceProxy" />
  <TypeSignature Language="F#" Value="type ServiceProxy = class&#xA;    inherit ProxyBase&#xA;    interface IServiceProxy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt die basisimplementierung für den Proxy zu den Remote IService-Schnittstellen bereit.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ServiceProxy ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public static TServiceInterface Create&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey = null, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector = Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TServiceInterface Create&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxy.Create``1(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxy.Create (serviceUri, partitionKey, targetReplicaSelector, listenerName)" />
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
            Erstellt einen Proxy zur Kommunikation mit den angegebenen Dienst mithilfe der Remote-Benutzeroberfläche TServiceInterface, die der Dienst implementiert.
            <typeparam name="TServiceInterface">Schnittstelle, die Remoteausführung wird</typeparam><param name="serviceUri">Uri des Diensts.</param> <param name="partitionKey">Die Partitionsschlüssel, der bestimmt, welche Dienstpartition zur Verarbeitung von Anforderungen von diesem Dienstproxy zuständig ist</param><param name="targetReplicaSelector">bestimmt, welches Replikat oder eine Instanz von der Dienstpartition der Client eine Verbindung herstellen soll An. </param> <param name="listenerName">Dieser Parameter ist Optional, wenn der Dienst über einen einzelnen Kommunikation Listener verfügt. Die Endpunkte des Diensts sind, im Format {"Endpunkte": {"Listener1": "Endpoint1", "Listener2": "Endpoint2"...}}. Wenn der Dienst mehrere Endpunkte verfügbar macht, identifiziert dieser Parameter die dieser Endpunkte für das Remoting-Kommunikation verwenden. </param><returns>Der Proxy, der die Schnittstelle implementiert, die Remote ausgeführt wird. Das zurückgegebene Objekt auch implementieren <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> Schnittstelle.</returns></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceInterfaceType">
      <MemberSignature Language="C#" Value="public Type ServiceInterfaceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type ServiceInterfaceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxy.ServiceInterfaceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceInterfaceType As Type" />
      <MemberSignature Language="F#" Value="member this.ServiceInterfaceType : Type" Usage="Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxy.ServiceInterfaceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Schnittstellentyp, der Remote ausgeführt wird.
            </summary>
        <value>Diensttyp-Schnittstelle</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePartitionClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingPartitionClient ServicePartitionClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingPartitionClient ServicePartitionClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxy.ServicePartitionClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePartitionClient As IServiceRemotingPartitionClient" />
      <MemberSignature Language="F#" Value="member this.ServicePartitionClient : Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingPartitionClient" Usage="Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxy.ServicePartitionClient" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy.ServicePartitionClient</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingPartitionClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die V1-Partition-Dienstclient verwendet, um die Anforderungen an den Dienst zu senden.
            </summary>
        <value>Von der ServiceProxy verwendete ServicePartitionClient</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePartitionClient2">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingPartitionClient ServicePartitionClient2 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingPartitionClient ServicePartitionClient2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxy.ServicePartitionClient2" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePartitionClient2 As IServiceRemotingPartitionClient" />
      <MemberSignature Language="F#" Value="member this.ServicePartitionClient2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingPartitionClient" Usage="Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxy.ServicePartitionClient2" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy.ServicePartitionClient2</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingPartitionClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die V2-Partition-Dienstclient verwendet, um die Anforderungen an den Dienst zu senden.
            </summary>
        <value>Von der ServiceProxy verwendete ServicePartitionClient</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>