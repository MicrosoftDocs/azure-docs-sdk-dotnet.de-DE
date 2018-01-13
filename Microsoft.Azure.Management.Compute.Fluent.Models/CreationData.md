<Type Name="CreationData" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.CreationData">
  <TypeSignature Language="C#" Value="public class CreationData" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CreationData extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData" />
  <TypeSignature Language="VB.NET" Value="Public Class CreationData" />
  <TypeSignature Language="F#" Value="type CreationData = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f5173-101">Daten, die beim Erstellen eines Datenträgers verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="f5173-101">Data used when creating a disk.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CreationData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f5173-102">Initialisiert eine neue Instanz der CreationData-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f5173-102">Initializes a new instance of the CreationData class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CreationData (Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption createOption, string storageAccountId = null, Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference imageReference = null, string sourceUri = null, string sourceResourceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption createOption, string storageAccountId, class Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference imageReference, string sourceUri, string sourceResourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createOption As DiskCreateOption, Optional storageAccountId As String = null, Optional imageReference As ImageDiskReference = null, Optional sourceUri As String = null, Optional sourceResourceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.CreationData : Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption * string * Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.CreationData" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.CreationData (createOption, storageAccountId, imageReference, sourceUri, sourceResourceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createOption" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption" />
        <Parameter Name="storageAccountId" Type="System.String" />
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference" />
        <Parameter Name="sourceUri" Type="System.String" />
        <Parameter Name="sourceResourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="createOption"><span data-ttu-id="f5173-103">Folgende Werte sind möglich: "Leer", "Anfügen", "FromImage", "Import", "Kopieren", "Wiederherstellen"</span><span class="sxs-lookup"><span data-stu-id="f5173-103">Possible values include: 'Empty', 'Attach', 'FromImage', 'Import', 'Copy', 'Restore'</span></span></param>
        <param name="storageAccountId"><span data-ttu-id="f5173-104">Wenn CreateOption importieren Sie, den Azure Resource Manager-Bezeichner des Speicherkontos mit dem Blob als Datenträger importieren.</span><span class="sxs-lookup"><span data-stu-id="f5173-104">If createOption is Import, the Azure Resource Manager identifier of the storage account containing the blob to import as a disk.</span></span> <span data-ttu-id="f5173-105">Nur erforderlich, wenn das Blob in einem anderen Abonnement befindet.</span><span class="sxs-lookup"><span data-stu-id="f5173-105">Required only if the blob is in a different subscription</span></span></param>
        <param name="imageReference"><span data-ttu-id="f5173-106">Datenträger-Quellinformationen.</span><span class="sxs-lookup"><span data-stu-id="f5173-106">Disk source information.</span></span></param>
        <param name="sourceUri"><span data-ttu-id="f5173-107">Wenn CreationOption importieren, ist dies eine SAS-URI in ein Blob in einen verwalteten Datenträger importiert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="f5173-107">If creationOption is Import, this is a SAS URI to a blob to be imported into a managed disk.</span></span> <span data-ttu-id="f5173-108">Wenn CreationOption Kopie ist, ist dies ein relativer Uri ist, enthält die Id der Momentaufnahme für die Datenquelle an einen verwalteten Datenträger kopiert werden.</span><span class="sxs-lookup"><span data-stu-id="f5173-108">If creationOption is Copy, this is a relative Uri containing the id of the source snapshot to be copied into a managed disk.</span></span></param>
        <param name="sourceResourceId"><span data-ttu-id="f5173-109">Wenn CreateOption Kopie ist, ist dies die ARM-Id der Quellmomentaufnahme oder des Datenträgers an.</span><span class="sxs-lookup"><span data-stu-id="f5173-109">If createOption is Copy, this is the ARM id of the source snapshot or disk.</span></span> <span data-ttu-id="f5173-110">Wenn CreationOption Wiederherstellung ist, ist dies die ARM-ähnliche-Id von der Quelle Datenträger-Wiederherstellungspunkt an.</span><span class="sxs-lookup"><span data-stu-id="f5173-110">If creationOption is Restore, this is the ARM-like id of the source disk restore point.</span></span></param>
        <summary>
            <span data-ttu-id="f5173-111">Initialisiert eine neue Instanz der CreationData-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f5173-111">Initializes a new instance of the CreationData class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption CreateOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption CreateOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.CreateOption" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateOption As DiskCreateOption" />
      <MemberSignature Language="F#" Value="member this.CreateOption : Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.CreateOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5173-112">Ruft ab oder legt folgende Werte möglich sind: "Leer", "Anfügen", "FromImage", "Import", "Kopieren", "Wiederherstellen"</span><span class="sxs-lookup"><span data-stu-id="f5173-112">Gets or sets possible values include: 'Empty', 'Attach', 'FromImage', 'Import', 'Copy', 'Restore'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference ImageReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageReference As ImageDiskReference" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.ImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="imageReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5173-113">Ruft ab, oder legt ihn fest Datenträger Quellinformationen.</span><span class="sxs-lookup"><span data-stu-id="f5173-113">Gets or sets disk source information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceResourceId">
      <MemberSignature Language="C#" Value="public string SourceResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.SourceResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceResourceId As String" />
      <MemberSignature Language="F#" Value="member this.SourceResourceId : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.SourceResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="f5173-114">Ruft ab oder legt fest, ob CreateOption Kopie ist dies ist die ARM-Id der Quellmomentaufnahme oder des Datenträgers.</span><span class="sxs-lookup"><span data-stu-id="f5173-114">Gets or sets if createOption is Copy, this is the ARM id of the source snapshot or disk.</span></span> <span data-ttu-id="f5173-115">Wenn CreationOption Wiederherstellung ist, ist dies die ARM-ähnliche-Id von der Quelle Datenträger-Wiederherstellungspunkt an.</span><span class="sxs-lookup"><span data-stu-id="f5173-115">If creationOption is Restore, this is the ARM-like id of the source disk restore point.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceUri">
      <MemberSignature Language="C#" Value="public string SourceUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.SourceUri" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceUri As String" />
      <MemberSignature Language="F#" Value="member this.SourceUri : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.SourceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="f5173-116">Ruft ab oder legt fest, ob CreationOption Import ist, ist dies eine SAS-URI in ein Blob in einen verwalteten Datenträger importiert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="f5173-116">Gets or sets if creationOption is Import, this is a SAS URI to a blob to be imported into a managed disk.</span></span> <span data-ttu-id="f5173-117">Wenn CreationOption Kopie ist, ist dies ein relativer Uri ist, enthält die Id der Momentaufnahme für die Datenquelle an einen verwalteten Datenträger kopiert werden.</span><span class="sxs-lookup"><span data-stu-id="f5173-117">If creationOption is Copy, this is a relative Uri containing the id of the source snapshot to be copied into a managed disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountId">
      <MemberSignature Language="C#" Value="public string StorageAccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.StorageAccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountId As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountId : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.StorageAccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="f5173-118">Ruft ab, oder legt sie fest, wenn CreateOption importieren, den Azure Resource Manager-Bezeichner des Speicherkontos mit dem Blob als Datenträger importieren.</span><span class="sxs-lookup"><span data-stu-id="f5173-118">Gets or sets if createOption is Import, the Azure Resource Manager identifier of the storage account containing the blob to import as a disk.</span></span> <span data-ttu-id="f5173-119">Nur erforderlich, wenn das Blob in einem anderen Abonnement befindet.</span><span class="sxs-lookup"><span data-stu-id="f5173-119">Required only if the blob is in a different subscription</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="creationData.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f5173-120">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="f5173-120">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f5173-121">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="f5173-121">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>