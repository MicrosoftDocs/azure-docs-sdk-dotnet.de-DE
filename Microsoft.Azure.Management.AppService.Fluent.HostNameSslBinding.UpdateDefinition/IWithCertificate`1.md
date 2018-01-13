<Type Name="IWithCertificate&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithCertificate&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithCertificate&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCertificate`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithCertificate`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCertificate(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithCertificate&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Stufe der ein Hostname SSL Bindungsdefinition ermöglicht Zertifikatinformationen angegeben werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingAppServiceCertificateOrder">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType&lt;ParentT&gt; WithExistingAppServiceCertificateOrder (Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder certificateOrder);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType`1&lt;!ParentT&gt; WithExistingAppServiceCertificateOrder(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder certificateOrder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithCertificate`1.WithExistingAppServiceCertificateOrder(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingAppServiceCertificateOrder (certificateOrder As IAppServiceCertificateOrder) As IWithSslType(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingAppServiceCertificateOrder : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType&lt;'ParentT&gt;" Usage="iWithCertificate.WithExistingAppServiceCertificateOrder certificateOrder" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateOrder" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder" />
      </Parameters>
      <Docs>
        <param name="certificateOrder">Die zertifikatreihenfolge kann jetzt zu verwendende.</param>
        <summary>
            Gibt eine Bestellung kann jetzt zu verwendende Zertifikat zu verwenden. Dies ist in der Regel für die Wiederverwendung von Platzhalterzertifikate hilfreich.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStandardSslCertificateOrder">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithKeyVault&lt;ParentT&gt; WithNewStandardSslCertificateOrder (string certificateOrderName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithKeyVault`1&lt;!ParentT&gt; WithNewStandardSslCertificateOrder(string certificateOrderName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithCertificate`1.WithNewStandardSslCertificateOrder(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStandardSslCertificateOrder (certificateOrderName As String) As IWithKeyVault(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNewStandardSslCertificateOrder : string -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithKeyVault&lt;'ParentT&gt;" Usage="iWithCertificate.WithNewStandardSslCertificateOrder certificateOrderName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithKeyVault&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateOrderName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="certificateOrderName">Der Name des Auftrags Zertifikat.</param>
        <summary>
            Fügt eine neue Bestellung der App Service-Zertifikat für den Hostnamen zu verwenden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPfxCertificateToUpload">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType&lt;ParentT&gt; WithPfxCertificateToUpload (string pfxFile, string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType`1&lt;!ParentT&gt; WithPfxCertificateToUpload(string pfxFile, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithCertificate`1.WithPfxCertificateToUpload(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPfxCertificateToUpload (pfxFile As String, password As String) As IWithSslType(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPfxCertificateToUpload : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType&lt;'ParentT&gt;" Usage="iWithCertificate.WithPfxCertificateToUpload (pfxFile, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxFile" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pfxFile">Die PFX-Zertifikatdatei hochgeladen.</param>
        <param name="password">Das Kennwort für das Zertifikat.</param>
        <summary>
            Lädt eine PFX-Zertifikat hoch.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>