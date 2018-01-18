<Type Name="NetTcpRelaySecurityElement" FullName="Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement">
  <TypeSignature Language="C#" Value="public sealed class NetTcpRelaySecurityElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetTcpRelaySecurityElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetTcpRelaySecurityElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type NetTcpRelaySecurityElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="69d20-101">Stellt ein Konfigurationselement, das die Sicherheit für einen net-TCP-Dienst über die Azure Service Bus-Relay konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="69d20-101">Represents a configuration element that configures the security for a net TCP service through the Azure Service Bus relay.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelaySecurityElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayConnectionElement Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayConnectionElement Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As MessageSecurityOverRelayConnectionElement" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayConnectionElement" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayConnectionElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="69d20-102">Ruft ein Konfigurationselement, das die nachrichtensicherheitseinstellungen für die <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span><span class="sxs-lookup"><span data-stu-id="69d20-102">Gets a configuration element that represents the message security settings for the <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span></span></summary>
        <value><span data-ttu-id="69d20-103">Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayConnectionElement" /> , die die Nachricht enthält.</span><span class="sxs-lookup"><span data-stu-id="69d20-103">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayConnectionElement" /> that contains the message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndSecurityMode with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("mode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndSecurityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="69d20-104">Ruft ab oder legt einen XML-Wert, der beschreibt, ob Sicherheit auf Nachrichtenebene oder auf Transportebene von einem mit konfigurierten Endpunkt verwendet wird <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span><span class="sxs-lookup"><span data-stu-id="69d20-104">Gets or sets an XML value that describes whether message-level or transport-level security is used by an endpoint configured with <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span></span></summary>
        <value><span data-ttu-id="69d20-105">Gibt eine <see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" /> , enthält den Sicherheitsmodus.</span><span class="sxs-lookup"><span data-stu-id="69d20-105">Returns a <see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" /> that contains the security mode.</span></span> <span data-ttu-id="69d20-106">Der Standardwert ist Transport.</span><span class="sxs-lookup"><span data-stu-id="69d20-106">The default value is Transport.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.Properties" />
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
            <span data-ttu-id="69d20-107">Ruft die Auflistung von Eigenschaften ab.</span><span class="sxs-lookup"><span data-stu-id="69d20-107">Gets the collection of properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("relayClientAuthenticationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="69d20-108">Ruft ab oder legt den Authentifizierungstyp, der für den Client an den Azure-Servicebus zu präsentieren, beim Senden von Nachrichten erforderlich.</span><span class="sxs-lookup"><span data-stu-id="69d20-108">Gets or sets the authentication type required for the client to present to the Azure Service Bus when sending messages.</span></span></summary>
        <value><span data-ttu-id="69d20-109">Gibt eine <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> , der Authentifizierungstyp enthält.</span><span class="sxs-lookup"><span data-stu-id="69d20-109">Returns a <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> that contains the authentication type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As TcpRelayTransportSecurityElement" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.Transport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("transport")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="69d20-110">Ruft die sicherheitseinstellung "Transport" für die <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span><span class="sxs-lookup"><span data-stu-id="69d20-110">Gets the transport security setting for the <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span></span></summary>
        <value><span data-ttu-id="69d20-111">Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement" /> , der die RelayBindung enthält.</span><span class="sxs-lookup"><span data-stu-id="69d20-111">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement" /> that contains the relay binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>