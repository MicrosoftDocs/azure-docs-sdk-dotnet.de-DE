<Type Name="VirtualMachine" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachine">
  <TypeSignature Language="C#" Value="public class VirtualMachine : Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachine extends Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachine" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachine&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualMachine = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="9814e-101">Beschreibt einen virtuellen Computer an.</span><span class="sxs-lookup"><span data-stu-id="9814e-101">Describes a Virtual Machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachine ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachine.#ctor" />
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
            <span data-ttu-id="9814e-102">Initialisiert eine neue Instanz der Klasse VirtualMachine.</span><span class="sxs-lookup"><span data-stu-id="9814e-102">Initializes a new instance of the VirtualMachine class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachine (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Compute.Models.Plan plan = null, Microsoft.Azure.Management.Compute.Models.HardwareProfile hardwareProfile = null, Microsoft.Azure.Management.Compute.Models.StorageProfile storageProfile = null, Microsoft.Azure.Management.Compute.Models.OSProfile osProfile = null, Microsoft.Azure.Management.Compute.Models.NetworkProfile networkProfile = null, Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile diagnosticsProfile = null, Microsoft.Azure.Management.Compute.Models.SubResource availabilitySet = null, string provisioningState = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView instanceView = null, string licenseType = null, string vmId = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; resources = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity identity = null, System.Collections.Generic.IList&lt;string&gt; zones = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Compute.Models.Plan plan, class Microsoft.Azure.Management.Compute.Models.HardwareProfile hardwareProfile, class Microsoft.Azure.Management.Compute.Models.StorageProfile storageProfile, class Microsoft.Azure.Management.Compute.Models.OSProfile osProfile, class Microsoft.Azure.Management.Compute.Models.NetworkProfile networkProfile, class Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile diagnosticsProfile, class Microsoft.Azure.Management.Compute.Models.SubResource availabilitySet, string provisioningState, class Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView instanceView, string licenseType, string vmId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; resources, class Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity identity, class System.Collections.Generic.IList`1&lt;string&gt; zones) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachine.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Compute.Models.Plan,Microsoft.Azure.Management.Compute.Models.HardwareProfile,Microsoft.Azure.Management.Compute.Models.StorageProfile,Microsoft.Azure.Management.Compute.Models.OSProfile,Microsoft.Azure.Management.Compute.Models.NetworkProfile,Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile,Microsoft.Azure.Management.Compute.Models.SubResource,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension},Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachine : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Compute.Models.Plan * Microsoft.Azure.Management.Compute.Models.HardwareProfile * Microsoft.Azure.Management.Compute.Models.StorageProfile * Microsoft.Azure.Management.Compute.Models.OSProfile * Microsoft.Azure.Management.Compute.Models.NetworkProfile * Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile * Microsoft.Azure.Management.Compute.Models.SubResource * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; * Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachine" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachine (location, id, name, type, tags, plan, hardwareProfile, storageProfile, osProfile, networkProfile, diagnosticsProfile, availabilitySet, provisioningState, instanceView, licenseType, vmId, resources, identity, zones)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="plan" Type="Microsoft.Azure.Management.Compute.Models.Plan" />
        <Parameter Name="hardwareProfile" Type="Microsoft.Azure.Management.Compute.Models.HardwareProfile" />
        <Parameter Name="storageProfile" Type="Microsoft.Azure.Management.Compute.Models.StorageProfile" />
        <Parameter Name="osProfile" Type="Microsoft.Azure.Management.Compute.Models.OSProfile" />
        <Parameter Name="networkProfile" Type="Microsoft.Azure.Management.Compute.Models.NetworkProfile" />
        <Parameter Name="diagnosticsProfile" Type="Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile" />
        <Parameter Name="availabilitySet" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="instanceView" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView" />
        <Parameter Name="licenseType" Type="System.String" />
        <Parameter Name="vmId" Type="System.String" />
        <Parameter Name="resources" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity" />
        <Parameter Name="zones" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="9814e-103">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="9814e-103">Resource location</span></span></param>
        <param name="id"><span data-ttu-id="9814e-104">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="9814e-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="9814e-105">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="9814e-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="9814e-106">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="9814e-106">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="9814e-107">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="9814e-107">Resource tags</span></span></param>
        <param name="plan"><span data-ttu-id="9814e-108">Gibt Informationen zu den Marketplace-Image zum Erstellen des virtuellen Computers verwendet.</span><span class="sxs-lookup"><span data-stu-id="9814e-108">Specifies information about the marketplace image used to create the virtual machine.</span></span> <span data-ttu-id="9814e-109">Dieses Element wird nur für Marketplace-Images verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="9814e-109">This element is only used for marketplace images.</span></span> <span data-ttu-id="9814e-110">Bevor Sie einem Marketplace-Image aus einer API verwenden können, müssen Sie das Bild zur programmgesteuerten Verwendung aktivieren.</span><span class="sxs-lookup"><span data-stu-id="9814e-110">Before you can use a marketplace image from an API, you must enable the image for programmatic use.</span></span>  <span data-ttu-id="9814e-111">Suchen Sie im Azure-Portal Marketplace-Image, das Sie verwenden möchten und klicken Sie dann auf **bereitzustellende programmgesteuert, erste Schritte -&gt;**.</span><span class="sxs-lookup"><span data-stu-id="9814e-111">In the Azure portal, find the marketplace image that you want to use and then click **Want to deploy programmatically, Get Started -&gt;**.</span></span>
            <span data-ttu-id="9814e-112">Geben Sie alle erforderlichen Informationen ein, und klicken Sie dann auf **speichern**.</span><span class="sxs-lookup"><span data-stu-id="9814e-112">Enter any required information and then click **Save**.</span></span></param>
        <param name="hardwareProfile"><span data-ttu-id="9814e-113">Gibt die hardwareeinstellungen für die virtuelle Maschine an.</span><span class="sxs-lookup"><span data-stu-id="9814e-113">Specifies the hardware settings for the virtual machine.</span></span></param>
        <param name="storageProfile"><span data-ttu-id="9814e-114">Gibt die speichereinstellungen für den Datenträger des virtuellen Computers an.</span><span class="sxs-lookup"><span data-stu-id="9814e-114">Specifies the storage settings for the virtual machine disks.</span></span></param>
        <param name="osProfile"><span data-ttu-id="9814e-115">Gibt die betriebssystemeinstellungen für den virtuellen Computer an.</span><span class="sxs-lookup"><span data-stu-id="9814e-115">Specifies the operating system settings for the virtual machine.</span></span></param>
        <param name="networkProfile"><span data-ttu-id="9814e-116">Gibt die Netzwerkschnittstellen des virtuellen Computers an.</span><span class="sxs-lookup"><span data-stu-id="9814e-116">Specifies the network interfaces of the virtual machine.</span></span></param>
        <param name="diagnosticsProfile"><span data-ttu-id="9814e-117">Gibt den Status der Boot-diagnoseeinstellungen.</span><span class="sxs-lookup"><span data-stu-id="9814e-117">Specifies the boot diagnostic settings state.</span></span> <span data-ttu-id="9814e-118">&lt;Brasilien&gt;&lt;Br&gt;-api-Mindestversion: 2015-06-15.</span><span class="sxs-lookup"><span data-stu-id="9814e-118">&lt;br&gt;&lt;br&gt;Minimum api-version: 2015-06-15.</span></span></param>
        <param name="availabilitySet"><span data-ttu-id="9814e-119">Gibt Informationen über die verfügbarkeitsgruppe, der der virtuellen Maschine zugewiesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9814e-119">Specifies information about the availability set that the virtual machine should be assigned to.</span></span>
            <span data-ttu-id="9814e-120">Virtuelle Computer in derselben verfügbarkeitsgruppe angegeben werden auf verschiedene Knoten Maximierung der Verfügbarkeit zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="9814e-120">Virtual machines specified in the same availability set are allocated to different nodes to maximize availability.</span></span> <span data-ttu-id="9814e-121">Weitere Informationen zu Verfügbarkeitsgruppen finden Sie unter [Verwalten der Verfügbarkeit von virtuellen Computern](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-manage-availability?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span><span class="sxs-lookup"><span data-stu-id="9814e-121">For more information about availability sets, see [Manage the availability of virtual machines](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-manage-availability?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span></span>
            <span data-ttu-id="9814e-122">&lt;Brasilien&gt;&lt;Br&gt; finden Sie weitere Informationen zu Azure geplante Wartung von Integrationsdiensten, [geplante Wartung für virtuelle Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-planned-maintenance?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;Br&gt;&lt;Brasilien &gt; Derzeit ein virtuellen Computer nur verfügbarkeitsgruppe, die zum Zeitpunkt der Erstellung hinzugefügt werden kann.</span><span class="sxs-lookup"><span data-stu-id="9814e-122">&lt;br&gt;&lt;br&gt; For more information on Azure planned maintainance, see [Planned maintenance for virtual machines in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-planned-maintenance?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;br&gt; Currently, a VM can only be added to availability set at creation time.</span></span> <span data-ttu-id="9814e-123">Eine vorhandene virtuelle Maschine kann nicht zu einer verfügbarkeitsgruppe hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="9814e-123">An existing VM cannot be added to an availability set.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="9814e-124">Der Bereitstellungsstatus, die nur in der Antwort angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="9814e-124">The provisioning state, which only appears in the response.</span></span></param>
        <param name="instanceView"><span data-ttu-id="9814e-125">Die virtuelle Maschine Instanzansicht.</span><span class="sxs-lookup"><span data-stu-id="9814e-125">The virtual machine instance view.</span></span></param>
        <param name="licenseType"><span data-ttu-id="9814e-126">Gibt an, dass das Image oder Datenträger, der verwendet wird lizenzierte lokalen war.</span><span class="sxs-lookup"><span data-stu-id="9814e-126">Specifies that the image or disk that is being used was licensed on-premises.</span></span> <span data-ttu-id="9814e-127">Dieses Element wird nur für Bilder verwendet, die das Betriebssystem Windows Server enthalten.</span><span class="sxs-lookup"><span data-stu-id="9814e-127">This element is only used for images that contain the Windows Server operating system.</span></span>
            <span data-ttu-id="9814e-128">&lt;Brasilien&gt;&lt;Br&gt; folgende Werte sind möglich: &lt;Br&gt;&lt;Br&gt; "windows_client" &lt;Br&gt;&lt;Br&gt; Windows_Server &lt;Br&gt;&lt;Br&gt; Wenn dieses Element in einer Anforderung für ein Update enthalten ist, muss der Wert den ursprünglichen Wert übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="9814e-128">&lt;br&gt;&lt;br&gt; Possible values are: &lt;br&gt;&lt;br&gt; Windows_Client &lt;br&gt;&lt;br&gt; Windows_Server &lt;br&gt;&lt;br&gt; If this element is included in a request for an update, the value must match the initial value.</span></span> <span data-ttu-id="9814e-129">Dieser Wert kann nicht aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="9814e-129">This value cannot be updated.</span></span> <span data-ttu-id="9814e-130">&lt;Brasilien&gt;&lt;Br&gt; Weitere Informationen finden Sie unter [Azure Hybrid verwenden Vorteil für Windows Server](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;Br&gt;&lt;Br&gt; Minimum API-Version: 2015-06-15</span><span class="sxs-lookup"><span data-stu-id="9814e-130">&lt;br&gt;&lt;br&gt; For more information, see [Azure Hybrid Use Benefit for Windows Server](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;br&gt; Minimum api-version: 2015-06-15</span></span></param>
        <param name="vmId"><span data-ttu-id="9814e-131">Gibt die eindeutige VM-ID also ein 128-Bit-Bezeichner, der codiert und in allen Azure IaaS-VMs SMBIOS gespeichert und kann lesen verwenden Plattform BIOS-Befehle.</span><span class="sxs-lookup"><span data-stu-id="9814e-131">Specifies the VM unique ID which is a 128-bits identifier that is encoded and stored in all Azure IaaS VMs SMBIOS and can be read using platform BIOS commands.</span></span></param>
        <param name="resources"><span data-ttu-id="9814e-132">Die virtuelle Maschine untergeordneten Erweiterung Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="9814e-132">The virtual machine child extension resources.</span></span></param>
        <param name="identity"><span data-ttu-id="9814e-133">Die Identität des virtuellen Computers, wenn konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="9814e-133">The identity of the virtual machine, if configured.</span></span></param>
        <param name="zones"><span data-ttu-id="9814e-134">Die virtuelle Maschinenzonen.</span><span class="sxs-lookup"><span data-stu-id="9814e-134">The virtual machine zones.</span></span></param>
        <summary>
            <span data-ttu-id="9814e-135">Initialisiert eine neue Instanz der Klasse VirtualMachine.</span><span class="sxs-lookup"><span data-stu-id="9814e-135">Initializes a new instance of the VirtualMachine class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilitySet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource AvailabilitySet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource AvailabilitySet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.AvailabilitySet" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailabilitySet As SubResource" />
      <MemberSignature Language="F#" Value="member this.AvailabilitySet : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.AvailabilitySet" />
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
            <span data-ttu-id="9814e-136">Ruft ab oder legt gibt Informationen über die verfügbarkeitsgruppe, der der virtuellen Maschine zugewiesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9814e-136">Gets or sets specifies information about the availability set that the virtual machine should be assigned to.</span></span> <span data-ttu-id="9814e-137">Virtuelle Computer in derselben verfügbarkeitsgruppe angegeben werden auf verschiedene Knoten Maximierung der Verfügbarkeit zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="9814e-137">Virtual machines specified in the same availability set are allocated to different nodes to maximize availability.</span></span> <span data-ttu-id="9814e-138">Weitere Informationen zu Verfügbarkeitsgruppen finden Sie unter [Verwalten der Verfügbarkeit von virtuellen Computern](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-manage-availability?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span><span class="sxs-lookup"><span data-stu-id="9814e-138">For more information about availability sets, see [Manage the availability of virtual machines](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-manage-availability?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span></span>
            <span data-ttu-id="9814e-139">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Weitere Informationen zu Azure geplante Wartung von Integrationsdiensten, finden Sie unter [geplante Wartung für virtuelle Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-planned-maintenance?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Derzeit kann ein virtuellen Computer nur verfügbarkeitsgruppe, die zum Zeitpunkt der Erstellung hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="9814e-139">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For more information on Azure planned maintainance, see [Planned maintenance for virtual machines in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-planned-maintenance?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Currently, a VM can only be added to availability set at creation time.</span></span> <span data-ttu-id="9814e-140">Eine vorhandene virtuelle Maschine kann nicht zu einer verfügbarkeitsgruppe hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="9814e-140">An existing VM cannot be added to an availability set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile DiagnosticsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile DiagnosticsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.DiagnosticsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property DiagnosticsProfile As DiagnosticsProfile" />
      <MemberSignature Language="F#" Value="member this.DiagnosticsProfile : Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.DiagnosticsProfile" />
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
            <span data-ttu-id="9814e-141">Gibt an die diagnoseeinstellungen Startzustands, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="9814e-141">Gets or sets specifies the boot diagnostic settings state.</span></span>
            <span data-ttu-id="9814e-142">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Api-Mindestversion: 2015-06-15.</span><span class="sxs-lookup"><span data-stu-id="9814e-142">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt;Minimum api-version: 2015-06-15.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HardwareProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.HardwareProfile HardwareProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.HardwareProfile HardwareProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.HardwareProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property HardwareProfile As HardwareProfile" />
      <MemberSignature Language="F#" Value="member this.HardwareProfile : Microsoft.Azure.Management.Compute.Models.HardwareProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.HardwareProfile" />
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
            <span data-ttu-id="9814e-143">Ruft ab oder legt gibt die hardwareeinstellungen für die virtuelle Maschine an.</span><span class="sxs-lookup"><span data-stu-id="9814e-143">Gets or sets specifies the hardware settings for the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As VirtualMachineIdentity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9814e-144">Ruft ab oder legt die Identität des virtuellen Computers fest, wenn konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="9814e-144">Gets or sets the identity of the virtual machine, if configured.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceView">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView InstanceView { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView InstanceView" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.InstanceView" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceView As VirtualMachineInstanceView" />
      <MemberSignature Language="F#" Value="member this.InstanceView : Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.InstanceView" />
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
            <span data-ttu-id="9814e-145">Ruft die Instanzansicht für die virtuelle Maschine an.</span><span class="sxs-lookup"><span data-stu-id="9814e-145">Gets the virtual machine instance view.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.LicenseType" />
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
            <span data-ttu-id="9814e-146">Ruft ab oder legt ihn fest gibt an, dass das Image oder Datenträger, der verwendet wird lizenzierte lokalen war.</span><span class="sxs-lookup"><span data-stu-id="9814e-146">Gets or sets specifies that the image or disk that is being used was licensed on-premises.</span></span> <span data-ttu-id="9814e-147">Dieses Element wird nur für Bilder verwendet, die das Betriebssystem Windows Server enthalten.</span><span class="sxs-lookup"><span data-stu-id="9814e-147">This element is only used for images that contain the Windows Server operating system.</span></span>
            <span data-ttu-id="9814e-148">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Mögliche Werte sind: &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; "Windows_client" &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Windows_Server &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Wenn dieses Element in einer Anforderung für ein Update enthalten ist, muss der Wert den ursprünglichen Wert übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="9814e-148">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Possible values are: &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Windows_Client &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Windows_Server &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; If this element is included in a request for an update, the value must match the initial value.</span></span>
            <span data-ttu-id="9814e-149">Dieser Wert kann nicht aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="9814e-149">This value cannot be updated.</span></span> <span data-ttu-id="9814e-150">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Weitere Informationen finden Sie unter [Azure Hybrid verwenden Vorteil für Windows Server](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Api-Mindestversion: 2015-06-15</span><span class="sxs-lookup"><span data-stu-id="9814e-150">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For more information, see [Azure Hybrid Use Benefit for Windows Server](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Minimum api-version: 2015-06-15</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.NetworkProfile NetworkProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.NetworkProfile NetworkProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.NetworkProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkProfile As NetworkProfile" />
      <MemberSignature Language="F#" Value="member this.NetworkProfile : Microsoft.Azure.Management.Compute.Models.NetworkProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.NetworkProfile" />
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
            <span data-ttu-id="9814e-151">Ruft ab oder legt gibt die Netzwerkschnittstellen des virtuellen Computers an.</span><span class="sxs-lookup"><span data-stu-id="9814e-151">Gets or sets specifies the network interfaces of the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.OSProfile OsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.OSProfile OsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.OsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property OsProfile As OSProfile" />
      <MemberSignature Language="F#" Value="member this.OsProfile : Microsoft.Azure.Management.Compute.Models.OSProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.OsProfile" />
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
            <span data-ttu-id="9814e-152">Ruft ab oder legt gibt die betriebssystemeinstellungen für den virtuellen Computer an.</span><span class="sxs-lookup"><span data-stu-id="9814e-152">Gets or sets specifies the operating system settings for the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Plan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.Plan Plan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.Plan Plan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.Plan" />
      <MemberSignature Language="VB.NET" Value="Public Property Plan As Plan" />
      <MemberSignature Language="F#" Value="member this.Plan : Microsoft.Azure.Management.Compute.Models.Plan with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.Plan" />
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
            <span data-ttu-id="9814e-153">Ruft ab oder legt gibt Informationen zu den Marketplace-Image zum Erstellen des virtuellen Computers verwendet.</span><span class="sxs-lookup"><span data-stu-id="9814e-153">Gets or sets specifies information about the marketplace image used to create the virtual machine.</span></span> <span data-ttu-id="9814e-154">Dieses Element wird nur für Marketplace-Images verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="9814e-154">This element is only used for marketplace images.</span></span> <span data-ttu-id="9814e-155">Bevor Sie einem Marketplace-Image aus einer API verwenden können, müssen Sie das Bild zur programmgesteuerten Verwendung aktivieren.</span><span class="sxs-lookup"><span data-stu-id="9814e-155">Before you can use a marketplace image from an API, you must enable the image for programmatic use.</span></span>  <span data-ttu-id="9814e-156">Suchen Sie im Azure-Portal Marketplace-Image, das Sie verwenden möchten und klicken Sie dann auf **bereitzustellende programmgesteuert, erste Schritte -&amp;Gt;**.</span><span class="sxs-lookup"><span data-stu-id="9814e-156">In the Azure portal, find the marketplace image that you want to use and then click **Want to deploy programmatically, Get Started -&amp;gt;**.</span></span>
            <span data-ttu-id="9814e-157">Geben Sie alle erforderlichen Informationen ein, und klicken Sie dann auf **speichern**.</span><span class="sxs-lookup"><span data-stu-id="9814e-157">Enter any required information and then click **Save**.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.ProvisioningState" />
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
            <span data-ttu-id="9814e-158">Ruft den Status der Bereitstellung, die nur in der Antwort angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="9814e-158">Gets the provisioning state, which only appears in the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; Resources { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.Resources" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resources As IList(Of VirtualMachineExtension)" />
      <MemberSignature Language="F#" Value="member this.Resources : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.Resources" />
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
            <span data-ttu-id="9814e-159">Ruft die virtuelle Maschine untergeordneten Ressourcen Erweiterung ab.</span><span class="sxs-lookup"><span data-stu-id="9814e-159">Gets the virtual machine child extension resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.StorageProfile StorageProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.StorageProfile StorageProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.StorageProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageProfile As StorageProfile" />
      <MemberSignature Language="F#" Value="member this.StorageProfile : Microsoft.Azure.Management.Compute.Models.StorageProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.StorageProfile" />
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
            <span data-ttu-id="9814e-160">Ruft ab oder legt gibt die speichereinstellungen für den Datenträger des virtuellen Computers an.</span><span class="sxs-lookup"><span data-stu-id="9814e-160">Gets or sets specifies the storage settings for the virtual machine disks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachine.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="virtualMachine.Validate " />
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
            <span data-ttu-id="9814e-161">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="9814e-161">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9814e-162">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="9814e-162">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmId">
      <MemberSignature Language="C#" Value="public string VmId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.VmId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VmId As String" />
      <MemberSignature Language="F#" Value="member this.VmId : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.VmId" />
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
            <span data-ttu-id="9814e-163">Ruft gibt die eindeutige VM-ID also ein 128-Bit-Bezeichner, der codiert und in allen Azure IaaS-VMs SMBIOS gespeichert und kann lesen verwenden Plattform BIOS-Befehle.</span><span class="sxs-lookup"><span data-stu-id="9814e-163">Gets specifies the VM unique ID which is a 128-bits identifier that is encoded and stored in all Azure IaaS VMs SMBIOS and can be read using platform BIOS commands.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Zones">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Zones { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Zones" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.Zones" />
      <MemberSignature Language="VB.NET" Value="Public Property Zones As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Zones : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.Zones" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="zones")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9814e-164">Ruft ab oder legt die VM-Zonen.</span><span class="sxs-lookup"><span data-stu-id="9814e-164">Gets or sets the virtual machine zones.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>