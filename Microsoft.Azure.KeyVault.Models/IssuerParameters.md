<Type Name="IssuerParameters" FullName="Microsoft.Azure.KeyVault.Models.IssuerParameters">
  <TypeSignature Language="C#" Value="public class IssuerParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IssuerParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.IssuerParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class IssuerParameters" />
  <TypeSignature Language="F#" Value="type IssuerParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Parameter für den Aussteller der X509 Komponente eines Zertifikats.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IssuerParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.IssuerParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der IssuerParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IssuerParameters (string name = null, string certificateType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string certificateType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.IssuerParameters.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional certificateType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.IssuerParameters : string * string -&gt; Microsoft.Azure.KeyVault.Models.IssuerParameters" Usage="new Microsoft.Azure.KeyVault.Models.IssuerParameters (name, certificateType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="certificateType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des referenzierten Aussteller-Objekts oder der reservierte Namen; z. B. "Self" oder "Unknown".</param>
        <param name="certificateType">Der Typ des Zertifikats, das vom Anbieter Aussteller angefordert werden.</param>
        <summary>
            Initialisiert eine neue Instanz der IssuerParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateType">
      <MemberSignature Language="C#" Value="public string CertificateType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerParameters.CertificateType" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateType As String" />
      <MemberSignature Language="F#" Value="member this.CertificateType : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.IssuerParameters.CertificateType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cty")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest-Zertifikat vom Aussteller Anbieter angefordert werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerParameters.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.IssuerParameters.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Name des Objekts, auf die verwiesen wird, Aussteller oder reservierte Namen; z. B. "Self" oder "Unknown".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>