<Type Name="IWithSubnet&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Definition.IWithSubnet&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSubnet&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSubnet`1&lt;ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Definition.IWithSubnet`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSubnet(Of ReturnT)" />
  <TypeSignature Language="F#" Value="type IWithSubnet&lt;'ReturnT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ReturnT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ReturnT">To be added.</typeparam>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public ReturnT WithExistingSubnet (string parentNetworkResourceId, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithExistingSubnet(string parentNetworkResourceId, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Definition.IWithSubnet`1.WithExistingSubnet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (parentNetworkResourceId As String, subnetName As String) As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : string * string -&gt; 'ReturnT" Usage="iWithSubnet.WithExistingSubnet (parentNetworkResourceId, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentNetworkResourceId" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentNetworkResourceId"><span data-ttu-id="5de5c-101">ParentNetworkResourceId die Ressourcen-ID des virtuellen Netzwerks, das Subnetz ist Bestandteil des</span><span class="sxs-lookup"><span data-stu-id="5de5c-101">parentNetworkResourceId the resource ID of the virtual network the subnet is part of</span></span></param>
        <param name="subnetName"><span data-ttu-id="5de5c-102">SubnetName den Namen des Subnetzes</span><span class="sxs-lookup"><span data-stu-id="5de5c-102">subnetName the name of the subnet</span></span></param>
        <summary>
            <span data-ttu-id="5de5c-103">Diese Ressource im angegebene Subnetz zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="5de5c-103">Assigns the specified subnet to this resource.</span></span>
            </summary>
        <returns><span data-ttu-id="5de5c-104">die nächste Phase der definition</span><span class="sxs-lookup"><span data-stu-id="5de5c-104">the next stage of the definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>