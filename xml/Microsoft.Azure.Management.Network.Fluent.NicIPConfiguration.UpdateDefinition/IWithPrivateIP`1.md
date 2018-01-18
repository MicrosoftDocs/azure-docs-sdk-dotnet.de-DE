<Type Name="IWithPrivateIP&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPrivateIP&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.UpdateDefinition.IWithPrivateIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrivateIP`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.UpdateDefinition.IWithPrivateIPAddress`1&lt;class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithAttach`1&lt;class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrivateIP(Of ParentT)&#xA;Implements IWithPrivateIPAddress(Of IWithAttach(Of IUpdate))" />
  <TypeSignature Language="F#" Value="type IWithPrivateIP&lt;'ParentT&gt; = interface&#xA;    interface IWithPrivateIPAddress&lt;IWithAttach&lt;IUpdate&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.UpdateDefinition.IWithPrivateIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="b0344-101">Der Rückgabetyp des endgültigen Attachable.attach().</span><span class="sxs-lookup"><span data-stu-id="b0344-101">The return type of the final  Attachable.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="b0344-102">Die Stufe der Netzwerk-IP-Konfiguration Schnittstellendefinition ermöglicht, private IP-Adresse im Subnetz eines virtuellen Netzwerks anzugeben.</span><span class="sxs-lookup"><span data-stu-id="b0344-102">The stage of the network interface IP configuration definition allowing to specify private IP address within a virtual network subnet.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrivateIPVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithPrivateIPVersion (Microsoft.Azure.Management.Network.Fluent.Models.IPVersion ipVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithPrivateIPVersion(class Microsoft.Azure.Management.Network.Fluent.Models.IPVersion ipVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP`1.WithPrivateIPVersion(Microsoft.Azure.Management.Network.Fluent.Models.IPVersion)" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateIPVersion : Microsoft.Azure.Management.Network.Fluent.Models.IPVersion -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithPrivateIP.WithPrivateIPVersion ipVersion" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipVersion" Type="Microsoft.Azure.Management.Network.Fluent.Models.IPVersion" />
      </Parameters>
      <Docs>
        <param name="ipVersion"><span data-ttu-id="b0344-103">Eine IP-Version.</span><span class="sxs-lookup"><span data-stu-id="b0344-103">An IP version.</span></span></param>
        <summary>
            <span data-ttu-id="b0344-104">Gibt die IP-Version für die private IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="b0344-104">Specifies the IP version for the private IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b0344-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="b0344-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>