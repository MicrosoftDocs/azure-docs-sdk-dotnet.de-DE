<Type Name="ConnectivityMode" FullName="Microsoft.Azure.NotificationHubs.ConnectivityMode">
  <TypeSignature Language="C#" Value="public enum ConnectivityMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConnectivityMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.ConnectivityMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ConnectivityMode" />
  <TypeSignature Language="F#" Value="type ConnectivityMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>Beschreibt den Verbindungsmodus. </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AutoDetect">
      <MemberSignature Language="C#" Value="AutoDetect" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.NotificationHubs.ConnectivityMode AutoDetect = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.ConnectivityMode.AutoDetect" />
      <MemberSignature Language="VB.NET" Value="AutoDetect" />
      <MemberSignature Language="F#" Value="AutoDetect = 2" Usage="Microsoft.Azure.NotificationHubs.ConnectivityMode.AutoDetect" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>Modus "automatisch erkennen". Wählt automatisch zwischen den TCP-, HTTP- und HTTPS-Modi, die basierend auf einem automatischen Erkennungsmechanismus, der prüft, ob beide Verbindungsoptionen für die aktuell Netzwerkumgebung verfügbar ist. Wenn beide verfügbar sind, wird das System TCP wird standardmäßig ausgewählt.</summary>
      </Docs>
    </Member>
    <Member MemberName="Http">
      <MemberSignature Language="C#" Value="Http" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.NotificationHubs.ConnectivityMode Http = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.ConnectivityMode.Http" />
      <MemberSignature Language="VB.NET" Value="Http" />
      <MemberSignature Language="F#" Value="Http = 0" Usage="Microsoft.Azure.NotificationHubs.ConnectivityMode.Http" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>HTTP-Modus. Listener versucht, eine HTTP-Verbindung, gefolgt von einer HTTPS-Verbindung mit dem Windows Azure Service Bus-Dienst und das Abrufen von Nachrichten. Dadurch möglicherweise, dass Sie problemlos TCP-Port Einschränkungen umgehen.</summary>
      </Docs>
    </Member>
    <Member MemberName="Tcp">
      <MemberSignature Language="C#" Value="Tcp" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.NotificationHubs.ConnectivityMode Tcp = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.ConnectivityMode.Tcp" />
      <MemberSignature Language="VB.NET" Value="Tcp" />
      <MemberSignature Language="F#" Value="Tcp = 1" Usage="Microsoft.Azure.NotificationHubs.ConnectivityMode.Tcp" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>TCP-Modus (Standard). Erstellen Sie Listener TCP-Verbindungen mit dem Windows Azure Service Bus-Dienst an einen Zielport im Bereich 9350 bis 9354.</summary>
      </Docs>
    </Member>
  </Members>
</Type>