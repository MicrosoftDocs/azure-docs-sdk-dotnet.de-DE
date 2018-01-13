<Type Name="IWithRoute" FullName="Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IWithRoute">
  <TypeSignature Language="C#" Value="public interface IWithRoute" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRoute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IWithRoute" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRoute" />
  <TypeSignature Language="F#" Value="type IWithRoute = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a5f15-101">Die Phase der Tabellendefinition Route zum Hinzufügen, sodass entfernen oder Ändern von Routen.</span><span class="sxs-lookup"><span data-stu-id="a5f15-101">The stage of the route table definition allowing to add, remove or modify routes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineRoute">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate&gt; DefineRoute (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate&gt; DefineRoute(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IWithRoute.DefineRoute(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineRoute (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineRoute : string -&gt; Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate&gt;" Usage="iWithRoute.DefineRoute name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a5f15-102">Der Name der Route.</span><span class="sxs-lookup"><span data-stu-id="a5f15-102">The name of the route.</span></span></param>
        <summary>
            <span data-ttu-id="a5f15-103">Beginn der Definition eine neue Route die Routentabelle hinzu.</span><span class="sxs-lookup"><span data-stu-id="a5f15-103">Begins the definition of a new route to add to the route table.</span></span>
            <span data-ttu-id="a5f15-104">Die Definition muss mit einem Aufruf von Route.UpdateDefinitionStages.WithAttach.attach() abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="a5f15-104">The definition must be completed with a call to  Route.UpdateDefinitionStages.WithAttach.attach().</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5f15-105">Die erste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="a5f15-105">The first stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateRoute">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate UpdateRoute (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate UpdateRoute(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IWithRoute.UpdateRoute(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRoute (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateRoute : string -&gt; Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate" Usage="iWithRoute.UpdateRoute name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a5f15-106">Der Name der eine vorhandene Route.</span><span class="sxs-lookup"><span data-stu-id="a5f15-106">The name of an existing route.</span></span></param>
        <summary>
            <span data-ttu-id="a5f15-107">Startet das Update für eine vorhandene Route für die Routentabelle.</span><span class="sxs-lookup"><span data-stu-id="a5f15-107">Begins the update of an existing route on this route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5f15-108">Die erste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="a5f15-108">The first stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutRoute">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate WithoutRoute (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate WithoutRoute(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IWithRoute.WithoutRoute(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutRoute (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutRoute : string -&gt; Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate" Usage="iWithRoute.WithoutRoute name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a5f15-109">Der Name der eine vorhandene Route für die Routentabelle.</span><span class="sxs-lookup"><span data-stu-id="a5f15-109">The name of an existing route on this route table.</span></span></param>
        <summary>
            <span data-ttu-id="a5f15-110">Entfernt die angegebene Route aus der Routentabelle an.</span><span class="sxs-lookup"><span data-stu-id="a5f15-110">Removes the specified route from the route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5f15-111">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="a5f15-111">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRoute">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate WithRoute (string destinationAddressPrefix, Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType nextHop);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate WithRoute(string destinationAddressPrefix, class Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType nextHop) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IWithRoute.WithRoute(System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRoute (destinationAddressPrefix As String, nextHop As RouteNextHopType) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithRoute : string * Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType -&gt; Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate" Usage="iWithRoute.WithRoute (destinationAddressPrefix, nextHop)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="destinationAddressPrefix" Type="System.String" />
        <Parameter Name="nextHop" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType" />
      </Parameters>
      <Docs>
        <param name="destinationAddressPrefix"><span data-ttu-id="a5f15-112">Das Ziel-Adresspräfix, ausgedrückt in der CIDR-Notation für die Route zuweisen.</span><span class="sxs-lookup"><span data-stu-id="a5f15-112">The destination address prefix, expressed in the CIDR notation, for the route to apply to.</span></span></param>
        <param name="nextHop"><span data-ttu-id="a5f15-113">Der Typ des nächsten Hops.</span><span class="sxs-lookup"><span data-stu-id="a5f15-113">The next hop type.</span></span></param>
        <summary>
            <span data-ttu-id="a5f15-114">Erstellt eine Route nicht virtuelle Gerät an.</span><span class="sxs-lookup"><span data-stu-id="a5f15-114">Creates a non-virtual appliance route.</span></span>
            <span data-ttu-id="a5f15-115">Der Name wird automatisch generiert.</span><span class="sxs-lookup"><span data-stu-id="a5f15-115">The name is generated automatically.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5f15-116">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="a5f15-116">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRouteViaVirtualAppliance">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate WithRouteViaVirtualAppliance (string destinationAddressPrefix, string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate WithRouteViaVirtualAppliance(string destinationAddressPrefix, string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IWithRoute.WithRouteViaVirtualAppliance(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRouteViaVirtualAppliance (destinationAddressPrefix As String, ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithRouteViaVirtualAppliance : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate" Usage="iWithRoute.WithRouteViaVirtualAppliance (destinationAddressPrefix, ipAddress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="destinationAddressPrefix" Type="System.String" />
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="destinationAddressPrefix"><span data-ttu-id="a5f15-117">Das Ziel-Adresspräfix, ausgedrückt in der CIDR-Notation für die Route zuweisen.</span><span class="sxs-lookup"><span data-stu-id="a5f15-117">The destination address prefix, expressed in the CIDR notation, for the route to apply to.</span></span></param>
        <param name="ipAddress"><span data-ttu-id="a5f15-118">Die IP-Adresse dem virtuellen Gerät aus, um den Datenverkehr über weiterzuleiten.</span><span class="sxs-lookup"><span data-stu-id="a5f15-118">The IP address of the virtual appliance to route the traffic through.</span></span></param>
        <summary>
            <span data-ttu-id="a5f15-119">Erstellt eine Route über ein virtuelles Gerät.</span><span class="sxs-lookup"><span data-stu-id="a5f15-119">Creates a route via a virtual appliance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5f15-120">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="a5f15-120">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>