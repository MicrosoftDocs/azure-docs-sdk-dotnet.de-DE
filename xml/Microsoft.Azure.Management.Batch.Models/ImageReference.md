<Type Name="ImageReference" FullName="Microsoft.Azure.Management.Batch.Models.ImageReference">
  <TypeSignature Language="C#" Value="public class ImageReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.ImageReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageReference" />
  <TypeSignature Language="F#" Value="type ImageReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6d680-101">Ein Verweis auf ein Azure-virtuelle Computer-Marketplace-Image oder der Azure-Bildressource eines benutzerdefinierten virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="6d680-101">A reference to an Azure Virtual Machines Marketplace image or the Azure Image resource of a custom Virtual Machine.</span></span> <span data-ttu-id="6d680-102">Um die Liste der alle von Azure Batch überprüft ImageReferences zu erhalten, finden Sie unter den Vorgang "Liste unterstützter Knoten Agent SKUs".</span><span class="sxs-lookup"><span data-stu-id="6d680-102">To get the list of all imageReferences verified by Azure Batch, see the 'List supported node agent SKUs' operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ImageReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6d680-103">Initialisiert eine neue Instanz der Klasse ImageReference.</span><span class="sxs-lookup"><span data-stu-id="6d680-103">Initializes a new instance of the ImageReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference (string publisher = null, string offer = null, string sku = null, string version = null, string id = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string publisher, string offer, string sku, string version, string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ImageReference.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional publisher As String = null, Optional offer As String = null, Optional sku As String = null, Optional version As String = null, Optional id As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.ImageReference : string * string * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.ImageReference" Usage="new Microsoft.Azure.Management.Batch.Models.ImageReference (publisher, offer, sku, version, id)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher"><span data-ttu-id="6d680-104">Der Herausgeber des Images Marketplace für Azure-virtuellen Computern.</span><span class="sxs-lookup"><span data-stu-id="6d680-104">The publisher of the Azure Virtual Machines Marketplace image.</span></span></param>
        <param name="offer"><span data-ttu-id="6d680-105">Der Angebotstyp von der Azure-virtuelle Computer-Marketplace-Image.</span><span class="sxs-lookup"><span data-stu-id="6d680-105">The offer type of the Azure Virtual Machines Marketplace image.</span></span></param>
        <param name="sku"><span data-ttu-id="6d680-106">Die SKU des Images Marketplace für Azure-virtuellen Computern.</span><span class="sxs-lookup"><span data-stu-id="6d680-106">The SKU of the Azure Virtual Machines Marketplace image.</span></span></param>
        <param name="version"><span data-ttu-id="6d680-107">Die Version des Azure VMs Marketplace-Images.</span><span class="sxs-lookup"><span data-stu-id="6d680-107">The version of the Azure Virtual Machines Marketplace image.</span></span></param>
        <param name="id"><span data-ttu-id="6d680-108">Die ARM-Ressourcenbezeichner des Image des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="6d680-108">The ARM resource identifier of the virtual machine image.</span></span> <span data-ttu-id="6d680-109">Berechnet, dass die Knoten des Pools mit diesem benutzerdefinierten Abbild erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="6d680-109">Computes nodes of the pool will be created using this custom image.</span></span> <span data-ttu-id="6d680-110">Dies ist von der Form /subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName}</span><span class="sxs-lookup"><span data-stu-id="6d680-110">This is of the form /subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName}</span></span></param>
        <summary>
            <span data-ttu-id="6d680-111">Initialisiert eine neue Instanz der Klasse ImageReference.</span><span class="sxs-lookup"><span data-stu-id="6d680-111">Initializes a new instance of the ImageReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ImageReference.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ImageReference.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d680-112">Ruft ab oder legt den ARM-Ressourcenbezeichner des Image des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="6d680-112">Gets or sets the ARM resource identifier of the virtual machine image.</span></span> <span data-ttu-id="6d680-113">Berechnet, dass die Knoten des Pools mit diesem benutzerdefinierten Abbild erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="6d680-113">Computes nodes of the pool will be created using this custom image.</span></span> <span data-ttu-id="6d680-114">Dies ist von der Form /subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName}</span><span class="sxs-lookup"><span data-stu-id="6d680-114">This is of the form /subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName}</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6d680-115">Diese Eigenschaft ist für sich gegenseitig ausschließende und andere Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="6d680-115">This property is mutually exclusive with other properties.</span></span> <span data-ttu-id="6d680-116">Image des virtuellen Computers muss sich in derselben Region und demselben Abonnement wie der Azure Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="6d680-116">The virtual machine image must be in the same region and subscription as the Azure Batch account.</span></span> <span data-ttu-id="6d680-117">Informationen über die Firewall-Einstellungen für Batch-Knoten-Agent für die Kommunikation mit Batch-Dienst finden Sie unter https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration.</span><span class="sxs-lookup"><span data-stu-id="6d680-117">For information about the firewall settings for Batch node agent to communicate with Batch service see https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration .</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Offer">
      <MemberSignature Language="C#" Value="public string Offer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ImageReference.Offer" />
      <MemberSignature Language="VB.NET" Value="Public Property Offer As String" />
      <MemberSignature Language="F#" Value="member this.Offer : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ImageReference.Offer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="6d680-118">Ruft ab oder legt ihn fest die Angebot der Azure-virtuelle Computer-Marketplace-Image.</span><span class="sxs-lookup"><span data-stu-id="6d680-118">Gets or sets the offer type of the Azure Virtual Machines Marketplace image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6d680-119">Z. B. UbuntuServer oder Windows Server.</span><span class="sxs-lookup"><span data-stu-id="6d680-119">For example, UbuntuServer or WindowsServer.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ImageReference.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ImageReference.Publisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="6d680-120">Abrufen oder Festlegen der Herausgeber des Images Marketplace für Azure-virtuellen Computern.</span><span class="sxs-lookup"><span data-stu-id="6d680-120">Gets or sets the publisher of the Azure Virtual Machines Marketplace image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6d680-121">Canonical oder MicrosoftWindowsServer.</span><span class="sxs-lookup"><span data-stu-id="6d680-121">For example, Canonical or MicrosoftWindowsServer.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public string Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ImageReference.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As String" />
      <MemberSignature Language="F#" Value="member this.Sku : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ImageReference.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="6d680-122">Abrufen oder festlegen die SKU der Azure-virtuelle Computer-Marketplace-Image.</span><span class="sxs-lookup"><span data-stu-id="6d680-122">Gets or sets the SKU of the Azure Virtual Machines Marketplace image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6d680-123">Beispielsweise 14.04.0-LTS oder 2012 R2 Datencenter.</span><span class="sxs-lookup"><span data-stu-id="6d680-123">For example, 14.04.0-LTS or 2012-R2-Datacenter.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ImageReference.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ImageReference.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="6d680-124">Ruft ab oder legt die Version von der Azure-virtuelle Computer-Marketplace-Image.</span><span class="sxs-lookup"><span data-stu-id="6d680-124">Gets or sets the version of the Azure Virtual Machines Marketplace image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6d680-125">Ein Wert "latest" kann angegeben werden, um die neueste Version eines Bilds auszuwählen.</span><span class="sxs-lookup"><span data-stu-id="6d680-125">A value of 'latest' can be specified to select the latest version of an image.</span></span> <span data-ttu-id="6d680-126">Wenn nicht angegeben, ist die Standardeinstellung 'letzte'.</span><span class="sxs-lookup"><span data-stu-id="6d680-126">If omitted, the default is 'latest'.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>