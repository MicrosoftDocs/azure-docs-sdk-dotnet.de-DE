<Type Name="BasicHttpRelayBinding" FullName="Microsoft.ServiceBus.BasicHttpRelayBinding">
  <TypeSignature Language="C#" Value="public class BasicHttpRelayBinding : System.ServiceModel.Channels.Binding, System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BasicHttpRelayBinding extends System.ServiceModel.Channels.Binding implements class System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class BasicHttpRelayBinding&#xA;Inherits Binding&#xA;Implements IBindingRuntimePreferences" />
  <TypeSignature Language="F#" Value="type BasicHttpRelayBinding = class&#xA;    inherit Binding&#xA;    interface IBindingRuntimePreferences" />
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
    <summary><span data-ttu-id="89c30-101">Stellt eine Bindung, die ein Client verwenden kann, zum Konfigurieren von Endpunkten kommunizieren können, die mit ASMX-basierten Webdiensten und anderen Diensten, die mit WS-I Basic Profile 1.1.</span><span class="sxs-lookup"><span data-stu-id="89c30-101">Represents a binding that a client can use to configure endpoints that can communicate with ASMX-based Web services and other services that conform to the WS-I Basic Profile 1.1.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BasicHttpRelayBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.BasicHttpRelayBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="89c30-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="89c30-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BasicHttpRelayBinding (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.BasicHttpRelayBinding.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configurationName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.BasicHttpRelayBinding : string -&gt; Microsoft.ServiceBus.BasicHttpRelayBinding" Usage="new Microsoft.ServiceBus.BasicHttpRelayBinding configurationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configurationName"><span data-ttu-id="89c30-103">Die zu verwendende Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="89c30-103">The configuration to use.</span></span> </param>
        <summary><span data-ttu-id="89c30-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> -Klasse unter Verwendung der angegebenen Konfigurations.</span><span class="sxs-lookup"><span data-stu-id="89c30-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> class using the specified configuration.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BasicHttpRelayBinding (Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode securityMode, Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.BasicHttpRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.BasicHttpRelayBinding : Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode * Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.BasicHttpRelayBinding" Usage="new Microsoft.ServiceBus.BasicHttpRelayBinding (securityMode, relayClientAuthenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="securityMode" Type="Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode" />
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="securityMode"><span data-ttu-id="89c30-105">Der Typ der Sicherheit, die die SOAP-Nachricht und für den Client verwendet.</span><span class="sxs-lookup"><span data-stu-id="89c30-105">The type of security used with the SOAP message and for the client.</span></span> </param>
        <param name="relayClientAuthenticationType"><span data-ttu-id="89c30-106">Der Typ des vom Client verwendeten Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="89c30-106">The type of authentication used by the client.</span></span> </param>
        <summary><span data-ttu-id="89c30-107">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> Klasse mit dem eines angegebenen Typs von der Bindung verwendeten Sicherheitstyp und die vom Client verwendete Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="89c30-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> class with a specified type of security used by the binding and the authentication type used by the client.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.AllowCookies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89c30-108">Ruft ab oder legt einen Wert, der bestimmt, ob der Client Cookies ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="89c30-108">Gets or sets a value that determines if the client allows cookies.</span></span></summary>
        <value><span data-ttu-id="89c30-109">Gibt <see cref="T:System.Boolean" />.True zurück, um Cookies zu ermöglichen, andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="89c30-109">Returns <see cref="T:System.Boolean" />.true to allow cookies; otherwise, false.</span></span> <span data-ttu-id="89c30-110">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="89c30-110">The default value is false.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBindingElements">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElementCollection CreateBindingElements ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElementCollection CreateBindingElements() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.BasicHttpRelayBinding.CreateBindingElements" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateBindingElements () As BindingElementCollection" />
      <MemberSignature Language="F#" Value="override this.CreateBindingElements : unit -&gt; System.ServiceModel.Channels.BindingElementCollection" Usage="basicHttpRelayBinding.CreateBindingElements " />
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
        <summary><span data-ttu-id="89c30-111">Gibt eine geordnete Auflistung von Bindungselementen zurück, die in der aktuellen Bindung enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="89c30-111">Returns an ordered collection of binding elements contained in the current binding.</span></span></summary>
        <returns><span data-ttu-id="89c30-112">Gibt <see cref="T:System.ServiceModel.Channels.BindingElementCollection" />. Dem geordneten Stapel von Bindungselementen, die beschrieben werden, indem Sie die <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />.</span><span class="sxs-lookup"><span data-stu-id="89c30-112">Returns <see cref="T:System.ServiceModel.Channels.BindingElementCollection" />.Contains the ordered stack of binding elements described by the <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />.</span></span> <span data-ttu-id="89c30-113">Die Reihenfolge der Bindungselemente von unten ist die Transport-, Codierungs- und Sicherheit.</span><span class="sxs-lookup"><span data-stu-id="89c30-113">The order of the binding elements starting from the bottom is transport, encoding, and security.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvelopeVersion">
      <MemberSignature Language="C#" Value="public System.ServiceModel.EnvelopeVersion EnvelopeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.EnvelopeVersion EnvelopeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.EnvelopeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvelopeVersion As EnvelopeVersion" />
      <MemberSignature Language="F#" Value="member this.EnvelopeVersion : System.ServiceModel.EnvelopeVersion" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.EnvelopeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.EnvelopeVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89c30-114">Ruft die SOAP-Version ab, die für Nachrichten verwendet wird, die von dieser Bindung verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="89c30-114">Gets the version of SOAP that is used for messages that are processed by this binding.</span></span> </summary>
        <value><span data-ttu-id="89c30-115">Gibt <see cref="T:System.ServiceModel.EnvelopeVersion" />. Der Wert, der mit dieser Bindung verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="89c30-115">Returns <see cref="T:System.ServiceModel.EnvelopeVersion" />.The value that is used with this binding.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89c30-116">Ruft ab oder legt sie fest, wie der Hostname verglichen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="89c30-116">Gets or sets how the host name should be compared.</span></span></summary>
        <value><span data-ttu-id="89c30-117">Die Vergleichsmethode, die in den Namen des Hosts verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="89c30-117">The comparison method used in the host name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89c30-118">Ruft ab oder legt fest, ob das Bindungselement, das dynamisch ist.</span><span class="sxs-lookup"><span data-stu-id="89c30-118">Gets or sets whether the binding element is dynamic.</span></span></summary>
        <value><span data-ttu-id="89c30-119">"true", wenn das Bindungselement, das dynamisch ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="89c30-119">true if the binding element is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89c30-120">Ruft die maximal zulässige Größe für einen Pufferpool ab, der TCP-Meldungen speichert, die von der Bindung verarbeitet werden, oder legt diese Größe fest.</span><span class="sxs-lookup"><span data-stu-id="89c30-120">Gets or sets the maximum size allowed for a buffer pool that stores TCP messages processed by the binding.</span></span></summary>
        <value><span data-ttu-id="89c30-121">Die maximal zulässige Größe für einen Pufferpool, der TCP-Meldungen speichert, die von der Bindung verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="89c30-121">The maximum size allowed for a buffer pool that stores TCP messages processed by the binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89c30-122">Ruft die maximale Größe für einen Puffer ab, der Nachrichten von einem Kanal empfängt.</span><span class="sxs-lookup"><span data-stu-id="89c30-122">Gets or sets the maximum size for a buffer that receives messages from the channel.</span></span></summary>
        <value><span data-ttu-id="89c30-123">Gibt <see cref="T:System.Int32" />. Die maximale Größe in Bytes, der einen Puffer, in dem Nachrichten gespeichert, während sie für einen mit dieser Bindung konfigurierten Endpunkt verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="89c30-123">Returns <see cref="T:System.Int32" />.The maximum size, in bytes, of a buffer that stores messages while they are processed for an endpoint configured with this binding.</span></span> <span data-ttu-id="89c30-124">Der Standardwert ist 65.536 Bytes.</span><span class="sxs-lookup"><span data-stu-id="89c30-124">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.MaxReceivedMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89c30-125">Ruft die maximale Nachrichtengröße ab, die in einem Kanal empfangen werden kann, der mit dieser Bindung konfiguriert wurde, oder legt diese fest.</span><span class="sxs-lookup"><span data-stu-id="89c30-125">Gets or sets the maximum size for a message that can be received on a channel configured with this binding.</span></span></summary>
        <value><span data-ttu-id="89c30-126">Gibt <see cref="T:System.Int64" />. Die maximale Größe in Byte für eine Nachricht, die von der Bindung verarbeitet wird.</span><span class="sxs-lookup"><span data-stu-id="89c30-126">Returns <see cref="T:System.Int64" />.The maximum size, in bytes, for a message that is processed by the binding.</span></span> <span data-ttu-id="89c30-127">Der Standardwert ist 65.536 Bytes.</span><span class="sxs-lookup"><span data-stu-id="89c30-127">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageEncoding">
      <MemberSignature Language="C#" Value="public System.ServiceModel.WSMessageEncoding MessageEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.WSMessageEncoding MessageEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.MessageEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageEncoding As WSMessageEncoding" />
      <MemberSignature Language="F#" Value="member this.MessageEncoding : System.ServiceModel.WSMessageEncoding with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.MessageEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.WSMessageEncoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89c30-128">Ruft ab oder legt den Typ der nachrichtencodierung fest.</span><span class="sxs-lookup"><span data-stu-id="89c30-128">Gets or sets the type of message encoding.</span></span></summary>
        <value><span data-ttu-id="89c30-129">Gibt eine <see cref="T:System.ServiceModel.WSMessageEncoding" /> , die die Art der nachrichtencodierung enthält.</span><span class="sxs-lookup"><span data-stu-id="89c30-129">Returns a <see cref="T:System.ServiceModel.WSMessageEncoding" /> that contains the type of message encoding.</span></span> <span data-ttu-id="89c30-130">Der Standardwert ist Text.</span><span class="sxs-lookup"><span data-stu-id="89c30-130">The default value is Text.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAddress">
      <MemberSignature Language="C#" Value="public Uri ProxyAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ProxyAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.ProxyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.ProxyAddress : Uri with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.ProxyAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89c30-131">Ruft ab oder legt die Adresse des Proxyservers.</span><span class="sxs-lookup"><span data-stu-id="89c30-131">Gets or sets the proxy address.</span></span></summary>
        <value><span data-ttu-id="89c30-132">Gibt eine <see cref="T:System.Uri" /> , enthält die Adresse des Proxyservers.</span><span class="sxs-lookup"><span data-stu-id="89c30-132">Returns a <see cref="T:System.Uri" /> that  contains the proxy address.</span></span> <span data-ttu-id="89c30-133">Der Standardwert ist NULL.</span><span class="sxs-lookup"><span data-stu-id="89c30-133">The default value is null.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public System.Xml.XmlDictionaryReaderQuotas ReaderQuotas { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Xml.XmlDictionaryReaderQuotas ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public Property ReaderQuotas As XmlDictionaryReaderQuotas" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : System.Xml.XmlDictionaryReaderQuotas with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.ReaderQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.XmlDictionaryReaderQuotas</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89c30-134">Ruft ab oder legt die readerkontingente.</span><span class="sxs-lookup"><span data-stu-id="89c30-134">Gets or sets the reader quotas.</span></span></summary>
        <value><span data-ttu-id="89c30-135">Gibt eine <see cref="T:System.Xml.XmlDictionaryReaderQuotas" /> , das die komplexitätseinschränkungen für ausgetauschte SOAP-Nachrichten angibt.</span><span class="sxs-lookup"><span data-stu-id="89c30-135">Returns a <see cref="T:System.Xml.XmlDictionaryReaderQuotas" /> that specifies the complexity constraints on SOAP messages exchanged.</span></span> <span data-ttu-id="89c30-136">Die Standardwerte für diese Einschränkungen werden im folgenden Hinweisabschnitt angegeben.</span><span class="sxs-lookup"><span data-stu-id="89c30-136">The default values for these constraints are provided in the following Remarks section.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89c30-137">Ruft das URI-Transportschema für die Kanäle und die Listener ab, die mit dieser Bindung konfiguriert werden.</span><span class="sxs-lookup"><span data-stu-id="89c30-137">Gets the URI transport scheme for the channels and listeners that are configured with this binding.</span></span></summary>
        <value><span data-ttu-id="89c30-138">Das URI-Transportschema für die Kanäle und Listener, die mit dieser Bindung konfiguriert sind.</span><span class="sxs-lookup"><span data-stu-id="89c30-138">The URI transport scheme for the channels and listeners that are configured with this binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.BasicHttpRelaySecurity Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.BasicHttpRelaySecurity Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As BasicHttpRelaySecurity" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.BasicHttpRelaySecurity" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.BasicHttpRelaySecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89c30-139">Ruft die Auflistung der sicherheitsbindungen, die mit dieser Bindung verwendet.</span><span class="sxs-lookup"><span data-stu-id="89c30-139">Gets the collection of security bindings used with this binding.</span></span></summary>
        <value><span data-ttu-id="89c30-140">Gibt eine <see cref="T:Microsoft.ServiceBus.BasicHttpRelaySecurity" /> , die in der Bindung verwendeten Sicherheitseinstellungen enthält.</span><span class="sxs-lookup"><span data-stu-id="89c30-140">Returns a <see cref="T:Microsoft.ServiceBus.BasicHttpRelaySecurity" /> that contains the  security settings used in the binding.</span></span> <span data-ttu-id="89c30-141">Der Standardwert ist EndToEndBasicSecurityMode auf Transport festgelegt, RelayClientAuthenticationType RelayAccessToken, HttpRelayTransportSecurity HttypProxyCredentialType von keine und BasicHttpRelayMessageSecurity mit festgelegt ClientCredentialType BasicHttpMessageCredentialType.UserName und ein AlgorithmSuite von SecurityAlgorithmSuite.Basic256.</span><span class="sxs-lookup"><span data-stu-id="89c30-141">The default value has EndToEndBasicSecurityMode set to Transport, RelayClientAuthenticationType set to RelayAccessToken, HttpRelayTransportSecurity with HttypProxyCredentialType of None, and BasicHttpRelayMessageSecurity with ClientCredentialType of BasicHttpMessageCredentialType.UserName and an AlgorithmSuite of SecurityAlgorithmSuite.Basic256.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously">
      <MemberSignature Language="C#" Value="bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.System#ServiceModel#Channels#IBindingRuntimePreferences#ReceiveSynchronously" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property ReceiveSynchronously As Boolean Implements IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="F#" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
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
            <span data-ttu-id="89c30-142">Gibt an, dass eingehende Anforderungen asynchron gehandhabt werden.</span><span class="sxs-lookup"><span data-stu-id="89c30-142">Indicates that incoming requests are handled asynchronously.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TextEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding TextEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding TextEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.TextEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property TextEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.TextEncoding : System.Text.Encoding with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.TextEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Text.Encoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89c30-143">Ruft die Zeichencodierung ab oder legt die Zeichencodierung fest, die für den Meldungstext verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="89c30-143">Gets or sets the character encoding that is used for the message text.</span></span></summary>
        <value><span data-ttu-id="89c30-144">Gibt eine <see cref="T:System.Text.Encoding" /> , der angibt, das die zeichencodierung, die verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="89c30-144">Returns a <see cref="T:System.Text.Encoding" /> that indicates the character encoding that is used.</span></span> <span data-ttu-id="89c30-145">Der Standardwert ist UTF8Encoding.</span><span class="sxs-lookup"><span data-stu-id="89c30-145">The default is UTF8Encoding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89c30-146">Ruft den Übertragungsmodus ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="89c30-146">Gets or sets the transfer mode.</span></span></summary>
        <value><span data-ttu-id="89c30-147">Gibt eine <see cref="T:System.ServiceModel.TransferMode" /> , der angibt, ob der Dienst mit der Bindung verwendet Streaming- oder Puffermodus (oder beides) konfiguriert nachrichtenübertragung.</span><span class="sxs-lookup"><span data-stu-id="89c30-147">Returns a <see cref="T:System.ServiceModel.TransferMode" /> that indicates whether the service configured with the binding uses streamed or buffered (or both) modes of message transfer.</span></span> <span data-ttu-id="89c30-148">Standardmäßig verwenden HTTP, TCP/IP sowie named Pipe-Transporte gepufferte nachrichtenübertragungen.</span><span class="sxs-lookup"><span data-stu-id="89c30-148">By default, the HTTP, TCP/IP, and named pipe transports use buffered message transfers.</span></span> <span data-ttu-id="89c30-149">Der Standardwert ist buffered.</span><span class="sxs-lookup"><span data-stu-id="89c30-149">The default value is buffered.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultWebProxy">
      <MemberSignature Language="C#" Value="public bool UseDefaultWebProxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultWebProxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.UseDefaultWebProxy" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultWebProxy As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultWebProxy : bool with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.UseDefaultWebProxy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89c30-150">Ruft ab oder legt einen Wert, der bestimmt, ob der Client den Standard-Webproxy verwendet.</span><span class="sxs-lookup"><span data-stu-id="89c30-150">Gets or sets a value that determines if the client uses the default web proxy.</span></span></summary>
        <value><span data-ttu-id="89c30-151">Gibt "true" zurück, wenn der Client den Standard-Webproxy verwendet; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="89c30-151">Returns true if the client uses the default web proxy; otherwise, false.</span></span> <span data-ttu-id="89c30-152">Der Standardwert ist „true“.</span><span class="sxs-lookup"><span data-stu-id="89c30-152">The default is true.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>