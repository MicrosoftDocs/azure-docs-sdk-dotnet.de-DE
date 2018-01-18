<Type Name="VirtualMachineConfiguration" FullName="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration">
  <TypeSignature Language="C#" Value="public class VirtualMachineConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineConfiguration" />
  <TypeSignature Language="F#" Value="type VirtualMachineConfiguration = class" />
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
            <span data-ttu-id="a60e1-101">Die Konfiguration für die Serverknoten in einem Pool basierend auf den virtuellen Computern in Azure-Infrastruktur.</span><span class="sxs-lookup"><span data-stu-id="a60e1-101">The configuration for compute nodes in a pool based on the Azure Virtual Machines infrastructure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.#ctor" />
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
            <span data-ttu-id="a60e1-102">Initialisiert eine neue Instanz der VirtualMachineConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a60e1-102">Initializes a new instance of the VirtualMachineConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineConfiguration (Microsoft.Azure.Batch.Protocol.Models.ImageReference imageReference, string nodeAgentSKUId, Microsoft.Azure.Batch.Protocol.Models.OSDisk osDisk = null, Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration windowsConfiguration = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; dataDisks = null, string licenseType = null, Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration containerConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.Models.ImageReference imageReference, string nodeAgentSKUId, class Microsoft.Azure.Batch.Protocol.Models.OSDisk osDisk, class Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration windowsConfiguration, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; dataDisks, string licenseType, class Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration containerConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.#ctor(Microsoft.Azure.Batch.Protocol.Models.ImageReference,System.String,Microsoft.Azure.Batch.Protocol.Models.OSDisk,Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.DataDisk},System.String,Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration : Microsoft.Azure.Batch.Protocol.Models.ImageReference * string * Microsoft.Azure.Batch.Protocol.Models.OSDisk * Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; * string * Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration -&gt; Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration" Usage="new Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration (imageReference, nodeAgentSKUId, osDisk, windowsConfiguration, dataDisks, licenseType, containerConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Batch.Protocol.Models.ImageReference" />
        <Parameter Name="nodeAgentSKUId" Type="System.String" />
        <Parameter Name="osDisk" Type="Microsoft.Azure.Batch.Protocol.Models.OSDisk" />
        <Parameter Name="windowsConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration" />
        <Parameter Name="dataDisks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt;" />
        <Parameter Name="licenseType" Type="System.String" />
        <Parameter Name="containerConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration" />
      </Parameters>
      <Docs>
        <param name="imageReference"><span data-ttu-id="a60e1-103">Ein Verweis auf den Azure-virtuelle Computer-Marketplace-Image oder die benutzerdefinierte VM-Image zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="a60e1-103">A reference to the Azure Virtual Machines Marketplace image or the custom Virtual Machine image to use.</span></span></param>
        <param name="nodeAgentSKUId"><span data-ttu-id="a60e1-104">Die SKU des Batch-Knoten-Agent auf bereitzustellenden Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="a60e1-104">The SKU of the Batch node agent to be provisioned on compute nodes in the pool.</span></span></param>
        <param name="osDisk"><span data-ttu-id="a60e1-105">Einstellungen für den Betriebssystemdatenträger des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="a60e1-105">Settings for the operating system disk of the Virtual Machine.</span></span></param>
        <param name="windowsConfiguration"><span data-ttu-id="a60e1-106">Windows-Betriebssystem-Einstellungen auf dem virtuellen Computer.</span><span class="sxs-lookup"><span data-stu-id="a60e1-106">Windows operating system settings on the virtual machine.</span></span></param>
        <param name="dataDisks"><span data-ttu-id="a60e1-107">Die Konfiguration für Datenträger auf den Comptue-Knoten in den Pool zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a60e1-107">The configuration for data disks attached to the comptue nodes in the pool.</span></span></param>
        <param name="licenseType"><span data-ttu-id="a60e1-108">Der Typ des lokalen-Lizenz, um bei der Bereitstellung von Betriebssystemen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="a60e1-108">The type of on-premises license to be used when deploying the operating system.</span></span></param>
        <param name="containerConfiguration"><span data-ttu-id="a60e1-109">Die Konfiguration des Containers für den Pool.</span><span class="sxs-lookup"><span data-stu-id="a60e1-109">The container configuration for the pool.</span></span></param>
        <summary>
            <span data-ttu-id="a60e1-110">Initialisiert eine neue Instanz der VirtualMachineConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a60e1-110">Initializes a new instance of the VirtualMachineConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration ContainerConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration ContainerConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.ContainerConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerConfiguration As ContainerConfiguration" />
      <MemberSignature Language="F#" Value="member this.ContainerConfiguration : Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.ContainerConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a60e1-111">Ruft ab oder legt die Konfiguration des Containers für den Pool.</span><span class="sxs-lookup"><span data-stu-id="a60e1-111">Gets or sets the container configuration for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a60e1-112">Wenn angegeben, erfolgt die Setup auf jedem Knoten im Pool zu Aufgaben in Containern ausgeführt werden können.</span><span class="sxs-lookup"><span data-stu-id="a60e1-112">If specified, setup is performed on each node in the pool to allow tasks to run in containers.</span></span> <span data-ttu-id="a60e1-113">Alle regulären und Auftrags-Manager Aufgaben für diesen Pool ausgeführt, müssen die ContainerSettings-Eigenschaft angeben, und alle anderen Aufgaben können sie angeben.</span><span class="sxs-lookup"><span data-stu-id="a60e1-113">All regular tasks and job manager tasks run on this pool must specify the containerSettings property, and all other tasks may specify it.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As IList(Of DataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataDisks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a60e1-114">Ruft ab oder legt die Konfiguration für Datenträger auf den Comptue-Knoten in den Pool zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a60e1-114">Gets or sets the configuration for data disks attached to the comptue nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a60e1-115">Diese Eigenschaft muss angegeben werden, wenn die Serverknoten im Pool leere Datenträger verbunden werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a60e1-115">This property must be specified if the compute nodes in the pool need to have empty data disks attached to them.</span></span> <span data-ttu-id="a60e1-116">Dieser Wert kann nicht aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="a60e1-116">This cannot be updated.</span></span> <span data-ttu-id="a60e1-117">Jeder Knoten Ruft einen eigenen Datenträger (der Datenträger ist nicht auf eine Dateifreigabe) ab.</span><span class="sxs-lookup"><span data-stu-id="a60e1-117">Each node gets its own disk (the disk is not a file share).</span></span> <span data-ttu-id="a60e1-118">Vorhandene Datenträger können nicht angefügt werden, jede angefügte Datenträger ist leer.</span><span class="sxs-lookup"><span data-stu-id="a60e1-118">Existing disks cannot be attached, each attached disk is empty.</span></span> <span data-ttu-id="a60e1-119">Wenn der Knoten aus dem Pool entfernt wird, wird der Datenträger und alle zugeordneten Daten ebenfalls gelöscht.</span><span class="sxs-lookup"><span data-stu-id="a60e1-119">When the node is removed from the pool, the disk and all data associated with it is also deleted.</span></span> <span data-ttu-id="a60e1-120">Der Datenträger nicht nach dem Anfügen formatiert wird, müssen Sie vor der Verwendung - Weitere Informationen finden Sie unter https://docs.microsoft.com/en-us/azure/virtual-machines/linux/classic/attach-disk#initialize-a-new-data-disk-in-linux und https:// formatiert werden docs.Microsoft.com/en-US/Azure/Virtual-Machines/Windows/Attach-Disk-PS#Add-an-Empty-Data-Disk-to-a-Virtual-Machine.</span><span class="sxs-lookup"><span data-stu-id="a60e1-120">The disk is not formatted after being attached, it must be formatted before use - for more information see https://docs.microsoft.com/en-us/azure/virtual-machines/linux/classic/attach-disk#initialize-a-new-data-disk-in-linux and https://docs.microsoft.com/en-us/azure/virtual-machines/windows/attach-disk-ps#add-an-empty-data-disk-to-a-virtual-machine.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ImageReference ImageReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ImageReference ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageReference As ImageReference" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Batch.Protocol.Models.ImageReference with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.ImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="imageReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ImageReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a60e1-121">Ruft ab oder legt einen Verweis auf das Azure-virtuelle Computer-Marketplace-Image oder benutzerdefinierten virtuellen Computers zu verwendenden Images.</span><span class="sxs-lookup"><span data-stu-id="a60e1-121">Gets or sets a reference to the Azure Virtual Machines Marketplace image or the custom Virtual Machine image to use.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a60e1-122">Diese Eigenschaft und der Betriebssystemdatenträger schließen sich gegenseitig aus, und eine der Eigenschaften muss angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="a60e1-122">This property and osDisk are mutually exclusive and one of the properties must be specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="licenseType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="a60e1-123">Ruft ab, oder legt ihn fest lokalen Lizenztyp verwendet werden, wenn Sie das Betriebssystem bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="a60e1-123">Gets or sets the type of on-premises license to be used when deploying the operating system.</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>
             <span data-ttu-id="a60e1-124">Dies gilt nur für Bilder, die Windows-Betriebssystem enthalten und sollte nur verwendet werden, wenn Sie gültige lokale Lizenzen für die Knoten enthalten. diese bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="a60e1-124">This only applies to images that contain the Windows operating system, and should only be used when you hold valid on-premises licenses for the nodes which will be deployed.</span></span> <span data-ttu-id="a60e1-125">Wenn nicht angegeben ist, werden keine lokalen Lizenzierung Preisnachlass angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="a60e1-125">If omitted, no on-premises licensing discount is applied.</span></span> <span data-ttu-id="a60e1-126">Gültige Werte:</span><span class="sxs-lookup"><span data-stu-id="a60e1-126">Values are:</span></span>
             
             <span data-ttu-id="a60e1-127">Windows_Server - ist der lokale für Windows Server.</span><span class="sxs-lookup"><span data-stu-id="a60e1-127">Windows_Server - The on-premises license is for Windows Server.</span></span>
             <span data-ttu-id="a60e1-128">"Windows_client" - ist der lokale für Windows-Clients.</span><span class="sxs-lookup"><span data-stu-id="a60e1-128">Windows_Client - The on-premises license is for Windows Client.</span></span>
            
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeAgentSKUId">
      <MemberSignature Language="C#" Value="public string NodeAgentSKUId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeAgentSKUId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.NodeAgentSKUId" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeAgentSKUId As String" />
      <MemberSignature Language="F#" Value="member this.NodeAgentSKUId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.NodeAgentSKUId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeAgentSKUId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a60e1-129">Ruft ab oder legt die SKU des Batch-Knoten-Agent auf den Serverknoten im Pool bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="a60e1-129">Gets or sets the SKU of the Batch node agent to be provisioned on compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a60e1-130">Der Batch-Knoten-Agent ist ein Programm, das auf jedem Knoten im Pool ausgeführt wird, und stellt eine Schnittstelle Befehl Steuerelement zwischen den Knoten und der Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="a60e1-130">The Batch node agent is a program that runs on each node in the pool, and provides the command-and-control interface between the node and the Batch service.</span></span> <span data-ttu-id="a60e1-131">Es gibt verschiedene Implementierungen des Knoten-Agents (SKUs) für verschiedene Betriebssysteme.</span><span class="sxs-lookup"><span data-stu-id="a60e1-131">There are different implementations of the node agent, known as SKUs, for different operating systems.</span></span> <span data-ttu-id="a60e1-132">Sie müssen einen Knoten-Agent-SKU angeben, die den ausgewählten Bildverweis entspricht.</span><span class="sxs-lookup"><span data-stu-id="a60e1-132">You must specify a node agent SKU which matches the selected image reference.</span></span> <span data-ttu-id="a60e1-133">Um die Liste der unterstützten Knoten Agent SKUs sowie eine Liste von überprüften bildreferenzen zu erhalten, finden Sie unter dem Vorgang "Liste unterstützter Knoten Agent SKUs".</span><span class="sxs-lookup"><span data-stu-id="a60e1-133">To get the list of supported node agent SKUs along with their list of verified image references, see the 'List supported node agent SKUs' operation.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OsDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.OSDisk OsDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.OSDisk OsDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.OsDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property OsDisk As OSDisk" />
      <MemberSignature Language="F#" Value="member this.OsDisk : Microsoft.Azure.Batch.Protocol.Models.OSDisk with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.OsDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.OSDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a60e1-134">Ruft ab oder legt die Einstellungen für den Betriebssystemdatenträger des virtuellen Computers fest.</span><span class="sxs-lookup"><span data-stu-id="a60e1-134">Gets or sets settings for the operating system disk of the Virtual Machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a60e1-135">Diese Eigenschaft kann nur angegeben werden, wenn das Batch-Konto, wobei seine PoolAllocationMode-Eigenschaft auf "UserSubscription" festgelegt erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="a60e1-135">This property can be specified only if the Batch account was created with its poolAllocationMode property set to 'UserSubscription'.</span></span> <span data-ttu-id="a60e1-136">Diese Eigenschaft und die ImageReference schließen sich gegenseitig aus, und eine der Eigenschaften muss angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="a60e1-136">This property and imageReference are mutually exclusive and one of the properties must be specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineConfiguration.Validate " />
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
            <span data-ttu-id="a60e1-137">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="a60e1-137">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a60e1-138">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="a60e1-138">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WindowsConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration WindowsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration WindowsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsConfiguration As WindowsConfiguration" />
      <MemberSignature Language="F#" Value="member this.WindowsConfiguration : Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="windowsConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a60e1-139">Ruft ab oder legt Einstellungen des Windows-Betriebssystems auf dem virtuellen Computer.</span><span class="sxs-lookup"><span data-stu-id="a60e1-139">Gets or sets windows operating system settings on the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a60e1-140">Diese Eigenschaft muss angegeben werden, wenn die Eigenschaft ImageReference oder Betriebssystemdatenträger ein Linux-Betriebssystem-Image angibt.</span><span class="sxs-lookup"><span data-stu-id="a60e1-140">This property must not be specified if the imageReference or osDisk property specifies a Linux OS image.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>