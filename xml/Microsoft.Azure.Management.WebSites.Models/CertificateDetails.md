<Type Name="CertificateDetails" FullName="Microsoft.Azure.Management.WebSites.Models.CertificateDetails">
  <TypeSignature Language="C#" Value="public class CertificateDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.CertificateDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateDetails" />
  <TypeSignature Language="F#" Value="type CertificateDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9f81f-101">Details der SSL-Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="9f81f-101">SSL certificate details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CertificateDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9f81f-102">Initialisiert eine neue Instanz der CertificateDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9f81f-102">Initializes a new instance of the CertificateDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateDetails (Nullable&lt;int&gt; version = null, string serialNumber = null, string thumbprint = null, string subject = null, Nullable&lt;DateTime&gt; notBefore = null, Nullable&lt;DateTime&gt; notAfter = null, string signatureAlgorithm = null, string issuer = null, string rawData = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; version, string serialNumber, string thumbprint, string subject, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; notBefore, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; notAfter, string signatureAlgorithm, string issuer, string rawData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CertificateDetails.#ctor(System.Nullable{System.Int32},System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional version As Nullable(Of Integer) = null, Optional serialNumber As String = null, Optional thumbprint As String = null, Optional subject As String = null, Optional notBefore As Nullable(Of DateTime) = null, Optional notAfter As Nullable(Of DateTime) = null, Optional signatureAlgorithm As String = null, Optional issuer As String = null, Optional rawData As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.CertificateDetails : Nullable&lt;int&gt; * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.CertificateDetails" Usage="new Microsoft.Azure.Management.WebSites.Models.CertificateDetails (version, serialNumber, thumbprint, subject, notBefore, notAfter, signatureAlgorithm, issuer, rawData)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="version" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="serialNumber" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="subject" Type="System.String" />
        <Parameter Name="notBefore" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="notAfter" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="signatureAlgorithm" Type="System.String" />
        <Parameter Name="issuer" Type="System.String" />
        <Parameter Name="rawData" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="version"><span data-ttu-id="9f81f-103">Zertifikatsversion.</span><span class="sxs-lookup"><span data-stu-id="9f81f-103">Certificate Version.</span></span></param>
        <param name="serialNumber"><span data-ttu-id="9f81f-104">Seriennummer des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="9f81f-104">Certificate Serial Number.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="9f81f-105">Fingerabdruck des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="9f81f-105">Certificate Thumbprint.</span></span></param>
        <param name="subject"><span data-ttu-id="9f81f-106">Antragsteller des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="9f81f-106">Certificate Subject.</span></span></param>
        <param name="notBefore"><span data-ttu-id="9f81f-107">Datum-Zertifikat ist gültig.</span><span class="sxs-lookup"><span data-stu-id="9f81f-107">Date Certificate is valid from.</span></span></param>
        <param name="notAfter"><span data-ttu-id="9f81f-108">Datum-Zertifikat ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="9f81f-108">Date Certificate is valid to.</span></span></param>
        <param name="signatureAlgorithm"><span data-ttu-id="9f81f-109">Zertifikat-Signaturalgorithmus.</span><span class="sxs-lookup"><span data-stu-id="9f81f-109">Certificate Signature algorithm.</span></span></param>
        <param name="issuer"><span data-ttu-id="9f81f-110">Aussteller des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="9f81f-110">Certificate Issuer.</span></span></param>
        <param name="rawData"><span data-ttu-id="9f81f-111">Die Rohzertifikatdaten.</span><span class="sxs-lookup"><span data-stu-id="9f81f-111">Raw certificate data.</span></span></param>
        <summary>
            <span data-ttu-id="9f81f-112">Initialisiert eine neue Instanz der CertificateDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9f81f-112">Initializes a new instance of the CertificateDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Issuer">
      <MemberSignature Language="C#" Value="public string Issuer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Issuer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificateDetails.Issuer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Issuer As String" />
      <MemberSignature Language="F#" Value="member this.Issuer : string" Usage="Microsoft.Azure.Management.WebSites.Models.CertificateDetails.Issuer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="issuer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f81f-113">Ruft die Zertifikataussteller an.</span><span class="sxs-lookup"><span data-stu-id="9f81f-113">Gets certificate Issuer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotAfter">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NotAfter { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NotAfter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificateDetails.NotAfter" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NotAfter As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NotAfter : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.CertificateDetails.NotAfter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="notAfter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f81f-114">Ruft das Datum, an das Zertifikat gültig ist.</span><span class="sxs-lookup"><span data-stu-id="9f81f-114">Gets date Certificate is valid to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotBefore">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NotBefore { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NotBefore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificateDetails.NotBefore" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NotBefore As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NotBefore : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.CertificateDetails.NotBefore" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="notBefore")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f81f-115">Ruft das Datum, an das Zertifikat gültig ist.</span><span class="sxs-lookup"><span data-stu-id="9f81f-115">Gets date Certificate is valid from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RawData">
      <MemberSignature Language="C#" Value="public string RawData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RawData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificateDetails.RawData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RawData As String" />
      <MemberSignature Language="F#" Value="member this.RawData : string" Usage="Microsoft.Azure.Management.WebSites.Models.CertificateDetails.RawData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rawData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f81f-116">Ruft die Rohzertifikatdaten ab.</span><span class="sxs-lookup"><span data-stu-id="9f81f-116">Gets raw certificate data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerialNumber">
      <MemberSignature Language="C#" Value="public string SerialNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SerialNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificateDetails.SerialNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerialNumber As String" />
      <MemberSignature Language="F#" Value="member this.SerialNumber : string" Usage="Microsoft.Azure.Management.WebSites.Models.CertificateDetails.SerialNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serialNumber")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f81f-117">Ruft das Zertifikat Seriennummer.</span><span class="sxs-lookup"><span data-stu-id="9f81f-117">Gets certificate Serial Number.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignatureAlgorithm">
      <MemberSignature Language="C#" Value="public string SignatureAlgorithm { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SignatureAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificateDetails.SignatureAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SignatureAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.SignatureAlgorithm : string" Usage="Microsoft.Azure.Management.WebSites.Models.CertificateDetails.SignatureAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="signatureAlgorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f81f-118">Ruft die Zertifikat-Signaturalgorithmus ab.</span><span class="sxs-lookup"><span data-stu-id="9f81f-118">Gets certificate Signature algorithm.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subject">
      <MemberSignature Language="C#" Value="public string Subject { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Subject" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificateDetails.Subject" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subject As String" />
      <MemberSignature Language="F#" Value="member this.Subject : string" Usage="Microsoft.Azure.Management.WebSites.Models.CertificateDetails.Subject" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subject")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f81f-119">Ruft die Zertifikatantragsteller ab.</span><span class="sxs-lookup"><span data-stu-id="9f81f-119">Gets certificate Subject.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificateDetails.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string" Usage="Microsoft.Azure.Management.WebSites.Models.CertificateDetails.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f81f-120">Ruft die Zertifikatfingerabdruck an.</span><span class="sxs-lookup"><span data-stu-id="9f81f-120">Gets certificate Thumbprint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificateDetails.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Version : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.CertificateDetails.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f81f-121">Ruft das Zertifikat Version.</span><span class="sxs-lookup"><span data-stu-id="9f81f-121">Gets certificate Version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>