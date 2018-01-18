<Type Name="IMessageSession" FullName="Microsoft.Azure.ServiceBus.IMessageSession">
  <TypeSignature Language="C#" Value="public interface IMessageSession : Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMessageSession implements class Microsoft.Azure.ServiceBus.Core.IMessageReceiver, class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.IMessageSession" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMessageSession&#xA;Implements IMessageReceiver" />
  <TypeSignature Language="F#" Value="type IMessageSession = interface&#xA;    interface IMessageReceiver&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.IMessageReceiver</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="3257e-101">Beschreibt ein Sitzungsobjekt.</span><span class="sxs-lookup"><span data-stu-id="3257e-101">Describes a Session object.</span></span> <span data-ttu-id="3257e-102">IMessageSession kann zum Ausführen von Vorgängen für Sitzungen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="3257e-102">IMessageSession can be used to perform operations on sessions.</span></span>
            </summary>
    <remarks>
      <para>
            <span data-ttu-id="3257e-103">Service Bus-Sitzungen, so genannte "Gruppen" in das Protokoll AMQP 1.0 sind ungebundenen Ereignisfolgen zusammengehöriger Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="3257e-103">Service Bus Sessions, also called 'Groups' in the AMQP 1.0 protocol, are unbounded sequences of related messages.</span></span> <span data-ttu-id="3257e-104">Service Bus garantiert die Reihenfolge der Nachrichten in einer Sitzung.</span><span class="sxs-lookup"><span data-stu-id="3257e-104">ServiceBus guarantees ordering of messages in a session.</span></span>
            </para>
      <para>
            <span data-ttu-id="3257e-105">Alle Absender erstellen Sie eine Sitzung beim Senden von Nachrichten in einer Warteschlange oder ein Thema durch Festlegen der <see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" /> Eigenschaft Nachricht zu einer Anwendung definierter Eindeutiger Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="3257e-105">Any sender can create a session when submitting messages into a Topic or Queue by setting the <see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" /> property on Message to some application defined unique identifier.</span></span> <span data-ttu-id="3257e-106">Auf der Protokollebene AMQP 1.0 wird dieser Wert auf die Gruppen-Id-Eigenschaft zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3257e-106">At the AMQP 1.0 protocol level, this value maps to the group-id property.</span></span>
            </para>
      <para>
            <span data-ttu-id="3257e-107">Sitzungen sind vorhanden, wenn mindestens eine Nachricht mit der Sitzung SessionId in die Warteschlange oder ein Thema Abonnement vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="3257e-107">Sessions come into existence when there is at least one message with the session's SessionId in the Queue or Topic subscription.</span></span>
            <span data-ttu-id="3257e-108">Sobald eine Sitzung vorhanden ist, gibt es keine definierten Moment oder einer Geste für, wenn die Sitzung abläuft, oder wird nicht mehr angezeigt.</span><span class="sxs-lookup"><span data-stu-id="3257e-108">Once a Session exists, there is no defined moment or gesture for when the session expires or disappears.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; GetStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; GetStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IMessageSession.GetStateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetStateAsync () As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member GetStateAsync : unit -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="iMessageSession.GetStateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3257e-109">Ruft den Sitzungsstatus ab.</span><span class="sxs-lookup"><span data-stu-id="3257e-109">Gets the session state.</span></span>
            </summary>
        <returns><span data-ttu-id="3257e-110">Der Sitzungsstatus als Bytearray.</span><span class="sxs-lookup"><span data-stu-id="3257e-110">The session state as byte array.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.IMessageSession.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime" Usage="Microsoft.Azure.ServiceBus.IMessageSession.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3257e-111">Ruft die Zeit ab, die die identifizierte Sitzung <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> erst für diesen Client gesperrt ist.</span><span class="sxs-lookup"><span data-stu-id="3257e-111">Gets the time that the session identified by <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> is locked until for this client.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewSessionLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewSessionLockAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewSessionLockAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IMessageSession.RenewSessionLockAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewSessionLockAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member RenewSessionLockAsync : unit -&gt; System.Threading.Tasks.Task" Usage="iMessageSession.RenewSessionLockAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3257e-112">Erneuert die Sperre für die Sitzung, die gemäß der <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />.</span><span class="sxs-lookup"><span data-stu-id="3257e-112">Renews the lock on the session specified by the <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />.</span></span> <span data-ttu-id="3257e-113">Die Sperre wird basierend auf der Einstellung für die Entität angegeben erneuert werden.</span><span class="sxs-lookup"><span data-stu-id="3257e-113">The lock will be renewed based on the setting specified on the entity.</span></span>
            </summary>
        <returns><span data-ttu-id="3257e-114">Der asynchrone Vorgang</span><span class="sxs-lookup"><span data-stu-id="3257e-114">The asynchronous operation</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="3257e-115">Wenn Sie eine Sitzung annehmen, wird die Sitzung während der Erstellung der Warteschlange/Abonnement für diese Clientinstanz vom Dienst für eine Dauer entsprechend den Angaben gesperrt.</span><span class="sxs-lookup"><span data-stu-id="3257e-115">When you accept a session, the session is locked for this client instance by the service for a duration as specified during the Queue/Subscription creation.</span></span>
            <span data-ttu-id="3257e-116">Wenn länger als diese Dauer der Sitzung Verarbeitung erforderlich ist, muss die Sitzung-Sperre erneuert werden.</span><span class="sxs-lookup"><span data-stu-id="3257e-116">If processing of the session requires longer than this duration, the session-lock needs to be renewed.</span></span> <span data-ttu-id="3257e-117">Bei jeder Verlängerung er setzt die Uhrzeit zurück, für die Sitzung durch die LockDuration, legen Sie für die Entität gesperrt ist.</span><span class="sxs-lookup"><span data-stu-id="3257e-117">For each renewal, it resets the time the session is locked by the LockDuration set on the Entity.</span></span>
            </para>
          <para>
            <span data-ttu-id="3257e-118">Erneuerung der Sitzung werden alle Nachrichten in der Sitzung auch erneuert.</span><span class="sxs-lookup"><span data-stu-id="3257e-118">Renewal of session renews all the messages in the session as well.</span></span> <span data-ttu-id="3257e-119">Jede einzelne Nachricht muss nicht erneuert werden.</span><span class="sxs-lookup"><span data-stu-id="3257e-119">Each individual message need not be renewed.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string" Usage="Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3257e-120">Ruft die SessionId ab.</span><span class="sxs-lookup"><span data-stu-id="3257e-120">Gets the SessionId.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetStateAsync (byte[] sessionState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetStateAsync(unsigned int8[] sessionState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IMessageSession.SetStateAsync(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function SetStateAsync (sessionState As Byte()) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetStateAsync : byte[] -&gt; System.Threading.Tasks.Task" Usage="iMessageSession.SetStateAsync sessionState" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionState" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="sessionState"><span data-ttu-id="3257e-121">Ein Bytearray des Sitzungsstatus</span><span class="sxs-lookup"><span data-stu-id="3257e-121">A byte array of session state</span></span></param>
        <summary>
            <span data-ttu-id="3257e-122">Legen Sie einen benutzerdefinierten Zustand für die Sitzung mit einem späteren Zeitpunkt abgerufen werden kann<see cref="M:Microsoft.Azure.ServiceBus.IMessageSession.GetStateAsync" /></span><span class="sxs-lookup"><span data-stu-id="3257e-122">Set a custom state on the session which can be later retrieved using <see cref="M:Microsoft.Azure.ServiceBus.IMessageSession.GetStateAsync" /></span></span></summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="3257e-123">Dieser Status wird ewig auf Service Bus gespeichert, wenn Sie einen leeren Zustand festzulegen.</span><span class="sxs-lookup"><span data-stu-id="3257e-123">This state is stored on Service Bus forever unless you set an empty state on it.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>