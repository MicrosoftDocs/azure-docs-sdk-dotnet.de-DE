<Type Name="WSHttpRelaySecurity" FullName="Microsoft.ServiceBus.WSHttpRelaySecurity">
  <TypeSignature Language="C#" Value="public sealed class WSHttpRelaySecurity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit WSHttpRelaySecurity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.WSHttpRelaySecurity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class WSHttpRelaySecurity" />
  <TypeSignature Language="F#" Value="type WSHttpRelaySecurity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt die Sicherheitseinstellungen für die <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.NonDualMessageSecurityOverRelayHttp Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.NonDualMessageSecurityOverRelayHttp Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelaySecurity.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As NonDualMessageSecurityOverRelayHttp" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.NonDualMessageSecurityOverRelayHttp" Usage="Microsoft.ServiceBus.WSHttpRelaySecurity.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NonDualMessageSecurityOverRelayHttp</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Sicherheit auf Nachrichtenebene-Einstellungen für diese Azure Service Bus-Bindung ab.</summary>
        <value>Gibt <see cref="T:Microsoft.ServiceBus.NonDualMessageSecurityOverRelayHttp" />. Enthält die Sicherheitseinstellungen an. Der Standardwert umfasst: EstablishSecurityContext Standardsatz auf "true", ist "Windows" ClientCredentialType AlgorithmSuite ist Basic256 und NegotiateServiceCredential ist "true".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelaySecurity.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndSecurityMode with get, set" Usage="Microsoft.ServiceBus.WSHttpRelaySecurity.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndSecurityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Gibt den nachrichtensicherheitsmodus für diese Azure Service Bus-Bindung an. </summary>
        <value>Gibt <see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" />. Enthält den Sicherheitsmodus für diese Azure Service Bus-Bindung an. Der Standardwert ist Transport.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelaySecurity.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.WSHttpRelaySecurity.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ermittelt oder definiert den Authentifizierungstyp, der für die dienstanwendung oder Client-Anwendung, geben Sie an den Azure-Servicebus erforderlich sind.</summary>
        <value>Der Authentifizierungstyp, der für die dienstanwendung oder Client-Anwendung, geben Sie an den Azure-Servicebus erforderlich sind. Der Standardwert lautet <see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.HttpRelayTransportSecurity Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.HttpRelayTransportSecurity Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelaySecurity.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As HttpRelayTransportSecurity" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.HttpRelayTransportSecurity" Usage="Microsoft.ServiceBus.WSHttpRelaySecurity.Transport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.HttpRelayTransportSecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ein Objekt, das die Sicherheit auf Transportebene-Einstellungen für dieses Azure Service Bus-Bindung enthält. </summary>
        <value>Gibt <see cref="T:Microsoft.ServiceBus.HttpRelayTransportSecurity" />. Enthält die transportsicherheit für dieses Element an. Der Standardwert umfasst ClientCredentialType der None- und eine ProxyCredentialType ' None '.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>