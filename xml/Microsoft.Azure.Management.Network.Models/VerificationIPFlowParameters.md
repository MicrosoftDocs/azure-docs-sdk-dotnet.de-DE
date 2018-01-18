<Type Name="VerificationIPFlowParameters" FullName="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters">
  <TypeSignature Language="C#" Value="public class VerificationIPFlowParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VerificationIPFlowParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class VerificationIPFlowParameters" />
  <TypeSignature Language="F#" Value="type VerificationIPFlowParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f214a-101">Parameter, die den IP-Nachrichtenfluss zu prüfende definieren.</span><span class="sxs-lookup"><span data-stu-id="f214a-101">Parameters that define the IP flow to be verified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VerificationIPFlowParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f214a-102">Initialisiert eine neue Instanz der VerificationIPFlowParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f214a-102">Initializes a new instance of the VerificationIPFlowParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VerificationIPFlowParameters (string targetResourceId, string direction, string protocol, string localPort, string remotePort, string localIPAddress, string remoteIPAddress, string targetNicResourceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetResourceId, string direction, string protocol, string localPort, string remotePort, string localIPAddress, string remoteIPAddress, string targetNicResourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetResourceId As String, direction As String, protocol As String, localPort As String, remotePort As String, localIPAddress As String, remoteIPAddress As String, Optional targetNicResourceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" Usage="new Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters (targetResourceId, direction, protocol, localPort, remotePort, localIPAddress, remoteIPAddress, targetNicResourceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="direction" Type="System.String" />
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="localPort" Type="System.String" />
        <Parameter Name="remotePort" Type="System.String" />
        <Parameter Name="localIPAddress" Type="System.String" />
        <Parameter Name="remoteIPAddress" Type="System.String" />
        <Parameter Name="targetNicResourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetResourceId"><span data-ttu-id="f214a-103">Die ID der Zielressource Nächster Hop auf ausführen.</span><span class="sxs-lookup"><span data-stu-id="f214a-103">The ID of the target resource to perform next-hop on.</span></span></param>
        <param name="direction"><span data-ttu-id="f214a-104">Die Richtung des Pakets als ein 5-Tupel dargestellt.</span><span class="sxs-lookup"><span data-stu-id="f214a-104">The direction of the packet represented as a 5-tuple.</span></span> <span data-ttu-id="f214a-105">Folgende Werte sind möglich: "Inbound", "Ausgehend"</span><span class="sxs-lookup"><span data-stu-id="f214a-105">Possible values include: 'Inbound', 'Outbound'</span></span></param>
        <param name="protocol"><span data-ttu-id="f214a-106">Protokoll auf überprüft werden.</span><span class="sxs-lookup"><span data-stu-id="f214a-106">Protocol to be verified on.</span></span> <span data-ttu-id="f214a-107">Folgende Werte sind möglich: "TCP", "UDP"</span><span class="sxs-lookup"><span data-stu-id="f214a-107">Possible values include: 'TCP', 'UDP'</span></span></param>
        <param name="localPort"><span data-ttu-id="f214a-108">Der lokale Port.</span><span class="sxs-lookup"><span data-stu-id="f214a-108">The local port.</span></span> <span data-ttu-id="f214a-109">Zulässige Werte sind eine einzelne ganze Zahl im Bereich (0-65535).</span><span class="sxs-lookup"><span data-stu-id="f214a-109">Acceptable values are a single integer in the range (0-65535).</span></span> <span data-ttu-id="f214a-110">Unterstützung für \* für den Quellport abhängig von der Richtung.</span><span class="sxs-lookup"><span data-stu-id="f214a-110">Support for \* for the source port, which depends on the direction.</span></span></param>
        <param name="remotePort"><span data-ttu-id="f214a-111">Der Remoteport.</span><span class="sxs-lookup"><span data-stu-id="f214a-111">The remote port.</span></span> <span data-ttu-id="f214a-112">Zulässige Werte sind eine einzelne ganze Zahl im Bereich (0-65535).</span><span class="sxs-lookup"><span data-stu-id="f214a-112">Acceptable values are a single integer in the range (0-65535).</span></span> <span data-ttu-id="f214a-113">Unterstützung für \* für den Quellport abhängig von der Richtung.</span><span class="sxs-lookup"><span data-stu-id="f214a-113">Support for \* for the source port, which depends on the direction.</span></span></param>
        <param name="localIPAddress"><span data-ttu-id="f214a-114">Die lokale IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="f214a-114">The local IP address.</span></span> <span data-ttu-id="f214a-115">Zulässige Werte sind gültige IPv4-Adressen.</span><span class="sxs-lookup"><span data-stu-id="f214a-115">Acceptable values are valid IPv4 addresses.</span></span></param>
        <param name="remoteIPAddress"><span data-ttu-id="f214a-116">Die IP-Remoteadresse.</span><span class="sxs-lookup"><span data-stu-id="f214a-116">The remote IP address.</span></span> <span data-ttu-id="f214a-117">Zulässige Werte sind gültige IPv4-Adressen.</span><span class="sxs-lookup"><span data-stu-id="f214a-117">Acceptable values are valid IPv4 addresses.</span></span></param>
        <param name="targetNicResourceId"><span data-ttu-id="f214a-118">Der NIC-ID.</span><span class="sxs-lookup"><span data-stu-id="f214a-118">The NIC ID.</span></span> <span data-ttu-id="f214a-119">(Wenn der virtuelle Computer mehrere NICs hat, und IP-Weiterleitung für ein beliebiges von ihnen aktiviert ist, muss dann dieser Parameter angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="f214a-119">(If VM has multiple NICs and IP forwarding is enabled on any of them, then this parameter must be specified.</span></span> <span data-ttu-id="f214a-120">Andernfalls optional).</span><span class="sxs-lookup"><span data-stu-id="f214a-120">Otherwise optional).</span></span></param>
        <summary>
            <span data-ttu-id="f214a-121">Initialisiert eine neue Instanz der VerificationIPFlowParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f214a-121">Initializes a new instance of the VerificationIPFlowParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Direction">
      <MemberSignature Language="C#" Value="public string Direction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Direction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.Direction" />
      <MemberSignature Language="VB.NET" Value="Public Property Direction As String" />
      <MemberSignature Language="F#" Value="member this.Direction : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.Direction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="direction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f214a-122">Ruft ab oder legt die Richtung des Pakets als ein 5-Tupel dargestellt.</span><span class="sxs-lookup"><span data-stu-id="f214a-122">Gets or sets the direction of the packet represented as a 5-tuple.</span></span>
            <span data-ttu-id="f214a-123">Folgende Werte sind möglich: "Inbound", "Ausgehend"</span><span class="sxs-lookup"><span data-stu-id="f214a-123">Possible values include: 'Inbound', 'Outbound'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalIPAddress">
      <MemberSignature Language="C#" Value="public string LocalIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.LocalIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.LocalIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.LocalIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="localIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f214a-124">Ruft ab oder legt die lokale IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="f214a-124">Gets or sets the local IP address.</span></span> <span data-ttu-id="f214a-125">Zulässige Werte sind gültige IPv4-Adressen.</span><span class="sxs-lookup"><span data-stu-id="f214a-125">Acceptable values are valid IPv4 addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalPort">
      <MemberSignature Language="C#" Value="public string LocalPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.LocalPort" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalPort As String" />
      <MemberSignature Language="F#" Value="member this.LocalPort : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.LocalPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="localPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f214a-126">Ruft ab oder legt den lokalen Port.</span><span class="sxs-lookup"><span data-stu-id="f214a-126">Gets or sets the local port.</span></span> <span data-ttu-id="f214a-127">Zulässige Werte sind eine einzelne ganze Zahl im Bereich (0-65535).</span><span class="sxs-lookup"><span data-stu-id="f214a-127">Acceptable values are a single integer in the range (0-65535).</span></span> <span data-ttu-id="f214a-128">Unterstützung für \* für den Quellport abhängig von der Richtung.</span><span class="sxs-lookup"><span data-stu-id="f214a-128">Support for \* for the source port, which depends on the direction.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f214a-129">Ruft ab, oder legt sie fest, die auf überprüft werden.</span><span class="sxs-lookup"><span data-stu-id="f214a-129">Gets or sets protocol to be verified on.</span></span> <span data-ttu-id="f214a-130">Folgende Werte sind möglich: "TCP", "UDP"</span><span class="sxs-lookup"><span data-stu-id="f214a-130">Possible values include: 'TCP', 'UDP'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteIPAddress">
      <MemberSignature Language="C#" Value="public string RemoteIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.RemoteIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.RemoteIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.RemoteIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="remoteIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f214a-131">Ruft ab oder legt die IP-Remoteadresse.</span><span class="sxs-lookup"><span data-stu-id="f214a-131">Gets or sets the remote IP address.</span></span> <span data-ttu-id="f214a-132">Zulässige Werte sind gültige IPv4-Adressen.</span><span class="sxs-lookup"><span data-stu-id="f214a-132">Acceptable values are valid IPv4 addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotePort">
      <MemberSignature Language="C#" Value="public string RemotePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemotePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.RemotePort" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotePort As String" />
      <MemberSignature Language="F#" Value="member this.RemotePort : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.RemotePort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="remotePort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f214a-133">Ruft ab oder legt den Remoteport.</span><span class="sxs-lookup"><span data-stu-id="f214a-133">Gets or sets the remote port.</span></span> <span data-ttu-id="f214a-134">Zulässige Werte sind eine einzelne ganze Zahl im Bereich (0-65535).</span><span class="sxs-lookup"><span data-stu-id="f214a-134">Acceptable values are a single integer in the range (0-65535).</span></span> <span data-ttu-id="f214a-135">Unterstützung für \* für den Quellport abhängig von der Richtung.</span><span class="sxs-lookup"><span data-stu-id="f214a-135">Support for \* for the source port, which depends on the direction.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetNicResourceId">
      <MemberSignature Language="C#" Value="public string TargetNicResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetNicResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.TargetNicResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetNicResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetNicResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.TargetNicResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetNicResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f214a-136">Ruft ab oder legt die NIC ID.</span><span class="sxs-lookup"><span data-stu-id="f214a-136">Gets or sets the NIC ID.</span></span> <span data-ttu-id="f214a-137">(Wenn der virtuelle Computer mehrere NICs hat, und IP-Weiterleitung für ein beliebiges von ihnen aktiviert ist, muss dann dieser Parameter angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="f214a-137">(If VM has multiple NICs and IP forwarding is enabled on any of them, then this parameter must be specified.</span></span>
            <span data-ttu-id="f214a-138">Andernfalls optional).</span><span class="sxs-lookup"><span data-stu-id="f214a-138">Otherwise optional).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceId">
      <MemberSignature Language="C#" Value="public string TargetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.TargetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.TargetResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f214a-139">Ruft ab oder legt die ID der Zielressource Nächster Hop auf ausführen.</span><span class="sxs-lookup"><span data-stu-id="f214a-139">Gets or sets the ID of the target resource to perform next-hop on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="verificationIPFlowParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f214a-140">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="f214a-140">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f214a-141">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="f214a-141">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>