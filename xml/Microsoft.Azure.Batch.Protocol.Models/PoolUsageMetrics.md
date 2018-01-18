<Type Name="PoolUsageMetrics" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics">
  <TypeSignature Language="C#" Value="public class PoolUsageMetrics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolUsageMetrics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolUsageMetrics" />
  <TypeSignature Language="F#" Value="type PoolUsageMetrics = class" />
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
            <span data-ttu-id="1abbb-101">Nutzungsmetriken für einen Pool in ein aggregationsintervall.</span><span class="sxs-lookup"><span data-stu-id="1abbb-101">Usage metrics for a pool across an aggregation interval.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolUsageMetrics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.#ctor" />
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
            <span data-ttu-id="1abbb-102">Initialisiert eine neue Instanz der PoolUsageMetrics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1abbb-102">Initializes a new instance of the PoolUsageMetrics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolUsageMetrics (string poolId, DateTime startTime, DateTime endTime, string vmSize, double totalCoreHours, double dataIngressGiB, double dataEgressGiB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string poolId, valuetype System.DateTime startTime, valuetype System.DateTime endTime, string vmSize, float64 totalCoreHours, float64 dataIngressGiB, float64 dataEgressGiB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.#ctor(System.String,System.DateTime,System.DateTime,System.String,System.Double,System.Double,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (poolId As String, startTime As DateTime, endTime As DateTime, vmSize As String, totalCoreHours As Double, dataIngressGiB As Double, dataEgressGiB As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics : string * DateTime * DateTime * string * double * double * double -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics (poolId, startTime, endTime, vmSize, totalCoreHours, dataIngressGiB, dataEgressGiB)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="endTime" Type="System.DateTime" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="totalCoreHours" Type="System.Double" />
        <Parameter Name="dataIngressGiB" Type="System.Double" />
        <Parameter Name="dataEgressGiB" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="1abbb-103">Die ID des Pools, dessen Metriken in diesem Eintrag aggregiert werden.</span><span class="sxs-lookup"><span data-stu-id="1abbb-103">The ID of the pool whose metrics are aggregated in this entry.</span></span></param>
        <param name="startTime"><span data-ttu-id="1abbb-104">Die Startzeit des aggregationsintervalls durch diesen Eintrag abgedeckt werden.</span><span class="sxs-lookup"><span data-stu-id="1abbb-104">The start time of the aggregation interval covered by this entry.</span></span></param>
        <param name="endTime"><span data-ttu-id="1abbb-105">Die Endzeit des aggregationsintervalls durch diesen Eintrag abgedeckt werden.</span><span class="sxs-lookup"><span data-stu-id="1abbb-105">The end time of the aggregation interval covered by this entry.</span></span></param>
        <param name="vmSize"><span data-ttu-id="1abbb-106">Die Größe der virtuellen Maschinen in den Pool.</span><span class="sxs-lookup"><span data-stu-id="1abbb-106">The size of virtual machines in the pool.</span></span> <span data-ttu-id="1abbb-107">Alle virtuellen Computer in einem Pool haben die gleiche Größe.</span><span class="sxs-lookup"><span data-stu-id="1abbb-107">All VMs in a pool are the same size.</span></span></param>
        <param name="totalCoreHours"><span data-ttu-id="1abbb-108">Die insgesamt kernstunden im Pool während dieses aggregationsintervalls verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="1abbb-108">The total core hours used in the pool during this aggregation interval.</span></span></param>
        <param name="dataIngressGiB"><span data-ttu-id="1abbb-109">Die übergreifende des Rechenzentrums Netzwerk eingehend an den Pool während dieses Intervalls schlägt in gib betragen.</span><span class="sxs-lookup"><span data-stu-id="1abbb-109">The cross data center network ingress to the pool during this interval, in GiB.</span></span></param>
        <param name="dataEgressGiB"><span data-ttu-id="1abbb-110">Die übergreifende des Rechenzentrums Netzwerk Ausgang aus dem Pool während dieses Intervalls schlägt in gib betragen.</span><span class="sxs-lookup"><span data-stu-id="1abbb-110">The cross data center network egress from the pool during this interval, in GiB.</span></span></param>
        <summary>
            <span data-ttu-id="1abbb-111">Initialisiert eine neue Instanz der PoolUsageMetrics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1abbb-111">Initializes a new instance of the PoolUsageMetrics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataEgressGiB">
      <MemberSignature Language="C#" Value="public double DataEgressGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DataEgressGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.DataEgressGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property DataEgressGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DataEgressGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.DataEgressGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataEgressGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1abbb-112">Abrufen oder Festlegen der Cross Datenausgang Center Netzwerk aus dem Pool während dieses Intervalls schlägt in gib betragen.</span><span class="sxs-lookup"><span data-stu-id="1abbb-112">Gets or sets the cross data center network egress from the pool during this interval, in GiB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataIngressGiB">
      <MemberSignature Language="C#" Value="public double DataIngressGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DataIngressGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.DataIngressGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property DataIngressGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DataIngressGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.DataIngressGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataIngressGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1abbb-113">Ermittelt oder definiert die Cross Dateneingang Center Netzwerk an den Pool während dieses Intervalls schlägt in gib betragen.</span><span class="sxs-lookup"><span data-stu-id="1abbb-113">Gets or sets the cross data center network ingress to the pool during this interval, in GiB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public DateTime EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.EndTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1abbb-114">Ruft ab oder legt die Endzeit des aggregationsintervalls durch diesen Eintrag abgedeckt werden.</span><span class="sxs-lookup"><span data-stu-id="1abbb-114">Gets or sets the end time of the aggregation interval covered by this entry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.PoolId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1abbb-115">Ruft ab oder legt die ID des Pools, dessen Metriken aggregiert werden, in diesem Eintrag.</span><span class="sxs-lookup"><span data-stu-id="1abbb-115">Gets or sets the ID of the pool whose metrics are aggregated in this entry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1abbb-116">Ruft ab oder legt die Startzeit des aggregationsintervalls durch diesen Eintrag abgedeckt werden.</span><span class="sxs-lookup"><span data-stu-id="1abbb-116">Gets or sets the start time of the aggregation interval covered by this entry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCoreHours">
      <MemberSignature Language="C#" Value="public double TotalCoreHours { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 TotalCoreHours" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.TotalCoreHours" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalCoreHours As Double" />
      <MemberSignature Language="F#" Value="member this.TotalCoreHours : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.TotalCoreHours" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalCoreHours")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1abbb-117">Abrufen oder Festlegen der gesamten kernstunden im Pool während dieses aggregationsintervalls verwendet.</span><span class="sxs-lookup"><span data-stu-id="1abbb-117">Gets or sets the total core hours used in the pool during this aggregation interval.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolUsageMetrics.Validate " />
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
            <span data-ttu-id="1abbb-118">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="1abbb-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1abbb-119">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="1abbb-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1abbb-120">Ruft ab oder legt die Größe der virtuellen Computer im Pool.</span><span class="sxs-lookup"><span data-stu-id="1abbb-120">Gets or sets the size of virtual machines in the pool.</span></span> <span data-ttu-id="1abbb-121">Alle virtuellen Computer in einem Pool haben die gleiche Größe.</span><span class="sxs-lookup"><span data-stu-id="1abbb-121">All VMs in a pool are the same size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1abbb-122">Informationen zu den verfügbaren Größen von virtuellen Maschinen für Cloud-Dienste-Pools (Pools mit CloudServiceConfiguration erstellt) finden Sie unter Größen für Cloud-Dienste (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/).</span><span class="sxs-lookup"><span data-stu-id="1abbb-122">For information about available sizes of virtual machines for Cloud Services pools (pools created with cloudServiceConfiguration), see Sizes for Cloud Services (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/).</span></span>
            <span data-ttu-id="1abbb-123">Batch unterstützt alle Cloud-Dienste-VM-Größen außer sind ExtraSmall, STANDARD_A1_V2 und STANDARD_A2_V2.</span><span class="sxs-lookup"><span data-stu-id="1abbb-123">Batch supports all Cloud Services VM sizes except ExtraSmall, STANDARD_A1_V2 and STANDARD_A2_V2.</span></span> <span data-ttu-id="1abbb-124">Informationen zu den verfügbaren VM-Größen für Anwendungspools, die mithilfe von Images aus dem virtuellen Computer Marketplace (Pools mit VirtualMachineConfiguration erstellt) finden Sie unter Größen für virtuelle Maschinen (Linux) (https://azure.microsoft.com/documentation/articles/ virtuelle Maschinen-Linux-Größen /) oder Größen für virtuelle Computer (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/).</span><span class="sxs-lookup"><span data-stu-id="1abbb-124">For information about available VM sizes for pools using images from the Virtual Machines Marketplace (pools created with virtualMachineConfiguration) see Sizes for Virtual Machines (Linux) (https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/) or Sizes for Virtual Machines (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/).</span></span>
            <span data-ttu-id="1abbb-125">Batch unterstützt alle Azure-VM-Größen außer STANDARD_A0 und die mit Premium-Speicher (STANDARD_GS STANDARD_DS und STANDARD_DSV2-Serie).</span><span class="sxs-lookup"><span data-stu-id="1abbb-125">Batch supports all Azure VM sizes except STANDARD_A0 and those with premium storage (STANDARD_GS, STANDARD_DS, and STANDARD_DSV2 series).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>