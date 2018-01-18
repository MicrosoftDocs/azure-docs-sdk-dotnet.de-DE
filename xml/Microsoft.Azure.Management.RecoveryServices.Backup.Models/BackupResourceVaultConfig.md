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
            <span data-ttu-id="cdf2e-101">Backup-Tresor Config Ressourcendetails.</span><span class="sxs-lookup"><span data-stu-id="cdf2e-101">Backup resource vault config details.</span></span>
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
            <span data-ttu-id="cdf2e-102">Initialisiert eine neue Instanz der BackupResourceVaultConfig-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cdf2e-102">Initializes a new instance of the BackupResourceVaultConfig class.</span></span>
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
        <param name="storageType"><span data-ttu-id="cdf2e-103">Speichertyp.</span><span class="sxs-lookup"><span data-stu-id="cdf2e-103">Storage type.</span></span> <span data-ttu-id="cdf2e-104">Folgende Werte sind möglich: "Ungültig", "GeoRedundant", "LocallyRedundant"</span><span class="sxs-lookup"><span data-stu-id="cdf2e-104">Possible values include: 'Invalid', 'GeoRedundant', 'LocallyRedundant'</span></span></param>
        <param name="storageTypeState"><span data-ttu-id="cdf2e-105">Gesperrt oder entsperrt.</span><span class="sxs-lookup"><span data-stu-id="cdf2e-105">Locked or Unlocked.</span></span> <span data-ttu-id="cdf2e-106">Sobald ein Computer für eine Ressource registriert wurde, wird die StorageTypeState immer gesperrt.</span><span class="sxs-lookup"><span data-stu-id="cdf2e-106">Once a machine is registered against a resource, the storageTypeState is always Locked.</span></span> <span data-ttu-id="cdf2e-107">Folgende Werte sind möglich: "Ungültig", "Gesperrt", "Gesperrt"</span><span class="sxs-lookup"><span data-stu-id="cdf2e-107">Possible values include: 'Invalid', 'Locked', 'Unlocked'</span></span></param>
        <param name="enhancedSecurityState"><span data-ttu-id="cdf2e-108">Aktiviert oder deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="cdf2e-108">Enabled or Disabled.</span></span> <span data-ttu-id="cdf2e-109">Folgende Werte sind möglich: "Ungültig", "Aktiviert", "Deaktiviert"</span><span class="sxs-lookup"><span data-stu-id="cdf2e-109">Possible values include: 'Invalid', 'Enabled', 'Disabled'</span></span></param>
        <summary>
            <span data-ttu-id="cdf2e-110">Initialisiert eine neue Instanz der BackupResourceVaultConfig-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cdf2e-110">Initializes a new instance of the BackupResourceVaultConfig class.</span></span>
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
            <span data-ttu-id="cdf2e-111">Ruft ab, oder legt sie fest, aktiviert oder deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="cdf2e-111">Gets or sets enabled or Disabled.</span></span> <span data-ttu-id="cdf2e-112">Folgende Werte sind möglich: "Ungültig", "Aktiviert", "Deaktiviert"</span><span class="sxs-lookup"><span data-stu-id="cdf2e-112">Possible values include: 'Invalid', 'Enabled', 'Disabled'</span></span>
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
            <span data-ttu-id="cdf2e-113">Ruft ab oder legt ihn fest Speicher.</span><span class="sxs-lookup"><span data-stu-id="cdf2e-113">Gets or sets storage type.</span></span> <span data-ttu-id="cdf2e-114">Folgende Werte sind möglich: "Ungültig", "GeoRedundant", "LocallyRedundant"</span><span class="sxs-lookup"><span data-stu-id="cdf2e-114">Possible values include: 'Invalid', 'GeoRedundant', 'LocallyRedundant'</span></span>
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
            <span data-ttu-id="cdf2e-115">Ruft ab oder legt sie fest, gesperrt oder entsperrt.</span><span class="sxs-lookup"><span data-stu-id="cdf2e-115">Gets or sets locked or Unlocked.</span></span> <span data-ttu-id="cdf2e-116">Sobald ein Computer für eine Ressource registriert wurde, wird die StorageTypeState immer gesperrt.</span><span class="sxs-lookup"><span data-stu-id="cdf2e-116">Once a machine is registered against a resource, the storageTypeState is always Locked.</span></span> <span data-ttu-id="cdf2e-117">Folgende Werte sind möglich: "Ungültig", "Gesperrt", "Gesperrt"</span><span class="sxs-lookup"><span data-stu-id="cdf2e-117">Possible values include: 'Invalid', 'Locked', 'Unlocked'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>