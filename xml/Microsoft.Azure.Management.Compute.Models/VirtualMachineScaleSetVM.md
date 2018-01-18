<Type Name="VirtualMachineScaleSetVM" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetVM : Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetVM extends Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetVM&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetVM = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="577ef-101">Beschreibt eine virtuelle Maschine Scale Set virtuelle Maschine an.</span><span class="sxs-lookup"><span data-stu-id="577ef-101">Describes a virtual machine scale set virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVM ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="577ef-102">Initialisiert eine neue Instanz der VirtualMachineScaleSetVM-Klasse.</span><span class="sxs-lookup"><span data-stu-id="577ef-102">Initializes a new instance of the VirtualMachineScaleSetVM class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVM (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string instanceId = null, Microsoft.Azure.Management.Compute.Models.Sku sku = null, Nullable&lt;bool&gt; latestModelApplied = null, string vmId = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView instanceView = null, Microsoft.Azure.Management.Compute.Models.HardwareProfile hardwareProfile = null, Microsoft.Azure.Management.Compute.Models.StorageProfile storageProfile = null, Microsoft.Azure.Management.Compute.Models.OSProfile osProfile = null, Microsoft.Azure.Management.Compute.Models.NetworkProfile networkProfile = null, Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile diagnosticsProfile = null, Microsoft.Azure.Management.Compute.Models.SubResource availabilitySet = null, string provisioningState = null, string licenseType = null, Microsoft.Azure.Management.Compute.Models.Plan plan = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; resources = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string instanceId, class Microsoft.Azure.Management.Compute.Models.Sku sku, valuetype System.Nullable`1&lt;bool&gt; latestModelApplied, string vmId, class Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView instanceView, class Microsoft.Azure.Management.Compute.Models.HardwareProfile hardwareProfile, class Microsoft.Azure.Management.Compute.Models.StorageProfile storageProfile, class Microsoft.Azure.Management.Compute.Models.OSProfile osProfile, class Microsoft.Azure.Management.Compute.Models.NetworkProfile networkProfile, class Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile diagnosticsProfile, class Microsoft.Azure.Management.Compute.Models.SubResource availabilitySet, string provisioningState, string licenseType, class Microsoft.Azure.Management.Compute.Models.Plan plan, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; resources) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.Compute.Models.Sku,System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView,Microsoft.Azure.Management.Compute.Models.HardwareProfile,Microsoft.Azure.Management.Compute.Models.StorageProfile,Microsoft.Azure.Management.Compute.Models.OSProfile,Microsoft.Azure.Management.Compute.Models.NetworkProfile,Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile,Microsoft.Azure.Management.Compute.Models.SubResource,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Plan,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.Compute.Models.Sku * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView * Microsoft.Azure.Management.Compute.Models.HardwareProfile * Microsoft.Azure.Management.Compute.Models.StorageProfile * Microsoft.Azure.Management.Compute.Models.OSProfile * Microsoft.Azure.Management.Compute.Models.NetworkProfile * Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile * Microsoft.Azure.Management.Compute.Models.SubResource * string * string * Microsoft.Azure.Management.Compute.Models.Plan * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM (location, id, name, type, tags, instanceId, sku, latestModelApplied, vmId, instanceView, hardwareProfile, storageProfile, osProfile, networkProfile, diagnosticsProfile, availabilitySet, provisioningState, licenseType, plan, resources)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Compute.Models.Sku" />
        <Parameter Name="latestModelApplied" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="vmId" Type="System.String" />
        <Parameter Name="instanceView" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView" />
        <Parameter Name="hardwareProfile" Type="Microsoft.Azure.Management.Compute.Models.HardwareProfile" />
        <Parameter Name="storageProfile" Type="Microsoft.Azure.Management.Compute.Models.StorageProfile" />
        <Parameter Name="osProfile" Type="Microsoft.Azure.Management.Compute.Models.OSProfile" />
        <Parameter Name="networkProfile" Type="Microsoft.Azure.Management.Compute.Models.NetworkProfile" />
        <Parameter Name="diagnosticsProfile" Type="Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile" />
        <Parameter Name="availabilitySet" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="licenseType" Type="System.String" />
        <Parameter Name="plan" Type="Microsoft.Azure.Management.Compute.Models.Plan" />
        <Parameter Name="resources" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="577ef-103">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="577ef-103">Resource location</span></span></param>
        <param name="id"><span data-ttu-id="577ef-104">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="577ef-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="577ef-105">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="577ef-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="577ef-106">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="577ef-106">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="577ef-107">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="577ef-107">Resource tags</span></span></param>
        <param name="instanceId"><span data-ttu-id="577ef-108">Die VM-Instanz-ID.</span><span class="sxs-lookup"><span data-stu-id="577ef-108">The virtual machine instance ID.</span></span></param>
        <param name="sku"><span data-ttu-id="577ef-109">Die virtuelle Maschine SKU.</span><span class="sxs-lookup"><span data-stu-id="577ef-109">The virtual machine SKU.</span></span></param>
        <param name="latestModelApplied"><span data-ttu-id="577ef-110">Gibt an, ob das aktuelle Modell mit dem virtuellen Computer angewendet wurde.</span><span class="sxs-lookup"><span data-stu-id="577ef-110">Specifies whether the latest model has been applied to the virtual machine.</span></span></param>
        <param name="vmId"><span data-ttu-id="577ef-111">Azure VM eindeutige ID.</span><span class="sxs-lookup"><span data-stu-id="577ef-111">Azure VM unique ID.</span></span></param>
        <param name="instanceView"><span data-ttu-id="577ef-112">Die virtuelle Maschine Instanzansicht.</span><span class="sxs-lookup"><span data-stu-id="577ef-112">The virtual machine instance view.</span></span></param>
        <param name="hardwareProfile"><span data-ttu-id="577ef-113">Gibt die hardwareeinstellungen für die virtuelle Maschine an.</span><span class="sxs-lookup"><span data-stu-id="577ef-113">Specifies the hardware settings for the virtual machine.</span></span></param>
        <param name="storageProfile"><span data-ttu-id="577ef-114">Gibt die speichereinstellungen für den Datenträger des virtuellen Computers an.</span><span class="sxs-lookup"><span data-stu-id="577ef-114">Specifies the storage settings for the virtual machine disks.</span></span></param>
        <param name="osProfile"><span data-ttu-id="577ef-115">Gibt die betriebssystemeinstellungen für den virtuellen Computer an.</span><span class="sxs-lookup"><span data-stu-id="577ef-115">Specifies the operating system settings for the virtual machine.</span></span></param>
        <param name="networkProfile"><span data-ttu-id="577ef-116">Gibt die Netzwerkschnittstellen des virtuellen Computers an.</span><span class="sxs-lookup"><span data-stu-id="577ef-116">Specifies the network interfaces of the virtual machine.</span></span></param>
        <param name="diagnosticsProfile"><span data-ttu-id="577ef-117">Gibt den Status der Boot-diagnoseeinstellungen.</span><span class="sxs-lookup"><span data-stu-id="577ef-117">Specifies the boot diagnostic settings state.</span></span> <span data-ttu-id="577ef-118">&lt;Brasilien&gt;&lt;Br&gt;-api-Mindestversion: 2015-06-15.</span><span class="sxs-lookup"><span data-stu-id="577ef-118">&lt;br&gt;&lt;br&gt;Minimum api-version: 2015-06-15.</span></span></param>
        <param name="availabilitySet"><span data-ttu-id="577ef-119">Gibt Informationen über die verfügbarkeitsgruppe, der der virtuellen Maschine zugewiesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="577ef-119">Specifies information about the availability set that the virtual machine should be assigned to.</span></span>
            <span data-ttu-id="577ef-120">Virtuelle Computer in derselben verfügbarkeitsgruppe angegeben werden auf verschiedene Knoten Maximierung der Verfügbarkeit zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="577ef-120">Virtual machines specified in the same availability set are allocated to different nodes to maximize availability.</span></span> <span data-ttu-id="577ef-121">Weitere Informationen zu Verfügbarkeitsgruppen finden Sie unter [Verwalten der Verfügbarkeit von virtuellen Computern](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-manage-availability?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span><span class="sxs-lookup"><span data-stu-id="577ef-121">For more information about availability sets, see [Manage the availability of virtual machines](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-manage-availability?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span></span>
            <span data-ttu-id="577ef-122">&lt;Brasilien&gt;&lt;Br&gt; finden Sie weitere Informationen zu Azure geplante Wartung von Integrationsdiensten, [geplante Wartung für virtuelle Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-planned-maintenance?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;Br&gt;&lt;Brasilien &gt; Derzeit ein virtuellen Computer nur verfügbarkeitsgruppe, die zum Zeitpunkt der Erstellung hinzugefügt werden kann.</span><span class="sxs-lookup"><span data-stu-id="577ef-122">&lt;br&gt;&lt;br&gt; For more information on Azure planned maintainance, see [Planned maintenance for virtual machines in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-planned-maintenance?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;br&gt; Currently, a VM can only be added to availability set at creation time.</span></span> <span data-ttu-id="577ef-123">Eine vorhandene virtuelle Maschine kann nicht zu einer verfügbarkeitsgruppe hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="577ef-123">An existing VM cannot be added to an availability set.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="577ef-124">Der Bereitstellungsstatus, die nur in der Antwort angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="577ef-124">The provisioning state, which only appears in the response.</span></span></param>
        <param name="licenseType"><span data-ttu-id="577ef-125">Gibt an, dass das Image oder Datenträger, der verwendet wird lizenzierte lokalen war.</span><span class="sxs-lookup"><span data-stu-id="577ef-125">Specifies that the image or disk that is being used was licensed on-premises.</span></span> <span data-ttu-id="577ef-126">Dieses Element wird nur für Bilder verwendet, die das Betriebssystem Windows Server enthalten.</span><span class="sxs-lookup"><span data-stu-id="577ef-126">This element is only used for images that contain the Windows Server operating system.</span></span>
            <span data-ttu-id="577ef-127">&lt;Brasilien&gt;&lt;Br&gt; folgende Werte sind möglich: &lt;Br&gt;&lt;Br&gt; "windows_client" &lt;Br&gt;&lt;Br&gt; Windows_Server &lt;Br&gt;&lt;Br&gt; Wenn dieses Element in einer Anforderung für ein Update enthalten ist, muss der Wert den ursprünglichen Wert übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="577ef-127">&lt;br&gt;&lt;br&gt; Possible values are: &lt;br&gt;&lt;br&gt; Windows_Client &lt;br&gt;&lt;br&gt; Windows_Server &lt;br&gt;&lt;br&gt; If this element is included in a request for an update, the value must match the initial value.</span></span> <span data-ttu-id="577ef-128">Dieser Wert kann nicht aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="577ef-128">This value cannot be updated.</span></span> <span data-ttu-id="577ef-129">&lt;Brasilien&gt;&lt;Br&gt; Weitere Informationen finden Sie unter [Azure Hybrid verwenden Vorteil für Windows Server](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;Br&gt;&lt;Br&gt; Minimum API-Version: 2015-06-15</span><span class="sxs-lookup"><span data-stu-id="577ef-129">&lt;br&gt;&lt;br&gt; For more information, see [Azure Hybrid Use Benefit for Windows Server](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;br&gt; Minimum api-version: 2015-06-15</span></span></param>
        <param name="plan"><span data-ttu-id="577ef-130">Gibt Informationen zu den Marketplace-Image zum Erstellen des virtuellen Computers verwendet.</span><span class="sxs-lookup"><span data-stu-id="577ef-130">Specifies information about the marketplace image used to create the virtual machine.</span></span> <span data-ttu-id="577ef-131">Dieses Element wird nur für Marketplace-Images verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="577ef-131">This element is only used for marketplace images.</span></span> <span data-ttu-id="577ef-132">Bevor Sie einem Marketplace-Image aus einer API verwenden können, müssen Sie das Bild zur programmgesteuerten Verwendung aktivieren.</span><span class="sxs-lookup"><span data-stu-id="577ef-132">Before you can use a marketplace image from an API, you must enable the image for programmatic use.</span></span>  <span data-ttu-id="577ef-133">Suchen Sie im Azure-Portal Marketplace-Image, das Sie verwenden möchten und klicken Sie dann auf **bereitzustellende programmgesteuert, erste Schritte -&gt;**.</span><span class="sxs-lookup"><span data-stu-id="577ef-133">In the Azure portal, find the marketplace image that you want to use and then click **Want to deploy programmatically, Get Started -&gt;**.</span></span>
            <span data-ttu-id="577ef-134">Geben Sie alle erforderlichen Informationen ein, und klicken Sie dann auf **speichern**.</span><span class="sxs-lookup"><span data-stu-id="577ef-134">Enter any required information and then click **Save**.</span></span></param>
        <param name="resources"><span data-ttu-id="577ef-135">Die virtuelle Maschine untergeordneten Erweiterung Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="577ef-135">The virtual machine child extension resources.</span></span></param>
        <summary>
            <span data-ttu-id="577ef-136">Initialisiert eine neue Instanz der VirtualMachineScaleSetVM-Klasse.</span><span class="sxs-lookup"><span data-stu-id="577ef-136">Initializes a new instance of the VirtualMachineScaleSetVM class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilitySet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource AvailabilitySet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource AvailabilitySet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.AvailabilitySet" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailabilitySet As SubResource" />
      <MemberSignature Language="F#" Value="member this.AvailabilitySet : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.AvailabilitySet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availabilitySet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="577ef-137">Ruft ab oder legt gibt Informationen über die verfügbarkeitsgruppe, der der virtuellen Maschine zugewiesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="577ef-137">Gets or sets specifies information about the availability set that the virtual machine should be assigned to.</span></span> <span data-ttu-id="577ef-138">Virtuelle Computer in derselben verfügbarkeitsgruppe angegeben werden auf verschiedene Knoten Maximierung der Verfügbarkeit zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="577ef-138">Virtual machines specified in the same availability set are allocated to different nodes to maximize availability.</span></span> <span data-ttu-id="577ef-139">Weitere Informationen zu Verfügbarkeitsgruppen finden Sie unter [Verwalten der Verfügbarkeit von virtuellen Computern](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-manage-availability?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span><span class="sxs-lookup"><span data-stu-id="577ef-139">For more information about availability sets, see [Manage the availability of virtual machines](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-manage-availability?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span></span>
            <span data-ttu-id="577ef-140">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Weitere Informationen zu Azure geplante Wartung von Integrationsdiensten, finden Sie unter [geplante Wartung für virtuelle Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-planned-maintenance?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Derzeit kann ein virtuellen Computer nur verfügbarkeitsgruppe, die zum Zeitpunkt der Erstellung hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="577ef-140">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For more information on Azure planned maintainance, see [Planned maintenance for virtual machines in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-planned-maintenance?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Currently, a VM can only be added to availability set at creation time.</span></span> <span data-ttu-id="577ef-141">Eine vorhandene virtuelle Maschine kann nicht zu einer verfügbarkeitsgruppe hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="577ef-141">An existing VM cannot be added to an availability set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile DiagnosticsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile DiagnosticsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.DiagnosticsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property DiagnosticsProfile As DiagnosticsProfile" />
      <MemberSignature Language="F#" Value="member this.DiagnosticsProfile : Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.DiagnosticsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.diagnosticsProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="577ef-142">Gibt an die diagnoseeinstellungen Startzustands, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="577ef-142">Gets or sets specifies the boot diagnostic settings state.</span></span>
            <span data-ttu-id="577ef-143">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Api-Mindestversion: 2015-06-15.</span><span class="sxs-lookup"><span data-stu-id="577ef-143">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt;Minimum api-version: 2015-06-15.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HardwareProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.HardwareProfile HardwareProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.HardwareProfile HardwareProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.HardwareProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property HardwareProfile As HardwareProfile" />
      <MemberSignature Language="F#" Value="member this.HardwareProfile : Microsoft.Azure.Management.Compute.Models.HardwareProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.HardwareProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hardwareProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.HardwareProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="577ef-144">Ruft ab oder legt gibt die hardwareeinstellungen für die virtuelle Maschine an.</span><span class="sxs-lookup"><span data-stu-id="577ef-144">Gets or sets specifies the hardware settings for the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceId">
      <MemberSignature Language="C#" Value="public string InstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.InstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceId As String" />
      <MemberSignature Language="F#" Value="member this.InstanceId : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.InstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="instanceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="577ef-145">Ruft die VM-Instanz-ID.</span><span class="sxs-lookup"><span data-stu-id="577ef-145">Gets the virtual machine instance ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceView">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView InstanceView { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView InstanceView" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.InstanceView" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceView As VirtualMachineInstanceView" />
      <MemberSignature Language="F#" Value="member this.InstanceView : Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.InstanceView" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.instanceView")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="577ef-146">Ruft die Instanzansicht für die virtuelle Maschine an.</span><span class="sxs-lookup"><span data-stu-id="577ef-146">Gets the virtual machine instance view.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LatestModelApplied">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; LatestModelApplied { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; LatestModelApplied" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.LatestModelApplied" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LatestModelApplied As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.LatestModelApplied : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.LatestModelApplied" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.latestModelApplied")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="577ef-147">Ruft gibt an, ob das aktuelle Modell mit dem virtuellen Computer angewendet wurde.</span><span class="sxs-lookup"><span data-stu-id="577ef-147">Gets specifies whether the latest model has been applied to the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.licenseType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="577ef-148">Ruft ab oder legt ihn fest gibt an, dass das Image oder Datenträger, der verwendet wird lizenzierte lokalen war.</span><span class="sxs-lookup"><span data-stu-id="577ef-148">Gets or sets specifies that the image or disk that is being used was licensed on-premises.</span></span> <span data-ttu-id="577ef-149">Dieses Element wird nur für Bilder verwendet, die das Betriebssystem Windows Server enthalten.</span><span class="sxs-lookup"><span data-stu-id="577ef-149">This element is only used for images that contain the Windows Server operating system.</span></span>
            <span data-ttu-id="577ef-150">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Mögliche Werte sind: &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; "Windows_client" &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Windows_Server &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Wenn dieses Element in einer Anforderung für ein Update enthalten ist, muss der Wert den ursprünglichen Wert übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="577ef-150">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Possible values are: &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Windows_Client &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Windows_Server &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; If this element is included in a request for an update, the value must match the initial value.</span></span>
            <span data-ttu-id="577ef-151">Dieser Wert kann nicht aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="577ef-151">This value cannot be updated.</span></span> <span data-ttu-id="577ef-152">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Weitere Informationen finden Sie unter [Azure Hybrid verwenden Vorteil für Windows Server](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Api-Mindestversion: 2015-06-15</span><span class="sxs-lookup"><span data-stu-id="577ef-152">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For more information, see [Azure Hybrid Use Benefit for Windows Server](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Minimum api-version: 2015-06-15</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.NetworkProfile NetworkProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.NetworkProfile NetworkProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.NetworkProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkProfile As NetworkProfile" />
      <MemberSignature Language="F#" Value="member this.NetworkProfile : Microsoft.Azure.Management.Compute.Models.NetworkProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.NetworkProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.NetworkProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="577ef-153">Ruft ab oder legt gibt die Netzwerkschnittstellen des virtuellen Computers an.</span><span class="sxs-lookup"><span data-stu-id="577ef-153">Gets or sets specifies the network interfaces of the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.OSProfile OsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.OSProfile OsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.OsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property OsProfile As OSProfile" />
      <MemberSignature Language="F#" Value="member this.OsProfile : Microsoft.Azure.Management.Compute.Models.OSProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.OsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.osProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OSProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="577ef-154">Ruft ab oder legt gibt die betriebssystemeinstellungen für den virtuellen Computer an.</span><span class="sxs-lookup"><span data-stu-id="577ef-154">Gets or sets specifies the operating system settings for the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Plan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.Plan Plan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.Plan Plan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.Plan" />
      <MemberSignature Language="VB.NET" Value="Public Property Plan As Plan" />
      <MemberSignature Language="F#" Value="member this.Plan : Microsoft.Azure.Management.Compute.Models.Plan with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.Plan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="plan")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Plan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="577ef-155">Ruft ab oder legt gibt Informationen zu den Marketplace-Image zum Erstellen des virtuellen Computers verwendet.</span><span class="sxs-lookup"><span data-stu-id="577ef-155">Gets or sets specifies information about the marketplace image used to create the virtual machine.</span></span> <span data-ttu-id="577ef-156">Dieses Element wird nur für Marketplace-Images verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="577ef-156">This element is only used for marketplace images.</span></span> <span data-ttu-id="577ef-157">Bevor Sie einem Marketplace-Image aus einer API verwenden können, müssen Sie das Bild zur programmgesteuerten Verwendung aktivieren.</span><span class="sxs-lookup"><span data-stu-id="577ef-157">Before you can use a marketplace image from an API, you must enable the image for programmatic use.</span></span>  <span data-ttu-id="577ef-158">Suchen Sie im Azure-Portal Marketplace-Image, das Sie verwenden möchten und klicken Sie dann auf **bereitzustellende programmgesteuert, erste Schritte -&amp;Gt;**.</span><span class="sxs-lookup"><span data-stu-id="577ef-158">In the Azure portal, find the marketplace image that you want to use and then click **Want to deploy programmatically, Get Started -&amp;gt;**.</span></span>
            <span data-ttu-id="577ef-159">Geben Sie alle erforderlichen Informationen ein, und klicken Sie dann auf **speichern**.</span><span class="sxs-lookup"><span data-stu-id="577ef-159">Enter any required information and then click **Save**.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="577ef-160">Ruft den Status der Bereitstellung, die nur in der Antwort angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="577ef-160">Gets the provisioning state, which only appears in the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; Resources { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.Resources" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resources As IList(Of VirtualMachineExtension)" />
      <MemberSignature Language="F#" Value="member this.Resources : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.Resources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resources")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="577ef-161">Ruft die virtuelle Maschine untergeordneten Ressourcen Erweiterung ab.</span><span class="sxs-lookup"><span data-stu-id="577ef-161">Gets the virtual machine child extension resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.Sku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Models.Sku" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="577ef-162">Ruft den virtuellen Computer SKU ab.</span><span class="sxs-lookup"><span data-stu-id="577ef-162">Gets the virtual machine SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.StorageProfile StorageProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.StorageProfile StorageProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.StorageProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageProfile As StorageProfile" />
      <MemberSignature Language="F#" Value="member this.StorageProfile : Microsoft.Azure.Management.Compute.Models.StorageProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.StorageProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.StorageProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="577ef-163">Ruft ab oder legt gibt die speichereinstellungen für den Datenträger des virtuellen Computers an.</span><span class="sxs-lookup"><span data-stu-id="577ef-163">Gets or sets specifies the storage settings for the virtual machine disks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetVM.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="577ef-164">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="577ef-164">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="577ef-165">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="577ef-165">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmId">
      <MemberSignature Language="C#" Value="public string VmId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.VmId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VmId As String" />
      <MemberSignature Language="F#" Value="member this.VmId : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.VmId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="577ef-166">Ruft die Azure VM eindeutige ID.</span><span class="sxs-lookup"><span data-stu-id="577ef-166">Gets azure VM unique ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>