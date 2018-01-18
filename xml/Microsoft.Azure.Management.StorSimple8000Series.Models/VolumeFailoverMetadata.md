<Type Name="VolumeFailoverMetadata" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata">
  <TypeSignature Language="C#" Value="public class VolumeFailoverMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VolumeFailoverMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata" />
  <TypeSignature Language="VB.NET" Value="Public Class VolumeFailoverMetadata" />
  <TypeSignature Language="F#" Value="type VolumeFailoverMetadata = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f0d2f-101">Die Metadaten von einem Volume, das gültige verfügt über cloud-Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-101">The metadata of a volume that has valid cloud snapshot.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VolumeFailoverMetadata ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f0d2f-102">Initialisiert eine neue Instanz der VolumeFailoverMetadata-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-102">Initializes a new instance of the VolumeFailoverMetadata class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VolumeFailoverMetadata (string volumeId = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType&gt; volumeType = null, Nullable&lt;long&gt; sizeInBytes = null, Nullable&lt;DateTime&gt; backupCreatedDate = null, string backupElementId = null, string backupId = null, string backupPolicyId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string volumeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType&gt; volumeType, valuetype System.Nullable`1&lt;int64&gt; sizeInBytes, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; backupCreatedDate, string backupElementId, string backupId, string backupPolicyId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType},System.Nullable{System.Int64},System.Nullable{System.DateTime},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional volumeId As String = null, Optional volumeType As Nullable(Of VolumeType) = null, Optional sizeInBytes As Nullable(Of Long) = null, Optional backupCreatedDate As Nullable(Of DateTime) = null, Optional backupElementId As String = null, Optional backupId As String = null, Optional backupPolicyId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata : string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType&gt; * Nullable&lt;int64&gt; * Nullable&lt;DateTime&gt; * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata (volumeId, volumeType, sizeInBytes, backupCreatedDate, backupElementId, backupId, backupPolicyId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="volumeId" Type="System.String" />
        <Parameter Name="volumeType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType&gt;" />
        <Parameter Name="sizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="backupCreatedDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="backupElementId" Type="System.String" />
        <Parameter Name="backupId" Type="System.String" />
        <Parameter Name="backupPolicyId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="volumeId"><span data-ttu-id="f0d2f-103">Die Pfad-ID des Volumes.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-103">The path ID of the volume.</span></span></param>
        <param name="volumeType"><span data-ttu-id="f0d2f-104">Der Typ des Volumes.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-104">The type of the volume.</span></span> <span data-ttu-id="f0d2f-105">Folgende Werte sind möglich: "Mehrstufigen", "Archivierung", "LocallyPinned"</span><span class="sxs-lookup"><span data-stu-id="f0d2f-105">Possible values include: 'Tiered', 'Archival', 'LocallyPinned'</span></span></param>
        <param name="sizeInBytes"><span data-ttu-id="f0d2f-106">Die Größe des Volumes in Bytes, die zum Zeitpunkt wurde der Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-106">The size of the volume in bytes at the time the snapshot was taken.</span></span></param>
        <param name="backupCreatedDate"><span data-ttu-id="f0d2f-107">Das Datum, an dem die Momentaufnahme erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-107">The date at which the snapshot was taken.</span></span></param>
        <param name="backupElementId"><span data-ttu-id="f0d2f-108">Die Pfad-ID, der das Backup-Element für dieses Volume, in den Sicherungssatz eingeschlossen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-108">The path ID of the backup-element for this volume, inside the backup set.</span></span></param>
        <param name="backupId"><span data-ttu-id="f0d2f-109">Die Pfad-ID, der den Sicherungssatz eingeschlossen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-109">The path ID of the backup set.</span></span></param>
        <param name="backupPolicyId"><span data-ttu-id="f0d2f-110">Die Pfad-ID der Sicherungsrichtlinie mit dem die Momentaufnahme erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-110">The path ID of the backup policy using which the snapshot was taken.</span></span></param>
        <summary>
            <span data-ttu-id="f0d2f-111">Initialisiert eine neue Instanz der VolumeFailoverMetadata-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-111">Initializes a new instance of the VolumeFailoverMetadata class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupCreatedDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; BackupCreatedDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; BackupCreatedDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata.BackupCreatedDate" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupCreatedDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.BackupCreatedDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata.BackupCreatedDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupCreatedDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0d2f-112">Ruft ab oder legt das Datum, an dem die Momentaufnahme erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-112">Gets or sets the date at which the snapshot was taken.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupElementId">
      <MemberSignature Language="C#" Value="public string BackupElementId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupElementId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata.BackupElementId" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupElementId As String" />
      <MemberSignature Language="F#" Value="member this.BackupElementId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata.BackupElementId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupElementId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0d2f-113">Ruft ab oder legt die Pfad-ID von der Backup-Element für dieses Volume, in dem Sicherungssatz fest.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-113">Gets or sets the path ID of the backup-element for this volume, inside the backup set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupId">
      <MemberSignature Language="C#" Value="public string BackupId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata.BackupId" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupId As String" />
      <MemberSignature Language="F#" Value="member this.BackupId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata.BackupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0d2f-114">Ruft ab oder legt die Pfad-ID des Sicherungssatzes.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-114">Gets or sets the path ID of the backup set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicyId">
      <MemberSignature Language="C#" Value="public string BackupPolicyId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupPolicyId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata.BackupPolicyId" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupPolicyId As String" />
      <MemberSignature Language="F#" Value="member this.BackupPolicyId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata.BackupPolicyId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupPolicyId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0d2f-115">Ruft ab oder legt die Pfad-ID der Sicherungsrichtlinie mit dem die Momentaufnahme erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-115">Gets or sets the path ID of the backup policy using which the snapshot was taken.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property SizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sizeInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0d2f-116">Ruft ab oder legt die Größe des Volumes in Bytes fest, die zum Zeitpunkt der Momentaufnahme befunden hat.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-116">Gets or sets the size of the volume in bytes at the time the snapshot was taken.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeId">
      <MemberSignature Language="C#" Value="public string VolumeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VolumeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata.VolumeId" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeId As String" />
      <MemberSignature Language="F#" Value="member this.VolumeId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata.VolumeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="volumeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0d2f-117">Ruft ab oder legt die Pfad-ID des Volumes.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-117">Gets or sets the path ID of the volume.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType&gt; VolumeType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType&gt; VolumeType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata.VolumeType" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeType As Nullable(Of VolumeType)" />
      <MemberSignature Language="F#" Value="member this.VolumeType : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata.VolumeType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="volumeType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0d2f-118">Ruft ab oder legt den Typ des Volumes fest.</span><span class="sxs-lookup"><span data-stu-id="f0d2f-118">Gets or sets the type of the volume.</span></span> <span data-ttu-id="f0d2f-119">Folgende Werte sind möglich: "Mehrstufigen", "Archivierung", "LocallyPinned"</span><span class="sxs-lookup"><span data-stu-id="f0d2f-119">Possible values include: 'Tiered', 'Archival', 'LocallyPinned'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>