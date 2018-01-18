<Type Name="BackupResourceVaultConfigsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceVaultConfigsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupResourceVaultConfigsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupResourceVaultConfigsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceVaultConfigsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupResourceVaultConfigsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupResourceVaultConfigsOperationsExtensions = class" />
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
            <span data-ttu-id="b5a1f-101">Erweiterungsmethoden für BackupResourceVaultConfigsOperations.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-101">Extension methods for BackupResourceVaultConfigsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations operations, string vaultName, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations operations, string vaultName, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceVaultConfigsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBackupResourceVaultConfigsOperations, vaultName As String, resourceGroupName As String) As BackupResourceVaultConfigResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceVaultConfigsOperationsExtensions.Get (operations, vaultName, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b5a1f-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="b5a1f-103">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b5a1f-104">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5a1f-105">Ruft die Ressourcenkonfiguration Tresor ab.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-105">Fetches resource vault config.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations operations, string vaultName, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations operations, string vaultName, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceVaultConfigsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceVaultConfigsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceVaultConfigsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b5a1f-106">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-106">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="b5a1f-107">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-107">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b5a1f-108">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-108">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5a1f-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5a1f-110">Ruft die Ressourcenkonfiguration Tresor ab.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-110">Fetches resource vault config.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource Update (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations operations, string vaultName, string resourceGroupName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource Update(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations operations, string vaultName, string resourceGroupName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceVaultConfigsOperationsExtensions.Update(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IBackupResourceVaultConfigsOperations, vaultName As String, resourceGroupName As String, parameters As BackupResourceVaultConfigResource) As BackupResourceVaultConfigResource" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceVaultConfigsOperationsExtensions.Update (operations, vaultName, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b5a1f-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-111">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="b5a1f-112">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-112">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b5a1f-113">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-113">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b5a1f-114">konfigurationsanforderungen für die Ressource</span><span class="sxs-lookup"><span data-stu-id="b5a1f-114">resource config request</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5a1f-115">Updates Tresor Sicherheit Config.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-115">Updates vault security config.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource&gt; UpdateAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations operations, string vaultName, string resourceGroupName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource&gt; UpdateAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations operations, string vaultName, string resourceGroupName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceVaultConfigsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceVaultConfigsOperationsExtensions.UpdateAsync (operations, vaultName, resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceVaultConfigsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b5a1f-116">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-116">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="b5a1f-117">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-117">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b5a1f-118">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-118">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b5a1f-119">konfigurationsanforderungen für die Ressource</span><span class="sxs-lookup"><span data-stu-id="b5a1f-119">resource config request</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5a1f-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5a1f-121">Updates Tresor Sicherheit Config.</span><span class="sxs-lookup"><span data-stu-id="b5a1f-121">Updates vault security config.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>