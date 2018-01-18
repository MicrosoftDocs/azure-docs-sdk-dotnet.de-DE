<Type Name="EndToEndBasicHttpSecurityMode" FullName="Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode">
  <TypeSignature Language="C#" Value="public enum EndToEndBasicHttpSecurityMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed EndToEndBasicHttpSecurityMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum EndToEndBasicHttpSecurityMode" />
  <TypeSignature Language="F#" Value="type EndToEndBasicHttpSecurityMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary><span data-ttu-id="62bdf-101">Ein Enumerationstyp, der angibt, die Sicherheitsmodi, die mit verwendet werden können <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />.</span><span class="sxs-lookup"><span data-stu-id="62bdf-101">An enumeration type that specifies the modes of security that can be used with <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="Message" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode Message = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode.Message" />
      <MemberSignature Language="VB.NET" Value="Message" />
      <MemberSignature Language="F#" Value="Message = 2" Usage="Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode.Message" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary><span data-ttu-id="62bdf-102">Sicherheit wird über WS-Security-SOAP-nachrichtensicherheit bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="62bdf-102">Security is provided using WS-Security SOAP message security.</span></span> <span data-ttu-id="62bdf-103">Für die <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> erfordert das System, dass das Serverzertifikat dem Client separat zur Verfügung gestellt wird.</span><span class="sxs-lookup"><span data-stu-id="62bdf-103">For the <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />, the system requires that the server certificate be provided to the client separately.</span></span> <span data-ttu-id="62bdf-104">Die gültigen Typen von Clientanmeldeinformationen für diese Bindung sind Benutzername und das Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="62bdf-104">The valid client credential types for this binding are UserName and Certificate.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="62bdf-105">Nachrichten werden nicht während der Übertragung gesichert.</span><span class="sxs-lookup"><span data-stu-id="62bdf-105">Messages are not secured during transfer.</span></span> </summary>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="Transport" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode Transport = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode.Transport" />
      <MemberSignature Language="VB.NET" Value="Transport" />
      <MemberSignature Language="F#" Value="Transport = 1" Usage="Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode.Transport" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="62bdf-106">Die Sicherheit wird über HTTPS bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="62bdf-106">Security is provided using HTTPS.</span></span> <span data-ttu-id="62bdf-107">Der Dienst muss mit SSL-Zertifikaten konfiguriert werden.</span><span class="sxs-lookup"><span data-stu-id="62bdf-107">The service must be configured with SSL certificates.</span></span> <span data-ttu-id="62bdf-108">Die SOAP-Nachricht wird als Ganzes mit HTTPS geschützt.</span><span class="sxs-lookup"><span data-stu-id="62bdf-108">The SOAP message is protected as a whole using HTTPS.</span></span> <span data-ttu-id="62bdf-109">Der Dienst wird vom Client anhand des SSL-Zertifikats des Diensts authentifiziert.</span><span class="sxs-lookup"><span data-stu-id="62bdf-109">The service is authenticated by the client using the service’s SSL certificate.</span></span> <span data-ttu-id="62bdf-110">Die Clientauthentifizierung wird über ClientCredentialType gesteuert.</span><span class="sxs-lookup"><span data-stu-id="62bdf-110">The client authentication is controlled through the ClientCredentialType.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="TransportWithMessageCredential">
      <MemberSignature Language="C#" Value="TransportWithMessageCredential" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode TransportWithMessageCredential = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode.TransportWithMessageCredential" />
      <MemberSignature Language="VB.NET" Value="TransportWithMessageCredential" />
      <MemberSignature Language="F#" Value="TransportWithMessageCredential = 3" Usage="Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode.TransportWithMessageCredential" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary><span data-ttu-id="62bdf-111">Integrität, Vertraulichkeit und Serverauthentifizierung werden über HTTPS bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="62bdf-111">Integrity, confidentiality and server authentication are provided by HTTPS.</span></span> <span data-ttu-id="62bdf-112">Der Dienst muss mit einem Zertifikat konfiguriert werden.</span><span class="sxs-lookup"><span data-stu-id="62bdf-112">The service must be configured with a certificate.</span></span> <span data-ttu-id="62bdf-113">Die Clientauthentifizierung wird über die SOAP-Nachrichtensicherheit bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="62bdf-113">Client authentication is provided by means of SOAP message security.</span></span> <span data-ttu-id="62bdf-114">Dieser Modus findet Anwendung, wenn sich der Benutzer mit UserName oder Certificat-Anmeldeinformationen authentifiziert und eine HTTPS-Bereitstellung zum Sichern der Nachrichtenübertragung vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="62bdf-114">This mode is applicable when the user is authenticating with a UserName or Certificate credential and there is an existing HTTPS deployment for securing message transfer.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>