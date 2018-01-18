<Type Name="WorkerPoolResourceInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner">
  <TypeSignature Language="C#" Value="public class WorkerPoolResourceInner : Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WorkerPoolResourceInner extends Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner" />
  <TypeSignature Language="VB.NET" Value="Public Class WorkerPoolResourceInner&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type WorkerPoolResourceInner = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="41846-101">Workerpool einer App Service-Umgebung ARM-Ressource.</span><span class="sxs-lookup"><span data-stu-id="41846-101">Worker pool of an App Service Environment ARM resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WorkerPoolResourceInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="41846-102">Initialisiert eine neue Instanz der WorkerPoolResourceInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="41846-102">Initializes a new instance of the WorkerPoolResourceInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WorkerPoolResourceInner (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;int&gt; workerSizeId = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ComputeModeOptions&gt; computeMode = null, string workerSize = null, Nullable&lt;int&gt; workerCount = null, System.Collections.Generic.IList&lt;string&gt; instanceNames = null, Microsoft.Azure.Management.AppService.Fluent.Models.SkuDescription sku = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;int32&gt; workerSizeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ComputeModeOptions&gt; computeMode, string workerSize, valuetype System.Nullable`1&lt;int32&gt; workerCount, class System.Collections.Generic.IList`1&lt;string&gt; instanceNames, class Microsoft.Azure.Management.AppService.Fluent.Models.SkuDescription sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.ComputeModeOptions},System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.AppService.Fluent.Models.SkuDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional workerSizeId As Nullable(Of Integer) = null, Optional computeMode As Nullable(Of ComputeModeOptions) = null, Optional workerSize As String = null, Optional workerCount As Nullable(Of Integer) = null, Optional instanceNames As IList(Of String) = null, Optional sku As SkuDescription = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner : string * string * string * string * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ComputeModeOptions&gt; * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.AppService.Fluent.Models.SkuDescription -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner (id, name, kind, type, workerSizeId, computeMode, workerSize, workerCount, instanceNames, sku)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="workerSizeId" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="computeMode" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ComputeModeOptions&gt;" />
        <Parameter Name="workerSize" Type="System.String" />
        <Parameter Name="workerCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="instanceNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.AppService.Fluent.Models.SkuDescription" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="kind">To be added.</param>
        <param name="type">To be added.</param>
        <param name="workerSizeId">To be added.</param>
        <param name="computeMode">To be added.</param>
        <param name="workerSize">To be added.</param>
        <param name="workerCount">To be added.</param>
        <param name="instanceNames">To be added.</param>
        <param name="sku">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ComputeModeOptions&gt; ComputeMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ComputeModeOptions&gt; ComputeMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner.ComputeMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputeMode As Nullable(Of ComputeModeOptions)" />
      <MemberSignature Language="F#" Value="member this.ComputeMode : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ComputeModeOptions&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner.ComputeMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.computeMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ComputeModeOptions&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41846-103">Ruft ab, oder legt sie fest, freigegeben oder dediziert app hosten.</span><span class="sxs-lookup"><span data-stu-id="41846-103">Gets or sets shared or dedicated app hosting.</span></span> <span data-ttu-id="41846-104">Folgende Werte sind möglich: "Shared", "Reserviert", "Dynamic"</span><span class="sxs-lookup"><span data-stu-id="41846-104">Possible values include: 'Shared', 'Dedicated', 'Dynamic'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; InstanceNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; InstanceNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner.InstanceNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.InstanceNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner.InstanceNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="41846-105">Ruft die Namen aller Instanzen in der workerpool (schreibgeschützt).</span><span class="sxs-lookup"><span data-stu-id="41846-105">Gets names of all instances in the worker pool (read only).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.SkuDescription Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.SkuDescription Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As SkuDescription" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.AppService.Fluent.Models.SkuDescription with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.SkuDescription</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner.WorkerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.WorkerCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner.WorkerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="41846-106">Ruft ab, oder legt Sie Anzahl der Instanzen in der workerpool fest.</span><span class="sxs-lookup"><span data-stu-id="41846-106">Gets or sets number of instances in the worker pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerSize">
      <MemberSignature Language="C#" Value="public string WorkerSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkerSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner.WorkerSize" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerSize As String" />
      <MemberSignature Language="F#" Value="member this.WorkerSize : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner.WorkerSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="41846-107">Abrufen oder Festlegen der VM-Größe der Pool-Worker-Instanzen.</span><span class="sxs-lookup"><span data-stu-id="41846-107">Gets or sets VM size of the worker pool instances.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerSizeId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; WorkerSizeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; WorkerSizeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner.WorkerSizeId" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerSizeId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.WorkerSizeId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner.WorkerSizeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="41846-108">Ruft ab, oder legt Sie workergrößen-ID zum Verweisen auf diese workerpool fest.</span><span class="sxs-lookup"><span data-stu-id="41846-108">Gets or sets worker size ID for referencing this worker pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>