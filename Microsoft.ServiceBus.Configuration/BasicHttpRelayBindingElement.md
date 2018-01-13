<Type Name="BasicHttpRelayBindingElement" FullName="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement">
  <TypeSignature Language="C#" Value="public class BasicHttpRelayBindingElement : System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BasicHttpRelayBindingElement extends System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class BasicHttpRelayBindingElement&#xA;Inherits StandardBindingElement" />
  <TypeSignature Language="F#" Value="type BasicHttpRelayBindingElement = class&#xA;    inherit StandardBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.StandardBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="5ab77-101">Stellt ein Konfigurationselement, der angibt, eine Bindung verwendet, um die Kommunikation mit WS-I Basic Profile 1.1-konformen Webdiensten, wie beispielsweise ASMX-basierten Diensten oder zum Annehmen von Meldungen von ASMX-basierten Clients über das Azure-Servicebus.</span><span class="sxs-lookup"><span data-stu-id="5ab77-101">Represents a configuration element that specifies a binding used to communicate with WS-I Basic Profile 1.1-conformant Web Services like ASMX-based services or to accept messages from ASMX-based clients through the Azure Service Bus.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BasicHttpRelayBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="5ab77-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5ab77-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BasicHttpRelayBindingElement (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement : string -&gt; Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement" Usage="new Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5ab77-103">Der Name des Bindungselements.</span><span class="sxs-lookup"><span data-stu-id="5ab77-103">The name of the binding element.</span></span></param>
        <summary><span data-ttu-id="5ab77-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement" />-Klasse unter Verwendung des angegebenen Namens.</span><span class="sxs-lookup"><span data-stu-id="5ab77-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement" /> class using the specified name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.AllowCookies" />
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
        <summary><span data-ttu-id="5ab77-105">Ruft ab oder legt einen booleschen Wert, der angibt, ob der Client Cookies akzeptiert und für zukünftige Anfragen propagiert.</span><span class="sxs-lookup"><span data-stu-id="5ab77-105">Gets or sets a Boolean value that indicates whether the client accepts cookies and propagates them on future requests.</span></span></summary>
        <value><span data-ttu-id="5ab77-106">"true", wenn der Client Cookies akzeptiert und für zukünftige Anfragen propagiert; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="5ab77-106">true if the client accepts cookies and propagates them on future requests; otherwise, false.</span></span> <span data-ttu-id="5ab77-107">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="5ab77-107">The default value is false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5ab77-108">Ruft den Typ dieses Bindungselements ab.</span><span class="sxs-lookup"><span data-stu-id="5ab77-108">Gets the type of this binding element.</span></span></summary>
        <value><span data-ttu-id="5ab77-109">Gibt eine <see cref="T:System.Type" /> , die den Bindungstyp für das Element enthält.</span><span class="sxs-lookup"><span data-stu-id="5ab77-109">Returns a <see cref="T:System.Type" /> that contains the binding element type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="basicHttpRelayBindingElement.InitializeFrom binding" />
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
        <param name="binding"><span data-ttu-id="5ab77-110">Die Bindung nicht initialisieren.</span><span class="sxs-lookup"><span data-stu-id="5ab77-110">The Binding to initialize from.</span></span></param>
        <summary><span data-ttu-id="5ab77-111">Initialisiert dieses Bindungskonfigurationselement mit dem Inhalt der angegebenen Bindungsauflistung.</span><span class="sxs-lookup"><span data-stu-id="5ab77-111">Initializes this binding configuration element with the content of the specified binding collection.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.IsDynamic" />
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
        <summary><span data-ttu-id="5ab77-112">Ruft ab oder legt fest, ob das Bindungselement, das dynamisch ist.</span><span class="sxs-lookup"><span data-stu-id="5ab77-112">Gets or sets whether the binding element is dynamic.</span></span></summary>
        <value><span data-ttu-id="5ab77-113">"true", wenn das Bindungselement, das dynamisch ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="5ab77-113">true if the binding element is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.MaxBufferPoolSize" />
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
        <summary><span data-ttu-id="5ab77-114">Ruft die maximale Größe für einen Pufferpool ab, der TCP-Meldungen speichert, die von der Bindung verarbeitet werden, oder legt die maximale Größe für einen Pufferpool fest.</span><span class="sxs-lookup"><span data-stu-id="5ab77-114">Gets or sets the maximum size for a buffer pool that stores messages processed by the binding.</span></span></summary>
        <value><span data-ttu-id="5ab77-115">Gibt eine <see cref="T:System.Int64" /> , enthält die Größe des Pufferpools.</span><span class="sxs-lookup"><span data-stu-id="5ab77-115">Returns an <see cref="T:System.Int64" /> that contains the buffer pool size.</span></span> <span data-ttu-id="5ab77-116">Der Standardwert ist 512\*1024  Byte.</span><span class="sxs-lookup"><span data-stu-id="5ab77-116">The default value is 512\*1024 bytes.</span></span> <span data-ttu-id="5ab77-117">Der minimale Wert ist 0.</span><span class="sxs-lookup"><span data-stu-id="5ab77-117">The minimum value is 0.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.MaxBufferSize" />
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
        <summary><span data-ttu-id="5ab77-118">Ruft ab oder legt die maximale Größe eines Puffers, in dem Nachrichten gespeichert, während sie für einen mit dieser Bindung konfigurierten Endpunkt verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="5ab77-118">Gets or sets the maximum size of a buffer that stores messages while they are processed for an endpoint configured with this binding.</span></span></summary>
        <value><span data-ttu-id="5ab77-119">Gibt die maximale Puffergröße.</span><span class="sxs-lookup"><span data-stu-id="5ab77-119">Returns the maximum buffer size.</span></span> <span data-ttu-id="5ab77-120">Der Standardwert ist 65.536 Bytes.</span><span class="sxs-lookup"><span data-stu-id="5ab77-120">The default value is 65,536 bytes.</span></span> <span data-ttu-id="5ab77-121">Der Mindestwert ist 1 Byte.</span><span class="sxs-lookup"><span data-stu-id="5ab77-121">The minimum value is 1 byte.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.MaxReceivedMessageSize" />
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
        <summary><span data-ttu-id="5ab77-122">Ruft ab oder legt die maximale Nachrichtengröße in Byte einschließlich Header angibt, für eine Nachricht, die in einem mit dieser Bindung konfigurierten Kanal empfangen werden können.</span><span class="sxs-lookup"><span data-stu-id="5ab77-122">Gets or sets the maximum message size, in bytes, including headers, for a message that can be received on a channel configured with this binding.</span></span></summary>
        <value><span data-ttu-id="5ab77-123">Die Größe des Maximalgröße empfangener Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="5ab77-123">The maximum received message size.</span></span> <span data-ttu-id="5ab77-124">Der Standardwert ist 65.536 Bytes.</span><span class="sxs-lookup"><span data-stu-id="5ab77-124">The default value is 65,536 bytes.</span></span> <span data-ttu-id="5ab77-125">Der Mindestwert ist 1 Byte.</span><span class="sxs-lookup"><span data-stu-id="5ab77-125">The minimum value is 1 byte.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageEncoding">
      <MemberSignature Language="C#" Value="public System.ServiceModel.WSMessageEncoding MessageEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.WSMessageEncoding MessageEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.MessageEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageEncoding As WSMessageEncoding" />
      <MemberSignature Language="F#" Value="member this.MessageEncoding : System.ServiceModel.WSMessageEncoding with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.MessageEncoding" />
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
        <summary><span data-ttu-id="5ab77-126">Ruft ab oder legt sie fest, die messaging-Codierung, der angibt, ob MTOM oder Text/XML verwendet wird, um die SOAP-Nachricht zu codieren.</span><span class="sxs-lookup"><span data-stu-id="5ab77-126">Gets or sets the messaging encoding that indicates whether MTOM or text/XML is used to encode the SOAP message.</span></span></summary>
        <value><span data-ttu-id="5ab77-127">Gibt eine <see cref="T:System.ServiceModel.WSMessageEncoding" /> , Text/XML oder MTOM enthält.</span><span class="sxs-lookup"><span data-stu-id="5ab77-127">Returns a <see cref="T:System.ServiceModel.WSMessageEncoding" /> that contains either Text/XML or MTOM.</span></span> <span data-ttu-id="5ab77-128">Der Standardwert ist Text.</span><span class="sxs-lookup"><span data-stu-id="5ab77-128">The default value is Text.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="basicHttpRelayBindingElement.OnApplyConfiguration binding" />
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
        <param name="binding"><span data-ttu-id="5ab77-129">Die Bindung, diese Konfiguration angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5ab77-129">The Binding to apply this configuration to.</span></span></param>
        <summary><span data-ttu-id="5ab77-130">Wendet die Einstellungen dieses Konfigurationselements auf die angegebene Bindung.</span><span class="sxs-lookup"><span data-stu-id="5ab77-130">Applies the settings of this configuration element to the specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5ab77-131">Ruft eine Auflistung der Objekte, die Attribute werden können oder Konfiguration-Element für dieses bindungskonfigurationselement.</span><span class="sxs-lookup"><span data-stu-id="5ab77-131">Gets a collection of objects that can be attributes or configuration element objects of this binding configuration element.</span></span></summary>
        <value><span data-ttu-id="5ab77-132">Gibt eine <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> , enthält die Eigenschaften der aktuellen Instanz.</span><span class="sxs-lookup"><span data-stu-id="5ab77-132">Returns a <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> that contains the properties of the current instance.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAddress">
      <MemberSignature Language="C#" Value="public Uri ProxyAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ProxyAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.ProxyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.ProxyAddress : Uri with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.ProxyAddress" />
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
        <summary><span data-ttu-id="5ab77-133">Abrufen oder festlegen den URI, der die Adresse des HTTP-Proxys beschreibt.</span><span class="sxs-lookup"><span data-stu-id="5ab77-133">Gets or sets the URI that describes the address of the HTTP proxy.</span></span></summary>
        <value><span data-ttu-id="5ab77-134">Gibt eine <see cref="T:System.Uri" /> , die den URI enthält.</span><span class="sxs-lookup"><span data-stu-id="5ab77-134">Returns a <see cref="T:System.Uri" /> that contains the URI.</span></span> <span data-ttu-id="5ab77-135">Der Standardwert ist NULL.</span><span class="sxs-lookup"><span data-stu-id="5ab77-135">The default is null.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReaderQuotas As XmlDictionaryReaderQuotasElement" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.ReaderQuotas" />
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
        <summary><span data-ttu-id="5ab77-136">Ruft ab oder legt einen XML-Wert, der Beschränkungen der Komplexität von SOAP-Nachrichten gespeichert werden, die von mit dieser Bindung konfigurierten Endpunkten verarbeitet werden können.</span><span class="sxs-lookup"><span data-stu-id="5ab77-136">Gets or sets an XML value that places constraints on the complexity of SOAP messages that can be processed by endpoints configured with this binding.</span></span></summary>
        <value><span data-ttu-id="5ab77-137">Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" /> , die die readerkontingente enthält.</span><span class="sxs-lookup"><span data-stu-id="5ab77-137">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" /> that contains the reader quotas.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As BasicHttpRelaySecurityElement" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.Security" />
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
        <ReturnType>Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5ab77-138">Ruft den Typ der Sicherheit für die Bindung verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5ab77-138">Gets the type of security to be used for the binding.</span></span></summary>
        <value><span data-ttu-id="5ab77-139">Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement" /> , angibt, dass den Typ der Sicherheit mit der Bindung verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5ab77-139">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement" /> that specifies the type of security to be used with the binding.</span></span> <span data-ttu-id="5ab77-140">Der Standardwert ist None.</span><span class="sxs-lookup"><span data-stu-id="5ab77-140">The default value is None.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TextEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding TextEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding TextEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.TextEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property TextEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.TextEncoding : System.Text.Encoding with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.TextEncoding" />
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
        <summary><span data-ttu-id="5ab77-141">Ruft die Zeichensatzcodierung ab, die zum Ausgeben von Meldungen über die Bindung verwendet werden soll, oder legt sie fest.</span><span class="sxs-lookup"><span data-stu-id="5ab77-141">Gets or sets the character set encoding to be used for emitting messages on the binding.</span></span></summary>
        <value><span data-ttu-id="5ab77-142">Gibt eine <see cref="T:System.Text.Encoding" /> , enthält der textcodierung.</span><span class="sxs-lookup"><span data-stu-id="5ab77-142">Returns a <see cref="T:System.Text.Encoding" /> that contains the text encoding.</span></span> <span data-ttu-id="5ab77-143">Der Standardwert ist UTF8.</span><span class="sxs-lookup"><span data-stu-id="5ab77-143">The default value is UTF8.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.TransferMode" />
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
        <summary><span data-ttu-id="5ab77-144">Ruft ab oder legt fest, ob Nachrichten gepuffert oder bei einer Anforderung oder Antwort gestreamt werden.</span><span class="sxs-lookup"><span data-stu-id="5ab77-144">Gets or sets whether messages are buffered or streamed on a request or response.</span></span></summary>
        <value><span data-ttu-id="5ab77-145">Gibt eine <see cref="T:System.ServiceModel.TransferMode" /> , die den Übertragungsmodus enthält.</span><span class="sxs-lookup"><span data-stu-id="5ab77-145">Returns a <see cref="T:System.ServiceModel.TransferMode" /> that contains the transfer mode.</span></span> <span data-ttu-id="5ab77-146">Der Standardwert ist TransferMode.Buffered.</span><span class="sxs-lookup"><span data-stu-id="5ab77-146">The default value is TransferMode.Buffered.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultWebProxy">
      <MemberSignature Language="C#" Value="public bool UseDefaultWebProxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultWebProxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.UseDefaultWebProxy" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultWebProxy As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultWebProxy : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.UseDefaultWebProxy" />
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
        <summary><span data-ttu-id="5ab77-147">Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der automatisch konfigurierte HTTP-Proxy des Systems bei Verfügbarkeit verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5ab77-147">Gets or sets a value that indicates whether the auto-configured HTTP proxy of the system should be used, if available.</span></span></summary>
        <value><span data-ttu-id="5ab77-148">True, um den HTTP-Proxy verwenden; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="5ab77-148">true to use the http proxy; otherwise, false.</span></span> <span data-ttu-id="5ab77-149">Der Standardwert lautet „true“.</span><span class="sxs-lookup"><span data-stu-id="5ab77-149">The default value is true.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>