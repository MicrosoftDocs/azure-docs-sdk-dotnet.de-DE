<Type Name="CertificateVerificationDescription" FullName="Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription">
  <TypeSignature Language="C#" Value="public class CertificateVerificationDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateVerificationDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateVerificationDescription" />
  <TypeSignature Language="F#" Value="type CertificateVerificationDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2cb5f-101">Das JSON-serialisierten Leaf-Zertifikat</span><span class="sxs-lookup"><span data-stu-id="2cb5f-101">The JSON-serialized leaf certificate</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateVerificationDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2cb5f-102">Initialisiert eine neue Instanz der CertificateVerificationDescription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2cb5f-102">Initializes a new instance of the CertificateVerificationDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateVerificationDescription (string certificate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string certificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional certificate As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription : string -&gt; Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription" Usage="new Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription certificate" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="certificate" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="certificate"><span data-ttu-id="2cb5f-103">Base64-Darstellung eines X509 Zertifikat CER-Datei oder der Inhalt nur PEM-Datei.</span><span class="sxs-lookup"><span data-stu-id="2cb5f-103">base-64 representation of X509 certificate .cer file or just .pem file content.</span></span></param>
        <summary>
            <span data-ttu-id="2cb5f-104">Initialisiert eine neue Instanz der CertificateVerificationDescription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2cb5f-104">Initializes a new instance of the CertificateVerificationDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificate">
      <MemberSignature Language="C#" Value="public string Certificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Certificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription.Certificate" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificate As String" />
      <MemberSignature Language="F#" Value="member this.Certificate : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription.Certificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2cb5f-105">Ruft ab oder legt ihn fest Base64-Darstellung eines X509 CER-Zertifikatdatei oder nur PEM-Datei Inhalt.</span><span class="sxs-lookup"><span data-stu-id="2cb5f-105">Gets or sets base-64 representation of X509 certificate .cer file or just .pem file content.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>