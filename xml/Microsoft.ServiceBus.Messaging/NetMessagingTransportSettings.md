<Type Name="NetMessagingTransportSettings" FullName="Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings">
  <TypeSignature Language="C#" Value="public sealed class NetMessagingTransportSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetMessagingTransportSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetMessagingTransportSettings" />
  <TypeSignature Language="F#" Value="type NetMessagingTransportSettings = class&#xA;    interface ITransportSettings&#xA;    interface IServiceBusSecuritySettings" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="8bf0d-101">Stellt die .NET messaging transporteinstellungen dar.</span><span class="sxs-lookup"><span data-stu-id="8bf0d-101">Represents .NET messaging transport settings.</span></span></summary>
    <remarks>
            <span data-ttu-id="8bf0d-102">Diese Klasse bietet Unterstützung für die spezifische Konfiguration Net Messaging Protocol (SBMP) für die NetMessagingBinding.MessagingFactorySettings-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="8bf0d-102">This class provides Net Messaging Protocol (SBMP) specific configuration support for the NetMessagingBinding.MessagingFactorySettings property.</span></span>  
            <span data-ttu-id="8bf0d-103">Macht zur Konfiguration der Einstellungen, die auf die MessagingFactorySettings zur Verfügung stehen.</span><span class="sxs-lookup"><span data-stu-id="8bf0d-103">It exposes to configuration the settings available on the MessagingFactorySettings.</span></span>
            </remarks>
    <altmember cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />
    <altmember cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
    <example>
      <code>
            <span data-ttu-id="8bf0d-104">Erstellen von Einstellungen für die MessagingFactory (für laufzeitvorgänge) MessagingFactorySettings FactorySettings neue MessagingFactorySettings() = {NetMessagingTransportSettings = neue NetMessagingTransportSettings(), Anmeldeinformationen = TransportClientCredentialBase.CreateSharedSecretCredential (IssuerName, IssuerKey)};</span><span class="sxs-lookup"><span data-stu-id="8bf0d-104">// Create settings for the MessagingFactory (for runtime operations) MessagingFactorySettings factorySettings = new MessagingFactorySettings() { NetMessagingTransportSettings = new NetMessagingTransportSettings(), Credential = TransportClientCredentialBase.CreateSharedSecretCredential(IssuerName, IssuerKey), };</span></span>
            
            <span data-ttu-id="8bf0d-105">Erstellen der Factory MessagingFactory MessagingFactory = MessagingFactory.Create (MyServiceBusNamespace, FactorySettings);</span><span class="sxs-lookup"><span data-stu-id="8bf0d-105">// Create the MessagingFactory MessagingFactory factory = MessagingFactory.Create(myServiceBusNamespace, factorySettings);</span></span>
            
            <span data-ttu-id="8bf0d-106">Anwendungswarteschlangen-Client erstellen</span><span class="sxs-lookup"><span data-stu-id="8bf0d-106">// Create queue client</span></span>
            
            </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetMessagingTransportSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="8bf0d-107">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8bf0d-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchFlushInterval">
      <MemberSignature Language="C#" Value="public TimeSpan BatchFlushInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan BatchFlushInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.BatchFlushInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchFlushInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.BatchFlushInterval : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.BatchFlushInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8bf0d-108">Ruft ab oder legt die batchleerungsintervall.</span><span class="sxs-lookup"><span data-stu-id="8bf0d-108">Gets or sets the batch flush interval.</span></span></summary>
        <value><span data-ttu-id="8bf0d-109">Batchleerungsintervall.</span><span class="sxs-lookup"><span data-stu-id="8bf0d-109">The batch flush interval.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public object Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Object" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; obj&#xA;override this.Clone : unit -&gt; obj" Usage="netMessagingTransportSettings.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.ITransportSettings.Clone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="8bf0d-110">Erstellt eine tiefe Kopie dieses Objekts.</span><span class="sxs-lookup"><span data-stu-id="8bf0d-110">Makes a deep copy of this object.</span></span></summary>
        <returns><span data-ttu-id="8bf0d-111">Eine Kopie dieses Objekts.</span><span class="sxs-lookup"><span data-stu-id="8bf0d-111">A copy of this object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableRedirect">
      <MemberSignature Language="C#" Value="public bool EnableRedirect { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableRedirect" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.EnableRedirect" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableRedirect As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableRedirect : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.EnableRedirect" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8bf0d-112">Ruft einen Wert, der angibt, ob die Nachricht Umleitung aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="8bf0d-112">Gets a value that indicates whether the message redirect is enabled.</span></span></summary>
        <value><span data-ttu-id="8bf0d-113">"true", wenn die Nachricht Umleitung aktiviert ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="8bf0d-113">true if the message redirect is enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.LeaseTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.LeaseTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bf0d-114">Ruft ab oder legt den Lease-Timeoutwert für die Eigenschaft LeaseTimeout innerhalb der <seealso cref="P:System.ServiceModel.Channels.TcpTransportBindingElement.ConnectionPoolSettings" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="8bf0d-114">Gets or sets the lease timeout value for the LeaseTimeout property within the <seealso cref="P:System.ServiceModel.Channels.TcpTransportBindingElement.ConnectionPoolSettings" /> class.</span></span>
            <span data-ttu-id="8bf0d-115">Die Standardeinstellung ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="8bf0d-115">Default is 5 minutes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="8bf0d-116">Lösen Sie aus, wenn der Wert kleiner sein als TimeSpan.Zero oder größer als Int32.MaxValue-Millisekunden ist.</span><span class="sxs-lookup"><span data-stu-id="8bf0d-116">throw if value is less than TimeSpan.Zero or larger than Int32.MaxValue milliseconds</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>