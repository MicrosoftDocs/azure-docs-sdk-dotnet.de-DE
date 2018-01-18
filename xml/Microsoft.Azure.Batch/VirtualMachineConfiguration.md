<Type Name="VirtualMachineConfiguration" FullName="Microsoft.Azure.Batch.VirtualMachineConfiguration">
  <TypeSignature Language="C#" Value="public class VirtualMachineConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineConfiguration" />
  <TypeSignature Language="F#" Value="type VirtualMachineConfiguration = class&#xA;    interface ITransportObjectProvider&lt;VirtualMachineConfiguration&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="3b5df-101">Die Konfiguration für die Serverknoten in einem Pool basierend auf den virtuellen Computern in Azure-Infrastruktur.</span><span class="sxs-lookup"><span data-stu-id="3b5df-101">The configuration for compute nodes in a pool based on the Azure Virtual Machines infrastructure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineConfiguration (Microsoft.Azure.Batch.ImageReference imageReference, string nodeAgentSkuId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.ImageReference imageReference, string nodeAgentSkuId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.VirtualMachineConfiguration.#ctor(Microsoft.Azure.Batch.ImageReference,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.VirtualMachineConfiguration : Microsoft.Azure.Batch.ImageReference * string -&gt; Microsoft.Azure.Batch.VirtualMachineConfiguration" Usage="new Microsoft.Azure.Batch.VirtualMachineConfiguration (imageReference, nodeAgentSkuId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Batch.ImageReference" />
        <Parameter Name="nodeAgentSkuId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageReference"><span data-ttu-id="3b5df-102">Ein Verweis auf das Marketplace-Image in Azure VMs oder des benutzerdefinierten Images des virtuellen Computers zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="3b5df-102">A reference to the Azure Virtual Machines Marketplace Image or the custom Virtual Machine Image to use.</span></span></param>
        <param name="nodeAgentSkuId"><span data-ttu-id="3b5df-103">Der SKU der Batch Knoten-Agent auf den Computeknoten bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="3b5df-103">The SKU of Batch Node Agent to be provisioned on the compute node.</span></span></param>
        <summary>
            <span data-ttu-id="3b5df-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3b5df-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ContainerConfiguration ContainerConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ContainerConfiguration ContainerConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ContainerConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerConfiguration As ContainerConfiguration" />
      <MemberSignature Language="F#" Value="member this.ContainerConfiguration : Microsoft.Azure.Batch.ContainerConfiguration with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.ContainerConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ContainerConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b5df-105">Ruft ab oder legt die Konfiguration des Containers für den Pool.</span><span class="sxs-lookup"><span data-stu-id="3b5df-105">Gets or sets the container configuration for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3b5df-106">Wenn angegeben, erfolgt die Setup auf jedem Knoten im Pool zu Aufgaben in Containern ausgeführt werden können.</span><span class="sxs-lookup"><span data-stu-id="3b5df-106">If specified, setup is performed on each node in the pool to allow tasks to run in containers.</span></span> <span data-ttu-id="3b5df-107">Alle regulären und Auftrags-Manager Aufgaben für diesen Pool ausführen müssen angeben, <see cref="T:Microsoft.Azure.Batch.TaskContainerSettings" />, und alle anderen Aufgaben können sie angeben.</span><span class="sxs-lookup"><span data-stu-id="3b5df-107">All regular tasks and job manager tasks run on this pool must specify <see cref="T:Microsoft.Azure.Batch.TaskContainerSettings" />, and all other tasks may specify it.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.DataDisk&gt; DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.DataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As IList(Of DataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.DataDisk&gt; with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.DataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b5df-108">Ruft ab oder legt die Konfiguration für Datenträger auf den Comptue-Knoten in den Pool zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3b5df-108">Gets or sets the configuration for data disks attached to the Comptue Nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3b5df-109">Diese Eigenschaft muss angegeben werden, wenn die Serverknoten im Pool leere Datenträger verbunden werden sollen.</span><span class="sxs-lookup"><span data-stu-id="3b5df-109">This property must be specified if the Compute Nodes in the pool need to have empty data disks attached to them.</span></span> <span data-ttu-id="3b5df-110">Dieser Wert kann nicht aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="3b5df-110">This cannot be updated.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ImageReference ImageReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ImageReference ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageReference As ImageReference" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Batch.ImageReference with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.ImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ImageReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b5df-111">Ermittelt oder definiert einen Verweis auf das Marketplace-Image in Azure VMs oder des benutzerdefinierten Images des virtuellen Computers zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="3b5df-111">Gets or sets a reference to the Azure Virtual Machines Marketplace Image or the custom Virtual Machine Image to use.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3b5df-112">Diese Eigenschaft und <see cref="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.OSDisk" /> gegenseitig und eine der Eigenschaften muss angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="3b5df-112">This property and <see cref="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.OSDisk" /> are mutually exclusive and one of the properties must be specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b5df-113">Ruft ab, oder legt ihn fest lokalen Lizenztyp verwendet werden, wenn Sie das Betriebssystem bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="3b5df-113">Gets or sets the type of on-premises license to be used when deploying the operating system.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3b5df-114">Dies gilt nur für Bilder, die Windows-Betriebssystem enthalten und sollte nur verwendet werden, wenn Sie gültige lokale Lizenzen für die Knoten enthalten. diese bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="3b5df-114">This only applies to images that contain the Windows operating system, and should only be used when you hold valid on-premises licenses for the nodes which will be deployed.</span></span> <span data-ttu-id="3b5df-115">Wenn nicht angegeben ist, werden keine lokalen Lizenzierung Preisnachlass angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="3b5df-115">If omitted, no on-premises licensing discount is applied.</span></span> <span data-ttu-id="3b5df-116">Werte sind: "Windows_Server" - die lokalen-Lizenz ist für Windows Server.</span><span class="sxs-lookup"><span data-stu-id="3b5df-116">Values are: 'Windows_Server' - The on-premises license is for Windows Server.</span></span> <span data-ttu-id="3b5df-117">"" Windows_client "-" ist die lokale-Lizenz für Windows-Clients.</span><span class="sxs-lookup"><span data-stu-id="3b5df-117">'Windows_Client' - The on-premises license is for Windows Client.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeAgentSkuId">
      <MemberSignature Language="C#" Value="public string NodeAgentSkuId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeAgentSkuId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.NodeAgentSkuId" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeAgentSkuId As String" />
      <MemberSignature Language="F#" Value="member this.NodeAgentSkuId : string with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.NodeAgentSkuId" />
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
            <span data-ttu-id="3b5df-118">Ruft ab, oder legt ihn fest-SKU von Batch Knoten Agent auf den Computeknoten bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="3b5df-118">Gets or sets the SKU of Batch Node Agent to be provisioned on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3b5df-119">Der Batch-Knoten-Agent ist ein Programm, das auf jedem Knoten im Pool ausgeführt wird, und stellt eine Schnittstelle Befehl Steuerelement zwischen den Knoten und der Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="3b5df-119">The Batch node agent is a program that runs on each node in the pool, and provides the command-and-control interface between the node and the Batch service.</span></span> <span data-ttu-id="3b5df-120">Es gibt verschiedene Implementierungen des Knoten-Agents (SKUs) für verschiedene Betriebssysteme.</span><span class="sxs-lookup"><span data-stu-id="3b5df-120">There are different implementations of the node agent, known as SKUs, for different operating systems.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.OSDisk OSDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.OSDisk OSDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.OSDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property OSDisk As OSDisk" />
      <MemberSignature Language="F#" Value="member this.OSDisk : Microsoft.Azure.Batch.OSDisk with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.OSDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.OSDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b5df-121">Ruft ab oder legt die Einstellungen für den Betriebssystemdatenträger des virtuellen Computers fest.</span><span class="sxs-lookup"><span data-stu-id="3b5df-121">Gets or sets settings for the operating system disk of the Virtual Machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3b5df-122">Diese Eigenschaft kann nur angegeben werden, wenn das Batch-Konto, wobei seine PoolAllocationMode-Eigenschaft auf "UserSubscription" festgelegt erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="3b5df-122">This property can be specified only if the Batch account was created with its poolAllocationMode property set to 'UserSubscription'.</span></span> <span data-ttu-id="3b5df-123">Diese Eigenschaft und <see cref="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ImageReference" /> gegenseitig und eine der Eigenschaften muss angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="3b5df-123">This property and <see cref="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ImageReference" /> are mutually exclusive and one of the properties must be specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.WindowsConfiguration WindowsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.WindowsConfiguration WindowsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsConfiguration As WindowsConfiguration" />
      <MemberSignature Language="F#" Value="member this.WindowsConfiguration : Microsoft.Azure.Batch.WindowsConfiguration with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.WindowsConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b5df-124">Ruft ab oder legt Einstellungen des Windows-Betriebssystems auf dem virtuellen Computer.</span><span class="sxs-lookup"><span data-stu-id="3b5df-124">Gets or sets windows operating system settings on the virtual machine.</span></span> <span data-ttu-id="3b5df-125">Diese Eigenschaft muss angegeben werden, wenn die Eigenschaft ImageReference ein Linux-Betriebssystem-Image angibt.</span><span class="sxs-lookup"><span data-stu-id="3b5df-125">This property must not be specified if the ImageReference property specifies a Linux OS image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>