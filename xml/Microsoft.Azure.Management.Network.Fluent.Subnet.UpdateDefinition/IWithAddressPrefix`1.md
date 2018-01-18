<Type Name="IWithAddressPrefix&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAddressPrefix&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAddressPrefix&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAddressPrefix`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAddressPrefix`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAddressPrefix(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAddressPrefix&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="fd6a8-101">Der übergeordnete Typ.</span><span class="sxs-lookup"><span data-stu-id="fd6a8-101">The parent type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="fd6a8-102">Die Phase der subnetzdefinition ermöglicht den Adressraum für das Subnetz an.</span><span class="sxs-lookup"><span data-stu-id="fd6a8-102">The stage of the subnet definition allowing to specify the address space for the subnet.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAddressPrefix">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithAddressPrefix (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithAddressPrefix(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAddressPrefix`1.WithAddressPrefix(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAddressPrefix (cidr As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAddressPrefix : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAddressPrefix.WithAddressPrefix cidr" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cidr"><span data-ttu-id="fd6a8-103">Die IP-Adresse Speicherplatz Präfix mithilfe der CIDR-Notation.</span><span class="sxs-lookup"><span data-stu-id="fd6a8-103">The IP address space prefix using the CIDR notation.</span></span></param>
        <summary>
            <span data-ttu-id="fd6a8-104">Gibt den IP-Adressraum des Subnetzes innerhalb des Adressraums des Netzwerks an.</span><span class="sxs-lookup"><span data-stu-id="fd6a8-104">Specifies the IP address space of the subnet, within the address space of the network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="fd6a8-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="fd6a8-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>