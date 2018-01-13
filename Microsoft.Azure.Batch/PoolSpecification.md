<Type Name="PoolSpecification" FullName="Microsoft.Azure.Batch.PoolSpecification">
  <TypeSignature Language="C#" Value="public class PoolSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PoolSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolSpecification" />
  <TypeSignature Language="F#" Value="type PoolSpecification = class&#xA;    interface ITransportObjectProvider&lt;PoolSpecification&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="62d98-101">Die Spezifikation für einen Pool.</span><span class="sxs-lookup"><span data-stu-id="62d98-101">The specification for a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolSpecification.#ctor" />
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
            <span data-ttu-id="62d98-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.PoolSpecification" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="62d98-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.PoolSpecification" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLicenses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApplicationLicenses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApplicationLicenses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.ApplicationLicenses" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationLicenses As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLicenses : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.ApplicationLicenses" />
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
            <span data-ttu-id="62d98-103">Ruft ab oder legt die Liste der Anwendungslizenzen der Batch-Dienst auf jeder Serverknoten im Pool verfügbar gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="62d98-103">Gets or sets the list of application licenses the Batch service will make available on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="62d98-104">Die Liste der Anwendungslizenzen muss es sich um eine Teilmenge der verfügbaren Batch Dienstlizenzen Anwendung sein.</span><span class="sxs-lookup"><span data-stu-id="62d98-104">The list of application licenses must be a subset of available Batch service application licenses.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.ApplicationPackageReferences" />
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
            <span data-ttu-id="62d98-105">Ruft ab oder legt eine Liste der Anwendungsverweise an Paket auf jeder Serverknoten im Pool installiert werden.</span><span class="sxs-lookup"><span data-stu-id="62d98-105">Gets or sets a list of application package references to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoScaleEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoScaleEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" />
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
            <span data-ttu-id="62d98-106">Ruft ab oder legt fest, ob die Größe des Pools mit der Zeit automatisch angepasst.</span><span class="sxs-lookup"><span data-stu-id="62d98-106">Gets or sets whether the pool size should automatically adjust over time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="62d98-107">Wenn "false" eines der <see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" /> oder <see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetLowPriorityComputeNodes" /> ist eine erforderliche Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="62d98-107">If false, one of the <see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" /> or <see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetLowPriorityComputeNodes" /> property is required.</span></span></para>
          <para><span data-ttu-id="62d98-108">Bei "true", die <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleFormula" /> ist eine erforderliche Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="62d98-108">If true, the <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleFormula" /> property is required.</span></span> <span data-ttu-id="62d98-109">Der Pool wird automatisch entsprechend der Formel.</span><span class="sxs-lookup"><span data-stu-id="62d98-109">The pool automatically resizes according to the formula.</span></span></para>
          <para><span data-ttu-id="62d98-110">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="62d98-110">The default value is false.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEvaluationInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoScaleEvaluationInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoScaleEvaluationInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEvaluationInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEvaluationInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEvaluationInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.AutoScaleEvaluationInterval" />
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
            <span data-ttu-id="62d98-111">Ruft ab oder legt ein Zeitintervall an, passen Sie die Poolgröße gemäß automatisch an die <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleFormula" />.</span><span class="sxs-lookup"><span data-stu-id="62d98-111">Gets or sets a time interval at which to automatically adjust the pool size according to the <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleFormula" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="62d98-112">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="62d98-112">The default value is 15 minutes.</span></span> <span data-ttu-id="62d98-113">Der minimal zulässige Wert beträgt 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="62d98-113">The minimum allowed value is 5 minutes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleFormula">
      <MemberSignature Language="C#" Value="public string AutoScaleFormula { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoScaleFormula" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleFormula" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleFormula As String" />
      <MemberSignature Language="F#" Value="member this.AutoScaleFormula : string with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.AutoScaleFormula" />
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
            <span data-ttu-id="62d98-114">Ruft ab oder legt eine Formel für die gewünschte Anzahl von Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="62d98-114">Gets or sets a formula for the desired number of compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="62d98-115">Für das Schreiben von Formeln für automatische Skalierung finden Sie unter https://azure.microsoft.com/documentation/articles/batch-automatic-scaling/.</span><span class="sxs-lookup"><span data-stu-id="62d98-115">For how to write autoscale formulas, see https://azure.microsoft.com/documentation/articles/batch-automatic-scaling/.</span></span> <span data-ttu-id="62d98-116">Diese Eigenschaft ist erforderlich, wenn <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> festgelegt ist auf "true".</span><span class="sxs-lookup"><span data-stu-id="62d98-116">This property is required if <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> is set to true.</span></span> <span data-ttu-id="62d98-117">Sie muss null sein, wenn AutoScaleEnabled auf "false" festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="62d98-117">It must be null if AutoScaleEnabled is false.</span></span></para>
          <para><span data-ttu-id="62d98-118">Die Formel wird auf Gültigkeit überprüft, bevor der Pool erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="62d98-118">The formula is checked for validity before the pool is created.</span></span> <span data-ttu-id="62d98-119">Wenn die Formel nicht gültig ist, wird eine Ausnahme ausgelöst, wenn Sie versuchen, einen commit für die <see cref="T:Microsoft.Azure.Batch.PoolSpecification" />.</span><span class="sxs-lookup"><span data-stu-id="62d98-119">If the formula is not valid, an exception is thrown when you try to commit the <see cref="T:Microsoft.Azure.Batch.PoolSpecification" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.CertificateReference&gt; CertificateReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateReferences As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.CertificateReferences" />
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
            <span data-ttu-id="62d98-120">Ruft ab oder legt eine Liste der Zertifikate auf jeder Serverknoten im Pool installiert werden.</span><span class="sxs-lookup"><span data-stu-id="62d98-120">Gets or sets a list of certificates to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudServiceConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudServiceConfiguration CloudServiceConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.CloudServiceConfiguration CloudServiceConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudServiceConfiguration As CloudServiceConfiguration" />
      <MemberSignature Language="F#" Value="member this.CloudServiceConfiguration : Microsoft.Azure.Batch.CloudServiceConfiguration with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" />
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
            <span data-ttu-id="62d98-121">Ruft ab oder legt die <see cref="P:Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" /> für den Pool.</span><span class="sxs-lookup"><span data-stu-id="62d98-121">Gets or sets the <see cref="P:Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" /> for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="62d98-122">Diese Eigenschaft ist mit sich gegenseitig ausschließende <see cref="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" />.</span><span class="sxs-lookup"><span data-stu-id="62d98-122">This property is mutually exclusive with <see cref="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.DisplayName" />
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
            <span data-ttu-id="62d98-123">Ruft ab oder legt den Anzeigenamen für den Pool.</span><span class="sxs-lookup"><span data-stu-id="62d98-123">Gets or sets the display name for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InterComputeNodeCommunicationEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; InterComputeNodeCommunicationEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; InterComputeNodeCommunicationEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.InterComputeNodeCommunicationEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property InterComputeNodeCommunicationEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.InterComputeNodeCommunicationEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.InterComputeNodeCommunicationEnabled" />
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
            <span data-ttu-id="62d98-124">Ruft ab oder legt sie fest, ob der Pool direkten Kommunikation zwischen der Serverknoten zulässt.</span><span class="sxs-lookup"><span data-stu-id="62d98-124">Gets or sets whether the pool permits direct communication between its compute nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="62d98-125">Aktivieren der Kommunikation zwischen den Knoten schränkt die maximale Größe des Pools aufgrund von Einschränkungen der Bereitstellung auf den Knoten des Pools.</span><span class="sxs-lookup"><span data-stu-id="62d98-125">Enabling inter-node communication limits the maximum size of the pool due to deployment restrictions on the nodes of the pool.</span></span> <span data-ttu-id="62d98-126">Dies kann im Pool nicht die gewünschte Größe erreichen führen.</span><span class="sxs-lookup"><span data-stu-id="62d98-126">This may result in the pool not reaching its desired size.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTasksPerComputeNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTasksPerComputeNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTasksPerComputeNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.MaxTasksPerComputeNode" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTasksPerComputeNode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTasksPerComputeNode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.MaxTasksPerComputeNode" />
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
            <span data-ttu-id="62d98-127">Ruft ab oder legt die maximale Anzahl von Aufgaben, die gleichzeitig auf einem einzelnen Serverknoten im Pool ausgeführt werden können.</span><span class="sxs-lookup"><span data-stu-id="62d98-127">Gets or sets the maximum number of tasks that can run concurrently on a single compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="62d98-128">Der Standardwert ist 1.</span><span class="sxs-lookup"><span data-stu-id="62d98-128">The default value is 1.</span></span> <span data-ttu-id="62d98-129">Der maximale Wert dieser Einstellung hängt von der Größe der Serverknoten im Pool (die <see cref="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineSize" /> Eigenschaft).</span><span class="sxs-lookup"><span data-stu-id="62d98-129">The maximum value of this setting depends on the size of the compute nodes in the pool (the <see cref="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineSize" /> property).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.Metadata" />
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
            <span data-ttu-id="62d98-130">Ruft ab oder legt eine Liste von Name / Wert-Paaren, die dem Pool als Metadaten zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="62d98-130">Gets or sets a list of name-value pairs associated with the pool as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.NetworkConfiguration NetworkConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.NetworkConfiguration NetworkConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.NetworkConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkConfiguration As NetworkConfiguration" />
      <MemberSignature Language="F#" Value="member this.NetworkConfiguration : Microsoft.Azure.Batch.NetworkConfiguration with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.NetworkConfiguration" />
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
            <span data-ttu-id="62d98-131">Ruft ab oder legt die Netzwerkkonfiguration des Pools.</span><span class="sxs-lookup"><span data-stu-id="62d98-131">Gets or sets the network configuration of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ResizeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ResizeTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.ResizeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ResizeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.ResizeTimeout" />
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
            <span data-ttu-id="62d98-132">Ruft ab oder legt das Timeout für die Zuweisung von Serverknoten in den Pool.</span><span class="sxs-lookup"><span data-stu-id="62d98-132">Gets or sets the timeout for allocation of compute nodes to the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="62d98-133">Dieses Timeout gilt nur für die manuelle Skalierung. Es hat keine Wirkung, wenn <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> festgelegt ist auf "true".</span><span class="sxs-lookup"><span data-stu-id="62d98-133">This timeout applies only to manual scaling; it has no effect when <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> is set to true.</span></span></para>
          <para><span data-ttu-id="62d98-134">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="62d98-134">The default value is 15 minutes.</span></span> <span data-ttu-id="62d98-135">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="62d98-135">The minimum value is 5 minutes.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.StartTask with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.StartTask" />
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
            <span data-ttu-id="62d98-136">Ruft ab oder legt einen Task auf jeder Compute-Knoten ausgeführt wird, wie den Pool hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="62d98-136">Gets or sets a task to run on each compute node as it joins the pool.</span></span> <span data-ttu-id="62d98-137">Der Task ausgeführt wird, wenn der Knoten hinzugefügt wird, an den Pool oder der Knoten neu gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="62d98-137">The task runs when the node is added to the pool or when the node is restarted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicated">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicated { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicated" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicated As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicated : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.TargetDedicated" />
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
            <span data-ttu-id="62d98-138">Diese Eigenschaft ist ein Alias für <see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" /> und wird nur für Abwärtskompatibilität unterstützt.</span><span class="sxs-lookup"><span data-stu-id="62d98-138">This property is an alias for <see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" /> and is supported only for backward compatibility.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicatedComputeNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicatedComputeNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicatedComputeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicatedComputeNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicatedComputeNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" />
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
            <span data-ttu-id="62d98-139">Ruft ab oder legt die gewünschte Anzahl von dedizierten Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="62d98-139">Gets or sets the desired number of dedicated compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="62d98-140">Diese Einstellung kann nicht angegeben werden, wenn <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> festgelegt ist auf "true".</span><span class="sxs-lookup"><span data-stu-id="62d98-140">This setting cannot be specified if <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> is set to true.</span></span> <span data-ttu-id="62d98-141">Mindestens eine dieser Eigenschaft und <see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetLowPriorityComputeNodes" /> muss angegeben werden, wenn <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> lautet "false".</span><span class="sxs-lookup"><span data-stu-id="62d98-141">At least one of this property and <see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetLowPriorityComputeNodes" /> must be specified if <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> is false.</span></span> <span data-ttu-id="62d98-142">Wenn nicht angegeben, lautet der Standardwert 0.</span><span class="sxs-lookup"><span data-stu-id="62d98-142">If not specified, the default is 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLowPriorityComputeNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetLowPriorityComputeNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetLowPriorityComputeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.TargetLowPriorityComputeNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLowPriorityComputeNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetLowPriorityComputeNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.TargetLowPriorityComputeNodes" />
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
            <span data-ttu-id="62d98-143">Ruft ab oder legt die gewünschte Anzahl von Serverknoten mit niedriger Priorität im Pool.</span><span class="sxs-lookup"><span data-stu-id="62d98-143">Gets or sets the desired number of low-priority compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="62d98-144">Diese Einstellung kann nicht angegeben werden, wenn <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> festgelegt ist auf "true".</span><span class="sxs-lookup"><span data-stu-id="62d98-144">This setting cannot be specified if <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> is set to true.</span></span> <span data-ttu-id="62d98-145">Mindestens eine der <see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" /> und diese Eigenschaft muss angegeben werden, wenn <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> lautet "false".</span><span class="sxs-lookup"><span data-stu-id="62d98-145">At least one of <see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" /> and this property must be specified if <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> is false.</span></span> <span data-ttu-id="62d98-146">Wenn nicht angegeben, lautet der Standardwert 0.</span><span class="sxs-lookup"><span data-stu-id="62d98-146">If not specified, the default is 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskSchedulingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskSchedulingPolicy TaskSchedulingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskSchedulingPolicy TaskSchedulingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.TaskSchedulingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskSchedulingPolicy As TaskSchedulingPolicy" />
      <MemberSignature Language="F#" Value="member this.TaskSchedulingPolicy : Microsoft.Azure.Batch.TaskSchedulingPolicy with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.TaskSchedulingPolicy" />
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
            <span data-ttu-id="62d98-147">Ruft ab oder legt sie fest, wie Aufgaben auf Serverknoten im Pool verteilt sind.</span><span class="sxs-lookup"><span data-stu-id="62d98-147">Gets or sets how tasks are distributed among compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.UserAccount&gt; UserAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.UserAccount&gt; UserAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.UserAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccounts As IList(Of UserAccount)" />
      <MemberSignature Language="F#" Value="member this.UserAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.UserAccount&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.UserAccounts" />
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
            <span data-ttu-id="62d98-148">Ruft ab oder legt die Liste der Benutzerkonten auf jedem Knoten im Pool erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="62d98-148">Gets or sets the list of user accounts to be created on each node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.VirtualMachineConfiguration VirtualMachineConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.VirtualMachineConfiguration VirtualMachineConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineConfiguration As VirtualMachineConfiguration" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineConfiguration : Microsoft.Azure.Batch.VirtualMachineConfiguration with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" />
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
            <span data-ttu-id="62d98-149">Ruft ab oder legt die <see cref="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" /> des Pools.</span><span class="sxs-lookup"><span data-stu-id="62d98-149">Gets or sets the <see cref="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" /> of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="62d98-150">Diese Eigenschaft ist mit sich gegenseitig ausschließende <see cref="P:Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" />.</span><span class="sxs-lookup"><span data-stu-id="62d98-150">This property is mutually exclusive with <see cref="P:Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineSize">
      <MemberSignature Language="C#" Value="public string VirtualMachineSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineSize As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineSize : string with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.VirtualMachineSize" />
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
            <span data-ttu-id="62d98-151">Ruft ab oder legt die Größe der virtuellen Computer im Pool.</span><span class="sxs-lookup"><span data-stu-id="62d98-151">Gets or sets the size of the virtual machines in the pool.</span></span>  <span data-ttu-id="62d98-152">Alle virtuellen Computer in einem Pool haben die gleiche Größe.</span><span class="sxs-lookup"><span data-stu-id="62d98-152">All virtual machines in a pool are the same size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="62d98-153">Informationen zu den verfügbaren Größen von virtuellen Maschinen für Cloud-Dienste-Pools (Pools mit erstellt eine <see cref="P:Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" />), finden Sie unter https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/.</span><span class="sxs-lookup"><span data-stu-id="62d98-153">For information about available sizes of virtual machines for Cloud Services pools (pools created with a <see cref="P:Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" />), see https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/.</span></span> <span data-ttu-id="62d98-154">Batch unterstützt alle Cloud-Dienste VM-Größen sind ExtraSmall mit Ausnahme von.</span><span class="sxs-lookup"><span data-stu-id="62d98-154">Batch supports all Cloud Services VM sizes except ExtraSmall.</span></span></para>
          <para><span data-ttu-id="62d98-155">Informationen zu den verfügbaren VM-Größen für Anwendungspools, die mithilfe von Images von virtuellen Maschinen Marketplace (mit erstellten Ressourcenpools einer <see cref="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" />) finden Sie unter https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ oder https:// Azure.Microsoft.com/Documentation/articles/Virtual-Machines-Windows-sizes/.</span><span class="sxs-lookup"><span data-stu-id="62d98-155">For information about available VM sizes for pools using images from the Virtual Machines Marketplace (pools created with a <see cref="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" />) see https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ or https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/.</span></span> <span data-ttu-id="62d98-156">Batch unterstützt alle Azure-VM-Größen außer STANDARD_A0 und die mit Premium-Speicher (z. B. STANDARD_GS STANDARD_DS und STANDARD_DSV2-Serie).</span><span class="sxs-lookup"><span data-stu-id="62d98-156">Batch supports all Azure VM sizes except STANDARD_A0 and those with premium storage (for example STANDARD_GS, STANDARD_DS, and STANDARD_DSV2 series).</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>