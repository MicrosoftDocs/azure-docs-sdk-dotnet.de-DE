<Type Name="NetMessagingTransportExtensionElement" FullName="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement">
  <TypeSignature Language="C#" Value="public sealed class NetMessagingTransportExtensionElement : System.ServiceModel.Configuration.TransportElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetMessagingTransportExtensionElement extends System.ServiceModel.Configuration.TransportElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetMessagingTransportExtensionElement&#xA;Inherits TransportElement" />
  <TypeSignature Language="F#" Value="type NetMessagingTransportExtensionElement = class&#xA;    inherit TransportElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.TransportElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="762fa-101">Stellt die Net messaging Transport Extension-Element dar.</span><span class="sxs-lookup"><span data-stu-id="762fa-101">Represents the net messaging transport extension element.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetMessagingTransportExtensionElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="762fa-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="762fa-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyConfiguration">
      <MemberSignature Language="C#" Value="public override void ApplyConfiguration (System.ServiceModel.Channels.BindingElement bindingElement);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ApplyConfiguration(class System.ServiceModel.Channels.BindingElement bindingElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement.ApplyConfiguration(System.ServiceModel.Channels.BindingElement)" />
      <MemberSignature Language="F#" Value="override this.ApplyConfiguration : System.ServiceModel.Channels.BindingElement -&gt; unit" Usage="netMessagingTransportExtensionElement.ApplyConfiguration bindingElement" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bindingElement" Type="System.ServiceModel.Channels.BindingElement" />
      </Parameters>
      <Docs>
        <param name="bindingElement">
            <span data-ttu-id="762fa-103">Das <see cref="T:System.ServiceModel.Channels.BindingElement" /> dieses Konfigurationselements.</span><span class="sxs-lookup"><span data-stu-id="762fa-103">The <see cref="T:System.ServiceModel.Channels.BindingElement" /> to this configuration element.</span></span>
            </param>
        <summary> <span data-ttu-id="762fa-104">Übernimmt die Einstellungen vom angegebenen <see cref="T:&#xA;            System.ServiceModel.Channels.BindingElement" /> für dieses Konfigurationselement.</span><span class="sxs-lookup"><span data-stu-id="762fa-104">Applies the settings of the specified <see cref="T:&#xA;            System.ServiceModel.Channels.BindingElement" /> to this configuration element.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="public override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="762fa-105">Ruft den Typ des Bindungselements darstellt, die verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="762fa-105">Gets the type of binding element being used.</span></span></summary>
        <value><span data-ttu-id="762fa-106">Der Typ des Bindungselements darstellt, die verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="762fa-106">The type of binding element being used.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public override void CopyFrom (System.ServiceModel.Configuration.ServiceModelExtensionElement from);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void CopyFrom(class System.ServiceModel.Configuration.ServiceModelExtensionElement from) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement.CopyFrom(System.ServiceModel.Configuration.ServiceModelExtensionElement)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub CopyFrom (from As ServiceModelExtensionElement)" />
      <MemberSignature Language="F#" Value="override this.CopyFrom : System.ServiceModel.Configuration.ServiceModelExtensionElement -&gt; unit" Usage="netMessagingTransportExtensionElement.CopyFrom from" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.ServiceModel.Configuration.ServiceModelExtensionElement" />
      </Parameters>
      <Docs>
        <param name="from">
            <span data-ttu-id="762fa-107">Das Konfigurationselement, dessen Einstellungen in dieses Konfigurationselement kopiert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="762fa-107">The configuration element whose settings are to be copied to this configuration element.</span></span>
            </param>
        <summary> <span data-ttu-id="762fa-108">Kopiert die Einstellungen des angegebenen Konfigurationselements in dieses Konfigurationselement.</span><span class="sxs-lookup"><span data-stu-id="762fa-108">Copies the settings from the specified configuration element to this configuration element.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDefaultBindingElement">
      <MemberSignature Language="C#" Value="protected override System.ServiceModel.Channels.TransportBindingElement CreateDefaultBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.ServiceModel.Channels.TransportBindingElement CreateDefaultBindingElement() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement.CreateDefaultBindingElement" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateDefaultBindingElement () As TransportBindingElement" />
      <MemberSignature Language="F#" Value="override this.CreateDefaultBindingElement : unit -&gt; System.ServiceModel.Channels.TransportBindingElement" Usage="netMessagingTransportExtensionElement.CreateDefaultBindingElement " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.TransportBindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary> <span data-ttu-id="762fa-109">Gibt ein benutzerdefiniertes Bindungselementobjekt mit Standardwerten zurück.</span><span class="sxs-lookup"><span data-stu-id="762fa-109">Returns a custom binding element object with default values.</span></span> </summary>
        <returns> <span data-ttu-id="762fa-110">Ein benutzerdefiniertes <see cref="T:System.ServiceModel.Channels.BindingElement" />-Objekt mit Standardwerten.</span><span class="sxs-lookup"><span data-stu-id="762fa-110">A custom <see cref="T:System.ServiceModel.Channels.BindingElement" /> object with default values.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.BindingElement bindingElement);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.BindingElement bindingElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement.InitializeFrom(System.ServiceModel.Channels.BindingElement)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.BindingElement -&gt; unit" Usage="netMessagingTransportExtensionElement.InitializeFrom bindingElement" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bindingElement" Type="System.ServiceModel.Channels.BindingElement" />
      </Parameters>
      <Docs>
        <param name="bindingElement"> <span data-ttu-id="762fa-111">Ein Bindungselement.</span><span class="sxs-lookup"><span data-stu-id="762fa-111">A binding element.</span></span> </param>
        <summary> <span data-ttu-id="762fa-112">Initialisiert dieses Bindungskonfigurationselement mit dem Inhalt des angegebenen Bindungselements.</span><span class="sxs-lookup"><span data-stu-id="762fa-112">Initializes this binding configuration element with the content of the specified binding element.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("prefetchCount", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="762fa-113">Ruft ab oder legt die Anzahl der Prefetch.</span><span class="sxs-lookup"><span data-stu-id="762fa-113">Gets or sets the number of prefetch.</span></span></summary>
        <value><span data-ttu-id="762fa-114">Die Anzahl der Prefetch.</span><span class="sxs-lookup"><span data-stu-id="762fa-114">The number of prefetch.</span></span></value>
        <remarks> <span data-ttu-id="762fa-115">Wirkt sich auf die nächste empfangsaufruf mit dem server</span><span class="sxs-lookup"><span data-stu-id="762fa-115">Takes effect on the next receive call to the server</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="762fa-116">Ruft die <seealso cref="T:System.Configuration.ConfigurationPropertyCollection" /> Konfigurationseigenschaft.</span><span class="sxs-lookup"><span data-stu-id="762fa-116">Gets the <seealso cref="T:System.Configuration.ConfigurationPropertyCollection" /> configuration property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionIdleTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan SessionIdleTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan SessionIdleTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement.SessionIdleTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionIdleTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.SessionIdleTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement.SessionIdleTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("sessionIdleTimeout", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.PositiveTimeSpanValidator</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="762fa-117">Ruft ab oder legt die SessionIdleTimeout.</span><span class="sxs-lookup"><span data-stu-id="762fa-117">Gets or sets the SessionIdleTimeout.</span></span></summary>
        <value><span data-ttu-id="762fa-118">Wenn ein Vorgang IInputSessionChannel.TryReceive Meldung(en) innerhalb dieser Zeitspanne keine erhält, wird der Kanal Ende der Sitzung angegeben.</span><span class="sxs-lookup"><span data-stu-id="762fa-118">If an IInputSessionChannel.TryReceive operation doesn’t receive any message within this TimeSpan then the channel will indicate end of session.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransportSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement TransportSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement TransportSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement.TransportSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransportSettings As NetMessagingTransportSettingsElement" />
      <MemberSignature Language="F#" Value="member this.TransportSettings : Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportExtensionElement.TransportSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("transportSettings", IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="762fa-119">Ruft ab oder legt das Transportbindungselement der Einstellungen für die net-messaging.</span><span class="sxs-lookup"><span data-stu-id="762fa-119">Gets or sets the transport settings element for the net messaging.</span></span></summary>
        <value><span data-ttu-id="762fa-120">Das Transportelement des Einstellungen für die net-messaging.</span><span class="sxs-lookup"><span data-stu-id="762fa-120">The transport settings element for the net messaging.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>