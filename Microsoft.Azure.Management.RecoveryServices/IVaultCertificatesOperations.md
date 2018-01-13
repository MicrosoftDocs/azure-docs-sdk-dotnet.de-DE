<Type Name="IVaultCertificatesOperations" FullName="Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations">
  <TypeSignature Language="C#" Value="public interface IVaultCertificatesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVaultCertificatesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVaultCertificatesOperations" />
  <TypeSignature Language="F#" Value="type IVaultCertificatesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            VaultCertificatesOperations-Vorgänge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultCertificateResponse&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string vaultName, string certificateName, Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest certificateRequest, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.VaultCertificateResponse&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string vaultName, string certificateName, class Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest certificateRequest, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations.CreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultCertificateResponse&gt;&gt;" Usage="iVaultCertificatesOperations.CreateWithHttpMessagesAsync (resourceGroupName, vaultName, certificateName, certificateRequest, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultCertificateResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateRequest" Type="Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Hochladen eines Zertifikats für eine Ressource an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>