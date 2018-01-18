<Type Name="JobConstraints" FullName="Microsoft.Azure.Batch.Protocol.Models.JobConstraints">
  <TypeSignature Language="C#" Value="public class JobConstraints" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobConstraints extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobConstraints" />
  <TypeSignature Language="VB.NET" Value="Public Class JobConstraints" />
  <TypeSignature Language="F#" Value="type JobConstraints = class" />
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
            <span data-ttu-id="91504-101">Die ausführungseinschränkungen für einen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="91504-101">The execution constraints for a job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobConstraints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobConstraints.#ctor" />
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
            <span data-ttu-id="91504-102">Initialisiert eine neue Instanz der Klasse "jobconstraints".</span><span class="sxs-lookup"><span data-stu-id="91504-102">Initializes a new instance of the JobConstraints class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobConstraints (Nullable&lt;TimeSpan&gt; maxWallClockTime = null, Nullable&lt;int&gt; maxTaskRetryCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; maxWallClockTime, valuetype System.Nullable`1&lt;int32&gt; maxTaskRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobConstraints.#ctor(System.Nullable{System.TimeSpan},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional maxWallClockTime As Nullable(Of TimeSpan) = null, Optional maxTaskRetryCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobConstraints : Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobConstraints" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobConstraints (maxWallClockTime, maxTaskRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxWallClockTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxTaskRetryCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="maxWallClockTime"><span data-ttu-id="91504-103">Die maximal verstrichene Zeit, die der Auftrag ausgeführt werden kann, gemessen ab dem Zeitpunkt der Erstellung des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="91504-103">The maximum elapsed time that the job may run, measured from the time the job is created.</span></span></param>
        <param name="maxTaskRetryCount"><span data-ttu-id="91504-104">Die maximale Anzahl der Häufigkeit, mit die jede Aufgabe wiederholt werden kann.</span><span class="sxs-lookup"><span data-stu-id="91504-104">The maximum number of times each task may be retried.</span></span> <span data-ttu-id="91504-105">Der Batch-Dienst wiederholt einen Task, wenn sein Exitcode ungleich null ist.</span><span class="sxs-lookup"><span data-stu-id="91504-105">The Batch service retries a task if its exit code is nonzero.</span></span></param>
        <summary>
            <span data-ttu-id="91504-106">Initialisiert eine neue Instanz der Klasse "jobconstraints".</span><span class="sxs-lookup"><span data-stu-id="91504-106">Initializes a new instance of the JobConstraints class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTaskRetryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTaskRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobConstraints.MaxTaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTaskRetryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTaskRetryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobConstraints.MaxTaskRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTaskRetryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91504-107">Ruft ab oder legt die maximale Anzahl der Häufigkeit, mit die jede Aufgabe wiederholt werden kann.</span><span class="sxs-lookup"><span data-stu-id="91504-107">Gets or sets the maximum number of times each task may be retried.</span></span>
            <span data-ttu-id="91504-108">Der Batch-Dienst wiederholt einen Task, wenn sein Exitcode ungleich null ist.</span><span class="sxs-lookup"><span data-stu-id="91504-108">The Batch service retries a task if its exit code is nonzero.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="91504-109">Beachten Sie, dass dieser Wert die Anzahl der Wiederholungen ausdrücklich steuert.</span><span class="sxs-lookup"><span data-stu-id="91504-109">Note that this value specifically controls the number of retries.</span></span>
            <span data-ttu-id="91504-110">Der Batch-Dienst wird jede Aufgabe einmal versucht, und kann bis zu diesem Limit dann wiederholen.</span><span class="sxs-lookup"><span data-stu-id="91504-110">The Batch service will try each task once, and may then retry up to this limit.</span></span> <span data-ttu-id="91504-111">Wenn beispielsweise die maximale Anzahl von Wiederholungsversuchen 3 ist, versucht der Batch-Dienst einen Task bis zu viermal (ein erster Versuch und drei Wiederholungsversuche).</span><span class="sxs-lookup"><span data-stu-id="91504-111">For example, if the maximum retry count is 3, Batch tries a task up to 4 times (one initial try and 3 retries).</span></span> <span data-ttu-id="91504-112">Wenn die maximale Anzahl von Wiederholungsversuchen 0 ist, wiederholt der Batch-Dienst Tasks nicht.</span><span class="sxs-lookup"><span data-stu-id="91504-112">If the maximum retry count is 0, the Batch service does not retry tasks.</span></span>
            <span data-ttu-id="91504-113">Wenn die maximale Anzahl von Wiederholungsversuchen -1 ist, wiederholt der Batch-Dienst Tasks unbegrenzt.</span><span class="sxs-lookup"><span data-stu-id="91504-113">If the maximum retry count is -1, the Batch service retries tasks without limit.</span></span> <span data-ttu-id="91504-114">Der Standardwert ist 0 (keine Wiederholungsversuche).</span><span class="sxs-lookup"><span data-stu-id="91504-114">The default value is 0 (no retries).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxWallClockTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaxWallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaxWallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobConstraints.MaxWallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxWallClockTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaxWallClockTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobConstraints.MaxWallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxWallClockTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91504-115">Ruft ab oder legt die maximale Zeitspanne, die der Auftrag ausgeführt werden kann, gemessen ab dem Zeitpunkt der Erstellung des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="91504-115">Gets or sets the maximum elapsed time that the job may run, measured from the time the job is created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="91504-116">Wenn der Auftrag nicht innerhalb des Zeitlimits abgeschlossen wird, beendet der Batch-Dienst diese und alle Aufgaben, die noch ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="91504-116">If the job does not complete within the time limit, the Batch service terminates it and any tasks that are still running.</span></span> <span data-ttu-id="91504-117">In diesem Fall wird der Grund für die Beendigung MaxWallClockTimeExpiry sein.</span><span class="sxs-lookup"><span data-stu-id="91504-117">In this case, the termination reason will be MaxWallClockTimeExpiry.</span></span> <span data-ttu-id="91504-118">Wenn diese Eigenschaft nicht angegeben wird, ist es nicht zeitlich begrenzt auf, wie lange der Auftrag ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="91504-118">If this property is not specified, there is no time limit on how long the job may run.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>