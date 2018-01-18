<Type Name="MpnsCredential" FullName="Microsoft.Azure.NotificationHubs.MpnsCredential">
  <TypeSignature Language="C#" Value="public class MpnsCredential : Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MpnsCredential extends Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.MpnsCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class MpnsCredential&#xA;Inherits PnsCredential" />
  <TypeSignature Language="F#" Value="type MpnsCredential = class&#xA;    inherit PnsCredential" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.PnsCredential</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="MpnsCredential", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="e9c6a-101">Veranschaulicht die Anmeldeinformationen des Microsoft Push Notification Service (MPNS).</span><span class="sxs-lookup"><span data-stu-id="e9c6a-101">Provides credential of Microsoft Push Notification Service (MPNS).</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="e9c6a-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.MpnsCredential" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.MpnsCredential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsCredential (byte[] certificateBuffer, string certificateKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] certificateBuffer, string certificateKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsCredential.#ctor(System.Byte[],System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (certificateBuffer As Byte(), certificateKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.MpnsCredential : byte[] * string -&gt; Microsoft.Azure.NotificationHubs.MpnsCredential" Usage="new Microsoft.Azure.NotificationHubs.MpnsCredential (certificateBuffer, certificateKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="certificateBuffer" Type="System.Byte[]" />
        <Parameter Name="certificateKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="certificateBuffer"><span data-ttu-id="e9c6a-103">Der Zertifikat-Puffer.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-103">The certificate buffer.</span></span></param>
        <param name="certificateKey"><span data-ttu-id="e9c6a-104">Der Schlüssel des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-104">The certificate key.</span></span></param>
        <summary><span data-ttu-id="e9c6a-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.MpnsCredential" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.MpnsCredential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsCredential (System.Security.Cryptography.X509Certificates.X509Certificate mpnsCertificate, string certificateKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Security.Cryptography.X509Certificates.X509Certificate mpnsCertificate, string certificateKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsCredential.#ctor(System.Security.Cryptography.X509Certificates.X509Certificate,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (mpnsCertificate As X509Certificate, certificateKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.MpnsCredential : System.Security.Cryptography.X509Certificates.X509Certificate * string -&gt; Microsoft.Azure.NotificationHubs.MpnsCredential" Usage="new Microsoft.Azure.NotificationHubs.MpnsCredential (mpnsCertificate, certificateKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mpnsCertificate" Type="System.Security.Cryptography.X509Certificates.X509Certificate" />
        <Parameter Name="certificateKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="mpnsCertificate"><span data-ttu-id="e9c6a-106">Das MPNS-Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-106">The MPNS certificate.</span></span></param>
        <param name="certificateKey"><span data-ttu-id="e9c6a-107">Der Schlüssel des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-107">The certificate key.</span></span></param>
        <summary><span data-ttu-id="e9c6a-108">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.MpnsCredential" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-108">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.MpnsCredential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsCredential (string certificatePath, string certificateKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string certificatePath, string certificateKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsCredential.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (certificatePath As String, certificateKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.MpnsCredential : string * string -&gt; Microsoft.Azure.NotificationHubs.MpnsCredential" Usage="new Microsoft.Azure.NotificationHubs.MpnsCredential (certificatePath, certificateKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="certificatePath" Type="System.String" />
        <Parameter Name="certificateKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="certificatePath"><span data-ttu-id="e9c6a-109">Der Pfad des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-109">The certificate path.</span></span></param>
        <param name="certificateKey"><span data-ttu-id="e9c6a-110">Der Schlüssel des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-110">The certificate key.</span></span></param>
        <summary><span data-ttu-id="e9c6a-111">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.MpnsCredential" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-111">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.MpnsCredential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateKey">
      <MemberSignature Language="C#" Value="public string CertificateKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.MpnsCredential.CertificateKey" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateKey As String" />
      <MemberSignature Language="F#" Value="member this.CertificateKey : string with get, set" Usage="Microsoft.Azure.NotificationHubs.MpnsCredential.CertificateKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e9c6a-112">Ruft ab oder legt den Schlüssel des Zertifikats für diese Anmeldeinformation.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-112">Gets or sets the certificate key for this credential.</span></span></summary>
        <value><span data-ttu-id="e9c6a-113">Der Schlüssel des Zertifikats für diese Anmeldeinformation.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-113">The certificate key for this credential.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsCredential.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (other As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="mpnsCredential.Equals other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="e9c6a-114">Die andere zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-114">The other object to compare.</span></span></param>
        <summary><span data-ttu-id="e9c6a-115">Gibt an, ob die Anmeldeinformationen mit einem bestimmten Objekt übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-115">Specifies whether the credential is the same with a specific object.</span></span></summary>
        <returns><span data-ttu-id="e9c6a-116">"true", wenn die Anmeldeinformationen mit einem bestimmten Objekt gleich sind; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="e9c6a-116">true if the credential is the same with a specific object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsCredential.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="mpnsCredential.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="e9c6a-117">Ruft den Hashcode für die Anmeldeinformationen ab.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-117">Retrieves the hash code for the credentials.</span></span></summary>
        <returns><span data-ttu-id="e9c6a-118">Der Hashcode für die Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-118">The hash code for the credentials.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MpnsCertificate">
      <MemberSignature Language="C#" Value="public string MpnsCertificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MpnsCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.MpnsCredential.MpnsCertificate" />
      <MemberSignature Language="VB.NET" Value="Public Property MpnsCertificate As String" />
      <MemberSignature Language="F#" Value="member this.MpnsCertificate : string with get, set" Usage="Microsoft.Azure.NotificationHubs.MpnsCredential.MpnsCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e9c6a-119">Ruft ab oder legt das MPNS-Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-119">Gets or sets the MPNS certificate.</span></span></summary>
        <value><span data-ttu-id="e9c6a-120">Das MPNS-Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-120">The MPNS certificate.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidate">
      <MemberSignature Language="C#" Value="protected override void OnValidate (bool allowLocalMockPns);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidate(bool allowLocalMockPns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsCredential.OnValidate(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidate (allowLocalMockPns As Boolean)" />
      <MemberSignature Language="F#" Value="override this.OnValidate : bool -&gt; unit" Usage="mpnsCredential.OnValidate allowLocalMockPns" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="allowLocalMockPns" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="allowLocalMockPns"><span data-ttu-id="e9c6a-121">"true", um lokale simulierten PNS zu ermöglichen; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="e9c6a-121">true to allow local mock PNS; otherwise, false.</span></span></param>
        <summary><span data-ttu-id="e9c6a-122">Überprüft die MPNS-Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="e9c6a-122">Validates the MPNS credential.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>