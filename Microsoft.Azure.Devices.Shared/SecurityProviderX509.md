<Type Name="SecurityProviderX509" FullName="Microsoft.Azure.Devices.Shared.SecurityProviderX509">
  <TypeSignature Language="C#" Value="public abstract class SecurityProviderX509 : Microsoft.Azure.Devices.Shared.SecurityProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit SecurityProviderX509 extends Microsoft.Azure.Devices.Shared.SecurityProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Shared.SecurityProviderX509" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class SecurityProviderX509&#xA;Inherits SecurityProvider" />
  <TypeSignature Language="F#" Value="type SecurityProviderX509 = class&#xA;    inherit SecurityProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Devices.Shared.SecurityProvider</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="08719-101">Für x. 509-basierte Hardware Security Modules Gerät Security Provider-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="08719-101">The Device Security Provider interface for X.509-based Hardware Security Modules.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected SecurityProviderX509 ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderX509.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthenticationCertificate">
      <MemberSignature Language="C#" Value="public abstract System.Security.Cryptography.X509Certificates.X509Certificate2 GetAuthenticationCertificate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Security.Cryptography.X509Certificates.X509Certificate2 GetAuthenticationCertificate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderX509.GetAuthenticationCertificate" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetAuthenticationCertificate () As X509Certificate2" />
      <MemberSignature Language="F#" Value="abstract member GetAuthenticationCertificate : unit -&gt; System.Security.Cryptography.X509Certificates.X509Certificate2" Usage="securityProviderX509.GetAuthenticationCertificate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.X509Certificates.X509Certificate2</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="08719-102">Ruft das Zertifikat für die Authentifizierung von TLS-Gerät verwendet.</span><span class="sxs-lookup"><span data-stu-id="08719-102">Gets the certificate used for TLS device authentication.</span></span>
            </summary>
        <returns><span data-ttu-id="08719-103">Das Clientzertifikat, das während der TLS-Kommunikation verwendet.</span><span class="sxs-lookup"><span data-stu-id="08719-103">The client certificate used during TLS communications.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthenticationCertificateChain">
      <MemberSignature Language="C#" Value="public abstract System.Security.Cryptography.X509Certificates.X509Certificate2Collection GetAuthenticationCertificateChain ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Security.Cryptography.X509Certificates.X509Certificate2Collection GetAuthenticationCertificateChain() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderX509.GetAuthenticationCertificateChain" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetAuthenticationCertificateChain () As X509Certificate2Collection" />
      <MemberSignature Language="F#" Value="abstract member GetAuthenticationCertificateChain : unit -&gt; System.Security.Cryptography.X509Certificates.X509Certificate2Collection" Usage="securityProviderX509.GetAuthenticationCertificateChain " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.X509Certificates.X509Certificate2Collection</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="08719-104">Ruft die Vertrauenskette, die in den vertrauenswürdigen Stamm auf dem Server installierten enden soll.</span><span class="sxs-lookup"><span data-stu-id="08719-104">Gets the certificate trust chain that will end in the Trusted Root installed on the server side.</span></span>
            </summary>
        <returns><span data-ttu-id="08719-105">Die Zertifikatkette.</span><span class="sxs-lookup"><span data-stu-id="08719-105">The certificate chain.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationID">
      <MemberSignature Language="C#" Value="public override string GetRegistrationID ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string GetRegistrationID() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderX509.GetRegistrationID" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetRegistrationID () As String" />
      <MemberSignature Language="F#" Value="override this.GetRegistrationID : unit -&gt; string" Usage="securityProviderX509.GetRegistrationID " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="08719-106">Gibt die RegistrationID zurück.</span><span class="sxs-lookup"><span data-stu-id="08719-106">Returns the RegistrationID.</span></span>
            </summary>
        <returns><span data-ttu-id="08719-107">Die RegistrationID.</span><span class="sxs-lookup"><span data-stu-id="08719-107">The RegistrationID.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>