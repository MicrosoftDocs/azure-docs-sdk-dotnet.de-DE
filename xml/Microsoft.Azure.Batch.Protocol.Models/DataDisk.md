<Type Name="DataDisk" FullName="Microsoft.Azure.Batch.Protocol.Models.DataDisk">
  <TypeSignature Language="C#" Value="public class DataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.DataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class DataDisk" />
  <TypeSignature Language="F#" Value="type DataDisk = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e718f-101">Einstellungen auf, die von den Datenträgern zugeordnet, um die Serverknoten im Pool verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="e718f-101">Settings which will be used by the data disks associated to compute nodes in the pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.DataDisk.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e718f-102">Initialisiert eine neue Instanz der DataDisk-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e718f-102">Initializes a new instance of the DataDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisk (int lun, int diskSizeGB, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; caching = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.StorageAccountType&gt; storageAccountType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 lun, int32 diskSizeGB, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; caching, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.StorageAccountType&gt; storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.DataDisk.#ctor(System.Int32,System.Int32,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.CachingType},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.StorageAccountType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (lun As Integer, diskSizeGB As Integer, Optional caching As Nullable(Of CachingType) = null, Optional storageAccountType As Nullable(Of StorageAccountType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.DataDisk : int * int * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.StorageAccountType&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.DataDisk" Usage="new Microsoft.Azure.Batch.Protocol.Models.DataDisk (lun, diskSizeGB, caching, storageAccountType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="diskSizeGB" Type="System.Int32" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt;" />
        <Parameter Name="storageAccountType" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.StorageAccountType&gt;" />
      </Parameters>
      <Docs>
        <param name="lun"><span data-ttu-id="e718f-103">Die logische Gerätenummer.</span><span class="sxs-lookup"><span data-stu-id="e718f-103">The logical unit number.</span></span></param>
        <param name="diskSizeGB"><span data-ttu-id="e718f-104">Die ursprüngliche Datenträgergröße in Gigabyte.</span><span class="sxs-lookup"><span data-stu-id="e718f-104">The initial disk size in gigabytes.</span></span></param>
        <param name="caching"><span data-ttu-id="e718f-105">Der Typ des Zwischenspeichern konfigurieren, um für die Datenträger für Daten aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="e718f-105">The type of caching to be enabled for the data disks.</span></span></param>
        <param name="storageAccountType"><span data-ttu-id="e718f-106">Der speicherkontotyp für den Datenträger verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="e718f-106">The storage account type to be used for the data disk.</span></span></param>
        <summary>
            <span data-ttu-id="e718f-107">Initialisiert eine neue Instanz der DataDisk-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e718f-107">Initializes a new instance of the DataDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.DataDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingType)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.DataDisk.Caching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="caching")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e718f-108">Ruft ab oder legt den Typ des Zwischenspeichern konfigurieren, um für die Datenträger für Daten aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="e718f-108">Gets or sets the type of caching to be enabled for the data disks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e718f-109">Der Standardwert für das caching ist none.</span><span class="sxs-lookup"><span data-stu-id="e718f-109">The default value for caching is none.</span></span> <span data-ttu-id="e718f-110">Weitere Informationen zu Optionen für die Zwischenspeicherung finden Sie unter: https://blogs.msdn.microsoft.com/windowsazurestorage/2012/06/27/exploring-windows-azure-drives-disks-and-images/.</span><span class="sxs-lookup"><span data-stu-id="e718f-110">For information about the caching options see: https://blogs.msdn.microsoft.com/windowsazurestorage/2012/06/27/exploring-windows-azure-drives-disks-and-images/.</span></span>
            <span data-ttu-id="e718f-111">Folgende Werte sind möglich: "none", "ReadOnly", "ReadWrite"</span><span class="sxs-lookup"><span data-stu-id="e718f-111">Possible values include: 'none', 'readOnly', 'readWrite'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public int DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.DataDisk.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Integer" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.DataDisk.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskSizeGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e718f-112">Ruft ab oder legt die anfängliche Größe in Gigabyte.</span><span class="sxs-lookup"><span data-stu-id="e718f-112">Gets or sets the initial disk size in gigabytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lun">
      <MemberSignature Language="C#" Value="public int Lun { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Lun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.DataDisk.Lun" />
      <MemberSignature Language="VB.NET" Value="Public Property Lun As Integer" />
      <MemberSignature Language="F#" Value="member this.Lun : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.DataDisk.Lun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e718f-113">Ruft ab oder legt die Anzahl der logischen Einheit.</span><span class="sxs-lookup"><span data-stu-id="e718f-113">Gets or sets the logical unit number.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e718f-114">Die Lun dient zur eindeutigen Identifizierung jeder Datenträger.</span><span class="sxs-lookup"><span data-stu-id="e718f-114">The lun is used to uniquely identify each data disk.</span></span> <span data-ttu-id="e718f-115">Wenn mehrere Datenträger anfügen zu können, muss eine unterschiedliche Lun aufweisen.</span><span class="sxs-lookup"><span data-stu-id="e718f-115">If attaching multiple disks, each should have a distinct lun.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.StorageAccountType&gt; StorageAccountType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.StorageAccountType&gt; StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.DataDisk.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountType As Nullable(Of StorageAccountType)" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.StorageAccountType&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.DataDisk.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.StorageAccountType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e718f-116">Abrufen oder Festlegen der speicherkontotyp für den Datenträger verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="e718f-116">Gets or sets the storage account type to be used for the data disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e718f-117">Wenn nicht angegeben, ist die Standardeinstellung "Standard_lrs".</span><span class="sxs-lookup"><span data-stu-id="e718f-117">If omitted, the default is "standard_lrs".</span></span> <span data-ttu-id="e718f-118">Folgende Werte sind möglich: "StandardLRS", "PremiumLRS"</span><span class="sxs-lookup"><span data-stu-id="e718f-118">Possible values include: 'StandardLRS', 'PremiumLRS'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.DataDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataDisk.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e718f-119">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="e718f-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e718f-120">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="e718f-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>