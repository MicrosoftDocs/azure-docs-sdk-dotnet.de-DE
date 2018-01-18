<Type Name="IClientAssertionCertificate" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate">
  <TypeSignature Language="C#" Value="public interface IClientAssertionCertificate" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IClientAssertionCertificate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IClientAssertionCertificate" />
  <TypeSignature Language="F#" Value="type IClientAssertionCertificate = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="355b2-101">Schnittstelle für die Implementierung basierte Zertifikatvorgänge</span><span class="sxs-lookup"><span data-stu-id="355b2-101">Interface for implementing certificate based operations</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="355b2-102">Ruft den Bezeichner des Clients, die das Token anfordert.</span><span class="sxs-lookup"><span data-stu-id="355b2-102">Gets the identifier of the client requesting the token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sign">
      <MemberSignature Language="C#" Value="public byte[] Sign (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance unsigned int8[] Sign(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate.Sign(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Sign (message As String) As Byte()" />
      <MemberSignature Language="F#" Value="abstract member Sign : string -&gt; byte[]" Usage="iClientAssertionCertificate.Sign message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="355b2-103">Meldung, die signiert werden muss</span><span class="sxs-lookup"><span data-stu-id="355b2-103">Message that needs to be signed</span></span></param>
        <summary>
            <span data-ttu-id="355b2-104">Signiert eine Nachricht mit dem privaten Schlüssel im Zertifikat</span><span class="sxs-lookup"><span data-stu-id="355b2-104">Signs a message using the private key in the certificate</span></span>
            </summary>
        <returns><span data-ttu-id="355b2-105">Signierte Nachricht als Bytearray</span><span class="sxs-lookup"><span data-stu-id="355b2-105">Signed message as a byte array</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="355b2-106">Fingerabdruck des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="355b2-106">Thumbprint of the Certificate</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>