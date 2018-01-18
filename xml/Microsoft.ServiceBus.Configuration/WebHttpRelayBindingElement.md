<Type Name="WebHttpRelayBindingElement" FullName="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement">
  <TypeSignature Language="C#" Value="public class WebHttpRelayBindingElement : System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebHttpRelayBindingElement extends System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class WebHttpRelayBindingElement&#xA;Inherits StandardBindingElement" />
  <TypeSignature Language="F#" Value="type WebHttpRelayBindingElement = class&#xA;    inherit StandardBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.StandardBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="68c65-101">Ein Bindungselement, das zum Konfigurieren von Endpunkten für einen Azure Service Bus-Relay-Dienst, der auf HTTP-Anforderungen und nicht durch SOAP-Nachrichten reagiert.</span><span class="sxs-lookup"><span data-stu-id="68c65-101">A binding element used to configure endpoints for an Azure Service Bus relay service that responds to HTTP requests instead of SOAP messages.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebHttpRelayBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="68c65-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="68c65-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebHttpRelayBindingElement (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement : string -&gt; Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement" Usage="new Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="68c65-103">Der Name des neuen Bindungselements.</span><span class="sxs-lookup"><span data-stu-id="68c65-103">The name of the new binding element.</span></span></param>
        <summary><span data-ttu-id="68c65-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement" />-Klasse unter Verwendung des angegebenen Namens.</span><span class="sxs-lookup"><span data-stu-id="68c65-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement" /> class using the specified name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.AllowCookies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("allowCookies", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="68c65-105">Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der Client Cookies akzeptiert und bei zukünftigen Anfragen weiterleitet.</span><span class="sxs-lookup"><span data-stu-id="68c65-105">Gets or sets a value that indicates whether the client accepts cookies and propagates them on future requests.</span></span></summary>
        <value><span data-ttu-id="68c65-106">"true", wenn Cookies zulässig sind; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="68c65-106">true if cookies are allowed; otherwise, false.</span></span> <span data-ttu-id="68c65-107">Der Standardwert ist false.</span><span class="sxs-lookup"><span data-stu-id="68c65-107">The default is false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="68c65-108">Ruft den Typ der Bindung, die dieses Konfigurationselement darstellt.</span><span class="sxs-lookup"><span data-stu-id="68c65-108">Gets the type of binding that this configuration element represents.</span></span></summary>
        <value><span data-ttu-id="68c65-109">Gibt eine <see cref="T:System.Type" /> , der Bindungstyp enthält.</span><span class="sxs-lookup"><span data-stu-id="68c65-109">Returns a <see cref="T:System.Type" /> that contains the binding type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="webHttpRelayBindingElement.InitializeFrom binding" />
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
        <param name="binding"> <span data-ttu-id="68c65-110">Die Bindung dieses Konfigurationselements aus aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="68c65-110">The binding to update this configuration element from.</span></span></param>
        <summary><span data-ttu-id="68c65-111">Initialisiert den Inhalt dieses Bindungskonfigurationselements aus den Eigenschaftswerten einer angegebenen Bindung.</span><span class="sxs-lookup"><span data-stu-id="68c65-111">Initializes the contents of this binding configuration element from the property values of a specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.IsDynamic" />
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
        <summary><span data-ttu-id="68c65-112">Ruft ab oder legt fest, ob das Bindungselement, das dynamisch ist.</span><span class="sxs-lookup"><span data-stu-id="68c65-112">Gets or sets whether the binding element is dynamic.</span></span></summary>
        <value><span data-ttu-id="68c65-113">"true", wenn das Bindungselement, das dynamisch ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="68c65-113">true if the binding element is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxBufferPoolSize" />
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
        <summary><span data-ttu-id="68c65-114">Ruft die maximale Speicherkapazität für den Puffer-Manager ab, der die Puffer verwaltet, die für die von dieser Bindung verwendeten Endpunkte erforderlich sind, oder legt sie fest.</span><span class="sxs-lookup"><span data-stu-id="68c65-114">Gets or sets the maximum amount of memory allocated for the buffer manager that manages the buffers required by endpoints that use this binding.</span></span></summary>
        <value><span data-ttu-id="68c65-115">Gibt die maximale Größe in Bytes des Pufferpools, die von einem mit dieser Bindung konfigurierten Endpunkt verwendet.</span><span class="sxs-lookup"><span data-stu-id="68c65-115">Returns the maximum size, in bytes, for the pool of buffers used by an endpoint configured with this binding.</span></span> <span data-ttu-id="68c65-116">Der Standardwert ist 65.536 Bytes.</span><span class="sxs-lookup"><span data-stu-id="68c65-116">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxBufferSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="68c65-117">Ruft die maximale Speicherkapazität ab, die vom Manager der Nachrichtenpuffer verwendet werden kann, die Nachrichten aus dem Kanal empfangen, oder legt diese fest.</span><span class="sxs-lookup"><span data-stu-id="68c65-117">Gets or sets the maximum amount of memory that is allocated for use by the manager of the message buffers that receive messages from the channel.</span></span></summary>
        <value><span data-ttu-id="68c65-118">Gibt die maximale Arbeitsspeichermenge in Bytes zur Verwendung in den Puffer-Manager zurück.</span><span class="sxs-lookup"><span data-stu-id="68c65-118">Returns the maximum amount of memory, in bytes, available for use by the message buffer manager.</span></span> <span data-ttu-id="68c65-119">Der Standardwert ist 524.288 (0x80000) Bytes.</span><span class="sxs-lookup"><span data-stu-id="68c65-119">The default value is 524,288 (0x80000) bytes.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="68c65-120">Der festgelegte Wert ist kleiner oder gleich 0.</span><span class="sxs-lookup"><span data-stu-id="68c65-120">The value set is less than or equal to zero.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxReceivedMessageSize" />
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
        <summary><span data-ttu-id="68c65-121">Ruft die maximale Größe für eine Nachricht ab, die von der Bindung verarbeitet werden kann, oder legt sie fest.</span><span class="sxs-lookup"><span data-stu-id="68c65-121">Gets or sets the maximum size for a message that can be processed by the binding.</span></span></summary>
        <value><span data-ttu-id="68c65-122">Gibt die maximale Größe in Byte für eine Nachricht, die von der Bindung verarbeitet wird.</span><span class="sxs-lookup"><span data-stu-id="68c65-122">Returns the maximum size, in bytes, for a message that is processed by the binding.</span></span> <span data-ttu-id="68c65-123">Der Standardwert ist 65.536 Bytes.</span><span class="sxs-lookup"><span data-stu-id="68c65-123">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="68c65-124">Der Wert ist kleiner als 0 (null).</span><span class="sxs-lookup"><span data-stu-id="68c65-124">The value is less than zero.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="webHttpRelayBindingElement.OnApplyConfiguration binding" />
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
        <param name="binding"> <span data-ttu-id="68c65-125">Die Bindung, die Einstellungen zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="68c65-125">The binding to update the settings of.</span></span></param>
        <summary><span data-ttu-id="68c65-126">Wendet die Einstellungen dieses Konfigurationselements auf die angegebene Bindung.</span><span class="sxs-lookup"><span data-stu-id="68c65-126">Applies the settings of this configuration element to the specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="68c65-127">Ruft eine Auflistung der Objekte, die Attribute werden können oder Konfiguration Element dieses Konfigurationselements ab.</span><span class="sxs-lookup"><span data-stu-id="68c65-127">Gets a collection of objects that can be attributes or configuration element objects of this configuration element.</span></span></summary>
        <value><span data-ttu-id="68c65-128">Gibt eine <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> , die eine Auflistung von ConfigurationProperty-Objekte, die Attribute werden können oder ConfigurationElement auf dieses Konfigurationselement enthält.</span><span class="sxs-lookup"><span data-stu-id="68c65-128">Returns a <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> that contains a collection of ConfigurationProperty objects that can be attributes or ConfigurationElement objects on this configuration element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAddress">
      <MemberSignature Language="C#" Value="public Uri ProxyAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ProxyAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.ProxyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.ProxyAddress : Uri with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.ProxyAddress" />
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
        <summary><span data-ttu-id="68c65-129">Ruft die URI-Adresse des HTTP-Proxys ab oder legt sie fest.</span><span class="sxs-lookup"><span data-stu-id="68c65-129">Gets or sets the URI address of the HTTP proxy.</span></span></summary>
        <value><span data-ttu-id="68c65-130">Gibt eine <see cref="T:System.Uri" /> , die als die Adresse des HTTP-Proxy dient.</span><span class="sxs-lookup"><span data-stu-id="68c65-130">Returns a <see cref="T:System.Uri" /> that serves as the address of the HTTP proxy.</span></span> <span data-ttu-id="68c65-131">Der Standardwert ist NULL.</span><span class="sxs-lookup"><span data-stu-id="68c65-131">The default value is null.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReaderQuotas As XmlDictionaryReaderQuotasElement" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.ReaderQuotas" />
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
        <summary><span data-ttu-id="68c65-132">Ruft das Konfigurationselement ab, das die Beschränkungen für die Komplexität von SOAP-Meldungen enthält, die von Endpunkten verarbeitet werden können, die mit dieser Bindung konfiguriert wurden, oder legt dieses Element fest.</span><span class="sxs-lookup"><span data-stu-id="68c65-132">Gets or sets the configuration element that contains the constraints on the complexity of SOAP messages that can be processed by endpoints configured with this binding.</span></span></summary>
        <value><span data-ttu-id="68c65-133">Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" /> , die die Komplexität Einschränkungen enthält.</span><span class="sxs-lookup"><span data-stu-id="68c65-133">Returns an <see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" /> that contains the complexity restraints.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="68c65-134">Die Valueset ist null.</span><span class="sxs-lookup"><span data-stu-id="68c65-134">The valueset is null.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="68c65-135">Die Kontingentwerte von XmlDictionaryReaderQuotas sind schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="68c65-135">The quota values of XmlDictionaryReaderQuotas are read only.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="68c65-136">Die festgelegten Kontingente müssen positiv sein.</span><span class="sxs-lookup"><span data-stu-id="68c65-136">The quotas set must be positive.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As WebHttpRelaySecurityElement" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("security")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="68c65-137">Ruft das Konfigurationselement ab, das die mit dieser Bindung verwendeten Sicherheitseinstellungen enthält.</span><span class="sxs-lookup"><span data-stu-id="68c65-137">Gets the configuration element that contains the security settings used with this binding.</span></span></summary>
        <value><span data-ttu-id="68c65-138">Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement" /> , das die Sicherheitseinstellungen für diese Bindung enthält.</span><span class="sxs-lookup"><span data-stu-id="68c65-138">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement" /> that contains the security settings for this binding.</span></span> <span data-ttu-id="68c65-139">Der Standardwert ist none.</span><span class="sxs-lookup"><span data-stu-id="68c65-139">The default value is none.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("transferMode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="68c65-140">Ruft ab oder legt einen Wert, der angibt, ob der Dienst mit der zugehörigen Bindung Streaming-oder Puffermodus (oder beides) Modi nachrichtenübertragung konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="68c65-140">Gets or sets a value that indicates whether the service configured with the associated binding uses streamed or buffered (or both) modes of message transfer.</span></span></summary>
        <value><span data-ttu-id="68c65-141">Gibt eine <see cref="T:System.ServiceModel.TransferMode" /> enthält, die angibt, ob der Dienst mit der Bindung verwendet Streaming- oder Puffermodus (oder beides) nachrichtenübertragung.</span><span class="sxs-lookup"><span data-stu-id="68c65-141">Returns a <see cref="T:System.ServiceModel.TransferMode" /> that contains indicates whether the service configured with the binding uses streamed or buffered (or both) modes of message transfer.</span></span> <span data-ttu-id="68c65-142">Der Standardwert ist Buffered.</span><span class="sxs-lookup"><span data-stu-id="68c65-142">The default value is Buffered.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ComponentModel.InvalidEnumArgumentException"><span data-ttu-id="68c65-143">Der festgelegte Wert ist kein gültiger Übertragungsmodus Wert.</span><span class="sxs-lookup"><span data-stu-id="68c65-143">The value set is not a valid TransferMode value.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultWebProxy">
      <MemberSignature Language="C#" Value="public bool UseDefaultWebProxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultWebProxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.UseDefaultWebProxy" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultWebProxy As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultWebProxy : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.UseDefaultWebProxy" />
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
        <summary><span data-ttu-id="68c65-144">Ruft ab oder legt einen Wert, der angibt, ob der automatisch konfigurierte HTTP-Proxy des Systems mit der zugehörigen Bindung verwendet werden soll, falls verfügbar.</span><span class="sxs-lookup"><span data-stu-id="68c65-144">Gets or sets a value that indicates whether the auto-configured HTTP proxy of the system should be used with the associated binding, if available.</span></span></summary>
        <value><span data-ttu-id="68c65-145">"true", wenn der automatisch konfigurierte HTTP-Proxy des Systems verwendet, falls verfügbar sein soll; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="68c65-145">true if the auto-configured HTTP proxy of the system should be used, if available; otherwise, false.</span></span> <span data-ttu-id="68c65-146">Der Standardwert lautet „true“.</span><span class="sxs-lookup"><span data-stu-id="68c65-146">The default value is true.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding WriteEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding WriteEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.WriteEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.WriteEncoding : System.Text.Encoding with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.WriteEncoding" />
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
          <AttributeName>System.Configuration.ConfigurationProperty("writeEncoding", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Text.Encoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="68c65-147">Ruft ab oder legt sie fest, das die zeichencodierung, die für den Nachrichtentext in die zugeordnete Bindung verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="68c65-147">Gets or sets the character encoding that is used for the message text in the associated binding.</span></span></summary>
        <value><span data-ttu-id="68c65-148">Gibt eine <see cref="T:System.Text.Encoding" /> , der angibt, das die zeichencodierung, die verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="68c65-148">Returns a <see cref="T:System.Text.Encoding" /> that indicates the character encoding that is used.</span></span> <span data-ttu-id="68c65-149">Der Standardwert ist UTF8Encoding.</span><span class="sxs-lookup"><span data-stu-id="68c65-149">The default is UTF8Encoding.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="68c65-150">Der festgelegte Wert ist null.</span><span class="sxs-lookup"><span data-stu-id="68c65-150">The value set is null.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>