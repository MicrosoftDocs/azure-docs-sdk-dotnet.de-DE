<Type Name="ContainerGroup" FullName="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup">
  <TypeSignature Language="C#" Value="public class ContainerGroup : Microsoft.Azure.Management.ContainerInstance.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerGroup extends Microsoft.Azure.Management.ContainerInstance.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerGroup&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ContainerGroup = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ContainerInstance.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e3fb2-101">Ein Containergruppe.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-101">A container group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e3fb2-102">Initialisiert eine neue Instanz der ContainerGroup-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-102">Initializes a new instance of the ContainerGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerGroup (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string provisioningState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Container&gt; containers = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential&gt; imageRegistryCredentials = null, string restartPolicy = null, Microsoft.Azure.Management.ContainerInstance.Models.IpAddress ipAddress = null, string osType = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Volume&gt; volumes = null, Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView instanceView = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string provisioningState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.Container&gt; containers, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential&gt; imageRegistryCredentials, string restartPolicy, class Microsoft.Azure.Management.ContainerInstance.Models.IpAddress ipAddress, string osType, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.Volume&gt; volumes, class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView instanceView) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ContainerInstance.Models.Container},System.Collections.Generic.IList{Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential},System.String,Microsoft.Azure.Management.ContainerInstance.Models.IpAddress,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ContainerInstance.Models.Volume},Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Container&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential&gt; * string * Microsoft.Azure.Management.ContainerInstance.Models.IpAddress * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Volume&gt; * Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView -&gt; Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup" Usage="new Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup (location, id, name, type, tags, provisioningState, containers, imageRegistryCredentials, restartPolicy, ipAddress, osType, volumes, instanceView)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="containers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Container&gt;" />
        <Parameter Name="imageRegistryCredentials" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential&gt;" />
        <Parameter Name="restartPolicy" Type="System.String" />
        <Parameter Name="ipAddress" Type="Microsoft.Azure.Management.ContainerInstance.Models.IpAddress" />
        <Parameter Name="osType" Type="System.String" />
        <Parameter Name="volumes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Volume&gt;" />
        <Parameter Name="instanceView" Type="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="e3fb2-103">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-103">The resource location.</span></span></param>
        <param name="id"><span data-ttu-id="e3fb2-104">Die Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-104">The resource id.</span></span></param>
        <param name="name"><span data-ttu-id="e3fb2-105">Der Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-105">The resource name.</span></span></param>
        <param name="type"><span data-ttu-id="e3fb2-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-106">The resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="e3fb2-107">Der Ressourcen-Tags.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-107">The resource tags.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="e3fb2-108">Der Bereitstellungsstatus der Gruppe "Container".</span><span class="sxs-lookup"><span data-stu-id="e3fb2-108">The provisioning state of the container group.</span></span> <span data-ttu-id="e3fb2-109">Dies wird nur in der Antwort angezeigt.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-109">This only appears in the response.</span></span></param>
        <param name="containers"><span data-ttu-id="e3fb2-110">Der Container innerhalb der Containergruppe.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-110">The containers within the container group.</span></span></param>
        <param name="imageRegistryCredentials"><span data-ttu-id="e3fb2-111">Die Anmeldeinformationen des Image-Registrierung, die durch denen die Containergruppe erstellt wurde, aus.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-111">The image registry credentials by which the container group is created from.</span></span></param>
        <param name="restartPolicy"><span data-ttu-id="e3fb2-112">Starten Sie die Richtlinie für alle Container innerhalb der Containergruppe neu.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-112">Restart policy for all containers within the container group.</span></span>
            - <span data-ttu-id="e3fb2-113">`Always`Immer neu gestartet</span><span class="sxs-lookup"><span data-stu-id="e3fb2-113">`Always` Always restart</span></span>
            - <span data-ttu-id="e3fb2-114">`OnFailure`Fehler beim erneuten Starten</span><span class="sxs-lookup"><span data-stu-id="e3fb2-114">`OnFailure` Restart on failure</span></span>
            - <span data-ttu-id="e3fb2-115">`Never`Nie neu starten.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-115">`Never` Never restart .</span></span> <span data-ttu-id="e3fb2-116">Folgende Werte sind möglich: "Immer", "OnFailure", "Nie"</span><span class="sxs-lookup"><span data-stu-id="e3fb2-116">Possible values include: 'Always', 'OnFailure', 'Never'</span></span></param>
        <param name="ipAddress"><span data-ttu-id="e3fb2-117">Die IP-Adresstyp der Gruppe "Container".</span><span class="sxs-lookup"><span data-stu-id="e3fb2-117">The IP address type of the container group.</span></span></param>
        <param name="osType"><span data-ttu-id="e3fb2-118">Der Typ des Betriebssystems, die Container in der Containergruppe erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-118">The operating system type required by the containers in the container group.</span></span> <span data-ttu-id="e3fb2-119">Folgende Werte sind möglich: "Windows", "Linux"</span><span class="sxs-lookup"><span data-stu-id="e3fb2-119">Possible values include: 'Windows', 'Linux'</span></span></param>
        <param name="volumes"><span data-ttu-id="e3fb2-120">Die Liste der Volumes, die von Containern in dieser Containergruppe eingebunden werden können.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-120">The list of volumes that can be mounted by containers in this container group.</span></span></param>
        <param name="instanceView"><span data-ttu-id="e3fb2-121">Die Instanzansicht der Gruppe "Container".</span><span class="sxs-lookup"><span data-stu-id="e3fb2-121">The instance view of the container group.</span></span> <span data-ttu-id="e3fb2-122">In der Antwort nur gültig.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-122">Only valid in response.</span></span></param>
        <summary>
            <span data-ttu-id="e3fb2-123">Initialisiert eine neue Instanz der ContainerGroup-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-123">Initializes a new instance of the ContainerGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Containers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Container&gt; Containers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.Container&gt; Containers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.Containers" />
      <MemberSignature Language="VB.NET" Value="Public Property Containers As IList(Of Container)" />
      <MemberSignature Language="F#" Value="member this.Containers : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Container&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.Containers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.containers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Container&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3fb2-124">Abrufen oder Festlegen der Container innerhalb der Containergruppe.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-124">Gets or sets the containers within the container group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageRegistryCredentials">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential&gt; ImageRegistryCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential&gt; ImageRegistryCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.ImageRegistryCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageRegistryCredentials As IList(Of ImageRegistryCredential)" />
      <MemberSignature Language="F#" Value="member this.ImageRegistryCredentials : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.ImageRegistryCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.imageRegistryCredentials")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ImageRegistryCredential&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3fb2-125">Ruft ab oder legt das Bild Registrierung Anmeldeinformationen, die Containergruppe erstellt wurde, aus.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-125">Gets or sets the image registry credentials by which the container group is created from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceView">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView InstanceView { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView InstanceView" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.InstanceView" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceView As ContainerGroupPropertiesInstanceView" />
      <MemberSignature Language="F#" Value="member this.InstanceView : Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.InstanceView" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.instanceView")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3fb2-126">Ruft die Instanzansicht der Gruppe "Container" ab.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-126">Gets the instance view of the container group.</span></span> <span data-ttu-id="e3fb2-127">In der Antwort nur gültig.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-127">Only valid in response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerInstance.Models.IpAddress IpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerInstance.Models.IpAddress IpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.IpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property IpAddress As IpAddress" />
      <MemberSignature Language="F#" Value="member this.IpAddress : Microsoft.Azure.Management.ContainerInstance.Models.IpAddress with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.IpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.IpAddress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3fb2-128">Ruft ab oder legt die IP-Adresstyp, der Gruppe "Container".</span><span class="sxs-lookup"><span data-stu-id="e3fb2-128">Gets or sets the IP address type of the container group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public string OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As String" />
      <MemberSignature Language="F#" Value="member this.OsType : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3fb2-129">Ruft ab oder legt den Typ des Betriebssystems, die Container in der Containergruppe erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-129">Gets or sets the operating system type required by the containers in the container group.</span></span> <span data-ttu-id="e3fb2-130">Folgende Werte sind möglich: "Windows", "Linux"</span><span class="sxs-lookup"><span data-stu-id="e3fb2-130">Possible values include: 'Windows', 'Linux'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="e3fb2-131">Ruft den Bereitstellungsstatus der Gruppe "Container" ab.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-131">Gets the provisioning state of the container group.</span></span> <span data-ttu-id="e3fb2-132">Dies wird nur in der Antwort angezeigt.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-132">This only appears in the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartPolicy">
      <MemberSignature Language="C#" Value="public string RestartPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RestartPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.RestartPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RestartPolicy As String" />
      <MemberSignature Language="F#" Value="member this.RestartPolicy : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.RestartPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.restartPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3fb2-133">Ruft ab oder legt neu starten-Richtlinie für alle Container innerhalb der Containergruppe aus.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-133">Gets or sets restart policy for all containers within the container group.</span></span>
            - <span data-ttu-id="e3fb2-134">`Always`Immer neu gestartet</span><span class="sxs-lookup"><span data-stu-id="e3fb2-134">`Always` Always restart</span></span>
            - <span data-ttu-id="e3fb2-135">`OnFailure`Fehler beim erneuten Starten</span><span class="sxs-lookup"><span data-stu-id="e3fb2-135">`OnFailure` Restart on failure</span></span>
            - <span data-ttu-id="e3fb2-136">`Never`Nie neu starten.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-136">`Never` Never restart .</span></span> <span data-ttu-id="e3fb2-137">Folgende Werte sind möglich: "Immer", "OnFailure", "Nie"</span><span class="sxs-lookup"><span data-stu-id="e3fb2-137">Possible values include: 'Always', 'OnFailure', 'Never'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="containerGroup.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e3fb2-138">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-138">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e3fb2-139">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="e3fb2-139">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Volumes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Volume&gt; Volumes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.Volume&gt; Volumes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.Volumes" />
      <MemberSignature Language="VB.NET" Value="Public Property Volumes As IList(Of Volume)" />
      <MemberSignature Language="F#" Value="member this.Volumes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Volume&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup.Volumes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.volumes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Volume&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3fb2-140">Ruft ab oder legt die Liste der Volumes, die von Containern in dieser Containergruppe eingebunden werden können.</span><span class="sxs-lookup"><span data-stu-id="e3fb2-140">Gets or sets the list of volumes that can be mounted by containers in this container group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>