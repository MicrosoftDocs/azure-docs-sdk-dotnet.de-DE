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
    <summary>Stellt ein Konfigurationselement, das die Sicherheit für einen grundlegenden HTTP-RelayBindung konfiguriert.</summary>
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
        <summary>Ruft ein Konfigurationselement, der angibt, die Einstellungen für Sicherheit auf Nachrichtenebene für einen <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.BasicHttpRelayMessageSecurityElement" /> , das die Sicherheitseinstellungen enthält.</value>
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
        <summary>Ruft ab oder legt den Sicherheitsmodus für eine <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />.</summary>
        <value>Gibt einen Wert aus der <see cref="T:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode" /> Enumeration. Der Standardwert ist none.</value>
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
            Ruft die Auflistung von Eigenschaften ab.
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
        <summary>Ruft ab oder legt den Authentifizierungstyp, der in diesem Konfigurationselement angegeben.</summary>
        <value>Gibt einen Wert aus <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> , enthält den Typ der Authentifizierung verwendet werden, von den Bindungselementen, die auf die aktuelle Instanz angewendet wird.</value>
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
        <summary>Ruft ein Konfigurationselement, der angibt, die Einstellungen für Sicherheit auf Transportebene für eine <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> Bindung.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement" /> , enthält Eigenschaften, die Authentifizierungsparameter für den HTTP-Transport steuern.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>