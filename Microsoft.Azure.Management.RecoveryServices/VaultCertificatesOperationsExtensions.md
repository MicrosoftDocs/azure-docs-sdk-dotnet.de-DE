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
            Erweiterungsmethoden für VaultCertificatesOperations.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.
            </param>
        <param name="vaultName">
            Der Name des Recovery Services-Tresor.
            </param>
        <param name="certificateName">
            Anzeigename des Zertifikats.
            </param>
        <param name="certificateRequest">
            Die Eingabeparameter für das Hochladen des Zertifikats Tresor.
            </param>
        <summary>
            Hochladen eines Zertifikats für eine Ressource an.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.
            </param>
        <param name="vaultName">
            Der Name des Recovery Services-Tresor.
            </param>
        <param name="certificateName">
            Anzeigename des Zertifikats.
            </param>
        <param name="certificateRequest">
            Die Eingabeparameter für das Hochladen des Zertifikats Tresor.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Hochladen eines Zertifikats für eine Ressource an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>