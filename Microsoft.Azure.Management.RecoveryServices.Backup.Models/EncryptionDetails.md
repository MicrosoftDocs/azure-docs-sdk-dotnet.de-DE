<Type Name="EncryptionDetails" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails">
  <TypeSignature Language="C#" Value="public class EncryptionDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EncryptionDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class EncryptionDetails" />
  <TypeSignature Language="F#" Value="type EncryptionDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Details erforderlich, wenn die VM zum Zeitpunkt der Sicherung verschlüsselt wurde.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der EncryptionDetails-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionDetails (Nullable&lt;bool&gt; encryptionEnabled = null, string kekUrl = null, string secretKeyUrl = null, string kekVaultId = null, string secretKeyVaultId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; encryptionEnabled, string kekUrl, string secretKeyUrl, string kekVaultId, string secretKeyVaultId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails.#ctor(System.Nullable{System.Boolean},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional encryptionEnabled As Nullable(Of Boolean) = null, Optional kekUrl As String = null, Optional secretKeyUrl As String = null, Optional kekVaultId As String = null, Optional secretKeyVaultId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails : Nullable&lt;bool&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails (encryptionEnabled, kekUrl, secretKeyUrl, kekVaultId, secretKeyVaultId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="encryptionEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="kekUrl" Type="System.String" />
        <Parameter Name="secretKeyUrl" Type="System.String" />
        <Parameter Name="kekVaultId" Type="System.String" />
        <Parameter Name="secretKeyVaultId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="encryptionEnabled">Bestimmt, ob dieser Sicherungskopie zum Zeitpunkt der Sicherung ein verschlüsselten virtuellen Computers darstellt.</param>
        <param name="kekUrl">Key-Url.</param>
        <param name="secretKeyUrl">Für den geheimen Url.</param>
        <param name="kekVaultId">ID des Key Vault, in dem KEK gespeichert ist.</param>
        <param name="secretKeyVaultId">ID des Key Vault, in dem geheime Schlüssel gespeichert ist.</param>
        <summary>
            Initialisiert eine neue Instanz der EncryptionDetails-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EncryptionEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EncryptionEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails.EncryptionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EncryptionEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails.EncryptionEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encryptionEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt identifiziert, ob dieser Sicherungskopie zum Zeitpunkt der Sicherung ein verschlüsselten virtuellen Computers darstellt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KekUrl">
      <MemberSignature Language="C#" Value="public string KekUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KekUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails.KekUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property KekUrl As String" />
      <MemberSignature Language="F#" Value="member this.KekUrl : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails.KekUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kekUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Url-Taste, ruft ab oder legt ihn fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KekVaultId">
      <MemberSignature Language="C#" Value="public string KekVaultId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KekVaultId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails.KekVaultId" />
      <MemberSignature Language="VB.NET" Value="Public Property KekVaultId As String" />
      <MemberSignature Language="F#" Value="member this.KekVaultId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails.KekVaultId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kekVaultId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-ID des Key Vault, in dem KEK gespeichert ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretKeyUrl">
      <MemberSignature Language="C#" Value="public string SecretKeyUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretKeyUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails.SecretKeyUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretKeyUrl As String" />
      <MemberSignature Language="F#" Value="member this.SecretKeyUrl : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails.SecretKeyUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secretKeyUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Url für den geheimen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretKeyVaultId">
      <MemberSignature Language="C#" Value="public string SecretKeyVaultId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretKeyVaultId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails.SecretKeyVaultId" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretKeyVaultId As String" />
      <MemberSignature Language="F#" Value="member this.SecretKeyVaultId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails.SecretKeyVaultId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secretKeyVaultId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ID des Key Vault, in dem geheime Schlüssel gespeichert ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>