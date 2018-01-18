<Type Name="ImageReference" FullName="Microsoft.Azure.Batch.Protocol.Models.ImageReference">
  <TypeSignature Language="C#" Value="public class ImageReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ImageReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageReference" />
  <TypeSignature Language="F#" Value="type ImageReference = class" />
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
            <span data-ttu-id="19785-101">Ein Verweis auf ein Azure-virtuelle Computer-Marketplace-Image oder ein benutzerdefiniertes Image des virtuellen Azure-Computer.</span><span class="sxs-lookup"><span data-stu-id="19785-101">A reference to an Azure Virtual Machines Marketplace image or a custom Azure Virtual Machine image.</span></span> <span data-ttu-id="19785-102">Zum Abrufen aller Azure Marketplace-Image-Verweise, die vom Azure Batch überprüft wurden, finden Sie unter "Liste Knoten Agent-SKUs" Vorgang.</span><span class="sxs-lookup"><span data-stu-id="19785-102">To get the list of all Azure Marketplace image references verified by Azure Batch, see the 'List node agent SKUs' operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ImageReference.#ctor" />
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
            <span data-ttu-id="19785-103">Initialisiert eine neue Instanz der Klasse ImageReference.</span><span class="sxs-lookup"><span data-stu-id="19785-103">Initializes a new instance of the ImageReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference (string publisher = null, string offer = null, string sku = null, string version = null, string virtualMachineImageId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string publisher, string offer, string sku, string version, string virtualMachineImageId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ImageReference.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional publisher As String = null, Optional offer As String = null, Optional sku As String = null, Optional version As String = null, Optional virtualMachineImageId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ImageReference : string * string * string * string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.ImageReference" Usage="new Microsoft.Azure.Batch.Protocol.Models.ImageReference (publisher, offer, sku, version, virtualMachineImageId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="virtualMachineImageId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher"><span data-ttu-id="19785-104">Der Herausgeber des Images Marketplace für Azure-virtuellen Computern.</span><span class="sxs-lookup"><span data-stu-id="19785-104">The publisher of the Azure Virtual Machines Marketplace image.</span></span></param>
        <param name="offer"><span data-ttu-id="19785-105">Der Angebotstyp von der Azure-virtuelle Computer-Marketplace-Image.</span><span class="sxs-lookup"><span data-stu-id="19785-105">The offer type of the Azure Virtual Machines Marketplace image.</span></span></param>
        <param name="sku"><span data-ttu-id="19785-106">Die SKU des Images Marketplace für Azure-virtuellen Computern.</span><span class="sxs-lookup"><span data-stu-id="19785-106">The SKU of the Azure Virtual Machines Marketplace image.</span></span></param>
        <param name="version"><span data-ttu-id="19785-107">Die Version des Azure VMs Marketplace-Images.</span><span class="sxs-lookup"><span data-stu-id="19785-107">The version of the Azure Virtual Machines Marketplace image.</span></span></param>
        <param name="virtualMachineImageId"><span data-ttu-id="19785-108">Die ARM-Ressourcenbezeichner des Image des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="19785-108">The ARM resource identifier of the virtual machine image.</span></span> <span data-ttu-id="19785-109">Berechnet, dass die Knoten des Pools mit diesem benutzerdefinierten Abbild erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="19785-109">Computes nodes of the pool will be created using this custom image.</span></span> <span data-ttu-id="19785-110">Dies ist von der Form /subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName}</span><span class="sxs-lookup"><span data-stu-id="19785-110">This is of the form /subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName}</span></span></param>
        <summary>
            <span data-ttu-id="19785-111">Initialisiert eine neue Instanz der Klasse ImageReference.</span><span class="sxs-lookup"><span data-stu-id="19785-111">Initializes a new instance of the ImageReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offer">
      <MemberSignature Language="C#" Value="public string Offer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ImageReference.Offer" />
      <MemberSignature Language="VB.NET" Value="Public Property Offer As String" />
      <MemberSignature Language="F#" Value="member this.Offer : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ImageReference.Offer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="offer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="19785-112">Ruft ab oder legt ihn fest die Angebot der Azure-virtuelle Computer-Marketplace-Image.</span><span class="sxs-lookup"><span data-stu-id="19785-112">Gets or sets the offer type of the Azure Virtual Machines Marketplace image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="19785-113">Z. B. UbuntuServer oder Windows Server.</span><span class="sxs-lookup"><span data-stu-id="19785-113">For example, UbuntuServer or WindowsServer.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ImageReference.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ImageReference.Publisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="publisher")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="19785-114">Abrufen oder Festlegen der Herausgeber des Images Marketplace für Azure-virtuellen Computern.</span><span class="sxs-lookup"><span data-stu-id="19785-114">Gets or sets the publisher of the Azure Virtual Machines Marketplace image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="19785-115">Canonical oder MicrosoftWindowsServer.</span><span class="sxs-lookup"><span data-stu-id="19785-115">For example, Canonical or MicrosoftWindowsServer.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public string Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ImageReference.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As String" />
      <MemberSignature Language="F#" Value="member this.Sku : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ImageReference.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="19785-116">Abrufen oder festlegen die SKU der Azure-virtuelle Computer-Marketplace-Image.</span><span class="sxs-lookup"><span data-stu-id="19785-116">Gets or sets the SKU of the Azure Virtual Machines Marketplace image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="19785-117">Beispielsweise 14.04.0-LTS oder 2012 R2 Datencenter.</span><span class="sxs-lookup"><span data-stu-id="19785-117">For example, 14.04.0-LTS or 2012-R2-Datacenter.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ImageReference.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ImageReference.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="19785-118">Ruft ab oder legt die Version von der Azure-virtuelle Computer-Marketplace-Image.</span><span class="sxs-lookup"><span data-stu-id="19785-118">Gets or sets the version of the Azure Virtual Machines Marketplace image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="19785-119">Ein Wert "latest" kann angegeben werden, um die neueste Version eines Bilds auszuwählen.</span><span class="sxs-lookup"><span data-stu-id="19785-119">A value of 'latest' can be specified to select the latest version of an image.</span></span> <span data-ttu-id="19785-120">Wenn nicht angegeben, ist die Standardeinstellung 'letzte'.</span><span class="sxs-lookup"><span data-stu-id="19785-120">If omitted, the default is 'latest'.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineImageId">
      <MemberSignature Language="C#" Value="public string VirtualMachineImageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineImageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ImageReference.VirtualMachineImageId" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineImageId As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineImageId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ImageReference.VirtualMachineImageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineImageId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="19785-121">Ruft ab oder legt den ARM-Ressourcenbezeichner des Image des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="19785-121">Gets or sets the ARM resource identifier of the virtual machine image.</span></span> <span data-ttu-id="19785-122">Berechnet, dass die Knoten des Pools mit diesem benutzerdefinierten Abbild erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="19785-122">Computes nodes of the pool will be created using this custom image.</span></span> <span data-ttu-id="19785-123">Dies ist von der Form /subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName}</span><span class="sxs-lookup"><span data-stu-id="19785-123">This is of the form /subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName}</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="19785-124">Diese Eigenschaft ist mit anderen Eigenschaften ImageReference gegenseitig.</span><span class="sxs-lookup"><span data-stu-id="19785-124">This property is mutually exclusive with other ImageReference properties.</span></span> <span data-ttu-id="19785-125">Image des virtuellen Computers muss sich in derselben Region und demselben Abonnement wie der Azure Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="19785-125">The virtual machine image must be in the same region and subscription as the Azure Batch account.</span></span> <span data-ttu-id="19785-126">Informationen über die Firewall-Einstellungen für den Batch-Knoten-Agent für die Kommunikation mit der Batch-Dienst finden Sie unter https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration.</span><span class="sxs-lookup"><span data-stu-id="19785-126">For information about the firewall settings for the Batch node agent to communicate with the Batch service see https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>