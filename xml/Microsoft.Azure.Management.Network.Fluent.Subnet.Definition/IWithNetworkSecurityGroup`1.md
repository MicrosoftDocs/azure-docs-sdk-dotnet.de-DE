<Type Name="IWithNetworkSecurityGroup&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithNetworkSecurityGroup&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNetworkSecurityGroup&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNetworkSecurityGroup`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithNetworkSecurityGroup`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNetworkSecurityGroup(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithNetworkSecurityGroup&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="a0424-101">Der übergeordnete Typ.</span><span class="sxs-lookup"><span data-stu-id="a0424-101">The parent type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="a0424-102">Die Phase der subnetzdefinition ermöglicht die Netzwerksicherheitsgruppe zum Subnetz zugewiesen an.</span><span class="sxs-lookup"><span data-stu-id="a0424-102">The stage of the subnet definition allowing to specify the network security group to assign to the subnet.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingNetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach&lt;ParentT&gt; WithExistingNetworkSecurityGroup (Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup nsg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach`1&lt;!ParentT&gt; WithExistingNetworkSecurityGroup(class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup nsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithNetworkSecurityGroup`1.WithExistingNetworkSecurityGroup(Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingNetworkSecurityGroup (nsg As INetworkSecurityGroup) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingNetworkSecurityGroup : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithNetworkSecurityGroup.WithExistingNetworkSecurityGroup nsg" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nsg" Type="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup" />
      </Parameters>
      <Docs>
        <param name="nsg"><span data-ttu-id="a0424-103">Die Netzwerksicherheitsgruppe zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="a0424-103">The network security group to assign.</span></span></param>
        <summary>
            <span data-ttu-id="a0424-104">Dieses Subnetz wird eine vorhandene Netzwerksicherheitsgruppe zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="a0424-104">Assigns an existing network security group to this subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a0424-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="a0424-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingNetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach&lt;ParentT&gt; WithExistingNetworkSecurityGroup (string resourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach`1&lt;!ParentT&gt; WithExistingNetworkSecurityGroup(string resourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithNetworkSecurityGroup`1.WithExistingNetworkSecurityGroup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingNetworkSecurityGroup (resourceId As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingNetworkSecurityGroup : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithNetworkSecurityGroup.WithExistingNetworkSecurityGroup resourceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceId"><span data-ttu-id="a0424-106">Ressourcen-ID der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="a0424-106">The resource ID of the network security group.</span></span></param>
        <summary>
            <span data-ttu-id="a0424-107">Dieses Subnetz wird eine vorhandene Netzwerksicherheitsgruppe zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="a0424-107">Assigns an existing network security group to this subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a0424-108">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="a0424-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>