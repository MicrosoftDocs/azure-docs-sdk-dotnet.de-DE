<Type Name="GenericResource" FullName="Microsoft.Azure.Management.ResourceManager.Models.GenericResource">
  <TypeSignature Language="C#" Value="public class GenericResource : Microsoft.Azure.Management.ResourceManager.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GenericResource extends Microsoft.Azure.Management.ResourceManager.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
  <TypeSignature Language="VB.NET" Value="Public Class GenericResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type GenericResource = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8f09f-101">Informationen zur Ressource.</span><span class="sxs-lookup"><span data-stu-id="8f09f-101">Resource information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GenericResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.GenericResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8f09f-102">Initialisiert eine neue Instanz der GenericResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8f09f-102">Initializes a new instance of the GenericResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GenericResource (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.ResourceManager.Models.Plan plan = null, object properties = null, string kind = null, string managedBy = null, Microsoft.Azure.Management.ResourceManager.Models.Sku sku = null, Microsoft.Azure.Management.ResourceManager.Models.Identity identity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.ResourceManager.Models.Plan plan, object properties, string kind, string managedBy, class Microsoft.Azure.Management.ResourceManager.Models.Sku sku, class Microsoft.Azure.Management.ResourceManager.Models.Identity identity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.GenericResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.ResourceManager.Models.Plan,System.Object,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.Sku,Microsoft.Azure.Management.ResourceManager.Models.Identity)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.GenericResource : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.ResourceManager.Models.Plan * obj * string * string * Microsoft.Azure.Management.ResourceManager.Models.Sku * Microsoft.Azure.Management.ResourceManager.Models.Identity -&gt; Microsoft.Azure.Management.ResourceManager.Models.GenericResource" Usage="new Microsoft.Azure.Management.ResourceManager.Models.GenericResource (id, name, type, location, tags, plan, properties, kind, managedBy, sku, identity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="plan" Type="Microsoft.Azure.Management.ResourceManager.Models.Plan" />
        <Parameter Name="properties" Type="System.Object" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="managedBy" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.ResourceManager.Models.Sku" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.ResourceManager.Models.Identity" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="8f09f-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="8f09f-103">Resource ID</span></span></param>
        <param name="name"><span data-ttu-id="8f09f-104">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="8f09f-104">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="8f09f-105">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="8f09f-105">Resource type</span></span></param>
        <param name="location"><span data-ttu-id="8f09f-106">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="8f09f-106">Resource location</span></span></param>
        <param name="tags"><span data-ttu-id="8f09f-107">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="8f09f-107">Resource tags</span></span></param>
        <param name="plan"><span data-ttu-id="8f09f-108">Der Plan der Ressource.</span><span class="sxs-lookup"><span data-stu-id="8f09f-108">The plan of the resource.</span></span></param>
        <param name="properties"><span data-ttu-id="8f09f-109">Die Ressourceneigenschaften.</span><span class="sxs-lookup"><span data-stu-id="8f09f-109">The resource properties.</span></span></param>
        <param name="kind"><span data-ttu-id="8f09f-110">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="8f09f-110">The kind of the resource.</span></span></param>
        <param name="managedBy"><span data-ttu-id="8f09f-111">Die ID der Ressource, die diese Ressource verwaltet.</span><span class="sxs-lookup"><span data-stu-id="8f09f-111">ID of the resource that manages this resource.</span></span></param>
        <param name="sku"><span data-ttu-id="8f09f-112">Die SKU der Ressource.</span><span class="sxs-lookup"><span data-stu-id="8f09f-112">The SKU of the resource.</span></span></param>
        <param name="identity"><span data-ttu-id="8f09f-113">Die Identität der Ressource.</span><span class="sxs-lookup"><span data-stu-id="8f09f-113">The identity of the resource.</span></span></param>
        <summary>
            <span data-ttu-id="8f09f-114">Initialisiert eine neue Instanz der GenericResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8f09f-114">Initializes a new instance of the GenericResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.Identity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.Identity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.GenericResource.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As Identity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.ResourceManager.Models.Identity with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.GenericResource.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.Identity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f09f-115">Ruft ab oder legt die Identität der Ressource.</span><span class="sxs-lookup"><span data-stu-id="8f09f-115">Gets or sets the identity of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.GenericResource.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.GenericResource.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f09f-116">Ruft ab oder legt die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="8f09f-116">Gets or sets the kind of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedBy">
      <MemberSignature Language="C#" Value="public string ManagedBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ManagedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.GenericResource.ManagedBy" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedBy As String" />
      <MemberSignature Language="F#" Value="member this.ManagedBy : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.GenericResource.ManagedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="managedBy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f09f-117">Ruft ab oder legt die ID der Ressource, die diese Ressource verwaltet.</span><span class="sxs-lookup"><span data-stu-id="8f09f-117">Gets or sets ID of the resource that manages this resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Plan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.Plan Plan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.Plan Plan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.GenericResource.Plan" />
      <MemberSignature Language="VB.NET" Value="Public Property Plan As Plan" />
      <MemberSignature Language="F#" Value="member this.Plan : Microsoft.Azure.Management.ResourceManager.Models.Plan with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.GenericResource.Plan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="plan")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.Plan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f09f-118">Ruft ab oder legt den Plan der Ressource.</span><span class="sxs-lookup"><span data-stu-id="8f09f-118">Gets or sets the plan of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public object Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.GenericResource.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As Object" />
      <MemberSignature Language="F#" Value="member this.Properties : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.GenericResource.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f09f-119">Ruft ab oder legt die Ressourceneigenschaften.</span><span class="sxs-lookup"><span data-stu-id="8f09f-119">Gets or sets the resource properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.GenericResource.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.ResourceManager.Models.Sku with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.GenericResource.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f09f-120">Ruft ab oder legt die SKU der Ressource.</span><span class="sxs-lookup"><span data-stu-id="8f09f-120">Gets or sets the SKU of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.GenericResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="genericResource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8f09f-121">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="8f09f-121">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f09f-122">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="8f09f-122">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>