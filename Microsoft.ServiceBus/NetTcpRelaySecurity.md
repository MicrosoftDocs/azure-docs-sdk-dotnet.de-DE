<Type Name="NetTcpRelaySecurity" FullName="Microsoft.ServiceBus.NetTcpRelaySecurity">
  <TypeSignature Language="C#" Value="public sealed class NetTcpRelaySecurity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetTcpRelaySecurity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NetTcpRelaySecurity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetTcpRelaySecurity" />
  <TypeSignature Language="F#" Value="type NetTcpRelaySecurity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Gibt die Sicherheitstypen auf Transportebene und auf Nachrichtenebene an, die von einem mit einer <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> konfigurierten Endpunkt verwendet werden.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.MessageSecurityOverRelayConnection Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.MessageSecurityOverRelayConnection Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelaySecurity.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As MessageSecurityOverRelayConnection" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.MessageSecurityOverRelayConnection" Usage="Microsoft.ServiceBus.NetTcpRelaySecurity.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.MessageSecurityOverRelayConnection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Typ der Sicherheitsanforderungen auf Nachrichtenebene für einen mit einer <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> konfigurierten Dienst ab. </summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.MessageSecurityOverRelayConnection" /> , der den Typ der sicherheitsanforderungen auf Nachrichtenebene für einen Endpunkt angibt. Die standardsicherheitseinstellungen sind: eine ClientCredentialType UserName; und ein AlgorithmSuite von Basic256.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelaySecurity.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndSecurityMode with get, set" Usage="Microsoft.ServiceBus.NetTcpRelaySecurity.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndSecurityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt fest, ob Sicherheit auf Nachrichtenebene und auf Transportebene von einem mit einem <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> konfigurierten Endpunkt verwendet werden.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" /> , der angibt, ob Sicherheit auf Nachrichtenebene oder auf Transportebene von einem Endpunkt verwendet wird. Der Standardwert ist Transport.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der Wert ist kein gültiger <see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" /> Feld.</exception>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelaySecurity.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.NetTcpRelaySecurity.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt sie fest der Relay-Authentifizierungstyp.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> , enthält die relayclient-Authentifizierungstyp.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der Wert ist kein gültiger <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> Feld.</exception>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TcpRelayTransportSecurity Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.TcpRelayTransportSecurity Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelaySecurity.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As TcpRelayTransportSecurity" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.TcpRelayTransportSecurity" Usage="Microsoft.ServiceBus.NetTcpRelaySecurity.Transport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayTransportSecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Typ der Sicherheitsanforderungen auf Nachrichtenebene für einen mit einer <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> konfigurierten Endpunkt ab.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.TcpRelayTransportSecurity" /> , der den Typ der Sicherheit auf Transportebene Anforderungen für einen Endpunkt angibt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>