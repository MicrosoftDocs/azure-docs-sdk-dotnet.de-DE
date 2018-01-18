<Type Name="ImageReference" FullName="Microsoft.Azure.Management.Compute.Models.ImageReference">
  <TypeSignature Language="C#" Value="public class ImageReference : Microsoft.Azure.Management.Compute.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageReference extends Microsoft.Azure.Management.Compute.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ImageReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageReference&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ImageReference = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cdc3f-101">Gibt Informationen über das zu verwendende Bild.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-101">Specifies information about the image to use.</span></span> <span data-ttu-id="cdc3f-102">Sie können Informationen zu Plattform-Images, Marketplace-Images oder Images für virtuelle Computer angeben.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-102">You can specify information about platform images, marketplace images, or virtual machine images.</span></span> <span data-ttu-id="cdc3f-103">Dieses Element ist erforderlich, wenn Sie ein Plattformimage, eine Marketplace-Image oder ein Image eines virtuellen Computers verwenden möchten, jedoch nicht in andere Vorgänge zur Erstellung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-103">This element is required when you want to use a platform image, marketplace image, or virtual machine image, but is not used in other creation operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageReference.#ctor" />
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
            <span data-ttu-id="cdc3f-104">Initialisiert eine neue Instanz der Klasse ImageReference.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-104">Initializes a new instance of the ImageReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference (string id = null, string publisher = null, string offer = null, string sku = null, string version = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string publisher, string offer, string sku, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageReference.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional publisher As String = null, Optional offer As String = null, Optional sku As String = null, Optional version As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ImageReference : string * string * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.ImageReference" Usage="new Microsoft.Azure.Management.Compute.Models.ImageReference (id, publisher, offer, sku, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="cdc3f-105">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="cdc3f-105">Resource Id</span></span></param>
        <param name="publisher"><span data-ttu-id="cdc3f-106">Der Herausgeber des Images.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-106">The image publisher.</span></span></param>
        <param name="offer"><span data-ttu-id="cdc3f-107">Gibt das Angebot des Plattformimage oder Marketplace-Image zum Erstellen des virtuellen Computers verwendet.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-107">Specifies the offer of the platform image or marketplace image used to create the virtual machine.</span></span></param>
        <param name="sku"><span data-ttu-id="cdc3f-108">Das Bild-SKU.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-108">The image SKU.</span></span></param>
        <param name="version"><span data-ttu-id="cdc3f-109">Gibt die Version der Plattform-Images oder Marketplace-Image zum Erstellen des virtuellen Computers verwendet.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-109">Specifies the version of the platform image or marketplace image used to create the virtual machine.</span></span> <span data-ttu-id="cdc3f-110">Die zulässigen Formate sind Hauptversion.Nebenversion.Build oder 'letzte'.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-110">The allowed formats are Major.Minor.Build or 'latest'.</span></span> <span data-ttu-id="cdc3f-111">Haupt- und Nebenversion, Build sind Dezimalzahlen.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-111">Major, Minor, and Build are decimal numbers.</span></span> <span data-ttu-id="cdc3f-112">Geben Sie 'letzte', verwenden Sie die neueste Version eines Bilds zur Zeit bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-112">Specify 'latest' to use the latest version of an image available at deploy time.</span></span> <span data-ttu-id="cdc3f-113">Auch wenn Sie "Letzte" die VM-Image wird nicht automatisch nach dem Update bereitstellen Zeit, selbst wenn eine neue Version verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-113">Even if you use 'latest', the VM image will not automatically update after deploy time even if a new version becomes available.</span></span></param>
        <summary>
            <span data-ttu-id="cdc3f-114">Initialisiert eine neue Instanz der Klasse ImageReference.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-114">Initializes a new instance of the ImageReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offer">
      <MemberSignature Language="C#" Value="public string Offer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageReference.Offer" />
      <MemberSignature Language="VB.NET" Value="Public Property Offer As String" />
      <MemberSignature Language="F#" Value="member this.Offer : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageReference.Offer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="cdc3f-115">Ruft ab oder legt gibt das Angebot des Plattformimage oder Marketplace-Image zum Erstellen des virtuellen Computers verwendet.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-115">Gets or sets specifies the offer of the platform image or marketplace image used to create the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageReference.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageReference.Publisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="cdc3f-116">Ermittelt oder definiert den Image-Verleger.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-116">Gets or sets the image publisher.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public string Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageReference.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As String" />
      <MemberSignature Language="F#" Value="member this.Sku : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageReference.Sku" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cdc3f-117">Ruft ab oder legt das Bild SKU.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-117">Gets or sets the image SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageReference.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageReference.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="cdc3f-118">Ruft ab oder legt gibt die Version der Plattform-Images oder Marketplace-Image zum Erstellen des virtuellen Computers verwendet.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-118">Gets or sets specifies the version of the platform image or marketplace image used to create the virtual machine.</span></span> <span data-ttu-id="cdc3f-119">Die zulässigen Formate sind Hauptversion.Nebenversion.Build oder 'letzte'.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-119">The allowed formats are Major.Minor.Build or 'latest'.</span></span> <span data-ttu-id="cdc3f-120">Haupt- und Nebenversion, Build sind Dezimalzahlen.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-120">Major, Minor, and Build are decimal numbers.</span></span> <span data-ttu-id="cdc3f-121">Geben Sie 'letzte', verwenden Sie die neueste Version eines Bilds zur Zeit bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-121">Specify 'latest' to use the latest version of an image available at deploy time.</span></span> <span data-ttu-id="cdc3f-122">Auch wenn Sie "Letzte" die VM-Image wird nicht automatisch nach dem Update bereitstellen Zeit, selbst wenn eine neue Version verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="cdc3f-122">Even if you use 'latest', the VM image will not automatically update after deploy time even if a new version becomes available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>