<Type Name="IWithKeyVault&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithKeyVault&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithKeyVault&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithKeyVault`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithKeyVault`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithKeyVault(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithKeyVault&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="5fe6b-101">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="5fe6b-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="5fe6b-102">Die Phase der Hostname SSL-Bindungsdefinition ermöglicht schlüsseltresor für den Zertifikatspeicher angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="5fe6b-102">The stage of a hostname SSL binding definition allowing key vault for certificate store to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingKeyVault">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType&lt;ParentT&gt; WithExistingKeyVault (Microsoft.Azure.Management.KeyVault.Fluent.IVault vault);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType`1&lt;!ParentT&gt; WithExistingKeyVault(class Microsoft.Azure.Management.KeyVault.Fluent.IVault vault) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithKeyVault`1.WithExistingKeyVault(Microsoft.Azure.Management.KeyVault.Fluent.IVault)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingKeyVault (vault As IVault) As IWithSslType(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingKeyVault : Microsoft.Azure.Management.KeyVault.Fluent.IVault -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType&lt;'ParentT&gt;" Usage="iWithKeyVault.WithExistingKeyVault vault" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vault" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVault" />
      </Parameters>
      <Docs>
        <param name="vault"><span data-ttu-id="5fe6b-103">Die vorhandenen Tresor verwenden.</span><span class="sxs-lookup"><span data-stu-id="5fe6b-103">The existing vault to use.</span></span></param>
        <summary>
            <span data-ttu-id="5fe6b-104">Speichert das Zertifikat in einem bereits vorhandenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="5fe6b-104">Stores the certificate in an existing vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5fe6b-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="5fe6b-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewKeyVault">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType&lt;ParentT&gt; WithNewKeyVault (string vaultName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType`1&lt;!ParentT&gt; WithNewKeyVault(string vaultName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithKeyVault`1.WithNewKeyVault(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewKeyVault (vaultName As String) As IWithSslType(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNewKeyVault : string -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType&lt;'ParentT&gt;" Usage="iWithKeyVault.WithNewKeyVault vaultName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="vaultName"><span data-ttu-id="5fe6b-106">Der Name des zu erstellenden Schlüsseltresors.</span><span class="sxs-lookup"><span data-stu-id="5fe6b-106">The name of the key vault to create.</span></span></param>
        <summary>
            <span data-ttu-id="5fe6b-107">Erstellt einen neue schlüsseltresor zum Speichern des Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="5fe6b-107">Creates a new key vault to store the certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5fe6b-108">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="5fe6b-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>