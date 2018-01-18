<Type Name="HttpLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService">
  <TypeSignature Language="C#" Value="public class HttpLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HttpLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class HttpLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type HttpLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("Http")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="b6f68-101">Verknüpften Dienst für einen HTTP-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="b6f68-101">Linked service for an HTTP endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b6f68-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b6f68-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpLinkedService (string url, string authenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string url, string authenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As String, authenticationType As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService : string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService (url, authenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="authenticationType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="url">To be added.</param>
        <param name="authenticationType">To be added.</param>
        <summary>
            <span data-ttu-id="b6f68-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService" /> Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="b6f68-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService" /> class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b6f68-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b6f68-104">Required.</span></span> <span data-ttu-id="b6f68-105">Der Authentifizierungstyp für die Verbindung mit dem HTTP-Server verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="b6f68-105">The authentication type to be used to connect to the HTTP server.</span></span>
            <span data-ttu-id="b6f68-106">Muss einer der <see cref="T:Microsoft.Azure.Management.DataFactories.Models.HttpAuthenticationType" />.</span><span class="sxs-lookup"><span data-stu-id="b6f68-106">Must be one of <see cref="T:Microsoft.Azure.Management.DataFactories.Models.HttpAuthenticationType" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertThumbprint">
      <MemberSignature Language="C#" Value="public string CertThumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.CertThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property CertThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.CertThumbprint : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.CertThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b6f68-107">Optional.</span><span class="sxs-lookup"><span data-stu-id="b6f68-107">Optional.</span></span> <span data-ttu-id="b6f68-108">Fingerabdruck des Zertifikats für ClientCertificate-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="b6f68-108">Thumbprint of certificate for ClientCertificate authentication.</span></span> <span data-ttu-id="b6f68-109">Nur gültig für die lokale Kopie.</span><span class="sxs-lookup"><span data-stu-id="b6f68-109">Only valid for on-premises copy.</span></span>
            <span data-ttu-id="b6f68-110">Für die lokale Kopie mit ClientCertificate-Authentifizierung sollte "CertThumbprint" gelöscht oder EmbeddedCertData/Kennwort angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="b6f68-110">For on-premises copy with ClientCertificate authentication, either CertThumbprint or EmbeddedCertData/Password should be specified.</span></span>
            
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmbeddedCertData">
      <MemberSignature Language="C#" Value="public string EmbeddedCertData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EmbeddedCertData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.EmbeddedCertData" />
      <MemberSignature Language="VB.NET" Value="Public Property EmbeddedCertData As String" />
      <MemberSignature Language="F#" Value="member this.EmbeddedCertData : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.EmbeddedCertData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b6f68-111">Optional.</span><span class="sxs-lookup"><span data-stu-id="b6f68-111">Optional.</span></span> <span data-ttu-id="b6f68-112">Base64-codierte Zertifikatdaten für ClientCertificate-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="b6f68-112">Base64 encoded certificate data for ClientCertificate authentication.</span></span> <span data-ttu-id="b6f68-113">Für die lokale Kopie mit ClientCertificate-Authentifizierung sollte "CertThumbprint" gelöscht oder EmbeddedCertData/Kennwort angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="b6f68-113">For on-premises copy with ClientCertificate authentication, either CertThumbprint or EmbeddedCertData/Password should be specified.</span></span>
            
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableServerCertificateValidation">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableServerCertificateValidation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableServerCertificateValidation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.EnableServerCertificateValidation" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableServerCertificateValidation As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableServerCertificateValidation : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.EnableServerCertificateValidation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b6f68-114">Optional.</span><span class="sxs-lookup"><span data-stu-id="b6f68-114">Optional.</span></span> <span data-ttu-id="b6f68-115">Bei "true", überprüfen Sie die HTTP-SSL-Serverzertifikats Wenn die Verbindung über SSL/TLS-Kanal.</span><span class="sxs-lookup"><span data-stu-id="b6f68-115">If true, validate the HTTP server SSL certificate when connect over SSL/TLS channel.</span></span>
            <span data-ttu-id="b6f68-116">Standardwert ist "true".</span><span class="sxs-lookup"><span data-stu-id="b6f68-116">Default value is true.</span></span>
            <span data-ttu-id="b6f68-117">Es wird nicht empfohlen, das Festlegen dieser Eigenschaft auf "false", um die Überprüfung zu überspringen.</span><span class="sxs-lookup"><span data-stu-id="b6f68-117">It is not recommended to set this property to false to skip the validation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public string EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As String" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b6f68-118">Optional.</span><span class="sxs-lookup"><span data-stu-id="b6f68-118">Optional.</span></span> <span data-ttu-id="b6f68-119">Die verschlüsselten Anmeldeinformationen für Basic, Digest, Windows oder ClientCertificate-Authentifizierung nur gültig für die lokale Kopie.</span><span class="sxs-lookup"><span data-stu-id="b6f68-119">The encrypted credential for Basic, Digest, Windows or ClientCertificate authentication, only valid for on-premises copy.</span></span>
            <span data-ttu-id="b6f68-120">Für die lokale Kopie mit nicht anonyme Authentifizierung sollte die Benutzername/Kennwort, ClientThumbprint, EmbeddedCertData/Kennwort oder EncryptedCredential angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="b6f68-120">For on-premises copy with non-Anonymous authentication, either Username/Password, ClientThumbprint, EmbeddedCertData/Password or EncryptedCredential should be specified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayName">
      <MemberSignature Language="C#" Value="public string GatewayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.GatewayName" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayName As String" />
      <MemberSignature Language="F#" Value="member this.GatewayName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.GatewayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b6f68-121">Optional.</span><span class="sxs-lookup"><span data-stu-id="b6f68-121">Optional.</span></span> <span data-ttu-id="b6f68-122">Der Name des lokalen Netzwerkgateways.</span><span class="sxs-lookup"><span data-stu-id="b6f68-122">The on-premises gateway name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b6f68-123">Optional.</span><span class="sxs-lookup"><span data-stu-id="b6f68-123">Optional.</span></span> <span data-ttu-id="b6f68-124">Kennwort für Basic, Digest, Windows oder ClientCertificate mit EmbeddedCertData Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="b6f68-124">Password for Basic, Digest, Windows, or ClientCertificate with EmbeddedCertData authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b6f68-125">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b6f68-125">Required.</span></span> <span data-ttu-id="b6f68-126">Die Basis-URL des HTTP-Endpunkts, z. B. http://www.microsoft.com.</span><span class="sxs-lookup"><span data-stu-id="b6f68-126">The base URL of the HTTP endpoint, e.g. http://www.microsoft.com.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b6f68-127">Optional.</span><span class="sxs-lookup"><span data-stu-id="b6f68-127">Optional.</span></span> <span data-ttu-id="b6f68-128">Der Benutzername für die Standard-, Digest- oder Windows-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="b6f68-128">User name for Basic, Digest, or Windows authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>