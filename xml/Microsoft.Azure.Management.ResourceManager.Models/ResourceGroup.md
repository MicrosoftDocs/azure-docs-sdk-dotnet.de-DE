<Type Name="ResourceGroup" FullName="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup">
  <TypeSignature Language="C#" Value="public class ResourceGroup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceGroup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceGroup" />
  <TypeSignature Language="F#" Value="type ResourceGroup = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0705c-101">Informationen zur Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="0705c-101">Resource group information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0705c-102">Initialisiert eine neue Instanz der ResourceGroup-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0705c-102">Initializes a new instance of the ResourceGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceGroup (string location, string id = null, string name = null, Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties properties = null, string managedBy = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties properties, string managedBy, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional properties As ResourceGroupProperties = null, Optional managedBy As String = null, Optional tags As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup : string * string * string * Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup (location, id, name, properties, managedBy, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties" />
        <Parameter Name="managedBy" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="0705c-103">Der Speicherort der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="0705c-103">The location of the resource group.</span></span> <span data-ttu-id="0705c-104">Es kann nicht geändert werden, nachdem die Ressourcengruppe erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="0705c-104">It cannot be changed after the resource group has been created.</span></span> <span data-ttu-id="0705c-105">Es Muct eines unterstützten Azure-Standorte sein.</span><span class="sxs-lookup"><span data-stu-id="0705c-105">It muct be one of the supported Azure locations.</span></span></param>
        <param name="id"><span data-ttu-id="0705c-106">Die ID der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="0705c-106">The ID of the resource group.</span></span></param>
        <param name="name"><span data-ttu-id="0705c-107">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="0705c-107">The name of the resource group.</span></span></param>
        <param name="properties">To be added.</param>
        <param name="managedBy"><span data-ttu-id="0705c-108">Die ID der Ressource, die diese Ressourcengruppe verwaltet.</span><span class="sxs-lookup"><span data-stu-id="0705c-108">The ID of the resource that manages this resource group.</span></span></param>
        <param name="tags"><span data-ttu-id="0705c-109">Die Ressourcengruppe zugeordneten Tags.</span><span class="sxs-lookup"><span data-stu-id="0705c-109">The tags attached to the resource group.</span></span></param>
        <summary>
            <span data-ttu-id="0705c-110">Initialisiert eine neue Instanz der ResourceGroup-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0705c-110">Initializes a new instance of the ResourceGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0705c-111">Ruft die ID der Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="0705c-111">Gets the ID of the resource group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0705c-112">Ruft ab oder legt den Speicherort der Ressourcengruppe fest.</span><span class="sxs-lookup"><span data-stu-id="0705c-112">Gets or sets the location of the resource group.</span></span> <span data-ttu-id="0705c-113">Es kann nicht geändert werden, nachdem die Ressourcengruppe erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="0705c-113">It cannot be changed after the resource group has been created.</span></span> <span data-ttu-id="0705c-114">Es Muct eines unterstützten Azure-Standorte sein.</span><span class="sxs-lookup"><span data-stu-id="0705c-114">It muct be one of the supported Azure locations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedBy">
      <MemberSignature Language="C#" Value="public string ManagedBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ManagedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup.ManagedBy" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedBy As String" />
      <MemberSignature Language="F#" Value="member this.ManagedBy : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup.ManagedBy" />
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
            <span data-ttu-id="0705c-115">Ruft ab oder legt die ID der Ressource, die diese Ressourcengruppe verwaltet.</span><span class="sxs-lookup"><span data-stu-id="0705c-115">Gets or sets the ID of the resource that manages this resource group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="0705c-116">Ruft ab oder legt den Namen der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="0705c-116">Gets or sets the name of the resource group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As ResourceGroupProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup.Properties" />
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
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0705c-117">Abrufen oder Festlegen der Ressourcengruppe zugeordneten Tags.</span><span class="sxs-lookup"><span data-stu-id="0705c-117">Gets or sets the tags attached to the resource group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceGroup.Validate " />
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
            <span data-ttu-id="0705c-118">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="0705c-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0705c-119">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="0705c-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>