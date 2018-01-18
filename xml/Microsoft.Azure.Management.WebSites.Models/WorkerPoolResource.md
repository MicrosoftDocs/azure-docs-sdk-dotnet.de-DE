<Type Name="WorkerPoolResource" FullName="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource">
  <TypeSignature Language="C#" Value="public class WorkerPoolResource : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WorkerPoolResource extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
  <TypeSignature Language="VB.NET" Value="Public Class WorkerPoolResource&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type WorkerPoolResource = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="559c9-101">Workerpool einer App Service-Umgebung ARM-Ressource.</span><span class="sxs-lookup"><span data-stu-id="559c9-101">Worker pool of an App Service Environment ARM resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WorkerPoolResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="559c9-102">Initialisiert eine neue Instanz der WorkerPoolResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="559c9-102">Initializes a new instance of the WorkerPoolResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WorkerPoolResource (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;int&gt; workerSizeId = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; computeMode = null, string workerSize = null, Nullable&lt;int&gt; workerCount = null, System.Collections.Generic.IList&lt;string&gt; instanceNames = null, Microsoft.Azure.Management.WebSites.Models.SkuDescription sku = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;int32&gt; workerSizeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; computeMode, string workerSize, valuetype System.Nullable`1&lt;int32&gt; workerCount, class System.Collections.Generic.IList`1&lt;string&gt; instanceNames, class Microsoft.Azure.Management.WebSites.Models.SkuDescription sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions},System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.WebSites.Models.SkuDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional workerSizeId As Nullable(Of Integer) = null, Optional computeMode As Nullable(Of ComputeModeOptions) = null, Optional workerSize As String = null, Optional workerCount As Nullable(Of Integer) = null, Optional instanceNames As IList(Of String) = null, Optional sku As SkuDescription = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource : string * string * string * string * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.WebSites.Models.SkuDescription -&gt; Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" Usage="new Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource (id, name, kind, type, workerSizeId, computeMode, workerSize, workerCount, instanceNames, sku)" />
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
        <Parameter Name="workerSizeId" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="computeMode" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt;" />
        <Parameter Name="workerSize" Type="System.String" />
        <Parameter Name="workerCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="instanceNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.WebSites.Models.SkuDescription" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="559c9-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="559c9-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="559c9-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="559c9-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="559c9-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="559c9-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="559c9-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="559c9-106">Resource type.</span></span></param>
        <param name="workerSizeId"><span data-ttu-id="559c9-107">Workergrößen-ID zum Verweisen auf diese workerpool.</span><span class="sxs-lookup"><span data-stu-id="559c9-107">Worker size ID for referencing this worker pool.</span></span></param>
        <param name="computeMode"><span data-ttu-id="559c9-108">Freigegeben oder dediziert app gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="559c9-108">Shared or dedicated app hosting.</span></span> <span data-ttu-id="559c9-109">Folgende Werte sind möglich: "Shared", "Reserviert", "Dynamic"</span><span class="sxs-lookup"><span data-stu-id="559c9-109">Possible values include: 'Shared', 'Dedicated', 'Dynamic'</span></span></param>
        <param name="workerSize"><span data-ttu-id="559c9-110">VM-Größe der Pool-Worker-Instanzen.</span><span class="sxs-lookup"><span data-stu-id="559c9-110">VM size of the worker pool instances.</span></span></param>
        <param name="workerCount"><span data-ttu-id="559c9-111">Die Anzahl der Instanzen in der workerpool.</span><span class="sxs-lookup"><span data-stu-id="559c9-111">Number of instances in the worker pool.</span></span></param>
        <param name="instanceNames"><span data-ttu-id="559c9-112">Die Namen aller Instanzen in der workerpool (schreibgeschützt).</span><span class="sxs-lookup"><span data-stu-id="559c9-112">Names of all instances in the worker pool (read only).</span></span></param>
        <param name="sku">To be added.</param>
        <summary>
            <span data-ttu-id="559c9-113">Initialisiert eine neue Instanz der WorkerPoolResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="559c9-113">Initializes a new instance of the WorkerPoolResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; ComputeMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; ComputeMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.ComputeMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputeMode As Nullable(Of ComputeModeOptions)" />
      <MemberSignature Language="F#" Value="member this.ComputeMode : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.ComputeMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.computeMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="559c9-114">Ruft ab, oder legt sie fest, freigegeben oder dediziert app hosten.</span><span class="sxs-lookup"><span data-stu-id="559c9-114">Gets or sets shared or dedicated app hosting.</span></span> <span data-ttu-id="559c9-115">Folgende Werte sind möglich: "Shared", "Reserviert", "Dynamic"</span><span class="sxs-lookup"><span data-stu-id="559c9-115">Possible values include: 'Shared', 'Dedicated', 'Dynamic'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; InstanceNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; InstanceNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.InstanceNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.InstanceNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.InstanceNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.instanceNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="559c9-116">Ruft die Namen aller Instanzen in der workerpool (schreibgeschützt).</span><span class="sxs-lookup"><span data-stu-id="559c9-116">Gets names of all instances in the worker pool (read only).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SkuDescription Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SkuDescription Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As SkuDescription" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.WebSites.Models.SkuDescription with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SkuDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; WorkerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; WorkerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.WorkerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.WorkerCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.WorkerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.workerCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="559c9-117">Ruft ab, oder legt Sie Anzahl der Instanzen in der workerpool fest.</span><span class="sxs-lookup"><span data-stu-id="559c9-117">Gets or sets number of instances in the worker pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerSize">
      <MemberSignature Language="C#" Value="public string WorkerSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkerSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.WorkerSize" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerSize As String" />
      <MemberSignature Language="F#" Value="member this.WorkerSize : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.WorkerSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.workerSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="559c9-118">Abrufen oder Festlegen der VM-Größe der Pool-Worker-Instanzen.</span><span class="sxs-lookup"><span data-stu-id="559c9-118">Gets or sets VM size of the worker pool instances.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerSizeId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; WorkerSizeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; WorkerSizeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.WorkerSizeId" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerSizeId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.WorkerSizeId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.WorkerSizeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.workerSizeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="559c9-119">Ruft ab, oder legt Sie workergrößen-ID zum Verweisen auf diese workerpool fest.</span><span class="sxs-lookup"><span data-stu-id="559c9-119">Gets or sets worker size ID for referencing this worker pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>