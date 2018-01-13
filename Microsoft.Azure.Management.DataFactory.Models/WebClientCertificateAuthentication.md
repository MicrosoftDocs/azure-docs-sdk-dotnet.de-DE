<Type Name="WebClientCertificateAuthentication" FullName="Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication">
  <TypeSignature Language="C#" Value="public class WebClientCertificateAuthentication : Microsoft.Azure.Management.DataFactory.Models.WebLinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebClientCertificateAuthentication extends Microsoft.Azure.Management.DataFactory.Models.WebLinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication" />
  <TypeSignature Language="VB.NET" Value="Public Class WebClientCertificateAuthentication&#xA;Inherits WebLinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type WebClientCertificateAuthentication = class&#xA;    inherit WebLinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.WebLinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("ClientCertificate")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Eine WebLinkedService, die Clientzertifikat verwenden-basierte Authentifizierung für die Kommunikation mit einem HTTP-Endpunkt. Dieses Schema folgt gegenseitigen Authentifizierung; die Server muss gültige Anmeldeinformationen auch an den Client bereitstellen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebClientCertificateAuthentication ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der WebClientCertificateAuthentication-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebClientCertificateAuthentication (object url, Microsoft.Azure.Management.DataFactory.Models.SecureString pfx, Microsoft.Azure.Management.DataFactory.Models.SecureString password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object url, class Microsoft.Azure.Management.DataFactory.Models.SecureString pfx, class Microsoft.Azure.Management.DataFactory.Models.SecureString password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.#ctor(System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,Microsoft.Azure.Management.DataFactory.Models.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As Object, pfx As SecureString, password As SecureString)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication : obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * Microsoft.Azure.Management.DataFactory.Models.SecureString -&gt; Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication" Usage="new Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication (url, pfx, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.Object" />
        <Parameter Name="pfx" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
      </Parameters>
      <Docs>
        <param name="url">Die URL des des Webdienst-Endpunkts, z. B. http://www.microsoft.com. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="pfx">Base64-codierte Inhalt einer PFX-Datei.</param>
        <param name="password">Kennwort für die PFX-Datei.</param>
        <summary>
            Initialisiert eine neue Instanz der WebClientCertificateAuthentication-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecureString" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Kennwort für die PFX-Datei.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pfx">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Pfx { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Pfx" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.Pfx" />
      <MemberSignature Language="VB.NET" Value="Public Property Pfx As SecureString" />
      <MemberSignature Language="F#" Value="member this.Pfx : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.Pfx" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pfx")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die base64-codierte Inhalt einer PFX-Datei.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="webClientCertificateAuthentication.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>