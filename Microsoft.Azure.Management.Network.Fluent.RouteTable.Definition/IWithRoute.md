<Type Name="IWithRoute" FullName="Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithRoute">
  <TypeSignature Language="C#" Value="public interface IWithRoute" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRoute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithRoute" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRoute" />
  <TypeSignature Language="F#" Value="type IWithRoute = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c0aa3-101">Die Phase der Tabellendefinition Route Routen hinzu, sodass.</span><span class="sxs-lookup"><span data-stu-id="c0aa3-101">The stage of the route table definition allowing to add routes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineRoute">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate&gt; DefineRoute (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate&gt; DefineRoute(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithRoute.DefineRoute(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineRoute (name As String) As IBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineRoute : string -&gt; Microsoft.Azure.Management.Network.Fluent.Route.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate&gt;" Usage="iWithRoute.DefineRoute name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c0aa3-102">Der Name der Route.</span><span class="sxs-lookup"><span data-stu-id="c0aa3-102">The name of the route.</span></span></param>
        <summary>
            <span data-ttu-id="c0aa3-103">Beginn der Definition eine neue Route die Routentabelle hinzu.</span><span class="sxs-lookup"><span data-stu-id="c0aa3-103">Begins the definition of a new route to add to the route table.</span></span>
            <span data-ttu-id="c0aa3-104">Die Definition muss mit einem Aufruf von Route.DefinitionStages.WithAttach.attach() abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="c0aa3-104">The definition must be completed with a call to  Route.DefinitionStages.WithAttach.attach().</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c0aa3-105">Die erste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c0aa3-105">The first stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRoute">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate WithRoute (string destinationAddressPrefix, Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType nextHop);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate WithRoute(string destinationAddressPrefix, class Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType nextHop) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithRoute.WithRoute(System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRoute (destinationAddressPrefix As String, nextHop As RouteNextHopType) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithRoute : string * Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType -&gt; Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate" Usage="iWithRoute.WithRoute (destinationAddressPrefix, nextHop)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="destinationAddressPrefix" Type="System.String" />
        <Parameter Name="nextHop" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType" />
      </Parameters>
      <Docs>
        <param name="destinationAddressPrefix"><span data-ttu-id="c0aa3-106">Das Ziel-Adresspräfix, ausgedrückt in der CIDR-Notation für die Route zuweisen.</span><span class="sxs-lookup"><span data-stu-id="c0aa3-106">The destination address prefix, expressed in the CIDR notation, for the route to apply to.</span></span></param>
        <param name="nextHop"><span data-ttu-id="c0aa3-107">Der Typ des nächsten Hops.</span><span class="sxs-lookup"><span data-stu-id="c0aa3-107">The next hop type.</span></span></param>
        <summary>
            <span data-ttu-id="c0aa3-108">Erstellt eine Route nicht virtuelle Gerät an.</span><span class="sxs-lookup"><span data-stu-id="c0aa3-108">Creates a non-virtual appliance route.</span></span>
            <span data-ttu-id="c0aa3-109">Der Name wird automatisch generiert.</span><span class="sxs-lookup"><span data-stu-id="c0aa3-109">The name is generated automatically.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c0aa3-110">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c0aa3-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRouteViaVirtualAppliance">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate WithRouteViaVirtualAppliance (string destinationAddressPrefix, string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate WithRouteViaVirtualAppliance(string destinationAddressPrefix, string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithRoute.WithRouteViaVirtualAppliance(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRouteViaVirtualAppliance (destinationAddressPrefix As String, ipAddress As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithRouteViaVirtualAppliance : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate" Usage="iWithRoute.WithRouteViaVirtualAppliance (destinationAddressPrefix, ipAddress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="destinationAddressPrefix" Type="System.String" />
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="destinationAddressPrefix"><span data-ttu-id="c0aa3-111">Das Ziel-Adresspräfix, ausgedrückt in der CIDR-Notation für die Route zuweisen.</span><span class="sxs-lookup"><span data-stu-id="c0aa3-111">The destination address prefix, expressed in the CIDR notation, for the route to apply to.</span></span></param>
        <param name="ipAddress"><span data-ttu-id="c0aa3-112">Die IP-Adresse dem virtuellen Gerät aus, um den Datenverkehr über weiterzuleiten.</span><span class="sxs-lookup"><span data-stu-id="c0aa3-112">The IP address of the virtual appliance to route the traffic through.</span></span></param>
        <summary>
            <span data-ttu-id="c0aa3-113">Erstellt eine Route über ein virtuelles Gerät.</span><span class="sxs-lookup"><span data-stu-id="c0aa3-113">Creates a route via a virtual appliance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c0aa3-114">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c0aa3-114">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>