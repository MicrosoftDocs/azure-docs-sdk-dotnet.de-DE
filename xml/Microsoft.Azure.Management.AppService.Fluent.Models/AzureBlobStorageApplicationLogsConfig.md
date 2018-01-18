<Type Name="AzureBlobStorageApplicationLogsConfig" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig">
  <TypeSignature Language="C#" Value="public class AzureBlobStorageApplicationLogsConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureBlobStorageApplicationLogsConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureBlobStorageApplicationLogsConfig" />
  <TypeSignature Language="F#" Value="type AzureBlobStorageApplicationLogsConfig = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6e634-101">Anwendungsprotokolle Azure-Blob-Speicherkonfiguration.</span><span class="sxs-lookup"><span data-stu-id="6e634-101">Application logs azure blob storage configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobStorageApplicationLogsConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6e634-102">Initialisiert eine neue Instanz der AzureBlobStorageApplicationLogsConfig-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6e634-102">Initializes a new instance of the AzureBlobStorageApplicationLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobStorageApplicationLogsConfig (Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; level = null, string sasUrl = null, Nullable&lt;int&gt; retentionInDays = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; level, string sasUrl, valuetype System.Nullable`1&lt;int32&gt; retentionInDays) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig.#ctor(System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel},System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional level As Nullable(Of LogLevel) = null, Optional sasUrl As String = null, Optional retentionInDays As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig (level, sasUrl, retentionInDays)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="level" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt;" />
        <Parameter Name="sasUrl" Type="System.String" />
        <Parameter Name="retentionInDays" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="level"><span data-ttu-id="6e634-103">Protokollebene.</span><span class="sxs-lookup"><span data-stu-id="6e634-103">Log level.</span></span> <span data-ttu-id="6e634-104">Folgende Werte sind möglich: "Off", "Verbose", "Information", "Warnung", "Fehler"</span><span class="sxs-lookup"><span data-stu-id="6e634-104">Possible values include: 'Off', 'Verbose', 'Information', 'Warning', 'Error'</span></span></param>
        <param name="sasUrl"><span data-ttu-id="6e634-105">SAS-Url zu einem Azure-Blob-Container mit Lese-/Schreibzugriff/Liste/Delete-Berechtigungen.</span><span class="sxs-lookup"><span data-stu-id="6e634-105">SAS url to a azure blob container with read/write/list/delete permissions.</span></span></param>
        <param name="retentionInDays"><span data-ttu-id="6e634-106">Die Beibehaltungsdauer in Tagen.</span><span class="sxs-lookup"><span data-stu-id="6e634-106">Retention in days.</span></span>
            <span data-ttu-id="6e634-107">Entfernen Sie die Blobs, die älter als X Tage.</span><span class="sxs-lookup"><span data-stu-id="6e634-107">Remove blobs older than X days.</span></span>
            <span data-ttu-id="6e634-108">0 oder niedriger bedeutet keine Beibehaltung.</span><span class="sxs-lookup"><span data-stu-id="6e634-108">0 or lower means no retention.</span></span></param>
        <summary>
            <span data-ttu-id="6e634-109">Initialisiert eine neue Instanz der AzureBlobStorageApplicationLogsConfig-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6e634-109">Initializes a new instance of the AzureBlobStorageApplicationLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As Nullable(Of LogLevel)" />
      <MemberSignature Language="F#" Value="member this.Level : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e634-110">Ruft ab, oder legt ihn fest Protokollebene.</span><span class="sxs-lookup"><span data-stu-id="6e634-110">Gets or sets log level.</span></span> <span data-ttu-id="6e634-111">Folgende Werte sind möglich: "Off", "Verbose", "Information", "Warnung", "Fehler"</span><span class="sxs-lookup"><span data-stu-id="6e634-111">Possible values include: 'Off', 'Verbose', 'Information', 'Warning', 'Error'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionInDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionInDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionInDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig.RetentionInDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionInDays As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionInDays : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig.RetentionInDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionInDays")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e634-112">Ruft ab oder legt die Beibehaltungsdauer in Tagen fest.</span><span class="sxs-lookup"><span data-stu-id="6e634-112">Gets or sets retention in days.</span></span>
            <span data-ttu-id="6e634-113">Entfernen Sie die Blobs, die älter als X Tage.</span><span class="sxs-lookup"><span data-stu-id="6e634-113">Remove blobs older than X days.</span></span>
            <span data-ttu-id="6e634-114">0 oder niedriger bedeutet keine Beibehaltung.</span><span class="sxs-lookup"><span data-stu-id="6e634-114">0 or lower means no retention.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasUrl">
      <MemberSignature Language="C#" Value="public string SasUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig.SasUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property SasUrl As String" />
      <MemberSignature Language="F#" Value="member this.SasUrl : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig.SasUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sasUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e634-115">Ruft ab oder legt SAS-Url zu einem Azure-Blob-Container mit Lese-/Schreibzugriff/Liste/Delete-Berechtigungen.</span><span class="sxs-lookup"><span data-stu-id="6e634-115">Gets or sets SAS url to a azure blob container with read/write/list/delete permissions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>