<Type Name="WebHttpRelayBinding" FullName="Microsoft.ServiceBus.WebHttpRelayBinding">
  <TypeSignature Language="C#" Value="public class WebHttpRelayBinding : System.ServiceModel.Channels.Binding, System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebHttpRelayBinding extends System.ServiceModel.Channels.Binding implements class System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.WebHttpRelayBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class WebHttpRelayBinding&#xA;Inherits Binding&#xA;Implements IBindingRuntimePreferences" />
  <TypeSignature Language="F#" Value="type WebHttpRelayBinding = class&#xA;    inherit Binding&#xA;    interface IBindingRuntimePreferences" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Channels.Binding</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Channels.IBindingRuntimePreferences</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="6e67b-101">Eine Bindung, die zum Konfigurieren von Endpunkten für Webdienste, die durch HTTP-Anforderungen und nicht durch SOAP-Nachrichten bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="6e67b-101">A binding used to configure endpoints for Web services that are exposed through HTTP requests instead of SOAP messages.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebHttpRelayBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WebHttpRelayBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6e67b-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6e67b-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" /> class.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebHttpRelayBinding (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WebHttpRelayBinding.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configurationName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.WebHttpRelayBinding : string -&gt; Microsoft.ServiceBus.WebHttpRelayBinding" Usage="new Microsoft.ServiceBus.WebHttpRelayBinding configurationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configurationName"><span data-ttu-id="6e67b-103">Die zu verwendende Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="6e67b-103">The configuration to use.</span></span></param>
        <summary><span data-ttu-id="6e67b-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" /> -Klasse mit dem angegebenen Konfigurationsnamen.</span><span class="sxs-lookup"><span data-stu-id="6e67b-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" /> class using the specified configuration name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebHttpRelayBinding (Microsoft.ServiceBus.EndToEndWebHttpSecurityMode securityMode, Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndWebHttpSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WebHttpRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndWebHttpSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.WebHttpRelayBinding : Microsoft.ServiceBus.EndToEndWebHttpSecurityMode * Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.WebHttpRelayBinding" Usage="new Microsoft.ServiceBus.WebHttpRelayBinding (securityMode, relayClientAuthenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="securityMode" Type="Microsoft.ServiceBus.EndToEndWebHttpSecurityMode" />
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="securityMode"><span data-ttu-id="6e67b-105">Mit der Bindung verwendeten Sicherheitstyp.</span><span class="sxs-lookup"><span data-stu-id="6e67b-105">The type of security used with the binding.</span></span></param>
        <param name="relayClientAuthenticationType"><span data-ttu-id="6e67b-106">Der Typ der Clientauthentifizierung auf das Relay verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6e67b-106">The type of client authentication used on the relay.</span></span> </param>
        <summary><span data-ttu-id="6e67b-107">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" /> -Klasse mithilfe des angegebenen Typs, der Sicherheit und Relay-Clientauthentifizierung.</span><span class="sxs-lookup"><span data-stu-id="6e67b-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" /> class using the specified type of security and relay client authentication.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.AllowCookies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e67b-108">Ruft ab oder legt einen Wert, der angibt, ob Cookies, in die Nachrichten zugelassen werden über die <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" />.</span><span class="sxs-lookup"><span data-stu-id="6e67b-108">Gets or sets a value that specifies whether cookies are allowed in the messages sent via the <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" />.</span></span></summary>
        <value><span data-ttu-id="6e67b-109">"Wahr" zurückgegeben, wenn Cookies zulässig sind; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="6e67b-109">Returns true if cookies are allowed; otherwise, false.</span></span> <span data-ttu-id="6e67b-110">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="6e67b-110">The default value is false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentTypeMapper">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Channels.WebContentTypeMapper ContentTypeMapper { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Channels.WebContentTypeMapper ContentTypeMapper" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.ContentTypeMapper" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentTypeMapper As WebContentTypeMapper" />
      <MemberSignature Language="F#" Value="member this.ContentTypeMapper : System.ServiceModel.Channels.WebContentTypeMapper with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.ContentTypeMapper" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.WebContentTypeMapper</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e67b-111">Ruft die Inhaltstypzuordnung ab bzw. legt sie fest.</span><span class="sxs-lookup"><span data-stu-id="6e67b-111">Gets or sets the content type mapper.</span></span></summary>
        <value><span data-ttu-id="6e67b-112">Die Inhaltstypzuordnung.</span><span class="sxs-lookup"><span data-stu-id="6e67b-112">The content type mapper.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBindingElements">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElementCollection CreateBindingElements ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElementCollection CreateBindingElements() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WebHttpRelayBinding.CreateBindingElements" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateBindingElements () As BindingElementCollection" />
      <MemberSignature Language="F#" Value="override this.CreateBindingElements : unit -&gt; System.ServiceModel.Channels.BindingElementCollection" Usage="webHttpRelayBinding.CreateBindingElements " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.BindingElementCollection</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6e67b-113">Erstellt eine Auflistung mit den Bindungselementen für die Bindung.</span><span class="sxs-lookup"><span data-stu-id="6e67b-113">Creates a collection with the binding elements for the binding.</span></span></summary>
        <returns><span data-ttu-id="6e67b-114">Gibt eine <see cref="T:System.ServiceModel.Channels.BindingElementCollection" /> , enthält den geordneten Stapel mit Bindungselementen, die verwendet werden, indem Sie die <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" />.</span><span class="sxs-lookup"><span data-stu-id="6e67b-114">Returns a <see cref="T:System.ServiceModel.Channels.BindingElementCollection" /> that contains the ordered stack of binding elements used by the <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvelopeVersion">
      <MemberSignature Language="C#" Value="public System.ServiceModel.EnvelopeVersion EnvelopeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.EnvelopeVersion EnvelopeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.EnvelopeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvelopeVersion As EnvelopeVersion" />
      <MemberSignature Language="F#" Value="member this.EnvelopeVersion : System.ServiceModel.EnvelopeVersion" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.EnvelopeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.EnvelopeVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e67b-115">Ruft die SOAP-Umschlagversion ab.</span><span class="sxs-lookup"><span data-stu-id="6e67b-115">Gets the SOAP envelope version.</span></span> </summary>
        <value><span data-ttu-id="6e67b-116">Gibt einen Wert vom Typ <see cref="T:System.ServiceModel.EnvelopeVersion" /> zurück.</span><span class="sxs-lookup"><span data-stu-id="6e67b-116">Returns a <see cref="T:System.ServiceModel.EnvelopeVersion" />.</span></span> <span data-ttu-id="6e67b-117">Da die <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" /> immer gibt EnvelopeVersion.None SOAP nicht verwendet.<see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" /></span><span class="sxs-lookup"><span data-stu-id="6e67b-117">Since the <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" /> does not use SOAP, this always returns EnvelopeVersion.None.<see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" /></span></span> <span data-ttu-id="6e67b-118">die Bindung, die Sie für SOAP verwendet werden sollte ist nicht wahrscheinlich messaging.</span><span class="sxs-lookup"><span data-stu-id="6e67b-118">is not likely the binding you should be using for SOAP messaging.</span></span> <span data-ttu-id="6e67b-119">Allerdings wird die Service Bus SOAP unterstützt.</span><span class="sxs-lookup"><span data-stu-id="6e67b-119">However, Service Bus does support SOAP.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e67b-120">Abrufen oder Festlegen des Vergleichsmodus, der auf den Namen des Hosts verwendet.</span><span class="sxs-lookup"><span data-stu-id="6e67b-120">Gets or sets the comparison mode used on the host name.</span></span></summary>
        <value><span data-ttu-id="6e67b-121">Der Vergleichsmodus auf den Namen des Hosts verwendet.</span><span class="sxs-lookup"><span data-stu-id="6e67b-121">The comparison mode used on the host name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e67b-122">Ruft ab oder legt fest, ob die RelayBindung dynamisch ist.</span><span class="sxs-lookup"><span data-stu-id="6e67b-122">Gets or sets whether the relay binding is dynamic.</span></span></summary>
        <value><span data-ttu-id="6e67b-123">"true", wenn die RelayBindung dynamisch ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="6e67b-123">true if the relay binding is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e67b-124">Ruft ab oder legt die maximale Größe des Pufferpools, die vom Transport.</span><span class="sxs-lookup"><span data-stu-id="6e67b-124">Gets or sets the maximum buffer pool size used by the transport.</span></span></summary>
        <value><span data-ttu-id="6e67b-125">Gibt die maximale Größe des Pufferpools.</span><span class="sxs-lookup"><span data-stu-id="6e67b-125">Returns the maximum buffer pool size.</span></span> <span data-ttu-id="6e67b-126">Der Standardwert ist 524288 Bytes.</span><span class="sxs-lookup"><span data-stu-id="6e67b-126">The default is 524288 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e67b-127">Ruft ab oder legt die maximale Puffergröße, die vom Transport unterstützt.</span><span class="sxs-lookup"><span data-stu-id="6e67b-127">Gets or sets the maximum buffer size supported by the transport.</span></span> </summary>
        <value><span data-ttu-id="6e67b-128">Gibt die maximale Puffergröße.</span><span class="sxs-lookup"><span data-stu-id="6e67b-128">Returns the max buffer size.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.MaxReceivedMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e67b-129">Ruft die maximal zulässige Nachrichtengröße ab oder legt die Größe fest, die empfangen werden kann.</span><span class="sxs-lookup"><span data-stu-id="6e67b-129">Gets or sets the maximum allowable message size that can be received.</span></span></summary>
        <value><span data-ttu-id="6e67b-130">Gibt die maximale zulässige Nachrichtengröße zurück.</span><span class="sxs-lookup"><span data-stu-id="6e67b-130">Returns the maximum allowable message size.</span></span> <span data-ttu-id="6e67b-131">Die Standardgröße beträgt 65.536 Bytes.</span><span class="sxs-lookup"><span data-stu-id="6e67b-131">The default size is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAddress">
      <MemberSignature Language="C#" Value="public Uri ProxyAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ProxyAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.ProxyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.ProxyAddress : Uri with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.ProxyAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e67b-132">Ruft einen URI ab oder legt ihn fest, der die Adresse des Proxys enthält, der für HTTP-Anforderungen verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6e67b-132">Gets or sets a URI that contains the address of the proxy to use for HTTP requests.</span></span></summary>
        <value><span data-ttu-id="6e67b-133">Gibt eine <see cref="T:System.Uri" /> , enthält die Adresse des Proxyservers, der für HTTP-Anforderungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="6e67b-133">Returns a <see cref="T:System.Uri" /> that contains the address of the proxy to use for HTTP requests.</span></span> <span data-ttu-id="6e67b-134">Der Standardwert ist NULL.</span><span class="sxs-lookup"><span data-stu-id="6e67b-134">The default value is null.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public System.Xml.XmlDictionaryReaderQuotas ReaderQuotas { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Xml.XmlDictionaryReaderQuotas ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public Property ReaderQuotas As XmlDictionaryReaderQuotas" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : System.Xml.XmlDictionaryReaderQuotas with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.ReaderQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.XmlDictionaryReaderQuotas</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e67b-135">Ruft ab oder legt XML-readerkontingente auf die verarbeiteten Nachrichten fest.</span><span class="sxs-lookup"><span data-stu-id="6e67b-135">Gets or sets xml reader quotas on the messages processed.</span></span></summary>
        <value><span data-ttu-id="6e67b-136">Gibt eine <see cref="T:System.Xml.XmlDictionaryReaderQuotas" /> , die die readerkontingente enthält.</span><span class="sxs-lookup"><span data-stu-id="6e67b-136">Returns a <see cref="T:System.Xml.XmlDictionaryReaderQuotas" /> that contains the reader quotas.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e67b-137">Ruft das Schema für die Endpunkte, die mit der Bindung verwendet.</span><span class="sxs-lookup"><span data-stu-id="6e67b-137">Gets the scheme for the endpoints used with the binding.</span></span></summary>
        <value><span data-ttu-id="6e67b-138">Gibt das Schema zurück.</span><span class="sxs-lookup"><span data-stu-id="6e67b-138">Returns the scheme.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.WebHttpRelaySecurity Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.WebHttpRelaySecurity Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As WebHttpRelaySecurity" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.WebHttpRelaySecurity" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.WebHttpRelaySecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e67b-139">Ruft die Sicherheitseinstellungen für die aktuelle Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="6e67b-139">Gets the security settings for the current instance.</span></span></summary>
        <value><span data-ttu-id="6e67b-140">Gibt eine <see cref="T:Microsoft.ServiceBus.WebHttpRelaySecurity" /> , das die Sicherheitseinstellungen enthält.</span><span class="sxs-lookup"><span data-stu-id="6e67b-140">Returns a <see cref="T:Microsoft.ServiceBus.WebHttpRelaySecurity" /> that contains the security settings.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously">
      <MemberSignature Language="C#" Value="bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.System#ServiceModel#Channels#IBindingRuntimePreferences#ReceiveSynchronously" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property ReceiveSynchronously As Boolean Implements IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="F#" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e67b-141">Gibt an, dass eingehende Anforderungen asynchron gehandhabt werden.</span><span class="sxs-lookup"><span data-stu-id="6e67b-141">Indicates that incoming requests are handled asynchronously.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e67b-142">Ruft den Übertragungsmodus ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="6e67b-142">Gets or sets the transfer mode.</span></span></summary>
        <value><span data-ttu-id="6e67b-143">Gibt eine <see cref="T:System.ServiceModel.TransferMode" /> , die den Übertragungsmodus enthält.</span><span class="sxs-lookup"><span data-stu-id="6e67b-143">Returns a <see cref="T:System.ServiceModel.TransferMode" /> that contains the transfer mode.</span></span> <span data-ttu-id="6e67b-144">Der Standardwert ist Buffered.</span><span class="sxs-lookup"><span data-stu-id="6e67b-144">The default is Buffered.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultWebProxy">
      <MemberSignature Language="C#" Value="public bool UseDefaultWebProxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultWebProxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.UseDefaultWebProxy" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultWebProxy As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultWebProxy : bool with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.UseDefaultWebProxy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e67b-145">Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Proxyeinstellungen auf dem Computer anstatt der benutzerspezifischen Einstellungen verwendet werden sollen.</span><span class="sxs-lookup"><span data-stu-id="6e67b-145">Gets or sets a value that indicates whether the machine-wide proxy settings are used rather than the user specific settings.</span></span></summary>
        <value><span data-ttu-id="6e67b-146">"true", wenn die computerweite Proxyeinstellungen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="6e67b-146">true if machine-wide proxy settings are used.</span></span> <span data-ttu-id="6e67b-147">Andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="6e67b-147">Otherwise false.</span></span> <span data-ttu-id="6e67b-148">Die Standardeinstellung ist "true".</span><span class="sxs-lookup"><span data-stu-id="6e67b-148">The default setting is true.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding WriteEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding WriteEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.WriteEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.WriteEncoding : System.Text.Encoding with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.WriteEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Text.Encoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e67b-149">Ruft die Zeichencodierung ab, oder legt die Zeichencodierung fest, die zum Schreiben des Nachrichtentextes verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="6e67b-149">Gets or sets the character encoding that is used to write the message text.</span></span></summary>
        <value><span data-ttu-id="6e67b-150">Gibt eine <see cref="T:System.Text.Encoding" /> , das die Codierung enthält.</span><span class="sxs-lookup"><span data-stu-id="6e67b-150">Returns a <see cref="T:System.Text.Encoding" /> that contains the encoding.</span></span> <span data-ttu-id="6e67b-151">Der Standardwert ist utf8encoding.</span><span class="sxs-lookup"><span data-stu-id="6e67b-151">The default value is utf8encoding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>