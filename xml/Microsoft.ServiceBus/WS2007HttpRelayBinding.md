<Type Name="WS2007HttpRelayBinding" FullName="Microsoft.ServiceBus.WS2007HttpRelayBinding">
  <TypeSignature Language="C#" Value="public class WS2007HttpRelayBinding : Microsoft.ServiceBus.WSHttpRelayBinding" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WS2007HttpRelayBinding extends Microsoft.ServiceBus.WSHttpRelayBinding" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.WS2007HttpRelayBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class WS2007HttpRelayBinding&#xA;Inherits WSHttpRelayBinding" />
  <TypeSignature Language="F#" Value="type WS2007HttpRelayBinding = class&#xA;    inherit WSHttpRelayBinding" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.WSHttpRelayBinding</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="6df5c-101">Stellt eine interoperable Bindung, die abgeleitet <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> und bietet Unterstützung für die aktualisierten Versionen der Bindungselemente Sicherheit, ReliableSession und TransactionFlow-Protokolls.</span><span class="sxs-lookup"><span data-stu-id="6df5c-101">Represents an interoperable binding that derives from <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> and provides support for the updated versions of the Security, ReliableSession, and TransactionFlow binding elements.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WS2007HttpRelayBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WS2007HttpRelayBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6df5c-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.WS2007HttpRelayBinding" />-Klasse mit einem von der Bindung verwendeten Sicherheitstyp.</span><span class="sxs-lookup"><span data-stu-id="6df5c-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.WS2007HttpRelayBinding" /> class with a specified type of security used by the binding.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WS2007HttpRelayBinding (string configName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WS2007HttpRelayBinding.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.WS2007HttpRelayBinding : string -&gt; Microsoft.ServiceBus.WS2007HttpRelayBinding" Usage="new Microsoft.ServiceBus.WS2007HttpRelayBinding configName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configName"><span data-ttu-id="6df5c-103">Der Konfigurationsname der Bindung für die<see cref="T:Microsoft.ServiceBus.Configuration.WS2007HttpRelayBindingElement" /></span><span class="sxs-lookup"><span data-stu-id="6df5c-103">The binding configuration name for the <see cref="T:Microsoft.ServiceBus.Configuration.WS2007HttpRelayBindingElement" /></span></span></param>
        <summary><span data-ttu-id="6df5c-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.WS2007HttpRelayBinding" />-Klasse mit einer durch ihren Konfigurationsnamen angegebenen Bindung.</span><span class="sxs-lookup"><span data-stu-id="6df5c-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.WS2007HttpRelayBinding" /> class with a binding specified by its configuration name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WS2007HttpRelayBinding (Microsoft.ServiceBus.EndToEndSecurityMode securityMode, Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WS2007HttpRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.WS2007HttpRelayBinding : Microsoft.ServiceBus.EndToEndSecurityMode * Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.WS2007HttpRelayBinding" Usage="new Microsoft.ServiceBus.WS2007HttpRelayBinding (securityMode, relayClientAuthenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="securityMode" Type="Microsoft.ServiceBus.EndToEndSecurityMode" />
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="securityMode"><span data-ttu-id="6df5c-105">Der Sicherheitsmodus, der den Sicherheitstyp angibt, das die SOAP-Nachricht und für den Client verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="6df5c-105">The security mode that specifies the type of security that is used with the SOAP message and for the client.</span></span></param>
        <param name="relayClientAuthenticationType"><span data-ttu-id="6df5c-106">Der Typ des vom Client verwendeten Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="6df5c-106">The type of authentication used by the client.</span></span></param>
        <summary><span data-ttu-id="6df5c-107">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.WS2007HttpRelayBinding" /> Klasse mit einem angegebenen Typ der Sicherheit und Relay-Clientauthentifizierung, die von der Bindung verwendet.</span><span class="sxs-lookup"><span data-stu-id="6df5c-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.WS2007HttpRelayBinding" /> class with a specified type of security and relay client authentication used by the binding.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WS2007HttpRelayBinding (Microsoft.ServiceBus.EndToEndSecurityMode securityMode, Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType, bool reliableSessionEnabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType, bool reliableSessionEnabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WS2007HttpRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType,System.Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.WS2007HttpRelayBinding : Microsoft.ServiceBus.EndToEndSecurityMode * Microsoft.ServiceBus.RelayClientAuthenticationType * bool -&gt; Microsoft.ServiceBus.WS2007HttpRelayBinding" Usage="new Microsoft.ServiceBus.WS2007HttpRelayBinding (securityMode, relayClientAuthenticationType, reliableSessionEnabled)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="securityMode" Type="Microsoft.ServiceBus.EndToEndSecurityMode" />
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
        <Parameter Name="reliableSessionEnabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="securityMode"><span data-ttu-id="6df5c-108">Gibt an, der den Sicherheitstyp, der die SOAP-Nachricht und für den Client verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="6df5c-108">Specifies the type of security that is used with the SOAP message and for the client.</span></span></param>
        <param name="relayClientAuthenticationType"><span data-ttu-id="6df5c-109">Der Typ des vom Client verwendeten Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="6df5c-109">The type of authentication used by the client.</span></span></param>
        <param name="reliableSessionEnabled"><span data-ttu-id="6df5c-110">"true", wenn eine zuverlässige Sitzung aktiviert ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="6df5c-110">true if a reliable session is enabled; otherwise, false.</span></span></param>
        <summary><span data-ttu-id="6df5c-111">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.WS2007HttpRelayBinding" /> Klasse mit einem angegebenen Typ der Sicherheit, die von der Bindung verwendet, den angegebenen Authentifizierungstyp für das Client-Relay und einem Wert, der angibt, ob eine zuverlässige Sitzung aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="6df5c-111">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.WS2007HttpRelayBinding" /> class with a specified type of security used by the binding, the specified authentication for the client relay, and a value that indicates whether a reliable session is enabled.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSecurity">
      <MemberSignature Language="C#" Value="protected override System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WS2007HttpRelayBinding.CreateMessageSecurity" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateMessageSecurity () As SecurityBindingElement" />
      <MemberSignature Language="F#" Value="override this.CreateMessageSecurity : unit -&gt; System.ServiceModel.Channels.SecurityBindingElement" Usage="wS2007HttpRelayBinding.CreateMessageSecurity " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.SecurityBindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6df5c-112">Ruft das Sicherheitsbindungselement von der aktuellen Bindung ab.</span><span class="sxs-lookup"><span data-stu-id="6df5c-112">Retrieves the security binding element from the current binding.</span></span></summary>
        <returns><span data-ttu-id="6df5c-113">Gibt eine <see cref="T:System.ServiceModel.Channels.SecurityBindingElement" /> , die das aktuelle Sicherheitsbindungselement enthält.</span><span class="sxs-lookup"><span data-stu-id="6df5c-113">Returns a <see cref="T:System.ServiceModel.Channels.SecurityBindingElement" /> that contains the current security binding element.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>