<Type Name="KEKDetails" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails">
  <TypeSignature Language="C#" Value="public class KEKDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KEKDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class KEKDetails" />
  <TypeSignature Language="F#" Value="type KEKDetails = class" />
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
            KEK ist Verschlüsselungsschlüssel für BEK.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KEKDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der KEKDetails-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KEKDetails (string keyUrl = null, string keyVaultId = null, string keyBackupData = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyUrl, string keyVaultId, string keyBackupData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional keyUrl As String = null, Optional keyVaultId As String = null, Optional keyBackupData As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails : string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails (keyUrl, keyVaultId, keyBackupData)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyUrl" Type="System.String" />
        <Parameter Name="keyVaultId" Type="System.String" />
        <Parameter Name="keyBackupData" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyUrl">Der Schlüssel ist KEK.</param>
        <param name="keyVaultId">Key Vault-ID, in dem dieser Schlüssel gespeichert ist.</param>
        <param name="keyBackupData">KEK-Daten.</param>
        <summary>
            Initialisiert eine neue Instanz der KEKDetails-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyBackupData">
      <MemberSignature Language="C#" Value="public string KeyBackupData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyBackupData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails.KeyBackupData" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyBackupData As String" />
      <MemberSignature Language="F#" Value="member this.KeyBackupData : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails.KeyBackupData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyBackupData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest KEK-Daten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyUrl">
      <MemberSignature Language="C#" Value="public string KeyUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails.KeyUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyUrl As String" />
      <MemberSignature Language="F#" Value="member this.KeyUrl : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails.KeyUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Schlüssel ist KEK.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultId">
      <MemberSignature Language="C#" Value="public string KeyVaultId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails.KeyVaultId" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultId As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails.KeyVaultId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyVaultId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Key Vault-ID, in dem dieser Schlüssel gespeichert ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>