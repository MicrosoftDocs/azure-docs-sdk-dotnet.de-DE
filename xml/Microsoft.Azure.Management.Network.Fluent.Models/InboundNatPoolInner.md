<Type Name="InboundNatPoolInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner">
  <TypeSignature Language="C#" Value="public class InboundNatPoolInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InboundNatPoolInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner" />
  <TypeSignature Language="VB.NET" Value="Public Class InboundNatPoolInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type InboundNatPoolInner = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ec0bb-101">Pool für eingehende NAT des Load Balancers.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-101">Inbound NAT pool of the load balancer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatPoolInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ec0bb-102">Initialisiert eine neue Instanz der InboundNatPoolInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-102">Initializes a new instance of the InboundNatPoolInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatPoolInner (string protocol, int frontendPortRangeStart, int frontendPortRangeEnd, int backendPort, string id = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource frontendIPConfiguration = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string protocol, int32 frontendPortRangeStart, int32 frontendPortRangeEnd, int32 backendPort, string id, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource frontendIPConfiguration, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.#ctor(System.String,System.Int32,System.Int32,System.Int32,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (protocol As String, frontendPortRangeStart As Integer, frontendPortRangeEnd As Integer, backendPort As Integer, Optional id As String = null, Optional frontendIPConfiguration As SubResource = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner : string * int * int * int * string * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner (protocol, frontendPortRangeStart, frontendPortRangeEnd, backendPort, id, frontendIPConfiguration, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="frontendPortRangeStart" Type="System.Int32" />
        <Parameter Name="frontendPortRangeEnd" Type="System.Int32" />
        <Parameter Name="backendPort" Type="System.Int32" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="frontendIPConfiguration" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol"><span data-ttu-id="ec0bb-103">Das Transportprotokoll für den Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-103">The transport protocol for the endpoint.</span></span>
            <span data-ttu-id="ec0bb-104">Mögliche Werte sind: "Udp" oder "Tcp".</span><span class="sxs-lookup"><span data-stu-id="ec0bb-104">Possible values are: 'Udp' or 'Tcp'.</span></span> <span data-ttu-id="ec0bb-105">Folgende Werte sind möglich: "Udp", "Tcp"</span><span class="sxs-lookup"><span data-stu-id="ec0bb-105">Possible values include: 'Udp', 'Tcp'</span></span></param>
        <param name="frontendPortRangeStart"><span data-ttu-id="ec0bb-106">Die erste Portnummer im Bereich des externen Ports, die eingehende Nat NICs, die einem Lastenausgleichsmodul zugeordnet bereitstellen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-106">The first port number in the range of external ports that will be used to provide Inbound Nat to NICs associated with a load balancer.</span></span> <span data-ttu-id="ec0bb-107">Zulässige Werte zwischen 1 und 65534 sein.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-107">Acceptable values range between 1 and 65534.</span></span></param>
        <param name="frontendPortRangeEnd"><span data-ttu-id="ec0bb-108">Die letzten Portnummer im Bereich des externen Ports, die eingehende Nat NICs, die einem Lastenausgleichsmodul zugeordnet bereitstellen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-108">The last port number in the range of external ports that will be used to provide Inbound Nat to NICs associated with a load balancer.</span></span> <span data-ttu-id="ec0bb-109">Akzeptable Werte liegen zwischen 1 und 65535.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-109">Acceptable values range between 1 and 65535.</span></span></param>
        <param name="backendPort"><span data-ttu-id="ec0bb-110">Der Port, der für interne Verbindungen am Endpunkt verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-110">The port used for internal connections on the endpoint.</span></span> <span data-ttu-id="ec0bb-111">Zulässige Werte liegen zwischen 1 und 65535 liegen.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-111">Acceptable values are between 1 and 65535.</span></span></param>
        <param name="id">To be added.</param>
        <param name="frontendIPConfiguration"><span data-ttu-id="ec0bb-112">Ein Verweis auf die Front-End-IP-Adressen.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-112">A reference to frontend IP addresses.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="ec0bb-113">Ruft den Bereitstellungsstatus der die öffentliche IP-Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-113">Gets the provisioning state of the PublicIP resource.</span></span> <span data-ttu-id="ec0bb-114">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="ec0bb-114">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="ec0bb-115">Der Name der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-115">The name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="ec0bb-116">Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-116">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="ec0bb-117">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-117">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="ec0bb-118">Initialisiert eine neue Instanz der InboundNatPoolInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-118">Initializes a new instance of the InboundNatPoolInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendPort">
      <MemberSignature Language="C#" Value="public int BackendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 BackendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendPort As Integer" />
      <MemberSignature Language="F#" Value="member this.BackendPort : int with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.BackendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec0bb-119">Ruft ab oder legt den Port für die interne Verbindungen am Endpunkt verwendet.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-119">Gets or sets the port used for internal connections on the endpoint.</span></span> <span data-ttu-id="ec0bb-120">Zulässige Werte liegen zwischen 1 und 65535 liegen.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-120">Acceptable values are between 1 and 65535.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec0bb-121">Ruft ab oder legt eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-121">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource FrontendIPConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource FrontendIPConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.FrontendIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendIPConfiguration As SubResource" />
      <MemberSignature Language="F#" Value="member this.FrontendIPConfiguration : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.FrontendIPConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendIPConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec0bb-122">Ruft ab oder legt einen Verweis auf die Front-End-IP-Adressen.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-122">Gets or sets a reference to frontend IP addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeEnd">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeEnd { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.FrontendPortRangeEnd" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPortRangeEnd As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeEnd : int with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.FrontendPortRangeEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendPortRangeEnd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec0bb-123">Ruft ab oder legt die letzten Portnummer im Bereich von externen Ports, die eingehende Nat NICs, die einem Lastenausgleichsmodul zugeordnet bereitstellen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-123">Gets or sets the last port number in the range of external ports that will be used to provide Inbound Nat to NICs associated with a load balancer.</span></span> <span data-ttu-id="ec0bb-124">Akzeptable Werte liegen zwischen 1 und 65535.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-124">Acceptable values range between 1 and 65535.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeStart">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeStart { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.FrontendPortRangeStart" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPortRangeStart As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeStart : int with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.FrontendPortRangeStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendPortRangeStart")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec0bb-125">Ruft ab oder legt die erste Portnummer im Bereich von externen Ports, die eingehende Nat NICs, die einem Lastenausgleichsmodul zugeordnet bereitstellen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-125">Gets or sets the first port number in the range of external ports that will be used to provide Inbound Nat to NICs associated with a load balancer.</span></span> <span data-ttu-id="ec0bb-126">Zulässige Werte zwischen 1 und 65534 sein.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-126">Acceptable values range between 1 and 65534.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec0bb-127">Ruft ab oder legt den Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-127">Gets or sets the name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="ec0bb-128">Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-128">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec0bb-129">Ruft ab oder legt das Transportprotokoll für den Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-129">Gets or sets the transport protocol for the endpoint.</span></span> <span data-ttu-id="ec0bb-130">Mögliche Werte sind: "Udp" oder "Tcp".</span><span class="sxs-lookup"><span data-stu-id="ec0bb-130">Possible values are: 'Udp' or 'Tcp'.</span></span> <span data-ttu-id="ec0bb-131">Folgende Werte sind möglich: "Udp", "Tcp"</span><span class="sxs-lookup"><span data-stu-id="ec0bb-131">Possible values include: 'Udp', 'Tcp'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec0bb-132">Ruft den Bereitstellungsstatus der die öffentliche IP-Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-132">Gets the provisioning state of the PublicIP resource.</span></span> <span data-ttu-id="ec0bb-133">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="ec0bb-133">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="inboundNatPoolInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ec0bb-134">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="ec0bb-134">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ec0bb-135">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="ec0bb-135">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>