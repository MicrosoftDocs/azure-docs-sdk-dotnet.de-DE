<Type Name="ClientAssertionCertificate" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate">
  <TypeSignature Language="C#" Value="public sealed class ClientAssertionCertificate : Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClientAssertionCertificate extends System.Object implements class Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClientAssertionCertificate&#xA;Implements IClientAssertionCertificate" />
  <TypeSignature Language="F#" Value="type ClientAssertionCertificate = class&#xA;    interface IClientAssertionCertificate" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Die zum Erstellen von Client-Assertion verwendete Zertifikat enthält.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientAssertionCertificate (string clientId, System.Security.Cryptography.X509Certificates.X509Certificate2 certificate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, class System.Security.Cryptography.X509Certificates.X509Certificate2 certificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate.#ctor(System.String,System.Security.Cryptography.X509Certificates.X509Certificate2)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientId As String, certificate As X509Certificate2)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate : string * System.Security.Cryptography.X509Certificates.X509Certificate2 -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate (clientId, certificate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="certificate" Type="System.Security.Cryptography.X509Certificates.X509Certificate2" />
      </Parameters>
      <Docs>
        <param name="clientId">Der Bezeichner des Clients, die das Token anfordert.</param>
        <param name="certificate">Das Zertifikat als Anmeldeinformationen verwendet.</param>
        <summary>
            Konstruktor zum Erstellen von Anmeldeinformationen mit Client-Id und das Zertifikat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificate">
      <MemberSignature Language="C#" Value="public System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate.Certificate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Certificate As X509Certificate2" />
      <MemberSignature Language="F#" Value="member this.Certificate : System.Security.Cryptography.X509Certificates.X509Certificate2" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate.Certificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.X509Certificates.X509Certificate2</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Zertifikat als Anmeldeinformationen verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate.ClientId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate.ClientId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Bezeichner des Clients, die das Token anfordert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinKeySizeInBits">
      <MemberSignature Language="C#" Value="public static int MinKeySizeInBits { get; }" />
      <MemberSignature Language="ILAsm" Value=".property int32 MinKeySizeInBits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate.MinKeySizeInBits" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MinKeySizeInBits As Integer" />
      <MemberSignature Language="F#" Value="member this.MinKeySizeInBits : int" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate.MinKeySizeInBits" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft mindestens X509 zertifikatschlüsselgröße in bits
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sign">
      <MemberSignature Language="C#" Value="public byte[] Sign (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance unsigned int8[] Sign(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate.Sign(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Sign (message As String) As Byte()" />
      <MemberSignature Language="F#" Value="abstract member Sign : string -&gt; byte[]&#xA;override this.Sign : string -&gt; byte[]" Usage="clientAssertionCertificate.Sign message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate.Sign(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Meldung, die signiert werden muss</param>
        <summary>
            Signiert eine Nachricht mit dem privaten Schlüssel im Zertifikat
            </summary>
        <returns>Signierte Nachricht als Bytearray</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate.Thumbprint" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate.Thumbprint</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Fingerabdruck des Zertifikats zurückgibt
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>