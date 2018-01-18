<Type Name="BasicHttpRelaySecurityElement" FullName="Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement">
  <TypeSignature Language="C#" Value="public sealed class BasicHttpRelaySecurityElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BasicHttpRelaySecurityElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BasicHttpRelaySecurityElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type BasicHttpRelaySecurityElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="e7db8-101">Stellt ein Konfigurationselement, das die Sicherheit für einen grundlegenden HTTP-RelayBindung konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="e7db8-101">Represents a configuration element that configures the security for a basic HTTP relay binding.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BasicHttpRelaySecurityElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.#ctor" />
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
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.BasicHttpRelayMessageSecurityElement Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.BasicHttpRelayMessageSecurityElement Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As BasicHttpRelayMessageSecurityElement" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.Configuration.BasicHttpRelayMessageSecurityElement" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.Message" />
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
        <ReturnType>Microsoft.ServiceBus.Configuration.BasicHttpRelayMessageSecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e7db8-102">Ruft ein Konfigurationselement, der angibt, die Einstellungen für Sicherheit auf Nachrichtenebene für einen <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />.</span><span class="sxs-lookup"><span data-stu-id="e7db8-102">Gets a Configuration element that specifies the message-level security settings for a <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />.</span></span></summary>
        <value><span data-ttu-id="e7db8-103">Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.BasicHttpRelayMessageSecurityElement" /> , das die Sicherheitseinstellungen enthält.</span><span class="sxs-lookup"><span data-stu-id="e7db8-103">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.BasicHttpRelayMessageSecurityElement" /> that contains the security settings.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndBasicHttpSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.Mode" />
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
        <ReturnType>Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e7db8-104">Ruft ab oder legt den Sicherheitsmodus für eine <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />.</span><span class="sxs-lookup"><span data-stu-id="e7db8-104">Gets or sets the security mode for a <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />.</span></span></summary>
        <value><span data-ttu-id="e7db8-105">Gibt einen Wert aus der <see cref="T:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode" /> Enumeration.</span><span class="sxs-lookup"><span data-stu-id="e7db8-105">Returns a value from the <see cref="T:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode" /> enumeration.</span></span> <span data-ttu-id="e7db8-106">Der Standardwert ist none.</span><span class="sxs-lookup"><span data-stu-id="e7db8-106">The default value is none.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.Properties" />
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
            <span data-ttu-id="e7db8-107">Ruft die Auflistung von Eigenschaften ab.</span><span class="sxs-lookup"><span data-stu-id="e7db8-107">Gets the collection of properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.RelayClientAuthenticationType" />
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
        <summary><span data-ttu-id="e7db8-108">Ruft ab oder legt den Authentifizierungstyp, der in diesem Konfigurationselement angegeben.</span><span class="sxs-lookup"><span data-stu-id="e7db8-108">Gets or sets the authentication type specified in this configuration element.</span></span></summary>
        <value><span data-ttu-id="e7db8-109">Gibt einen Wert aus <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> , enthält den Typ der Authentifizierung verwendet werden, von den Bindungselementen, die auf die aktuelle Instanz angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="e7db8-109">Returns a value from <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> that contains the type of authentication to be used by binding elements the current instance is applied to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As HttpRelayTransportSecurityElement" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.Transport" />
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
        <ReturnType>Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e7db8-110">Ruft ein Konfigurationselement, der angibt, die Einstellungen für Sicherheit auf Transportebene für eine <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> Bindung.</span><span class="sxs-lookup"><span data-stu-id="e7db8-110">Gets a configuration element that specifies the transport-level security settings for a <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> binding.</span></span></summary>
        <value><span data-ttu-id="e7db8-111">Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement" /> , enthält Eigenschaften, die Authentifizierungsparameter für den HTTP-Transport steuern.</span><span class="sxs-lookup"><span data-stu-id="e7db8-111">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement" /> that contains properties that control authentication parameters for the HTTP transport.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>