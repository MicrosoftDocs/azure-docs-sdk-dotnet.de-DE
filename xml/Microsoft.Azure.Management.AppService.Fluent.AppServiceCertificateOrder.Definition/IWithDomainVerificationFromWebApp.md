<Type Name="IWithDomainVerificationFromWebApp" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerificationFromWebApp">
  <TypeSignature Language="C#" Value="public interface IWithDomainVerificationFromWebApp : Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDomainVerificationFromWebApp implements class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerificationFromWebApp" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDomainVerificationFromWebApp&#xA;Implements IWithDomainVerification" />
  <TypeSignature Language="F#" Value="type IWithDomainVerificationFromWebApp = interface&#xA;    interface IWithDomainVerification" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="baa3a-101">Eine app Zertifikat Reihenfolge Dienstdefinition ermöglicht weitere Domäne Überprüfungsmethoden festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="baa3a-101">An app service certificate order definition allowing more domain verification methods to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithWebAppVerification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault WithWebAppVerification (Microsoft.Azure.Management.AppService.Fluent.IWebAppBase webApp);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault WithWebAppVerification(class Microsoft.Azure.Management.AppService.Fluent.IWebAppBase webApp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerificationFromWebApp.WithWebAppVerification(Microsoft.Azure.Management.AppService.Fluent.IWebAppBase)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWebAppVerification (webApp As IWebAppBase) As IWithKeyVault" />
      <MemberSignature Language="F#" Value="abstract member WithWebAppVerification : Microsoft.Azure.Management.AppService.Fluent.IWebAppBase -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault" Usage="iWithDomainVerificationFromWebApp.WithWebAppVerification webApp" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webApp" Type="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase" />
      </Parameters>
      <Docs>
        <param name="webApp"><span data-ttu-id="baa3a-102">Die Web-app, die an den Hostnamen gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="baa3a-102">The web app bound to the hostname.</span></span></param>
        <summary>
            <span data-ttu-id="baa3a-103">Gibt die Web-app, um den Besitz der Domäne zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="baa3a-103">Specifies the web app to verify the ownership of the domain.</span></span> <span data-ttu-id="baa3a-104">Die Web-app muss an den Hostnamen für das Zertifikat gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="baa3a-104">The web app needs to be bound to the hostname for the certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="baa3a-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="baa3a-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>