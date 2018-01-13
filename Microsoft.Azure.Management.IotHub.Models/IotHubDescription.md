<Type Name="IotHubDescription" FullName="Microsoft.Azure.Management.IotHub.Models.IotHubDescription">
  <TypeSignature Language="C#" Value="public class IotHubDescription : Microsoft.Azure.Management.IotHub.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IotHubDescription extends Microsoft.Azure.Management.IotHub.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.IotHubDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class IotHubDescription&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type IotHubDescription = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.IotHub.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7461a-101">Die Beschreibung des IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="7461a-101">The description of the IoT hub.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7461a-102">Initialisiert eine neue Instanz der IotHubDescription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7461a-102">Initializes a new instance of the IotHubDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubDescription (string location, string subscriptionid, string resourcegroup, Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo sku, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string etag = null, Microsoft.Azure.Management.IotHub.Models.IotHubProperties properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string subscriptionid, string resourcegroup, class Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo sku, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string etag, class Microsoft.Azure.Management.IotHub.Models.IotHubProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubDescription.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.IotHub.Models.IotHubProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, subscriptionid As String, resourcegroup As String, sku As IotHubSkuInfo, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional etag As String = null, Optional properties As IotHubProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.IotHubDescription : string * string * string * Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.IotHub.Models.IotHubProperties -&gt; Microsoft.Azure.Management.IotHub.Models.IotHubDescription" Usage="new Microsoft.Azure.Management.IotHub.Models.IotHubDescription (location, subscriptionid, resourcegroup, sku, id, name, type, tags, etag, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="subscriptionid" Type="System.String" />
        <Parameter Name="resourcegroup" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.IotHub.Models.IotHubProperties" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="7461a-103">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="7461a-103">The resource location.</span></span></param>
        <param name="subscriptionid"><span data-ttu-id="7461a-104">Die Abonnement-ID.</span><span class="sxs-lookup"><span data-stu-id="7461a-104">The subscription identifier.</span></span></param>
        <param name="resourcegroup"><span data-ttu-id="7461a-105">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="7461a-105">The name of the resource group that contains the IoT hub.</span></span> <span data-ttu-id="7461a-106">Ein Ressourcengruppenname identifiziert eindeutig die Ressourcengruppe innerhalb des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="7461a-106">A resource group name uniquely identifies the resource group within the subscription.</span></span></param>
        <param name="sku">To be added.</param>
        <param name="id"><span data-ttu-id="7461a-107">Der Ressourcenbezeichner.</span><span class="sxs-lookup"><span data-stu-id="7461a-107">The resource identifier.</span></span></param>
        <param name="name"><span data-ttu-id="7461a-108">Der Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="7461a-108">The resource name.</span></span></param>
        <param name="type"><span data-ttu-id="7461a-109">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="7461a-109">The resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="7461a-110">Der Ressourcen-Tags.</span><span class="sxs-lookup"><span data-stu-id="7461a-110">The resource tags.</span></span></param>
        <param name="etag"><span data-ttu-id="7461a-111">Der Etag-Feld ist *nicht* erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7461a-111">The Etag field is *not* required.</span></span> <span data-ttu-id="7461a-112">Wenn diese im Antworttext angegeben wird, muss er auch als Header pro der normalen ETag-Konvention angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="7461a-112">If it is provided in the response body, it must also be provided as a header per the normal ETag convention.</span></span></param>
        <param name="properties">To be added.</param>
        <summary>
            <span data-ttu-id="7461a-113">Initialisiert eine neue Instanz der IotHubDescription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7461a-113">Initializes a new instance of the IotHubDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubDescription.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubDescription.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="7461a-114">Ruft ab oder legt den Etag-Feld ist *nicht* erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7461a-114">Gets or sets the Etag field is *not* required.</span></span> <span data-ttu-id="7461a-115">Wenn diese im Antworttext angegeben wird, muss er auch als Header pro der normalen ETag-Konvention angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="7461a-115">If it is provided in the response body, it must also be provided as a header per the normal ETag convention.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.IotHub.Models.IotHubProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.IotHub.Models.IotHubProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubDescription.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As IotHubProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.IotHub.Models.IotHubProperties with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubDescription.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.IotHubProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resourcegroup">
      <MemberSignature Language="C#" Value="public string Resourcegroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resourcegroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubDescription.Resourcegroup" />
      <MemberSignature Language="VB.NET" Value="Public Property Resourcegroup As String" />
      <MemberSignature Language="F#" Value="member this.Resourcegroup : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubDescription.Resourcegroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourcegroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7461a-116">Ruft ab oder legt den Namen der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="7461a-116">Gets or sets the name of the resource group that contains the IoT hub.</span></span> <span data-ttu-id="7461a-117">Ein Ressourcengruppenname identifiziert eindeutig die Ressourcengruppe innerhalb des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="7461a-117">A resource group name uniquely identifies the resource group within the subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubDescription.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As IotHubSkuInfo" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubDescription.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subscriptionid">
      <MemberSignature Language="C#" Value="public string Subscriptionid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Subscriptionid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubDescription.Subscriptionid" />
      <MemberSignature Language="VB.NET" Value="Public Property Subscriptionid As String" />
      <MemberSignature Language="F#" Value="member this.Subscriptionid : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubDescription.Subscriptionid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subscriptionid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7461a-118">Ruft ab oder legt den Abonnementbezeichner.</span><span class="sxs-lookup"><span data-stu-id="7461a-118">Gets or sets the subscription identifier.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubDescription.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="iotHubDescription.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7461a-119">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="7461a-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7461a-120">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="7461a-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>