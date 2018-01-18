<Type Name="InboundNatPool" FullName="Microsoft.Azure.Management.Batch.Models.InboundNatPool">
  <TypeSignature Language="C#" Value="public class InboundNatPool" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InboundNatPool extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.InboundNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Class InboundNatPool" />
  <TypeSignature Language="F#" Value="type InboundNatPool = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7c8ec-101">Eine eingehende NAT-Pool, der verwendet werden kann, um bestimmte Ports auf Serverknoten in einem Batch-Pool extern zu behandeln.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-101">A inbound NAT pool that can be used to address specific ports on compute nodes in a Batch pool externally.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatPool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.InboundNatPool.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7c8ec-102">Initialisiert eine neue Instanz der Klasse Pool an.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-102">Initializes a new instance of the InboundNatPool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatPool (string name, Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol protocol, int backendPort, int frontendPortRangeStart, int frontendPortRangeEnd, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule&gt; networkSecurityGroupRules = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol protocol, int32 backendPort, int32 frontendPortRangeStart, int32 frontendPortRangeEnd, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule&gt; networkSecurityGroupRules) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.InboundNatPool.#ctor(System.String,Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol,System.Int32,System.Int32,System.Int32,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, protocol As InboundEndpointProtocol, backendPort As Integer, frontendPortRangeStart As Integer, frontendPortRangeEnd As Integer, Optional networkSecurityGroupRules As IList(Of NetworkSecurityGroupRule) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.InboundNatPool : string * Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol * int * int * int * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule&gt; -&gt; Microsoft.Azure.Management.Batch.Models.InboundNatPool" Usage="new Microsoft.Azure.Management.Batch.Models.InboundNatPool (name, protocol, backendPort, frontendPortRangeStart, frontendPortRangeEnd, networkSecurityGroupRules)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="protocol" Type="Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol" />
        <Parameter Name="backendPort" Type="System.Int32" />
        <Parameter Name="frontendPortRangeStart" Type="System.Int32" />
        <Parameter Name="frontendPortRangeEnd" Type="System.Int32" />
        <Parameter Name="networkSecurityGroupRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7c8ec-103">Der Name des Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-103">The name of the endpoint.</span></span></param>
        <param name="protocol"><span data-ttu-id="7c8ec-104">Das Protokoll des Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-104">The protocol of the endpoint.</span></span></param>
        <param name="backendPort"><span data-ttu-id="7c8ec-105">Die Nummer des Ports auf den Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-105">The port number on the compute node.</span></span></param>
        <param name="frontendPortRangeStart"><span data-ttu-id="7c8ec-106">Die erste Portnummer im Bereich des externen Ports, die verwendet wird, um eingehenden Zugriff auf die BackendPort auf einzelne Serverknoten bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-106">The first port number in the range of external ports that will be used to provide inbound access to the backendPort on individual compute nodes.</span></span></param>
        <param name="frontendPortRangeEnd"><span data-ttu-id="7c8ec-107">Die letzten Portnummer im Bereich des externen Ports, die verwendet wird, um eingehenden Zugriff auf die BackendPort auf einzelne Serverknoten bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-107">The last port number in the range of external ports that will be used to provide inbound access to the backendPort on individual compute nodes.</span></span></param>
        <param name="networkSecurityGroupRules"><span data-ttu-id="7c8ec-108">Eine Liste von Netzwerksicherheits-Gruppenregeln, die an den Endpunkt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-108">A list of network security group rules that will be applied to the endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="7c8ec-109">Initialisiert eine neue Instanz der Klasse Pool an.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-109">Initializes a new instance of the InboundNatPool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendPort">
      <MemberSignature Language="C#" Value="public int BackendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 BackendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.InboundNatPool.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendPort As Integer" />
      <MemberSignature Language="F#" Value="member this.BackendPort : int with get, set" Usage="Microsoft.Azure.Management.Batch.Models.InboundNatPool.BackendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backendPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c8ec-110">Ruft ab oder legt die Portnummer auf dem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-110">Gets or sets the port number on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="7c8ec-111">Dies muss in einem Batch-Pool eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-111">This must be unique within a Batch pool.</span></span> <span data-ttu-id="7c8ec-112">Zulässige Werte liegen zwischen 1 und 65535, außer für 22, 3389, 29876 und 29877 wie diese reserviert sind.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-112">Acceptable values are between 1 and 65535 except for 22, 3389, 29876 and 29877 as these are reserved.</span></span> <span data-ttu-id="7c8ec-113">Ggf. reserviert werden die Werte bereitgestellt, die Anforderung mit HTTP-Statuscode 400 ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-113">If any reserved values are provided the request fails with HTTP status code 400.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeEnd">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeEnd { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.InboundNatPool.FrontendPortRangeEnd" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPortRangeEnd As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeEnd : int with get, set" Usage="Microsoft.Azure.Management.Batch.Models.InboundNatPool.FrontendPortRangeEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="frontendPortRangeEnd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c8ec-114">Ruft ab oder legt die letzten Portnummer im Bereich von externen Ports, die verwendet wird, um eingehenden Zugriff auf die BackendPort auf einzelne Serverknoten bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-114">Gets or sets the last port number in the range of external ports that will be used to provide inbound access to the backendPort on individual compute nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="7c8ec-115">Zulässige Werte zwischen 1 und 65534 außer Ports von 50000 55000 der Batch-Dienst reserviert sind.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-115">Acceptable values range between 1 and 65534 except ports from 50000 to 55000 which are reserved by the Batch service.</span></span> <span data-ttu-id="7c8ec-116">Alle Bereiche in einem Pool müssen eindeutig sein und dürfen sich nicht überschneiden.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-116">All ranges within a pool must be distinct and cannot overlap.</span></span> <span data-ttu-id="7c8ec-117">Wenn alle reservierten oder überlappende Werte, dass die Anforderung mit HTTP-Statuscode 400 schlägt fehl bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-117">If any reserved or overlapping values are provided the request fails with HTTP status code 400.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeStart">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeStart { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.InboundNatPool.FrontendPortRangeStart" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPortRangeStart As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeStart : int with get, set" Usage="Microsoft.Azure.Management.Batch.Models.InboundNatPool.FrontendPortRangeStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="frontendPortRangeStart")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c8ec-118">Ruft ab oder legt die erste Portnummer im Bereich von externen Ports, die verwendet wird, um eingehenden Zugriff auf die BackendPort auf einzelne Serverknoten bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-118">Gets or sets the first port number in the range of external ports that will be used to provide inbound access to the backendPort on individual compute nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="7c8ec-119">Die zulässigen Werte-Bereich zwischen 1 und 65534 außer Ports von 50000 55000 die reserviert sind.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-119">Acceptable values range between 1 and 65534 except ports from 50000 to 55000 which are reserved.</span></span> <span data-ttu-id="7c8ec-120">Alle Bereiche in einem Pool müssen eindeutig sein und dürfen sich nicht überschneiden.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-120">All ranges within a pool must be distinct and cannot overlap.</span></span> <span data-ttu-id="7c8ec-121">Wenn alle reservierten oder überlappende Werte, dass die Anforderung mit HTTP-Statuscode 400 schlägt fehl bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-121">If any reserved or overlapping values are provided the request fails with HTTP status code 400.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.InboundNatPool.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.InboundNatPool.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="7c8ec-122">Ruft den Namen des Endpunkts ab oder legt diesen fest.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-122">Gets or sets the name of the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="7c8ec-123">Der Name in einem Batch-Pool muss eindeutig sein, kann Buchstaben, Zahlen, Unterstriche, Punkte und Bindestriche enthalten.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-123">The name must be unique within a Batch pool, can contain letters, numbers, underscores, periods, and hyphens.</span></span> <span data-ttu-id="7c8ec-124">Namen müssen mit einem Buchstaben beginnen oder Zahl, mit einem Buchstaben, eine Zahl oder ein Unterstrich enden und 77 Zeichen nicht überschreiten.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-124">Names must start with a letter or number, must end with a letter, number, or underscore, and cannot exceed 77 characters.</span></span>  <span data-ttu-id="7c8ec-125">Wenn alle ungültigen Werte, dass die Anforderung mit HTTP-Statuscode 400 schlägt fehl bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-125">If any invalid values are provided the request fails with HTTP status code 400.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroupRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule&gt; NetworkSecurityGroupRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule&gt; NetworkSecurityGroupRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.InboundNatPool.NetworkSecurityGroupRules" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkSecurityGroupRules As IList(Of NetworkSecurityGroupRule)" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroupRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.InboundNatPool.NetworkSecurityGroupRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkSecurityGroupRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c8ec-126">Ruft ab oder legt eine Liste der Netzwerksicherheit, Regeln, die an den Endpunkt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-126">Gets or sets a list of network security group rules that will be applied to the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="7c8ec-127">Die maximale Anzahl von Regeln, die für alle Endpunkte in einem Batch-Pool angegeben werden können, ist 25.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-127">The maximum number of rules that can be specified across all the endpoints on a Batch pool is 25.</span></span> <span data-ttu-id="7c8ec-128">Wenn keine Netzwerksicherheits-Gruppenregeln angegeben sind, wird eine Standardregel erstellt werden, um eingehenden Zugriff auf den angegebenen BackendPort zulassen.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-128">If no network security group rules are specified, a default rule will be created to allow inbound access to the specified backendPort.</span></span> <span data-ttu-id="7c8ec-129">Wenn die maximale Anzahl von Netzwerksicherheits-Gruppenregeln überschritten, wird die Anforderung mit HTTP-Statuscode 400 schlägt fehl.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-129">If the maximum number of network security group rules is exceeded the request fails with HTTP status code 400.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.InboundNatPool.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As InboundEndpointProtocol" />
      <MemberSignature Language="F#" Value="member this.Protocol : Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol with get, set" Usage="Microsoft.Azure.Management.Batch.Models.InboundNatPool.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c8ec-130">Ruft ab oder legt das Protokoll des Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-130">Gets or sets the protocol of the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="7c8ec-131">Folgende Werte sind möglich: "TCP", "UDP"</span><span class="sxs-lookup"><span data-stu-id="7c8ec-131">Possible values include: 'TCP', 'UDP'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.InboundNatPool.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="inboundNatPool.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7c8ec-132">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="7c8ec-132">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7c8ec-133">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="7c8ec-133">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>