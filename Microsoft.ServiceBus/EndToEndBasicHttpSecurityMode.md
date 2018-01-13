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
    <summary>Ein Enumerationstyp, der angibt, die Sicherheitsmodi, die mit verwendet werden können <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />. </summary>
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
        <summary>Sicherheit wird über WS-Security-SOAP-nachrichtensicherheit bereitgestellt. Für die <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> erfordert das System, dass das Serverzertifikat dem Client separat zur Verfügung gestellt wird. Die gültigen Typen von Clientanmeldeinformationen für diese Bindung sind Benutzername und das Zertifikat an.</summary>
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
        <summary>Nachrichten werden nicht während der Übertragung gesichert. </summary>
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
        <summary>Die Sicherheit wird über HTTPS bereitgestellt. Der Dienst muss mit SSL-Zertifikaten konfiguriert werden. Die SOAP-Nachricht wird als Ganzes mit HTTPS geschützt. Der Dienst wird vom Client anhand des SSL-Zertifikats des Diensts authentifiziert. Die Clientauthentifizierung wird über ClientCredentialType gesteuert.</summary>
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
        <summary>Integrität, Vertraulichkeit und Serverauthentifizierung werden über HTTPS bereitgestellt. Der Dienst muss mit einem Zertifikat konfiguriert werden. Die Clientauthentifizierung wird über die SOAP-Nachrichtensicherheit bereitgestellt. Dieser Modus findet Anwendung, wenn sich der Benutzer mit UserName oder Certificat-Anmeldeinformationen authentifiziert und eine HTTPS-Bereitstellung zum Sichern der Nachrichtenübertragung vorhanden ist.</summary>
      </Docs>
    </Member>
  </Members>
</Type>