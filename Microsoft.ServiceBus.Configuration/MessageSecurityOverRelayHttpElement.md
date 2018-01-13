<Type Name="MessageSecurityOverRelayHttpElement" FullName="Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement">
  <TypeSignature Language="C#" Value="public class MessageSecurityOverRelayHttpElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MessageSecurityOverRelayHttpElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement" />
  <TypeSignature Language="VB.NET" Value="Public Class MessageSecurityOverRelayHttpElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type MessageSecurityOverRelayHttpElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Ein Konfigurationselement, die die nachrichtensicherheit über das Azure Service Bus-Relay, die über einen HTTP-Transport-Mechanismus beschreibt.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AlgorithmSuite">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement.AlgorithmSuite" />
      <MemberSignature Language="VB.NET" Value="Public Property AlgorithmSuite As SecurityAlgorithmSuite" />
      <MemberSignature Language="F#" Value="member this.AlgorithmSuite : System.ServiceModel.Security.SecurityAlgorithmSuite with get, set" Usage="Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement.AlgorithmSuite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.TypeConverter(typeof(Microsoft.ServiceBus.Configuration.SecurityAlgorithmSuiteConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("algorithmSuite", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Security.SecurityAlgorithmSuite</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt fest, aus der Konfigurationsdatei der nachrichtenverschlüsselung und Key Wrap-Algorithmen verwendet, um eine HTTP-Nachricht zu sichern.</summary>
        <value>Die Nachricht nachrichtenverschlüsselungs- und Key Wrap-Algorithmen verwendet, um eine HTTP-Nachricht zu sichern.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCredentialType">
      <MemberSignature Language="C#" Value="public System.ServiceModel.MessageCredentialType ClientCredentialType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.MessageCredentialType ClientCredentialType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement.ClientCredentialType" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCredentialType As MessageCredentialType" />
      <MemberSignature Language="F#" Value="member this.ClientCredentialType : System.ServiceModel.MessageCredentialType with get, set" Usage="Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement.ClientCredentialType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("clientCredentialType", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.MessageCredentialType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab, oder legt ihn fest, aus der Konfigurationsdatei den Typ der Anmeldeinformationen beim Durchführen der Clientauthentifizierung mit nachrichtenbasierte Sicherheit oder TransportWithMessageCredential verwendet werden soll.</summary>
        <value>Gibt eine <see cref="T:System.ServiceModel.MessageCredentialType" /> , die den Anmeldeinformationstyp für Nachrichten enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NegotiateServiceCredential">
      <MemberSignature Language="C#" Value="public bool NegotiateServiceCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool NegotiateServiceCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement.NegotiateServiceCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property NegotiateServiceCredential As Boolean" />
      <MemberSignature Language="F#" Value="member this.NegotiateServiceCredential : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement.NegotiateServiceCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("negotiateServiceCredential", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab, oder legt ihn fest, aus der Konfigurationsdatei einen booleschen Wert, der angibt, ob die Dienstanmeldeinformationen auf dem Client Out-of-Band bereitgestellt oder vom Dienst an den Client über einen Aushandlungsvorgang abgerufen wird.</summary>
        <value>"true", wenn die Dienstanmeldeinformationen auf dem Client Out-of-Band bereitgestellt oder vom Dienst an den Client über einen Aushandlungsvorgang abgerufen wird; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>