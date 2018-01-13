<Type Name="MessageSecurityOverRelayHttp" FullName="Microsoft.ServiceBus.MessageSecurityOverRelayHttp">
  <TypeSignature Language="C#" Value="public class MessageSecurityOverRelayHttp" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MessageSecurityOverRelayHttp extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.MessageSecurityOverRelayHttp" />
  <TypeSignature Language="VB.NET" Value="Public Class MessageSecurityOverRelayHttp" />
  <TypeSignature Language="F#" Value="type MessageSecurityOverRelayHttp = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Ermöglicht das Festlegen von Sicherheitseigenschaften auf Nachrichtenebene für die <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />-Bindung.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AlgorithmSuite">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.MessageSecurityOverRelayHttp.AlgorithmSuite" />
      <MemberSignature Language="VB.NET" Value="Public Property AlgorithmSuite As SecurityAlgorithmSuite" />
      <MemberSignature Language="F#" Value="member this.AlgorithmSuite : System.ServiceModel.Security.SecurityAlgorithmSuite with get, set" Usage="Microsoft.ServiceBus.MessageSecurityOverRelayHttp.AlgorithmSuite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Security.SecurityAlgorithmSuite</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Gibt die Algorithmussammlung für Sicherheitsmeldungen auf SOAP-Ebene an. </summary>
        <value>Gibt <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" />zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCredentialType">
      <MemberSignature Language="C#" Value="public System.ServiceModel.MessageCredentialType ClientCredentialType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.MessageCredentialType ClientCredentialType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.MessageSecurityOverRelayHttp.ClientCredentialType" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCredentialType As MessageCredentialType" />
      <MemberSignature Language="F#" Value="member this.ClientCredentialType : System.ServiceModel.MessageCredentialType with get, set" Usage="Microsoft.ServiceBus.MessageSecurityOverRelayHttp.ClientCredentialType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.MessageCredentialType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Gibt den Typ der Clientanmeldeinformationen zur Clientauthentifizierung verwendet.</summary>
        <value>Gibt eine <see cref="T:System.ServiceModel.MessageCredentialType" /> , welches algorithmuspaket enthält. Der Standardwert ist Basic256.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSecureConversationEnabled">
      <MemberSignature Language="C#" Value="protected virtual bool IsSecureConversationEnabled ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool IsSecureConversationEnabled() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.MessageSecurityOverRelayHttp.IsSecureConversationEnabled" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function IsSecureConversationEnabled () As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsSecureConversationEnabled : unit -&gt; bool&#xA;override this.IsSecureConversationEnabled : unit -&gt; bool" Usage="messageSecurityOverRelayHttp.IsSecureConversationEnabled " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Nur in Erweiterbarkeitsszenarien verwendet, um anzugeben, ob eine Instanz einer Klasse abgeleitet <see cref="T:Microsoft.ServiceBus.MessageSecurityOverRelayHttp" /> ist konfiguriert, um die sichere Konversation auszuführen.</summary>
        <returns>Gibt immer "true" zurück, es sei denn, die in einer abgeleiteten Klasse außer Kraft gesetzt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NegotiateServiceCredential">
      <MemberSignature Language="C#" Value="public bool NegotiateServiceCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool NegotiateServiceCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.MessageSecurityOverRelayHttp.NegotiateServiceCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property NegotiateServiceCredential As Boolean" />
      <MemberSignature Language="F#" Value="member this.NegotiateServiceCredential : bool with get, set" Usage="Microsoft.ServiceBus.MessageSecurityOverRelayHttp.NegotiateServiceCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Dienstanmeldeinformationen auf dem Client außerhalb des Bereichs bereitgestellt oder vom Dienst über einen Aushandlungsvorgang abgerufen werden.</summary>
        <value>Gibt "true" zurück, wenn die Dienstanmeldeinformationen über einen Aushandlungsvorgang abgerufen wird; andernfalls "false". Der Standardwert ist „true“.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>