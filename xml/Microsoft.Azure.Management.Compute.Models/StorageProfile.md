<Type Name="StorageProfile" FullName="Microsoft.Azure.Management.Compute.Models.StorageProfile">
  <TypeSignature Language="C#" Value="public class StorageProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.StorageProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageProfile" />
  <TypeSignature Language="F#" Value="type StorageProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3d885-101">Gibt die speichereinstellungen für den Datenträger des virtuellen Computers an.</span><span class="sxs-lookup"><span data-stu-id="3d885-101">Specifies the storage settings for the virtual machine disks.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.StorageProfile.#ctor" />
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
            <span data-ttu-id="3d885-102">Initialisiert eine neue Instanz der StorageProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3d885-102">Initializes a new instance of the StorageProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageProfile (Microsoft.Azure.Management.Compute.Models.ImageReference imageReference = null, Microsoft.Azure.Management.Compute.Models.OSDisk osDisk = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DataDisk&gt; dataDisks = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Models.ImageReference imageReference, class Microsoft.Azure.Management.Compute.Models.OSDisk osDisk, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.DataDisk&gt; dataDisks) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.StorageProfile.#ctor(Microsoft.Azure.Management.Compute.Models.ImageReference,Microsoft.Azure.Management.Compute.Models.OSDisk,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.DataDisk})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.StorageProfile : Microsoft.Azure.Management.Compute.Models.ImageReference * Microsoft.Azure.Management.Compute.Models.OSDisk * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DataDisk&gt; -&gt; Microsoft.Azure.Management.Compute.Models.StorageProfile" Usage="new Microsoft.Azure.Management.Compute.Models.StorageProfile (imageReference, osDisk, dataDisks)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Compute.Models.ImageReference" />
        <Parameter Name="osDisk" Type="Microsoft.Azure.Management.Compute.Models.OSDisk" />
        <Parameter Name="dataDisks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DataDisk&gt;" />
      </Parameters>
      <Docs>
        <param name="imageReference"><span data-ttu-id="3d885-103">Gibt Informationen über das zu verwendende Bild.</span><span class="sxs-lookup"><span data-stu-id="3d885-103">Specifies information about the image to use.</span></span> <span data-ttu-id="3d885-104">Sie können Informationen zu Plattform-Images, Marketplace-Images oder Images für virtuelle Computer angeben.</span><span class="sxs-lookup"><span data-stu-id="3d885-104">You can specify information about platform images, marketplace images, or virtual machine images.</span></span> <span data-ttu-id="3d885-105">Dieses Element ist erforderlich, wenn Sie ein Plattformimage, eine Marketplace-Image oder ein Image eines virtuellen Computers verwenden möchten, jedoch nicht in andere Vorgänge zur Erstellung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="3d885-105">This element is required when you want to use a platform image, marketplace image, or virtual machine image, but is not used in other creation operations.</span></span></param>
        <param name="osDisk"><span data-ttu-id="3d885-106">Gibt Informationen zu den Betriebssystem-Datenträger, die von der virtuellen Maschine verwendet.</span><span class="sxs-lookup"><span data-stu-id="3d885-106">Specifies information about the operating system disk used by the virtual machine.</span></span> <span data-ttu-id="3d885-107">&lt;Brasilien&gt;&lt;Br&gt; Weitere Informationen zu Datenträgern finden Sie unter [zu Datenträgern und virtuellen Festplatten für virtuelle Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span><span class="sxs-lookup"><span data-stu-id="3d885-107">&lt;br&gt;&lt;br&gt; For more information about disks, see [About disks and VHDs for Azure virtual machines](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span></span></param>
        <param name="dataDisks"><span data-ttu-id="3d885-108">Gibt die Parameter, die zum Hinzufügen eines Datenträgers an einen virtuellen Computer verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="3d885-108">Specifies the parameters that are used to add a data disk to a virtual machine.</span></span> <span data-ttu-id="3d885-109">&lt;Brasilien&gt;&lt;Br&gt; Weitere Informationen zu Datenträgern finden Sie unter [zu Datenträgern und virtuellen Festplatten für virtuelle Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span><span class="sxs-lookup"><span data-stu-id="3d885-109">&lt;br&gt;&lt;br&gt; For more information about disks, see [About disks and VHDs for Azure virtual machines](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span></span></param>
        <summary>
            <span data-ttu-id="3d885-110">Initialisiert eine neue Instanz der StorageProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3d885-110">Initializes a new instance of the StorageProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DataDisk&gt; DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.DataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.StorageProfile.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As IList(Of DataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DataDisk&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.StorageProfile.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataDisks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3d885-111">Ruft ab oder legt gibt die Parameter, die zum Hinzufügen eines Datenträgers an einen virtuellen Computer verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="3d885-111">Gets or sets specifies the parameters that are used to add a data disk to a virtual machine.</span></span> <span data-ttu-id="3d885-112">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Weitere Informationen zu Datenträgern finden Sie unter [zu Datenträgern und virtuellen Festplatten für virtuelle Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span><span class="sxs-lookup"><span data-stu-id="3d885-112">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For more information about disks, see [About disks and VHDs for Azure virtual machines](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ImageReference ImageReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ImageReference ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.StorageProfile.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageReference As ImageReference" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Management.Compute.Models.ImageReference with get, set" Usage="Microsoft.Azure.Management.Compute.Models.StorageProfile.ImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="imageReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ImageReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3d885-113">Ruft ab oder legt gibt Informationen über das zu verwendende Bild.</span><span class="sxs-lookup"><span data-stu-id="3d885-113">Gets or sets specifies information about the image to use.</span></span> <span data-ttu-id="3d885-114">Sie können Informationen zu Plattform-Images, Marketplace-Images oder Images für virtuelle Computer angeben.</span><span class="sxs-lookup"><span data-stu-id="3d885-114">You can specify information about platform images, marketplace images, or virtual machine images.</span></span> <span data-ttu-id="3d885-115">Dieses Element ist erforderlich, wenn Sie ein Plattformimage, eine Marketplace-Image oder ein Image eines virtuellen Computers verwenden möchten, jedoch nicht in andere Vorgänge zur Erstellung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="3d885-115">This element is required when you want to use a platform image, marketplace image, or virtual machine image, but is not used in other creation operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.OSDisk OsDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.OSDisk OsDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.StorageProfile.OsDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property OsDisk As OSDisk" />
      <MemberSignature Language="F#" Value="member this.OsDisk : Microsoft.Azure.Management.Compute.Models.OSDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Models.StorageProfile.OsDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OSDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3d885-116">Ruft ab oder legt gibt Informationen zu den Betriebssystem-Datenträger, die von der virtuellen Maschine verwendet.</span><span class="sxs-lookup"><span data-stu-id="3d885-116">Gets or sets specifies information about the operating system disk used by the virtual machine.</span></span> <span data-ttu-id="3d885-117">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Weitere Informationen zu Datenträgern finden Sie unter [zu Datenträgern und virtuellen Festplatten für virtuelle Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span><span class="sxs-lookup"><span data-stu-id="3d885-117">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For more information about disks, see [About disks and VHDs for Azure virtual machines](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.StorageProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageProfile.Validate " />
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
            <span data-ttu-id="3d885-118">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="3d885-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3d885-119">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="3d885-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>