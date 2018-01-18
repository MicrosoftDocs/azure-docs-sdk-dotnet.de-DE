<Type Name="InboundNatPool" FullName="Microsoft.Azure.Batch.InboundNatPool">
  <TypeSignature Language="C#" Value="public class InboundNatPool" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InboundNatPool extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.InboundNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Class InboundNatPool" />
  <TypeSignature Language="F#" Value="type InboundNatPool = class&#xA;    interface ITransportObjectProvider&lt;InboundNATPool&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ec687-101">Eine eingehende NAT-Pool, der verwendet werden kann, um bestimmte Ports auf Serverknoten in einem Batch-Pool extern zu behandeln.</span><span class="sxs-lookup"><span data-stu-id="ec687-101">A inbound NAT pool that can be used to address specific ports on compute nodes in a Batch pool externally.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatPool (string name, Microsoft.Azure.Batch.Common.InboundEndpointProtocol protocol, int backendPort, int frontendPortRangeStart, int frontendPortRangeEnd, System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; networkSecurityGroupRules = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Batch.Common.InboundEndpointProtocol protocol, int32 backendPort, int32 frontendPortRangeStart, int32 frontendPortRangeEnd, class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; networkSecurityGroupRules) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.InboundNatPool.#ctor(System.String,Microsoft.Azure.Batch.Common.InboundEndpointProtocol,System.Int32,System.Int32,System.Int32,System.Collections.Generic.IReadOnlyList{Microsoft.Azure.Batch.NetworkSecurityGroupRule})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, protocol As InboundEndpointProtocol, backendPort As Integer, frontendPortRangeStart As Integer, frontendPortRangeEnd As Integer, Optional networkSecurityGroupRules As IReadOnlyList(Of NetworkSecurityGroupRule) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.InboundNatPool : string * Microsoft.Azure.Batch.Common.InboundEndpointProtocol * int * int * int * System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; -&gt; Microsoft.Azure.Batch.InboundNatPool" Usage="new Microsoft.Azure.Batch.InboundNatPool (name, protocol, backendPort, frontendPortRangeStart, frontendPortRangeEnd, networkSecurityGroupRules)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="protocol" Type="Microsoft.Azure.Batch.Common.InboundEndpointProtocol" />
        <Parameter Name="backendPort" Type="System.Int32" />
        <Parameter Name="frontendPortRangeStart" Type="System.Int32" />
        <Parameter Name="frontendPortRangeEnd" Type="System.Int32" />
        <Parameter Name="networkSecurityGroupRules" Type="System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="ec687-102">Der Name des Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="ec687-102">The name of the endpoint.</span></span></param>
        <param name="protocol"><span data-ttu-id="ec687-103">Das Protokoll des Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="ec687-103">The protocol of the endpoint.</span></span></param>
        <param name="backendPort"><span data-ttu-id="ec687-104">Die Nummer des Ports auf den Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="ec687-104">The port number on the compute node.</span></span></param>
        <param name="frontendPortRangeStart"><span data-ttu-id="ec687-105">Die erste Portnummer im Bereich des externen Ports, die verwendet wird, um eingehenden Zugriff auf die BackendPort auf einzelne Serverknoten bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="ec687-105">The first port number in the range of external ports that will be used to provide inbound access to the backendPort on individual compute nodes.</span></span></param>
        <param name="frontendPortRangeEnd"><span data-ttu-id="ec687-106">Die letzten Portnummer im Bereich des externen Ports, die verwendet wird, um eingehenden Zugriff auf die BackendPort auf einzelne Serverknoten bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="ec687-106">The last port number in the range of external ports that will be used to provide inbound access to the backendPort on individual compute nodes.</span></span></param>
        <param name="networkSecurityGroupRules"><span data-ttu-id="ec687-107">Eine Liste von Netzwerksicherheits-Gruppenregeln, die an den Endpunkt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ec687-107">A list of network security group rules that will be applied to the endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="ec687-108">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.InboundNatPool" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ec687-108">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.InboundNatPool" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendPort">
      <MemberSignature Language="C#" Value="public int BackendPort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 BackendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackendPort As Integer" />
      <MemberSignature Language="F#" Value="member this.BackendPort : int" Usage="Microsoft.Azure.Batch.InboundNatPool.BackendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec687-109">Ruft die Nummer des Ports auf den Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="ec687-109">Gets the port number on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ec687-110">Dies muss in einem Batch-Pool eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="ec687-110">This must be unique within a Batch pool.</span></span> <span data-ttu-id="ec687-111">Zulässige Werte liegen zwischen 1 und 65535, außer für 22, 3389, 29876 und 29877 wie diese reserviert sind.</span><span class="sxs-lookup"><span data-stu-id="ec687-111">Acceptable values are between 1 and 65535 except for 22, 3389, 29876 and 29877 as these are reserved.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeEnd">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeEnd { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.FrontendPortRangeEnd" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FrontendPortRangeEnd As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeEnd : int" Usage="Microsoft.Azure.Batch.InboundNatPool.FrontendPortRangeEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec687-112">Ruft die letzten Portnummer im Bereich von externen Ports, die verwendet wird, um eingehenden Zugriff auf die BackendPort auf einzelne Serverknoten bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="ec687-112">Gets the last port number in the range of external ports that will be used to provide inbound access to the backendPort on individual compute nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ec687-113">Zulässige Werte zwischen 1 und 65534 außer Ports von 50000 55000 der Batch-Dienst reserviert sind.</span><span class="sxs-lookup"><span data-stu-id="ec687-113">Acceptable values range between 1 and 65534 except ports from 50000 to 55000 which are reserved by the Batch service.</span></span> <span data-ttu-id="ec687-114">Alle Bereiche in einem Pool müssen eindeutig sein und dürfen sich nicht überschneiden.</span><span class="sxs-lookup"><span data-stu-id="ec687-114">All ranges within a pool must be distinct and cannot overlap.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeStart">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeStart { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.FrontendPortRangeStart" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FrontendPortRangeStart As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeStart : int" Usage="Microsoft.Azure.Batch.InboundNatPool.FrontendPortRangeStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec687-115">Ruft die erste Portnummer im Bereich von externen Ports, die verwendet wird, um eingehenden Zugriff auf die BackendPort auf einzelne Serverknoten bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="ec687-115">Gets the first port number in the range of external ports that will be used to provide inbound access to the backendPort on individual compute nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ec687-116">Die zulässigen Werte-Bereich zwischen 1 und 65534 außer Ports von 50000 55000 die reserviert sind.</span><span class="sxs-lookup"><span data-stu-id="ec687-116">Acceptable values range between 1 and 65534 except ports from 50000 to 55000 which are reserved.</span></span> <span data-ttu-id="ec687-117">Alle Bereiche in einem Pool müssen eindeutig sein und dürfen sich nicht überschneiden.</span><span class="sxs-lookup"><span data-stu-id="ec687-117">All ranges within a pool must be distinct and cannot overlap.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Batch.InboundNatPool.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec687-118">Ruft den Namen des Endpunkts ab.</span><span class="sxs-lookup"><span data-stu-id="ec687-118">Gets the name of the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ec687-119">Der Name in einem Batch-Pool muss eindeutig sein, kann Buchstaben, Zahlen, Unterstriche, Punkte und Bindestriche enthalten.</span><span class="sxs-lookup"><span data-stu-id="ec687-119">The name must be unique within a Batch pool, can contain letters, numbers, underscores, periods, and hyphens.</span></span> <span data-ttu-id="ec687-120">Namen müssen mit einem Buchstaben beginnen oder Zahl, mit einem Buchstaben, eine Zahl oder ein Unterstrich enden und 77 Zeichen nicht überschreiten.</span><span class="sxs-lookup"><span data-stu-id="ec687-120">Names must start with a letter or number, must end with a letter, number, or underscore, and cannot exceed 77 characters.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroupRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; NetworkSecurityGroupRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; NetworkSecurityGroupRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.NetworkSecurityGroupRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkSecurityGroupRules As IReadOnlyList(Of NetworkSecurityGroupRule)" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroupRules : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt;" Usage="Microsoft.Azure.Batch.InboundNatPool.NetworkSecurityGroupRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec687-121">Ruft eine Liste der Netzwerksicherheit, Regeln, die an den Endpunkt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ec687-121">Gets a list of network security group rules that will be applied to the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ec687-122">Die maximale Anzahl von Regeln, die für alle Endpunkte für einen Pool angegeben werden können, ist 25.</span><span class="sxs-lookup"><span data-stu-id="ec687-122">The maximum number of rules that can be specified across all the endpoints on a pool is 25.</span></span> <span data-ttu-id="ec687-123">Wenn keine Netzwerksicherheits-Gruppenregeln angegeben sind, wird eine Standardregel erstellt werden, um eingehenden Zugriff auf den angegebenen BackendPort zulassen.</span><span class="sxs-lookup"><span data-stu-id="ec687-123">If no network security group rules are specified, a default rule will be created to allow inbound access to the specified backendPort.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.InboundEndpointProtocol Protocol { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.InboundEndpointProtocol Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Protocol As InboundEndpointProtocol" />
      <MemberSignature Language="F#" Value="member this.Protocol : Microsoft.Azure.Batch.Common.InboundEndpointProtocol" Usage="Microsoft.Azure.Batch.InboundNatPool.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.InboundEndpointProtocol</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec687-124">Ruft das Protokoll des Endpunkts ab.</span><span class="sxs-lookup"><span data-stu-id="ec687-124">Gets the protocol of the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>