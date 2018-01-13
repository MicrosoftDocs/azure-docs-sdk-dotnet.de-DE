<Type Name="WebHttpRelaySecurity" FullName="Microsoft.ServiceBus.WebHttpRelaySecurity">
  <TypeSignature Language="C#" Value="public sealed class WebHttpRelaySecurity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit WebHttpRelaySecurity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.WebHttpRelaySecurity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class WebHttpRelaySecurity" />
  <TypeSignature Language="F#" Value="type WebHttpRelaySecurity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Gibt die verfügbaren Sicherheitstypen für einen Dienstendpunkt an, der für den Empfang von HTTP-Anforderungen konfiguriert wurde. </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndWebHttpSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndWebHttpSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelaySecurity.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndWebHttpSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndWebHttpSecurityMode with get, set" Usage="Microsoft.ServiceBus.WebHttpRelaySecurity.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndWebHttpSecurityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Sicherheitsmodus ab, der von einem Endpunkt verwendet wird, der für den Empfang von HTTP-Anforderungen mit <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" /> konfiguriert ist, oder legt ihn fest.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.EndToEndWebHttpSecurityMode" /> , der angibt, ob Sicherheit auf Transportebene, nur die Anmeldeinformationen oder keine Sicherheit von einem Endpunkt verwendet wird. Der Standardwert ist None.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der Wert ist eine gültige EndToEndWebHttpSecurityMode.</exception>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelaySecurity.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.WebHttpRelaySecurity.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Abrufen oder Festlegen der relayclient-Authentifizierungstyp verwendet, die für den Dienstclient.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> , enthält die relayclient-Authentifizierungstyp. Der Standardwert ist RelayClientAuthenticationType.RelayAccessToken. </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.HttpRelayTransportSecurity Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.HttpRelayTransportSecurity Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelaySecurity.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As HttpRelayTransportSecurity" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.HttpRelayTransportSecurity" Usage="Microsoft.ServiceBus.WebHttpRelaySecurity.Transport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.HttpRelayTransportSecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Sicherheitseinstellungen auf Transportebene für eine Bindung.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.HttpRelayTransportSecurity" /> , das die Bindung enthält. Festgelegten Standardwerte sind eine ClientCredentialType von None, eine ProxyCredentialType ' None ', und Bereich = "".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>