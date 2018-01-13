<Type Name="VolumeContainer" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer">
  <TypeSignature Language="C#" Value="public class VolumeContainer : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VolumeContainer extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" />
  <TypeSignature Language="VB.NET" Value="Public Class VolumeContainer&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type VolumeContainer = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Der volumecontainer.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VolumeContainer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Anmeldedatenobjekt-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VolumeContainer (string storageAccountCredentialId, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret encryptionKey = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus&gt; encryptionStatus = null, Nullable&lt;int&gt; volumeCount = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OwnerShipStatus&gt; ownerShipStatus = null, Nullable&lt;int&gt; bandWidthRateInMbps = null, string bandwidthSettingId = null, Nullable&lt;long&gt; totalCloudStorageUsageInBytes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storageAccountCredentialId, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret encryptionKey, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus&gt; encryptionStatus, valuetype System.Nullable`1&lt;int32&gt; volumeCount, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.OwnerShipStatus&gt; ownerShipStatus, valuetype System.Nullable`1&lt;int32&gt; bandWidthRateInMbps, string bandwidthSettingId, valuetype System.Nullable`1&lt;int64&gt; totalCloudStorageUsageInBytes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.#ctor(System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.OwnerShipStatus},System.Nullable{System.Int32},System.String,System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccountCredentialId As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null, Optional encryptionKey As AsymmetricEncryptedSecret = null, Optional encryptionStatus As Nullable(Of EncryptionStatus) = null, Optional volumeCount As Nullable(Of Integer) = null, Optional ownerShipStatus As Nullable(Of OwnerShipStatus) = null, Optional bandWidthRateInMbps As Nullable(Of Integer) = null, Optional bandwidthSettingId As String = null, Optional totalCloudStorageUsageInBytes As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer : string * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OwnerShipStatus&gt; * Nullable&lt;int&gt; * string * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer (storageAccountCredentialId, id, name, type, kind, encryptionKey, encryptionStatus, volumeCount, ownerShipStatus, bandWidthRateInMbps, bandwidthSettingId, totalCloudStorageUsageInBytes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccountCredentialId" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="encryptionKey" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" />
        <Parameter Name="encryptionStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus&gt;" />
        <Parameter Name="volumeCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="ownerShipStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OwnerShipStatus&gt;" />
        <Parameter Name="bandWidthRateInMbps" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="bandwidthSettingId" Type="System.String" />
        <Parameter Name="totalCloudStorageUsageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="storageAccountCredentialId">Die Pfad-ID des Speicherkontos, das dem volumecontainer zugeordnet werden soll.</param>
        <param name="id">Die Pfad-ID, die das Objekt eindeutig identifiziert.</param>
        <param name="name">Der Name des Objekts.</param>
        <param name="type">Der hierarchische Typ des Objekts.</param>
        <param name="kind">Die Art des Objekts. Derzeit wird nur Series8000 wird unterstützt. Folgende Werte sind möglich: "Series8000"</param>
        <param name="encryptionKey">Der Schlüssel zum Verschlüsseln von Daten in der Volume-Container. Es ist erforderlich, wenn die Eigenschaft "EncryptionStatus" "aktiviert" ist.</param>
        <param name="encryptionStatus">Das Flag zur Angabe, ob Verschlüsselung oder nicht aktiviert ist. Folgende Werte sind möglich: "Enabled", "Disabled"</param>
        <param name="volumeCount">Die Anzahl der Volumes im Volume-Container.</param>
        <param name="ownerShipStatus">Der Besitzer Ship Status der Volume-Container. Nur, wenn der Status "NotOwned" lautet, ist der Löschvorgang auf dem volumecontainer zulässig. Folgende Werte sind möglich: "Besitzer", "NotOwned"</param>
        <param name="bandWidthRateInMbps">Die Bandbreite-Rate auf dem volumecontainer festgelegt.</param>
        <param name="bandwidthSettingId">Die ID der bandbreiteneinstellung für die der Volume-Container zugeordnet werden soll.</param>
        <param name="totalCloudStorageUsageInBytes">Den gesamten cloudspeicher für den volumecontainer.</param>
        <summary>
            Initialisiert eine neue Instanz der Anmeldedatenobjekt-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BandWidthRateInMbps">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BandWidthRateInMbps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BandWidthRateInMbps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.BandWidthRateInMbps" />
      <MemberSignature Language="VB.NET" Value="Public Property BandWidthRateInMbps As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BandWidthRateInMbps : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.BandWidthRateInMbps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.bandWidthRateInMbps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Bandbreitenrate, auf dem volumecontainer festgelegt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BandwidthSettingId">
      <MemberSignature Language="C#" Value="public string BandwidthSettingId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BandwidthSettingId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.BandwidthSettingId" />
      <MemberSignature Language="VB.NET" Value="Public Property BandwidthSettingId As String" />
      <MemberSignature Language="F#" Value="member this.BandwidthSettingId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.BandwidthSettingId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.bandwidthSettingId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ID der bandbreiteneinstellung für die der Volume-Container zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret EncryptionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret EncryptionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.EncryptionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionKey As AsymmetricEncryptedSecret" />
      <MemberSignature Language="F#" Value="member this.EncryptionKey : Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.EncryptionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Schlüssel zum Verschlüsseln von Daten in der Volume-Container fest.
            Es ist erforderlich, wenn die Eigenschaft "EncryptionStatus" "aktiviert" ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus&gt; EncryptionStatus { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus&gt; EncryptionStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.EncryptionStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionStatus As Nullable(Of EncryptionStatus)" />
      <MemberSignature Language="F#" Value="member this.EncryptionStatus : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.EncryptionStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Flag zur Angabe, ob Verschlüsselung oder nicht aktiviert ist.
            Folgende Werte sind möglich: "Enabled", "Disabled"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OwnerShipStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OwnerShipStatus&gt; OwnerShipStatus { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.OwnerShipStatus&gt; OwnerShipStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.OwnerShipStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property OwnerShipStatus As Nullable(Of OwnerShipStatus)" />
      <MemberSignature Language="F#" Value="member this.OwnerShipStatus : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OwnerShipStatus&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.OwnerShipStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ownerShipStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OwnerShipStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Besitzer Status des volumecontainers ausgeliefert. Nur, wenn der Status "NotOwned" lautet, ist der Löschvorgang auf dem volumecontainer zulässig. Folgende Werte sind möglich: "Besitzer", "NotOwned"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountCredentialId">
      <MemberSignature Language="C#" Value="public string StorageAccountCredentialId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountCredentialId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.StorageAccountCredentialId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountCredentialId As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountCredentialId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.StorageAccountCredentialId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccountCredentialId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Pfad-ID des Speicherkontos, das dem volumecontainer zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCloudStorageUsageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; TotalCloudStorageUsageInBytes { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; TotalCloudStorageUsageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.TotalCloudStorageUsageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalCloudStorageUsageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.TotalCloudStorageUsageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.TotalCloudStorageUsageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.totalCloudStorageUsageInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den gesamten cloudspeicher für den volumecontainer an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="volumeContainer.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VolumeCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; VolumeCount { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; VolumeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.VolumeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.VolumeCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer.VolumeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.volumeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Volumes im Volume-Container.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>