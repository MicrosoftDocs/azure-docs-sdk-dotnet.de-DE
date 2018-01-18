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
            <span data-ttu-id="970d8-101">Eine app Zertifikat Reihenfolge Dienstdefinition SKU festgelegt werden können.</span><span class="sxs-lookup"><span data-stu-id="970d8-101">An app service certificate order definition allowing SKU to be set.</span></span>
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
            <span data-ttu-id="970d8-102">Gibt die SKU des Zertifikats als standard.</span><span class="sxs-lookup"><span data-stu-id="970d8-102">Specifies the SKU of the certificate to be standard.</span></span> <span data-ttu-id="970d8-103">Es werden nur SSL-Support, um den Hostnamen und www.hostname angeben.</span><span class="sxs-lookup"><span data-stu-id="970d8-103">It will only provide SSL support to the hostname, and www.hostname.</span></span> <span data-ttu-id="970d8-104">Platzhalter werden SSL-Unterstützung unter dem Hostnamen einer untergeordneten Domäne bereit.</span><span class="sxs-lookup"><span data-stu-id="970d8-104">Wildcard type will provide SSL support to any sub-domain under the hostname.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="970d8-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="970d8-105">The next stage of the definition.</span></span></return>
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
            <span data-ttu-id="970d8-106">Gibt die SKU des Zertifikats, um Platzhalter betrachtet.</span><span class="sxs-lookup"><span data-stu-id="970d8-106">Specifies the SKU of the certificate to be wildcard.</span></span> <span data-ttu-id="970d8-107">Es wird SSL-Unterstützung unter dem Hostnamen einer untergeordneten Domäne bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="970d8-107">It will provide SSL support to any sub-domain under the hostname.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="970d8-108">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="970d8-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>