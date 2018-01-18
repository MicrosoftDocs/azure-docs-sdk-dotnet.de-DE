<Type Name="VerificationIPFlowParametersInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner">
  <TypeSignature Language="C#" Value="public class VerificationIPFlowParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VerificationIPFlowParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class VerificationIPFlowParametersInner" />
  <TypeSignature Language="F#" Value="type VerificationIPFlowParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4d8e6-101">Parameter, die den IP-Nachrichtenfluss zu prüfende definieren.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-101">Parameters that define the IP flow to be verified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VerificationIPFlowParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4d8e6-102">Initialisiert eine neue Instanz der VerificationIPFlowParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-102">Initializes a new instance of the VerificationIPFlowParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VerificationIPFlowParametersInner (string targetResourceId, string direction, string protocol, string localPort, string remotePort, string localIPAddress, string remoteIPAddress, string targetNicResourceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetResourceId, string direction, string protocol, string localPort, string remotePort, string localIPAddress, string remoteIPAddress, string targetNicResourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetResourceId As String, direction As String, protocol As String, localPort As String, remotePort As String, localIPAddress As String, remoteIPAddress As String, Optional targetNicResourceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner (targetResourceId, direction, protocol, localPort, remotePort, localIPAddress, remoteIPAddress, targetNicResourceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
        <param name="targetResourceId"><span data-ttu-id="4d8e6-103">Die ID der Zielressource Nächster Hop auf ausführen.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-103">The ID of the target resource to perform next-hop on.</span></span></param>
        <param name="direction"><span data-ttu-id="4d8e6-104">Die Richtung des Pakets als ein 5-Tupel dargestellt.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-104">The direction of the packet represented as a 5-tuple.</span></span> <span data-ttu-id="4d8e6-105">Folgende Werte sind möglich: "Inbound", "Ausgehend"</span><span class="sxs-lookup"><span data-stu-id="4d8e6-105">Possible values include: 'Inbound', 'Outbound'</span></span></param>
        <param name="protocol"><span data-ttu-id="4d8e6-106">Protokoll auf überprüft werden.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-106">Protocol to be verified on.</span></span> <span data-ttu-id="4d8e6-107">Folgende Werte sind möglich: "TCP", "UDP"</span><span class="sxs-lookup"><span data-stu-id="4d8e6-107">Possible values include: 'TCP', 'UDP'</span></span></param>
        <param name="localPort"><span data-ttu-id="4d8e6-108">Der lokale Port.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-108">The local port.</span></span> <span data-ttu-id="4d8e6-109">Zulässige Werte sind eine einzelne ganze Zahl im Bereich (0-65535).</span><span class="sxs-lookup"><span data-stu-id="4d8e6-109">Acceptable values are a single integer in the range (0-65535).</span></span> <span data-ttu-id="4d8e6-110">Unterstützung für \* für den Quellport abhängig von der Richtung.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-110">Support for \* for the source port, which depends on the direction.</span></span></param>
        <param name="remotePort"><span data-ttu-id="4d8e6-111">Der Remoteport.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-111">The remote port.</span></span> <span data-ttu-id="4d8e6-112">Zulässige Werte sind eine einzelne ganze Zahl im Bereich (0-65535).</span><span class="sxs-lookup"><span data-stu-id="4d8e6-112">Acceptable values are a single integer in the range (0-65535).</span></span> <span data-ttu-id="4d8e6-113">Unterstützung für \* für den Quellport abhängig von der Richtung.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-113">Support for \* for the source port, which depends on the direction.</span></span></param>
        <param name="localIPAddress"><span data-ttu-id="4d8e6-114">Die lokale IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-114">The local IP address.</span></span> <span data-ttu-id="4d8e6-115">Zulässige Werte sind gültige IPv4-Adressen.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-115">Acceptable values are valid IPv4 addresses.</span></span></param>
        <param name="remoteIPAddress"><span data-ttu-id="4d8e6-116">Die IP-Remoteadresse.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-116">The remote IP address.</span></span> <span data-ttu-id="4d8e6-117">Zulässige Werte sind gültige IPv4-Adressen.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-117">Acceptable values are valid IPv4 addresses.</span></span></param>
        <param name="targetNicResourceId"><span data-ttu-id="4d8e6-118">Der NIC-ID.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-118">The NIC ID.</span></span> <span data-ttu-id="4d8e6-119">(Wenn der virtuelle Computer mehrere NICs hat, und IP-Weiterleitung für ein beliebiges von ihnen aktiviert ist, muss dann dieser Parameter angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-119">(If VM has multiple NICs and IP forwarding is enabled on any of them, then this parameter must be specified.</span></span> <span data-ttu-id="4d8e6-120">Andernfalls optional).</span><span class="sxs-lookup"><span data-stu-id="4d8e6-120">Otherwise optional).</span></span></param>
        <summary>
            <span data-ttu-id="4d8e6-121">Initialisiert eine neue Instanz der VerificationIPFlowParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-121">Initializes a new instance of the VerificationIPFlowParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Direction">
      <MemberSignature Language="C#" Value="public string Direction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Direction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.Direction" />
      <MemberSignature Language="VB.NET" Value="Public Property Direction As String" />
      <MemberSignature Language="F#" Value="member this.Direction : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.Direction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="4d8e6-122">Ruft ab oder legt die Richtung des Pakets als ein 5-Tupel dargestellt.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-122">Gets or sets the direction of the packet represented as a 5-tuple.</span></span>
            <span data-ttu-id="4d8e6-123">Folgende Werte sind möglich: "Inbound", "Ausgehend"</span><span class="sxs-lookup"><span data-stu-id="4d8e6-123">Possible values include: 'Inbound', 'Outbound'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalIPAddress">
      <MemberSignature Language="C#" Value="public string LocalIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.LocalIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.LocalIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.LocalIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="4d8e6-124">Ruft ab oder legt die lokale IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-124">Gets or sets the local IP address.</span></span> <span data-ttu-id="4d8e6-125">Zulässige Werte sind gültige IPv4-Adressen.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-125">Acceptable values are valid IPv4 addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalPort">
      <MemberSignature Language="C#" Value="public string LocalPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.LocalPort" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalPort As String" />
      <MemberSignature Language="F#" Value="member this.LocalPort : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.LocalPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="4d8e6-126">Ruft ab oder legt den lokalen Port.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-126">Gets or sets the local port.</span></span> <span data-ttu-id="4d8e6-127">Zulässige Werte sind eine einzelne ganze Zahl im Bereich (0-65535).</span><span class="sxs-lookup"><span data-stu-id="4d8e6-127">Acceptable values are a single integer in the range (0-65535).</span></span> <span data-ttu-id="4d8e6-128">Unterstützung für \* für den Quellport abhängig von der Richtung.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-128">Support for \* for the source port, which depends on the direction.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="4d8e6-129">Ruft ab, oder legt sie fest, die auf überprüft werden.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-129">Gets or sets protocol to be verified on.</span></span> <span data-ttu-id="4d8e6-130">Folgende Werte sind möglich: "TCP", "UDP"</span><span class="sxs-lookup"><span data-stu-id="4d8e6-130">Possible values include: 'TCP', 'UDP'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteIPAddress">
      <MemberSignature Language="C#" Value="public string RemoteIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.RemoteIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.RemoteIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.RemoteIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="4d8e6-131">Ruft ab oder legt die IP-Remoteadresse.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-131">Gets or sets the remote IP address.</span></span> <span data-ttu-id="4d8e6-132">Zulässige Werte sind gültige IPv4-Adressen.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-132">Acceptable values are valid IPv4 addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotePort">
      <MemberSignature Language="C#" Value="public string RemotePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemotePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.RemotePort" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotePort As String" />
      <MemberSignature Language="F#" Value="member this.RemotePort : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.RemotePort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="4d8e6-133">Ruft ab oder legt den Remoteport.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-133">Gets or sets the remote port.</span></span> <span data-ttu-id="4d8e6-134">Zulässige Werte sind eine einzelne ganze Zahl im Bereich (0-65535).</span><span class="sxs-lookup"><span data-stu-id="4d8e6-134">Acceptable values are a single integer in the range (0-65535).</span></span> <span data-ttu-id="4d8e6-135">Unterstützung für \* für den Quellport abhängig von der Richtung.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-135">Support for \* for the source port, which depends on the direction.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetNicResourceId">
      <MemberSignature Language="C#" Value="public string TargetNicResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetNicResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.TargetNicResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetNicResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetNicResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.TargetNicResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="4d8e6-136">Ruft ab oder legt die NIC ID.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-136">Gets or sets the NIC ID.</span></span> <span data-ttu-id="4d8e6-137">(Wenn der virtuelle Computer mehrere NICs hat, und IP-Weiterleitung für ein beliebiges von ihnen aktiviert ist, muss dann dieser Parameter angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-137">(If VM has multiple NICs and IP forwarding is enabled on any of them, then this parameter must be specified.</span></span>
            <span data-ttu-id="4d8e6-138">Andernfalls optional).</span><span class="sxs-lookup"><span data-stu-id="4d8e6-138">Otherwise optional).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceId">
      <MemberSignature Language="C#" Value="public string TargetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.TargetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.TargetResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="4d8e6-139">Ruft ab oder legt die ID der Zielressource Nächster Hop auf ausführen.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-139">Gets or sets the ID of the target resource to perform next-hop on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="verificationIPFlowParametersInner.Validate " />
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
            <span data-ttu-id="4d8e6-140">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="4d8e6-140">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4d8e6-141">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="4d8e6-141">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>