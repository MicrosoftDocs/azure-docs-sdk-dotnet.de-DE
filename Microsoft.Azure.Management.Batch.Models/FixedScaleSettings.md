<Type Name="FixedScaleSettings" FullName="Microsoft.Azure.Management.Batch.Models.FixedScaleSettings">
  <TypeSignature Language="C#" Value="public class FixedScaleSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FixedScaleSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.FixedScaleSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class FixedScaleSettings" />
  <TypeSignature Language="F#" Value="type FixedScaleSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="884e9-101">Feste skalierungseinstellungen für den Pool.</span><span class="sxs-lookup"><span data-stu-id="884e9-101">Fixed scale settings for the pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FixedScaleSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="884e9-102">Initialisiert eine neue Instanz der FixedScaleSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="884e9-102">Initializes a new instance of the FixedScaleSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FixedScaleSettings (Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;int&gt; targetDedicatedNodes = null, Nullable&lt;int&gt; targetLowPriorityNodes = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; nodeDeallocationOption = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityNodes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; nodeDeallocationOption) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.#ctor(System.Nullable{System.TimeSpan},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional targetDedicatedNodes As Nullable(Of Integer) = null, Optional targetLowPriorityNodes As Nullable(Of Integer) = null, Optional nodeDeallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.FixedScaleSettings : Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; -&gt; Microsoft.Azure.Management.Batch.Models.FixedScaleSettings" Usage="new Microsoft.Azure.Management.Batch.Models.FixedScaleSettings (resizeTimeout, targetDedicatedNodes, targetLowPriorityNodes, nodeDeallocationOption)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="targetDedicatedNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="nodeDeallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt;" />
      </Parameters>
      <Docs>
        <param name="resizeTimeout"><span data-ttu-id="884e9-103">Das Timeout für die Zuweisung von Serverknoten in den Pool.</span><span class="sxs-lookup"><span data-stu-id="884e9-103">The timeout for allocation of compute nodes to the pool.</span></span></param>
        <param name="targetDedicatedNodes"><span data-ttu-id="884e9-104">Die gewünschte Anzahl von dedizierten Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="884e9-104">The desired number of dedicated compute nodes in the pool.</span></span></param>
        <param name="targetLowPriorityNodes"><span data-ttu-id="884e9-105">Die gewünschte Anzahl von mit niedriger Priorität Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="884e9-105">The desired number of low-priority compute nodes in the pool.</span></span></param>
        <param name="nodeDeallocationOption"><span data-ttu-id="884e9-106">Bestimmt, was mit einem Knoten und seine ausgeführten Tasks geschehen, wenn Verkleinerung des Pools.</span><span class="sxs-lookup"><span data-stu-id="884e9-106">Determines what to do with a node and its running task(s) if the pool size is decreasing.</span></span></param>
        <summary>
            <span data-ttu-id="884e9-107">Initialisiert eine neue Instanz der FixedScaleSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="884e9-107">Initializes a new instance of the FixedScaleSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDeallocationOption">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; NodeDeallocationOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; NodeDeallocationOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.NodeDeallocationOption" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeDeallocationOption As Nullable(Of ComputeNodeDeallocationOption)" />
      <MemberSignature Language="F#" Value="member this.NodeDeallocationOption : Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.NodeDeallocationOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeDeallocationOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="884e9-108">Ruft ab oder legt bestimmt, was mit einem Knoten und seine ausgeführten Tasks geschehen, wenn Verkleinerung des Pools.</span><span class="sxs-lookup"><span data-stu-id="884e9-108">Gets or sets determines what to do with a node and its running task(s) if the pool size is decreasing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="884e9-109">Wenn nicht angegeben, ist der Standardwert wieder in Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="884e9-109">If omitted, the default value is Requeue.</span></span> <span data-ttu-id="884e9-110">Folgende Werte sind möglich: "Requeue", "Beenden", "TaskCompletion", "RetainedData"</span><span class="sxs-lookup"><span data-stu-id="884e9-110">Possible values include: 'Requeue', 'Terminate', 'TaskCompletion', 'RetainedData'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ResizeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ResizeTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.ResizeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ResizeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.ResizeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resizeTimeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="884e9-111">Ruft ab oder legt das Timeout für die Zuweisung von Serverknoten in den Pool.</span><span class="sxs-lookup"><span data-stu-id="884e9-111">Gets or sets the timeout for allocation of compute nodes to the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="884e9-112">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="884e9-112">The default value is 15 minutes.</span></span> <span data-ttu-id="884e9-113">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="884e9-113">The minimum value is 5 minutes.</span></span> <span data-ttu-id="884e9-114">Wenn Sie einen Wert kleiner als 5 Minuten angeben, weist der Batch-Dienst die Anforderung mit einem Fehler zurück; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung).</span><span class="sxs-lookup"><span data-stu-id="884e9-114">If you specify a value less than 5 minutes, the Batch service rejects the request with an error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicatedNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicatedNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicatedNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.TargetDedicatedNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicatedNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicatedNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.TargetDedicatedNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetDedicatedNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="884e9-115">Ruft ab oder legt die gewünschte Anzahl von dedizierten Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="884e9-115">Gets or sets the desired number of dedicated compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="884e9-116">Mindestens eine der TargetDedicatedNodes, müssen es sich um TargetLowPriority Knoten festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="884e9-116">At least one of targetDedicatedNodes, targetLowPriority nodes must be set.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLowPriorityNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetLowPriorityNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetLowPriorityNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.TargetLowPriorityNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLowPriorityNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetLowPriorityNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.TargetLowPriorityNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetLowPriorityNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="884e9-117">Ruft ab oder legt die gewünschte Anzahl von Serverknoten mit niedriger Priorität im Pool.</span><span class="sxs-lookup"><span data-stu-id="884e9-117">Gets or sets the desired number of low-priority compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="884e9-118">Mindestens eine der TargetDedicatedNodes, müssen es sich um TargetLowPriority Knoten festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="884e9-118">At least one of targetDedicatedNodes, targetLowPriority nodes must be set.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>