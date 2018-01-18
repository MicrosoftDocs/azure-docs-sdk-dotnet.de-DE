<Type Name="AzureBlobStorageHttpLogsConfig" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig">
  <TypeSignature Language="C#" Value="public class AzureBlobStorageHttpLogsConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureBlobStorageHttpLogsConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureBlobStorageHttpLogsConfig" />
  <TypeSignature Language="F#" Value="type AzureBlobStorageHttpLogsConfig = class" />
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
            <span data-ttu-id="32cbc-101">HTTP-Protokolle auf Azure-Blob-Speicherkonfiguration.</span><span class="sxs-lookup"><span data-stu-id="32cbc-101">Http logs to azure blob storage configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobStorageHttpLogsConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="32cbc-102">Initialisiert eine neue Instanz der AzureBlobStorageHttpLogsConfig-Klasse.</span><span class="sxs-lookup"><span data-stu-id="32cbc-102">Initializes a new instance of the AzureBlobStorageHttpLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobStorageHttpLogsConfig (string sasUrl = null, Nullable&lt;int&gt; retentionInDays = null, Nullable&lt;bool&gt; enabled = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sasUrl, valuetype System.Nullable`1&lt;int32&gt; retentionInDays, valuetype System.Nullable`1&lt;bool&gt; enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional sasUrl As String = null, Optional retentionInDays As Nullable(Of Integer) = null, Optional enabled As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig : string * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig (sasUrl, retentionInDays, enabled)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sasUrl" Type="System.String" />
        <Parameter Name="retentionInDays" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="sasUrl"><span data-ttu-id="32cbc-103">SAS-Url zu einem Azure-Blob-Container mit Lese-/Schreibzugriff/Liste/Delete-Berechtigungen.</span><span class="sxs-lookup"><span data-stu-id="32cbc-103">SAS url to a azure blob container with read/write/list/delete permissions.</span></span></param>
        <param name="retentionInDays"><span data-ttu-id="32cbc-104">Die Beibehaltungsdauer in Tagen.</span><span class="sxs-lookup"><span data-stu-id="32cbc-104">Retention in days.</span></span>
            <span data-ttu-id="32cbc-105">Entfernen Sie die Blobs, die älter als X Tage.</span><span class="sxs-lookup"><span data-stu-id="32cbc-105">Remove blobs older than X days.</span></span>
            <span data-ttu-id="32cbc-106">0 oder niedriger bedeutet keine Beibehaltung.</span><span class="sxs-lookup"><span data-stu-id="32cbc-106">0 or lower means no retention.</span></span></param>
        <param name="enabled"><span data-ttu-id="32cbc-107">Aktiviert.</span><span class="sxs-lookup"><span data-stu-id="32cbc-107">Enabled.</span></span></param>
        <summary>
            <span data-ttu-id="32cbc-108">Initialisiert eine neue Instanz der AzureBlobStorageHttpLogsConfig-Klasse.</span><span class="sxs-lookup"><span data-stu-id="32cbc-108">Initializes a new instance of the AzureBlobStorageHttpLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="32cbc-109">Ruft ab oder legt ihn fest, die aktiviert.</span><span class="sxs-lookup"><span data-stu-id="32cbc-109">Gets or sets enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionInDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionInDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionInDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig.RetentionInDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionInDays As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionInDays : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig.RetentionInDays" />
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
            <span data-ttu-id="32cbc-110">Ruft ab oder legt die Beibehaltungsdauer in Tagen fest.</span><span class="sxs-lookup"><span data-stu-id="32cbc-110">Gets or sets retention in days.</span></span>
            <span data-ttu-id="32cbc-111">Entfernen Sie die Blobs, die älter als X Tage.</span><span class="sxs-lookup"><span data-stu-id="32cbc-111">Remove blobs older than X days.</span></span>
            <span data-ttu-id="32cbc-112">0 oder niedriger bedeutet keine Beibehaltung.</span><span class="sxs-lookup"><span data-stu-id="32cbc-112">0 or lower means no retention.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasUrl">
      <MemberSignature Language="C#" Value="public string SasUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig.SasUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property SasUrl As String" />
      <MemberSignature Language="F#" Value="member this.SasUrl : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig.SasUrl" />
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
            <span data-ttu-id="32cbc-113">Ruft ab oder legt SAS-Url zu einem Azure-Blob-Container mit Lese-/Schreibzugriff/Liste/Delete-Berechtigungen.</span><span class="sxs-lookup"><span data-stu-id="32cbc-113">Gets or sets SAS url to a azure blob container with read/write/list/delete permissions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>