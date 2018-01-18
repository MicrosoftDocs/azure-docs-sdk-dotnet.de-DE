<Type Name="ManagementGroup" FullName="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup">
  <TypeSignature Language="C#" Value="public class ManagementGroup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagementGroup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagementGroup" />
  <TypeSignature Language="F#" Value="type ManagementGroup = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="942dc-101">Die Details der Verwaltung.</span><span class="sxs-lookup"><span data-stu-id="942dc-101">The management group details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="942dc-102">Initialisiert eine neue Instanz der Klasse ManagementGroup wird aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="942dc-102">Initializes a new instance of the ManagementGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementGroup (string id = null, string type = null, Nullable&lt;Guid&gt; name = null, Nullable&lt;Guid&gt; tenantId = null, string displayName = null, Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string type, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; name, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; tenantId, string displayName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.#ctor(System.String,System.String,System.Nullable{System.Guid},System.Nullable{System.Guid},System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional type As String = null, Optional name As Nullable(Of Guid) = null, Optional tenantId As Nullable(Of Guid) = null, Optional displayName As String = null, Optional details As ManagementGroupDetailsProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup : string * string * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup (id, type, name, tenantId, displayName, details)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="name" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="tenantId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="details" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="942dc-103">Die ID der Verwaltungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="942dc-103">The ID of the management group.</span></span> <span data-ttu-id="942dc-104">Beispiel:</span><span class="sxs-lookup"><span data-stu-id="942dc-104">E.g.</span></span>
            <span data-ttu-id="942dc-105">/Providers/Microsoft.Management/managementGroups/20000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="942dc-105">/providers/Microsoft.Management/managementGroups/20000000-0000-0000-0000-000000000000</span></span></param>
        <param name="type"><span data-ttu-id="942dc-106">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="942dc-106">The type of the resource.</span></span> <span data-ttu-id="942dc-107">Beispiel:</span><span class="sxs-lookup"><span data-stu-id="942dc-107">E.g.</span></span>
            <span data-ttu-id="942dc-108">/Providers/Microsoft.Management/managementGroups</span><span class="sxs-lookup"><span data-stu-id="942dc-108">/providers/Microsoft.Management/managementGroups</span></span></param>
        <param name="name"><span data-ttu-id="942dc-109">Der Name der Verwaltungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="942dc-109">The name of the management group.</span></span> <span data-ttu-id="942dc-110">Beispiel:</span><span class="sxs-lookup"><span data-stu-id="942dc-110">E.g.</span></span>
            <span data-ttu-id="942dc-111">20000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="942dc-111">20000000-0000-0000-0000-000000000000</span></span></param>
        <param name="tenantId"><span data-ttu-id="942dc-112">Die AAD-Mandanten-ID der Verwaltungsgruppe zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="942dc-112">The AAD Tenant ID associated with the management group.</span></span> <span data-ttu-id="942dc-113">Beispiel:</span><span class="sxs-lookup"><span data-stu-id="942dc-113">E.g.</span></span> <span data-ttu-id="942dc-114">10000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="942dc-114">10000000-0000-0000-0000-000000000000</span></span></param>
        <param name="displayName"><span data-ttu-id="942dc-115">Der angezeigte Name der Verwaltungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="942dc-115">The friendly name of the management group.</span></span></param>
        <param name="details"><span data-ttu-id="942dc-116">Details</span><span class="sxs-lookup"><span data-stu-id="942dc-116">Details</span></span></param>
        <summary>
            <span data-ttu-id="942dc-117">Initialisiert eine neue Instanz der Klasse ManagementGroup wird aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="942dc-117">Initializes a new instance of the ManagementGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As ManagementGroupDetailsProperties" />
      <MemberSignature Language="F#" Value="member this.Details : Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="942dc-118">Ruft ab oder legt Sie Details fest.</span><span class="sxs-lookup"><span data-stu-id="942dc-118">Gets or sets details</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="942dc-119">Ruft ab oder legt den Anzeigenamen der Verwaltungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="942dc-119">Gets or sets the friendly name of the management group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.Id" />
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
            <span data-ttu-id="942dc-120">Ruft die ID der Verwaltungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="942dc-120">Gets the ID of the management group.</span></span> <span data-ttu-id="942dc-121">Beispiel:</span><span class="sxs-lookup"><span data-stu-id="942dc-121">E.g.</span></span>
            <span data-ttu-id="942dc-122">/Providers/Microsoft.Management/managementGroups/20000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="942dc-122">/providers/Microsoft.Management/managementGroups/20000000-0000-0000-0000-000000000000</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.Name : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.Name" />
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
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="942dc-123">Ruft den Namen der Verwaltungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="942dc-123">Gets the name of the management group.</span></span> <span data-ttu-id="942dc-124">Beispiel:</span><span class="sxs-lookup"><span data-stu-id="942dc-124">E.g.</span></span>
            <span data-ttu-id="942dc-125">20000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="942dc-125">20000000-0000-0000-0000-000000000000</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; TenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.TenantId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="942dc-126">Ruft ab oder legt die AAD-Mandanten-ID der Verwaltungsgruppe zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="942dc-126">Gets or sets the AAD Tenant ID associated with the management group.</span></span> <span data-ttu-id="942dc-127">Beispiel:</span><span class="sxs-lookup"><span data-stu-id="942dc-127">E.g.</span></span> <span data-ttu-id="942dc-128">10000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="942dc-128">10000000-0000-0000-0000-000000000000</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="942dc-129">Ruft den Typ der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="942dc-129">Gets the type of the resource.</span></span> <span data-ttu-id="942dc-130">Beispiel:</span><span class="sxs-lookup"><span data-stu-id="942dc-130">E.g.</span></span>
            <span data-ttu-id="942dc-131">/Providers/Microsoft.Management/managementGroups</span><span class="sxs-lookup"><span data-stu-id="942dc-131">/providers/Microsoft.Management/managementGroups</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>