<Type Name="WSHttpRelayBindingBaseElement" FullName="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement">
  <TypeSignature Language="C#" Value="public abstract class WSHttpRelayBindingBaseElement : System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit WSHttpRelayBindingBaseElement extends System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class WSHttpRelayBindingBaseElement&#xA;Inherits StandardBindingElement" />
  <TypeSignature Language="F#" Value="type WSHttpRelayBindingBaseElement = class&#xA;    inherit StandardBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.StandardBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="6da98-101">Stellt eine Basisklasse für die<see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement" /> Konfigurationselement, das eine Bindung angibt, die verteilte Transaktionen und sichere, zuverlässige Sitzungen unterstützt.</span><span class="sxs-lookup"><span data-stu-id="6da98-101">Provides a base class for the<see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement" /> configuration element that specifies a binding that supports distributed transactions and secure, reliable sessions.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected WSHttpRelayBindingBaseElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6da98-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6da98-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected WSHttpRelayBindingBaseElement (string name);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement : string -&gt; Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" Usage="new Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="6da98-103">Ein Name, der dieses Konfigurationselement eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="6da98-103">A name that uniquely identifies this configuration element.</span></span></param>
        <summary><span data-ttu-id="6da98-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" />-Klasse mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="6da98-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" /> class with the specified name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="wSHttpRelayBindingBaseElement.InitializeFrom binding" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binding" Type="System.ServiceModel.Channels.Binding" />
      </Parameters>
      <Docs>
        <param name="binding"> <span data-ttu-id="6da98-105">Eine Bindung.</span><span class="sxs-lookup"><span data-stu-id="6da98-105">A binding.</span></span></param>
        <summary><span data-ttu-id="6da98-106">Initialisiert dieses Bindungskonfigurationselement mit dem Inhalt der angegebenen Bindung.</span><span class="sxs-lookup"><span data-stu-id="6da98-106">Initializes this binding configuration element with the content of the specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("isDynamic", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6da98-107">Ruft ab oder legt fest, ob das Bindungselement Basis dynamisch ist.</span><span class="sxs-lookup"><span data-stu-id="6da98-107">Gets or sets whether the binding base element is dynamic.</span></span></summary>
        <value><span data-ttu-id="6da98-108">"true", wenn die Bindung Basiselement dynamisch ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="6da98-108">true if the binding base element is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxBufferPoolSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.LongValidator(MinValue=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6da98-109">Ruft ab oder legt die maximale Größe des Pufferpools, die von verarbeitete Nachrichten speichert die <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> Bindung.</span><span class="sxs-lookup"><span data-stu-id="6da98-109">Gets or sets the maximum size of the buffer pool that stores messages processed by the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></summary>
        <value><span data-ttu-id="6da98-110">Die maximale Größe des Pufferpools, die Nachrichten speichert verarbeitet, indem die <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> Bindung.</span><span class="sxs-lookup"><span data-stu-id="6da98-110">The maximum size of the buffer pool that stores messages processed by the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span> <span data-ttu-id="6da98-111">Der Standardwert ist 524288 Bytes.</span><span class="sxs-lookup"><span data-stu-id="6da98-111">The default is 524288 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.MaxReceivedMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxReceivedMessageSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.LongValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6da98-112">Ruft ab oder legt die maximale Größe für Nachrichten, die in einem mit konfigurierten Kanal empfangen die <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> Bindung.</span><span class="sxs-lookup"><span data-stu-id="6da98-112">Gets or sets the maximum size for messages received on a channel configured with the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></summary>
        <value><span data-ttu-id="6da98-113">Die maximale Größe für Nachrichten, die in einem mit konfigurierten Kanal empfangen die <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> Bindung.</span><span class="sxs-lookup"><span data-stu-id="6da98-113">The maximum size for messages received on a channel configured with the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span> <span data-ttu-id="6da98-114">Der Standardwert ist 65.536 Bytes.</span><span class="sxs-lookup"><span data-stu-id="6da98-114">The default is 65536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageEncoding">
      <MemberSignature Language="C#" Value="public System.ServiceModel.WSMessageEncoding MessageEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.WSMessageEncoding MessageEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.MessageEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageEncoding As WSMessageEncoding" />
      <MemberSignature Language="F#" Value="member this.MessageEncoding : System.ServiceModel.WSMessageEncoding with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.MessageEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("messageEncoding", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.WSMessageEncoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6da98-115">Ruft ab oder legt fest, ob MTOM oder Text/XML verwendet wird, um SOAP-Nachrichten zu codieren.</span><span class="sxs-lookup"><span data-stu-id="6da98-115">Gets or sets whether MTOM or Text/XML is used to encode SOAP messages.</span></span></summary>
        <value><span data-ttu-id="6da98-116">Gibt an, ob MTOM oder Text/XML verwendet wird, um SOAP-Nachrichten zu codieren.</span><span class="sxs-lookup"><span data-stu-id="6da98-116">Indicates whether MTOM or Text/XML is used to encode SOAP messages.</span></span> <span data-ttu-id="6da98-117">Der Standardwert ist Text/XML.</span><span class="sxs-lookup"><span data-stu-id="6da98-117">The default is Text/XML.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="wSHttpRelayBindingBaseElement.OnApplyConfiguration binding" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binding" Type="System.ServiceModel.Channels.Binding" />
      </Parameters>
      <Docs>
        <param name="binding"> <span data-ttu-id="6da98-118">Die Bindung, die Einstellungen zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="6da98-118">The binding to update the settings of.</span></span></param>
        <summary><span data-ttu-id="6da98-119">Wendet die Einstellungen dieses Konfigurationselements auf die angegebene Bindung.</span><span class="sxs-lookup"><span data-stu-id="6da98-119">Applies the settings of this configuration element to the specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6da98-120">Ruft eine Auflistung von Eigenschaften für dieses bindungskonfigurationselement.</span><span class="sxs-lookup"><span data-stu-id="6da98-120">Gets a collection of properties of this binding configuration element.</span></span></summary>
        <value><span data-ttu-id="6da98-121">Eine Auflistung von Eigenschaften für dieses bindungskonfigurationselement.</span><span class="sxs-lookup"><span data-stu-id="6da98-121">A collection of properties of this binding configuration element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAddress">
      <MemberSignature Language="C#" Value="public Uri ProxyAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ProxyAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.ProxyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.ProxyAddress : Uri with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.ProxyAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("proxyAddress", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6da98-122">Ruft die URI-Adresse des HTTP-Proxys ab oder legt sie fest.</span><span class="sxs-lookup"><span data-stu-id="6da98-122">Gets or sets the URI address of the HTTP proxy.</span></span></summary>
        <value><span data-ttu-id="6da98-123">Die URI-Adresse des HTTP-Proxys.</span><span class="sxs-lookup"><span data-stu-id="6da98-123">The URI address of the HTTP proxy.</span></span> <span data-ttu-id="6da98-124">Der Standardwert ist NULL.</span><span class="sxs-lookup"><span data-stu-id="6da98-124">The default is null.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReaderQuotas As XmlDictionaryReaderQuotasElement" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.ReaderQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("readerQuotas")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6da98-125">Ruft Beschränkungen der Komplexität von SOAP-Nachrichten, die von mit konfigurierten Endpunkten verarbeitet werden, können die <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> Bindung.</span><span class="sxs-lookup"><span data-stu-id="6da98-125">Gets constraints on the complexity of SOAP messages that can be processed by endpoints configured with the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></summary>
        <value><span data-ttu-id="6da98-126">Beschränkungen der Komplexität von SOAP-Nachrichten, die von mit konfigurierten Endpunkten verarbeitet werden, können die <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> Bindung.</span><span class="sxs-lookup"><span data-stu-id="6da98-126">Constraints on the complexity of SOAP messages that can be processed by endpoints configured with the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReliableSession">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement ReliableSession { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement ReliableSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.ReliableSession" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReliableSession As StandardBindingOptionalReliableSessionElement" />
      <MemberSignature Language="F#" Value="member this.ReliableSession : System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.ReliableSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("reliableSession")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6da98-127">Ruft eine <see cref="T:System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" /> Konfigurationselement, das eine optionale Konfigurationseinstellung für WS-Reliable messaging in definierten stellt die <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> Bindung.</span><span class="sxs-lookup"><span data-stu-id="6da98-127">Gets a <see cref="T:System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" /> configuration element that represents an optional configuration setting for WS-Reliable messaging defined in the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></summary>
        <value><span data-ttu-id="6da98-128">Ein <see cref="T:System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" /> Konfigurationselement, das eine optionale Konfigurationseinstellung für WS-Reliable messaging in definierten stellt die <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> Bindung.</span><span class="sxs-lookup"><span data-stu-id="6da98-128">A <see cref="T:System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" /> configuration element that represents an optional configuration setting for WS-Reliable messaging defined in the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TextEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding TextEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding TextEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.TextEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property TextEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.TextEncoding : System.Text.Encoding with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.TextEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.TypeConverter(typeof(Microsoft.ServiceBus.Configuration.EncodingConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("textEncoding", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Text.Encoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6da98-129">Ruft die Zeichencodierung ab oder legt die Zeichencodierung fest, die für den Meldungstext verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="6da98-129">Gets or sets the character encoding that is used for the message text.</span></span></summary>
        <value><span data-ttu-id="6da98-130">Die zeichencodierung wird für den Meldungstext verwendet.</span><span class="sxs-lookup"><span data-stu-id="6da98-130">The character encoding that is used for the message text.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultWebProxy">
      <MemberSignature Language="C#" Value="public bool UseDefaultWebProxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultWebProxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.UseDefaultWebProxy" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultWebProxy As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultWebProxy : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.UseDefaultWebProxy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("useDefaultWebProxy", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6da98-131">Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der automatisch konfigurierte HTTP-Proxy des Systems bei Verfügbarkeit verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6da98-131">Gets or sets a value that indicates whether the auto-configured HTTP proxy of the system should be used, if available.</span></span></summary>
        <value><span data-ttu-id="6da98-132">"true", wenn der automatisch konfigurierte HTTP-Proxy des Systems verwendet, falls verfügbar sein soll; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="6da98-132">true if the auto-configured HTTP proxy of the system should be used, if available; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>