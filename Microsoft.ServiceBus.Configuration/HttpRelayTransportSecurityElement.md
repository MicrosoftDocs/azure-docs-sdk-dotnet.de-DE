<Type Name="HttpRelayTransportSecurityElement" FullName="Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement">
  <TypeSignature Language="C#" Value="public sealed class HttpRelayTransportSecurityElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HttpRelayTransportSecurityElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HttpRelayTransportSecurityElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type HttpRelayTransportSecurityElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt ein Konfigurationselement dar, mit dem Authentifizierungsparameter für den HTTP-Transport kontrolliert werden. Diese Klasse kann nicht vererbt werden.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpRelayTransportSecurityElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement.#ctor" />
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
    <Member MemberName="ProxyCredentialType">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HttpProxyCredentialType ProxyCredentialType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HttpProxyCredentialType ProxyCredentialType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement.ProxyCredentialType" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyCredentialType As HttpProxyCredentialType" />
      <MemberSignature Language="F#" Value="member this.ProxyCredentialType : System.ServiceModel.HttpProxyCredentialType with get, set" Usage="Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement.ProxyCredentialType" />
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
        <summary>Ruft ab, oder legt ihn fest, aus der Konfigurationsdatei den Typ der Clientanmeldeinformationen für die Authentifizierung gegenüber dem Proxy verwendet werden soll.</summary>
        <value>Gibt eine <see cref="T:System.ServiceModel.HttpProxyCredentialType" /> , die den Proxytyp enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>