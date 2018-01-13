<Type Name="ImageReference" FullName="Microsoft.Azure.Batch.ImageReference">
  <TypeSignature Language="C#" Value="public class ImageReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ImageReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageReference" />
  <TypeSignature Language="F#" Value="type ImageReference = class&#xA;    interface ITransportObjectProvider&lt;ImageReference&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="094fc-101">Azure VM-Image.</span><span class="sxs-lookup"><span data-stu-id="094fc-101">Azure Virtual Machine image.</span></span> <span data-ttu-id="094fc-102">Zum Abrufen aller Azure Marketplace-Image-Verweise, die vom Azure Batch überprüft wurden, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListNodeAgentSkus(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> und <see cref="P:Microsoft.Azure.Batch.NodeAgentSku.VerifiedImageReferences" />.</span><span class="sxs-lookup"><span data-stu-id="094fc-102">To get the list of all Azure Marketplace image references verified by Azure Batch, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListNodeAgentSkus(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> and <see cref="P:Microsoft.Azure.Batch.NodeAgentSku.VerifiedImageReferences" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference (string virtualMachineImageId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string virtualMachineImageId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ImageReference.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (virtualMachineImageId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ImageReference : string -&gt; Microsoft.Azure.Batch.ImageReference" Usage="new Microsoft.Azure.Batch.ImageReference virtualMachineImageId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="virtualMachineImageId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="virtualMachineImageId">
            <span data-ttu-id="094fc-103">Die ARM-Ressourcenbezeichner des Image des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="094fc-103">The ARM resource identifier of the virtual machine image.</span></span> <span data-ttu-id="094fc-104">Berechnet, dass die Knoten des Pools mit diesem benutzerdefinierten Abbild erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="094fc-104">Computes nodes of the pool will be created using this custom image.</span></span> <span data-ttu-id="094fc-105">Dies ist von der Form /subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName}</span><span class="sxs-lookup"><span data-stu-id="094fc-105">This is of the form /subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName}</span></span>
            </param>
        <summary>
            <span data-ttu-id="094fc-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.ImageReference" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="094fc-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.ImageReference" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference (string offer, string publisher, string sku, string version = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string offer, string publisher, string sku, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ImageReference.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (offer As String, publisher As String, sku As String, Optional version As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ImageReference : string * string * string * string -&gt; Microsoft.Azure.Batch.ImageReference" Usage="new Microsoft.Azure.Batch.ImageReference (offer, publisher, sku, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="offer"><span data-ttu-id="094fc-107">Der Angebotstyp von der Azure-virtuelle Computer-Marketplace-Image.</span><span class="sxs-lookup"><span data-stu-id="094fc-107">The offer type of the Azure Virtual Machines Marketplace image.</span></span></param>
        <param name="publisher"><span data-ttu-id="094fc-108">Der Herausgeber des Images Marketplace für Azure-virtuellen Computern.</span><span class="sxs-lookup"><span data-stu-id="094fc-108">The publisher of the Azure Virtual Machines Marketplace image.</span></span></param>
        <param name="sku"><span data-ttu-id="094fc-109">Die SKU des Images Marketplace für Azure-virtuellen Computern.</span><span class="sxs-lookup"><span data-stu-id="094fc-109">The SKU of the Azure Virtual Machines Marketplace image.</span></span></param>
        <param name="version"><span data-ttu-id="094fc-110">Die Version des Azure VMs Marketplace-Images.</span><span class="sxs-lookup"><span data-stu-id="094fc-110">The version of the Azure Virtual Machines Marketplace image.</span></span></param>
        <summary>
            <span data-ttu-id="094fc-111">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.ImageReference" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="094fc-111">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.ImageReference" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offer">
      <MemberSignature Language="C#" Value="public string Offer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ImageReference.Offer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Offer As String" />
      <MemberSignature Language="F#" Value="member this.Offer : string" Usage="Microsoft.Azure.Batch.ImageReference.Offer" />
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
            <span data-ttu-id="094fc-112">Ruft den Angebot des Images Marketplace für Azure-virtuellen Computern ab.</span><span class="sxs-lookup"><span data-stu-id="094fc-112">Gets the offer type of the Azure Virtual Machines Marketplace image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="094fc-113">Z. B. UbuntuServer oder Windows Server.</span><span class="sxs-lookup"><span data-stu-id="094fc-113">For example, UbuntuServer or WindowsServer.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ImageReference.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string" Usage="Microsoft.Azure.Batch.ImageReference.Publisher" />
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
            <span data-ttu-id="094fc-114">Ruft den Herausgeber des Images Marketplace für Azure-virtuellen Computern ab.</span><span class="sxs-lookup"><span data-stu-id="094fc-114">Gets the publisher of the Azure Virtual Machines Marketplace image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="094fc-115">Canonical oder MicrosoftWindowsServer.</span><span class="sxs-lookup"><span data-stu-id="094fc-115">For example, Canonical or MicrosoftWindowsServer.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public string Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ImageReference.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As String" />
      <MemberSignature Language="F#" Value="member this.Sku : string" Usage="Microsoft.Azure.Batch.ImageReference.Sku" />
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
            <span data-ttu-id="094fc-116">Ruft die SKU des Images Marketplace für Azure-virtuellen Computern ab.</span><span class="sxs-lookup"><span data-stu-id="094fc-116">Gets the SKU of the Azure Virtual Machines Marketplace image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="094fc-117">Beispielsweise 14.04.0-LTS oder 2012 R2 Datencenter.</span><span class="sxs-lookup"><span data-stu-id="094fc-117">For example, 14.04.0-LTS or 2012-R2-Datacenter.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ImageReference.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string" Usage="Microsoft.Azure.Batch.ImageReference.Version" />
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
            <span data-ttu-id="094fc-118">Ruft die Version der Azure-virtuelle Computer-Marketplace-Image ab.</span><span class="sxs-lookup"><span data-stu-id="094fc-118">Gets the version of the Azure Virtual Machines Marketplace image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="094fc-119">Wenn diese Eigenschaft nicht angegeben ist, wird standardmäßig "Latest", die neueste Version des Bilds wird.</span><span class="sxs-lookup"><span data-stu-id="094fc-119">If this property is not specified, it defaults to 'latest', which is the latest version of the image.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineImageId">
      <MemberSignature Language="C#" Value="public string VirtualMachineImageId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineImageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ImageReference.VirtualMachineImageId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineImageId As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineImageId : string" Usage="Microsoft.Azure.Batch.ImageReference.VirtualMachineImageId" />
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
            <span data-ttu-id="094fc-120">Ruft den ARM-Ressourcenbezeichner des Image des virtuellen Computers ab.</span><span class="sxs-lookup"><span data-stu-id="094fc-120">Gets the ARM resource identifier of the virtual machine image.</span></span> <span data-ttu-id="094fc-121">Berechnet, dass die Knoten des Pools mit diesem benutzerdefinierten Abbild erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="094fc-121">Computes nodes of the pool will be created using this custom image.</span></span> <span data-ttu-id="094fc-122">Dies ist von der Form /subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName}</span><span class="sxs-lookup"><span data-stu-id="094fc-122">This is of the form /subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName}</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="094fc-123">Diese Eigenschaft ist mit anderen Eigenschaften ImageReference gegenseitig.</span><span class="sxs-lookup"><span data-stu-id="094fc-123">This property is mutually exclusive with other ImageReference properties.</span></span> <span data-ttu-id="094fc-124">Image des virtuellen Computers muss sich in derselben Region und demselben Abonnement wie der Azure Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="094fc-124">The virtual machine image must be in the same region and subscription as the Azure Batch account.</span></span> <span data-ttu-id="094fc-125">Informationen über die Firewall-Einstellungen für den Batch-Knoten-Agent für die Kommunikation mit Batch-Dienst finden Sie unter https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration.</span><span class="sxs-lookup"><span data-stu-id="094fc-125">For information about the firewall settings for the Batch node agent to communicate with Batch service see https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>