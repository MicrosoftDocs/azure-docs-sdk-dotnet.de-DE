<Type Name="AutoPoolSpecification" FullName="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification">
  <TypeSignature Language="C#" Value="public class AutoPoolSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoPoolSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoPoolSpecification" />
  <TypeSignature Language="F#" Value="type AutoPoolSpecification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6c199-101">Gibt die Eigenschaften für eine temporäre "Pools".</span><span class="sxs-lookup"><span data-stu-id="6c199-101">Specifies characteristics for a temporary 'auto pool'.</span></span> <span data-ttu-id="6c199-102">Der Batch-Dienst wird diese Pools erstellt, wenn der Auftrag übermittelt wird.</span><span class="sxs-lookup"><span data-stu-id="6c199-102">The Batch service will create this auto pool when the job is submitted.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoPoolSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6c199-103">Initialisiert eine neue Instanz der AutoPoolSpecification-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6c199-103">Initializes a new instance of the AutoPoolSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoPoolSpecification (Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption poolLifetimeOption, string autoPoolIdPrefix = null, Nullable&lt;bool&gt; keepAlive = null, Microsoft.Azure.Batch.Protocol.Models.PoolSpecification pool = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption poolLifetimeOption, string autoPoolIdPrefix, valuetype System.Nullable`1&lt;bool&gt; keepAlive, class Microsoft.Azure.Batch.Protocol.Models.PoolSpecification pool) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.#ctor(Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.PoolSpecification)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification : Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.PoolSpecification -&gt; Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification" Usage="new Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification (poolLifetimeOption, autoPoolIdPrefix, keepAlive, pool)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="poolLifetimeOption" Type="Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption" />
        <Parameter Name="autoPoolIdPrefix" Type="System.String" />
        <Parameter Name="keepAlive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="pool" Type="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification" />
      </Parameters>
      <Docs>
        <param name="poolLifetimeOption"><span data-ttu-id="6c199-104">Die minimale Lebensdauer der automatisch erstellten Pools und wie mehrere Aufträge nach einem Zeitplan, die den Pools zugewiesen werden.</span><span class="sxs-lookup"><span data-stu-id="6c199-104">The minimum lifetime of created auto pools, and how multiple jobs on a schedule are assigned to pools.</span></span></param>
        <param name="autoPoolIdPrefix"><span data-ttu-id="6c199-105">Ein Präfix, das den eindeutigen Bezeichner hinzugefügt, wenn ein Pool automatisch erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="6c199-105">A prefix to be added to the unique identifier when a pool is automatically created.</span></span></param>
        <param name="keepAlive"><span data-ttu-id="6c199-106">Ob einen automatischer Pool nach Ablauf der Lebensdauer aufrechtzuerhalten.</span><span class="sxs-lookup"><span data-stu-id="6c199-106">Whether to keep an auto pool alive after its lifetime expires.</span></span></param>
        <param name="pool"><span data-ttu-id="6c199-107">Die poolspezifikation für den automatischen Pool.</span><span class="sxs-lookup"><span data-stu-id="6c199-107">The pool specification for the auto pool.</span></span></param>
        <summary>
            <span data-ttu-id="6c199-108">Initialisiert eine neue Instanz der AutoPoolSpecification-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6c199-108">Initializes a new instance of the AutoPoolSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoPoolIdPrefix">
      <MemberSignature Language="C#" Value="public string AutoPoolIdPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoPoolIdPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.AutoPoolIdPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoPoolIdPrefix As String" />
      <MemberSignature Language="F#" Value="member this.AutoPoolIdPrefix : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.AutoPoolIdPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoPoolIdPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6c199-109">Ruft ab oder legt ein Präfix für den eindeutigen Bezeichner hinzugefügt, wenn ein Pool automatisch erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="6c199-109">Gets or sets a prefix to be added to the unique identifier when a pool is automatically created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6c199-110">Der Batch-Dienst weist jedem Pool automatisch einen eindeutigen Bezeichner bei der Erstellung.</span><span class="sxs-lookup"><span data-stu-id="6c199-110">The Batch service assigns each auto pool a unique identifier on creation.</span></span> <span data-ttu-id="6c199-111">Um für unterschiedliche Zwecke erstellten Ressourcenpools unterscheiden, können Sie angeben, dieses Element aus, um die ID ein Präfix hinzuzufügen, die zugewiesen wird.</span><span class="sxs-lookup"><span data-stu-id="6c199-111">To distinguish between pools created for different purposes, you can specify this element to add a prefix to the ID that is assigned.</span></span> <span data-ttu-id="6c199-112">Das Präfix kann bis zu 20 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="6c199-112">The prefix can be up to 20 characters long.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAlive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; KeepAlive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; KeepAlive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.KeepAlive" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAlive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.KeepAlive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.KeepAlive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keepAlive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6c199-113">Ruft ab oder legt fest, ob einen automatischer Pool nach Ablauf der Lebensdauer aufrechtzuerhalten.</span><span class="sxs-lookup"><span data-stu-id="6c199-113">Gets or sets whether to keep an auto pool alive after its lifetime expires.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6c199-114">Wenn "false", löscht der Batch-Dienst den Pool nach Ablauf der Lebensdauer (wie durch die Einstellung PoolLifetimeOption bestimmt); Wenn der Auftrag oder den Auftrag zu planen, also abgeschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="6c199-114">If false, the Batch service deletes the pool once its lifetime (as determined by the poolLifetimeOption setting) expires; that is, when the job or job schedule completes.</span></span> <span data-ttu-id="6c199-115">Bei "true", wird der Batch-Dienst den Pool nicht automatisch gelöscht.</span><span class="sxs-lookup"><span data-stu-id="6c199-115">If true, the Batch service does not delete the pool automatically.</span></span> <span data-ttu-id="6c199-116">Es liegt im Ermessen der Benutzer automatisch Pools, die mit dieser Option erstellte zu löschen.</span><span class="sxs-lookup"><span data-stu-id="6c199-116">It is up to the user to delete auto pools created with this option.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Pool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolSpecification Pool { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolSpecification Pool" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.Pool" />
      <MemberSignature Language="VB.NET" Value="Public Property Pool As PoolSpecification" />
      <MemberSignature Language="F#" Value="member this.Pool : Microsoft.Azure.Batch.Protocol.Models.PoolSpecification with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.Pool" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pool")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6c199-117">Ruft ab oder legt die poolspezifikation für den automatischen Pool.</span><span class="sxs-lookup"><span data-stu-id="6c199-117">Gets or sets the pool specification for the auto pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolLifetimeOption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption PoolLifetimeOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption PoolLifetimeOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.PoolLifetimeOption" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolLifetimeOption As PoolLifetimeOption" />
      <MemberSignature Language="F#" Value="member this.PoolLifetimeOption : Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.PoolLifetimeOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolLifetimeOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6c199-118">Ruft ab oder legt die minimale Lebensdauer der erstellten automatisch Pools und wie mehrere Aufträge nach einem Zeitplan, die den Pools zugewiesen werden.</span><span class="sxs-lookup"><span data-stu-id="6c199-118">Gets or sets the minimum lifetime of created auto pools, and how multiple jobs on a schedule are assigned to pools.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6c199-119">Folgende Werte sind möglich: "JobSchedule", "Projekt"</span><span class="sxs-lookup"><span data-stu-id="6c199-119">Possible values include: 'jobSchedule', 'job'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="autoPoolSpecification.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6c199-120">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="6c199-120">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6c199-121">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="6c199-121">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>