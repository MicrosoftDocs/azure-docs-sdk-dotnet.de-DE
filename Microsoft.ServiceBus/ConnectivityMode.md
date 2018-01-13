<Type Name="ConnectivityMode" FullName="Microsoft.ServiceBus.ConnectivityMode">
  <TypeSignature Language="C#" Value="public enum ConnectivityMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConnectivityMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.ConnectivityMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ConnectivityMode" />
  <TypeSignature Language="F#" Value="type ConnectivityMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>Legt das zugrunde liegende auf Übertragungsebene-Protokoll zur Kommunikation mit Service Bus verwendet. </summary>
    <remarks>Der Verbindungsmodus unterscheidet sich von der <see cref="T:Microsoft.ServiceBus.Messaging.TransportType" /> Protokoll, das der Dienst für die Clientkommunikation angibt. Der Transporttyp wird durch die verwendete Bindung bestimmt. Unabhängig davon, welche <see cref="T:Microsoft.ServiceBus.Messaging.TransportType" /> Auswahl (NetMessaging oder AMQP), die Kommunikation über den ausgewählten Verbindungsmodus verwendet wird. Beispielsweise haben Sie AMQP TCP-oder HTTP (S) auftreten. </remarks>
  </Docs>
  <Members>
    <Member MemberName="AutoDetect">
      <MemberSignature Language="C#" Value="AutoDetect" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.ConnectivityMode AutoDetect = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivityMode.AutoDetect" />
      <MemberSignature Language="VB.NET" Value="AutoDetect" />
      <MemberSignature Language="F#" Value="AutoDetect = 2" Usage="Microsoft.ServiceBus.ConnectivityMode.AutoDetect" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>Modus "automatisch erkennen". Wählt automatisch zwischen den TCP-, HTTP- und HTTPS-Modi, die basierend auf einem automatischen Erkennungsmechanismus, der prüft, ob beide Verbindungsoptionen für die aktuell Netzwerkumgebung verfügbar ist. Wenn beide verfügbar sind, wird das System TCP wird standardmäßig ausgewählt.</summary>
      </Docs>
    </Member>
    <Member MemberName="Http">
      <MemberSignature Language="C#" Value="Http" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.ConnectivityMode Http = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivityMode.Http" />
      <MemberSignature Language="VB.NET" Value="Http" />
      <MemberSignature Language="F#" Value="Http = 0" Usage="Microsoft.ServiceBus.ConnectivityMode.Http" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>HTTP-Modus. Listener versucht, eine HTTP-Verbindung, gefolgt von einer HTTPS-Verbindung mit der Service Bus-Dienst, und Warten auf Nachrichten. Dadurch möglicherweise, dass Sie problemlos TCP-Port Einschränkungen umgehen.</summary>
      </Docs>
    </Member>
    <Member MemberName="Https">
      <MemberSignature Language="C#" Value="Https" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.ConnectivityMode Https = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivityMode.Https" />
      <MemberSignature Language="VB.NET" Value="Https" />
      <MemberSignature Language="F#" Value="Https = 3" Usage="Microsoft.ServiceBus.ConnectivityMode.Https" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>HTTPS-Modus. Listener eine HTTPS-Verbindung mit dem Service Bus-Dienst versucht dann Nachrichten warten. </summary>
      </Docs>
    </Member>
    <Member MemberName="Tcp">
      <MemberSignature Language="C#" Value="Tcp" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.ConnectivityMode Tcp = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivityMode.Tcp" />
      <MemberSignature Language="VB.NET" Value="Tcp" />
      <MemberSignature Language="F#" Value="Tcp = 1" Usage="Microsoft.ServiceBus.ConnectivityMode.Tcp" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>TCP-Modus (Standard). Erstellen Sie Listener TCP-Verbindungen mit dem Service Bus-Dienst an einen Zielport im Bereich 9350 bis 9354.</summary>
      </Docs>
    </Member>
  </Members>
</Type>