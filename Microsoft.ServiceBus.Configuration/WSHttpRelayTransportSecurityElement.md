<Type Name="WSHttpRelayTransportSecurityElement" FullName="Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement">
  <TypeSignature Language="C#" Value="public sealed class WSHttpRelayTransportSecurityElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit WSHttpRelayTransportSecurityElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class WSHttpRelayTransportSecurityElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type WSHttpRelayTransportSecurityElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Ein Konfigurationselement, das die Sicherheit auf eine HTTP-Übertragung über das Azure Service Bus-Relay beschreibt.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WSHttpRelayTransportSecurityElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement.#ctor" />
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
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement.Properties" />
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
    <Member MemberName="ProxyCredentialType">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HttpProxyCredentialType ProxyCredentialType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HttpProxyCredentialType ProxyCredentialType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement.ProxyCredentialType" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyCredentialType As HttpProxyCredentialType" />
      <MemberSignature Language="F#" Value="member this.ProxyCredentialType : System.ServiceModel.HttpProxyCredentialType with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement.ProxyCredentialType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("proxyCredentialType", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HttpProxyCredentialType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Typ der Anmeldeinformationen an, die vom Dienst oder Client-Endpunkt für die Authentifizierung gegenüber dem Proxy verwendet werden.</summary>
        <value>Der Typ der Clientanmeldeinformationen an, von der Dienst- oder Client-Endpunkt für die Authentifizierung gegenüber dem Proxy verwendet werden.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>