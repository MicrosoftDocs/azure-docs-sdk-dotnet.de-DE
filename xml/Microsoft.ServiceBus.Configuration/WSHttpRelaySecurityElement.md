<Type Name="WSHttpRelaySecurityElement" FullName="Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement">
  <TypeSignature Language="C#" Value="public sealed class WSHttpRelaySecurityElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit WSHttpRelaySecurityElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class WSHttpRelaySecurityElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type WSHttpRelaySecurityElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="08c07-101">Stellt ein Konfigurationselement, das die Sicherheit für einen WS-HTTP-Dienst über die Azure Service Bus-Relay konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="08c07-101">Represents a configuration element that configures the security for a WS-HTTP service through the Azure Service Bus relay.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WSHttpRelaySecurityElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.#ctor" />
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
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As NonDualMessageSecurityOverRelayHttpElement" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.Message" />
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
        <ReturnType>Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="08c07-102">Ruft die Sicherheitseinstellungen für die Meldung ab.</span><span class="sxs-lookup"><span data-stu-id="08c07-102">Gets the security settings for the message.</span></span></summary>
        <value><span data-ttu-id="08c07-103">Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement" /> , die Sicherheitseinstellungen für die Nachricht angibt.</span><span class="sxs-lookup"><span data-stu-id="08c07-103">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement" /> that specifies the security settings for the message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndSecurityMode with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.Mode" />
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
        <summary><span data-ttu-id="08c07-104">Ruft ab oder legt den Sicherheitsmodus, der von einem zum Empfangen von HTTP-Anforderungen konfigurierten Endpunkt verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="08c07-104">Gets or sets the mode of security that is used by an endpoint configured to receive HTTP requests.</span></span></summary>
        <value><span data-ttu-id="08c07-105">Gibt eine <see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" /> , angibt, der den Sicherheitstyp, der angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="08c07-105">Returns a <see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" /> that specifies the type of security that is applied.</span></span> <span data-ttu-id="08c07-106">Der Standardwert ist Nachricht.</span><span class="sxs-lookup"><span data-stu-id="08c07-106">The default value is Message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.RelayClientAuthenticationType" />
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
        <summary><span data-ttu-id="08c07-107">Abrufen oder Festlegen der relayclient-Authentifizierungstyp verwendet, die für den Dienstclient.</span><span class="sxs-lookup"><span data-stu-id="08c07-107">Gets or sets the relay client authentication type used by the service client.</span></span></summary>
        <value><span data-ttu-id="08c07-108">Gibt eine <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> , der Authentifizierungstyp enthält.</span><span class="sxs-lookup"><span data-stu-id="08c07-108">Returns a <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> that contains the authentication type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As WSHttpRelayTransportSecurityElement" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.Transport" />
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
        <ReturnType>Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="08c07-109">Ruft die Sicherheitseinstellungen für den Transport ab.</span><span class="sxs-lookup"><span data-stu-id="08c07-109">Gets the security settings for the transport.</span></span></summary>
        <value><span data-ttu-id="08c07-110">Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement" /> , die Sicherheitseinstellungen für den Transport angibt. Verwenden der <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement" /> von dieser Eigenschaft, um die transportsicherheitsparameter für festzulegen zurückgegebene Objekt der <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />.</span><span class="sxs-lookup"><span data-stu-id="08c07-110">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement" /> that specifies the security settings for the transport.Use the <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement" /> object returned by this property to set the transport security parameters for the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />.</span></span> <span data-ttu-id="08c07-111">Wenn der TransportCredentialOnly-Wert, wird angegeben wird <see cref="M:Microsoft.ServiceBus.WSHttpRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType,System.Boolean)" />, und klicken Sie dann die von der Transport-Eigenschaft angegebenen Einstellungen für den Dienstendpunkt wirksam werden.</span><span class="sxs-lookup"><span data-stu-id="08c07-111">If the TransportCredentialOnly value is specified by <see cref="M:Microsoft.ServiceBus.WSHttpRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType,System.Boolean)" />, then the settings provided by the Transport property become effective for the service endpoint.</span></span> <span data-ttu-id="08c07-112">Der Wert dieser Eigenschaft kann nur im Konstruktor festgelegt ihn als expliziten Parameter und der Wert kann nicht erneut festgelegt werden, nachdem die Bindungsinstanz erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="08c07-112">The value of this property can set only in the constructor it as an explicit parameter and its value cannot be set again after the binding instance is created.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>