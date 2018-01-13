<Type Name="SecurityProviderX509Certificate" FullName="Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate">
  <TypeSignature Language="C#" Value="public class SecurityProviderX509Certificate : Microsoft.Azure.Devices.Shared.SecurityProviderX509" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecurityProviderX509Certificate extends Microsoft.Azure.Devices.Shared.SecurityProviderX509" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate" />
  <TypeSignature Language="VB.NET" Value="Public Class SecurityProviderX509Certificate&#xA;Inherits SecurityProviderX509" />
  <TypeSignature Language="F#" Value="type SecurityProviderX509Certificate = class&#xA;    inherit SecurityProviderX509" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Devices.Shared.SecurityProviderX509</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Der Geräteclient für die Sicherheit für X509 Authentifizierung mithilfe eines Zertifikats-Objekts.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityProviderX509Certificate (System.Security.Cryptography.X509Certificates.X509Certificate2 clientCertificate, System.Security.Cryptography.X509Certificates.X509Certificate2Collection certificateChain = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Security.Cryptography.X509Certificates.X509Certificate2 clientCertificate, class System.Security.Cryptography.X509Certificates.X509Certificate2Collection certificateChain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate.#ctor(System.Security.Cryptography.X509Certificates.X509Certificate2,System.Security.Cryptography.X509Certificates.X509Certificate2Collection)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientCertificate As X509Certificate2, Optional certificateChain As X509Certificate2Collection = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate : System.Security.Cryptography.X509Certificates.X509Certificate2 * System.Security.Cryptography.X509Certificates.X509Certificate2Collection -&gt; Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate" Usage="new Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate (clientCertificate, certificateChain)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientCertificate" Type="System.Security.Cryptography.X509Certificates.X509Certificate2" />
        <Parameter Name="certificateChain" Type="System.Security.Cryptography.X509Certificates.X509Certificate2Collection" />
      </Parameters>
      <Docs>
        <param name="clientCertificate">Das Clientzertifikat für die Authentifizierung verwendet.</param>
        <param name="certificateChain">Die Zertifikatkette, die mit dem Stammzertifikat führende hochgeladen an den Dienst bereitgestellt.</param>
        <summary>
            Initialisiert eine neue Instanz der SecurityProviderX509Certificate-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected override void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.Dispose : bool -&gt; unit" Usage="securityProviderX509Certificate.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">"true", um sowohl verwaltete als auch nicht verwaltete Ressourcen freizugeben; "false", gibt nur nicht verwaltete Ressourcen frei.</param>
        <summary>
            Die von der SecurityProviderX509Certificate verwendeten nicht verwalteten Ressourcen frei und verwirft optional auch die verwalteten Ressourcen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthenticationCertificate">
      <MemberSignature Language="C#" Value="public override System.Security.Cryptography.X509Certificates.X509Certificate2 GetAuthenticationCertificate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Security.Cryptography.X509Certificates.X509Certificate2 GetAuthenticationCertificate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate.GetAuthenticationCertificate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetAuthenticationCertificate () As X509Certificate2" />
      <MemberSignature Language="F#" Value="override this.GetAuthenticationCertificate : unit -&gt; System.Security.Cryptography.X509Certificates.X509Certificate2" Usage="securityProviderX509Certificate.GetAuthenticationCertificate " />
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
            Ruft die Vertrauenskette, die in den vertrauenswürdigen Stamm auf dem Server installierten enden soll.
            </summary>
        <returns>Die Zertifikatkette.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthenticationCertificateChain">
      <MemberSignature Language="C#" Value="public override System.Security.Cryptography.X509Certificates.X509Certificate2Collection GetAuthenticationCertificateChain ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Security.Cryptography.X509Certificates.X509Certificate2Collection GetAuthenticationCertificateChain() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate.GetAuthenticationCertificateChain" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetAuthenticationCertificateChain () As X509Certificate2Collection" />
      <MemberSignature Language="F#" Value="override this.GetAuthenticationCertificateChain : unit -&gt; System.Security.Cryptography.X509Certificates.X509Certificate2Collection" Usage="securityProviderX509Certificate.GetAuthenticationCertificateChain " />
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
            Ruft das Zertifikat für die Authentifizierung von TLS-Gerät verwendet.
            </summary>
        <returns>Das Clientzertifikat, das während der TLS-Kommunikation verwendet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>