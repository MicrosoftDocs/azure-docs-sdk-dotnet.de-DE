<Type Name="IWithCertificateSku" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCertificateSku">
  <TypeSignature Language="C#" Value="public interface IWithCertificateSku" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCertificateSku" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCertificateSku" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCertificateSku" />
  <TypeSignature Language="F#" Value="type IWithCertificateSku = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Eine app Zertifikat Reihenfolge Dienstdefinition SKU festgelegt werden können.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithStandardSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerificationFromWebApp WithStandardSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerificationFromWebApp WithStandardSku() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCertificateSku.WithStandardSku" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStandardSku () As IWithDomainVerificationFromWebApp" />
      <MemberSignature Language="F#" Value="abstract member WithStandardSku : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerificationFromWebApp" Usage="iWithCertificateSku.WithStandardSku " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerificationFromWebApp</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt die SKU des Zertifikats als standard. Es werden nur SSL-Support, um den Hostnamen und www.hostname angeben. Platzhalter werden SSL-Unterstützung unter dem Hostnamen einer untergeordneten Domäne bereit.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithWildcardSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification WithWildcardSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification WithWildcardSku() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCertificateSku.WithWildcardSku" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWildcardSku () As IWithDomainVerification" />
      <MemberSignature Language="F#" Value="abstract member WithWildcardSku : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification" Usage="iWithCertificateSku.WithWildcardSku " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt die SKU des Zertifikats, um Platzhalter betrachtet. Es wird SSL-Unterstützung unter dem Hostnamen einer untergeordneten Domäne bereitstellen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>