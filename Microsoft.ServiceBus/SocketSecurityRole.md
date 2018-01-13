<Type Name="SocketSecurityRole" FullName="Microsoft.ServiceBus.SocketSecurityRole">
  <TypeSignature Language="C#" Value="public enum SocketSecurityRole" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed SocketSecurityRole extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.SocketSecurityRole" />
  <TypeSignature Language="VB.NET" Value="Public Enum SocketSecurityRole" />
  <TypeSignature Language="F#" Value="type SocketSecurityRole = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>Beschreibt die Rolle für die Socket-Sicherheit. </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.SocketSecurityRole None = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SocketSecurityRole.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 2" Usage="Microsoft.ServiceBus.SocketSecurityRole.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.SocketSecurityRole</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>Wenn auf einem Client festgelegt ist, wird die Anwendung nicht verschlüsselte Nachrichten senden. Wenn auf einem Server festgelegt, wird die Anwendung akzeptiert, verschlüsselte und unverschlüsselte Nachrichten.</summary>
      </Docs>
    </Member>
    <Member MemberName="SslClient">
      <MemberSignature Language="C#" Value="SslClient" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.SocketSecurityRole SslClient = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SocketSecurityRole.SslClient" />
      <MemberSignature Language="VB.NET" Value="SslClient" />
      <MemberSignature Language="F#" Value="SslClient = 1" Usage="Microsoft.ServiceBus.SocketSecurityRole.SslClient" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.SocketSecurityRole</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>Die Anwendung wird als ein SSL-Client, was bedeutet, dass die Anwendung versucht, eine Verbindung herstellen und das Senden von Nachrichten über einen verschlüsselten Kanal identifiziert. </summary>
      </Docs>
    </Member>
    <Member MemberName="SslServer">
      <MemberSignature Language="C#" Value="SslServer" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.SocketSecurityRole SslServer = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SocketSecurityRole.SslServer" />
      <MemberSignature Language="VB.NET" Value="SslServer" />
      <MemberSignature Language="F#" Value="SslServer = 0" Usage="Microsoft.ServiceBus.SocketSecurityRole.SslServer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.SocketSecurityRole</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>Identifiziert die Anwendung als SSL-Server, was bedeutet, dass die Anwendung nur auf eine sicheren transportverbindung akzeptiert.</summary>
      </Docs>
    </Member>
  </Members>
</Type>