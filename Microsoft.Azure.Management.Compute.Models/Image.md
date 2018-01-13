<Type Name="Image" FullName="Microsoft.Azure.Management.Compute.Models.Image">
  <TypeSignature Language="C#" Value="public class Image : Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Image extends Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.Image" />
  <TypeSignature Language="VB.NET" Value="Public Class Image&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Image = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="d8efa-101">Quellbenutzer Bild virtuelle Festplatte an.</span><span class="sxs-lookup"><span data-stu-id="d8efa-101">The source user image virtual hard disk.</span></span> <span data-ttu-id="d8efa-102">Die virtuelle Festplatte wird vor dem Anfügen an den virtuellen Computer kopiert werden.</span><span class="sxs-lookup"><span data-stu-id="d8efa-102">The virtual hard disk will be copied before being attached to the virtual machine.</span></span> <span data-ttu-id="d8efa-103">Wenn SourceImage bereitgestellt wird, muss die virtuelle Festplatte für Ziel nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="d8efa-103">If SourceImage is provided, the destination virtual hard drive must not exist.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Image ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Image.#ctor" />
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
            <span data-ttu-id="d8efa-104">Initialisiert eine neue Instanz der Image-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d8efa-104">Initializes a new instance of the Image class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Image (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Compute.Models.SubResource sourceVirtualMachine = null, Microsoft.Azure.Management.Compute.Models.ImageStorageProfile storageProfile = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Compute.Models.SubResource sourceVirtualMachine, class Microsoft.Azure.Management.Compute.Models.ImageStorageProfile storageProfile, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Image.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Compute.Models.SubResource,Microsoft.Azure.Management.Compute.Models.ImageStorageProfile,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional sourceVirtualMachine As SubResource = null, Optional storageProfile As ImageStorageProfile = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.Image : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Compute.Models.SubResource * Microsoft.Azure.Management.Compute.Models.ImageStorageProfile * string -&gt; Microsoft.Azure.Management.Compute.Models.Image" Usage="new Microsoft.Azure.Management.Compute.Models.Image (location, id, name, type, tags, sourceVirtualMachine, storageProfile, provisioningState)" />
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
        <Parameter Name="sourceVirtualMachine" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
        <Parameter Name="storageProfile" Type="Microsoft.Azure.Management.Compute.Models.ImageStorageProfile" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="d8efa-105">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="d8efa-105">Resource location</span></span></param>
        <param name="id"><span data-ttu-id="d8efa-106">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="d8efa-106">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="d8efa-107">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="d8efa-107">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="d8efa-108">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="d8efa-108">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="d8efa-109">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="d8efa-109">Resource tags</span></span></param>
        <param name="sourceVirtualMachine"><span data-ttu-id="d8efa-110">Die ursprüngliche virtuelle Maschine aus dem Image erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="d8efa-110">The source virtual machine from which Image is created.</span></span></param>
        <param name="storageProfile"><span data-ttu-id="d8efa-111">Gibt die speichereinstellungen für den Datenträger des virtuellen Computers an.</span><span class="sxs-lookup"><span data-stu-id="d8efa-111">Specifies the storage settings for the virtual machine disks.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="d8efa-112">Der Bereitstellungsstatus.</span><span class="sxs-lookup"><span data-stu-id="d8efa-112">The provisioning state.</span></span></param>
        <summary>
            <span data-ttu-id="d8efa-113">Initialisiert eine neue Instanz der Image-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d8efa-113">Initializes a new instance of the Image class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Image.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Compute.Models.Image.ProvisioningState" />
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
            <span data-ttu-id="d8efa-114">Ruft den Bereitstellungsstatus.</span><span class="sxs-lookup"><span data-stu-id="d8efa-114">Gets the provisioning state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceVirtualMachine">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource SourceVirtualMachine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource SourceVirtualMachine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Image.SourceVirtualMachine" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceVirtualMachine As SubResource" />
      <MemberSignature Language="F#" Value="member this.SourceVirtualMachine : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Image.SourceVirtualMachine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourceVirtualMachine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8efa-115">Ruft ab oder legt die ursprüngliche virtuelle Maschine, die aus dem Image erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="d8efa-115">Gets or sets the source virtual machine from which Image is created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ImageStorageProfile StorageProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ImageStorageProfile StorageProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Image.StorageProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageProfile As ImageStorageProfile" />
      <MemberSignature Language="F#" Value="member this.StorageProfile : Microsoft.Azure.Management.Compute.Models.ImageStorageProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Image.StorageProfile" />
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
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ImageStorageProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8efa-116">Ruft ab oder legt gibt die speichereinstellungen für den Datenträger des virtuellen Computers an.</span><span class="sxs-lookup"><span data-stu-id="d8efa-116">Gets or sets specifies the storage settings for the virtual machine disks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Image.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="image.Validate " />
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
            <span data-ttu-id="d8efa-117">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="d8efa-117">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d8efa-118">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="d8efa-118">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>