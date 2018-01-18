<Type Name="PacketCaptureFilter" FullName="Microsoft.Azure.Management.Network.Models.PacketCaptureFilter">
  <TypeSignature Language="C#" Value="public class PacketCaptureFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PacketCaptureFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.PacketCaptureFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class PacketCaptureFilter" />
  <TypeSignature Language="F#" Value="type PacketCaptureFilter = class" />
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
            <span data-ttu-id="48e72-101">Filter für die erfassungsanforderung Paket angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="48e72-101">Filter that is applied to packet capture request.</span></span> <span data-ttu-id="48e72-102">Es können mehrere Filter angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="48e72-102">Multiple filters can be applied.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PacketCaptureFilter.#ctor" />
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
            <span data-ttu-id="48e72-103">Initialisiert eine neue Instanz der PacketCaptureFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="48e72-103">Initializes a new instance of the PacketCaptureFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureFilter (string protocol = null, string localIPAddress = null, string remoteIPAddress = null, string localPort = null, string remotePort = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string protocol, string localIPAddress, string remoteIPAddress, string localPort, string remotePort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PacketCaptureFilter.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional protocol As String = null, Optional localIPAddress As String = null, Optional remoteIPAddress As String = null, Optional localPort As String = null, Optional remotePort As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.PacketCaptureFilter : string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.PacketCaptureFilter" Usage="new Microsoft.Azure.Management.Network.Models.PacketCaptureFilter (protocol, localIPAddress, remoteIPAddress, localPort, remotePort)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="localIPAddress" Type="System.String" />
        <Parameter Name="remoteIPAddress" Type="System.String" />
        <Parameter Name="localPort" Type="System.String" />
        <Parameter Name="remotePort" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol"><span data-ttu-id="48e72-104">Protokoll auf gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="48e72-104">Protocol to be filtered on.</span></span> <span data-ttu-id="48e72-105">Folgende Werte sind möglich: "TCP", "UDP", "Alle"</span><span class="sxs-lookup"><span data-stu-id="48e72-105">Possible values include: 'TCP', 'UDP', 'Any'</span></span></param>
        <param name="localIPAddress"><span data-ttu-id="48e72-106">Lokale IP-Adresse auf gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="48e72-106">Local IP Address to be filtered on.</span></span>
            <span data-ttu-id="48e72-107">Notation: "127.0.0.1" für einzelne-Adresseintrag.</span><span class="sxs-lookup"><span data-stu-id="48e72-107">Notation: "127.0.0.1" for single address entry.</span></span>
            <span data-ttu-id="48e72-108">"127.0.0.1-127.0.0.255" für den Bereich.</span><span class="sxs-lookup"><span data-stu-id="48e72-108">"127.0.0.1-127.0.0.255" for range.</span></span> <span data-ttu-id="48e72-109">"127.0.0.1;127.0.0.5"?</span><span class="sxs-lookup"><span data-stu-id="48e72-109">"127.0.0.1;127.0.0.5"?</span></span> <span data-ttu-id="48e72-110">für mehrere Einträge.</span><span class="sxs-lookup"><span data-stu-id="48e72-110">for multiple entries.</span></span> <span data-ttu-id="48e72-111">Mehrere Bereiche, die derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48e72-111">Multiple ranges not currently supported.</span></span> <span data-ttu-id="48e72-112">Mischen von Bereichen mit mehreren Einträgen, die derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48e72-112">Mixing ranges with multiple entries not currently supported.</span></span> <span data-ttu-id="48e72-113">Standard = Null.</span><span class="sxs-lookup"><span data-stu-id="48e72-113">Default = null.</span></span></param>
        <param name="remoteIPAddress"><span data-ttu-id="48e72-114">Lokale IP-Adresse auf gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="48e72-114">Local IP Address to be filtered on.</span></span>
            <span data-ttu-id="48e72-115">Notation: "127.0.0.1" für einzelne-Adresseintrag.</span><span class="sxs-lookup"><span data-stu-id="48e72-115">Notation: "127.0.0.1" for single address entry.</span></span>
            <span data-ttu-id="48e72-116">"127.0.0.1-127.0.0.255" für den Bereich.</span><span class="sxs-lookup"><span data-stu-id="48e72-116">"127.0.0.1-127.0.0.255" for range.</span></span> <span data-ttu-id="48e72-117">"127.0.0.1;127.0.0.5;" für mehrere Einträge.</span><span class="sxs-lookup"><span data-stu-id="48e72-117">"127.0.0.1;127.0.0.5;" for multiple entries.</span></span> <span data-ttu-id="48e72-118">Mehrere Bereiche, die derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48e72-118">Multiple ranges not currently supported.</span></span> <span data-ttu-id="48e72-119">Mischen von Bereichen mit mehreren Einträgen, die derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48e72-119">Mixing ranges with multiple entries not currently supported.</span></span> <span data-ttu-id="48e72-120">Standard = Null.</span><span class="sxs-lookup"><span data-stu-id="48e72-120">Default = null.</span></span></param>
        <param name="localPort"><span data-ttu-id="48e72-121">Lokaler Port auf gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="48e72-121">Local port to be filtered on.</span></span> <span data-ttu-id="48e72-122">Notation: nach Eingabe eines einzelnen Port "80". " 80-85" für den Bereich.</span><span class="sxs-lookup"><span data-stu-id="48e72-122">Notation: "80" for single port entry."80-85" for range.</span></span> <span data-ttu-id="48e72-123">"80, 443;" für mehrere Einträge.</span><span class="sxs-lookup"><span data-stu-id="48e72-123">"80;443;" for multiple entries.</span></span> <span data-ttu-id="48e72-124">Mehrere Bereiche, die derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48e72-124">Multiple ranges not currently supported.</span></span> <span data-ttu-id="48e72-125">Mischen von Bereichen mit mehreren Einträgen, die derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48e72-125">Mixing ranges with multiple entries not currently supported.</span></span> <span data-ttu-id="48e72-126">Standard = Null.</span><span class="sxs-lookup"><span data-stu-id="48e72-126">Default = null.</span></span></param>
        <param name="remotePort"><span data-ttu-id="48e72-127">Der Remoteport auf gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="48e72-127">Remote port to be filtered on.</span></span> <span data-ttu-id="48e72-128">Notation: nach Eingabe eines einzelnen Port "80". " 80-85" für den Bereich.</span><span class="sxs-lookup"><span data-stu-id="48e72-128">Notation: "80" for single port entry."80-85" for range.</span></span> <span data-ttu-id="48e72-129">"80, 443;" für mehrere Einträge.</span><span class="sxs-lookup"><span data-stu-id="48e72-129">"80;443;" for multiple entries.</span></span> <span data-ttu-id="48e72-130">Mehrere Bereiche, die derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48e72-130">Multiple ranges not currently supported.</span></span> <span data-ttu-id="48e72-131">Mischen von Bereichen mit mehreren Einträgen, die derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48e72-131">Mixing ranges with multiple entries not currently supported.</span></span> <span data-ttu-id="48e72-132">Standard = Null.</span><span class="sxs-lookup"><span data-stu-id="48e72-132">Default = null.</span></span></param>
        <summary>
            <span data-ttu-id="48e72-133">Initialisiert eine neue Instanz der PacketCaptureFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="48e72-133">Initializes a new instance of the PacketCaptureFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalIPAddress">
      <MemberSignature Language="C#" Value="public string LocalIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureFilter.LocalIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.LocalIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureFilter.LocalIPAddress" />
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
            <span data-ttu-id="48e72-134">Ruft ab, oder legt ihn fest lokale IP-Adresse auf gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="48e72-134">Gets or sets local IP Address to be filtered on.</span></span> <span data-ttu-id="48e72-135">Notation: "127.0.0.1" für einzelne-Adresseintrag.</span><span class="sxs-lookup"><span data-stu-id="48e72-135">Notation: "127.0.0.1" for single address entry.</span></span> <span data-ttu-id="48e72-136">"127.0.0.1-127.0.0.255" für den Bereich.</span><span class="sxs-lookup"><span data-stu-id="48e72-136">"127.0.0.1-127.0.0.255" for range.</span></span> <span data-ttu-id="48e72-137">"127.0.0.1;127.0.0.5"?</span><span class="sxs-lookup"><span data-stu-id="48e72-137">"127.0.0.1;127.0.0.5"?</span></span> <span data-ttu-id="48e72-138">für mehrere Einträge.</span><span class="sxs-lookup"><span data-stu-id="48e72-138">for multiple entries.</span></span> <span data-ttu-id="48e72-139">Mehrere Bereiche, die derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48e72-139">Multiple ranges not currently supported.</span></span> <span data-ttu-id="48e72-140">Mischen von Bereichen mit mehreren Einträgen, die derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48e72-140">Mixing ranges with multiple entries not currently supported.</span></span> <span data-ttu-id="48e72-141">Standard = Null.</span><span class="sxs-lookup"><span data-stu-id="48e72-141">Default = null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalPort">
      <MemberSignature Language="C#" Value="public string LocalPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureFilter.LocalPort" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalPort As String" />
      <MemberSignature Language="F#" Value="member this.LocalPort : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureFilter.LocalPort" />
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
            <span data-ttu-id="48e72-142">Abrufen oder Festlegen der lokalen Port gefiltert werden.</span><span class="sxs-lookup"><span data-stu-id="48e72-142">Gets or sets local port to be filtered on.</span></span> <span data-ttu-id="48e72-143">Notation: nach Eingabe eines einzelnen Port "80". " 80-85" für den Bereich.</span><span class="sxs-lookup"><span data-stu-id="48e72-143">Notation: "80" for single port entry."80-85" for range.</span></span> <span data-ttu-id="48e72-144">"80, 443;" für mehrere Einträge.</span><span class="sxs-lookup"><span data-stu-id="48e72-144">"80;443;" for multiple entries.</span></span> <span data-ttu-id="48e72-145">Mehrere Bereiche, die derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48e72-145">Multiple ranges not currently supported.</span></span> <span data-ttu-id="48e72-146">Mischen von Bereichen mit mehreren Einträgen, die derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48e72-146">Mixing ranges with multiple entries not currently supported.</span></span> <span data-ttu-id="48e72-147">Standard = Null.</span><span class="sxs-lookup"><span data-stu-id="48e72-147">Default = null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureFilter.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureFilter.Protocol" />
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
            <span data-ttu-id="48e72-148">Ruft ab, oder legt sie fest, die gefiltert werden.</span><span class="sxs-lookup"><span data-stu-id="48e72-148">Gets or sets protocol to be filtered on.</span></span> <span data-ttu-id="48e72-149">Folgende Werte sind möglich: "TCP", "UDP", "Alle"</span><span class="sxs-lookup"><span data-stu-id="48e72-149">Possible values include: 'TCP', 'UDP', 'Any'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteIPAddress">
      <MemberSignature Language="C#" Value="public string RemoteIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureFilter.RemoteIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.RemoteIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureFilter.RemoteIPAddress" />
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
            <span data-ttu-id="48e72-150">Ruft ab, oder legt ihn fest lokale IP-Adresse auf gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="48e72-150">Gets or sets local IP Address to be filtered on.</span></span> <span data-ttu-id="48e72-151">Notation: "127.0.0.1" für einzelne-Adresseintrag.</span><span class="sxs-lookup"><span data-stu-id="48e72-151">Notation: "127.0.0.1" for single address entry.</span></span> <span data-ttu-id="48e72-152">"127.0.0.1-127.0.0.255" für den Bereich.</span><span class="sxs-lookup"><span data-stu-id="48e72-152">"127.0.0.1-127.0.0.255" for range.</span></span> <span data-ttu-id="48e72-153">"127.0.0.1;127.0.0.5;" für mehrere Einträge.</span><span class="sxs-lookup"><span data-stu-id="48e72-153">"127.0.0.1;127.0.0.5;" for multiple entries.</span></span> <span data-ttu-id="48e72-154">Mehrere Bereiche, die derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48e72-154">Multiple ranges not currently supported.</span></span> <span data-ttu-id="48e72-155">Mischen von Bereichen mit mehreren Einträgen, die derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48e72-155">Mixing ranges with multiple entries not currently supported.</span></span> <span data-ttu-id="48e72-156">Standard = Null.</span><span class="sxs-lookup"><span data-stu-id="48e72-156">Default = null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotePort">
      <MemberSignature Language="C#" Value="public string RemotePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemotePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureFilter.RemotePort" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotePort As String" />
      <MemberSignature Language="F#" Value="member this.RemotePort : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureFilter.RemotePort" />
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
            <span data-ttu-id="48e72-157">Ruft ab, oder legt ihn fest Remoteport auf gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="48e72-157">Gets or sets remote port to be filtered on.</span></span> <span data-ttu-id="48e72-158">Notation: nach Eingabe eines einzelnen Port "80". " 80-85" für den Bereich.</span><span class="sxs-lookup"><span data-stu-id="48e72-158">Notation: "80" for single port entry."80-85" for range.</span></span> <span data-ttu-id="48e72-159">"80, 443;" für mehrere Einträge.</span><span class="sxs-lookup"><span data-stu-id="48e72-159">"80;443;" for multiple entries.</span></span> <span data-ttu-id="48e72-160">Mehrere Bereiche, die derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48e72-160">Multiple ranges not currently supported.</span></span> <span data-ttu-id="48e72-161">Mischen von Bereichen mit mehreren Einträgen, die derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48e72-161">Mixing ranges with multiple entries not currently supported.</span></span> <span data-ttu-id="48e72-162">Standard = Null.</span><span class="sxs-lookup"><span data-stu-id="48e72-162">Default = null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>