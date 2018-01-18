<Type Name="NetEventRelayBinding" FullName="Microsoft.ServiceBus.NetEventRelayBinding">
  <TypeSignature Language="C#" Value="public class NetEventRelayBinding : Microsoft.ServiceBus.NetOnewayRelayBinding, System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetEventRelayBinding extends Microsoft.ServiceBus.NetOnewayRelayBinding implements class System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NetEventRelayBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class NetEventRelayBinding&#xA;Inherits NetOnewayRelayBinding&#xA;Implements IBindingRuntimePreferences" />
  <TypeSignature Language="F#" Value="type NetEventRelayBinding = class&#xA;    inherit NetOnewayRelayBinding&#xA;    interface IBindingRuntimePreferences" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.NetOnewayRelayBinding</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Channels.IBindingRuntimePreferences</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="09940-101">Stellt eine Bindung, die unidirektionale Ereignis Multicasting unterstützt und kann eine beliebige Anzahl von Ereignisherausgeber und -Ereignisconsumer rendezvous-am selben Endpunkt dar.</span><span class="sxs-lookup"><span data-stu-id="09940-101">Represents a binding that supports one-way event multicasting and allows any number of event publishers and event consumers to rendezvous at the same endpoint.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetEventRelayBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetEventRelayBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="09940-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="09940-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetEventRelayBinding (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetEventRelayBinding.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configurationName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetEventRelayBinding : string -&gt; Microsoft.ServiceBus.NetEventRelayBinding" Usage="new Microsoft.ServiceBus.NetEventRelayBinding configurationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configurationName"><span data-ttu-id="09940-103">Der Name der die zu verwendende Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="09940-103">The name of the configuration to use.</span></span></param>
        <summary><span data-ttu-id="09940-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" /> -Klasse unter Verwendung der angegebenen Konfigurations.</span><span class="sxs-lookup"><span data-stu-id="09940-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" /> class, using the specified configuration.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetEventRelayBinding (Microsoft.ServiceBus.EndToEndSecurityMode securityMode, Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetEventRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (securityMode As EndToEndSecurityMode, relayClientAuthenticationType As RelayEventSubscriberAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetEventRelayBinding : Microsoft.ServiceBus.EndToEndSecurityMode * Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType -&gt; Microsoft.ServiceBus.NetEventRelayBinding" Usage="new Microsoft.ServiceBus.NetEventRelayBinding (securityMode, relayClientAuthenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="securityMode" Type="Microsoft.ServiceBus.EndToEndSecurityMode" />
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="securityMode"><span data-ttu-id="09940-105">Der Typ der Sicherheit, die die SOAP-Nachricht und für den Client verwendet.</span><span class="sxs-lookup"><span data-stu-id="09940-105">The type of security used with the SOAP message and for the client.</span></span> </param>
        <param name="relayClientAuthenticationType"><span data-ttu-id="09940-106">Der Typ des vom Client verwendeten Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="09940-106">The type of authentication used by the client.</span></span></param>
        <summary><span data-ttu-id="09940-107">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" /> -Klasse unter Verwendung der angegebenen Sicherheit Modus und Relay-Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="09940-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" /> class, using the specified security mode and relay client authentication type.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetEventRelayBinding (Microsoft.ServiceBus.RelayedOnewayTransportBindingElement transport, System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, Microsoft.ServiceBus.NetOnewayRelaySecurity security);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.RelayedOnewayTransportBindingElement transport, class System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, class Microsoft.ServiceBus.NetOnewayRelaySecurity security) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetEventRelayBinding.#ctor(Microsoft.ServiceBus.RelayedOnewayTransportBindingElement,System.ServiceModel.Channels.BinaryMessageEncodingBindingElement,Microsoft.ServiceBus.NetOnewayRelaySecurity)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (transport As RelayedOnewayTransportBindingElement, encoding As BinaryMessageEncodingBindingElement, security As NetOnewayRelaySecurity)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetEventRelayBinding : Microsoft.ServiceBus.RelayedOnewayTransportBindingElement * System.ServiceModel.Channels.BinaryMessageEncodingBindingElement * Microsoft.ServiceBus.NetOnewayRelaySecurity -&gt; Microsoft.ServiceBus.NetEventRelayBinding" Usage="new Microsoft.ServiceBus.NetEventRelayBinding (transport, encoding, security)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transport" Type="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" />
        <Parameter Name="encoding" Type="System.ServiceModel.Channels.BinaryMessageEncodingBindingElement" />
        <Parameter Name="security" Type="Microsoft.ServiceBus.NetOnewayRelaySecurity" />
      </Parameters>
      <Docs>
        <param name="transport"> <span data-ttu-id="09940-108">Die zu verwendende Transport.</span><span class="sxs-lookup"><span data-stu-id="09940-108">The transport to use.</span></span> </param>
        <param name="encoding"> <span data-ttu-id="09940-109">Die zu verwendende Codierung.</span><span class="sxs-lookup"><span data-stu-id="09940-109">The encoding to use.</span></span> </param>
        <param name="security"> <span data-ttu-id="09940-110">Der Typ der Sicherheit, die die SOAP-Nachricht und für den Client verwendet.</span><span class="sxs-lookup"><span data-stu-id="09940-110">The type of security used with the SOAP message and for the client.</span></span> </param>
        <summary><span data-ttu-id="09940-111">Initialisiert eine neue Instanz der dem<see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" /> -Klasse unter Verwendung der angegebenen Elemente für Transport, Codierung und Sicherheit.</span><span class="sxs-lookup"><span data-stu-id="09940-111">Initializes a new instance of the<see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" /> class, using the specified transport, encoding, and security elements.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void ApplyConfiguration (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void ApplyConfiguration(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetEventRelayBinding.ApplyConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub ApplyConfiguration (configurationName As String)" />
      <MemberSignature Language="F#" Value="override this.ApplyConfiguration : string -&gt; unit" Usage="netEventRelayBinding.ApplyConfiguration configurationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configurationName"><span data-ttu-id="09940-112">Der Name des Konfigurationselements werden die Einstellungen aus.</span><span class="sxs-lookup"><span data-stu-id="09940-112">The name of the configuration element to take the settings from.</span></span></param>
        <summary><span data-ttu-id="09940-113">Die Einstellungen des Konfigurationselements, das entspricht dem angegebenen Namen auf die aktuelle Instanz dieses Bindungselements angewendet.</span><span class="sxs-lookup"><span data-stu-id="09940-113">Applies the settings from the configuration element that corresponds to the specified name to the current instance of this binding element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBindingElementsMatch">
      <MemberSignature Language="C#" Value="protected bool IsBindingElementsMatch (Microsoft.ServiceBus.RelayedOnewayTransportBindingElement transport, System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, System.ServiceModel.Channels.ReliableSessionBindingElement session);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance bool IsBindingElementsMatch(class Microsoft.ServiceBus.RelayedOnewayTransportBindingElement transport, class System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, class System.ServiceModel.Channels.ReliableSessionBindingElement session) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetEventRelayBinding.IsBindingElementsMatch(Microsoft.ServiceBus.RelayedOnewayTransportBindingElement,System.ServiceModel.Channels.BinaryMessageEncodingBindingElement,System.ServiceModel.Channels.ReliableSessionBindingElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Function IsBindingElementsMatch (transport As RelayedOnewayTransportBindingElement, encoding As BinaryMessageEncodingBindingElement, session As ReliableSessionBindingElement) As Boolean" />
      <MemberSignature Language="F#" Value="override this.IsBindingElementsMatch : Microsoft.ServiceBus.RelayedOnewayTransportBindingElement * System.ServiceModel.Channels.BinaryMessageEncodingBindingElement * System.ServiceModel.Channels.ReliableSessionBindingElement -&gt; bool" Usage="netEventRelayBinding.IsBindingElementsMatch (transport, encoding, session)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transport" Type="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" />
        <Parameter Name="encoding" Type="System.ServiceModel.Channels.BinaryMessageEncodingBindingElement" />
        <Parameter Name="session" Type="System.ServiceModel.Channels.ReliableSessionBindingElement" />
      </Parameters>
      <Docs>
        <param name="transport"> <span data-ttu-id="09940-114">Der Transport, auf die aktuelle Instanz geprüft werden soll.</span><span class="sxs-lookup"><span data-stu-id="09940-114">The transport to check against the current instance.</span></span> </param>
        <param name="encoding"> <span data-ttu-id="09940-115">Die Codierung für die aktuelle Instanz zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="09940-115">The encoding to check against the current instance.</span></span> </param>
        <param name="session"> <span data-ttu-id="09940-116">Die Sitzung, auf die aktuelle Instanz geprüft werden soll.</span><span class="sxs-lookup"><span data-stu-id="09940-116">The session to check against the current instance.</span></span></param>
        <summary><span data-ttu-id="09940-117">Ruft einen Wert, der bestimmt, ob die angegebenen Bindungselemente der aktuellen Instanz übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="09940-117">Retrieves a value that determines if the specified binding elements match the current instance.</span></span> </summary>
        <returns><span data-ttu-id="09940-118">Gibt "true" zurück, wenn die Bindungen übereinstimmen; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="09940-118">Returns true if the bindings match; otherwise, false.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>