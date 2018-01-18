<Type Name="CreationData" FullName="Microsoft.Azure.Management.Compute.Models.CreationData">
  <TypeSignature Language="C#" Value="public class CreationData" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CreationData extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.CreationData" />
  <TypeSignature Language="VB.NET" Value="Public Class CreationData" />
  <TypeSignature Language="F#" Value="type CreationData = class" />
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
            <span data-ttu-id="e468e-101">Daten, die beim Erstellen eines Datenträgers verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="e468e-101">Data used when creating a disk.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CreationData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.CreationData.#ctor" />
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
            <span data-ttu-id="e468e-102">Initialisiert eine neue Instanz der CreationData-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e468e-102">Initializes a new instance of the CreationData class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CreationData (Microsoft.Azure.Management.Compute.Models.DiskCreateOption createOption, string storageAccountId = null, Microsoft.Azure.Management.Compute.Models.ImageDiskReference imageReference = null, string sourceUri = null, string sourceResourceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Models.DiskCreateOption createOption, string storageAccountId, class Microsoft.Azure.Management.Compute.Models.ImageDiskReference imageReference, string sourceUri, string sourceResourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.CreationData.#ctor(Microsoft.Azure.Management.Compute.Models.DiskCreateOption,System.String,Microsoft.Azure.Management.Compute.Models.ImageDiskReference,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createOption As DiskCreateOption, Optional storageAccountId As String = null, Optional imageReference As ImageDiskReference = null, Optional sourceUri As String = null, Optional sourceResourceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.CreationData : Microsoft.Azure.Management.Compute.Models.DiskCreateOption * string * Microsoft.Azure.Management.Compute.Models.ImageDiskReference * string * string -&gt; Microsoft.Azure.Management.Compute.Models.CreationData" Usage="new Microsoft.Azure.Management.Compute.Models.CreationData (createOption, storageAccountId, imageReference, sourceUri, sourceResourceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createOption" Type="Microsoft.Azure.Management.Compute.Models.DiskCreateOption" />
        <Parameter Name="storageAccountId" Type="System.String" />
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Compute.Models.ImageDiskReference" />
        <Parameter Name="sourceUri" Type="System.String" />
        <Parameter Name="sourceResourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="createOption"><span data-ttu-id="e468e-103">Listet die möglichen Quellen der Erstellung des Datenträgers.</span><span class="sxs-lookup"><span data-stu-id="e468e-103">This enumerates the possible sources of a disk's creation.</span></span> <span data-ttu-id="e468e-104">Folgende Werte sind möglich: "Leer", "Anfügen", "FromImage", "Import", "Kopieren"</span><span class="sxs-lookup"><span data-stu-id="e468e-104">Possible values include: 'Empty', 'Attach', 'FromImage', 'Import', 'Copy'</span></span></param>
        <param name="storageAccountId"><span data-ttu-id="e468e-105">Wenn CreateOption importieren Sie, den Azure Resource Manager-Bezeichner des Speicherkontos mit dem Blob als Datenträger importieren.</span><span class="sxs-lookup"><span data-stu-id="e468e-105">If createOption is Import, the Azure Resource Manager identifier of the storage account containing the blob to import as a disk.</span></span> <span data-ttu-id="e468e-106">Nur erforderlich, wenn das Blob in einem anderen Abonnement befindet.</span><span class="sxs-lookup"><span data-stu-id="e468e-106">Required only if the blob is in a different subscription</span></span></param>
        <param name="imageReference"><span data-ttu-id="e468e-107">Datenträger-Quellinformationen.</span><span class="sxs-lookup"><span data-stu-id="e468e-107">Disk source information.</span></span></param>
        <param name="sourceUri"><span data-ttu-id="e468e-108">Wenn CreateOption importieren, ist dies der URI des Blob in einen verwalteten Datenträger importiert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="e468e-108">If createOption is Import, this is the URI of a blob to be imported into a managed disk.</span></span></param>
        <param name="sourceResourceId"><span data-ttu-id="e468e-109">Wenn CreateOption Kopie ist, ist dies die ARM-Id der Quellmomentaufnahme oder des Datenträgers an.</span><span class="sxs-lookup"><span data-stu-id="e468e-109">If createOption is Copy, this is the ARM id of the source snapshot or disk.</span></span></param>
        <summary>
            <span data-ttu-id="e468e-110">Initialisiert eine neue Instanz der CreationData-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e468e-110">Initializes a new instance of the CreationData class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.DiskCreateOption CreateOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Models.DiskCreateOption CreateOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.CreationData.CreateOption" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateOption As DiskCreateOption" />
      <MemberSignature Language="F#" Value="member this.CreateOption : Microsoft.Azure.Management.Compute.Models.DiskCreateOption with get, set" Usage="Microsoft.Azure.Management.Compute.Models.CreationData.CreateOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.DiskCreateOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e468e-111">Ruft ab oder legt dies Listet die möglichen Quellen der Erstellung des Datenträgers.</span><span class="sxs-lookup"><span data-stu-id="e468e-111">Gets or sets this enumerates the possible sources of a disk's creation.</span></span> <span data-ttu-id="e468e-112">Folgende Werte sind möglich: "Leer", "Anfügen", "FromImage", "Import", "Kopieren"</span><span class="sxs-lookup"><span data-stu-id="e468e-112">Possible values include: 'Empty', 'Attach', 'FromImage', 'Import', 'Copy'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ImageDiskReference ImageReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ImageDiskReference ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.CreationData.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageReference As ImageDiskReference" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Management.Compute.Models.ImageDiskReference with get, set" Usage="Microsoft.Azure.Management.Compute.Models.CreationData.ImageReference" />
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
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ImageDiskReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e468e-113">Ruft ab, oder legt ihn fest Datenträger Quellinformationen.</span><span class="sxs-lookup"><span data-stu-id="e468e-113">Gets or sets disk source information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceResourceId">
      <MemberSignature Language="C#" Value="public string SourceResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.CreationData.SourceResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceResourceId As String" />
      <MemberSignature Language="F#" Value="member this.SourceResourceId : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.CreationData.SourceResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e468e-114">Ruft ab oder legt fest, ob CreateOption Kopie ist dies ist die ARM-Id der Quellmomentaufnahme oder des Datenträgers.</span><span class="sxs-lookup"><span data-stu-id="e468e-114">Gets or sets if createOption is Copy, this is the ARM id of the source snapshot or disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceUri">
      <MemberSignature Language="C#" Value="public string SourceUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.CreationData.SourceUri" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceUri As String" />
      <MemberSignature Language="F#" Value="member this.SourceUri : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.CreationData.SourceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e468e-115">Ruft ab oder legt fest, ob CreateOption Import ist, ist dies der URI des Blob in einen verwalteten Datenträger importiert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="e468e-115">Gets or sets if createOption is Import, this is the URI of a blob to be imported into a managed disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountId">
      <MemberSignature Language="C#" Value="public string StorageAccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.CreationData.StorageAccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountId As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountId : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.CreationData.StorageAccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e468e-116">Ruft ab, oder legt sie fest, wenn CreateOption importieren, den Azure Resource Manager-Bezeichner des Speicherkontos mit dem Blob als Datenträger importieren.</span><span class="sxs-lookup"><span data-stu-id="e468e-116">Gets or sets if createOption is Import, the Azure Resource Manager identifier of the storage account containing the blob to import as a disk.</span></span> <span data-ttu-id="e468e-117">Nur erforderlich, wenn das Blob in einem anderen Abonnement befindet.</span><span class="sxs-lookup"><span data-stu-id="e468e-117">Required only if the blob is in a different subscription</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.CreationData.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="creationData.Validate " />
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
            <span data-ttu-id="e468e-118">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="e468e-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e468e-119">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="e468e-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>