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
            Eine app Zertifikat Reihenfolge Dienstdefinition ermöglicht weitere Domäne Überprüfungsmethoden festgelegt werden.
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
        <param name="vault">Der Tresor privaten Schlüssel gespeichert werden soll.</param>
        <summary>
            Gibt eine vorhandene schlüsseltresor zum privaten Schlüssel des Zertifikats zu speichern.
            Tresor muss 2 Dienstprinzipale Lese-/Schreibzugriff geheime Schlüssel zulassen: f3c21649-0979-4721-ac85-b0216b2cf413 und abfa0a7c-a6b6-4736-8310-5855508787-cd.
            Wenn sie keinen Zugriff haben, wird es versucht werden, um Zugriff zu gewähren. Wenn Sie aus einer Identität ohne Zugriff auf die Active Directory Graph angemeldet sind, schlägt dieser Versuch fehl.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
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
        <param name="vaultName">Der Name des neuen schlüsseltresors.</param>
        <param name="region">Der Bereich auf den Tresor erstellen.</param>
        <summary>
            Erstellt einen neue schlüsseltresor zum privaten Schlüssel des Zertifikats zu speichern.
            Verwenden Sie diese Methode nicht, wenn Sie aus einer Identität ohne Zugriff auf die Active Directory Graph angemeldet sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>