<Type Name="AppServiceCertificateOrderPatchResource" FullName="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource">
  <TypeSignature Language="C#" Value="public class AppServiceCertificateOrderPatchResource : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServiceCertificateOrderPatchResource extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServiceCertificateOrderPatchResource&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type AppServiceCertificateOrderPatchResource = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5a40c-101">ARM-Ressource für eine zertifikatreihenfolge, die über Azure erworben wird.</span><span class="sxs-lookup"><span data-stu-id="5a40c-101">ARM resource for a certificate order that is purchased through Azure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceCertificateOrderPatchResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-102">Initialisiert eine neue Instanz der AppServiceCertificateOrderPatchResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5a40c-102">Initializes a new instance of the AppServiceCertificateOrderPatchResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceCertificateOrderPatchResource (string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate&gt; certificates = null, string distinguishedName = null, string domainVerificationToken = null, Nullable&lt;int&gt; validityInYears = null, Nullable&lt;int&gt; keySize = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateProductType&gt; productType = null, Nullable&lt;bool&gt; autoRenew = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus&gt; status = null, Microsoft.Azure.Management.WebSites.Models.CertificateDetails signedCertificate = null, string csr = null, Microsoft.Azure.Management.WebSites.Models.CertificateDetails intermediate = null, Microsoft.Azure.Management.WebSites.Models.CertificateDetails root = null, string serialNumber = null, Nullable&lt;DateTime&gt; lastCertificateIssuanceTime = null, Nullable&lt;DateTime&gt; expirationTime = null, Nullable&lt;bool&gt; isPrivateKeyExternal = null, System.Collections.Generic.IList&lt;string&gt; appServiceCertificateNotRenewableReasons = null, Nullable&lt;DateTime&gt; nextAutoRenewalTimeStamp = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate&gt; certificates, string distinguishedName, string domainVerificationToken, valuetype System.Nullable`1&lt;int32&gt; validityInYears, valuetype System.Nullable`1&lt;int32&gt; keySize, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.CertificateProductType&gt; productType, valuetype System.Nullable`1&lt;bool&gt; autoRenew, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus&gt; status, class Microsoft.Azure.Management.WebSites.Models.CertificateDetails signedCertificate, string csr, class Microsoft.Azure.Management.WebSites.Models.CertificateDetails intermediate, class Microsoft.Azure.Management.WebSites.Models.CertificateDetails root, string serialNumber, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastCertificateIssuanceTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expirationTime, valuetype System.Nullable`1&lt;bool&gt; isPrivateKeyExternal, class System.Collections.Generic.IList`1&lt;string&gt; appServiceCertificateNotRenewableReasons, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; nextAutoRenewalTimeStamp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.WebSites.Models.CertificateProductType},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.WebSites.Models.ProvisioningState},System.Nullable{Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus},Microsoft.Azure.Management.WebSites.Models.CertificateDetails,System.String,Microsoft.Azure.Management.WebSites.Models.CertificateDetails,Microsoft.Azure.Management.WebSites.Models.CertificateDetails,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional certificates As IDictionary(Of String, AppServiceCertificate) = null, Optional distinguishedName As String = null, Optional domainVerificationToken As String = null, Optional validityInYears As Nullable(Of Integer) = null, Optional keySize As Nullable(Of Integer) = null, Optional productType As Nullable(Of CertificateProductType) = null, Optional autoRenew As Nullable(Of Boolean) = null, Optional provisioningState As Nullable(Of ProvisioningState) = null, Optional status As Nullable(Of CertificateOrderStatus) = null, Optional signedCertificate As CertificateDetails = null, Optional csr As String = null, Optional intermediate As CertificateDetails = null, Optional root As CertificateDetails = null, Optional serialNumber As String = null, Optional lastCertificateIssuanceTime As Nullable(Of DateTime) = null, Optional expirationTime As Nullable(Of DateTime) = null, Optional isPrivateKeyExternal As Nullable(Of Boolean) = null, Optional appServiceCertificateNotRenewableReasons As IList(Of String) = null, Optional nextAutoRenewalTimeStamp As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateProductType&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus&gt; * Microsoft.Azure.Management.WebSites.Models.CertificateDetails * string * Microsoft.Azure.Management.WebSites.Models.CertificateDetails * Microsoft.Azure.Management.WebSites.Models.CertificateDetails * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource" Usage="new Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource (id, name, kind, type, certificates, distinguishedName, domainVerificationToken, validityInYears, keySize, productType, autoRenew, provisioningState, status, signedCertificate, csr, intermediate, root, serialNumber, lastCertificateIssuanceTime, expirationTime, isPrivateKeyExternal, appServiceCertificateNotRenewableReasons, nextAutoRenewalTimeStamp)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="certificates" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate&gt;" />
        <Parameter Name="distinguishedName" Type="System.String" />
        <Parameter Name="domainVerificationToken" Type="System.String" />
        <Parameter Name="validityInYears" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="keySize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="productType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateProductType&gt;" />
        <Parameter Name="autoRenew" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus&gt;" />
        <Parameter Name="signedCertificate" Type="Microsoft.Azure.Management.WebSites.Models.CertificateDetails" />
        <Parameter Name="csr" Type="System.String" />
        <Parameter Name="intermediate" Type="Microsoft.Azure.Management.WebSites.Models.CertificateDetails" />
        <Parameter Name="root" Type="Microsoft.Azure.Management.WebSites.Models.CertificateDetails" />
        <Parameter Name="serialNumber" Type="System.String" />
        <Parameter Name="lastCertificateIssuanceTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="expirationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="isPrivateKeyExternal" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="appServiceCertificateNotRenewableReasons" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="nextAutoRenewalTimeStamp" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="5a40c-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="5a40c-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="5a40c-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="5a40c-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="5a40c-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="5a40c-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="5a40c-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="5a40c-106">Resource type.</span></span></param>
        <param name="certificates"><span data-ttu-id="5a40c-107">Status des geheimen Schlüssels Key Vault.</span><span class="sxs-lookup"><span data-stu-id="5a40c-107">State of the Key Vault secret.</span></span></param>
        <param name="distinguishedName"><span data-ttu-id="5a40c-108">Definierter Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="5a40c-108">Certificate distinguished name.</span></span></param>
        <param name="domainVerificationToken"><span data-ttu-id="5a40c-109">Domäne überprüfungstokens.</span><span class="sxs-lookup"><span data-stu-id="5a40c-109">Domain verification token.</span></span></param>
        <param name="validityInYears"><span data-ttu-id="5a40c-110">Die Dauer in Jahren (muss zwischen 1 und 3 liegen).</span><span class="sxs-lookup"><span data-stu-id="5a40c-110">Duration in years (must be between 1 and 3).</span></span></param>
        <param name="keySize"><span data-ttu-id="5a40c-111">Die zertifikatschlüsselgröße.</span><span class="sxs-lookup"><span data-stu-id="5a40c-111">Certificate key size.</span></span></param>
        <param name="productType"><span data-ttu-id="5a40c-112">Typ für das Produkt.</span><span class="sxs-lookup"><span data-stu-id="5a40c-112">Certificate product type.</span></span> <span data-ttu-id="5a40c-113">Folgende Werte sind möglich: "StandardDomainValidatedSsl", "StandardDomainValidatedWildCardSsl"</span><span class="sxs-lookup"><span data-stu-id="5a40c-113">Possible values include: 'StandardDomainValidatedSsl', 'StandardDomainValidatedWildCardSsl'</span></span></param>
        <param name="autoRenew"><span data-ttu-id="5a40c-114">&lt;Code&gt;"true"&lt;/code&gt; , wenn das Zertifikat automatisch erneuert werden soll, wenn diese abläuft; andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="5a40c-114">&lt;code&gt;true&lt;/code&gt; if the certificate should be automatically renewed when it expires; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="5a40c-115">Status des zertifikatreihenfolge.</span><span class="sxs-lookup"><span data-stu-id="5a40c-115">Status of certificate order.</span></span>
            <span data-ttu-id="5a40c-116">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen", "InProgress", "Löschen"</span><span class="sxs-lookup"><span data-stu-id="5a40c-116">Possible values include: 'Succeeded', 'Failed', 'Canceled', 'InProgress', 'Deleting'</span></span></param>
        <param name="status"><span data-ttu-id="5a40c-117">Aktuellen Auftragsstatus.</span><span class="sxs-lookup"><span data-stu-id="5a40c-117">Current order status.</span></span> <span data-ttu-id="5a40c-118">Folgende Werte sind möglich: "Pendingissuance", "Ausgestellt", "Gesperrt", "Canceled", "Abgelehnt", "Pendingrevocation", "PendingRekey", "Nicht verwendet", "Abgelaufen", "NotSubmitted"</span><span class="sxs-lookup"><span data-stu-id="5a40c-118">Possible values include: 'Pendingissuance', 'Issued', 'Revoked', 'Canceled', 'Denied', 'Pendingrevocation', 'PendingRekey', 'Unused', 'Expired', 'NotSubmitted'</span></span></param>
        <param name="signedCertificate"><span data-ttu-id="5a40c-119">Signiertes Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a40c-119">Signed certificate.</span></span></param>
        <param name="csr"><span data-ttu-id="5a40c-120">Letzte CSR, die für diesen Auftrag erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="5a40c-120">Last CSR that was created for this order.</span></span></param>
        <param name="intermediate"><span data-ttu-id="5a40c-121">Zwischenzertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a40c-121">Intermediate certificate.</span></span></param>
        <param name="root"><span data-ttu-id="5a40c-122">Stammzertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a40c-122">Root certificate.</span></span></param>
        <param name="serialNumber"><span data-ttu-id="5a40c-123">Aktuelle Seriennummer des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="5a40c-123">Current serial number of the certificate.</span></span></param>
        <param name="lastCertificateIssuanceTime"><span data-ttu-id="5a40c-124">Zeitpunkt der letzten Ausstellung Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a40c-124">Certificate last issuance time.</span></span></param>
        <param name="expirationTime"><span data-ttu-id="5a40c-125">Zertifikat für den Ablauf.</span><span class="sxs-lookup"><span data-stu-id="5a40c-125">Certificate expiration time.</span></span></param>
        <param name="isPrivateKeyExternal"><span data-ttu-id="5a40c-126">&lt;Code&gt;"true"&lt;/code&gt; wenn private Schlüssel, externe ist, andernfalls ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="5a40c-126">&lt;code&gt;true&lt;/code&gt; if private key is external; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="appServiceCertificateNotRenewableReasons"><span data-ttu-id="5a40c-127">Gründe für die App Service-Zertifikat nicht erneuerbar zum aktuellen Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="5a40c-127">Reasons why App Service Certificate is not renewable at the current moment.</span></span></param>
        <param name="nextAutoRenewalTimeStamp"><span data-ttu-id="5a40c-128">Zeitstempel, wenn das Zertifikat automatisch wäre erneuert weiter</span><span class="sxs-lookup"><span data-stu-id="5a40c-128">Time stamp when the certificate would be auto renewed next</span></span></param>
        <summary>
            <span data-ttu-id="5a40c-129">Initialisiert eine neue Instanz der AppServiceCertificateOrderPatchResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5a40c-129">Initializes a new instance of the AppServiceCertificateOrderPatchResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServiceCertificateNotRenewableReasons">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AppServiceCertificateNotRenewableReasons { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AppServiceCertificateNotRenewableReasons" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.AppServiceCertificateNotRenewableReasons" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppServiceCertificateNotRenewableReasons As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AppServiceCertificateNotRenewableReasons : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.AppServiceCertificateNotRenewableReasons" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appServiceCertificateNotRenewableReasons")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-130">Ruft die Gründe für die App Service-Zertifikat nicht erneuerbar zum aktuellen Zeitpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="5a40c-130">Gets reasons why App Service Certificate is not renewable at the current moment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoRenew">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoRenew { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoRenew" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.AutoRenew" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoRenew As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoRenew : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.AutoRenew" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoRenew")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-131">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn das Zertifikat automatisch erneuert werden soll, wenn diese abläuft; andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt ; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="5a40c-131">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the certificate should be automatically renewed when it expires; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate&gt; Certificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate&gt; Certificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Certificates" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificates As IDictionary(Of String, AppServiceCertificate)" />
      <MemberSignature Language="F#" Value="member this.Certificates : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Certificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.certificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-132">Ruft ab oder legt ihn fest der Key Vaults für den geheimen.</span><span class="sxs-lookup"><span data-stu-id="5a40c-132">Gets or sets state of the Key Vault secret.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Csr">
      <MemberSignature Language="C#" Value="public string Csr { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Csr" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Csr" />
      <MemberSignature Language="VB.NET" Value="Public Property Csr As String" />
      <MemberSignature Language="F#" Value="member this.Csr : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Csr" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.csr")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-133">Abrufen oder Festlegen der letzten CSR, die für diesen Auftrag erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="5a40c-133">Gets or sets last CSR that was created for this order.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DistinguishedName">
      <MemberSignature Language="C#" Value="public string DistinguishedName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DistinguishedName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.DistinguishedName" />
      <MemberSignature Language="VB.NET" Value="Public Property DistinguishedName As String" />
      <MemberSignature Language="F#" Value="member this.DistinguishedName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.DistinguishedName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.distinguishedName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-134">Ruft ab, oder legt ihn fest definierten Zertifikatnamen.</span><span class="sxs-lookup"><span data-stu-id="5a40c-134">Gets or sets certificate distinguished name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainVerificationToken">
      <MemberSignature Language="C#" Value="public string DomainVerificationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainVerificationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.DomainVerificationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DomainVerificationToken As String" />
      <MemberSignature Language="F#" Value="member this.DomainVerificationToken : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.DomainVerificationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.domainVerificationToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-135">Ruft die Überprüfung der Domäne token.</span><span class="sxs-lookup"><span data-stu-id="5a40c-135">Gets domain verification token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.expirationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-136">Ruft die Ablaufzeit des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="5a40c-136">Gets certificate expiration time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Intermediate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.CertificateDetails Intermediate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.CertificateDetails Intermediate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Intermediate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Intermediate As CertificateDetails" />
      <MemberSignature Language="F#" Value="member this.Intermediate : Microsoft.Azure.Management.WebSites.Models.CertificateDetails" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Intermediate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.intermediate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.CertificateDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-137">Ruft bei zwischenänderungen Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a40c-137">Gets intermediate certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPrivateKeyExternal">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsPrivateKeyExternal { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsPrivateKeyExternal" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.IsPrivateKeyExternal" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPrivateKeyExternal As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsPrivateKeyExternal : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.IsPrivateKeyExternal" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isPrivateKeyExternal")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-138">Ruft &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn private Schlüssel, externe ist, andernfalls ist &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="5a40c-138">Gets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if private key is external; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; KeySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; KeySize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.KeySize" />
      <MemberSignature Language="VB.NET" Value="Public Property KeySize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.KeySize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.KeySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keySize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-139">Ruft ab, oder legt die zertifikatschlüsselgröße fest.</span><span class="sxs-lookup"><span data-stu-id="5a40c-139">Gets or sets certificate key size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastCertificateIssuanceTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastCertificateIssuanceTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastCertificateIssuanceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.LastCertificateIssuanceTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastCertificateIssuanceTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastCertificateIssuanceTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.LastCertificateIssuanceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastCertificateIssuanceTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-140">Ruft Zertifikat zuletzt Ausstellung ab.</span><span class="sxs-lookup"><span data-stu-id="5a40c-140">Gets certificate last issuance time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextAutoRenewalTimeStamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NextAutoRenewalTimeStamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NextAutoRenewalTimeStamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.NextAutoRenewalTimeStamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextAutoRenewalTimeStamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NextAutoRenewalTimeStamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.NextAutoRenewalTimeStamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nextAutoRenewalTimeStamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-141">Ruft Zeitstempel erzeugt, wenn das Zertifikat automatisch erneuert neben wäre</span><span class="sxs-lookup"><span data-stu-id="5a40c-141">Gets time stamp when the certificate would be auto renewed next</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProductType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateProductType&gt; ProductType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.CertificateProductType&gt; ProductType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.ProductType" />
      <MemberSignature Language="VB.NET" Value="Public Property ProductType As Nullable(Of CertificateProductType)" />
      <MemberSignature Language="F#" Value="member this.ProductType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateProductType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.ProductType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.productType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateProductType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-142">Ruft ab, oder legt ihn fest Zertifikat Product-Typs.</span><span class="sxs-lookup"><span data-stu-id="5a40c-142">Gets or sets certificate product type.</span></span> <span data-ttu-id="5a40c-143">Folgende Werte sind möglich: "StandardDomainValidatedSsl", "StandardDomainValidatedWildCardSsl"</span><span class="sxs-lookup"><span data-stu-id="5a40c-143">Possible values include: 'StandardDomainValidatedSsl', 'StandardDomainValidatedWildCardSsl'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-144">Ruft den Status zertifikatreihenfolge ab.</span><span class="sxs-lookup"><span data-stu-id="5a40c-144">Gets status of certificate order.</span></span> <span data-ttu-id="5a40c-145">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen", "InProgress", "Löschen"</span><span class="sxs-lookup"><span data-stu-id="5a40c-145">Possible values include: 'Succeeded', 'Failed', 'Canceled', 'InProgress', 'Deleting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Root">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.CertificateDetails Root { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.CertificateDetails Root" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Root" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Root As CertificateDetails" />
      <MemberSignature Language="F#" Value="member this.Root : Microsoft.Azure.Management.WebSites.Models.CertificateDetails" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Root" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.root")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.CertificateDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-146">Ruft die Stammzertifikat an.</span><span class="sxs-lookup"><span data-stu-id="5a40c-146">Gets root certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerialNumber">
      <MemberSignature Language="C#" Value="public string SerialNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SerialNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.SerialNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerialNumber As String" />
      <MemberSignature Language="F#" Value="member this.SerialNumber : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.SerialNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serialNumber")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-147">Ruft die aktuellen Seriennummer des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="5a40c-147">Gets current serial number of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignedCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.CertificateDetails SignedCertificate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.CertificateDetails SignedCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.SignedCertificate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SignedCertificate As CertificateDetails" />
      <MemberSignature Language="F#" Value="member this.SignedCertificate : Microsoft.Azure.Management.WebSites.Models.CertificateDetails" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.SignedCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.signedCertificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.CertificateDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-148">Ruft signiertes Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a40c-148">Gets signed certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of CertificateOrderStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-149">Ruft die aktuellen Auftragsstatus ab.</span><span class="sxs-lookup"><span data-stu-id="5a40c-149">Gets current order status.</span></span> <span data-ttu-id="5a40c-150">Folgende Werte sind möglich: "Pendingissuance", "Ausgestellt", "Gesperrt", "Canceled", "Abgelehnt", "Pendingrevocation", "PendingRekey", "Nicht verwendet", "Abgelaufen", "NotSubmitted"</span><span class="sxs-lookup"><span data-stu-id="5a40c-150">Possible values include: 'Pendingissuance', 'Issued', 'Revoked', 'Canceled', 'Denied', 'Pendingrevocation', 'PendingRekey', 'Unused', 'Expired', 'NotSubmitted'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="appServiceCertificateOrderPatchResource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-151">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="5a40c-151">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5a40c-152">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="5a40c-152">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ValidityInYears">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ValidityInYears { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ValidityInYears" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.ValidityInYears" />
      <MemberSignature Language="VB.NET" Value="Public Property ValidityInYears As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ValidityInYears : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.ValidityInYears" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.validityInYears")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a40c-153">Ruft ab oder legt die Dauer in Jahren (muss zwischen 1 und 3 liegen) fest.</span><span class="sxs-lookup"><span data-stu-id="5a40c-153">Gets or sets duration in years (must be between 1 and 3).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>