<Type Name="AmazonMWSLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService">
  <TypeSignature Language="C#" Value="public class AmazonMWSLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AmazonMWSLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AmazonMWSLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type AmazonMWSLinkedService = class&#xA;    inherit LinkedService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.LinkedService</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("AmazonMWS")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5214b-101">Amazon-Marketplace-Webdienst verknüpfter Dienst.</span><span class="sxs-lookup"><span data-stu-id="5214b-101">Amazon Marketplace Web Service linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonMWSLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5214b-102">Initialisiert eine neue Instanz der AmazonMWSLinkedService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5214b-102">Initializes a new instance of the AmazonMWSLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonMWSLinkedService (object endpoint, object marketplaceID, object sellerID, object accessKeyId, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase mwsAuthToken = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase secretKey = null, object useEncryptedEndpoints = null, object useHostVerification = null, object usePeerVerification = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object endpoint, object marketplaceID, object sellerID, object accessKeyId, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, class Microsoft.Azure.Management.DataFactory.Models.SecretBase mwsAuthToken, class Microsoft.Azure.Management.DataFactory.Models.SecretBase secretKey, object useEncryptedEndpoints, object useHostVerification, object usePeerVerification, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.#ctor(System.Object,System.Object,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,Microsoft.Azure.Management.DataFactory.Models.SecretBase,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpoint As Object, marketplaceID As Object, sellerID As Object, accessKeyId As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional mwsAuthToken As SecretBase = null, Optional secretKey As SecretBase = null, Optional useEncryptedEndpoints As Object = null, Optional useHostVerification As Object = null, Optional usePeerVerification As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService : obj * obj * obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * Microsoft.Azure.Management.DataFactory.Models.SecretBase * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService (endpoint, marketplaceID, sellerID, accessKeyId, additionalProperties, connectVia, description, mwsAuthToken, secretKey, useEncryptedEndpoints, useHostVerification, usePeerVerification, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Object" />
        <Parameter Name="marketplaceID" Type="System.Object" />
        <Parameter Name="sellerID" Type="System.Object" />
        <Parameter Name="accessKeyId" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="mwsAuthToken" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="secretKey" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="useEncryptedEndpoints" Type="System.Object" />
        <Parameter Name="useHostVerification" Type="System.Object" />
        <Parameter Name="usePeerVerification" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="5214b-103">Der Endpunkt der Amazon MWS-Servers (d. h. mws.amazonservices.com)</span><span class="sxs-lookup"><span data-stu-id="5214b-103">The endpoint of the Amazon MWS server, (i.e. mws.amazonservices.com)</span></span></param>
        <param name="marketplaceID"><span data-ttu-id="5214b-104">Die Amazon Marketplace-ID, aus der Daten abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="5214b-104">The Amazon Marketplace ID you want to retrieve data from.</span></span> <span data-ttu-id="5214b-105">Zum Abrufen von Daten aus mehreren Marketplace-IDs trennen Sie diese durch ein Komma (,) ein.</span><span class="sxs-lookup"><span data-stu-id="5214b-105">To retrive data from multiple Marketplace IDs, seperate them with a comma (,).</span></span> <span data-ttu-id="5214b-106">(d. h. A2EUQ1WTGCTBG2)</span><span class="sxs-lookup"><span data-stu-id="5214b-106">(i.e. A2EUQ1WTGCTBG2)</span></span></param>
        <param name="sellerID"><span data-ttu-id="5214b-107">Die Amazon-Verkäufer-ID.</span><span class="sxs-lookup"><span data-stu-id="5214b-107">The Amazon seller ID.</span></span></param>
        <param name="accessKeyId"><span data-ttu-id="5214b-108">Die Access-Id verwendet, um auf Daten zugreifen.</span><span class="sxs-lookup"><span data-stu-id="5214b-108">The access key id used to access data.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="5214b-109">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="5214b-109">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="5214b-110">Der Integration Common Language Runtime-Verweis.</span><span class="sxs-lookup"><span data-stu-id="5214b-110">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="5214b-111">Beschreibung des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="5214b-111">Linked service description.</span></span></param>
        <param name="mwsAuthToken"><span data-ttu-id="5214b-112">Das Amazon MWS-Authentifizierungstoken.</span><span class="sxs-lookup"><span data-stu-id="5214b-112">The Amazon MWS authentication token.</span></span></param>
        <param name="secretKey"><span data-ttu-id="5214b-113">Der geheime Schlüssel, mit dem auf Daten zugegriffen wird.</span><span class="sxs-lookup"><span data-stu-id="5214b-113">The secret key used to access data.</span></span></param>
        <param name="useEncryptedEndpoints"><span data-ttu-id="5214b-114">Gibt an, ob die Endpunkte der Datenquelle mit HTTPS verschlüsselt sind.</span><span class="sxs-lookup"><span data-stu-id="5214b-114">Specifies whether the data source endpoints are encrypted using HTTPS.</span></span> <span data-ttu-id="5214b-115">Der Standardwert lautet „true“.</span><span class="sxs-lookup"><span data-stu-id="5214b-115">The default value is true.</span></span></param>
        <param name="useHostVerification"><span data-ttu-id="5214b-116">Gibt an, ob der Hostname im Zertifikat des Servers mit dem Hostnamen des Servers übereinstimmen muss, wenn eine Verbindung über SSL hergestellt wird.</span><span class="sxs-lookup"><span data-stu-id="5214b-116">Specifies whether to require the host name in the server's certificate to match the host name of the server when connecting over SSL.</span></span> <span data-ttu-id="5214b-117">Der Standardwert lautet „true“.</span><span class="sxs-lookup"><span data-stu-id="5214b-117">The default value is true.</span></span></param>
        <param name="usePeerVerification"><span data-ttu-id="5214b-118">Gibt an, ob die Identität des Servers bei Verbindung über SSL überprüft werden soll.</span><span class="sxs-lookup"><span data-stu-id="5214b-118">Specifies whether to verify the identity of the server when connecting over SSL.</span></span> <span data-ttu-id="5214b-119">Der Standardwert lautet „true“.</span><span class="sxs-lookup"><span data-stu-id="5214b-119">The default value is true.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="5214b-120">Die verschlüsselten Anmeldeinformationen für die Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5214b-120">The encrypted credential used for authentication.</span></span> <span data-ttu-id="5214b-121">Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager.</span><span class="sxs-lookup"><span data-stu-id="5214b-121">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="5214b-122">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="5214b-122">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="5214b-123">Initialisiert eine neue Instanz der AmazonMWSLinkedService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5214b-123">Initializes a new instance of the AmazonMWSLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessKeyId">
      <MemberSignature Language="C#" Value="public object AccessKeyId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AccessKeyId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.AccessKeyId" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessKeyId As Object" />
      <MemberSignature Language="F#" Value="member this.AccessKeyId : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.AccessKeyId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.accessKeyId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5214b-124">Ruft ab oder legt die Access-Id, die auf Daten zugegriffen hat.</span><span class="sxs-lookup"><span data-stu-id="5214b-124">Gets or sets the access key id used to access data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.encryptedCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5214b-125">Ruft ab oder legt die verschlüsselte Anmeldeinformationen für die Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5214b-125">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="5214b-126">Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager.</span><span class="sxs-lookup"><span data-stu-id="5214b-126">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="5214b-127">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="5214b-127">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public object Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As Object" />
      <MemberSignature Language="F#" Value="member this.Endpoint : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5214b-128">Ruft ab oder legt den Endpunkt des Servers Amazon MWS, (d. h. mws.amazonservices.com)</span><span class="sxs-lookup"><span data-stu-id="5214b-128">Gets or sets the endpoint of the Amazon MWS server, (i.e. mws.amazonservices.com)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MarketplaceID">
      <MemberSignature Language="C#" Value="public object MarketplaceID { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object MarketplaceID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.MarketplaceID" />
      <MemberSignature Language="VB.NET" Value="Public Property MarketplaceID As Object" />
      <MemberSignature Language="F#" Value="member this.MarketplaceID : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.MarketplaceID" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.marketplaceID")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5214b-129">Ruft ab oder legt die Amazon-Marketplace-ID, die Daten abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="5214b-129">Gets or sets the Amazon Marketplace ID you want to retrieve data from.</span></span> <span data-ttu-id="5214b-130">Zum Abrufen von Daten aus mehreren Marketplace-IDs trennen Sie diese durch ein Komma (,) ein.</span><span class="sxs-lookup"><span data-stu-id="5214b-130">To retrive data from multiple Marketplace IDs, seperate them with a comma (,).</span></span> <span data-ttu-id="5214b-131">(d. h. A2EUQ1WTGCTBG2)</span><span class="sxs-lookup"><span data-stu-id="5214b-131">(i.e. A2EUQ1WTGCTBG2)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MwsAuthToken">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase MwsAuthToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase MwsAuthToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.MwsAuthToken" />
      <MemberSignature Language="VB.NET" Value="Public Property MwsAuthToken As SecretBase" />
      <MemberSignature Language="F#" Value="member this.MwsAuthToken : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.MwsAuthToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.mwsAuthToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5214b-132">Abrufen oder Festlegen der Amazon MWS Authentifizierungstoken.</span><span class="sxs-lookup"><span data-stu-id="5214b-132">Gets or sets the Amazon MWS authentication token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase SecretKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase SecretKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.SecretKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretKey As SecretBase" />
      <MemberSignature Language="F#" Value="member this.SecretKey : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.SecretKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.secretKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5214b-133">Ruft ab, oder legt ihn fest den geheimen Schlüssel, die auf Daten zugegriffen hat.</span><span class="sxs-lookup"><span data-stu-id="5214b-133">Gets or sets the secret key used to access data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SellerID">
      <MemberSignature Language="C#" Value="public object SellerID { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SellerID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.SellerID" />
      <MemberSignature Language="VB.NET" Value="Public Property SellerID As Object" />
      <MemberSignature Language="F#" Value="member this.SellerID : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.SellerID" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.sellerID")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5214b-134">Ruft ab oder legt die Amazon Verkäufer-ID.</span><span class="sxs-lookup"><span data-stu-id="5214b-134">Gets or sets the Amazon seller ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseEncryptedEndpoints">
      <MemberSignature Language="C#" Value="public object UseEncryptedEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseEncryptedEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UseEncryptedEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property UseEncryptedEndpoints As Object" />
      <MemberSignature Language="F#" Value="member this.UseEncryptedEndpoints : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UseEncryptedEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.useEncryptedEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5214b-135">Gibt an, ob die Quelle Datenendpunkte über HTTPS verschlüsselt werden, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="5214b-135">Gets or sets specifies whether the data source endpoints are encrypted using HTTPS.</span></span> <span data-ttu-id="5214b-136">Der Standardwert lautet „true“.</span><span class="sxs-lookup"><span data-stu-id="5214b-136">The default value is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseHostVerification">
      <MemberSignature Language="C#" Value="public object UseHostVerification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseHostVerification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UseHostVerification" />
      <MemberSignature Language="VB.NET" Value="Public Property UseHostVerification As Object" />
      <MemberSignature Language="F#" Value="member this.UseHostVerification : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UseHostVerification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.useHostVerification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5214b-137">Gibt an, ob der Hostname im Zertifikat des Servers, den Hostnamen des Servers entsprechend der Verbindungsaufbau über SSL erforderlich ist, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="5214b-137">Gets or sets specifies whether to require the host name in the server's certificate to match the host name of the server when connecting over SSL.</span></span> <span data-ttu-id="5214b-138">Der Standardwert lautet „true“.</span><span class="sxs-lookup"><span data-stu-id="5214b-138">The default value is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsePeerVerification">
      <MemberSignature Language="C#" Value="public object UsePeerVerification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UsePeerVerification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UsePeerVerification" />
      <MemberSignature Language="VB.NET" Value="Public Property UsePeerVerification As Object" />
      <MemberSignature Language="F#" Value="member this.UsePeerVerification : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.UsePeerVerification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.usePeerVerification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5214b-139">Gibt an, ob die Identität des Servers zu überprüfen, Verbindungsaufbau über SSL, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="5214b-139">Gets or sets specifies whether to verify the identity of the server when connecting over SSL.</span></span> <span data-ttu-id="5214b-140">Der Standardwert lautet „true“.</span><span class="sxs-lookup"><span data-stu-id="5214b-140">The default value is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonMWSLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="amazonMWSLinkedService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5214b-141">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="5214b-141">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5214b-142">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="5214b-142">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>