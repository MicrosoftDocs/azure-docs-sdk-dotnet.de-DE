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
    <summary><span data-ttu-id="0e474-101">Gibt die Sicherheitstypen auf Transportebene und auf Nachrichtenebene an, die von einem mit einer <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> konfigurierten Endpunkt verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="0e474-101">Specifies the types of transport-level and message-level security used by an endpoint configured with a <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span></span></summary>
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
        <summary><span data-ttu-id="0e474-102">Ruft den Typ der Sicherheitsanforderungen auf Nachrichtenebene für einen mit einer <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> konfigurierten Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="0e474-102">Gets the type of message-level security requirements for a service configured with a <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span></span> </summary>
        <value><span data-ttu-id="0e474-103">Gibt eine <see cref="T:Microsoft.ServiceBus.MessageSecurityOverRelayConnection" /> , der den Typ der sicherheitsanforderungen auf Nachrichtenebene für einen Endpunkt angibt.</span><span class="sxs-lookup"><span data-stu-id="0e474-103">Returns a <see cref="T:Microsoft.ServiceBus.MessageSecurityOverRelayConnection" /> that indicates the type of message-level security requirements for an endpoint.</span></span> <span data-ttu-id="0e474-104">Die standardsicherheitseinstellungen sind: eine ClientCredentialType UserName; und ein AlgorithmSuite von Basic256.</span><span class="sxs-lookup"><span data-stu-id="0e474-104">The default security settings are: a ClientCredentialType of UserName; and an AlgorithmSuite of Basic256.</span></span></value>
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
        <summary><span data-ttu-id="0e474-105">Ruft ab oder legt fest, ob Sicherheit auf Nachrichtenebene und auf Transportebene von einem mit einem <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> konfigurierten Endpunkt verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="0e474-105">Gets or sets whether message-level and transport-level security are used by an endpoint configured with a <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span></span></summary>
        <value><span data-ttu-id="0e474-106">Gibt eine <see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" /> , der angibt, ob Sicherheit auf Nachrichtenebene oder auf Transportebene von einem Endpunkt verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="0e474-106">Returns an <see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" /> that indicates whether message-level or transport-level security is used by an endpoint.</span></span> <span data-ttu-id="0e474-107">Der Standardwert ist Transport.</span><span class="sxs-lookup"><span data-stu-id="0e474-107">The default value is Transport.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="0e474-108">Der Wert ist kein gültiger <see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" /> Feld.</span><span class="sxs-lookup"><span data-stu-id="0e474-108">The value is not a valid <see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" /> field.</span></span></exception>
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
        <summary><span data-ttu-id="0e474-109">Ruft ab oder legt sie fest der Relay-Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="0e474-109">Gets or sets the relay client authentication type.</span></span></summary>
        <value><span data-ttu-id="0e474-110">Gibt eine <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> , enthält die relayclient-Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="0e474-110">Returns a <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> that contains the relay client authentication type.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="0e474-111">Der Wert ist kein gültiger <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> Feld.</span><span class="sxs-lookup"><span data-stu-id="0e474-111">The value is not a valid <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> field.</span></span></exception>
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
        <summary><span data-ttu-id="0e474-112">Ruft den Typ der Sicherheitsanforderungen auf Nachrichtenebene für einen mit einer <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> konfigurierten Endpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="0e474-112">Gets the type of message-level security requirements for an endpoint configured with a <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span></span></summary>
        <value><span data-ttu-id="0e474-113">Gibt eine <see cref="T:Microsoft.ServiceBus.TcpRelayTransportSecurity" /> , der den Typ der Sicherheit auf Transportebene Anforderungen für einen Endpunkt angibt.</span><span class="sxs-lookup"><span data-stu-id="0e474-113">Returns a <see cref="T:Microsoft.ServiceBus.TcpRelayTransportSecurity" /> that indicates the type of transport-level security requirements for an endpoint.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>