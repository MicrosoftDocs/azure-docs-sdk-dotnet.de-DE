<Type Name="NetOnewayRelayBindingElement" FullName="Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement">
  <TypeSignature Language="C#" Value="public class NetOnewayRelayBindingElement : System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetOnewayRelayBindingElement extends System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class NetOnewayRelayBindingElement&#xA;Inherits StandardBindingElement" />
  <TypeSignature Language="F#" Value="type NetOnewayRelayBindingElement = class&#xA;    inherit StandardBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.StandardBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="ee5ec-101">Stellt ein Konfigurationselement, das eine Bindung für PeerChannel-TCP-messaging über den Servicebus angibt.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-101">Represents a configuration element that specifies a binding for peer channel-specific TCP messaging over the Service Bus.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetOnewayRelayBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="ee5ec-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetOnewayRelayBindingElement (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement : string -&gt; Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement" Usage="new Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="ee5ec-103">Ein Name, der dieses Konfigurationselement eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-103">A name that uniquely identifies this configuration element.</span></span></param>
        <summary><span data-ttu-id="ee5ec-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement" />-Klasse unter Verwendung des angegebenen Namens.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement" /> class using the specified name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ee5ec-105">Ruft ab oder legt einen XML-Wert, der den Typ des Bindungselements darstellt, der die aktuelle Instanz enthält.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-105">Gets or sets an XML value that contains the type of binding element of the current instance.</span></span></summary>
        <value><span data-ttu-id="ee5ec-106">Gibt eine <see cref="T:System.Type" /> , der den Typ der aktuellen Instanz enthält.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-106">Returns a <see cref="T:System.Type" /> that contains the type of the current instance.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="netOnewayRelayBindingElement.InitializeFrom binding" />
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
        <param name="binding"> <span data-ttu-id="ee5ec-107">Die Bindung.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-107">The binding.</span></span></param>
        <summary><span data-ttu-id="ee5ec-108">Initialisiert die aktuelle Instanz mit dem Inhalt der angegebenen Bindung.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-108">Initializes the current instance using the content of the specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenBacklog">
      <MemberSignature Language="C#" Value="public int ListenBacklog { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ListenBacklog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.ListenBacklog" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenBacklog As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenBacklog : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.ListenBacklog" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("listenBacklog", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ee5ec-109">Ruft ab oder legt einen XML-Wert, der die maximale Anzahl von verbindungsanforderungen in der Warteschlange enthält, die anstehen können.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-109">Gets or sets an XML value that contains the maximum number of queued connection requests that can be pending.</span></span></summary>
        <value><span data-ttu-id="ee5ec-110">Gibt die maximal mögliche Anzahl der ausstehenden Verbindungsanforderungen in der Warteschlange zurück.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-110">Returns the maximum number of queued connection requests that can be pending.</span></span> <span data-ttu-id="ee5ec-111">Der Standard ist 10.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-111">The default is 10.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.MaxBufferPoolSize" />
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
        <summary><span data-ttu-id="ee5ec-112">Ruft ab oder legt einen XML-Wert, der die maximale zulässige Größe für einen Pufferpool, der von der Bindung verarbeitet Nachrichten gespeichert werden, enthält.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-112">Gets or sets an XML value that contains the maximum size allowed for a buffer pool that stores messages processed by the binding.</span></span></summary>
        <value><span data-ttu-id="ee5ec-113">Gibt zulässige die maximale Größe für einen Pufferpool, der von der Bindung verarbeitet Nachrichten gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-113">Returns the maximum size allowed for a buffer pool that stores messages processed by the binding.</span></span> <span data-ttu-id="ee5ec-114">Der Standardwert ist 65.536.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-114">The default value is 65,536.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.MaxBufferSize" />
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
        <summary><span data-ttu-id="ee5ec-115">Ruft ab oder legt einen XML-Wert, der die maximale Größe des Puffers zum Speichern von Nachrichten im Arbeitsspeicher in Bytes enthält.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-115">Gets or sets an XML value that contains the maximum size, in bytes, of the buffer used to store messages in memory.</span></span></summary>
        <value><span data-ttu-id="ee5ec-116">Gibt die maximale Größe des Puffers zum Speichern von Nachrichten im Arbeitsspeicher in Bytes zurück.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-116">Returns the maximum size, in bytes, of the buffer used to store messages in memory.</span></span> <span data-ttu-id="ee5ec-117">Der Standardwert ist 65.536 Bytes.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-117">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConnections">
      <MemberSignature Language="C#" Value="public int MaxConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.MaxConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConnections : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.MaxConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxConnections", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ee5ec-118">Ruft ab oder legt einen XML-Wert, der die maximale Anzahl ausgehender und eingehender Verbindungen angibt, der Dienst erstellt bzw. annimmt.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-118">Gets or sets an XML value that specifies the maximum number of outbound and inbound connections the service creates and accepts respectively.</span></span></summary>
        <value><span data-ttu-id="ee5ec-119">Auf dem Client gibt die maximale Anzahl an Verbindungen, für die nachfolgende Wiederverwendung "zusammengelegt" werden; auf dem Server gibt Sie die maximale Anzahl zulässiger Verbindungen mit "Ausstehend" Verteilung zurück.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-119">On the client, returns the maximum number of connections to be pooled for subsequent reuse; on the server, returns the maximum number of connections allowed to be pending dispatch.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.MaxReceivedMessageSize" />
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
        <summary><span data-ttu-id="ee5ec-120">Ruft ab oder legt einen XML-Wert, der die maximale Größe einer Nachricht enthält, die in einem mit dieser Bindung konfigurierten Kanal beim Nachrichtenempfang zulässig.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-120">Gets or sets an XML value that contains the maximum size of a message that can be received on a channel configured with this binding.</span></span></summary>
        <value><span data-ttu-id="ee5ec-121">Gibt die maximale Größe in Byte für eine Nachricht, die von der Bindung verarbeitet wird zurück.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-121">Returns maximum size, in bytes, for a message that is processed by the binding.</span></span> <span data-ttu-id="ee5ec-122">Der Standardwert ist 65.536 Bytes.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-122">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="netOnewayRelayBindingElement.OnApplyConfiguration binding" />
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
        <param name="binding"> <span data-ttu-id="ee5ec-123">Die Bindung, die Einstellungen zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-123">The binding to update the settings of.</span></span></param>
        <summary><span data-ttu-id="ee5ec-124">Wendet die Einstellungen dieses Konfigurationselements auf die angegebene Bindung.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-124">Applies the settings of this configuration element to the specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ee5ec-125">Ruft eine ConfigurationPropertyCollection-Instanz, die eine Auflistung von ConfigurationProperty-Objekte, die Attribute werden können oder ConfigurationElement dieses Konfigurationselements enthält.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-125">Gets a ConfigurationPropertyCollection instance that contains a collection of ConfigurationProperty objects that can be attributes or ConfigurationElement objects of this configuration element.</span></span></summary>
        <value><span data-ttu-id="ee5ec-126">Gibt eine <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> , die eine Auflistung von ConfigurationProperty-Objekte, die Attribute werden können oder ConfigurationElement dieses Konfigurationselements enthält.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-126">Returns a <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> that contains a collection of ConfigurationProperty objects that can be attributes or ConfigurationElement objects of this configuration element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReaderQuotas As XmlDictionaryReaderQuotasElement" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" Usage="Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.ReaderQuotas" />
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
        <summary><span data-ttu-id="ee5ec-127">Ruft ab oder legt einen XML-Wert, der eine Einschränkung für die Komplexität von SOAP-Nachrichten gespeichert werden, die von mit dieser Bindung konfigurierten Endpunkten verarbeitet werden können.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-127">Gets or sets an XML value that places a constraint on the complexity of SOAP messages that can be processed by endpoints configured with this binding.</span></span></summary>
        <value><span data-ttu-id="ee5ec-128">Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" /> , das die komplexitätseinschränkungen für SOAP-Nachrichten angibt.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-128">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" /> that specifies the complexity constraints on SOAP messages.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.NetOnewayRelaySecurityElement Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.NetOnewayRelaySecurityElement Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As NetOnewayRelaySecurityElement" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.Configuration.NetOnewayRelaySecurityElement" Usage="Microsoft.ServiceBus.Configuration.NetOnewayRelayBindingElement.Security" />
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
        <ReturnType>Microsoft.ServiceBus.Configuration.NetOnewayRelaySecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ee5ec-129">Ruft einen XML-Wert, der Sicherheitselemente für eine Service Bus unidirektionale TCP-Relay-Bindung enthält.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-129">Gets an XML value that contains security elements for a Service Bus one-way TCP relay binding.</span></span></summary>
        <value><span data-ttu-id="ee5ec-130">Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.NetOnewayRelaySecurityElement" /> , die die Sicherheitselemente beschreibt.</span><span class="sxs-lookup"><span data-stu-id="ee5ec-130">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.NetOnewayRelaySecurityElement" /> that describes the security elements.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>