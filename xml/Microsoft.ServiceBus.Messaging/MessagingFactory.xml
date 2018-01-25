<Type Name="MessagingFactory" FullName="Microsoft.ServiceBus.Messaging.MessagingFactory">
  <TypeSignature Language="C#" Value="public abstract class MessagingFactory : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MessagingFactory extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MessagingFactory&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type MessagingFactory = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary> <span data-ttu-id="531b9-101">Die MessagingFactory-Klasse ist der Premium-Klasse, die für Vorgänge zur Laufzeit verwendet wird, zum Senden und empfangen zu und von Warteschlangen, Themen und Abonnements.</span><span class="sxs-lookup"><span data-stu-id="531b9-101">The MessagingFactory class is the anchor class used for run time operations to send and receive to and from queues, topics, or subscriptions.</span></span> </summary>
    <remarks><span data-ttu-id="531b9-102">Beachten Sie, dass alle Membermethode mit CreateXXXClient, z. B. CreateQueueClient, keine neue Entität im Namespace erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="531b9-102">Please note that any member method with CreateXXXClient, such as CreateQueueClient, does not create a new entity in the namespace.</span></span> <span data-ttu-id="531b9-103">IT nur ruft zu behandeln, um eine vorhandene Entität, die zuvor mit erstellt die <see cref="T:Microsoft.ServiceBus.NamespaceManager" />.</span><span class="sxs-lookup"><span data-stu-id="531b9-103">It only gets handle to an existing entity created earlier using the <see cref="T:Microsoft.ServiceBus.NamespaceManager" />.</span></span> <span data-ttu-id="531b9-104">Wenn diese Entitäten ist nicht im Namespace vorhanden, erhalten Sie eine Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="531b9-104">If these entities does not exist in the namespace, you will get an exception.</span></span></remarks>
    <altmember cref="T:Microsoft.ServiceBus.NamespaceManager" />
    <example>
      <code>
            <span data-ttu-id="531b9-105">String-Adresse = "sb://myapp.WindowsAzure.com/"; die Basisadresse des Namespace, um die Verbindung hergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="531b9-105">string Address = "sb://myapp.WindowsAzure.com/"; //base address of namespace you are connecting to.</span></span>
            <span data-ttu-id="531b9-106">MessagingFactorySettings MsgFactorySettings = neue MessagingFactorySettings(); Betriebsmodus Timeout angeben (optional) MessagingFactory MsgFactory = MessagingFactory.Create (Adresse, MsgFactorySettings);</span><span class="sxs-lookup"><span data-stu-id="531b9-106">MessagingFactorySettings MsgFactorySettings = new MessagingFactorySettings(); //specify operating timeout (optional) MessagingFactory MsgFactory = MessagingFactory.Create(Address, MsgFactorySettings);</span></span>
            </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.AcceptMessageSession" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession () As MessageSession" />
      <MemberSignature Language="F#" Value="member this.AcceptMessageSession : unit -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.AcceptMessageSession " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="531b9-107">Gibt die verfügbaren Sitzungen in allen Abonnements sitzungsfähigen und Warteschlangen im Dienstnamespace zurück.</span><span class="sxs-lookup"><span data-stu-id="531b9-107">Returns available sessions across all session-enabled subscriptions and queues in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="531b9-108">Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="531b9-108">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.AcceptMessageSession(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="member this.AcceptMessageSession : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.AcceptMessageSession serverWaitTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime"><span data-ttu-id="531b9-109">Der Timeout für die Verarbeitung.</span><span class="sxs-lookup"><span data-stu-id="531b9-109">The processing time out.</span></span></param>
        <summary><span data-ttu-id="531b9-110">Gibt die verfügbaren Sitzungen in allen Abonnements sitzungsfähigen und Warteschlangen im Dienstnamespace zurück.</span><span class="sxs-lookup"><span data-stu-id="531b9-110">Returns available sessions across all session-enabled subscriptions and queues in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="531b9-111">Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="531b9-111">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="member this.AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="messagingFactory.AcceptMessageSessionAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="531b9-112">Gibt asynchron zurück verfügbaren Sitzungen, in allen Abonnements sitzungsfähigen und Warteschlangen im Dienstnamespace.</span><span class="sxs-lookup"><span data-stu-id="531b9-112">Asynchronously returns available sessions across all session-enabled subscriptions and queues in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="531b9-113">Eine Taskinstanz, die den asynchronen Vorgang für den Accept-meldungssitzung darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-113">A task instance that represents the asynchronous operation for accept message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="member this.AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="messagingFactory.AcceptMessageSessionAsync serverWaitTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime"><span data-ttu-id="531b9-114">Der Timeout für die Verarbeitung.</span><span class="sxs-lookup"><span data-stu-id="531b9-114">The processing time out.</span></span></param>
        <summary><span data-ttu-id="531b9-115">Gibt asynchron zurück verfügbaren Sitzungen, in allen Abonnements sitzungsfähigen und Warteschlangen im Dienstnamespace.</span><span class="sxs-lookup"><span data-stu-id="531b9-115">Asynchronously returns available sessions across all session-enabled subscriptions and queues in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="531b9-116">Eine Taskinstanz, die den asynchronen Vorgang für den Accept-meldungssitzung darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-116">A task instance that represents the asynchronous operation for accept message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactory.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="531b9-117">Ruft die Basisadresse der messaging-Factory ab.</span><span class="sxs-lookup"><span data-stu-id="531b9-117">Gets the base address of the messaging factory.</span></span></summary>
        <value><span data-ttu-id="531b9-118">Ein URI, der die Basisadresse der messaging-Factory darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-118">A URI that represents the base address of the messaging factory.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create () As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : unit -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="531b9-119">Erstellt ein neues messaging Factoryobjekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-119">Creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="531b9-120">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-120">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;string&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (addresses As IEnumerable(Of String)) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;string&gt; -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create addresses" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="531b9-121">Eine Enumeration von Basisadressen.</span><span class="sxs-lookup"><span data-stu-id="531b9-121">An enumeration of base addresses.</span></span></param>
        <summary><span data-ttu-id="531b9-122">Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-122">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="531b9-123">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-123">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (addresses As IEnumerable(Of Uri)) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;Uri&gt; -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create addresses" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="531b9-124">Eine Enumeration der Adresse.</span><span class="sxs-lookup"><span data-stu-id="531b9-124">An enumeration of address.</span></span></param>
        <summary><span data-ttu-id="531b9-125">Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-125">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="531b9-126">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-126">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (address As String) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="531b9-127">Die Basisadresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="531b9-127">The base address of the service namespace.</span></span></param>
        <summary><span data-ttu-id="531b9-128">Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-128">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="531b9-129">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-129">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (address As Uri) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : Uri -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="531b9-130">Die Basisadresse des Namespace.</span><span class="sxs-lookup"><span data-stu-id="531b9-130">The namespace base address.</span></span></param>
        <summary><span data-ttu-id="531b9-131">Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-131">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="531b9-132">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-132">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (addresses As IEnumerable(Of String), factorySettings As MessagingFactorySettings) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;string&gt; * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (addresses, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="531b9-133">Eine Enumeration von Basisadressen.</span><span class="sxs-lookup"><span data-stu-id="531b9-133">An enumeration of base addresses.</span></span></param>
        <param name="factorySettings"><span data-ttu-id="531b9-134">Die werkseitigen Standardeinstellungen.</span><span class="sxs-lookup"><span data-stu-id="531b9-134">The factory settings.</span></span></param>
        <summary><span data-ttu-id="531b9-135">Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-135">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="531b9-136">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-136">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;string&gt; * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (addresses, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="531b9-137">Eine Enumeration von Basisadressen.</span><span class="sxs-lookup"><span data-stu-id="531b9-137">An enumeration of base addresses.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="531b9-138">Der Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="531b9-138">The token provider.</span></span></param>
        <summary><span data-ttu-id="531b9-139">Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-139">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="531b9-140">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-140">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (addresses As IEnumerable(Of Uri), factorySettings As MessagingFactorySettings) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;Uri&gt; * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (addresses, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="531b9-141">Eine Enumeration der Adresse.</span><span class="sxs-lookup"><span data-stu-id="531b9-141">An enumeration of address.</span></span></param>
        <param name="factorySettings"><span data-ttu-id="531b9-142">Die werkseitigen Standardeinstellungen.</span><span class="sxs-lookup"><span data-stu-id="531b9-142">The factory settings.</span></span></param>
        <summary><span data-ttu-id="531b9-143">Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-143">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="531b9-144">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-144">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;Uri&gt; * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (addresses, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="531b9-145">Eine Enumeration der Adresse.</span><span class="sxs-lookup"><span data-stu-id="531b9-145">An enumeration of address.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="531b9-146">Der Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="531b9-146">The token provider.</span></span></param>
        <summary><span data-ttu-id="531b9-147">Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-147">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="531b9-148">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-148">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (string address, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(string address, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.String,Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (address As String, factorySettings As MessagingFactorySettings) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (address, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="531b9-149">Die Basisadresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="531b9-149">The base address of the service namespace.</span></span></param>
        <param name="factorySettings"><span data-ttu-id="531b9-150">Die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="531b9-150">The <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> settings.</span></span></param>
        <summary><span data-ttu-id="531b9-151">Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-151">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="531b9-152">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-152">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.UriFormatException"><span data-ttu-id="531b9-153">Wird ausgelöst, wenn <paramref name="address" /> ist leer.</span><span class="sxs-lookup"><span data-stu-id="531b9-153">Thrown when <paramref name="address" /> is empty.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="531b9-154">Wird ausgelöst, wenn <paramref name="factorySettings" /> oder <paramref name="address" /> null sind.</span><span class="sxs-lookup"><span data-stu-id="531b9-154">Thrown when <paramref name="factorySettings" /> or <paramref name="address" /> are null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="531b9-155"><paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</span><span class="sxs-lookup"><span data-stu-id="531b9-155"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (string address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(string address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.String,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (address, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="531b9-156">Die Basisadresse des Namespaces.</span><span class="sxs-lookup"><span data-stu-id="531b9-156">The base address of the namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="531b9-157">Der Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="531b9-157">The token provider.</span></span></param>
        <summary><span data-ttu-id="531b9-158">Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-158">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="531b9-159">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-159">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="531b9-160"><paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</span><span class="sxs-lookup"><span data-stu-id="531b9-160"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
        <exception cref="T:System.UriFormatException"><span data-ttu-id="531b9-161">Wird ausgelöst, wenn <paramref name="address" /> ist leer.</span><span class="sxs-lookup"><span data-stu-id="531b9-161">Thrown when <paramref name="address" /> is empty.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="531b9-162">Wird ausgelöst, wenn <paramref name="tokenProvider" /> oder <paramref name="address" /> null sind.</span><span class="sxs-lookup"><span data-stu-id="531b9-162">Thrown when <paramref name="tokenProvider" /> or <paramref name="address" /> are null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (Uri address, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Uri address, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Uri,Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (address As Uri, factorySettings As MessagingFactorySettings) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (address, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="531b9-163">Die Basisadresse des Namespace.</span><span class="sxs-lookup"><span data-stu-id="531b9-163">The namespace base address.</span></span></param>
        <param name="factorySettings"><span data-ttu-id="531b9-164">Die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="531b9-164">The <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> settings.</span></span></param>
        <summary><span data-ttu-id="531b9-165">Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-165">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="531b9-166">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-166">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="531b9-167">Wird ausgelöst, wenn <paramref name="address" /> oder <paramref name="factorySettings" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="531b9-167">Thrown when <paramref name="address" /> or <paramref name="factorySettings" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="531b9-168"><paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</span><span class="sxs-lookup"><span data-stu-id="531b9-168"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (Uri address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Uri address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Uri,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (address, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="531b9-169">Die Basisadresse des Namespaces.</span><span class="sxs-lookup"><span data-stu-id="531b9-169">The base address of the namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="531b9-170">Der Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="531b9-170">The token provider.</span></span></param>
        <summary><span data-ttu-id="531b9-171">Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-171">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="531b9-172">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-172">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="531b9-173"><paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</span><span class="sxs-lookup"><span data-stu-id="531b9-173"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="531b9-174">Wird ausgelöst, wenn <paramref name="tokenProvider" /> oder <paramref name="address" /> null sind.</span><span class="sxs-lookup"><span data-stu-id="531b9-174">Thrown when <paramref name="tokenProvider" /> or <paramref name="address" /> are null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;string&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (addresses As IEnumerable(Of String)) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync addresses" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="531b9-175">Eine Enumeration von Basisadressen.</span><span class="sxs-lookup"><span data-stu-id="531b9-175">An enumeration of base addresses.</span></span></param>
        <summary><span data-ttu-id="531b9-176">Erstellt asynchron ein neue messaging Factory-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-176">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="531b9-177">Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-177">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (addresses As IEnumerable(Of Uri)) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;Uri&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync addresses" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="531b9-178">Eine Enumeration der Adresse.</span><span class="sxs-lookup"><span data-stu-id="531b9-178">An enumeration of address.</span></span></param>
        <summary><span data-ttu-id="531b9-179">Erstellt asynchron ein neue messaging Factory-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-179">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="531b9-180">Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-180">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (address As String) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="531b9-181">Die Basisadresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="531b9-181">The base address of the service namespace.</span></span></param>
        <summary><span data-ttu-id="531b9-182">Erstellt asynchron ein neue messaging Factory-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-182">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="531b9-183">Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-183">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (address As Uri) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Uri -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="531b9-184">Die Basisadresse des Namespace.</span><span class="sxs-lookup"><span data-stu-id="531b9-184">The namespace base address.</span></span></param>
        <summary><span data-ttu-id="531b9-185">Erstellt asynchron ein neue messaging Factory-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-185">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="531b9-186">Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-186">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (addresses As IEnumerable(Of String), factorySettings As MessagingFactorySettings) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;string&gt; * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (addresses, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="531b9-187">Eine Enumeration von Basisadressen.</span><span class="sxs-lookup"><span data-stu-id="531b9-187">An enumeration of base addresses.</span></span></param>
        <param name="factorySettings"><span data-ttu-id="531b9-188">Die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="531b9-188">The <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> settings.</span></span></param>
        <summary><span data-ttu-id="531b9-189">Erstellt asynchron ein neue messaging Factory-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-189">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="531b9-190">Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-190">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;string&gt; * Microsoft.ServiceBus.TokenProvider -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (addresses, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="531b9-191">Eine Enumeration von Basisadressen.</span><span class="sxs-lookup"><span data-stu-id="531b9-191">An enumeration of base addresses.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="531b9-192">Der Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="531b9-192">The token provider.</span></span></param>
        <summary><span data-ttu-id="531b9-193">Erstellt asynchron ein neue messaging Factory-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-193">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="531b9-194">Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-194">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (addresses As IEnumerable(Of Uri), factorySettings As MessagingFactorySettings) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;Uri&gt; * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (addresses, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="531b9-195">Eine Enumeration der Adresse.</span><span class="sxs-lookup"><span data-stu-id="531b9-195">An enumeration of address.</span></span></param>
        <param name="factorySettings"><span data-ttu-id="531b9-196">Die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="531b9-196">The <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> settings.</span></span></param>
        <summary><span data-ttu-id="531b9-197">Erstellt asynchron ein neue messaging Factory-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-197">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="531b9-198">Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-198">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;Uri&gt; * Microsoft.ServiceBus.TokenProvider -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (addresses, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="531b9-199">Eine Enumeration der Adresse.</span><span class="sxs-lookup"><span data-stu-id="531b9-199">An enumeration of address.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="531b9-200">Der Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="531b9-200">The token provider.</span></span></param>
        <summary><span data-ttu-id="531b9-201">Erstellt asynchron ein neue messaging Factory-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-201">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="531b9-202">Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-202">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (string address, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(string address, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.String,Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (address As String, factorySettings As MessagingFactorySettings) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : string * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (address, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="531b9-203">Die Basisadresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="531b9-203">The base address of the service namespace.</span></span></param>
        <param name="factorySettings"><span data-ttu-id="531b9-204">Die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="531b9-204">The <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> settings.</span></span></param>
        <summary><span data-ttu-id="531b9-205">Erstellt asynchron ein neue messaging Factory-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-205">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="531b9-206">Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-206">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (string address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(string address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.String,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : string * Microsoft.ServiceBus.TokenProvider -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (address, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="531b9-207">Die Basisadresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="531b9-207">The base address of the service namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="531b9-208">Der Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="531b9-208">The token provider.</span></span></param>
        <summary><span data-ttu-id="531b9-209">Erstellt asynchron ein neue messaging Factory-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-209">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="531b9-210">Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-210">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (Uri address, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Uri address, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Uri,Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (address As Uri, factorySettings As MessagingFactorySettings) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Uri * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (address, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="531b9-211">Die Basisadresse des Namespace.</span><span class="sxs-lookup"><span data-stu-id="531b9-211">The namespace base address.</span></span></param>
        <param name="factorySettings"><span data-ttu-id="531b9-212">Die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="531b9-212">The <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> settings.</span></span></param>
        <summary><span data-ttu-id="531b9-213">Erstellt asynchron ein neue messaging Factory-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-213">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="531b9-214">Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-214">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (Uri address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Uri address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Uri,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Uri * Microsoft.ServiceBus.TokenProvider -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (address, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="531b9-215">Die Basisadresse des Namespace.</span><span class="sxs-lookup"><span data-stu-id="531b9-215">The namespace base address.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="531b9-216">Der Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="531b9-216">The token provider.</span></span></param>
        <summary><span data-ttu-id="531b9-217">Erstellt asynchron ein neue messaging Factory-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-217">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="531b9-218">Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-218">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubClient CreateEventHubClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubClient CreateEventHubClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateEventHubClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubClient (path As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubClient : string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="messagingFactory.CreateEventHubClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="531b9-219">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="531b9-219">The path to the Event Hub.</span></span></param>
        <summary><span data-ttu-id="531b9-220">Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> -Objekt unter Verwendung des angegebenen Pfads.</span><span class="sxs-lookup"><span data-stu-id="531b9-220">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> object using the specified path.</span></span></summary>
        <returns><span data-ttu-id="531b9-221">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-221">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="531b9-222">Wird ausgelöst, wenn <paramref name="path" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="531b9-222">Thrown if <paramref name="path" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="531b9-223">Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="531b9-223">The connection string.</span></span></param>
        <summary><span data-ttu-id="531b9-224">Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt von einer Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="531b9-224">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object from a connection string.</span></span></summary>
        <returns><span data-ttu-id="531b9-225">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-225">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageReceiver CreateMessageReceiver (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageReceiver CreateMessageReceiver(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageReceiver(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageReceiver (entityPath As String) As MessageReceiver" />
      <MemberSignature Language="F#" Value="member this.CreateMessageReceiver : string -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="messagingFactory.CreateMessageReceiver entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="531b9-226">Der Pfad der Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-226">The path of the entity.</span></span></param>
        <summary><span data-ttu-id="531b9-227">Erstellt einen Empfänger einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="531b9-227">Creates a message receiver.</span></span></summary>
        <returns><span data-ttu-id="531b9-228">Die neu erstellte Nachrichtenempfänger.</span><span class="sxs-lookup"><span data-stu-id="531b9-228">The newly created message receiver.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageReceiver CreateMessageReceiver (string entityPath, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageReceiver CreateMessageReceiver(string entityPath, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="messagingFactory.CreateMessageReceiver (entityPath, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="531b9-229">Der Pfad der Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-229">The path of the entity.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="531b9-230">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="531b9-230">The receive mode.</span></span></param>
        <summary><span data-ttu-id="531b9-231">Erstellt einen Empfänger einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="531b9-231">Creates a message receiver.</span></span></summary>
        <returns><span data-ttu-id="531b9-232">Die neu erstellte Nachrichtenempfänger.</span><span class="sxs-lookup"><span data-stu-id="531b9-232">The newly created message receiver.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt; CreateMessageReceiverAsync (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageReceiver&gt; CreateMessageReceiverAsync(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageReceiverAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageReceiverAsync (entityPath As String) As Task(Of MessageReceiver)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageReceiverAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt;" Usage="messagingFactory.CreateMessageReceiverAsync entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="531b9-233">Der Pfad der Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-233">The path of the entity.</span></span></param>
        <summary><span data-ttu-id="531b9-234">Erstellt asynchron einen Empfänger einer Nachricht ein.</span><span class="sxs-lookup"><span data-stu-id="531b9-234">Asynchronously creates a message receiver.</span></span></summary>
        <returns><span data-ttu-id="531b9-235">Eine Taskinstanz, die der asynchrone Erstellvorgang Nachricht Empfänger darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-235">A task instance that represents the asynchronous create message receiver operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt; CreateMessageReceiverAsync (string entityPath, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageReceiver&gt; CreateMessageReceiverAsync(string entityPath, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageReceiverAsync(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageReceiverAsync : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt;" Usage="messagingFactory.CreateMessageReceiverAsync (entityPath, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="531b9-236">Der Pfad der Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-236">The path of the entity.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="531b9-237">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="531b9-237">The receive mode.</span></span></param>
        <summary><span data-ttu-id="531b9-238">Erstellt asynchron einen Empfänger einer Nachricht ein.</span><span class="sxs-lookup"><span data-stu-id="531b9-238">Asynchronously creates a message receiver.</span></span></summary>
        <returns><span data-ttu-id="531b9-239">Eine Taskinstanz, die der asynchrone Erstellvorgang Nachricht Empfänger darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-239">A task instance that represents the asynchronous create message receiver operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSender">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSender CreateMessageSender (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageSender CreateMessageSender(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageSender(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageSender (entityPath As String) As MessageSender" />
      <MemberSignature Language="F#" Value="member this.CreateMessageSender : string -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.CreateMessageSender entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="531b9-240">Der Pfad der Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-240">The path of the entity.</span></span></param>
        <summary><span data-ttu-id="531b9-241">Erstellt den Absender einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="531b9-241">Creates a message sender.</span></span></summary>
        <returns><span data-ttu-id="531b9-242">Der Absender der neu erstellte Nachricht.</span><span class="sxs-lookup"><span data-stu-id="531b9-242">The newly created message sender.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSender">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSender CreateMessageSender (string transferDestinationEntityPath, string viaEntityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageSender CreateMessageSender(string transferDestinationEntityPath, string viaEntityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageSender(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageSender (transferDestinationEntityPath As String, viaEntityPath As String) As MessageSender" />
      <MemberSignature Language="F#" Value="member this.CreateMessageSender : string * string -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.CreateMessageSender (transferDestinationEntityPath, viaEntityPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transferDestinationEntityPath" Type="System.String" />
        <Parameter Name="viaEntityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transferDestinationEntityPath"><span data-ttu-id="531b9-243">Der Pfad der Übertragung Ziel-Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-243">The transfer destination entity path.</span></span></param>
        <param name="viaEntityPath"><span data-ttu-id="531b9-244">Der Pfad über Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-244">The via-entity path.</span></span></param>
        <summary><span data-ttu-id="531b9-245">Erstellt den Absender einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="531b9-245">Creates a message sender.</span></span></summary>
        <returns><span data-ttu-id="531b9-246">Das erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-246">The created <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSenderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateMessageSenderAsync (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateMessageSenderAsync(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageSenderAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageSenderAsync (entityPath As String) As Task(Of MessageSender)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageSenderAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;" Usage="messagingFactory.CreateMessageSenderAsync entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="531b9-247">Der Pfad der Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-247">The path of the entity.</span></span></param>
        <summary><span data-ttu-id="531b9-248">Erstellt asynchron den Absender einer Nachricht ein.</span><span class="sxs-lookup"><span data-stu-id="531b9-248">Asynchronously creates a message sender.</span></span></summary>
        <returns><span data-ttu-id="531b9-249">Eine Taskinstanz, die der asynchrone Erstellvorgang Nachricht Absender darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-249">A task instance that represents the asynchronous create message sender operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSenderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateMessageSenderAsync (string transferDestinationEntityPath, string viaEntityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateMessageSenderAsync(string transferDestinationEntityPath, string viaEntityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageSenderAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageSenderAsync (transferDestinationEntityPath As String, viaEntityPath As String) As Task(Of MessageSender)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageSenderAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;" Usage="messagingFactory.CreateMessageSenderAsync (transferDestinationEntityPath, viaEntityPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transferDestinationEntityPath" Type="System.String" />
        <Parameter Name="viaEntityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transferDestinationEntityPath"><span data-ttu-id="531b9-250">Der Pfad der Übertragung Ziel-Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-250">The transfer destination entity path.</span></span></param>
        <param name="viaEntityPath"><span data-ttu-id="531b9-251">Der Pfad über Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-251">The via-entity path.</span></span></param>
        <summary><span data-ttu-id="531b9-252">Erstellt asynchron den Absender einer Nachricht ein.</span><span class="sxs-lookup"><span data-stu-id="531b9-252">Asynchronously creates a message sender.</span></span></summary>
        <returns><span data-ttu-id="531b9-253">Eine Taskinstanz, die der asynchrone Erstellvorgang Nachricht Absender darstellt.</span><span class="sxs-lookup"><span data-stu-id="531b9-253">A task instance that represents the asynchronous create message sender operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQueueClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueClient CreateQueueClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueClient CreateQueueClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateQueueClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQueueClient (path As String) As QueueClient" />
      <MemberSignature Language="F#" Value="member this.CreateQueueClient : string -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="messagingFactory.CreateQueueClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="531b9-254">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="531b9-254">The path of the queue relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="531b9-255">Erstellt einen neue warteschlangenclient.</span><span class="sxs-lookup"><span data-stu-id="531b9-255">Creates a new queue client.</span></span></summary>
        <returns><span data-ttu-id="531b9-256">Die neu erstellte Anwendungswarteschlangen-Client.</span><span class="sxs-lookup"><span data-stu-id="531b9-256">The newly created queue client.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="531b9-257"><paramref name="path" />ist null oder leer.</span><span class="sxs-lookup"><span data-stu-id="531b9-257"><paramref name="path" /> is null or empty.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <span data-ttu-id="531b9-258"><paramref name="path" />Länge ist größer als <see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />.</span><span class="sxs-lookup"><span data-stu-id="531b9-258"><paramref name="path" /> length is greater than <see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="531b9-259">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-259">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> object.</span></span> <span data-ttu-id="531b9-260">Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="531b9-260">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="531b9-261">Ein interner Fehler oder unerwartete Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="531b9-261">An internal error or unexpected exception occurs.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="531b9-262">Die Factory wurde geschlossen oder abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="531b9-262">The factory has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateQueueClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueClient CreateQueueClient (string path, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueClient CreateQueueClient(string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateQueueClient(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="member this.CreateQueueClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="messagingFactory.CreateQueueClient (path, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="531b9-263">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="531b9-263">The path of the queue relative to the service namespace base address.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="531b9-264">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="531b9-264">The receive mode.</span></span></param>
        <summary><span data-ttu-id="531b9-265">Erstellt einen neue warteschlangenclient.</span><span class="sxs-lookup"><span data-stu-id="531b9-265">Creates a new queue client.</span></span></summary>
        <returns><span data-ttu-id="531b9-266">Die neu erstellte Anwendungswarteschlangen-Client.</span><span class="sxs-lookup"><span data-stu-id="531b9-266">The newly created queue client.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="531b9-267"><paramref name="path" />ist null oder leer.</span><span class="sxs-lookup"><span data-stu-id="531b9-267"><paramref name="path" /> is null or empty.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <span data-ttu-id="531b9-268"><paramref name="path" />Länge ist größer als <see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />.</span><span class="sxs-lookup"><span data-stu-id="531b9-268"><paramref name="path" /> length is greater than <see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="531b9-269">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-269">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> object.</span></span> <span data-ttu-id="531b9-270">Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="531b9-270">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="531b9-271">Ein interner Fehler oder unerwartete Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="531b9-271">An internal error or unexpected exception occurs.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="531b9-272">Die Factory wurde geschlossen oder abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="531b9-272">The factory has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionClient CreateSubscriptionClient (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateSubscriptionClient(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateSubscriptionClient(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSubscriptionClient (topicPath As String, name As String) As SubscriptionClient" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionClient : string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="messagingFactory.CreateSubscriptionClient (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="531b9-273">Der Themenname relativ zu den Dienstnamespace.</span><span class="sxs-lookup"><span data-stu-id="531b9-273">The topic path relative to the service namespace.</span></span></param>
        <param name="name"><span data-ttu-id="531b9-274">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="531b9-274">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="531b9-275">Erstellt einen abonnementclient.</span><span class="sxs-lookup"><span data-stu-id="531b9-275">Creates a subscription client.</span></span></summary>
        <returns><span data-ttu-id="531b9-276">Der Client neu erstellte Abonnement.</span><span class="sxs-lookup"><span data-stu-id="531b9-276">The newly created subscription client.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="531b9-277">Die angegebene <paramref name="topicPath" /> ist null oder leer.</span><span class="sxs-lookup"><span data-stu-id="531b9-277">The supplied <paramref name="topicPath" /> is null or empty.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="531b9-278">Die Länge des <paramref name="topicPath" /> ist größer als <see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />.</span><span class="sxs-lookup"><span data-stu-id="531b9-278">The length of <paramref name="topicPath" /> is greater than <see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="531b9-279">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-279">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> object.</span></span> <span data-ttu-id="531b9-280">Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="531b9-280">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="531b9-281">Ein interner Fehler oder unerwartete Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="531b9-281">An internal error or unexpected exception occurs.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="531b9-282">Die Factory wurde geschlossen oder abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="531b9-282">The factory has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionClient CreateSubscriptionClient (string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateSubscriptionClient(string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateSubscriptionClient(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionClient : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="messagingFactory.CreateSubscriptionClient (topicPath, name, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="531b9-283">Der Themenname relativ zu den Dienstnamespace.</span><span class="sxs-lookup"><span data-stu-id="531b9-283">The topic path relative to the service namespace.</span></span></param>
        <param name="name"><span data-ttu-id="531b9-284">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="531b9-284">The name of the subscription.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="531b9-285">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="531b9-285">The receive mode.</span></span></param>
        <summary><span data-ttu-id="531b9-286">Erstellt einen neuen abonnementclient.</span><span class="sxs-lookup"><span data-stu-id="531b9-286">Creates a new subscription client.</span></span></summary>
        <returns><span data-ttu-id="531b9-287">Der Client neu erstellte Abonnement.</span><span class="sxs-lookup"><span data-stu-id="531b9-287">The newly created subscription client.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="531b9-288">Die angegebene <paramref name="topicPath" /> ist null oder leer.</span><span class="sxs-lookup"><span data-stu-id="531b9-288">The supplied <paramref name="topicPath" /> is null or empty.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="531b9-289">Die Länge des <paramref name="topicPath" /> ist größer als <see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />.</span><span class="sxs-lookup"><span data-stu-id="531b9-289">The length of <paramref name="topicPath" /> is greater than <see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="531b9-290">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-290">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> object.</span></span> <span data-ttu-id="531b9-291">Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="531b9-291">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="531b9-292">Ein interner Fehler oder unerwartete Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="531b9-292">An internal error or unexpected exception occurs.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="531b9-293">Die Factory wurde geschlossen oder abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="531b9-293">The factory has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateTopicClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicClient CreateTopicClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicClient CreateTopicClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateTopicClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTopicClient (path As String) As TopicClient" />
      <MemberSignature Language="F#" Value="member this.CreateTopicClient : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="messagingFactory.CreateTopicClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="531b9-294">Der Themenname relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="531b9-294">The topic path relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="531b9-295">Erstellt einen neuen themenclient.</span><span class="sxs-lookup"><span data-stu-id="531b9-295">Creates a new topic client.</span></span></summary>
        <returns><span data-ttu-id="531b9-296">Die neu erstellte themenclient.</span><span class="sxs-lookup"><span data-stu-id="531b9-296">The newly created topic client.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="531b9-297">Die angegebene <paramref name="path" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="531b9-297">The supplied <paramref name="path" /> is null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="531b9-298">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-298">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> object.</span></span> <span data-ttu-id="531b9-299">Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="531b9-299">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="531b9-300">Ein interner Fehler oder unerwartete Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="531b9-300">An internal error or unexpected exception occurs.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="531b9-301">Die Factory wurde geschlossen oder abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="531b9-301">The factory has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingFactorySettings GetSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessagingFactorySettings GetSettings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.GetSettings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSettings () As MessagingFactorySettings" />
      <MemberSignature Language="F#" Value="member this.GetSettings : unit -&gt; Microsoft.ServiceBus.Messaging.MessagingFactorySettings" Usage="messagingFactory.GetSettings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactorySettings</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="531b9-302">Ruft eine Kopie der Einstellungen der messaging-Factory.</span><span class="sxs-lookup"><span data-stu-id="531b9-302">Retrieves a copy of the settings of the messaging factory.</span></span></summary>
        <returns><span data-ttu-id="531b9-303">Eine Kopie des messaging Factory-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="531b9-303">A copy of the messaging factory settings.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncrementConnectionResetCount">
      <MemberSignature Language="C#" Value="protected void IncrementConnectionResetCount (Uri endpoint);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void IncrementConnectionResetCount(class System.Uri endpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.IncrementConnectionResetCount(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub IncrementConnectionResetCount (endpoint As Uri)" />
      <MemberSignature Language="F#" Value="member this.IncrementConnectionResetCount : Uri -&gt; unit" Usage="messagingFactory.IncrementConnectionResetCount endpoint" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="endpoint"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NamespaceEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Uri&gt; NamespaceEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; NamespaceEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactory.NamespaceEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NamespaceEndpoints As IEnumerable(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.NamespaceEndpoints : seq&lt;Uri&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.NamespaceEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="531b9-304">Ruft eine Liste der Endpunkte des Namespace ab.</span><span class="sxs-lookup"><span data-stu-id="531b9-304">Gets a list of namespace endpoints.</span></span></summary>
        <value><span data-ttu-id="531b9-305">Eine Liste von Namespace-Endpunkten.</span><span class="sxs-lookup"><span data-stu-id="531b9-305">A list of namespace endpoints.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="messagingFactory.OnAbort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="531b9-306">Führt die Aktion abbrechen.</span><span class="sxs-lookup"><span data-stu-id="531b9-306">Executes the abort action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageSession OnAcceptMessageSession (Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan serverWaitTime, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnAcceptMessageSession(valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan serverWaitTime, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnAcceptMessageSession(Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnAcceptMessageSession : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.OnAcceptMessageSession : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.OnAcceptMessageSession (receiveMode, serverWaitTime, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="receiveMode"><span data-ttu-id="531b9-307">Die Nachricht Empfangsmodus.</span><span class="sxs-lookup"><span data-stu-id="531b9-307">The message receive mode.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="531b9-308">Die Wartezeit des Servers.</span><span class="sxs-lookup"><span data-stu-id="531b9-308">The server wait time.</span></span></param>
        <param name="timeout"><span data-ttu-id="531b9-309">Das Timeout für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="531b9-309">The operation timeout.</span></span></param>
        <summary><span data-ttu-id="531b9-310">Führt der meldungssitzung akzeptieren.</span><span class="sxs-lookup"><span data-stu-id="531b9-310">Executes the accept message session.</span></span></summary>
        <returns><span data-ttu-id="531b9-311">Die nachrichtensitzung ausgeführten.</span><span class="sxs-lookup"><span data-stu-id="531b9-311">The executed message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAcceptSessionReceiver">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageSession OnAcceptSessionReceiver (string entityName, string sessionId, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnAcceptSessionReceiver(string entityName, string sessionId, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnAcceptSessionReceiver(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnAcceptSessionReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.OnAcceptSessionReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.OnAcceptSessionReceiver (entityName, sessionId, receiveMode, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="531b9-312">Der Name der Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-312">The name of the entity.</span></span></param>
        <param name="sessionId"><span data-ttu-id="531b9-313">Die Sitzungs-ID.</span><span class="sxs-lookup"><span data-stu-id="531b9-313">The session identifier.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="531b9-314">Die Nachricht Empfangsmodus.</span><span class="sxs-lookup"><span data-stu-id="531b9-314">The message receive mode.</span></span></param>
        <param name="timeout"><span data-ttu-id="531b9-315">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="531b9-315">The wait time before the operation times out.</span></span></param>
        <summary><span data-ttu-id="531b9-316">Führt eine Aktion Empfänger Sitzung annehmen.</span><span class="sxs-lookup"><span data-stu-id="531b9-316">Executes the accept session receiver action.</span></span></summary>
        <returns><span data-ttu-id="531b9-317">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen verweist akzeptieren Sitzung Empfänger Aktion.</span><span class="sxs-lookup"><span data-stu-id="531b9-317">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous accept session receiver action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAcceptMessageSession (Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan serverWaitTime, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAcceptMessageSession(valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan serverWaitTime, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginAcceptMessageSession(Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAcceptMessageSession : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginAcceptMessageSession (receiveMode, serverWaitTime, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="receiveMode"><span data-ttu-id="531b9-318">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="531b9-318">The receive mode.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="531b9-319">Die Wartezeit des Servers.</span><span class="sxs-lookup"><span data-stu-id="531b9-319">The server wait time.</span></span></param>
        <param name="timeout"><span data-ttu-id="531b9-320">Das Timeout für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="531b9-320">The operation timeout.</span></span></param>
        <param name="callback"><span data-ttu-id="531b9-321">Der asynchrone Rückruf.</span><span class="sxs-lookup"><span data-stu-id="531b9-321">The asynchronous callback.</span></span></param>
        <param name="state"><span data-ttu-id="531b9-322">der Sitzungsstatus.</span><span class="sxs-lookup"><span data-stu-id="531b9-322">The session state.</span></span></param>
        <summary><span data-ttu-id="531b9-323">Führt die Begin Sitzung Nachrichtenaktion akzeptieren.</span><span class="sxs-lookup"><span data-stu-id="531b9-323">Executes the begin accept message session action.</span></span></summary>
        <returns><span data-ttu-id="531b9-324">Das asynchrone Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="531b9-324">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAcceptSessionReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAcceptSessionReceiver (string entityName, string sessionId, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAcceptSessionReceiver(string entityName, string sessionId, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginAcceptSessionReceiver(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAcceptSessionReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginAcceptSessionReceiver (entityName, sessionId, receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="531b9-325">Der Name der Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-325">The name of the entity.</span></span></param>
        <param name="sessionId"><span data-ttu-id="531b9-326">Die Sitzungs-ID.</span><span class="sxs-lookup"><span data-stu-id="531b9-326">The session identifier.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="531b9-327">Die Nachricht Empfangsmodus.</span><span class="sxs-lookup"><span data-stu-id="531b9-327">The message receive mode.</span></span></param>
        <param name="timeout"><span data-ttu-id="531b9-328">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="531b9-328">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="531b9-329">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="531b9-329">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="531b9-330">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="531b9-330">A user-defined object that contains information about the receive operation.</span></span></param>
        <summary><span data-ttu-id="531b9-331">Führt die Begin Sitzung Empfänger Aktion annehmen.</span><span class="sxs-lookup"><span data-stu-id="531b9-331">Executes the begin accept session receiver action.</span></span></summary>
        <returns><span data-ttu-id="531b9-332">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen verweist akzeptieren Sitzung Empfänger Aktion.</span><span class="sxs-lookup"><span data-stu-id="531b9-332">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous accept session receiver action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginClose (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="531b9-333">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="531b9-333">The timeout.</span></span></param>
        <param name="callback"><span data-ttu-id="531b9-334">Der Rückruf.</span><span class="sxs-lookup"><span data-stu-id="531b9-334">The callback.</span></span></param>
        <param name="state"><span data-ttu-id="531b9-335">Der Zustand.</span><span class="sxs-lookup"><span data-stu-id="531b9-335">The state.</span></span></param>
        <summary><span data-ttu-id="531b9-336">Führt die Aktion "Schließen" beginnen.</span><span class="sxs-lookup"><span data-stu-id="531b9-336">Executes the begin close action.</span></span></summary>
        <returns><span data-ttu-id="531b9-337">Ein <see cref="T:System.IAsyncResult" /> Objekt, das die asynchrone Aktion "Schließen" verweist.</span><span class="sxs-lookup"><span data-stu-id="531b9-337">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous close action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateMessageReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateMessageReceiver (string entityName, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateMessageReceiver(string entityName, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginCreateMessageReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateMessageReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginCreateMessageReceiver (entityName, receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="531b9-338">Der Name der Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-338">The name of the entity.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="531b9-339">Die Nachricht Empfangsmodus.</span><span class="sxs-lookup"><span data-stu-id="531b9-339">The message receive mode.</span></span></param>
        <param name="timeout"><span data-ttu-id="531b9-340">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="531b9-340">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="531b9-341">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="531b9-341">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="531b9-342">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="531b9-342">A user-defined object that contains information about the receive operation.</span></span></param>
        <summary><span data-ttu-id="531b9-343">Führt die Begin Empfänger Nachrichtenaktion zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="531b9-343">Executes the begin create message receiver action.</span></span></summary>
        <returns><span data-ttu-id="531b9-344">Ein <see cref="T:System.IAsyncResult" /> Objekt, das die asynchrone Nachricht Empfänger Erstellungsaktion verweist.</span><span class="sxs-lookup"><span data-stu-id="531b9-344">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous create message receiver action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateMessageSender">
      <MemberSignature Language="C#" Value="protected virtual IAsyncResult OnBeginCreateMessageSender (string entityName, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateMessageSender(string entityName, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginCreateMessageSender(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnBeginCreateMessageSender (entityName As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateMessageSender : string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult&#xA;override this.OnBeginCreateMessageSender : string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginCreateMessageSender (entityName, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="531b9-345">Der Name der Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-345">The name of the entity.</span></span></param>
        <param name="timeout"><span data-ttu-id="531b9-346">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="531b9-346">The timeout.</span></span></param>
        <param name="callback"><span data-ttu-id="531b9-347">Der Rückruf.</span><span class="sxs-lookup"><span data-stu-id="531b9-347">The callback.</span></span></param>
        <param name="state"><span data-ttu-id="531b9-348">Der Zustand.</span><span class="sxs-lookup"><span data-stu-id="531b9-348">The state.</span></span></param>
        <summary><span data-ttu-id="531b9-349">Führt die Begin Absender Nachrichtenaktion zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="531b9-349">Executes the begin create message sender action.</span></span></summary>
        <returns><span data-ttu-id="531b9-350">Ein <see cref="T:System.IAsyncResult" /> Objekt, das die asynchrone Nachricht Absender Erstellungsaktion verweist.</span><span class="sxs-lookup"><span data-stu-id="531b9-350">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous create message sender action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateMessageSender">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateMessageSender (string transferDestinationEntityName, string viaEntityName, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateMessageSender(string transferDestinationEntityName, string viaEntityName, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginCreateMessageSender(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginCreateMessageSender (transferDestinationEntityName As String, viaEntityName As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateMessageSender : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginCreateMessageSender (transferDestinationEntityName, viaEntityName, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transferDestinationEntityName" Type="System.String" />
        <Parameter Name="viaEntityName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="transferDestinationEntityName"><span data-ttu-id="531b9-351">Der Name der Zielentität übertragen.</span><span class="sxs-lookup"><span data-stu-id="531b9-351">The name of the transfer destination entity.</span></span></param>
        <param name="viaEntityName"><span data-ttu-id="531b9-352">Der Name des via-Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-352">The via-entity name.</span></span></param>
        <param name="timeout"><span data-ttu-id="531b9-353">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="531b9-353">The timeout.</span></span></param>
        <param name="callback"><span data-ttu-id="531b9-354">Die Rückruf-Meldung.</span><span class="sxs-lookup"><span data-stu-id="531b9-354">The callback message.</span></span></param>
        <param name="state"><span data-ttu-id="531b9-355">Der Zustand.</span><span class="sxs-lookup"><span data-stu-id="531b9-355">The state.</span></span></param>
        <summary><span data-ttu-id="531b9-356">Führt die Begin Absender Nachrichtenaktion zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="531b9-356">Executes the begin create message sender action.</span></span></summary>
        <returns><span data-ttu-id="531b9-357">Ein <see cref="T:System.IAsyncResult" /> Objekt, das die asynchrone Nachricht Absender Erstellungsaktion verweist.</span><span class="sxs-lookup"><span data-stu-id="531b9-357">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous create message sender action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="messagingFactory.OnClose timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="531b9-358">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="531b9-358">The timeout.</span></span></param>
        <summary><span data-ttu-id="531b9-359">Führt die Aktion "Schließen".</span><span class="sxs-lookup"><span data-stu-id="531b9-359">Executes the close action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateEventHubClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.EventHubClient OnCreateEventHubClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.EventHubClient OnCreateEventHubClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateEventHubClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCreateEventHubClient (path As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="abstract member OnCreateEventHubClient : string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient&#xA;override this.OnCreateEventHubClient : string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="messagingFactory.OnCreateEventHubClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="531b9-360">Der Pfad der Event Hub-Clients.</span><span class="sxs-lookup"><span data-stu-id="531b9-360">The path of the event hub client.</span></span></param>
        <summary><span data-ttu-id="531b9-361">Führt die Ereignis-Hub Client Erstellungsaktion.</span><span class="sxs-lookup"><span data-stu-id="531b9-361">Executes the create event hub client action.</span></span></summary>
        <returns><span data-ttu-id="531b9-362">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />.</span><span class="sxs-lookup"><span data-stu-id="531b9-362">The created <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateMessageReceiver">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageReceiver OnCreateMessageReceiver (string entityName, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageReceiver OnCreateMessageReceiver(string entityName, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateMessageReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateMessageReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver&#xA;override this.OnCreateMessageReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="messagingFactory.OnCreateMessageReceiver (entityName, receiveMode, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="531b9-363">Der Name der Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-363">The name of the entity.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="531b9-364">Die Nachricht Empfangsmodus.</span><span class="sxs-lookup"><span data-stu-id="531b9-364">The message receive mode.</span></span></param>
        <param name="timeout"><span data-ttu-id="531b9-365">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="531b9-365">The timeout.</span></span></param>
        <summary><span data-ttu-id="531b9-366">Führt die Message-Empfänger Erstellungsaktion.</span><span class="sxs-lookup"><span data-stu-id="531b9-366">Executes the create message receiver action.</span></span></summary>
        <returns><span data-ttu-id="531b9-367">Ein <see cref="T:System.IAsyncResult" /> Objekt, das die asynchrone Nachricht Empfänger Erstellungsaktion verweist.</span><span class="sxs-lookup"><span data-stu-id="531b9-367">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous create message receiver action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateMessageSender">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageSender OnCreateMessageSender (string entityName, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnCreateMessageSender(string entityName, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateMessageSender(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCreateMessageSender (entityName As String, timeout As TimeSpan) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnCreateMessageSender : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSender&#xA;override this.OnCreateMessageSender : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.OnCreateMessageSender (entityName, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="531b9-368">Der Name der Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-368">The name of the entity.</span></span></param>
        <param name="timeout"><span data-ttu-id="531b9-369">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="531b9-369">The timeout.</span></span></param>
        <summary><span data-ttu-id="531b9-370">Führt die Nachrichten-Absender Erstellungsaktion.</span><span class="sxs-lookup"><span data-stu-id="531b9-370">Executes the create message sender action.</span></span></summary>
        <returns><span data-ttu-id="531b9-371">Ein <see cref="T:System.IAsyncResult" /> Objekt, das die asynchrone Nachricht Absender Erstellungsaktion verweist.</span><span class="sxs-lookup"><span data-stu-id="531b9-371">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous create message sender action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateMessageSender">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageSender OnCreateMessageSender (string transferDestinationEntityName, string viaEntityName, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnCreateMessageSender(string transferDestinationEntityName, string viaEntityName, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateMessageSender(System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCreateMessageSender (transferDestinationEntityName As String, viaEntityName As String, timeout As TimeSpan) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnCreateMessageSender : string * string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSender&#xA;override this.OnCreateMessageSender : string * string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.OnCreateMessageSender (transferDestinationEntityName, viaEntityName, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transferDestinationEntityName" Type="System.String" />
        <Parameter Name="viaEntityName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="transferDestinationEntityName"><span data-ttu-id="531b9-372">Der Name der Zielentität übertragen.</span><span class="sxs-lookup"><span data-stu-id="531b9-372">The name of the transfer destination entity.</span></span></param>
        <param name="viaEntityName"><span data-ttu-id="531b9-373">Der Name des via-Entität.</span><span class="sxs-lookup"><span data-stu-id="531b9-373">The via-entity name.</span></span></param>
        <param name="timeout"><span data-ttu-id="531b9-374">Das Timeout der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="531b9-374">The message timeout.</span></span></param>
        <summary><span data-ttu-id="531b9-375">Führt die Nachrichten-Absender Erstellungsaktion.</span><span class="sxs-lookup"><span data-stu-id="531b9-375">Executes the create message sender action.</span></span></summary>
        <returns><span data-ttu-id="531b9-376">Die ausgeführte <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> Aktion.</span><span class="sxs-lookup"><span data-stu-id="531b9-376">The executed <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateQueueClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.QueueClient OnCreateQueueClient (string path, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.QueueClient OnCreateQueueClient(string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateQueueClient(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateQueueClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient&#xA;override this.OnCreateQueueClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="messagingFactory.OnCreateQueueClient (path, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="531b9-377">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="531b9-377">The path of the queue relative to the service namespace base address.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="531b9-378">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="531b9-378">The receive mode.</span></span></param>
        <summary><span data-ttu-id="531b9-379">Führt eine Aktion Client Warteschlange erstellen.</span><span class="sxs-lookup"><span data-stu-id="531b9-379">Executes the create queue client action.</span></span></summary>
        <returns><span data-ttu-id="531b9-380">Die neu erstellte Anwendungswarteschlangen-Client.</span><span class="sxs-lookup"><span data-stu-id="531b9-380">The newly created queue client.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateSubscriptionClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.SubscriptionClient OnCreateSubscriptionClient (string subscriptionPath, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.SubscriptionClient OnCreateSubscriptionClient(string subscriptionPath, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateSubscriptionClient(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateSubscriptionClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient&#xA;override this.OnCreateSubscriptionClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="messagingFactory.OnCreateSubscriptionClient (subscriptionPath, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subscriptionPath" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="subscriptionPath"><span data-ttu-id="531b9-381">Der Pfad des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="531b9-381">The subscription path.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="531b9-382">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="531b9-382">The receive mode.</span></span></param>
        <summary><span data-ttu-id="531b9-383">Führt eine Abonnement-Client Erstellungsaktion.</span><span class="sxs-lookup"><span data-stu-id="531b9-383">Executes a create subscription client action.</span></span></summary>
        <returns><span data-ttu-id="531b9-384">Ein Client neu erstellte Abonnement.</span><span class="sxs-lookup"><span data-stu-id="531b9-384">A newly created subscription client.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateSubscriptionClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.SubscriptionClient OnCreateSubscriptionClient (string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.SubscriptionClient OnCreateSubscriptionClient(string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateSubscriptionClient(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateSubscriptionClient : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient&#xA;override this.OnCreateSubscriptionClient : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="messagingFactory.OnCreateSubscriptionClient (topicPath, name, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="531b9-385">Der Pfad des Abonnements relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="531b9-385">The path of the subscription relative to the service namespace base address.</span></span></param>
        <param name="name"><span data-ttu-id="531b9-386">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="531b9-386">The name of the subscription.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="531b9-387">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="531b9-387">The receive mode.</span></span></param>
        <summary><span data-ttu-id="531b9-388">Führt eine Abonnement-Client Erstellungsaktion.</span><span class="sxs-lookup"><span data-stu-id="531b9-388">Executes a create subscription client action.</span></span></summary>
        <returns><span data-ttu-id="531b9-389">Ein Client neu erstellte Abonnement.</span><span class="sxs-lookup"><span data-stu-id="531b9-389">A newly created subscription client.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateTopicClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.TopicClient OnCreateTopicClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.TopicClient OnCreateTopicClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateTopicClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCreateTopicClient (path As String) As TopicClient" />
      <MemberSignature Language="F#" Value="abstract member OnCreateTopicClient : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient&#xA;override this.OnCreateTopicClient : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="messagingFactory.OnCreateTopicClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="531b9-390">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="531b9-390">The path of the topic relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="531b9-391">Führt eine Aktion Client Thema erstellen.</span><span class="sxs-lookup"><span data-stu-id="531b9-391">Executes the create topic client action.</span></span></summary>
        <returns><span data-ttu-id="531b9-392">Die neu erstellte themenclient.</span><span class="sxs-lookup"><span data-stu-id="531b9-392">The newly created topic client.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndAcceptMessageSession(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndAcceptMessageSession (result As IAsyncResult) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member OnEndAcceptMessageSession : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.OnEndAcceptMessageSession result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="531b9-393">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="531b9-393">The result of the operation.</span></span></param>
        <summary><span data-ttu-id="531b9-394">Führt die End-Sitzung Nachrichtenaktion akzeptieren.</span><span class="sxs-lookup"><span data-stu-id="531b9-394">Executes the end accept message session action.</span></span></summary>
        <returns><span data-ttu-id="531b9-395">Die ausgeführte <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Aktion.</span><span class="sxs-lookup"><span data-stu-id="531b9-395">The executed <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAcceptSessionReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptSessionReceiver (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptSessionReceiver(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndAcceptSessionReceiver(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndAcceptSessionReceiver (result As IAsyncResult) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member OnEndAcceptSessionReceiver : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.OnEndAcceptSessionReceiver result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="531b9-396">Ein <see cref="T:System.IAsyncResult" /> -Objekt, das Zustandsinformationen und benutzerdefinierte Daten für diesen asynchronen Vorgang speichert.</span><span class="sxs-lookup"><span data-stu-id="531b9-396">An <see cref="T:System.IAsyncResult" /> object that stores state information and any user-defined data for this asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="531b9-397">Führt das Ende Sitzung Empfänger Aktion annehmen.</span><span class="sxs-lookup"><span data-stu-id="531b9-397">Executes the end accept session receiver action.</span></span></summary>
        <returns><span data-ttu-id="531b9-398">Die ausgeführte <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="531b9-398">The executed <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="messagingFactory.OnEndClose result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="531b9-399">Das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="531b9-399">The result.</span></span></param>
        <summary><span data-ttu-id="531b9-400">Führt die End-Aktion "Schließen".</span><span class="sxs-lookup"><span data-stu-id="531b9-400">Executes the end close action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateMessageReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateMessageReceiver (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateMessageReceiver(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndCreateMessageReceiver(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateMessageReceiver (result As IAsyncResult) As MessageReceiver" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateMessageReceiver : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="messagingFactory.OnEndCreateMessageReceiver result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="531b9-401">Das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="531b9-401">The result.</span></span></param>
        <summary><span data-ttu-id="531b9-402">Führt das Ende Empfänger Nachrichtenaktion zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="531b9-402">Executes the end create message receiver action.</span></span></summary>
        <returns><span data-ttu-id="531b9-403">Die ausgeführte <see cref="T:Microsoft.ServiceBus.Messaging.MessageReceiver" /> Aktion.</span><span class="sxs-lookup"><span data-stu-id="531b9-403">The executed <see cref="T:Microsoft.ServiceBus.Messaging.MessageReceiver" /> action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateMessageSender">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateMessageSender (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateMessageSender(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndCreateMessageSender(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateMessageSender (result As IAsyncResult) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateMessageSender : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.OnEndCreateMessageSender result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="531b9-404">Das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="531b9-404">The result.</span></span></param>
        <summary><span data-ttu-id="531b9-405">Führt das Ende Absender Nachrichtenaktion zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="531b9-405">Executes the end create message sender action.</span></span></summary>
        <returns><span data-ttu-id="531b9-406">Die ausgeführte <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> Aktion.</span><span class="sxs-lookup"><span data-stu-id="531b9-406">The executed <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PairNamespaceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PairNamespaceAsync (Microsoft.ServiceBus.Messaging.PairedNamespaceOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PairNamespaceAsync(class Microsoft.ServiceBus.Messaging.PairedNamespaceOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.PairNamespaceAsync(Microsoft.ServiceBus.Messaging.PairedNamespaceOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function PairNamespaceAsync (options As PairedNamespaceOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.PairNamespaceAsync : Microsoft.ServiceBus.Messaging.PairedNamespaceOptions -&gt; System.Threading.Tasks.Task" Usage="messagingFactory.PairNamespaceAsync options" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="531b9-407">Die ereignispaarbildung Optionen.</span><span class="sxs-lookup"><span data-stu-id="531b9-407">The pairing options.</span></span></param>
        <summary><span data-ttu-id="531b9-408">Asynchron einen Namespace-Paaren.</span><span class="sxs-lookup"><span data-stu-id="531b9-408">Asynchronously pairs a namespace.</span></span></summary>
        <returns><span data-ttu-id="531b9-409">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="531b9-409">The result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public virtual int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactory.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="531b9-410">Ruft ab oder legt die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="531b9-410">Gets or sets the number of messages that the message receiver can simultaneously request.</span></span></summary>
        <value><span data-ttu-id="531b9-411">Die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="531b9-411">The number of messages that the message receiver can simultaneously request.</span></span></value>
        <remarks> <span data-ttu-id="531b9-412">Wirkt sich auf die nächste Acceptmessagesession-Aufruf an den server</span><span class="sxs-lookup"><span data-stu-id="531b9-412">Takes effect on the next acceptmessagesession call to the server</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetConnection">
      <MemberSignature Language="C#" Value="public virtual void ResetConnection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ResetConnection() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.ResetConnection" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub ResetConnection ()" />
      <MemberSignature Language="F#" Value="abstract member ResetConnection : unit -&gt; unit&#xA;override this.ResetConnection : unit -&gt; unit" Usage="messagingFactory.ResetConnection " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>