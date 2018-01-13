<Type Name="IWithExistingSubnet" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithExistingSubnet">
  <TypeSignature Language="C#" Value="public interface IWithExistingSubnet : Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Update.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExistingSubnet implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Update.IWithSubnet`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithExistingSubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExistingSubnet&#xA;Implements IWithSubnet(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IWithExistingSubnet = interface&#xA;    interface IWithSubnet&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Update.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Die Phase der eine Anwendung Gateway Update festlegen, dass das Subnetz angeben wird das app-Gateway seine private IP-Adresse aus abrufen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.ISubnet subnet);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.ISubnet subnet) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithExistingSubnet.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.ISubnet)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (subnet As ISubnet) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.ISubnet -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithExistingSubnet.WithExistingSubnet subnet" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.Network.Fluent.ISubnet" />
      </Parameters>
      <Docs>
        <param name="subnet">Einem vorhandenen Subnetz.</param>
        <summary>
            Gibt an, dass das Subnetz das Anwendungsgateway ruft seine private IP-Adresse aus ab.
            Dadurch wird eine neue IP-Konfiguration erstellt, wenn sie nicht bereits vorhanden ist.
            Private (intern) Front-Ends, wird wenn alle aktiviert haben, konfiguriert werden ebenfalls dieses Subnetz verwendet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithExistingSubnet.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.INetwork,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (network As INetwork, subnetName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.INetwork * string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithExistingSubnet.WithExistingSubnet (network, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="network">Das virtuelle Netzwerk-Subnetz gehört.</param>
        <param name="subnetName">Der Name eines Subnetzes innerhalb des ausgewählten Netzwerks.</param>
        <summary>
            Gibt an, dass das Subnetz das Anwendungsgateway ruft seine private IP-Adresse aus ab.
            Dadurch wird eine neue IP-Konfiguration erstellt, wenn sie nicht bereits vorhanden ist.
            Private (intern) Front-Ends, wird wenn alle aktiviert haben, konfiguriert werden ebenfalls dieses Subnetz verwendet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>