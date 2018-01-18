<Type Name="ServiceSasParameters" FullName="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters">
  <TypeSignature Language="C#" Value="public class ServiceSasParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceSasParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceSasParameters" />
  <TypeSignature Language="F#" Value="type ServiceSasParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9dea7-101">Die Parameter Liste SAS-Dienstanmeldeinformationen einer Eintragsduplikate-Ressource.</span><span class="sxs-lookup"><span data-stu-id="9dea7-101">The parameters to list service SAS credentials of a speicific resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceSasParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-102">Initialisiert eine neue Instanz der ServiceSasParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9dea7-102">Initializes a new instance of the ServiceSasParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceSasParameters (string canonicalizedResource, string resource, string permissions = null, string iPAddressOrRange = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.HttpProtocol&gt; protocols = null, Nullable&lt;DateTime&gt; sharedAccessStartTime = null, Nullable&lt;DateTime&gt; sharedAccessExpiryTime = null, string identifier = null, string partitionKeyStart = null, string partitionKeyEnd = null, string rowKeyStart = null, string rowKeyEnd = null, string keyToSign = null, string cacheControl = null, string contentDisposition = null, string contentEncoding = null, string contentLanguage = null, string contentType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string canonicalizedResource, string resource, string permissions, string iPAddressOrRange, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.HttpProtocol&gt; protocols, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; sharedAccessStartTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; sharedAccessExpiryTime, string identifier, string partitionKeyStart, string partitionKeyEnd, string rowKeyStart, string rowKeyEnd, string keyToSign, string cacheControl, string contentDisposition, string contentEncoding, string contentLanguage, string contentType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.#ctor(System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Storage.Models.HttpProtocol},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (canonicalizedResource As String, resource As String, Optional permissions As String = null, Optional iPAddressOrRange As String = null, Optional protocols As Nullable(Of HttpProtocol) = null, Optional sharedAccessStartTime As Nullable(Of DateTime) = null, Optional sharedAccessExpiryTime As Nullable(Of DateTime) = null, Optional identifier As String = null, Optional partitionKeyStart As String = null, Optional partitionKeyEnd As String = null, Optional rowKeyStart As String = null, Optional rowKeyEnd As String = null, Optional keyToSign As String = null, Optional cacheControl As String = null, Optional contentDisposition As String = null, Optional contentEncoding As String = null, Optional contentLanguage As String = null, Optional contentType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.ServiceSasParameters : string * string * string * string * Nullable&lt;Microsoft.Azure.Management.Storage.Models.HttpProtocol&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * string * string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Storage.Models.ServiceSasParameters" Usage="new Microsoft.Azure.Management.Storage.Models.ServiceSasParameters (canonicalizedResource, resource, permissions, iPAddressOrRange, protocols, sharedAccessStartTime, sharedAccessExpiryTime, identifier, partitionKeyStart, partitionKeyEnd, rowKeyStart, rowKeyEnd, keyToSign, cacheControl, contentDisposition, contentEncoding, contentLanguage, contentType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="canonicalizedResource" Type="System.String" />
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="permissions" Type="System.String" />
        <Parameter Name="iPAddressOrRange" Type="System.String" />
        <Parameter Name="protocols" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.HttpProtocol&gt;" />
        <Parameter Name="sharedAccessStartTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="sharedAccessExpiryTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="identifier" Type="System.String" />
        <Parameter Name="partitionKeyStart" Type="System.String" />
        <Parameter Name="partitionKeyEnd" Type="System.String" />
        <Parameter Name="rowKeyStart" Type="System.String" />
        <Parameter Name="rowKeyEnd" Type="System.String" />
        <Parameter Name="keyToSign" Type="System.String" />
        <Parameter Name="cacheControl" Type="System.String" />
        <Parameter Name="contentDisposition" Type="System.String" />
        <Parameter Name="contentEncoding" Type="System.String" />
        <Parameter Name="contentLanguage" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="canonicalizedResource"><span data-ttu-id="9dea7-103">Den kanonischen Pfad zur signierten Ressource.</span><span class="sxs-lookup"><span data-stu-id="9dea7-103">The canonical path to the signed resource.</span></span></param>
        <param name="resource"><span data-ttu-id="9dea7-104">Die signierten Dienste zugegriffen werden kann mit dem SAS-Dienst.</span><span class="sxs-lookup"><span data-stu-id="9dea7-104">The signed services accessible with the service SAS.</span></span> <span data-ttu-id="9dea7-105">Folgende Werte sind möglich: Blob, (b), Container (c), Datei (f), Freigabe ("s").</span><span class="sxs-lookup"><span data-stu-id="9dea7-105">Possible values include: Blob (b), Container (c), File (f), Share (s).</span></span> <span data-ttu-id="9dea7-106">Folgende Werte sind möglich: "b", "c", "f", der "</span><span class="sxs-lookup"><span data-stu-id="9dea7-106">Possible values include: 'b', 'c', 'f', 's'</span></span></param>
        <param name="permissions"><span data-ttu-id="9dea7-107">Die signierten Berechtigungen für den SAS-Dienst.</span><span class="sxs-lookup"><span data-stu-id="9dea7-107">The signed permissions for the service SAS.</span></span> <span data-ttu-id="9dea7-108">Folgende Werte sind möglich: Lese-(R) Write (w), Delete (d), (l), (a) hinzufügen und erstellen (c), aktualisieren (u) und verarbeiten (p).</span><span class="sxs-lookup"><span data-stu-id="9dea7-108">Possible values include: Read (r), Write (w), Delete (d), List (l), Add (a), Create (c), Update (u) and Process (p).</span></span> <span data-ttu-id="9dea7-109">Folgende Werte sind möglich: verdächtigem "R", ","w","l","a","C","u","p"</span><span class="sxs-lookup"><span data-stu-id="9dea7-109">Possible values include: 'r', 'd', 'w', 'l', 'a', 'c', 'u', 'p'</span></span></param>
        <param name="iPAddressOrRange"><span data-ttu-id="9dea7-110">Eine IP-Adresse oder einen Bereich von IP-Adressen aus dem Anforderungen zu akzeptieren.</span><span class="sxs-lookup"><span data-stu-id="9dea7-110">An IP address or a range of IP addresses from which to accept requests.</span></span></param>
        <param name="protocols"><span data-ttu-id="9dea7-111">Das Protokoll zulässig für eine Anforderung mit dem SAS-Konto.</span><span class="sxs-lookup"><span data-stu-id="9dea7-111">The protocol permitted for a request made with the account SAS.</span></span> <span data-ttu-id="9dea7-112">Folgende Werte sind möglich: "Https und http", "Https"</span><span class="sxs-lookup"><span data-stu-id="9dea7-112">Possible values include: 'https,http', 'https'</span></span></param>
        <param name="sharedAccessStartTime"><span data-ttu-id="9dea7-113">Der Zeitpunkt, ab dem die SAS gültig wird.</span><span class="sxs-lookup"><span data-stu-id="9dea7-113">The time at which the SAS becomes valid.</span></span></param>
        <param name="sharedAccessExpiryTime"><span data-ttu-id="9dea7-114">Der Zeitpunkt, an dem die SAS ungültig wird.</span><span class="sxs-lookup"><span data-stu-id="9dea7-114">The time at which the shared access signature becomes invalid.</span></span></param>
        <param name="identifier"><span data-ttu-id="9dea7-115">Ein eindeutiger Wert bis zu 64 Zeichen lang, die mit einer Zugriffsrichtlinie für den Container, eine Warteschlange oder eine Tabelle angegeben korreliert.</span><span class="sxs-lookup"><span data-stu-id="9dea7-115">A unique value up to 64 characters in length that correlates to an access policy specified for the container, queue, or table.</span></span></param>
        <param name="partitionKeyStart"><span data-ttu-id="9dea7-116">Der Beginn des Partitionsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="9dea7-116">The start of partition key.</span></span></param>
        <param name="partitionKeyEnd"><span data-ttu-id="9dea7-117">Das Ende des Partitionsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="9dea7-117">The end of partition key.</span></span></param>
        <param name="rowKeyStart"><span data-ttu-id="9dea7-118">Der Beginn des Zeilenschlüssel.</span><span class="sxs-lookup"><span data-stu-id="9dea7-118">The start of row key.</span></span></param>
        <param name="rowKeyEnd"><span data-ttu-id="9dea7-119">Das Ende des Zeilenschlüssel.</span><span class="sxs-lookup"><span data-stu-id="9dea7-119">The end of row key.</span></span></param>
        <param name="keyToSign"><span data-ttu-id="9dea7-120">Der Schlüssel zum Signieren des Konto-SAS-Tokens mit.</span><span class="sxs-lookup"><span data-stu-id="9dea7-120">The key to sign the account SAS token with.</span></span></param>
        <param name="cacheControl"><span data-ttu-id="9dea7-121">Der Antwortheader für cachesteuerelement überschreiben.</span><span class="sxs-lookup"><span data-stu-id="9dea7-121">The response header override for cache control.</span></span></param>
        <param name="contentDisposition"><span data-ttu-id="9dea7-122">Der Antwortheader für die Content-Disposition überschreiben.</span><span class="sxs-lookup"><span data-stu-id="9dea7-122">The response header override for content disposition.</span></span></param>
        <param name="contentEncoding"><span data-ttu-id="9dea7-123">Der Antwortheader für inhaltscodierung überschreiben.</span><span class="sxs-lookup"><span data-stu-id="9dea7-123">The response header override for content encoding.</span></span></param>
        <param name="contentLanguage"><span data-ttu-id="9dea7-124">Der Antwortheader für die Sprache für Inhalt überschreiben.</span><span class="sxs-lookup"><span data-stu-id="9dea7-124">The response header override for content language.</span></span></param>
        <param name="contentType"><span data-ttu-id="9dea7-125">Der Antwortheader für den Inhaltstyp überschreiben.</span><span class="sxs-lookup"><span data-stu-id="9dea7-125">The response header override for content type.</span></span></param>
        <summary>
            <span data-ttu-id="9dea7-126">Initialisiert eine neue Instanz der ServiceSasParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9dea7-126">Initializes a new instance of the ServiceSasParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CacheControl">
      <MemberSignature Language="C#" Value="public string CacheControl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CacheControl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.CacheControl" />
      <MemberSignature Language="VB.NET" Value="Public Property CacheControl As String" />
      <MemberSignature Language="F#" Value="member this.CacheControl : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.CacheControl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rscc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-127">Ruft ab oder legt die Antwort-Header-Außerkraftsetzung für Cache-Control.</span><span class="sxs-lookup"><span data-stu-id="9dea7-127">Gets or sets the response header override for cache control.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanonicalizedResource">
      <MemberSignature Language="C#" Value="public string CanonicalizedResource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CanonicalizedResource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.CanonicalizedResource" />
      <MemberSignature Language="VB.NET" Value="Public Property CanonicalizedResource As String" />
      <MemberSignature Language="F#" Value="member this.CanonicalizedResource : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.CanonicalizedResource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="canonicalizedResource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-128">Ruft ab oder legt den kanonischen Pfad zur signierten Ressource.</span><span class="sxs-lookup"><span data-stu-id="9dea7-128">Gets or sets the canonical path to the signed resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentDisposition">
      <MemberSignature Language="C#" Value="public string ContentDisposition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentDisposition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.ContentDisposition" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentDisposition As String" />
      <MemberSignature Language="F#" Value="member this.ContentDisposition : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.ContentDisposition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rscd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-129">Ruft ab oder legt die Antwort Header Außerkraftsetzung für die Content-Disposition.</span><span class="sxs-lookup"><span data-stu-id="9dea7-129">Gets or sets the response header override for content disposition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentEncoding">
      <MemberSignature Language="C#" Value="public string ContentEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.ContentEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentEncoding As String" />
      <MemberSignature Language="F#" Value="member this.ContentEncoding : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.ContentEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rsce")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-130">Ruft ab oder legt die Antwort-Header-Außerkraftsetzung für die inhaltscodierung.</span><span class="sxs-lookup"><span data-stu-id="9dea7-130">Gets or sets the response header override for content encoding.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLanguage">
      <MemberSignature Language="C#" Value="public string ContentLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.ContentLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentLanguage As String" />
      <MemberSignature Language="F#" Value="member this.ContentLanguage : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.ContentLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rscl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-131">Ruft ab oder legt die Antwort Header Außerkraftsetzung für die Sprache für Inhalt.</span><span class="sxs-lookup"><span data-stu-id="9dea7-131">Gets or sets the response header override for content language.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rsct")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-132">Ruft ab oder legt die Antwort Header Außerkraftsetzung für den Inhaltstyp.</span><span class="sxs-lookup"><span data-stu-id="9dea7-132">Gets or sets the response header override for content type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identifier">
      <MemberSignature Language="C#" Value="public string Identifier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Identifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.Identifier" />
      <MemberSignature Language="VB.NET" Value="Public Property Identifier As String" />
      <MemberSignature Language="F#" Value="member this.Identifier : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.Identifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="signedIdentifier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-133">Ruft ab oder legt einen eindeutigen Wert bis zu 64 Zeichen lang, die mit einer Zugriffsrichtlinie für den Container, eine Warteschlange oder eine Tabelle angegeben korreliert.</span><span class="sxs-lookup"><span data-stu-id="9dea7-133">Gets or sets a unique value up to 64 characters in length that correlates to an access policy specified for the container, queue, or table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IPAddressOrRange">
      <MemberSignature Language="C#" Value="public string IPAddressOrRange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IPAddressOrRange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.IPAddressOrRange" />
      <MemberSignature Language="VB.NET" Value="Public Property IPAddressOrRange As String" />
      <MemberSignature Language="F#" Value="member this.IPAddressOrRange : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.IPAddressOrRange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="signedIp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-134">Ruft ab, oder legt sie fest, eine IP-Adresse oder einen Bereich von IP-Adressen aus dem Anforderungen zu akzeptieren.</span><span class="sxs-lookup"><span data-stu-id="9dea7-134">Gets or sets an IP address or a range of IP addresses from which to accept requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyToSign">
      <MemberSignature Language="C#" Value="public string KeyToSign { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyToSign" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.KeyToSign" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyToSign As String" />
      <MemberSignature Language="F#" Value="member this.KeyToSign : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.KeyToSign" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyToSign")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-135">Ruft ab oder legt den Schlüssel zum Signieren des Konto-SAS-Tokens mit fest.</span><span class="sxs-lookup"><span data-stu-id="9dea7-135">Gets or sets the key to sign the account SAS token with.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyEnd">
      <MemberSignature Language="C#" Value="public string PartitionKeyEnd { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.PartitionKeyEnd" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKeyEnd As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyEnd : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.PartitionKeyEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endPk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-136">Ruft ab oder legt das Ende des Partitionsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="9dea7-136">Gets or sets the end of partition key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyStart">
      <MemberSignature Language="C#" Value="public string PartitionKeyStart { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.PartitionKeyStart" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKeyStart As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyStart : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.PartitionKeyStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startPk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-137">Ruft ab oder legt den Anfang Partitionsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="9dea7-137">Gets or sets the start of partition key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permissions">
      <MemberSignature Language="C#" Value="public string Permissions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Permissions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.Permissions" />
      <MemberSignature Language="VB.NET" Value="Public Property Permissions As String" />
      <MemberSignature Language="F#" Value="member this.Permissions : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.Permissions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="signedPermission")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-138">Abrufen oder Festlegen der Berechtigungen für den Dienst SAS mit Vorzeichen.</span><span class="sxs-lookup"><span data-stu-id="9dea7-138">Gets or sets the signed permissions for the service SAS.</span></span> <span data-ttu-id="9dea7-139">Folgende Werte sind möglich: Lese-(R) Write (w), Delete (d), (l), (a) hinzufügen und erstellen (c), aktualisieren (u) und verarbeiten (p).</span><span class="sxs-lookup"><span data-stu-id="9dea7-139">Possible values include: Read (r), Write (w), Delete (d), List (l), Add (a), Create (c), Update (u) and Process (p).</span></span> <span data-ttu-id="9dea7-140">Folgende Werte sind möglich: verdächtigem "R", ","w","l","a","C","u","p"</span><span class="sxs-lookup"><span data-stu-id="9dea7-140">Possible values include: 'r', 'd', 'w', 'l', 'a', 'c', 'u', 'p'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocols">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.HttpProtocol&gt; Protocols { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.HttpProtocol&gt; Protocols" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.Protocols" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocols As Nullable(Of HttpProtocol)" />
      <MemberSignature Language="F#" Value="member this.Protocols : Nullable&lt;Microsoft.Azure.Management.Storage.Models.HttpProtocol&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.Protocols" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="signedProtocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.HttpProtocol&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-141">Abrufen oder Festlegen des Protokolls für eine Anforderung mit dem SAS-Konto zulässig.</span><span class="sxs-lookup"><span data-stu-id="9dea7-141">Gets or sets the protocol permitted for a request made with the account SAS.</span></span> <span data-ttu-id="9dea7-142">Folgende Werte sind möglich: "Https und http", "Https"</span><span class="sxs-lookup"><span data-stu-id="9dea7-142">Possible values include: 'https,http', 'https'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resource">
      <MemberSignature Language="C#" Value="public string Resource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.Resource" />
      <MemberSignature Language="VB.NET" Value="Public Property Resource As String" />
      <MemberSignature Language="F#" Value="member this.Resource : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.Resource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="signedResource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-143">Ermittelt oder definiert die signierte Dienste mit dem Dienst SAS zugegriffen werden kann.</span><span class="sxs-lookup"><span data-stu-id="9dea7-143">Gets or sets the signed services accessible with the service SAS.</span></span>
            <span data-ttu-id="9dea7-144">Folgende Werte sind möglich: Blob, (b), Container (c), Datei (f), Freigabe ("s").</span><span class="sxs-lookup"><span data-stu-id="9dea7-144">Possible values include: Blob (b), Container (c), File (f), Share (s).</span></span> <span data-ttu-id="9dea7-145">Folgende Werte sind möglich: "b", "c", "f", der "</span><span class="sxs-lookup"><span data-stu-id="9dea7-145">Possible values include: 'b', 'c', 'f', 's'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKeyEnd">
      <MemberSignature Language="C#" Value="public string RowKeyEnd { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKeyEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.RowKeyEnd" />
      <MemberSignature Language="VB.NET" Value="Public Property RowKeyEnd As String" />
      <MemberSignature Language="F#" Value="member this.RowKeyEnd : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.RowKeyEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endRk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-146">Ruft ab oder legt das Ende des Zeilenschlüssel.</span><span class="sxs-lookup"><span data-stu-id="9dea7-146">Gets or sets the end of row key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKeyStart">
      <MemberSignature Language="C#" Value="public string RowKeyStart { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKeyStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.RowKeyStart" />
      <MemberSignature Language="VB.NET" Value="Public Property RowKeyStart As String" />
      <MemberSignature Language="F#" Value="member this.RowKeyStart : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.RowKeyStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startRk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-147">Ruft ab oder legt den Anfang Zeilenschlüssel.</span><span class="sxs-lookup"><span data-stu-id="9dea7-147">Gets or sets the start of row key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessExpiryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; SharedAccessExpiryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; SharedAccessExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.SharedAccessExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessExpiryTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessExpiryTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.SharedAccessExpiryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="signedExpiry")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-148">Ruft ab oder legt die Zeit, an der die SAS ungültig wird.</span><span class="sxs-lookup"><span data-stu-id="9dea7-148">Gets or sets the time at which the shared access signature becomes invalid.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; SharedAccessStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; SharedAccessStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.SharedAccessStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.SharedAccessStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="signedStart")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-149">Ruft ab oder legt die Zeit, an der die SAS gültig wird.</span><span class="sxs-lookup"><span data-stu-id="9dea7-149">Gets or sets the time at which the SAS becomes valid.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.ServiceSasParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="serviceSasParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9dea7-150">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="9dea7-150">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9dea7-151">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="9dea7-151">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>