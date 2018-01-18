<Type Name="EHNamespace" FullName="Microsoft.Azure.Management.EventHub.Models.EHNamespace">
  <TypeSignature Language="C#" Value="public class EHNamespace : Microsoft.Azure.Management.EventHub.Models.TrackedResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EHNamespace extends Microsoft.Azure.Management.EventHub.Models.TrackedResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventHub.Models.EHNamespace" />
  <TypeSignature Language="VB.NET" Value="Public Class EHNamespace&#xA;Inherits TrackedResource" />
  <TypeSignature Language="F#" Value="type EHNamespace = class&#xA;    inherit TrackedResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.EventHub.Models.TrackedResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e8e86-101">Einzelnes Namespace-Element in der Liste "oder" Get-Vorgang</span><span class="sxs-lookup"><span data-stu-id="e8e86-101">Single Namespace item in List or Get Operation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EHNamespace ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.EHNamespace.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e8e86-102">Initialisiert eine neue Instanz der EHNamespace-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e8e86-102">Initializes a new instance of the EHNamespace class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EHNamespace (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.EventHub.Models.Sku sku = null, string provisioningState = null, Nullable&lt;DateTime&gt; createdAt = null, Nullable&lt;DateTime&gt; updatedAt = null, string serviceBusEndpoint = null, string metricId = null, Nullable&lt;bool&gt; isAutoInflateEnabled = null, Nullable&lt;int&gt; maximumThroughputUnits = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.EventHub.Models.Sku sku, string provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updatedAt, string serviceBusEndpoint, string metricId, valuetype System.Nullable`1&lt;bool&gt; isAutoInflateEnabled, valuetype System.Nullable`1&lt;int32&gt; maximumThroughputUnits) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.EHNamespace.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.EventHub.Models.Sku,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventHub.Models.EHNamespace : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.EventHub.Models.Sku * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;bool&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.EventHub.Models.EHNamespace" Usage="new Microsoft.Azure.Management.EventHub.Models.EHNamespace (id, name, type, location, tags, sku, provisioningState, createdAt, updatedAt, serviceBusEndpoint, metricId, isAutoInflateEnabled, maximumThroughputUnits)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.EventHub.Models.Sku" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updatedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="serviceBusEndpoint" Type="System.String" />
        <Parameter Name="metricId" Type="System.String" />
        <Parameter Name="isAutoInflateEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="maximumThroughputUnits" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="e8e86-103">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="e8e86-103">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="e8e86-104">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="e8e86-104">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="e8e86-105">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="e8e86-105">Resource type</span></span></param>
        <param name="location"><span data-ttu-id="e8e86-106">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="e8e86-106">Resource location</span></span></param>
        <param name="tags"><span data-ttu-id="e8e86-107">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="e8e86-107">Resource tags</span></span></param>
        <param name="sku"><span data-ttu-id="e8e86-108">Eigenschaften der Sku-Ressource</span><span class="sxs-lookup"><span data-stu-id="e8e86-108">Properties of sku resource</span></span></param>
        <param name="provisioningState"><span data-ttu-id="e8e86-109">Der Bereitstellungsstatus der der Namespace.</span><span class="sxs-lookup"><span data-stu-id="e8e86-109">Provisioning state of the Namespace.</span></span></param>
        <param name="createdAt"><span data-ttu-id="e8e86-110">Der Zeitpunkt, zu dem Namespace erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="e8e86-110">The time the Namespace was created.</span></span></param>
        <param name="updatedAt"><span data-ttu-id="e8e86-111">Der Zeitpunkt, zu dem Namespace aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="e8e86-111">The time the Namespace was updated.</span></span></param>
        <param name="serviceBusEndpoint"><span data-ttu-id="e8e86-112">Der Endpunkt, den Sie verwenden können, um Service Bus-Vorgänge auszuführen.</span><span class="sxs-lookup"><span data-stu-id="e8e86-112">Endpoint you can use to perform Service Bus operations.</span></span></param>
        <param name="metricId"><span data-ttu-id="e8e86-113">Der Bezeichner für die Azure Insights Metriken.</span><span class="sxs-lookup"><span data-stu-id="e8e86-113">Identifier for Azure Insights metrics.</span></span></param>
        <param name="isAutoInflateEnabled"><span data-ttu-id="e8e86-114">Ein Wert, der angibt, ob AutoInflate für Eventhub-Namespace aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="e8e86-114">Value that indicates whether AutoInflate is enabled for eventhub namespace.</span></span></param>
        <param name="maximumThroughputUnits"><span data-ttu-id="e8e86-115">Die Obergrenze der durchsatzeinheiten, wenn die AutoInflate aktiviert ist, sollten innerhalb von 0 bis 20 durchsatzeinheiten Wert sein.</span><span class="sxs-lookup"><span data-stu-id="e8e86-115">Upper limit of throughput units when AutoInflate is enabled, vaule should be within 0 to 20 throughput units.</span></span> <span data-ttu-id="e8e86-116">("0", wenn AutoInflateEnabled = "true")</span><span class="sxs-lookup"><span data-stu-id="e8e86-116">( '0' if AutoInflateEnabled = true)</span></span></param>
        <summary>
            <span data-ttu-id="e8e86-117">Initialisiert eine neue Instanz der EHNamespace-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e8e86-117">Initializes a new instance of the EHNamespace class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.EHNamespace.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.EventHub.Models.EHNamespace.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8e86-118">Ruft den Zeitpunkt der Erstellung der Namespace ab.</span><span class="sxs-lookup"><span data-stu-id="e8e86-118">Gets the time the Namespace was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAutoInflateEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsAutoInflateEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsAutoInflateEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.EHNamespace.IsAutoInflateEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAutoInflateEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsAutoInflateEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.EHNamespace.IsAutoInflateEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isAutoInflateEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8e86-119">Wert abgerufen oder festgelegt, der angibt, ob AutoInflate für Eventhub-Namespace aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="e8e86-119">Gets or sets value that indicates whether AutoInflate is enabled for eventhub namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumThroughputUnits">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaximumThroughputUnits { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaximumThroughputUnits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.EHNamespace.MaximumThroughputUnits" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumThroughputUnits As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaximumThroughputUnits : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.EHNamespace.MaximumThroughputUnits" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maximumThroughputUnits")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8e86-120">Ruft ab oder legt einen oberen Grenzwert der durchsatzeinheiten, wenn die AutoInflate aktiviert ist, muss Wert innerhalb von 0 bis 20 durchsatzeinheiten.</span><span class="sxs-lookup"><span data-stu-id="e8e86-120">Gets or sets upper limit of throughput units when AutoInflate is enabled, vaule should be within 0 to 20 throughput units.</span></span> <span data-ttu-id="e8e86-121">("0", wenn AutoInflateEnabled = "true")</span><span class="sxs-lookup"><span data-stu-id="e8e86-121">( '0' if AutoInflateEnabled = true)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricId">
      <MemberSignature Language="C#" Value="public string MetricId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MetricId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.EHNamespace.MetricId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MetricId As String" />
      <MemberSignature Language="F#" Value="member this.MetricId : string" Usage="Microsoft.Azure.Management.EventHub.Models.EHNamespace.MetricId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metricId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8e86-122">Ruft den Bezeichner für Azure Insights-Metriken ab.</span><span class="sxs-lookup"><span data-stu-id="e8e86-122">Gets identifier for Azure Insights metrics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.EHNamespace.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.EventHub.Models.EHNamespace.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="e8e86-123">Status der der Namespace ruft bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="e8e86-123">Gets provisioning state of the Namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusEndpoint">
      <MemberSignature Language="C#" Value="public string ServiceBusEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.EHNamespace.ServiceBusEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceBusEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusEndpoint : string" Usage="Microsoft.Azure.Management.EventHub.Models.EHNamespace.ServiceBusEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceBusEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8e86-124">Ruft die Endpunkt, den Sie verwenden können, um Service Bus-Vorgänge auszuführen.</span><span class="sxs-lookup"><span data-stu-id="e8e86-124">Gets endpoint you can use to perform Service Bus operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.EventHub.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.EventHub.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.EHNamespace.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.EventHub.Models.Sku with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.EHNamespace.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8e86-125">Ruft ab oder legt die Eigenschaften Sku-Ressource</span><span class="sxs-lookup"><span data-stu-id="e8e86-125">Gets or sets properties of sku resource</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.EHNamespace.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.EventHub.Models.EHNamespace.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.updatedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8e86-126">Ruft die Zeit ab, an die den Namespace aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="e8e86-126">Gets the time the Namespace was updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.EHNamespace.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="eHNamespace.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e8e86-127">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="e8e86-127">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e8e86-128">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="e8e86-128">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>