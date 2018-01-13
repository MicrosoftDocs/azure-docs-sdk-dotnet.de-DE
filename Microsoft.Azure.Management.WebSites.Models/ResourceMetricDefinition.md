<Type Name="ResourceMetricDefinition" FullName="Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition">
  <TypeSignature Language="C#" Value="public class ResourceMetricDefinition : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceMetricDefinition extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceMetricDefinition&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type ResourceMetricDefinition = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="95aea-101">Die Metadaten für die Metriken.</span><span class="sxs-lookup"><span data-stu-id="95aea-101">Metadata for the metrics.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceMetricDefinition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="95aea-102">Initialisiert eine neue Instanz der ResourceMetricDefinition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="95aea-102">Initializes a new instance of the ResourceMetricDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceMetricDefinition (string id = null, string name = null, string kind = null, string type = null, Microsoft.Azure.Management.WebSites.Models.ResourceMetricName resourceMetricDefinitionName = null, string unit = null, string primaryAggregationType = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricAvailability&gt; metricAvailabilities = null, string resourceUri = null, string resourceMetricDefinitionId = null, System.Collections.Generic.IDictionary&lt;string,string&gt; properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, class Microsoft.Azure.Management.WebSites.Models.ResourceMetricName resourceMetricDefinitionName, string unit, string primaryAggregationType, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricAvailability&gt; metricAvailabilities, string resourceUri, string resourceMetricDefinitionId, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.ResourceMetricName,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.ResourceMetricAvailability},System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional resourceMetricDefinitionName As ResourceMetricName = null, Optional unit As String = null, Optional primaryAggregationType As String = null, Optional metricAvailabilities As IList(Of ResourceMetricAvailability) = null, Optional resourceUri As String = null, Optional resourceMetricDefinitionId As String = null, Optional properties As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition : string * string * string * string * Microsoft.Azure.Management.WebSites.Models.ResourceMetricName * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricAvailability&gt; * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition" Usage="new Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition (id, name, kind, type, resourceMetricDefinitionName, unit, primaryAggregationType, metricAvailabilities, resourceUri, resourceMetricDefinitionId, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="resourceMetricDefinitionName" Type="Microsoft.Azure.Management.WebSites.Models.ResourceMetricName" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="primaryAggregationType" Type="System.String" />
        <Parameter Name="metricAvailabilities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricAvailability&gt;" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="resourceMetricDefinitionId" Type="System.String" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="95aea-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="95aea-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="95aea-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="95aea-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="95aea-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="95aea-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="95aea-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="95aea-106">Resource type.</span></span></param>
        <param name="resourceMetricDefinitionName"><span data-ttu-id="95aea-107">Der Name der Metrik.</span><span class="sxs-lookup"><span data-stu-id="95aea-107">Name of the metric.</span></span></param>
        <param name="unit"><span data-ttu-id="95aea-108">Maßeinheit der Metrik.</span><span class="sxs-lookup"><span data-stu-id="95aea-108">Unit of the metric.</span></span></param>
        <param name="primaryAggregationType"><span data-ttu-id="95aea-109">Primäre Aggregationstyp.</span><span class="sxs-lookup"><span data-stu-id="95aea-109">Primary aggregation type.</span></span></param>
        <param name="metricAvailabilities"><span data-ttu-id="95aea-110">Liste der Zeit Körner für die Metrik zusammen mit der Beibehaltungsdauer unterstützt.</span><span class="sxs-lookup"><span data-stu-id="95aea-110">List of time grains supported for the metric together with retention period.</span></span></param>
        <param name="resourceUri"><span data-ttu-id="95aea-111">Der Ressourcen-URI.</span><span class="sxs-lookup"><span data-stu-id="95aea-111">Resource URI.</span></span></param>
        <param name="resourceMetricDefinitionId"><span data-ttu-id="95aea-112">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="95aea-112">Resource ID.</span></span></param>
        <param name="properties"><span data-ttu-id="95aea-113">Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="95aea-113">Properties.</span></span></param>
        <summary>
            <span data-ttu-id="95aea-114">Initialisiert eine neue Instanz der ResourceMetricDefinition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="95aea-114">Initializes a new instance of the ResourceMetricDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricAvailabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricAvailability&gt; MetricAvailabilities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricAvailability&gt; MetricAvailabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition.MetricAvailabilities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MetricAvailabilities As IList(Of ResourceMetricAvailability)" />
      <MemberSignature Language="F#" Value="member this.MetricAvailabilities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricAvailability&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition.MetricAvailabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metricAvailabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricAvailability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95aea-115">Ruft die Liste Zeit Körner unterstützt für die Metrik zusammen mit der Beibehaltungsdauer ab.</span><span class="sxs-lookup"><span data-stu-id="95aea-115">Gets list of time grains supported for the metric together with retention period.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryAggregationType">
      <MemberSignature Language="C#" Value="public string PrimaryAggregationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryAggregationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition.PrimaryAggregationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryAggregationType As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryAggregationType : string" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition.PrimaryAggregationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primaryAggregationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95aea-116">Ruft die primäre Aggregationstyp ab.</span><span class="sxs-lookup"><span data-stu-id="95aea-116">Gets primary aggregation type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95aea-117">Ruft Eigenschaften ab.</span><span class="sxs-lookup"><span data-stu-id="95aea-117">Gets properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceMetricDefinitionId">
      <MemberSignature Language="C#" Value="public string ResourceMetricDefinitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceMetricDefinitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition.ResourceMetricDefinitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceMetricDefinitionId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceMetricDefinitionId : string" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition.ResourceMetricDefinitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95aea-118">Ruft die Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="95aea-118">Gets resource ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceMetricDefinitionName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.ResourceMetricName ResourceMetricDefinitionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.ResourceMetricName ResourceMetricDefinitionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition.ResourceMetricDefinitionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceMetricDefinitionName As ResourceMetricName" />
      <MemberSignature Language="F#" Value="member this.ResourceMetricDefinitionName : Microsoft.Azure.Management.WebSites.Models.ResourceMetricName" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition.ResourceMetricDefinitionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.ResourceMetricName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95aea-119">Ruft den Namen der Metrik.</span><span class="sxs-lookup"><span data-stu-id="95aea-119">Gets name of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceUri">
      <MemberSignature Language="C#" Value="public string ResourceUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition.ResourceUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceUri As String" />
      <MemberSignature Language="F#" Value="member this.ResourceUri : string" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition.ResourceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95aea-120">Ruft die Ressourcen-URI ab.</span><span class="sxs-lookup"><span data-stu-id="95aea-120">Gets resource URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95aea-121">Ruft die Maßeinheit der Metrik.</span><span class="sxs-lookup"><span data-stu-id="95aea-121">Gets unit of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>