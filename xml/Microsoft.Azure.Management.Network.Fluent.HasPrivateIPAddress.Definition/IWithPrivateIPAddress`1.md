<Type Name="IWithPrivateIPAddress&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Definition.IWithPrivateIPAddress&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPrivateIPAddress&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrivateIPAddress`1&lt;ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Definition.IWithPrivateIPAddress`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrivateIPAddress(Of ReturnT)" />
  <TypeSignature Language="F#" Value="type IWithPrivateIPAddress&lt;'ReturnT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ReturnT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ReturnT"><span data-ttu-id="5ca20-101">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="5ca20-101">The next stage of the definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="5ca20-102">Die Phase der Definition eines ermöglicht die private IP-Adresse angeben.</span><span class="sxs-lookup"><span data-stu-id="5ca20-102">The stage of a definition allowing to specify the private IP address.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrivateIPAddressDynamic">
      <MemberSignature Language="C#" Value="public ReturnT WithPrivateIPAddressDynamic ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithPrivateIPAddressDynamic() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Definition.IWithPrivateIPAddress`1.WithPrivateIPAddressDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateIPAddressDynamic () As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateIPAddressDynamic : unit -&gt; 'ReturnT" Usage="iWithPrivateIPAddress.WithPrivateIPAddressDynamic " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5ca20-103">Aktiviert dynamischen private IP-Adresszuordnung innerhalb des zugeordneten Subnetzes an.</span><span class="sxs-lookup"><span data-stu-id="5ca20-103">Enables dynamic private IP address allocation within the associated subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5ca20-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="5ca20-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPrivateIPAddressStatic">
      <MemberSignature Language="C#" Value="public ReturnT WithPrivateIPAddressStatic (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithPrivateIPAddressStatic(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Definition.IWithPrivateIPAddress`1.WithPrivateIPAddressStatic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateIPAddressStatic (ipAddress As String) As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateIPAddressStatic : string -&gt; 'ReturnT" Usage="iWithPrivateIPAddress.WithPrivateIPAddressStatic ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="5ca20-105">Eine statische IP-Adresse innerhalb des zugehörigen privaten IP-Adressbereichs.</span><span class="sxs-lookup"><span data-stu-id="5ca20-105">A static IP address within the associated private IP range.</span></span></param>
        <summary>
            <span data-ttu-id="5ca20-106">Weist die angegebene statische private IP-Adresse innerhalb des zugeordneten Subnetzes an.</span><span class="sxs-lookup"><span data-stu-id="5ca20-106">Assigns the specified static private IP address within the associated subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5ca20-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="5ca20-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>