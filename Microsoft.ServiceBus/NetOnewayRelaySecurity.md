<Type Name="NetOnewayRelaySecurity" FullName="Microsoft.ServiceBus.NetOnewayRelaySecurity">
  <TypeSignature Language="C#" Value="public sealed class NetOnewayRelaySecurity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetOnewayRelaySecurity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NetOnewayRelaySecurity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetOnewayRelaySecurity" />
  <TypeSignature Language="F#" Value="type NetOnewayRelaySecurity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Die Auflistung der Sicherheitseinstellungen für eine <see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" /> Bindung.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.MessageSecurityOverRelayOneway Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.MessageSecurityOverRelayOneway Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelaySecurity.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As MessageSecurityOverRelayOneway" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.MessageSecurityOverRelayOneway" Usage="Microsoft.ServiceBus.NetOnewayRelaySecurity.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.MessageSecurityOverRelayOneway</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Typ der Sicherheitsanforderungen auf Nachrichtenebene für einen mit einer <see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" /> konfigurierten Dienst ab.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.MessageSecurityOverRelayOneway" /> , der den Typ der sicherheitsanforderungen auf Nachrichtenebene für einen Endpunkt angibt. Die Standardeinstellung AlgorithmSuite ist Basic256, und die ClientCredentialType-Standardeinstellung ist "Windows".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelaySecurity.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndSecurityMode with get, set" Usage="Microsoft.ServiceBus.NetOnewayRelaySecurity.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndSecurityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt fest, ob Sicherheit auf Nachrichtenebene und auf Transportebene von einem mit einem <see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" /> konfigurierten Endpunkt verwendet werden.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" /> , der angibt, ob Sicherheit auf Nachrichtenebene oder auf Transportebene von einem Endpunkt verwendet werden. Der Standardwert ist Transport.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der Modus Sicherheitswert ist ungültig.</exception>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelaySecurity.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.NetOnewayRelaySecurity.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Authentifizierungstyp für das Relay-Client.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> , der Authentifizierungstyp enthält. Standardwert: <see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" />.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der Wert ist kein gültiger <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> Feld.</exception>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayedOnewayTransportSecurity Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.RelayedOnewayTransportSecurity Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelaySecurity.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As RelayedOnewayTransportSecurity" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.RelayedOnewayTransportSecurity" Usage="Microsoft.ServiceBus.NetOnewayRelaySecurity.Transport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayedOnewayTransportSecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Typ der Sicherheit auf Transportebene Anforderungen für einen Endpunkt konfiguriert, die mit einem <see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" />. Der Standardwert ist EncryptAndSign.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportSecurity" /> , der den Typ der Sicherheit auf Transportebene Anforderungen für einen Endpunkt angibt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>