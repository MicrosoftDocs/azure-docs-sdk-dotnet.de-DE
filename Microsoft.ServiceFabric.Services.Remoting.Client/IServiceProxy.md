<Type Name="IServiceProxy" FullName="Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy">
  <TypeSignature Language="C#" Value="public interface IServiceProxy" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceProxy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceProxy" />
  <TypeSignature Language="F#" Value="type IServiceProxy = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Dies ist der Client Side Basisschnittstelle für das Remoting. Das Framework bietet die Infrastruktur für den Remotezugriff für alle Dienstverträge, die von IService über ServiceRemotingListener und ServiceProxy erben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ServiceInterfaceType">
      <MemberSignature Language="C#" Value="public Type ServiceInterfaceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type ServiceInterfaceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy.ServiceInterfaceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceInterfaceType As Type" />
      <MemberSignature Language="F#" Value="member this.ServiceInterfaceType : Type" Usage="Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy.ServiceInterfaceType" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy.ServicePartitionClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePartitionClient As IServiceRemotingPartitionClient" />
      <MemberSignature Language="F#" Value="member this.ServicePartitionClient : Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingPartitionClient" Usage="Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy.ServicePartitionClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingPartitionClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Partition-Dienstclient verwendet, um die Anforderungen an den Dienst zu senden.
            </summary>
        <value>Von der ServiceProxy verwendete ServicePartitionClient</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePartitionClient2">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingPartitionClient ServicePartitionClient2 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingPartitionClient ServicePartitionClient2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy.ServicePartitionClient2" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePartitionClient2 As IServiceRemotingPartitionClient" />
      <MemberSignature Language="F#" Value="member this.ServicePartitionClient2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingPartitionClient" Usage="Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy.ServicePartitionClient2" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingPartitionClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Partition-Dienstclient verwendet, um die Anforderungen an den Dienst zu senden.
            </summary>
        <value>Von der ServiceProxy verwendete ServicePartitionClient</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>