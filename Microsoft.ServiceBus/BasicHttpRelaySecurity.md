<Type Name="BasicHttpRelaySecurity" FullName="Microsoft.ServiceBus.BasicHttpRelaySecurity">
  <TypeSignature Language="C#" Value="public sealed class BasicHttpRelaySecurity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BasicHttpRelaySecurity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.BasicHttpRelaySecurity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BasicHttpRelaySecurity" />
  <TypeSignature Language="F#" Value="type BasicHttpRelaySecurity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt Eigenschaften zum Konfigurieren der Sicherheitseinstellungen von einem <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> Bindung.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.BasicHttpRelayMessageSecurity Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.BasicHttpRelayMessageSecurity Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelaySecurity.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As BasicHttpRelayMessageSecurity" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.BasicHttpRelayMessageSecurity" Usage="Microsoft.ServiceBus.BasicHttpRelaySecurity.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.BasicHttpRelayMessageSecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Sicherheitseinstellungen auf Nachrichtenebene für eine <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />-Bindung ab.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.BasicHttpRelayMessageSecurity" />, die die Sicherheit auf Nachrichtenebene-Einstellungen für diese Bindung darstellt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelaySecurity.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndBasicHttpSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelaySecurity.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Sicherheitsmodus für eine <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />-Bindung ab oder legt ihn fest.</summary>
        <value>Einer der Werte von <see cref="T:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode" /> Enumeration. Der Standardwert ist None.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der Wert ist kein gültiger Wert für <see cref="T:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode" />.</exception>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelaySecurity.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelaySecurity.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Typ der Authentifizierung vom Azure Service Bus-Dienst verwendet.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> , die den Typ der Authentifizierung vom Dienst verwendete enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.HttpRelayTransportSecurity Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.HttpRelayTransportSecurity Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelaySecurity.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As HttpRelayTransportSecurity" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.HttpRelayTransportSecurity" Usage="Microsoft.ServiceBus.BasicHttpRelaySecurity.Transport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.HttpRelayTransportSecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Sicherheitseinstellungen auf Transportebene für eine <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />-Bindung ab.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.HttpRelayTransportSecurity" /> , das die Sicherheitseinstellungen enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>