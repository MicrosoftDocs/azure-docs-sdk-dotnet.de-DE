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
    <summary><span data-ttu-id="5eaae-101">Gibt die verfügbaren Sicherheitstypen für einen Dienstendpunkt an, der für den Empfang von HTTP-Anforderungen konfiguriert wurde.</span><span class="sxs-lookup"><span data-stu-id="5eaae-101">Specifies the types of security available to a service endpoint configured to receive HTTP requests.</span></span> </summary>
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
        <summary><span data-ttu-id="5eaae-102">Ruft den Sicherheitsmodus ab, der von einem Endpunkt verwendet wird, der für den Empfang von HTTP-Anforderungen mit <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" /> konfiguriert ist, oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="5eaae-102">Gets or sets the mode of security that is used by an endpoint configured to receive HTTP requests with a <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" />.</span></span></summary>
        <value><span data-ttu-id="5eaae-103">Gibt eine <see cref="T:Microsoft.ServiceBus.EndToEndWebHttpSecurityMode" /> , der angibt, ob Sicherheit auf Transportebene, nur die Anmeldeinformationen oder keine Sicherheit von einem Endpunkt verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="5eaae-103">Returns a <see cref="T:Microsoft.ServiceBus.EndToEndWebHttpSecurityMode" /> that indicates whether transport-level security, credential only, or no security is used by an endpoint.</span></span> <span data-ttu-id="5eaae-104">Der Standardwert ist None.</span><span class="sxs-lookup"><span data-stu-id="5eaae-104">The default value is None.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="5eaae-105">Der Wert ist eine gültige EndToEndWebHttpSecurityMode.</span><span class="sxs-lookup"><span data-stu-id="5eaae-105">The value is not a valid EndToEndWebHttpSecurityMode.</span></span></exception>
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
        <summary><span data-ttu-id="5eaae-106">Abrufen oder Festlegen der relayclient-Authentifizierungstyp verwendet, die für den Dienstclient.</span><span class="sxs-lookup"><span data-stu-id="5eaae-106">Gets or sets the relay client authentication type used by the service client.</span></span></summary>
        <value><span data-ttu-id="5eaae-107">Gibt eine <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> , enthält die relayclient-Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="5eaae-107">Returns a <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> that contains the relay client authentication type.</span></span> <span data-ttu-id="5eaae-108">Der Standardwert ist RelayClientAuthenticationType.RelayAccessToken.</span><span class="sxs-lookup"><span data-stu-id="5eaae-108">The default value is RelayClientAuthenticationType.RelayAccessToken.</span></span> </value>
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
        <summary><span data-ttu-id="5eaae-109">Ruft ab oder legt die Sicherheitseinstellungen auf Transportebene für eine Bindung.</span><span class="sxs-lookup"><span data-stu-id="5eaae-109">Gets or sets the Transport-level security settings for a binding.</span></span></summary>
        <value><span data-ttu-id="5eaae-110">Gibt eine <see cref="T:Microsoft.ServiceBus.HttpRelayTransportSecurity" /> , das die Bindung enthält.</span><span class="sxs-lookup"><span data-stu-id="5eaae-110">Returns a <see cref="T:Microsoft.ServiceBus.HttpRelayTransportSecurity" /> that contains the binding.</span></span> <span data-ttu-id="5eaae-111">Festgelegten Standardwerte sind eine ClientCredentialType von None, eine ProxyCredentialType ' None ', und Bereich = "".</span><span class="sxs-lookup"><span data-stu-id="5eaae-111">The default values set are a ClientCredentialType of None, a ProxyCredentialType of None, and Realm = "".</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>