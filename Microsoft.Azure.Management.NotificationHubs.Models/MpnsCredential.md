<Type Name="MpnsCredential" FullName="Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential">
  <TypeSignature Language="C#" Value="public class MpnsCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MpnsCredential extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class MpnsCredential" />
  <TypeSignature Language="F#" Value="type MpnsCredential = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="cf844-101">Beschreibung des eine NotificationHub-MpnsCredential.</span><span class="sxs-lookup"><span data-stu-id="cf844-101">Description of a NotificationHub MpnsCredential.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cf844-102">Initialisiert eine neue Instanz der MpnsCredential-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cf844-102">Initializes a new instance of the MpnsCredential class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsCredential (string mpnsCertificate = null, string certificateKey = null, string thumbprint = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string mpnsCertificate, string certificateKey, string thumbprint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional mpnsCertificate As String = null, Optional certificateKey As String = null, Optional thumbprint As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential : string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential (mpnsCertificate, certificateKey, thumbprint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mpnsCertificate" Type="System.String" />
        <Parameter Name="certificateKey" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="mpnsCertificate"><span data-ttu-id="cf844-103">Das MPNS-Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="cf844-103">The MPNS certificate.</span></span></param>
        <param name="certificateKey"><span data-ttu-id="cf844-104">Der Schlüssel des Zertifikats für diese Anmeldeinformation.</span><span class="sxs-lookup"><span data-stu-id="cf844-104">The certificate key for this credential.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="cf844-105">Das Mpns-Zertifikat-Fingerabdruck</span><span class="sxs-lookup"><span data-stu-id="cf844-105">The Mpns certificate Thumbprint</span></span></param>
        <summary>
            <span data-ttu-id="cf844-106">Initialisiert eine neue Instanz der MpnsCredential-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cf844-106">Initializes a new instance of the MpnsCredential class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateKey">
      <MemberSignature Language="C#" Value="public string CertificateKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential.CertificateKey" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateKey As String" />
      <MemberSignature Language="F#" Value="member this.CertificateKey : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential.CertificateKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.certificateKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf844-107">Ruft ab oder legt den Schlüssel des Zertifikats für diese Anmeldeinformation.</span><span class="sxs-lookup"><span data-stu-id="cf844-107">Gets or sets the certificate key for this credential.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MpnsCertificate">
      <MemberSignature Language="C#" Value="public string MpnsCertificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MpnsCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential.MpnsCertificate" />
      <MemberSignature Language="VB.NET" Value="Public Property MpnsCertificate As String" />
      <MemberSignature Language="F#" Value="member this.MpnsCertificate : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential.MpnsCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.mpnsCertificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf844-108">Ruft ab oder legt das MPNS-Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="cf844-108">Gets or sets the MPNS certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf844-109">Ruft ab oder legt das Mpns-Zertifikat-Fingerabdruck</span><span class="sxs-lookup"><span data-stu-id="cf844-109">Gets or sets the Mpns certificate Thumbprint</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>