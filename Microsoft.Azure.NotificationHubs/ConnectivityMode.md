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
    <summary><span data-ttu-id="3972a-101">Beschreibt den Verbindungsmodus.</span><span class="sxs-lookup"><span data-stu-id="3972a-101">Describes the connectivity mode.</span></span> </summary>
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
        <summary><span data-ttu-id="3972a-102">Modus "automatisch erkennen".</span><span class="sxs-lookup"><span data-stu-id="3972a-102">Auto-detect mode.</span></span> <span data-ttu-id="3972a-103">Wählt automatisch zwischen den TCP-, HTTP- und HTTPS-Modi, die basierend auf einem automatischen Erkennungsmechanismus, der prüft, ob beide Verbindungsoptionen für die aktuell Netzwerkumgebung verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="3972a-103">Automatically selects between the TCP, HTTP and HTTPS modes based on an auto-detection mechanism that probes whether either connectivity option is available for the current network environment.</span></span> <span data-ttu-id="3972a-104">Wenn beide verfügbar sind, wird das System TCP wird standardmäßig ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="3972a-104">If both are available, the system will choose TCP by default.</span></span></summary>
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
        <summary><span data-ttu-id="3972a-105">HTTP-Modus.</span><span class="sxs-lookup"><span data-stu-id="3972a-105">HTTP mode.</span></span> <span data-ttu-id="3972a-106">Listener versucht, eine HTTP-Verbindung, gefolgt von einer HTTPS-Verbindung mit dem Windows Azure Service Bus-Dienst und das Abrufen von Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="3972a-106">Listeners attempt an HTTP connection followed by an HTTPS connection with the Windows Azure Service Bus service and poll for messages.</span></span> <span data-ttu-id="3972a-107">Dadurch möglicherweise, dass Sie problemlos TCP-Port Einschränkungen umgehen.</span><span class="sxs-lookup"><span data-stu-id="3972a-107">This might allow you to more easily work around TCP port constraints.</span></span></summary>
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
        <summary><span data-ttu-id="3972a-108">TCP-Modus (Standard).</span><span class="sxs-lookup"><span data-stu-id="3972a-108">TCP mode (default).</span></span> <span data-ttu-id="3972a-109">Erstellen Sie Listener TCP-Verbindungen mit dem Windows Azure Service Bus-Dienst an einen Zielport im Bereich 9350 bis 9354.</span><span class="sxs-lookup"><span data-stu-id="3972a-109">Listeners create TCP connections to the Windows Azure Service Bus service to a destination port in the range 9350 to 9354.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>