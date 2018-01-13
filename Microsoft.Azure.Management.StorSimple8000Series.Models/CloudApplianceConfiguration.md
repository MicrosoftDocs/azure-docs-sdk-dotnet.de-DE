<Type Name="CloudApplianceConfiguration" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration">
  <TypeSignature Language="C#" Value="public class CloudApplianceConfiguration : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudApplianceConfiguration extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudApplianceConfiguration&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type CloudApplianceConfiguration = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="192ba-101">Die Cloud-Anwendungskonfiguration</span><span class="sxs-lookup"><span data-stu-id="192ba-101">The cloud appliance configuration</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudApplianceConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="192ba-102">Initialisiert eine neue Instanz der CloudApplianceConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="192ba-102">Initializes a new instance of the CloudApplianceConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudApplianceConfiguration (string modelNumber, string cloudPlatform, Microsoft.Azure.Management.StorSimple8000Series.Models.AcsConfiguration acsConfiguration, System.Collections.Generic.IList&lt;string&gt; supportedStorageAccountTypes, System.Collections.Generic.IList&lt;string&gt; supportedRegions, System.Collections.Generic.IList&lt;string&gt; supportedVmTypes, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VmImage&gt; supportedVmImages, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string modelNumber, string cloudPlatform, class Microsoft.Azure.Management.StorSimple8000Series.Models.AcsConfiguration acsConfiguration, class System.Collections.Generic.IList`1&lt;string&gt; supportedStorageAccountTypes, class System.Collections.Generic.IList`1&lt;string&gt; supportedRegions, class System.Collections.Generic.IList`1&lt;string&gt; supportedVmTypes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VmImage&gt; supportedVmImages, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.#ctor(System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AcsConfiguration,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.VmImage},System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration : string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AcsConfiguration * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VmImage&gt; * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration (modelNumber, cloudPlatform, acsConfiguration, supportedStorageAccountTypes, supportedRegions, supportedVmTypes, supportedVmImages, id, name, type, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="modelNumber" Type="System.String" />
        <Parameter Name="cloudPlatform" Type="System.String" />
        <Parameter Name="acsConfiguration" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AcsConfiguration" />
        <Parameter Name="supportedStorageAccountTypes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="supportedRegions" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="supportedVmTypes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="supportedVmImages" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VmImage&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
      </Parameters>
      <Docs>
        <param name="modelNumber"><span data-ttu-id="192ba-103">Die Modellnummer.</span><span class="sxs-lookup"><span data-stu-id="192ba-103">The model number.</span></span></param>
        <param name="cloudPlatform"><span data-ttu-id="192ba-104">Die Cloudplattform.</span><span class="sxs-lookup"><span data-stu-id="192ba-104">The cloud platform.</span></span></param>
        <param name="acsConfiguration"><span data-ttu-id="192ba-105">Die ACS-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="192ba-105">The ACS configuration.</span></span></param>
        <param name="supportedStorageAccountTypes"><span data-ttu-id="192ba-106">Konto Speichertypen unterstützt.</span><span class="sxs-lookup"><span data-stu-id="192ba-106">The supported storage account types.</span></span></param>
        <param name="supportedRegions"><span data-ttu-id="192ba-107">Die unterstützten Regionen.</span><span class="sxs-lookup"><span data-stu-id="192ba-107">The supported regions.</span></span></param>
        <param name="supportedVmTypes"><span data-ttu-id="192ba-108">Die Typen des unterstützten virtuellen Computer.</span><span class="sxs-lookup"><span data-stu-id="192ba-108">The supported virtual machine types.</span></span></param>
        <param name="supportedVmImages"><span data-ttu-id="192ba-109">Die Images des unterstützten virtuellen Computer.</span><span class="sxs-lookup"><span data-stu-id="192ba-109">The supported virtual machine images.</span></span></param>
        <param name="id"><span data-ttu-id="192ba-110">Die Pfad-ID, die das Objekt eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="192ba-110">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="192ba-111">Der Name des Objekts.</span><span class="sxs-lookup"><span data-stu-id="192ba-111">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="192ba-112">Der hierarchische Typ des Objekts.</span><span class="sxs-lookup"><span data-stu-id="192ba-112">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="192ba-113">Die Art des Objekts.</span><span class="sxs-lookup"><span data-stu-id="192ba-113">The Kind of the object.</span></span> <span data-ttu-id="192ba-114">Derzeit wird nur Series8000 wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="192ba-114">Currently only Series8000 is supported.</span></span> <span data-ttu-id="192ba-115">Folgende Werte sind möglich: "Series8000"</span><span class="sxs-lookup"><span data-stu-id="192ba-115">Possible values include: 'Series8000'</span></span></param>
        <summary>
            <span data-ttu-id="192ba-116">Initialisiert eine neue Instanz der CloudApplianceConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="192ba-116">Initializes a new instance of the CloudApplianceConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcsConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AcsConfiguration AcsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AcsConfiguration AcsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.AcsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property AcsConfiguration As AcsConfiguration" />
      <MemberSignature Language="F#" Value="member this.AcsConfiguration : Microsoft.Azure.Management.StorSimple8000Series.Models.AcsConfiguration with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.AcsConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.acsConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AcsConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="192ba-117">Ruft ab oder legt die ACS-Konfiguration fest.</span><span class="sxs-lookup"><span data-stu-id="192ba-117">Gets or sets the ACS configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudPlatform">
      <MemberSignature Language="C#" Value="public string CloudPlatform { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CloudPlatform" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.CloudPlatform" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudPlatform As String" />
      <MemberSignature Language="F#" Value="member this.CloudPlatform : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.CloudPlatform" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cloudPlatform")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="192ba-118">Abrufen oder festlegen die Cloud-Plattform.</span><span class="sxs-lookup"><span data-stu-id="192ba-118">Gets or sets the cloud platform.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModelNumber">
      <MemberSignature Language="C#" Value="public string ModelNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ModelNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.ModelNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property ModelNumber As String" />
      <MemberSignature Language="F#" Value="member this.ModelNumber : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.ModelNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.modelNumber")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="192ba-119">Ruft ab oder legt die Modellnummer.</span><span class="sxs-lookup"><span data-stu-id="192ba-119">Gets or sets the model number.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedRegions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SupportedRegions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SupportedRegions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.SupportedRegions" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportedRegions As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SupportedRegions : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.SupportedRegions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.supportedRegions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="192ba-120">Ruft ab oder legt die unterstützten Regionen.</span><span class="sxs-lookup"><span data-stu-id="192ba-120">Gets or sets the supported regions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedStorageAccountTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SupportedStorageAccountTypes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SupportedStorageAccountTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.SupportedStorageAccountTypes" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportedStorageAccountTypes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SupportedStorageAccountTypes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.SupportedStorageAccountTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.supportedStorageAccountTypes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="192ba-121">Ruft ab, oder legt ihn fest-Konto Speichertypen unterstützt.</span><span class="sxs-lookup"><span data-stu-id="192ba-121">Gets or sets the supported storage account types.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedVmImages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VmImage&gt; SupportedVmImages { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VmImage&gt; SupportedVmImages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.SupportedVmImages" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportedVmImages As IList(Of VmImage)" />
      <MemberSignature Language="F#" Value="member this.SupportedVmImages : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VmImage&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.SupportedVmImages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.supportedVmImages")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VmImage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="192ba-122">Ruft ab oder legt die Images des unterstützten virtuellen Computer.</span><span class="sxs-lookup"><span data-stu-id="192ba-122">Gets or sets the supported virtual machine images.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedVmTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SupportedVmTypes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SupportedVmTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.SupportedVmTypes" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportedVmTypes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SupportedVmTypes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.SupportedVmTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.supportedVmTypes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="192ba-123">Ruft ab oder legt fest, ob die unterstützten virtuellen Computer.</span><span class="sxs-lookup"><span data-stu-id="192ba-123">Gets or sets the supported virtual machine types.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cloudApplianceConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="192ba-124">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="192ba-124">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="192ba-125">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="192ba-125">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>