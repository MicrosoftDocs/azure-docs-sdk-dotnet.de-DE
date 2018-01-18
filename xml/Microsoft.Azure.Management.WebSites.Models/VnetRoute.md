<Type Name="VnetRoute" FullName="Microsoft.Azure.Management.WebSites.Models.VnetRoute">
  <TypeSignature Language="C#" Value="public class VnetRoute : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VnetRoute extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.VnetRoute" />
  <TypeSignature Language="VB.NET" Value="Public Class VnetRoute&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type VnetRoute = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="68147-101">Virtuelles Netzwerk Route-Vertrag verwendet, um die Routinginformationen für ein virtuelles Netzwerk zu übergeben.</span><span class="sxs-lookup"><span data-stu-id="68147-101">Virtual Network route contract used to pass routing information for a Virtual Network.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetRoute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.VnetRoute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="68147-102">Initialisiert eine neue Instanz der VnetRoute-Klasse.</span><span class="sxs-lookup"><span data-stu-id="68147-102">Initializes a new instance of the VnetRoute class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetRoute (string id = null, string name = null, string kind = null, string type = null, string vnetRouteName = null, string startAddress = null, string endAddress = null, string routeType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string vnetRouteName, string startAddress, string endAddress, string routeType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.VnetRoute.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional vnetRouteName As String = null, Optional startAddress As String = null, Optional endAddress As String = null, Optional routeType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.VnetRoute : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.VnetRoute" Usage="new Microsoft.Azure.Management.WebSites.Models.VnetRoute (id, name, kind, type, vnetRouteName, startAddress, endAddress, routeType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="vnetRouteName" Type="System.String" />
        <Parameter Name="startAddress" Type="System.String" />
        <Parameter Name="endAddress" Type="System.String" />
        <Parameter Name="routeType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="68147-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="68147-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="68147-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="68147-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="68147-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="68147-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="68147-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="68147-106">Resource type.</span></span></param>
        <param name="vnetRouteName"><span data-ttu-id="68147-107">Der Name der Route.</span><span class="sxs-lookup"><span data-stu-id="68147-107">The name of this route.</span></span> <span data-ttu-id="68147-108">Dies wird nur zurückgegeben, durch den Server und muss nicht vom Client festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="68147-108">This is only returned by the server and does not need to be set by the client.</span></span></param>
        <param name="startAddress"><span data-ttu-id="68147-109">Die Startadresse für diese Route.</span><span class="sxs-lookup"><span data-stu-id="68147-109">The starting address for this route.</span></span>
             <span data-ttu-id="68147-110">Dies kann auch eine CIDR-Notation, umfassen, in der Fall die letzte Adresse nicht angegeben werden muss.</span><span class="sxs-lookup"><span data-stu-id="68147-110">This may also include a CIDR notation, in which case the end address must not be specified.</span></span></param>
        <param name="endAddress"><span data-ttu-id="68147-111">Die Endadresse für diese Route.</span><span class="sxs-lookup"><span data-stu-id="68147-111">The ending address for this route.</span></span> <span data-ttu-id="68147-112">Wenn die erste Adresse in CIDR-Notation angegeben wird, muss dies ausgelassen werden.</span><span class="sxs-lookup"><span data-stu-id="68147-112">If the start address is specified in CIDR notation, this must be omitted.</span></span></param>
        <param name="routeType"><span data-ttu-id="68147-113">Der Typ der Route sieht: Standard – standardmäßig wird für jede app hat, leitet an die lokale Adressbereiche gemäß RFC1918 VERERBT - Routen von realen virtuelle Netzwerkrouten STATIC - statischen Routen, legen Sie für die app nur geerbt</span><span class="sxs-lookup"><span data-stu-id="68147-113">The type of route this is: DEFAULT - By default, every app has routes to the local address ranges specified by RFC1918 INHERITED - Routes inherited from the real Virtual Network routes STATIC - Static route set on the app only</span></span>
             
             <span data-ttu-id="68147-114">Diese Werte werden für die Synchronisierung von einer app-Routen, mit denen von einem virtuellen Netzwerk verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="68147-114">These values will be used for syncing an app's routes with those from a Virtual Network.</span></span> <span data-ttu-id="68147-115">Folgende Werte sind möglich: 'DEFAULT', "GEERBTE", "STATIC"</span><span class="sxs-lookup"><span data-stu-id="68147-115">Possible values include: 'DEFAULT', 'INHERITED', 'STATIC'</span></span></param>
        <summary>
             <span data-ttu-id="68147-116">Initialisiert eine neue Instanz der VnetRoute-Klasse.</span><span class="sxs-lookup"><span data-stu-id="68147-116">Initializes a new instance of the VnetRoute class.</span></span>
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndAddress">
      <MemberSignature Language="C#" Value="public string EndAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetRoute.EndAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EndAddress As String" />
      <MemberSignature Language="F#" Value="member this.EndAddress : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetRoute.EndAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68147-117">Ruft ab oder legt die Endadresse für diese Route.</span><span class="sxs-lookup"><span data-stu-id="68147-117">Gets or sets the ending address for this route.</span></span> <span data-ttu-id="68147-118">Wenn die erste Adresse in CIDR-Notation angegeben wird, muss dies ausgelassen werden.</span><span class="sxs-lookup"><span data-stu-id="68147-118">If the start address is specified in CIDR notation, this must be omitted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteType">
      <MemberSignature Language="C#" Value="public string RouteType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RouteType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetRoute.RouteType" />
      <MemberSignature Language="VB.NET" Value="Public Property RouteType As String" />
      <MemberSignature Language="F#" Value="member this.RouteType : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetRoute.RouteType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.routeType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="68147-119">Ruft ab oder legt den Typ der Route sieht: Standard – standardmäßig wird für jede app hat, leitet an die lokale Adressbereiche gemäß RFC1918 VERERBT - Routen von realen virtuelle Netzwerkrouten STATIC - statischen Routen, legen Sie für die app nur geerbt</span><span class="sxs-lookup"><span data-stu-id="68147-119">Gets or sets the type of route this is: DEFAULT - By default, every app has routes to the local address ranges specified by RFC1918 INHERITED - Routes inherited from the real Virtual Network routes STATIC - Static route set on the app only</span></span>
             
             <span data-ttu-id="68147-120">Diese Werte werden für die Synchronisierung von einer app-Routen, mit denen von einem virtuellen Netzwerk verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="68147-120">These values will be used for syncing an app's routes with those from a Virtual Network.</span></span> <span data-ttu-id="68147-121">Folgende Werte sind möglich: 'DEFAULT', "GEERBTE", "STATIC"</span><span class="sxs-lookup"><span data-stu-id="68147-121">Possible values include: 'DEFAULT', 'INHERITED', 'STATIC'</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAddress">
      <MemberSignature Language="C#" Value="public string StartAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetRoute.StartAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property StartAddress As String" />
      <MemberSignature Language="F#" Value="member this.StartAddress : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetRoute.StartAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68147-122">Ruft ab oder legt die Startadresse für diese Route fest.</span><span class="sxs-lookup"><span data-stu-id="68147-122">Gets or sets the starting address for this route.</span></span> <span data-ttu-id="68147-123">Dies kann auch eine CIDR-Notation, umfassen, in der Fall die letzte Adresse nicht angegeben werden muss.</span><span class="sxs-lookup"><span data-stu-id="68147-123">This may also include a CIDR notation, in which case the end address must not be specified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetRouteName">
      <MemberSignature Language="C#" Value="public string VnetRouteName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetRouteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetRoute.VnetRouteName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetRouteName As String" />
      <MemberSignature Language="F#" Value="member this.VnetRouteName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetRoute.VnetRouteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68147-124">Ruft ab oder legt den Namen dieser Route.</span><span class="sxs-lookup"><span data-stu-id="68147-124">Gets or sets the name of this route.</span></span> <span data-ttu-id="68147-125">Dies wird nur zurückgegeben, durch den Server und muss nicht vom Client festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="68147-125">This is only returned by the server and does not need to be set by the client.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>