<Type Name="IWithNextHopType&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithNextHopType&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNextHopType&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNextHopType`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithNextHopType`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNextHopType(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithNextHopType&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="1bbbe-101">Der Rückgabetyp der WithAttach.attach().</span><span class="sxs-lookup"><span data-stu-id="1bbbe-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="1bbbe-102">Die Phase einer Route-Definition, die an den Typ des nächsten Hops zulassen.</span><span class="sxs-lookup"><span data-stu-id="1bbbe-102">The stage of a route definition allowing to specify the next hop type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNextHop">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithNextHop (Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType nextHopType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithNextHop(class Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType nextHopType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithNextHopType`1.WithNextHop(Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNextHop (nextHopType As RouteNextHopType) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNextHop : Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType -&gt; Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithNextHopType.WithNextHop nextHopType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextHopType" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType" />
      </Parameters>
      <Docs>
        <param name="nextHopType"><span data-ttu-id="1bbbe-103">Ein Hop-Typ.</span><span class="sxs-lookup"><span data-stu-id="1bbbe-103">A hop type.</span></span></param>
        <summary>
            <span data-ttu-id="1bbbe-104">Gibt den Typ des nächsten Hops.</span><span class="sxs-lookup"><span data-stu-id="1bbbe-104">Specifies the next hop type.</span></span>
            <span data-ttu-id="1bbbe-105">Um eine virtuelle Anwendung zu verwenden, verwenden Sie stattdessen .withNextHopToVirtualAppliance(String), und geben Sie die IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="1bbbe-105">To use a virtual appliance, use  .withNextHopToVirtualAppliance(String) instead and specify its IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1bbbe-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="1bbbe-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNextHopToVirtualAppliance">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithNextHopToVirtualAppliance (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithNextHopToVirtualAppliance(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithNextHopType`1.WithNextHopToVirtualAppliance(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNextHopToVirtualAppliance (ipAddress As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNextHopToVirtualAppliance : string -&gt; Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithNextHopType.WithNextHopToVirtualAppliance ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="1bbbe-107">IP-Adresse einer vorhandenen virtual Appliance (virtueller Computer).</span><span class="sxs-lookup"><span data-stu-id="1bbbe-107">An IP address of an existing virtual appliance (virtual machine).</span></span></param>
        <summary>
            <span data-ttu-id="1bbbe-108">Gibt die IP-Adresse für den nächsten Hop fahren Sie mit dem virtuellen Gerät an.</span><span class="sxs-lookup"><span data-stu-id="1bbbe-108">Specifies the IP address of the virtual appliance for the next hop to go to.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1bbbe-109">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="1bbbe-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>