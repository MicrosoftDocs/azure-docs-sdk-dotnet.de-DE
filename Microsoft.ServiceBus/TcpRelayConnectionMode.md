<Type Name="TcpRelayConnectionMode" FullName="Microsoft.ServiceBus.TcpRelayConnectionMode">
  <TypeSignature Language="C#" Value="public enum TcpRelayConnectionMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TcpRelayConnectionMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.TcpRelayConnectionMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum TcpRelayConnectionMode" />
  <TypeSignature Language="F#" Value="type TcpRelayConnectionMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>Beschreibt den Verbindungsmodus für den <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />. </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Hybrid">
      <MemberSignature Language="C#" Value="Hybrid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.TcpRelayConnectionMode Hybrid = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Hybrid" />
      <MemberSignature Language="VB.NET" Value="Hybrid" />
      <MemberSignature Language="F#" Value="Hybrid = 1" Usage="Microsoft.ServiceBus.TcpRelayConnectionMode.Hybrid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayConnectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>Kommunikation ist über die Azure Service Bus-Infrastruktur mittels Relay weitergeleitet, während die Client- und Dienstendpunkte eine direkte Socketverbindung untereinander aushandeln. Die Koordination dieser direkten Verbindung wird vom Azure Service Bus-Cloud-Dienst gesteuert. Der Algorithmus für direkte Socketverbindungen kann direkte Verbindungen zwischen zwei Parteien, die sich hinter gegenüberliegenden Firewalls und NAT sit herstellen Geräte. Der Algorithmus verwendet nur ausgehende Verbindungen für Firewallausnahmen und stützt sich auf einen gegenseitigen Vorhersage Algorithmus für NAT-Durchlauf. Da der NAT-Traversal-Algorithmus eine sehr eng festgelegten Koordination und eine geschätzte Vorhersage über NAT erwartet abhängig ist, tendenziell der Algorithmus eine sehr hohe Erfolgsrate für die Startseite "und" Small Business-Szenarien mit einer kleinen Anzahl von clients und in die Erfolgsrate mit größeren NATs beeinträchtigt wird. Wenn eine direkte Verbindung hergestellt werden kann, wird die relayverbindung automatisch in eine direkte Verbindung ohne Nachrichten- oder Datenverluste aktualisiert. Wenn die direkte Verbindung hergestellt werden kann, weiterhin Daten der Azure Service Bus-Relay durchlaufen. 
            
            Dieser Modus erfordert zusätzlich ausgehenden Port 819 für die Vorhersage NAT-Algorithmus. Die meisten persönlichen Firewall-Produkte die ausgehende Socketverbindung, die durch die direkte eingerichtet wird eine Verbindung herstellen Modus benötigen auch eine einmalige Richtlinie-Ausnahme (der persönlichen Windows-Firewall und andere Produkte in der Regel fordert vom Benutzer gewährt werden soll der Benutzer) zur hostanwendung. 
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Relayed">
      <MemberSignature Language="C#" Value="Relayed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.TcpRelayConnectionMode Relayed = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Relayed" />
      <MemberSignature Language="VB.NET" Value="Relayed" />
      <MemberSignature Language="F#" Value="Relayed = 0" Usage="Microsoft.ServiceBus.TcpRelayConnectionMode.Relayed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayConnectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>Die gesamte Kommunikation wird durch die Azure Service Bus-Cloud mittels Relay weitergeleitet. Die SSL-geschützte steuerungsverbindung wird verwendet, um eine weitergeleitete End-to-End-Socketverbindung auszuhandeln, der alle Client-Dienst-Kommunikation durchläuft. Nachdem die Verbindung hergestellt wurde, fungiert die Azure Service Bus-Infrastruktur ähnlich wie eine socketweiterleitungsproxy, die einen bidirektionalen Bytedatenstrom aus. Dieser Modus erfordert zusätzlich ausgehenden Port 819 für die Vorhersage NAT-Algorithmus. Die meisten persönlichen Firewall-Produkte die ausgehende Socketverbindung, die durch die direkte eingerichtet wird eine Verbindung herstellen Modus benötigen auch eine einmalige Richtlinie-Ausnahme (der persönlichen Windows-Firewall und andere Produkte in der Regel fordert vom Benutzer gewährt werden soll der Benutzer) zur hostanwendung.</summary>
      </Docs>
    </Member>
  </Members>
</Type>