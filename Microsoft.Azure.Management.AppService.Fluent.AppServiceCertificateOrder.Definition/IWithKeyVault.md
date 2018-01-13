<Type Name="IWithKeyVault" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault">
  <TypeSignature Language="C#" Value="public interface IWithKeyVault" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithKeyVault" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithKeyVault" />
  <TypeSignature Language="F#" Value="type IWithKeyVault = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fd71d-101">Eine app Zertifikat Reihenfolge Dienstdefinition ermöglicht weitere Domäne Überprüfungsmethoden festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="fd71d-101">An app service certificate order definition allowing more domain verification methods to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingKeyVault">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCreate WithExistingKeyVault (Microsoft.Azure.Management.KeyVault.Fluent.IVault vault);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCreate WithExistingKeyVault(class Microsoft.Azure.Management.KeyVault.Fluent.IVault vault) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault.WithExistingKeyVault(Microsoft.Azure.Management.KeyVault.Fluent.IVault)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingKeyVault (vault As IVault) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingKeyVault : Microsoft.Azure.Management.KeyVault.Fluent.IVault -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCreate" Usage="iWithKeyVault.WithExistingKeyVault vault" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vault" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVault" />
      </Parameters>
      <Docs>
        <param name="vault"><span data-ttu-id="fd71d-102">Der Tresor privaten Schlüssel gespeichert werden soll.</span><span class="sxs-lookup"><span data-stu-id="fd71d-102">The vault to store the private key.</span></span></param>
        <summary>
            <span data-ttu-id="fd71d-103">Gibt eine vorhandene schlüsseltresor zum privaten Schlüssel des Zertifikats zu speichern.</span><span class="sxs-lookup"><span data-stu-id="fd71d-103">Specifies an existing key vault to store the certificate private key.</span></span>
            <span data-ttu-id="fd71d-104">Tresor muss 2 Dienstprinzipale Lese-/Schreibzugriff geheime Schlüssel zulassen: f3c21649-0979-4721-ac85-b0216b2cf413 und abfa0a7c-a6b6-4736-8310-5855508787-cd.</span><span class="sxs-lookup"><span data-stu-id="fd71d-104">The vault MUST allow 2 service principals to read/write secrets: f3c21649-0979-4721-ac85-b0216b2cf413 and abfa0a7c-a6b6-4736-8310-5855508787cd.</span></span>
            <span data-ttu-id="fd71d-105">Wenn sie keinen Zugriff haben, wird es versucht werden, um Zugriff zu gewähren.</span><span class="sxs-lookup"><span data-stu-id="fd71d-105">If they don't have access, an attempt will be made to grant access.</span></span> <span data-ttu-id="fd71d-106">Wenn Sie aus einer Identität ohne Zugriff auf die Active Directory Graph angemeldet sind, schlägt dieser Versuch fehl.</span><span class="sxs-lookup"><span data-stu-id="fd71d-106">If you are logged in from an identity without access to the Active Directory Graph, this attempt will fail.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="fd71d-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="fd71d-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewKeyVault">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCreate WithNewKeyVault (string vaultName, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCreate WithNewKeyVault(string vaultName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault.WithNewKeyVault(System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region)" />
      <MemberSignature Language="F#" Value="abstract member WithNewKeyVault : string * Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCreate" Usage="iWithKeyVault.WithNewKeyVault (vaultName, region)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="region" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" />
      </Parameters>
      <Docs>
        <param name="vaultName"><span data-ttu-id="fd71d-108">Der Name des neuen schlüsseltresors.</span><span class="sxs-lookup"><span data-stu-id="fd71d-108">The name of the new key vault.</span></span></param>
        <param name="region"><span data-ttu-id="fd71d-109">Der Bereich auf den Tresor erstellen.</span><span class="sxs-lookup"><span data-stu-id="fd71d-109">The region to create the vault.</span></span></param>
        <summary>
            <span data-ttu-id="fd71d-110">Erstellt einen neue schlüsseltresor zum privaten Schlüssel des Zertifikats zu speichern.</span><span class="sxs-lookup"><span data-stu-id="fd71d-110">Creates a new key vault to store the certificate private key.</span></span>
            <span data-ttu-id="fd71d-111">Verwenden Sie diese Methode nicht, wenn Sie aus einer Identität ohne Zugriff auf die Active Directory Graph angemeldet sind.</span><span class="sxs-lookup"><span data-stu-id="fd71d-111">DO NOT use this method if you are logged in from an identity without access to the Active Directory Graph.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="fd71d-112">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="fd71d-112">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>