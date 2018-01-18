<Type Name="VpnClientParameters" FullName="Microsoft.Azure.Management.Network.Models.VpnClientParameters">
  <TypeSignature Language="C#" Value="public class VpnClientParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VpnClientParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class VpnClientParameters" />
  <TypeSignature Language="F#" Value="type VpnClientParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6344f-101">VPN-Client-Parameter für die Erstellung eines Clientpakets</span><span class="sxs-lookup"><span data-stu-id="6344f-101">Vpn Client Parameters for package generation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VpnClientParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VpnClientParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6344f-102">Initialisiert eine neue Instanz der VpnClientParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6344f-102">Initializes a new instance of the VpnClientParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VpnClientParameters (string processorArchitecture = null, string authenticationMethod = null, string radiusServerAuthCertificate = null, System.Collections.Generic.IList&lt;string&gt; clientRootCertificates = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string processorArchitecture, string authenticationMethod, string radiusServerAuthCertificate, class System.Collections.Generic.IList`1&lt;string&gt; clientRootCertificates) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VpnClientParameters.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional processorArchitecture As String = null, Optional authenticationMethod As String = null, Optional radiusServerAuthCertificate As String = null, Optional clientRootCertificates As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.VpnClientParameters : string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Models.VpnClientParameters" Usage="new Microsoft.Azure.Management.Network.Models.VpnClientParameters (processorArchitecture, authenticationMethod, radiusServerAuthCertificate, clientRootCertificates)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="processorArchitecture" Type="System.String" />
        <Parameter Name="authenticationMethod" Type="System.String" />
        <Parameter Name="radiusServerAuthCertificate" Type="System.String" />
        <Parameter Name="clientRootCertificates" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="processorArchitecture"><span data-ttu-id="6344f-103">VPN-Client-Architektur des Prozessors.</span><span class="sxs-lookup"><span data-stu-id="6344f-103">VPN client Processor Architecture.</span></span> <span data-ttu-id="6344f-104">Mögliche Werte sind: "AMD64" "X86".</span><span class="sxs-lookup"><span data-stu-id="6344f-104">Possible values are: 'AMD64' and 'X86'.</span></span> <span data-ttu-id="6344f-105">Folgende Werte sind möglich: "Amd64", "X86"</span><span class="sxs-lookup"><span data-stu-id="6344f-105">Possible values include: 'Amd64', 'X86'</span></span></param>
        <param name="authenticationMethod"><span data-ttu-id="6344f-106">VPN-Client Authentifizierungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6344f-106">VPN client Authentication Method.</span></span> <span data-ttu-id="6344f-107">Mögliche Werte sind: "EAPTLS" und "EAPMSCHAPv2".</span><span class="sxs-lookup"><span data-stu-id="6344f-107">Possible values are: 'EAPTLS' and 'EAPMSCHAPv2'.</span></span> <span data-ttu-id="6344f-108">Folgende Werte sind möglich: "EAPTLS", "EAPMSCHAPv2"</span><span class="sxs-lookup"><span data-stu-id="6344f-108">Possible values include: 'EAPTLS', 'EAPMSCHAPv2'</span></span></param>
        <param name="radiusServerAuthCertificate"><span data-ttu-id="6344f-109">Die öffentlichen Daten für das Radius-Serverzertifikat Authentifizierung als Base-64-codierte Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="6344f-109">The public certificate data for the radius server authentication certificate as a Base-64 encoded string.</span></span> <span data-ttu-id="6344f-110">Nur erforderlich, wenn externe Radius-Authentifizierung mit EAPTLS-Authentifizierung konfiguriert wurde.</span><span class="sxs-lookup"><span data-stu-id="6344f-110">Required only if external radius authentication has been configured with EAPTLS authentication.</span></span></param>
        <param name="clientRootCertificates"><span data-ttu-id="6344f-111">Eine Liste der Zertifikate öffentliches Zertifikat des Clients Stammdaten codiert als Base64-Zeichenfolgen.</span><span class="sxs-lookup"><span data-stu-id="6344f-111">A list of client root certificates public certificate data encoded as Base-64 strings.</span></span>
            <span data-ttu-id="6344f-112">Ein optionaler Parameter für externe Radius-basierte Authentifizierung mit EAPTLS.</span><span class="sxs-lookup"><span data-stu-id="6344f-112">Optional parameter for external radius based authentication with EAPTLS.</span></span></param>
        <summary>
            <span data-ttu-id="6344f-113">Initialisiert eine neue Instanz der VpnClientParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6344f-113">Initializes a new instance of the VpnClientParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationMethod">
      <MemberSignature Language="C#" Value="public string AuthenticationMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientParameters.AuthenticationMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationMethod As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationMethod : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientParameters.AuthenticationMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authenticationMethod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6344f-114">Ruft ab, oder legt ihn fest-VPN-Client Authentifizierungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6344f-114">Gets or sets VPN client Authentication Method.</span></span> <span data-ttu-id="6344f-115">Mögliche Werte sind: "EAPTLS" und "EAPMSCHAPv2".</span><span class="sxs-lookup"><span data-stu-id="6344f-115">Possible values are: 'EAPTLS' and 'EAPMSCHAPv2'.</span></span> <span data-ttu-id="6344f-116">Folgende Werte sind möglich: "EAPTLS", "EAPMSCHAPv2"</span><span class="sxs-lookup"><span data-stu-id="6344f-116">Possible values include: 'EAPTLS', 'EAPMSCHAPv2'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRootCertificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ClientRootCertificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ClientRootCertificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientParameters.ClientRootCertificates" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRootCertificates As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ClientRootCertificates : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientParameters.ClientRootCertificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="clientRootCertificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6344f-117">Ruft ab oder legt eine Liste der clientstammzertifikate Zertifikat für Öffentliche Daten als Base64-Zeichenfolgen codiert.</span><span class="sxs-lookup"><span data-stu-id="6344f-117">Gets or sets a list of client root certificates public certificate data encoded as Base-64 strings.</span></span> <span data-ttu-id="6344f-118">Ein optionaler Parameter für externe Radius-basierte Authentifizierung mit EAPTLS.</span><span class="sxs-lookup"><span data-stu-id="6344f-118">Optional parameter for external radius based authentication with EAPTLS.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessorArchitecture">
      <MemberSignature Language="C#" Value="public string ProcessorArchitecture { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProcessorArchitecture" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientParameters.ProcessorArchitecture" />
      <MemberSignature Language="VB.NET" Value="Public Property ProcessorArchitecture As String" />
      <MemberSignature Language="F#" Value="member this.ProcessorArchitecture : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientParameters.ProcessorArchitecture" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="processorArchitecture")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6344f-119">Ruft ab, oder legt ihn fest-VPN-Client Prozessorarchitektur.</span><span class="sxs-lookup"><span data-stu-id="6344f-119">Gets or sets VPN client Processor Architecture.</span></span> <span data-ttu-id="6344f-120">Mögliche Werte sind: "AMD64" "X86".</span><span class="sxs-lookup"><span data-stu-id="6344f-120">Possible values are: 'AMD64' and 'X86'.</span></span> <span data-ttu-id="6344f-121">Folgende Werte sind möglich: "Amd64", "X86"</span><span class="sxs-lookup"><span data-stu-id="6344f-121">Possible values include: 'Amd64', 'X86'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RadiusServerAuthCertificate">
      <MemberSignature Language="C#" Value="public string RadiusServerAuthCertificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RadiusServerAuthCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientParameters.RadiusServerAuthCertificate" />
      <MemberSignature Language="VB.NET" Value="Public Property RadiusServerAuthCertificate As String" />
      <MemberSignature Language="F#" Value="member this.RadiusServerAuthCertificate : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientParameters.RadiusServerAuthCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="radiusServerAuthCertificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6344f-122">Ruft oder legt die öffentlichen Daten für den Radius-Server Authentifizierungszertifikat als Base64-codierte Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="6344f-122">Gets or sets the public certificate data for the radius server authentication certificate as a Base-64 encoded string.</span></span> <span data-ttu-id="6344f-123">Nur erforderlich, wenn externe Radius-Authentifizierung mit EAPTLS-Authentifizierung konfiguriert wurde.</span><span class="sxs-lookup"><span data-stu-id="6344f-123">Required only if external radius authentication has been configured with EAPTLS authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>