<Type Name="NamespaceType" FullName="Microsoft.ServiceBus.Management.NamespaceType">
  <TypeSignature Language="C#" Value="public enum NamespaceType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed NamespaceType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Management.NamespaceType" />
  <TypeSignature Language="VB.NET" Value="Public Enum NamespaceType" />
  <TypeSignature Language="F#" Value="type NamespaceType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary><span data-ttu-id="325a0-101">Gibt den Typ von Entitäten, die der Namespace enthalten kann (messaging Event Hubs oder benachrichtigungshubs).</span><span class="sxs-lookup"><span data-stu-id="325a0-101">Specifies the type of entities the namespace can contain (messaging, Event Hubs, or notification hubs).</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EventHub">
      <MemberSignature Language="C#" Value="EventHub" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Management.NamespaceType EventHub = unsigned int8(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Management.NamespaceType.EventHub" />
      <MemberSignature Language="VB.NET" Value="EventHub" />
      <MemberSignature Language="F#" Value="EventHub = 3" Usage="Microsoft.ServiceBus.Management.NamespaceType.EventHub" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Management.NamespaceType</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary><span data-ttu-id="325a0-102">Gibt an, dass der Namespace Event Hubs enthalten soll.</span><span class="sxs-lookup"><span data-stu-id="325a0-102">Specifies that the namespace should contain Event Hubs.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Messaging">
      <MemberSignature Language="C#" Value="Messaging" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Management.NamespaceType Messaging = unsigned int8(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Management.NamespaceType.Messaging" />
      <MemberSignature Language="VB.NET" Value="Messaging" />
      <MemberSignature Language="F#" Value="Messaging = 0" Usage="Microsoft.ServiceBus.Management.NamespaceType.Messaging" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Management.NamespaceType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="325a0-103">Gibt an, dass der Namespace messagingentitäten (Warteschlangen, Themen und Abonnements) enthalten soll.</span><span class="sxs-lookup"><span data-stu-id="325a0-103">Specifies that the namespace should contain messaging entities (queues, topics, or subscriptions).</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Mixed">
      <MemberSignature Language="C#" Value="Mixed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Management.NamespaceType Mixed = unsigned int8(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Management.NamespaceType.Mixed" />
      <MemberSignature Language="VB.NET" Value="Mixed" />
      <MemberSignature Language="F#" Value="Mixed = 2" Usage="Microsoft.ServiceBus.Management.NamespaceType.Mixed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Management.NamespaceType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary><span data-ttu-id="325a0-104">Nur für Abwärtskompatibilität unterstützt.</span><span class="sxs-lookup"><span data-stu-id="325a0-104">Supported only for backward compatibility.</span></span> <span data-ttu-id="325a0-105">Gibt an, dass der Namespace, eine Mischung von messagingentitäten und benachrichtigungshubs enthalten kann.</span><span class="sxs-lookup"><span data-stu-id="325a0-105">Specifies that the namespace can contain a mixture of messaging entities and notification hubs.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="NotificationHub">
      <MemberSignature Language="C#" Value="NotificationHub" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Management.NamespaceType NotificationHub = unsigned int8(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Management.NamespaceType.NotificationHub" />
      <MemberSignature Language="VB.NET" Value="NotificationHub" />
      <MemberSignature Language="F#" Value="NotificationHub = 1" Usage="Microsoft.ServiceBus.Management.NamespaceType.NotificationHub" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Management.NamespaceType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="325a0-106">Gibt an, dass der Namespace benachrichtigungshubs enthalten soll.</span><span class="sxs-lookup"><span data-stu-id="325a0-106">Specifies that the namespace should contain notification hubs.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Relay">
      <MemberSignature Language="C#" Value="Relay" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Management.NamespaceType Relay = unsigned int8(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Management.NamespaceType.Relay" />
      <MemberSignature Language="VB.NET" Value="Relay" />
      <MemberSignature Language="F#" Value="Relay = 4" Usage="Microsoft.ServiceBus.Management.NamespaceType.Relay" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Management.NamespaceType</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary><span data-ttu-id="325a0-107">Gibt an, dass der Namespace-Relays und Hybridverbindungen enthalten soll.</span><span class="sxs-lookup"><span data-stu-id="325a0-107">Specifies that the namespace should contain Relays and Hybrid Connections.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>