<Type Name="VaultCertificatesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.VaultCertificatesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VaultCertificatesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VaultCertificatesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.VaultCertificatesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VaultCertificatesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VaultCertificatesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f8b9e-101">Erweiterungsmethoden für VaultCertificatesOperations.</span><span class="sxs-lookup"><span data-stu-id="f8b9e-101">Extension methods for VaultCertificatesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Models.VaultCertificateResponse Create (this Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations operations, string resourceGroupName, string vaultName, string certificateName, Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest certificateRequest);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Models.VaultCertificateResponse Create(class Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations operations, string resourceGroupName, string vaultName, string certificateName, class Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest certificateRequest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultCertificatesOperationsExtensions.Create(Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations * string * string * string * Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest -&gt; Microsoft.Azure.Management.RecoveryServices.Models.VaultCertificateResponse" Usage="Microsoft.Azure.Management.RecoveryServices.VaultCertificatesOperationsExtensions.Create (operations, resourceGroupName, vaultName, certificateName, certificateRequest)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.VaultCertificateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateRequest" Type="Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8b9e-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f8b9e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f8b9e-103">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="f8b9e-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="f8b9e-104">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="f8b9e-104">The name of the recovery services vault.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f8b9e-105">Anzeigename des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="f8b9e-105">Certificate friendly name.</span></span>
            </param>
        <param name="certificateRequest">
            <span data-ttu-id="f8b9e-106">Die Eingabeparameter für das Hochladen des Zertifikats Tresor.</span><span class="sxs-lookup"><span data-stu-id="f8b9e-106">Input parameters for uploading the vault certificate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8b9e-107">Hochladen eines Zertifikats für eine Ressource an.</span><span class="sxs-lookup"><span data-stu-id="f8b9e-107">Upload a certificate for a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultCertificateResponse&gt; CreateAsync (this Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations operations, string resourceGroupName, string vaultName, string certificateName, Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest certificateRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.VaultCertificateResponse&gt; CreateAsync(class Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations operations, string resourceGroupName, string vaultName, string certificateName, class Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest certificateRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultCertificatesOperationsExtensions.CreateAsync(Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations * string * string * string * Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultCertificateResponse&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.VaultCertificatesOperationsExtensions.CreateAsync (operations, resourceGroupName, vaultName, certificateName, certificateRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.VaultCertificatesOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultCertificateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateRequest" Type="Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8b9e-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f8b9e-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f8b9e-109">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="f8b9e-109">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="f8b9e-110">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="f8b9e-110">The name of the recovery services vault.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f8b9e-111">Anzeigename des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="f8b9e-111">Certificate friendly name.</span></span>
            </param>
        <param name="certificateRequest">
            <span data-ttu-id="f8b9e-112">Die Eingabeparameter für das Hochladen des Zertifikats Tresor.</span><span class="sxs-lookup"><span data-stu-id="f8b9e-112">Input parameters for uploading the vault certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f8b9e-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f8b9e-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8b9e-114">Hochladen eines Zertifikats für eine Ressource an.</span><span class="sxs-lookup"><span data-stu-id="f8b9e-114">Upload a certificate for a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>