<Type Name="BackupResourceVaultConfig" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig">
  <TypeSignature Language="C#" Value="public class BackupResourceVaultConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupResourceVaultConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupResourceVaultConfig" />
  <TypeSignature Language="F#" Value="type BackupResourceVaultConfig = class" />
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
            Backup-Tresor Config Ressourcendetails.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupResourceVaultConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der BackupResourceVaultConfig-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupResourceVaultConfig (string storageType = null, string storageTypeState = null, string enhancedSecurityState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storageType, string storageTypeState, string enhancedSecurityState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional storageType As String = null, Optional storageTypeState As String = null, Optional enhancedSecurityState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig : string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig (storageType, storageTypeState, enhancedSecurityState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageType" Type="System.String" />
        <Parameter Name="storageTypeState" Type="System.String" />
        <Parameter Name="enhancedSecurityState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageType">Speichertyp. Folgende Werte sind möglich: "Ungültig", "GeoRedundant", "LocallyRedundant"</param>
        <param name="storageTypeState">Gesperrt oder entsperrt. Sobald ein Computer für eine Ressource registriert wurde, wird die StorageTypeState immer gesperrt. Folgende Werte sind möglich: "Ungültig", "Gesperrt", "Gesperrt"</param>
        <param name="enhancedSecurityState">Aktiviert oder deaktiviert. Folgende Werte sind möglich: "Ungültig", "Aktiviert", "Deaktiviert"</param>
        <summary>
            Initialisiert eine neue Instanz der BackupResourceVaultConfig-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnhancedSecurityState">
      <MemberSignature Language="C#" Value="public string EnhancedSecurityState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EnhancedSecurityState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig.EnhancedSecurityState" />
      <MemberSignature Language="VB.NET" Value="Public Property EnhancedSecurityState As String" />
      <MemberSignature Language="F#" Value="member this.EnhancedSecurityState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig.EnhancedSecurityState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enhancedSecurityState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie fest, aktiviert oder deaktiviert. Folgende Werte sind möglich: "Ungültig", "Aktiviert", "Deaktiviert"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageType">
      <MemberSignature Language="C#" Value="public string StorageType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig.StorageType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageType As String" />
      <MemberSignature Language="F#" Value="member this.StorageType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig.StorageType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Speicher. Folgende Werte sind möglich: "Ungültig", "GeoRedundant", "LocallyRedundant"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageTypeState">
      <MemberSignature Language="C#" Value="public string StorageTypeState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageTypeState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig.StorageTypeState" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageTypeState As String" />
      <MemberSignature Language="F#" Value="member this.StorageTypeState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig.StorageTypeState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageTypeState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, gesperrt oder entsperrt. Sobald ein Computer für eine Ressource registriert wurde, wird die StorageTypeState immer gesperrt. Folgende Werte sind möglich: "Ungültig", "Gesperrt", "Gesperrt"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>