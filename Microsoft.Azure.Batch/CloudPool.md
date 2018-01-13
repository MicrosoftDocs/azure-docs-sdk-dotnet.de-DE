<Type Name="CloudPool" FullName="Microsoft.Azure.Batch.CloudPool">
  <TypeSignature Language="C#" Value="public class CloudPool : Microsoft.Azure.Batch.IInheritedBehaviors, Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudPool extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors, class Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.CloudPool" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudPool&#xA;Implements IInheritedBehaviors, IRefreshable" />
  <TypeSignature Language="F#" Value="type CloudPool = class&#xA;    interface IRefreshable&#xA;    interface ITransportObjectProvider&lt;PoolAddParameter&gt;&#xA;    interface IInheritedBehaviors&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IRefreshable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="98bf3-101">Dieser Pool in der Azure Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="98bf3-101">A pool in the Azure Batch service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllocationState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.AllocationState&gt; AllocationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.AllocationState&gt; AllocationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationState As Nullable(Of AllocationState)" />
      <MemberSignature Language="F#" Value="member this.AllocationState : Nullable&lt;Microsoft.Azure.Batch.Common.AllocationState&gt;" Usage="Microsoft.Azure.Batch.CloudPool.AllocationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.AllocationState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-102">Ruft eine <see cref="T:Microsoft.Azure.Batch.Common.AllocationState" /> gibt an welchem Knoten Zuordnung Aktivitäten für den Pool stattfinden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-102">Gets an <see cref="T:Microsoft.Azure.Batch.Common.AllocationState" /> which indicates what node allocation activity is occurring on the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AllocationStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AllocationStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.AllocationStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AllocationStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudPool.AllocationStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-103">Ruft die Zeit, an dem der Pool erlangt seinem aktuellen hat <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-103">Gets the time at which the pool entered its current <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLicenses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApplicationLicenses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApplicationLicenses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.ApplicationLicenses" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationLicenses As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLicenses : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.ApplicationLicenses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-104">Ruft ab oder legt die Liste der Anwendungslizenzen der Batch-Dienst auf jeder Serverknoten im Pool verfügbar gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-104">Gets or sets the list of application licenses the Batch service will make available on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="98bf3-105">Die Liste der Anwendungslizenzen muss es sich um eine Teilmenge der verfügbaren Batch Dienstlizenzen Anwendung sein.</span><span class="sxs-lookup"><span data-stu-id="98bf3-105">The list of application licenses must be a subset of available Batch service application licenses.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.ApplicationPackageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-106">Ruft ab oder legt eine Liste von Anwendungspaketen auf jeder Serverknoten im Pool installiert werden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-106">Gets or sets a list of application packages to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoScaleEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoScaleEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-107">Ruft ab oder legt fest, ob die Poolgröße gemäß automatisch anpassen, sollten die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-107">Gets or sets whether the pool size should automatically adjust according to the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="98bf3-108">Bei "true", die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> ist eine erforderliche Eigenschaft, die der Pool ändert automatisch entsprechend der Formel und <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetDedicatedComputeNodes" /> und <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetLowPriorityComputeNodes" /> muss null sein.</span><span class="sxs-lookup"><span data-stu-id="98bf3-108">If true, the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> property is required, the pool automatically resizes according to the formula, and <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetDedicatedComputeNodes" /> and <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetLowPriorityComputeNodes" /> must be null.</span></span></para>
          <para><span data-ttu-id="98bf3-109">Wenn "false" eines der <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetDedicatedComputeNodes" /> oder <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetLowPriorityComputeNodes" /> Eigenschaften ist erforderlich.</span><span class="sxs-lookup"><span data-stu-id="98bf3-109">If false, one of the <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetDedicatedComputeNodes" /> or <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetLowPriorityComputeNodes" /> properties is required.</span></span></para>
          <para><span data-ttu-id="98bf3-110">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="98bf3-110">The default value is false.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEvaluationInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoScaleEvaluationInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoScaleEvaluationInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEvaluationInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEvaluationInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEvaluationInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.AutoScaleEvaluationInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-111">Ruft ab oder legt ein Zeitintervall an, passen Sie die Poolgröße gemäß automatisch an die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-111">Gets or sets a time interval at which to automatically adjust the pool size according to the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="98bf3-112">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-112">The default value is 15 minutes.</span></span> <span data-ttu-id="98bf3-113">Der minimal zulässige Wert beträgt 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-113">The minimum allowed value is 5 minutes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleFormula">
      <MemberSignature Language="C#" Value="public string AutoScaleFormula { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoScaleFormula" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleFormula As String" />
      <MemberSignature Language="F#" Value="member this.AutoScaleFormula : string with get, set" Usage="Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-114">Ruft ab oder legt eine Formel für die gewünschte Anzahl von Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-114">Gets or sets a formula for the desired number of compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="98bf3-115">Für das Schreiben von Formeln für automatische Skalierung finden Sie unter https://azure.microsoft.com/documentation/articles/batch-automatic-scaling/.</span><span class="sxs-lookup"><span data-stu-id="98bf3-115">For how to write autoscale formulas, see https://azure.microsoft.com/documentation/articles/batch-automatic-scaling/.</span></span> <span data-ttu-id="98bf3-116">Diese Eigenschaft ist erforderlich, wenn <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> festgelegt ist auf "true".</span><span class="sxs-lookup"><span data-stu-id="98bf3-116">This property is required if <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> is set to true.</span></span> <span data-ttu-id="98bf3-117">Sie muss null sein, wenn AutoScaleEnabled auf "false" festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="98bf3-117">It must be null if AutoScaleEnabled is false.</span></span></para>
          <para><span data-ttu-id="98bf3-118">Die Formel wird auf Gültigkeit überprüft, bevor der Pool erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="98bf3-118">The formula is checked for validity before the pool is created.</span></span> <span data-ttu-id="98bf3-119">Wenn die Formel nicht gültig ist, wird eine Ausnahme ausgelöst, wenn Sie versuchen, einen commit für die <see cref="T:Microsoft.Azure.Batch.CloudPool" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-119">If the formula is not valid, an exception is thrown when you try to commit the <see cref="T:Microsoft.Azure.Batch.CloudPool" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleRun">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AutoScaleRun AutoScaleRun { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.AutoScaleRun AutoScaleRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.AutoScaleRun" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoScaleRun As AutoScaleRun" />
      <MemberSignature Language="F#" Value="member this.AutoScaleRun : Microsoft.Azure.Batch.AutoScaleRun" Usage="Microsoft.Azure.Batch.CloudPool.AutoScaleRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AutoScaleRun</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-120">Ruft die Ergebnisse und Fehler aus der letzten Ausführung der <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-120">Gets the results and errors from the last execution of the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.CertificateReference&gt; CertificateReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateReferences As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.CertificateReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-121">Ruft ab oder legt eine Liste der Zertifikate auf jeder Serverknoten im Pool installiert werden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-121">Gets or sets a list of certificates to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeOSVersion">
      <MemberSignature Language="C#" Value="public void ChangeOSVersion (string targetOSVersion, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ChangeOSVersion(string targetOSVersion, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.ChangeOSVersion(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ChangeOSVersion (targetOSVersion As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.ChangeOSVersion : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.ChangeOSVersion (targetOSVersion, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="targetOSVersion"><span data-ttu-id="98bf3-122">Die Azure-Gastbetriebssystemversion, die auf den virtuellen Computern im Pool installiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="98bf3-122">The Azure Guest OS version to be installed on the virtual machines in the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-123">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-123">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-124">Ändert die Version des Betriebssystems von diesem Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-124">Changes the operating system version of this pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="98bf3-125">Während des Vorgangs der Änderung BS-Version durchläuft der Batch-Dienst die Knoten des Pools, ändern die Betriebssystemversion der Serverknoten an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-125">During the change OS version operation, the Batch service traverses the nodes of the pool, changing the OS version of compute nodes.</span></span>  <span data-ttu-id="98bf3-126">Wenn Compute-Knoten ausgewählt ist, sind alle Aufgaben, die auf diesem Knoten ausgeführt wird aus dem Knoten entfernt und in die Warteschlange zur später (oder auf einem anderen Serverknoten) erneut ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-126">When a compute node is chosen, any tasks running on that node are removed from the node and requeued to be rerun later (or on a different compute node).</span></span>  <span data-ttu-id="98bf3-127">Der Knoten wird nicht verfügbar sein, bis die versionsänderung abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="98bf3-127">The node will be unavailable until the version change is complete.</span></span></para>
          <para><span data-ttu-id="98bf3-128">Der Vorgang führt zu vorübergehend reduzierte Pool-Kapazität, wie Knoten außer Betrieb getroffen werden, um ihre Version des Betriebssystems geändert haben.</span><span class="sxs-lookup"><span data-stu-id="98bf3-128">The operation will result in temporarily reduced pool capacity as nodes are taken out of service to have their OS version changed.</span></span> <span data-ttu-id="98bf3-129">Obwohl die Batch-Dienst versucht wird, um zu vermeiden, ändern alle Serverknoten zur gleichen Zeit, garantiert jedoch nicht dazu (vor allem für kleine Pools); der Vorgang kann daher im Pool wird vorübergehend nicht verfügbar, um Aufgaben auszuführen, führen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-129">Although the Batch service tries to avoid changing all compute nodes at the same time, it does not guarantee to do this (particularly on small pools); therefore, the operation may result in the pool being temporarily unavailable to run tasks.</span></span></para>
          <para><span data-ttu-id="98bf3-130">Wenn Sie ein Betriebssystem-versionsänderung anfordern, ändert sich der Pool Zustand zu <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-130">When you request an OS version change, the pool state changes to <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />.</span></span>  <span data-ttu-id="98bf3-131">Wenn alle Knoten haben, ändern die Version zu berechnen, wird der Poolstatus zur zurück <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-131">When all compute nodes have finished changing version, the pool state returns to <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />.</span></span></para>
          <para><span data-ttu-id="98bf3-132">Während die versionsänderung, den Pool der läuft <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" /> gibt die Version des Betriebssystems, den Knoten aus, ändern und <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" /> gibt die Version des Betriebssystems, den Knoten zu ändern.</span><span class="sxs-lookup"><span data-stu-id="98bf3-132">While the version change is in progress, the pool's <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" /> reflects the OS version that nodes are changing from, and <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" /> reflects the OS version that nodes are changing to.</span></span> <span data-ttu-id="98bf3-133">Nachdem die Änderung abgeschlossen ist, wird CurrentOSVersion aktualisiert, entsprechend der Version des Betriebssystems nun auf allen Knoten ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="98bf3-133">Once the change is complete, CurrentOSVersion is updated to reflect the OS version now running on all nodes.</span></span></para>
          <para><span data-ttu-id="98bf3-134">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="98bf3-134">This is a blocking operation.</span></span> <span data-ttu-id="98bf3-135">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.ChangeOSVersionAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-135">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudPool.ChangeOSVersionAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeOSVersionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ChangeOSVersionAsync (string targetOSVersion, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ChangeOSVersionAsync(string targetOSVersion, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.ChangeOSVersionAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ChangeOSVersionAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.ChangeOSVersionAsync (targetOSVersion, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="targetOSVersion"><span data-ttu-id="98bf3-136">Die Azure-Gastbetriebssystemversion, die auf den virtuellen Computern im Pool installiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="98bf3-136">The Azure Guest OS version to be installed on the virtual machines in the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-137">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-137">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98bf3-138">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="98bf3-138">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-139">Ändert die Version des Betriebssystems von diesem Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-139">Changes the operating system version of this pool.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-140">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-140">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="98bf3-141">Während des Vorgangs der Änderung BS-Version durchläuft der Batch-Dienst die Knoten des Pools, ändern die Betriebssystemversion der Serverknoten an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-141">During the change OS version operation, the Batch service traverses the nodes of the pool, changing the OS version of compute nodes.</span></span>  <span data-ttu-id="98bf3-142">Wenn Compute-Knoten ausgewählt ist, sind alle Aufgaben, die auf diesem Knoten ausgeführt wird aus dem Knoten entfernt und in die Warteschlange zur später (oder auf einem anderen Serverknoten) erneut ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-142">When a compute node is chosen, any tasks running on that node are removed from the node and requeued to be rerun later (or on a different compute node).</span></span>  <span data-ttu-id="98bf3-143">Der Knoten wird nicht verfügbar sein, bis die versionsänderung abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="98bf3-143">The node will be unavailable until the version change is complete.</span></span></para>
          <para><span data-ttu-id="98bf3-144">Der Vorgang führt zu vorübergehend reduzierte Pool-Kapazität, wie Knoten außer Betrieb getroffen werden, um ihre Version des Betriebssystems geändert haben.</span><span class="sxs-lookup"><span data-stu-id="98bf3-144">The operation will result in temporarily reduced pool capacity as nodes are taken out of service to have their OS version changed.</span></span> <span data-ttu-id="98bf3-145">Obwohl die Batch-Dienst versucht wird, um zu vermeiden, ändern alle Serverknoten zur gleichen Zeit, garantiert jedoch nicht dazu (vor allem für kleine Pools); der Vorgang kann daher im Pool wird vorübergehend nicht verfügbar, um Aufgaben auszuführen, führen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-145">Although the Batch service tries to avoid changing all compute nodes at the same time, it does not guarantee to do this (particularly on small pools); therefore, the operation may result in the pool being temporarily unavailable to run tasks.</span></span></para>
          <para><span data-ttu-id="98bf3-146">Wenn Sie ein Betriebssystem-versionsänderung anfordern, ändert sich der Pool Zustand zu <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-146">When you request an OS version change, the pool state changes to <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />.</span></span>  <span data-ttu-id="98bf3-147">Wenn alle Knoten haben, ändern die Version zu berechnen, wird der Poolstatus zur zurück <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-147">When all compute nodes have finished changing version, the pool state returns to <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />.</span></span></para>
          <para><span data-ttu-id="98bf3-148">Während die versionsänderung, den Pool der läuft <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" /> gibt die Version des Betriebssystems, den Knoten aus, ändern und <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" /> gibt die Version des Betriebssystems, den Knoten zu ändern.</span><span class="sxs-lookup"><span data-stu-id="98bf3-148">While the version change is in progress, the pool's <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" /> reflects the OS version that nodes are changing from, and <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" /> reflects the OS version that nodes are changing to.</span></span> <span data-ttu-id="98bf3-149">Nachdem die Änderung abgeschlossen ist, wird CurrentOSVersion aktualisiert, entsprechend der Version des Betriebssystems nun auf allen Knoten ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="98bf3-149">Once the change is complete, CurrentOSVersion is updated to reflect the OS version now running on all nodes.</span></span></para>
          <para><span data-ttu-id="98bf3-150">Vorgang zum Ändern des Version wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-150">The change version operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudServiceConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudServiceConfiguration CloudServiceConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.CloudServiceConfiguration CloudServiceConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudServiceConfiguration As CloudServiceConfiguration" />
      <MemberSignature Language="F#" Value="member this.CloudServiceConfiguration : Microsoft.Azure.Batch.CloudServiceConfiguration with get, set" Usage="Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudServiceConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-151">Ruft ab oder legt die <see cref="P:Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" /> für den Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-151">Gets or sets the <see cref="P:Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" /> for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="public void Commit (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Commit(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Commit (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Commit : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.Commit additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-152">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-152">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-153">Führt einen Commit für diese <see cref="T:Microsoft.Azure.Batch.CloudPool" /> an den Azure Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="98bf3-153">Commits this <see cref="T:Microsoft.Azure.Batch.CloudPool" /> to the Azure Batch service.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="98bf3-154">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="98bf3-154">This is a blocking operation.</span></span> <span data-ttu-id="98bf3-155">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-155">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.CommitAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;CommitAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-156">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-156">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98bf3-157">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="98bf3-157">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-158">Führt einen Commit für diese <see cref="T:Microsoft.Azure.Batch.CloudPool" /> an den Azure Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="98bf3-158">Commits this <see cref="T:Microsoft.Azure.Batch.CloudPool" /> to the Azure Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-159">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-159">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="98bf3-160">Der Commitvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-160">The commit operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitChanges">
      <MemberSignature Language="C#" Value="public void CommitChanges (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CommitChanges(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.CommitChanges(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CommitChanges (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.CommitChanges : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.CommitChanges additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-161">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-161">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-162">Führt einen Commit für alle ausstehenden Änderungen dieser <see cref="T:Microsoft.Azure.Batch.CloudPool" /> an den Azure Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="98bf3-162">Commits all pending changes to this <see cref="T:Microsoft.Azure.Batch.CloudPool" /> to the Azure Batch service.</span></span>
            </summary>
        <remarks>
          <para>
            <span data-ttu-id="98bf3-163">Aktualisiert ein vorhandenes <see cref="T:Microsoft.Azure.Batch.CloudPool" /> auf der Batch-Dienst, indem Sie seine Eigenschaften mit den Eigenschaften dieser ersetzen <see cref="T:Microsoft.Azure.Batch.CloudPool" /> die geändert wurden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-163">Updates an existing <see cref="T:Microsoft.Azure.Batch.CloudPool" /> on the Batch service by replacing its properties with the properties of this <see cref="T:Microsoft.Azure.Batch.CloudPool" /> which have been changed.</span></span>
            <span data-ttu-id="98bf3-164">Unveränderte Eigenschaften werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="98bf3-164">Unchanged properties are ignored.</span></span>
            <span data-ttu-id="98bf3-165">Alle Änderungen seit der letzten Ausführung dieser Entität aus der Batch-Dienst abgerufen wurde (entweder über <see cref="M:Microsoft.Azure.Batch.CloudPool.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetPool(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, oder <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-165">All changes since the last time this entity was retrieved from the Batch service (either via <see cref="M:Microsoft.Azure.Batch.CloudPool.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetPool(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, or <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) are applied.</span></span>
            <span data-ttu-id="98bf3-166">Eigenschaften, die auf null wird explizit festgelegt sind, wird eine Ausnahme ausgelöst, da der Batch-Dienst nicht teilweise Updates unterstützt, die eine Eigenschaft auf null festgelegt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-166">Properties which are explicitly set to null will cause an exception because the Batch service does not support partial updates which set a property to null.</span></span>
            <span data-ttu-id="98bf3-167">Wenn Sie eine Eigenschaft auf null festgelegt, verwenden die <see cref="M:Microsoft.Azure.Batch.CloudPool.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="98bf3-167">If you need to set a property to null, use the <see cref="M:Microsoft.Azure.Batch.CloudPool.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> method.</span></span>
            </para>
          <para><span data-ttu-id="98bf3-168">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="98bf3-168">This is a blocking operation.</span></span> <span data-ttu-id="98bf3-169">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitChangesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-169">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitChangesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitChangesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitChangesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitChangesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.CommitChangesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitChangesAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.CommitChangesAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;CommitChangesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-170">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-170">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98bf3-171">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="98bf3-171">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-172">Führt einen Commit für alle ausstehenden Änderungen dieser <see cref="T:Microsoft.Azure.Batch.CloudPool" /> an den Azure Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="98bf3-172">Commits all pending changes to this <see cref="T:Microsoft.Azure.Batch.CloudPool" /> to the Azure Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-173">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-173">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="98bf3-174">Aktualisiert ein vorhandenes <see cref="T:Microsoft.Azure.Batch.CloudPool" /> auf der Batch-Dienst, indem Sie seine Eigenschaften mit den Eigenschaften dieser ersetzen <see cref="T:Microsoft.Azure.Batch.CloudPool" /> die geändert wurden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-174">Updates an existing <see cref="T:Microsoft.Azure.Batch.CloudPool" /> on the Batch service by replacing its properties with the properties of this <see cref="T:Microsoft.Azure.Batch.CloudPool" /> which have been changed.</span></span>
            <span data-ttu-id="98bf3-175">Unveränderte Eigenschaften werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="98bf3-175">Unchanged properties are ignored.</span></span>
            <span data-ttu-id="98bf3-176">Alle Änderungen seit der letzten Ausführung dieser Entität aus der Batch-Dienst abgerufen wurde (entweder über <see cref="M:Microsoft.Azure.Batch.CloudPool.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetPool(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, oder <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-176">All changes since the last time this entity was retrieved from the Batch service (either via <see cref="M:Microsoft.Azure.Batch.CloudPool.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetPool(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, or <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) are applied.</span></span>
            <span data-ttu-id="98bf3-177">Eigenschaften, die auf null wird explizit festgelegt sind, wird eine Ausnahme ausgelöst, da der Batch-Dienst nicht teilweise Updates unterstützt, die eine Eigenschaft auf null festgelegt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-177">Properties which are explicitly set to null will cause an exception because the Batch service does not support partial updates which set a property to null.</span></span>
            <span data-ttu-id="98bf3-178">Wenn Sie eine Eigenschaft auf null festzulegen, verwenden <see cref="M:Microsoft.Azure.Batch.CloudPool.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-178">If you need to set a property to null, use <see cref="M:Microsoft.Azure.Batch.CloudPool.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span>
            </para>
          <para><span data-ttu-id="98bf3-179">Dieser Vorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-179">This operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudPool.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-180">Ruft den Zeitpunkt der Erstellung für den Pool an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-180">Gets the creation time for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentDedicated">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentDedicated { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentDedicated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.CurrentDedicated" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentDedicated As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentDedicated : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.CloudPool.CurrentDedicated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Obsolete after 05/2017, use CurrentDedicatedComputeNodes instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-181">Diese Eigenschaft ist ein Alias für <see cref="P:Microsoft.Azure.Batch.CloudPool.CurrentDedicatedComputeNodes" /> und wird nur für Abwärtskompatibilität unterstützt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-181">This property is an alias for <see cref="P:Microsoft.Azure.Batch.CloudPool.CurrentDedicatedComputeNodes" /> and is supported only for backward compatibility.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentDedicatedComputeNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentDedicatedComputeNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentDedicatedComputeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.CurrentDedicatedComputeNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentDedicatedComputeNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentDedicatedComputeNodes : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.CloudPool.CurrentDedicatedComputeNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-182">Ruft die Anzahl der dedizierten Serverknoten, die derzeit im Pool ab.</span><span class="sxs-lookup"><span data-stu-id="98bf3-182">Gets the number of dedicated compute nodes currently in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentLowPriorityComputeNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentLowPriorityComputeNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentLowPriorityComputeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.CurrentLowPriorityComputeNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentLowPriorityComputeNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentLowPriorityComputeNodes : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.CloudPool.CurrentLowPriorityComputeNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-183">Ruft die Anzahl der Serverknoten mit niedriger Priorität, die derzeit im Pool ab.</span><span class="sxs-lookup"><span data-stu-id="98bf3-183">Gets the number of low-priority compute nodes currently in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="98bf3-184">Mit niedriger Priorität Serverknoten die vorweggenommen haben sind in dieser Anzahl enthalten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-184">Low-priority compute nodes which have been preempted are included in this count.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-185">Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst, die über dieses <see cref="T:Microsoft.Azure.Batch.CloudPool" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-185">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.CloudPool" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="98bf3-186">Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-186">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="98bf3-187">Änderungen werden in der Reihenfolge der Auflistung angewendet.</span><span class="sxs-lookup"><span data-stu-id="98bf3-187">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="98bf3-188">Der letzte write Wins.</span><span class="sxs-lookup"><span data-stu-id="98bf3-188">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Delete(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Delete : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.Delete additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-189">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-189">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-190">Löscht diesen Pool an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-190">Deletes this pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="98bf3-191">Der Löschvorgang fordert, dass der Pool gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-191">The delete operation requests that the pool be deleted.</span></span>  <span data-ttu-id="98bf3-192">Die Anforderung setzt den Pool in der <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="98bf3-192">The request puts the pool in the <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" /> state.</span></span>
            <span data-ttu-id="98bf3-193">Der Batch-Dienst wird requeue alle ausgeführten Aufgaben und das tatsächliche Pool löschen, ohne weitere Clientaktion ausführen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-193">The Batch service will requeue any running tasks and perform the actual pool deletion without any further client action.</span></span></para>
          <remarks><span data-ttu-id="98bf3-194">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="98bf3-194">This is a blocking operation.</span></span> <span data-ttu-id="98bf3-195">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-195">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudPool.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.DeleteAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-196">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-196">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98bf3-197">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="98bf3-197">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-198">Löscht diesen Pool an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-198">Deletes this pool.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-199">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-199">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="98bf3-200">Der Löschvorgang fordert, dass der Pool gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-200">The delete operation requests that the pool be deleted.</span></span>  <span data-ttu-id="98bf3-201">Die Anforderung setzt den Pool in der <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="98bf3-201">The request puts the pool in the <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" /> state.</span></span>
            <span data-ttu-id="98bf3-202">Der Batch-Dienst wird requeue alle ausgeführten Aufgaben und das tatsächliche Pool löschen, ohne weitere Clientaktion ausführen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-202">The Batch service will requeue any running tasks and perform the actual pool deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="98bf3-203">Der Löschvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-203">The delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScale">
      <MemberSignature Language="C#" Value="public void DisableAutoScale (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableAutoScale(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.DisableAutoScale(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DisableAutoScale (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DisableAutoScale : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.DisableAutoScale additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-204">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-204">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-205">Deaktiviert die automatische Skalierung für diesen Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-205">Disables automatic scaling on this pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="98bf3-206">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="98bf3-206">This is a blocking operation.</span></span> <span data-ttu-id="98bf3-207">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.DisableAutoScaleAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-207">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudPool.DisableAutoScaleAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableAutoScaleAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableAutoScaleAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.DisableAutoScaleAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableAutoScaleAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.DisableAutoScaleAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;DisableAutoScaleAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-208">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-208">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98bf3-209">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="98bf3-209">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-210">Deaktiviert die automatische Skalierung für diesen Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-210">Disables automatic scaling on this pool.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-211">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-211">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="98bf3-212">Der Deaktivierungsvorgang für die automatische Skalierung wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-212">The disable autoscale operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.CloudPool.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-213">Ruft ab oder legt den Anzeigenamen des Pools.</span><span class="sxs-lookup"><span data-stu-id="98bf3-213">Gets or sets the display name of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScale">
      <MemberSignature Language="C#" Value="public void EnableAutoScale (string autoscaleFormula = null, Nullable&lt;TimeSpan&gt; autoscaleEvaluationInterval = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableAutoScale(string autoscaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoscaleEvaluationInterval, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.EnableAutoScale(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableAutoScale (Optional autoscaleFormula As String = null, Optional autoscaleEvaluationInterval As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScale : string * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.EnableAutoScale (autoscaleFormula, autoscaleEvaluationInterval, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="autoscaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="autoscaleFormula"><span data-ttu-id="98bf3-214">Die Formel für die gewünschte Anzahl von Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-214">The formula for the desired number of compute nodes in the pool.</span></span></param>
        <param name="autoscaleEvaluationInterval"><span data-ttu-id="98bf3-215">Das Zeitintervall, an dem die Poolgröße gemäß Formel für automatische Skalierung automatisch angepasst werden soll.</span><span class="sxs-lookup"><span data-stu-id="98bf3-215">The time interval at which to automatically adjust the pool size according to the AutoScale formula.</span></span> <span data-ttu-id="98bf3-216">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-216">The default value is 15 minutes.</span></span> <span data-ttu-id="98bf3-217">Der minimal zulässige Wert beträgt 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-217">The minimum allowed value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-218">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-218">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-219">Ermöglicht die automatische Skalierung für diesen Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-219">Enables automatic scaling on this pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="98bf3-220">Die Formel wird auf Gültigkeit überprüft, bevor es an den Pool angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="98bf3-220">The formula is checked for validity before it is applied to the pool.</span></span> <span data-ttu-id="98bf3-221">Wenn die Formel nicht gültig ist, eine Ausnahme auftritt ist.</span><span class="sxs-lookup"><span data-stu-id="98bf3-221">If the formula is not valid, an exception occurs.</span></span></para>
          <para><span data-ttu-id="98bf3-222">Sie können keine Aktivieren der automatischen Skalierung für einen Pool, wenn ein größenänderungsvorgang für den Pool ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="98bf3-222">You cannot enable automatic scaling on a pool if a resize operation is in progress on the pool.</span></span></para>
          <para><span data-ttu-id="98bf3-223">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="98bf3-223">This is a blocking operation.</span></span> <span data-ttu-id="98bf3-224">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.EnableAutoScaleAsync(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-224">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudPool.EnableAutoScaleAsync(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableAutoScaleAsync (string autoscaleFormula = null, Nullable&lt;TimeSpan&gt; autoscaleEvaluationInterval = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableAutoScaleAsync(string autoscaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoscaleEvaluationInterval, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.EnableAutoScaleAsync(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScaleAsync : string * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.EnableAutoScaleAsync (autoscaleFormula, autoscaleEvaluationInterval, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;EnableAutoScaleAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="autoscaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="autoscaleFormula"><span data-ttu-id="98bf3-225">Die Formel für die gewünschte Anzahl von Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-225">The formula for the desired number of compute nodes in the pool.</span></span></param>
        <param name="autoscaleEvaluationInterval"><span data-ttu-id="98bf3-226">Das Zeitintervall, an dem die Poolgröße gemäß Formel für automatische Skalierung automatisch angepasst werden soll.</span><span class="sxs-lookup"><span data-stu-id="98bf3-226">The time interval at which to automatically adjust the pool size according to the AutoScale formula.</span></span> <span data-ttu-id="98bf3-227">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-227">The default value is 15 minutes.</span></span> <span data-ttu-id="98bf3-228">Der minimal zulässige Wert beträgt 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-228">The minimum allowed value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-229">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-229">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98bf3-230">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="98bf3-230">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-231">Ermöglicht die automatische Skalierung für diesen Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-231">Enables automatic scaling on this pool.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-232">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-232">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="98bf3-233">Die Formel wird auf Gültigkeit überprüft, bevor es an den Pool angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="98bf3-233">The formula is checked for validity before it is applied to the pool.</span></span> <span data-ttu-id="98bf3-234">Wenn die Formel nicht gültig ist, eine Ausnahme auftritt ist.</span><span class="sxs-lookup"><span data-stu-id="98bf3-234">If the formula is not valid, an exception occurs.</span></span></para>
          <para><span data-ttu-id="98bf3-235">Sie können keine Aktivieren der automatischen Skalierung für einen Pool, wenn ein größenänderungsvorgang für den Pool ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="98bf3-235">You cannot enable automatic scaling on a pool if a resize operation is in progress on the pool.</span></span></para>
          <para><span data-ttu-id="98bf3-236">Der Vorgang zum Aktivieren der automatischen Skalierung wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-236">The enable autoscale operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.Batch.CloudPool.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-237">Ruft das ETag für den Pool an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-237">Gets the ETag for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScale">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AutoScaleRun EvaluateAutoScale (string autoscaleFormula, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.AutoScaleRun EvaluateAutoScale(string autoscaleFormula, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.EvaluateAutoScale(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function EvaluateAutoScale (autoscaleFormula As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As AutoScaleRun" />
      <MemberSignature Language="F#" Value="member this.EvaluateAutoScale : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.AutoScaleRun" Usage="cloudPool.EvaluateAutoScale (autoscaleFormula, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AutoScaleRun</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="autoscaleFormula"><span data-ttu-id="98bf3-238">Die Formel für den Pool ausgewertet werden soll.</span><span class="sxs-lookup"><span data-stu-id="98bf3-238">The formula to be evaluated on the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-239">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-239">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-240">Ruft das Ergebnis der Auswertung einer Automatisches Formel für diesen Pool Skalierung.</span><span class="sxs-lookup"><span data-stu-id="98bf3-240">Gets the result of evaluating an automatic scaling formula on this pool.</span></span>  <span data-ttu-id="98bf3-241">Dies ist in erster Linie für eine Formel für automatische Skalierung überprüfen, da sie einfach das Ergebnis zurückgibt, ohne die Formel für den Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-241">This is primarily for validating an autoscale formula, as it simply returns the result without applying the formula to the pool.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-242">Das Ergebnis der Auswertung der <paramref name="autoscaleFormula" /> für diesen Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-242">The result of evaluating the <paramref name="autoscaleFormula" /> on this pool.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="98bf3-243">Die Formel überprüft wurde und seine Ergebnisse berechnet, jedoch nicht an den Pool angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="98bf3-243">The formula is validated and its results calculated, but is not applied to the pool.</span></span>  <span data-ttu-id="98bf3-244">Verwenden Sie zum Anwenden der Formel für den Pool <see cref="M:Microsoft.Azure.Batch.CloudPool.EnableAutoScale(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-244">To apply the formula to the pool, use <see cref="M:Microsoft.Azure.Batch.CloudPool.EnableAutoScale(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></para>
          <para><span data-ttu-id="98bf3-245">Diese Methode ändert sich nicht auf einem beliebigen Zustand des Pools und hat keinen Einfluss auf die <see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" /> oder <see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-245">This method does not change any state of the pool, and does not affect the <see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" /> or <see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />.</span></span></para>
          <para><span data-ttu-id="98bf3-246">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="98bf3-246">This is a blocking operation.</span></span> <span data-ttu-id="98bf3-247">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.EvaluateAutoScaleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-247">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudPool.EvaluateAutoScaleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt; EvaluateAutoScaleAsync (string autoscaleFormula, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.AutoScaleRun&gt; EvaluateAutoScaleAsync(string autoscaleFormula, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.EvaluateAutoScaleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EvaluateAutoScaleAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt;" Usage="cloudPool.EvaluateAutoScaleAsync (autoscaleFormula, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;EvaluateAutoScaleAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="autoscaleFormula"><span data-ttu-id="98bf3-248">Die Formel für den Pool ausgewertet werden soll.</span><span class="sxs-lookup"><span data-stu-id="98bf3-248">The formula to be evaluated on the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-249">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-249">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98bf3-250">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="98bf3-250">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-251">Ruft das Ergebnis der Auswertung einer Automatisches Formel für diesen Pool Skalierung.</span><span class="sxs-lookup"><span data-stu-id="98bf3-251">Gets the result of evaluating an automatic scaling formula on this pool.</span></span>  <span data-ttu-id="98bf3-252">Dies ist in erster Linie für eine Formel für automatische Skalierung überprüfen, da sie einfach das Ergebnis zurückgibt, ohne die Formel für den Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-252">This is primarily for validating an autoscale formula, as it simply returns the result without applying the formula to the pool.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-253">Das Ergebnis der Auswertung der <paramref name="autoscaleFormula" /> für diesen Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-253">The result of evaluating the <paramref name="autoscaleFormula" /> on this pool.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="98bf3-254">Die Formel überprüft wurde und seine Ergebnisse berechnet, jedoch nicht an den Pool angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="98bf3-254">The formula is validated and its results calculated, but is not applied to the pool.</span></span>  <span data-ttu-id="98bf3-255">Verwenden Sie zum Anwenden der Formel für den Pool <see cref="M:Microsoft.Azure.Batch.CloudPool.EnableAutoScaleAsync(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-255">To apply the formula to the pool, use <see cref="M:Microsoft.Azure.Batch.CloudPool.EnableAutoScaleAsync(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="98bf3-256">Diese Methode ändert sich nicht auf einem beliebigen Zustand des Pools und hat keinen Einfluss auf die <see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" /> oder <see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-256">This method does not change any state of the pool, and does not affect the <see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" /> or <see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />.</span></span></para>
          <para><span data-ttu-id="98bf3-257">Die Evaluate-Vorgänge werden asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-257">The evaluate operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetComputeNode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNode GetComputeNode (string computeNodeId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.ComputeNode GetComputeNode(string computeNodeId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.GetComputeNode(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetComputeNode : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.ComputeNode" Usage="cloudPool.GetComputeNode (computeNodeId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="computeNodeId"><span data-ttu-id="98bf3-258">Die Id der Serverknoten aus dem Pool abgerufen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-258">The id of the compute node to get from the pool.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="98bf3-259">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-259">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-260">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-260">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-261">Ruft den angegebenen Serverknoten aus diesem Pool ab.</span><span class="sxs-lookup"><span data-stu-id="98bf3-261">Gets the specified compute node from this pool.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-262">Ein <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> mit Informationen über den angegebenen Compute-Knoten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-262">A <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> containing information about the specified compute node.</span></span></returns>
        <remarks><span data-ttu-id="98bf3-263">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="98bf3-263">This is a blocking operation.</span></span> <span data-ttu-id="98bf3-264">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.GetComputeNodeAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-264">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudPool.GetComputeNodeAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetComputeNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt; GetComputeNodeAsync (string computeNodeId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; GetComputeNodeAsync(string computeNodeId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.GetComputeNodeAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetComputeNodeAsync : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt;" Usage="cloudPool.GetComputeNodeAsync (computeNodeId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="computeNodeId"><span data-ttu-id="98bf3-265">Die Id der Serverknoten aus dem Pool abgerufen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-265">The id of the compute node to get from the pool.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="98bf3-266">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-266">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-267">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-267">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98bf3-268">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="98bf3-268">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-269">Ruft den angegebenen Serverknoten aus diesem Pool ab.</span><span class="sxs-lookup"><span data-stu-id="98bf3-269">Gets the specified compute node from this pool.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-270">Ein <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> mit Informationen über den angegebenen Compute-Knoten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-270">A <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> containing information about the specified compute node.</span></span></returns>
        <remarks><span data-ttu-id="98bf3-271">Das Abrufen des Knotens wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-271">The get node operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.CloudPool.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-272">Ruft ab oder legt die Id des Pools.</span><span class="sxs-lookup"><span data-stu-id="98bf3-272">Gets or sets the id of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InterComputeNodeCommunicationEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; InterComputeNodeCommunicationEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; InterComputeNodeCommunicationEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.InterComputeNodeCommunicationEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property InterComputeNodeCommunicationEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.InterComputeNodeCommunicationEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.InterComputeNodeCommunicationEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-273">Ruft ab oder legt sie fest, ob der Pool direkten Kommunikation zwischen der Serverknoten zulässt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-273">Gets or sets whether the pool permits direct communication between its compute nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="98bf3-274">Aktivieren der Kommunikation zwischen den Knoten schränkt die maximale Größe des Pools aufgrund von Einschränkungen der Bereitstellung auf den Knoten des Pools.</span><span class="sxs-lookup"><span data-stu-id="98bf3-274">Enabling inter-node communication limits the maximum size of the pool due to deployment restrictions on the nodes of the pool.</span></span> <span data-ttu-id="98bf3-275">Dies kann im Pool nicht die gewünschte Größe erreichen führen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-275">This may result in the pool not reaching its desired size.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudPool.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-276">Ruft den Zeitpunkt den letzten Änderung des Pools an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-276">Gets the last modified time of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListComputeNodes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; ListComputeNodes (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; ListComputeNodes(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.ListComputeNodes(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListComputeNodes : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" Usage="cloudPool.ListComputeNodes (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="98bf3-277">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-277">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-278">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-278">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-279">Listet die <see cref="T:Microsoft.Azure.Batch.ComputeNode">Serverknoten</see> von diesem Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-279">Enumerates the <see cref="T:Microsoft.Azure.Batch.ComputeNode">compute nodes</see> of this pool.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-280">Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die asynchron oder synchron Auflisten von Computeknoten verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="98bf3-280">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate compute nodes asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="98bf3-281">Diese Methode gibt sofort zurück. nur, wenn die Auflistung aufgezählt wird, werden die Knoten aus dem Batch-Dienst abgerufen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-281">This method returns immediately; the nodes are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="98bf3-282">Datenabruf ist nicht atomaren; Knoten werden in Seiten während der Enumeration der Auflistung abgerufen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-282">Retrieval is non-atomic; nodes are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTasksPerComputeNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTasksPerComputeNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTasksPerComputeNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.MaxTasksPerComputeNode" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTasksPerComputeNode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTasksPerComputeNode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.MaxTasksPerComputeNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-283">Ruft ab oder legt die maximale Anzahl von Aufgaben, die gleichzeitig auf einem einzelnen Serverknoten im Pool ausgeführt werden können.</span><span class="sxs-lookup"><span data-stu-id="98bf3-283">Gets or sets the maximum number of tasks that can run concurrently on a single compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="98bf3-284">Der Standardwert ist 1.</span><span class="sxs-lookup"><span data-stu-id="98bf3-284">The default value is 1.</span></span> <span data-ttu-id="98bf3-285">Der maximale Wert dieser Einstellung hängt von der Größe der Serverknoten im Pool (die <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineSize" /> Eigenschaft).</span><span class="sxs-lookup"><span data-stu-id="98bf3-285">The maximum value of this setting depends on the size of the compute nodes in the pool (the <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineSize" /> property).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-286">Ruft ab oder legt eine Liste von Name / Wert-Paaren, die dem Pool als Metadaten zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="98bf3-286">Gets or sets a list of name-value pairs associated with the pool as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.NetworkConfiguration NetworkConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.NetworkConfiguration NetworkConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.NetworkConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkConfiguration As NetworkConfiguration" />
      <MemberSignature Language="F#" Value="member this.NetworkConfiguration : Microsoft.Azure.Batch.NetworkConfiguration with get, set" Usage="Microsoft.Azure.Batch.CloudPool.NetworkConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.NetworkConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-287">Ruft ab oder legt die Netzwerkkonfiguration des Pools.</span><span class="sxs-lookup"><span data-stu-id="98bf3-287">Gets or sets the network configuration of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public void Refresh (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Refresh(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="abstract member Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit&#xA;override this.Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.Refresh (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="98bf3-288">Die Detailstufe für die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="98bf3-288">The detail level for the refresh.</span></span>  <span data-ttu-id="98bf3-289">Wenn einer der weglässt Detailebene der <see cref="P:Microsoft.Azure.Batch.CloudPool.Id" /> -Eigenschaft angegeben ist, scheitert die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="98bf3-289">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.CloudPool.Id" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-290">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-290">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-291">Aktualisiert das aktuelle <see cref="T:Microsoft.Azure.Batch.CloudPool" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-291">Refreshes the current <see cref="T:Microsoft.Azure.Batch.CloudPool" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.RefreshAsync (detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;RefreshAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="98bf3-292">Die Detailstufe für die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="98bf3-292">The detail level for the refresh.</span></span>  <span data-ttu-id="98bf3-293">Wenn einer der weglässt Detailebene der <see cref="P:Microsoft.Azure.Batch.CloudPool.Id" /> -Eigenschaft angegeben ist, scheitert die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="98bf3-293">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.CloudPool.Id" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-294">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-294">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98bf3-295">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="98bf3-295">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-296">Aktualisiert das aktuelle <see cref="T:Microsoft.Azure.Batch.CloudPool" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-296">Refreshes the current <see cref="T:Microsoft.Azure.Batch.CloudPool" />.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-297">Ein <see cref="T:System.Threading.Tasks.Task" /> , das den asynchronen Aktualisierungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-297">A <see cref="T:System.Threading.Tasks.Task" /> representing the asynchronous refresh operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (Microsoft.Azure.Batch.ComputeNode computeNode, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(class Microsoft.Azure.Batch.ComputeNode computeNode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : Microsoft.Azure.Batch.ComputeNode * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.RemoveFromPool (computeNode, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="computeNode" Type="Microsoft.Azure.Batch.ComputeNode" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="computeNode"><span data-ttu-id="98bf3-298">Die <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-298">The <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="98bf3-299">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="98bf3-299">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="98bf3-300">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-300">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="98bf3-301">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-301">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="98bf3-302">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-302">The default value is 15 minutes.</span></span> <span data-ttu-id="98bf3-303">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-303">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-304">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-304">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-305">Entfernt den angegebenen Serverknoten aus diesem Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-305">Removes the specified compute node from this pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="98bf3-306">Wenn Sie mehrere Compute-Knoten aus einem Pool entfernen müssen, ist es effizienter, verwenden die <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> überladen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-306">If you need to remove multiple compute nodes from a pool, it is more efficient to use the <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> overload.</span></span></para>
          <para><span data-ttu-id="98bf3-307">Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-307">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="98bf3-308">Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</span><span class="sxs-lookup"><span data-stu-id="98bf3-308">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="98bf3-309">Beim Entfernen von Knoten aus eines Pools, den Pool der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert sich von <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-309">When you remove nodes from a pool, the pool's <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> changes from <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="98bf3-310">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="98bf3-310">This is a blocking operation.</span></span> <span data-ttu-id="98bf3-311">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-311">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (computeNodes As IEnumerable(Of ComputeNode), Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : seq&lt;Microsoft.Azure.Batch.ComputeNode&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.RemoveFromPool (computeNodes, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="computeNodes" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="computeNodes"><span data-ttu-id="98bf3-312">Die <see cref="T:Microsoft.Azure.Batch.ComputeNode">Serverknoten</see> aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-312">The <see cref="T:Microsoft.Azure.Batch.ComputeNode">compute nodes</see> to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="98bf3-313">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="98bf3-313">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="98bf3-314">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-314">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="98bf3-315">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-315">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="98bf3-316">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-316">The default value is 15 minutes.</span></span> <span data-ttu-id="98bf3-317">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-317">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-318">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-318">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-319">Entfernt die angegebene Serverknoten aus diesem Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-319">Removes the specified compute nodes from this pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="98bf3-320">Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-320">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="98bf3-321">Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</span><span class="sxs-lookup"><span data-stu-id="98bf3-321">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="98bf3-322">Beim Entfernen von Knoten aus eines Pools, den Pool der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert sich von <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-322">When you remove nodes from a pool, the pool's <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> changes from <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="98bf3-323">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="98bf3-323">This is a blocking operation.</span></span> <span data-ttu-id="98bf3-324">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-324">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (System.Collections.Generic.IEnumerable&lt;string&gt; computeNodeIds, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(class System.Collections.Generic.IEnumerable`1&lt;string&gt; computeNodeIds, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (computeNodeIds As IEnumerable(Of String), Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : seq&lt;string&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.RemoveFromPool (computeNodeIds, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="computeNodeIds" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="computeNodeIds"><span data-ttu-id="98bf3-325">Die Ids der Serverknoten aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-325">The ids of the compute nodes to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="98bf3-326">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="98bf3-326">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="98bf3-327">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-327">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="98bf3-328">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-328">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="98bf3-329">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-329">The default value is 15 minutes.</span></span> <span data-ttu-id="98bf3-330">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-330">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-331">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-331">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-332">Entfernt die angegebene Serverknoten aus diesem Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-332">Removes the specified compute nodes from this pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="98bf3-333">Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-333">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="98bf3-334">Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</span><span class="sxs-lookup"><span data-stu-id="98bf3-334">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="98bf3-335">Beim Entfernen von Knoten aus eines Pools, den Pool der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert sich von <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-335">When you remove nodes from a pool, the pool's <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> changes from <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="98bf3-336">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="98bf3-336">This is a blocking operation.</span></span> <span data-ttu-id="98bf3-337">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-337">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (computeNodeId As String, Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.RemoveFromPool (computeNodeId, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="computeNodeId"><span data-ttu-id="98bf3-338">Die Id der Serverknoten aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-338">The id of the compute node to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="98bf3-339">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="98bf3-339">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="98bf3-340">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-340">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="98bf3-341">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-341">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="98bf3-342">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-342">The default value is 15 minutes.</span></span> <span data-ttu-id="98bf3-343">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-343">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-344">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-344">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-345">Entfernt den angegebenen Serverknoten aus diesem Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-345">Removes the specified compute node from this pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="98bf3-346">Wenn Sie mehrere Compute-Knoten aus einem Pool entfernen müssen, ist es effizienter, verwenden die <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> überladen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-346">If you need to remove multiple compute nodes from a pool, it is more efficient to use the <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> overload.</span></span></para>
          <para><span data-ttu-id="98bf3-347">Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-347">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="98bf3-348">Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</span><span class="sxs-lookup"><span data-stu-id="98bf3-348">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="98bf3-349">Beim Entfernen von Knoten aus eines Pools, den Pool der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert sich von <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-349">When you remove nodes from a pool, the pool's <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> changes from <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="98bf3-350">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="98bf3-350">This is a blocking operation.</span></span> <span data-ttu-id="98bf3-351">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-351">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (Microsoft.Azure.Batch.ComputeNode computeNode, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(class Microsoft.Azure.Batch.ComputeNode computeNode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : Microsoft.Azure.Batch.ComputeNode * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.RemoveFromPoolAsync (computeNode, deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;RemoveFromPoolAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="computeNode" Type="Microsoft.Azure.Batch.ComputeNode" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="computeNode"><span data-ttu-id="98bf3-352">Die <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-352">The <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> to remove from the pool.</span></span></param>
        <param name="deallocationOption"><span data-ttu-id="98bf3-353">Gibt an, wenn der Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="98bf3-353">Specifies when nodes may be removed from the pool.</span></span> <span data-ttu-id="98bf3-354">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-354">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span></param>
        <param name="resizeTimeout"><span data-ttu-id="98bf3-355">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-355">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="98bf3-356">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-356">The default value is 15 minutes.</span></span> <span data-ttu-id="98bf3-357">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-357">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-358">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-358">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98bf3-359">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="98bf3-359">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-360">Entfernt den angegebenen Serverknoten aus diesem Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-360">Removes the specified compute node from this pool.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-361">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-361">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="98bf3-362">Wenn Sie mehrere Compute-Knoten aus einem Pool entfernen müssen, ist es effizienter, verwenden die <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> überladen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-362">If you need to remove multiple compute nodes from a pool, it is more efficient to use the <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> overload.</span></span></para>
          <para><span data-ttu-id="98bf3-363">Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-363">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="98bf3-364">Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</span><span class="sxs-lookup"><span data-stu-id="98bf3-364">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="98bf3-365">Beim Entfernen von Knoten aus eines Pools, den Pool der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert sich von <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-365">When you remove nodes from a pool, the pool's <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> changes from <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="98bf3-366">Der Entfernungsvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-366">The remove operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : seq&lt;Microsoft.Azure.Batch.ComputeNode&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.RemoveFromPoolAsync (computeNodes, deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;RemoveFromPoolAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="computeNodes" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="computeNodes"><span data-ttu-id="98bf3-367">Die <see cref="T:Microsoft.Azure.Batch.ComputeNode">Serverknoten</see> aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-367">The <see cref="T:Microsoft.Azure.Batch.ComputeNode">compute nodes</see> to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="98bf3-368">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="98bf3-368">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="98bf3-369">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-369">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="98bf3-370">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-370">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="98bf3-371">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-371">The default value is 15 minutes.</span></span> <span data-ttu-id="98bf3-372">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-372">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-373">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-373">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98bf3-374">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="98bf3-374">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-375">Entfernt die angegebene Serverknoten aus diesem Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-375">Removes the specified compute nodes from this pool.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-376">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-376">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="98bf3-377">Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-377">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="98bf3-378">Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</span><span class="sxs-lookup"><span data-stu-id="98bf3-378">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="98bf3-379">Beim Entfernen von Knoten aus eines Pools, den Pool der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert sich von <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-379">When you remove nodes from a pool, the pool's <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> changes from <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="98bf3-380">Der Entfernungsvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-380">The remove operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (System.Collections.Generic.IEnumerable&lt;string&gt; computeNodeIds, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; computeNodeIds, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : seq&lt;string&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.RemoveFromPoolAsync (computeNodeIds, deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;RemoveFromPoolAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="computeNodeIds" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="computeNodeIds"><span data-ttu-id="98bf3-381">Die Ids der Serverknoten aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-381">The ids of the compute nodes to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="98bf3-382">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="98bf3-382">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="98bf3-383">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-383">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="98bf3-384">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-384">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="98bf3-385">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-385">The default value is 15 minutes.</span></span> <span data-ttu-id="98bf3-386">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-386">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-387">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-387">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98bf3-388">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="98bf3-388">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-389">Entfernt die angegebene Serverknoten aus diesem Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-389">Removes the specified compute nodes from this pool.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-390">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-390">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="98bf3-391">Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-391">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="98bf3-392">Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</span><span class="sxs-lookup"><span data-stu-id="98bf3-392">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="98bf3-393">Beim Entfernen von Knoten aus eines Pools, den Pool der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert sich von <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-393">When you remove nodes from a pool, the pool's <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> changes from <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="98bf3-394">Der Entfernungsvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-394">The remove operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.RemoveFromPoolAsync (computeNodeId, deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;RemoveFromPoolAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="computeNodeId"><span data-ttu-id="98bf3-395">Die Id der Serverknoten aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-395">The id of the compute node to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="98bf3-396">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="98bf3-396">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="98bf3-397">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-397">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="98bf3-398">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-398">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="98bf3-399">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-399">The default value is 15 minutes.</span></span> <span data-ttu-id="98bf3-400">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-400">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-401">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-401">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98bf3-402">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="98bf3-402">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-403">Entfernt den angegebenen Serverknoten aus diesem Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-403">Removes the specified compute node from this pool.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-404">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-404">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="98bf3-405">Wenn Sie mehrere Compute-Knoten aus einem Pool entfernen müssen, ist es effizienter, verwenden die <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> überladen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-405">If you need to remove multiple compute nodes from a pool, it is more efficient to use the <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> overload.</span></span></para>
          <para><span data-ttu-id="98bf3-406">Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-406">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="98bf3-407">Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</span><span class="sxs-lookup"><span data-stu-id="98bf3-407">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="98bf3-408">Beim Entfernen von Knoten aus eines Pools, den Pool der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert sich von <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-408">When you remove nodes from a pool, the pool's <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> changes from <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="98bf3-409">Der Entfernungsvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-409">The remove operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Resize">
      <MemberSignature Language="C#" Value="public void Resize (Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Resize(valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.Resize(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Resize (Optional targetDedicatedComputeNodes As Nullable(Of Integer) = null, Optional targetLowPriorityComputeNodes As Nullable(Of Integer) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Resize : Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.Resize (targetDedicatedComputeNodes, targetLowPriorityComputeNodes, resizeTimeout, deallocationOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="targetDedicatedComputeNodes">
            <span data-ttu-id="98bf3-410">Die gewünschte Anzahl von dedizierten Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-410">The desired number of dedicated compute nodes in the pool.</span></span>
            <span data-ttu-id="98bf3-411">Mindestens eine der <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> ist erforderlich.</span><span class="sxs-lookup"><span data-stu-id="98bf3-411">At least one of <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> is required.</span></span>
            </param>
        <param name="targetLowPriorityComputeNodes">
            <span data-ttu-id="98bf3-412">Die gewünschte Anzahl von mit niedriger Priorität Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-412">The desired number of low-priority compute nodes in the pool.</span></span>
            <span data-ttu-id="98bf3-413">Mindestens eine der <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> ist erforderlich.</span><span class="sxs-lookup"><span data-stu-id="98bf3-413">At least one of <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> is required.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="98bf3-414">Das Timeout für die Belegung der Serverknoten an den Pool oder Entfernen von Computeknoten aus dem Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-414">The timeout for allocation of compute nodes to the pool or removal of compute nodes from the pool.</span></span> <span data-ttu-id="98bf3-415">Wenn der Pool nach diesem Zeitpunkt nicht auf die Zielgröße erreicht hat, wird die Größenänderung beendet.</span><span class="sxs-lookup"><span data-stu-id="98bf3-415">If the pool has not reached the target size after this time, the resize is stopped.</span></span> <span data-ttu-id="98bf3-416">Der Standardwert ist 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-416">The default is 15 minutes.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="98bf3-417">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten möglicherweise aus dem Pool entfernt werden, wenn Verkleinerung des Pools.</span><span class="sxs-lookup"><span data-stu-id="98bf3-417">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool, if the pool size is decreasing.</span></span> <span data-ttu-id="98bf3-418">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-418">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-419">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-419">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-420">Ändert die Größe dieses Pools.</span><span class="sxs-lookup"><span data-stu-id="98bf3-420">Resizes this pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="98bf3-421">Die Größenänderung fordert, dass der Pool Größe geändert werden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-421">The resize operation requests that the pool be resized.</span></span>  <span data-ttu-id="98bf3-422">Die Anforderung setzt den Pool in den <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" /> Zuordnungsstatus.</span><span class="sxs-lookup"><span data-stu-id="98bf3-422">The request puts the pool in the <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" /> allocation state.</span></span>
            <span data-ttu-id="98bf3-423">Der Batch-Dienst die tatsächliche Größe ohne weitere Clientaktion durchgeführt werden, und legen Sie den Zuordnungsstatus auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> Sie abschließend auf.</span><span class="sxs-lookup"><span data-stu-id="98bf3-423">The Batch service will perform the actual resize without any further client action, and set the allocation state to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> once complete.</span></span></para>
          <para>
            <span data-ttu-id="98bf3-424">Sie können nur die Größe eines Pools bei seiner <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-424">You can only resize a pool when its <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span>
            <span data-ttu-id="98bf3-425">Kann nicht geändert werden, die für die automatische Skalierung konfiguriert sind Pools (d. h. die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> Eigenschaft des Pools ist "true").</span><span class="sxs-lookup"><span data-stu-id="98bf3-425">You cannot resize pools which are configured for automatic scaling (that is, the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> property of the pool is true).</span></span>
            <span data-ttu-id="98bf3-426">Wenn Sie die Poolgröße verringern, wählt der Batch-Dienst die Knoten aus, zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-426">If you decrease the pool size, the Batch service chooses which nodes to remove.</span></span>  <span data-ttu-id="98bf3-427">Rufen Sie zum Entfernen von bestimmten Knoten <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-427">To remove specific nodes, call <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span>
            </para>
          <para><span data-ttu-id="98bf3-428">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="98bf3-428">This is a blocking operation.</span></span> <span data-ttu-id="98bf3-429">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.ResizeAsync(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-429">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudPool.ResizeAsync(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResizeAsync (Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ResizeAsync(valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.ResizeAsync(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResizeAsync : Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.ResizeAsync (targetDedicatedComputeNodes, targetLowPriorityComputeNodes, resizeTimeout, deallocationOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="targetDedicatedComputeNodes">
            <span data-ttu-id="98bf3-430">Die gewünschte Anzahl von dedizierten Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-430">The desired number of dedicated compute nodes in the pool.</span></span>
            <span data-ttu-id="98bf3-431">Mindestens eine der <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> ist erforderlich.</span><span class="sxs-lookup"><span data-stu-id="98bf3-431">At least one of <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> is required.</span></span>
            </param>
        <param name="targetLowPriorityComputeNodes">
            <span data-ttu-id="98bf3-432">Die gewünschte Anzahl von mit niedriger Priorität Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-432">The desired number of low-priority compute nodes in the pool.</span></span>
            <span data-ttu-id="98bf3-433">Mindestens eine der <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> ist erforderlich.</span><span class="sxs-lookup"><span data-stu-id="98bf3-433">At least one of <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> is required.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="98bf3-434">Das Timeout für die Belegung der Serverknoten an den Pool oder Entfernen von Computeknoten aus dem Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-434">The timeout for allocation of compute nodes to the pool or removal of compute nodes from the pool.</span></span> <span data-ttu-id="98bf3-435">Wenn der Pool nach diesem Zeitpunkt nicht auf die Zielgröße erreicht hat, wird die Größenänderung beendet.</span><span class="sxs-lookup"><span data-stu-id="98bf3-435">If the pool has not reached the target size after this time, the resize is stopped.</span></span> <span data-ttu-id="98bf3-436">Der Standardwert ist 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="98bf3-436">The default is 15 minutes.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="98bf3-437">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten möglicherweise aus dem Pool entfernt werden, wenn Verkleinerung des Pools.</span><span class="sxs-lookup"><span data-stu-id="98bf3-437">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool, if the pool size is decreasing.</span></span> <span data-ttu-id="98bf3-438">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-438">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-439">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-439">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98bf3-440">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="98bf3-440">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-441">Ändert die Größe dieses Pools.</span><span class="sxs-lookup"><span data-stu-id="98bf3-441">Resizes this pool.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-442">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-442">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="98bf3-443">Die Größenänderung fordert, dass der Pool Größe geändert werden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-443">The resize operation requests that the pool be resized.</span></span>  <span data-ttu-id="98bf3-444">Die Anforderung setzt den Pool in den <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" /> Zuordnungsstatus.</span><span class="sxs-lookup"><span data-stu-id="98bf3-444">The request puts the pool in the <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" /> allocation state.</span></span>
            <span data-ttu-id="98bf3-445">Der Batch-Dienst die tatsächliche Größe ohne weitere Clientaktion durchgeführt werden, und legen Sie den Zuordnungsstatus auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> Sie abschließend auf.</span><span class="sxs-lookup"><span data-stu-id="98bf3-445">The Batch service will perform the actual resize without any further client action, and set the allocation state to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> once complete.</span></span></para>
          <para>
            <span data-ttu-id="98bf3-446">Sie können nur die Größe eines Pools bei seiner <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-446">You can only resize a pool when its <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span>
            <span data-ttu-id="98bf3-447">Kann nicht geändert werden, die für die automatische Skalierung konfiguriert sind Pools (d. h. die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> Eigenschaft des Pools ist "true").</span><span class="sxs-lookup"><span data-stu-id="98bf3-447">You cannot resize pools which are configured for automatic scaling (that is, the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> property of the pool is true).</span></span>
            <span data-ttu-id="98bf3-448">Wenn Sie die Poolgröße verringern, wählt der Batch-Dienst die Knoten aus, zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-448">If you decrease the pool size, the Batch service chooses which nodes to remove.</span></span>  <span data-ttu-id="98bf3-449">Rufen Sie zum Entfernen von bestimmten Knoten <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-449">To remove specific nodes, call <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span>
            </para>
          <para><span data-ttu-id="98bf3-450">Die Größenänderung wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-450">The resize operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeErrors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ResizeError&gt; ResizeErrors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.ResizeError&gt; ResizeErrors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.ResizeErrors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResizeErrors As IReadOnlyList(Of ResizeError)" />
      <MemberSignature Language="F#" Value="member this.ResizeErrors : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ResizeError&gt;" Usage="Microsoft.Azure.Batch.CloudPool.ResizeErrors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ResizeError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-451">Ruft eine Liste der Fehler aufgetreten, der letzten Größenänderung auf der <see cref="T:Microsoft.Azure.Batch.CloudPool" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-451">Gets a list of errors encountered while performing the last resize on the <see cref="T:Microsoft.Azure.Batch.CloudPool" />.</span></span> <span data-ttu-id="98bf3-452">Fehler werden zurückgegeben, nur, wenn der Batch-Dienst ein Fehler beim Ändern der Größe des Pools und des Pools <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ist <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState">stetige</see>.</span><span class="sxs-lookup"><span data-stu-id="98bf3-452">Errors are returned only when the Batch service encountered an error while resizing the pool, and when the pool's <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> is <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState">Steady</see>.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ResizeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ResizeTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.ResizeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ResizeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.ResizeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-453">Ruft ab oder legt das Timeout für die Zuweisung von Serverknoten in den Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-453">Gets or sets the timeout for allocation of compute nodes to the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.StartTask with get, set" Usage="Microsoft.Azure.Batch.CloudPool.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-454">Ruft ab oder legt einen Task auf jeder Compute-Knoten ausgeführt wird, wie den Pool hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="98bf3-454">Gets or sets a task to run on each compute node as it joins the pool.</span></span> <span data-ttu-id="98bf3-455">Der Task ausgeführt wird, wenn der Knoten hinzugefügt wird, an den Pool oder der Knoten neu gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="98bf3-455">The task runs when the node is added to the pool or when the node is restarted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.PoolState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.PoolState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of PoolState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Common.PoolState&gt;" Usage="Microsoft.Azure.Batch.CloudPool.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.PoolState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-456">Ruft den aktuellen Status des Pools an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-456">Gets the current state of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudPool.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-457">Ruft den Zeitpunkt, an dem der Pool seinem aktuellen Status erlangt hat.</span><span class="sxs-lookup"><span data-stu-id="98bf3-457">Gets the time at which the pool entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolStatistics Statistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.PoolStatistics Statistics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.Statistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Statistics As PoolStatistics" />
      <MemberSignature Language="F#" Value="member this.Statistics : Microsoft.Azure.Batch.PoolStatistics" Usage="Microsoft.Azure.Batch.CloudPool.Statistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-458">Ruft die ressourcenauslastungsstatistiken für den Pool an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-458">Gets the resource usage statistics for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="98bf3-459">Diese Eigenschaft wird nur aufgefüllt, wenn die <see cref="T:Microsoft.Azure.Batch.CloudPool" /> abgerufen wurde, mit einem <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" /> einschließlich das 'Statistiken für Ressourcenpools'-Attribut; andernfalls ist null.</span><span class="sxs-lookup"><span data-stu-id="98bf3-459">This property is populated only if the <see cref="T:Microsoft.Azure.Batch.CloudPool" /> was retrieved with an <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" /> including the 'stats' attribute; otherwise it is null.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResize">
      <MemberSignature Language="C#" Value="public void StopResize (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void StopResize(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.StopResize(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub StopResize (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.StopResize : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.StopResize additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-460">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-460">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-461">Beendet eine Größenänderung für diesen Pool an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-461">Stops a resize operation on this pool.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-462">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-462">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="98bf3-463">Dieser Vorgang wird ein größenänderungsvorgang für den Pool beendet.</span><span class="sxs-lookup"><span data-stu-id="98bf3-463">This operation stops an ongoing resize operation on the pool.</span></span>  <span data-ttu-id="98bf3-464">Die Größe des Pools wird nach der Anzahl von Knoten stabilisieren, die sie sich befindet, wenn der Beendigungsvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="98bf3-464">The pool size will stabilize at the number of nodes it is at when the stop operation is done.</span></span>  <span data-ttu-id="98bf3-465">Während des Beendigungsvorgangs Pool <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert zunächst in <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" /> , und klicken Sie dann auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-465">During the stop operation, the pool <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> changes first to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" /> and then to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span>
            </para>
          <para><span data-ttu-id="98bf3-466">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="98bf3-466">This is a blocking operation.</span></span> <span data-ttu-id="98bf3-467">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.StopResizeAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-467">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudPool.StopResizeAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResizeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopResizeAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StopResizeAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.StopResizeAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopResizeAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.StopResizeAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="98bf3-468">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-468">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98bf3-469">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="98bf3-469">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="98bf3-470">Beendet eine Größenänderung für diesen Pool an.</span><span class="sxs-lookup"><span data-stu-id="98bf3-470">Stops a resize operation on this pool.</span></span>
            </summary>
        <returns><span data-ttu-id="98bf3-471">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-471">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="98bf3-472">Dieser Vorgang wird ein größenänderungsvorgang für den Pool beendet.</span><span class="sxs-lookup"><span data-stu-id="98bf3-472">This operation stops an ongoing resize operation on the pool.</span></span>  <span data-ttu-id="98bf3-473">Die Größe des Pools wird nach der Anzahl von Knoten stabilisieren, die sie sich befindet, wenn der Beendigungsvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="98bf3-473">The pool size will stabilize at the number of nodes it is at when the stop operation is done.</span></span>  <span data-ttu-id="98bf3-474">Während des Beendigungsvorgangs Pool <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert zunächst in <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" /> , und klicken Sie dann auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="98bf3-474">During the stop operation, the pool <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> changes first to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" /> and then to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span>
            </para>
          <para><span data-ttu-id="98bf3-475">Zum Beenden der Größe Vorgang führt asynchron aus.</span><span class="sxs-lookup"><span data-stu-id="98bf3-475">The stop resize operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicated">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicated { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.TargetDedicated" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicated As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicated : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.TargetDedicated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Obsolete after 05/2017, use TargetDedicatedComputeNodes instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-476">Diese Eigenschaft ist ein Alias für <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetDedicatedComputeNodes" /> und wird nur für Abwärtskompatibilität unterstützt.</span><span class="sxs-lookup"><span data-stu-id="98bf3-476">This property is an alias for <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetDedicatedComputeNodes" /> and is supported only for backward compatibility.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicatedComputeNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicatedComputeNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicatedComputeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.TargetDedicatedComputeNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicatedComputeNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicatedComputeNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.TargetDedicatedComputeNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-477">Ruft ab oder legt die gewünschte Anzahl von dedizierten Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-477">Gets or sets the desired number of dedicated compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="98bf3-478">Diese Einstellung kann nicht angegeben werden, wenn <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> festgelegt ist auf "true".</span><span class="sxs-lookup"><span data-stu-id="98bf3-478">This setting cannot be specified if <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> is set to true.</span></span> <span data-ttu-id="98bf3-479">Mindestens eine dieser Eigenschaft und <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetLowPriorityComputeNodes" /> muss angegeben werden, wenn <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> lautet "false".</span><span class="sxs-lookup"><span data-stu-id="98bf3-479">At least one of this property and <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetLowPriorityComputeNodes" /> must be specified if <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> is false.</span></span> <span data-ttu-id="98bf3-480">Wenn nicht angegeben, lautet der Standardwert 0.</span><span class="sxs-lookup"><span data-stu-id="98bf3-480">If not specified, the default is 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLowPriorityComputeNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetLowPriorityComputeNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetLowPriorityComputeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.TargetLowPriorityComputeNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLowPriorityComputeNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetLowPriorityComputeNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.TargetLowPriorityComputeNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-481">Ruft ab oder legt die gewünschte Anzahl von Serverknoten mit niedriger Priorität im Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-481">Gets or sets the desired number of low-priority compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="98bf3-482">Diese Einstellung kann nicht angegeben werden, wenn <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> festgelegt ist auf "true".</span><span class="sxs-lookup"><span data-stu-id="98bf3-482">This setting cannot be specified if <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> is set to true.</span></span> <span data-ttu-id="98bf3-483">Mindestens eine der <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetDedicatedComputeNodes" /> und diese Eigenschaft muss angegeben werden, wenn <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> lautet "false".</span><span class="sxs-lookup"><span data-stu-id="98bf3-483">At least one of <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetDedicatedComputeNodes" /> and this property must be specified if <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> is false.</span></span> <span data-ttu-id="98bf3-484">Wenn nicht angegeben, lautet der Standardwert 0.</span><span class="sxs-lookup"><span data-stu-id="98bf3-484">If not specified, the default is 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskSchedulingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskSchedulingPolicy TaskSchedulingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskSchedulingPolicy TaskSchedulingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.TaskSchedulingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskSchedulingPolicy As TaskSchedulingPolicy" />
      <MemberSignature Language="F#" Value="member this.TaskSchedulingPolicy : Microsoft.Azure.Batch.TaskSchedulingPolicy with get, set" Usage="Microsoft.Azure.Batch.CloudPool.TaskSchedulingPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskSchedulingPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-485">Ruft ab oder legt sie fest, wie Aufgaben auf Serverknoten im Pool verteilt sind.</span><span class="sxs-lookup"><span data-stu-id="98bf3-485">Gets or sets how tasks are distributed among compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.CloudPool.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-486">Ruft die URL des Pools.</span><span class="sxs-lookup"><span data-stu-id="98bf3-486">Gets the URL of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.UserAccount&gt; UserAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.UserAccount&gt; UserAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.UserAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccounts As IList(Of UserAccount)" />
      <MemberSignature Language="F#" Value="member this.UserAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.UserAccount&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.UserAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.UserAccount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-487">Ruft ab oder legt die Liste der Benutzerkonten auf jedem Knoten im Pool erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="98bf3-487">Gets or sets the list of user accounts to be created on each node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.VirtualMachineConfiguration VirtualMachineConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.VirtualMachineConfiguration VirtualMachineConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineConfiguration As VirtualMachineConfiguration" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineConfiguration : Microsoft.Azure.Batch.VirtualMachineConfiguration with get, set" Usage="Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.VirtualMachineConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-488">Ruft ab oder legt die <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" /> des Pools.</span><span class="sxs-lookup"><span data-stu-id="98bf3-488">Gets or sets the <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" /> of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineSize">
      <MemberSignature Language="C#" Value="public string VirtualMachineSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineSize As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineSize : string with get, set" Usage="Microsoft.Azure.Batch.CloudPool.VirtualMachineSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98bf3-489">Ruft ab oder legt die Größe der virtuellen Computer im Pool.</span><span class="sxs-lookup"><span data-stu-id="98bf3-489">Gets or sets the size of the virtual machines in the pool.</span></span>  <span data-ttu-id="98bf3-490">Alle virtuellen Computer in einem Pool haben die gleiche Größe.</span><span class="sxs-lookup"><span data-stu-id="98bf3-490">All virtual machines in a pool are the same size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="98bf3-491">Informationen zu den verfügbaren Größen von virtuellen Maschinen für Cloud-Dienste-Pools (Pools mit erstellt eine <see cref="P:Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" />), finden Sie unter https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/.</span><span class="sxs-lookup"><span data-stu-id="98bf3-491">For information about available sizes of virtual machines for Cloud Services pools (pools created with a <see cref="P:Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" />), see https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/.</span></span> <span data-ttu-id="98bf3-492">Batch unterstützt alle Cloud-Dienste VM-Größen sind ExtraSmall mit Ausnahme von.</span><span class="sxs-lookup"><span data-stu-id="98bf3-492">Batch supports all Cloud Services VM sizes except ExtraSmall.</span></span></para>
          <para><span data-ttu-id="98bf3-493">Informationen zu den verfügbaren VM-Größen für Anwendungspools, die mithilfe von Images von virtuellen Maschinen Marketplace (mit erstellten Ressourcenpools einer <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" />) finden Sie unter https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ oder https:// Azure.Microsoft.com/Documentation/articles/Virtual-Machines-Windows-sizes/.</span><span class="sxs-lookup"><span data-stu-id="98bf3-493">For information about available VM sizes for pools using images from the Virtual Machines Marketplace (pools created with a <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" />) see https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ or https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/.</span></span> <span data-ttu-id="98bf3-494">Batch unterstützt alle Azure-VM-Größen außer STANDARD_A0 und die mit Premium-Speicher (z. B. STANDARD_GS STANDARD_DS und STANDARD_DSV2-Serie).</span><span class="sxs-lookup"><span data-stu-id="98bf3-494">Batch supports all Azure VM sizes except STANDARD_A0 and those with premium storage (for example STANDARD_GS, STANDARD_DS, and STANDARD_DSV2 series).</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>