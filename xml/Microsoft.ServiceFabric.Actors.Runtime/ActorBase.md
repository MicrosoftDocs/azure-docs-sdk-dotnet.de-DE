<Type Name="ActorBase" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorBase">
  <TypeSignature Language="C#" Value="public abstract class ActorBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ActorBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ActorBase" />
  <TypeSignature Language="F#" Value="type ActorBase = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="37384-101">Stellt die Basisklasse für Akteure dar.</span><span class="sxs-lookup"><span data-stu-id="37384-101">Represents the base class for actors.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="37384-102">Der Basistyp für Akteure, die allgemeine Funktionalität für Akteure, die davon Herleiten bereitstellt <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />.</span><span class="sxs-lookup"><span data-stu-id="37384-102">The base type for actors, that provides the common functionality for actors that derive from <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />.</span></span>
            <span data-ttu-id="37384-103">Der Status wird über Garbage Collections der Akteur und Fail-Failover beibehalten.</span><span class="sxs-lookup"><span data-stu-id="37384-103">The state is preserved across actor garbage collections and fail-overs.</span></span>
            <span data-ttu-id="37384-104">Speichern und Abrufen des Status wird durch die Akteur-State-Anbieter bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="37384-104">The storage and retrieval of the state is provided by the actor state provider.</span></span> <span data-ttu-id="37384-105">Weitere Informationen finden Sie unter <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> .</span><span class="sxs-lookup"><span data-stu-id="37384-105">See <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> for more information.</span></span>
            </remarks>
    <altmember cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />
  </Docs>
  <Members>
    <Member MemberName="ActorService">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.ActorService ActorService { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.ActorService ActorService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ActorService" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorService As ActorService" />
      <MemberSignature Language="F#" Value="member this.ActorService : Microsoft.ServiceFabric.Actors.Runtime.ActorService" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ActorService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorService</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37384-106">Ruft die statusbehafteten dienstreplikats, die den Akteur gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="37384-106">Gets the stateful service replica that is hosting the actor.</span></span>
            </summary>
        <value>
            <span data-ttu-id="37384-107">Die <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ActorService" /> , die den Akteur hosting zustandsbehafteten dienstreplikats darstellt.</span><span class="sxs-lookup"><span data-stu-id="37384-107">The <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ActorService" /> that represents the stateful service replica hosting the actor.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public string ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : string" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37384-108">Ruft den Namen der Anwendung, die den Akteur-Dienst enthält, der dieser Akteur gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="37384-108">Gets the name of the application that contains the actor service that is hosting this actor.</span></span>
            </summary>
        <value><span data-ttu-id="37384-109">Der Name der Anwendung, die den Akteur-Dienst enthält, der dieser Akteur gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="37384-109">The name of application that contains the actor service that is hosting this actor.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEvent&lt;TEvent&gt;">
      <MemberSignature Language="C#" Value="protected TEvent GetEvent&lt;TEvent&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance !!TEvent GetEvent&lt;TEvent&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.GetEvent``1" />
      <MemberSignature Language="VB.NET" Value="Protected Function GetEvent(Of TEvent) () As TEvent" />
      <MemberSignature Language="F#" Value="member this.GetEvent : unit -&gt; 'Event" Usage="actorBase.GetEvent " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TEvent</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TEvent" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="TEvent"><span data-ttu-id="37384-110">Der Ereignistyp-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="37384-110">The Event interface type.</span></span></typeparam>
        <summary>
            <span data-ttu-id="37384-111">Ruft das Ereignis für die angegebene Schnittstelle ab.</span><span class="sxs-lookup"><span data-stu-id="37384-111">Gets the event for the specified event interface.</span></span>
            </summary>
        <returns><span data-ttu-id="37384-112">Gibt ein Ereignis, das die angegebene Schnittstelle darstellt.</span><span class="sxs-lookup"><span data-stu-id="37384-112">Returns an Event that represents the specified interface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReminder">
      <MemberSignature Language="C#" Value="protected Microsoft.ServiceFabric.Actors.Runtime.IActorReminder GetReminder (string reminderName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder GetReminder(string reminderName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.GetReminder(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Function GetReminder (reminderName As String) As IActorReminder" />
      <MemberSignature Language="F#" Value="member this.GetReminder : string -&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" Usage="actorBase.GetReminder reminderName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.IActorReminder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reminderName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="reminderName"><span data-ttu-id="37384-113">Der Name der Erinnerung abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="37384-113">The Name of the reminder to get.</span></span></param>
        <summary>
            <span data-ttu-id="37384-114">Ruft die Erinnerung Akteur mit dem angegebenen Namen ab.</span><span class="sxs-lookup"><span data-stu-id="37384-114">Gets the actor reminder with specified reminder name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="37384-115">Ein <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" /> , eine Akteur Erinnerung darstellt.</span><span class="sxs-lookup"><span data-stu-id="37384-115">An <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" /> that represents an actor reminder.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceFabric.Actors.ReminderNotFoundException"><span data-ttu-id="37384-116">Die Erinnerung für den Akteur wurde nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="37384-116">Reminder not found for the actor.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.ActorId Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.ActorId Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As ActorId" />
      <MemberSignature Language="F#" Value="member this.Id : Microsoft.ServiceFabric.Actors.ActorId" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorBase.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37384-117">Ruft die Identität des dieser Akteur mit dem Akteur-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="37384-117">Gets the identity of this actor with the actor service.</span></span>
            </summary>
        <value><span data-ttu-id="37384-118">Die <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> für den Akteur.</span><span class="sxs-lookup"><span data-stu-id="37384-118">The <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> for the actor.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnActivateAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnActivateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnActivateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnActivateAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnActivateAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OnActivateAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.OnActivateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="actorBase.OnActivateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="37384-119">Überschreiben Sie diese Methode zum Initialisieren der Elemente, Zustand initialisieren oder Zeitgeber zu registrieren.</span><span class="sxs-lookup"><span data-stu-id="37384-119">Override this method to initialize the members, initialize state or register timers.</span></span> <span data-ttu-id="37384-120">Diese Methode wird rechts aufgerufen, nachdem der Akteur aktiviert wird, und vor jeder Methode aufrufen oder Erinnerungen darauf weitergeleitet werden.</span><span class="sxs-lookup"><span data-stu-id="37384-120">This method is called right after the actor is activated and before any method call or reminders are dispatched on it.</span></span>
            </summary>
        <returns><span data-ttu-id="37384-121">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehende OnActivateAsync-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37384-121">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding OnActivateAsync operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeactivateAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnDeactivateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnDeactivateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnDeactivateAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnDeactivateAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OnDeactivateAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.OnDeactivateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="actorBase.OnDeactivateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
             <span data-ttu-id="37384-122">Überschreiben Sie diese Methode, um alle Ressourcen freizugeben.</span><span class="sxs-lookup"><span data-stu-id="37384-122">Override this method to release any resources.</span></span> <span data-ttu-id="37384-123">Diese Methode wird aufgerufen, wenn Akteur deaktiviert (Garbage Collection durch Akteur Common Language Runtime) ist.</span><span class="sxs-lookup"><span data-stu-id="37384-123">This method is called when actor is deactivated (garbage collected by Actor Runtime).</span></span>
             <span data-ttu-id="37384-124">Actor-Vorgänge wie Statusänderungen dürfen von dieser Methode nicht aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="37384-124">Actor operations like state changes should not be called from this method.</span></span>
            </summary>
        <returns><span data-ttu-id="37384-125">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehende OnDeactivateAsync Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37384-125">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding OnDeactivateAsync operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnPostActorMethodAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnPostActorMethodAsync (Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext actorMethodContext);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnPostActorMethodAsync(valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext actorMethodContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPostActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" />
      <MemberSignature Language="F#" Value="abstract member OnPostActorMethodAsync : Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext -&gt; System.Threading.Tasks.Task&#xA;override this.OnPostActorMethodAsync : Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext -&gt; System.Threading.Tasks.Task" Usage="actorBase.OnPostActorMethodAsync actorMethodContext" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorMethodContext" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" />
      </Parameters>
      <Docs>
        <param name="actorMethodContext">
            <span data-ttu-id="37384-126">Ein <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" /> beschreiben die Methode, die vom Akteur-Laufzeit, bevor Sie diese Methode aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="37384-126">An <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" /> describing the method that was invoked by actor runtime prior to this method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="37384-127">Überschreiben Sie diese Methode für eine Aktion ausgeführt, nachdem eine Akteur-Methode die Ausführung beendet ist.</span><span class="sxs-lookup"><span data-stu-id="37384-127">Override this method for performing any actions after an actor method has finished execution.</span></span>
            <span data-ttu-id="37384-128">Diese Methode wird aufgerufen, von Akteur Runtime eine Akteur-Methode Ausführung beendet wurde.</span><span class="sxs-lookup"><span data-stu-id="37384-128">This method is invoked by actor runtime an actor method has finished execution.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="37384-129">Gibt eine <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , post, actor-Method-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37384-129">Returns a <see cref="T:System.Threading.Tasks.Task">Task</see> representing post-actor-method operation.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="37384-130">Diese Methode wird aufgerufen, indem Akteur zur Laufzeit vor: <list type="bullet"> <item> <description>eine Schnittstellenmethode Akteur aufrufen, wenn eine Clientanforderung eingeht.</description> </item> <item> <description>Aufrufen einer Methode auf <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> Schnittstelle, wenn eine Erinnerung ausgelöst wird.</description> </item> <item> <description>Einem timerrückruf aufrufen, wenn Timer ausgelöst wird.</description></item></list></span><span class="sxs-lookup"><span data-stu-id="37384-130">This method is invoked by actor runtime prior to: <list type="bullet"><item><description>Invoking an actor interface method when a client request comes.</description></item><item><description>Invoking a method on <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> interface when a reminder fires.</description></item><item><description>Invoking a timer callback when timer fires.</description></item></list></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="OnPreActorMethodAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnPreActorMethodAsync (Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext actorMethodContext);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnPreActorMethodAsync(valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext actorMethodContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPreActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" />
      <MemberSignature Language="F#" Value="abstract member OnPreActorMethodAsync : Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext -&gt; System.Threading.Tasks.Task&#xA;override this.OnPreActorMethodAsync : Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext -&gt; System.Threading.Tasks.Task" Usage="actorBase.OnPreActorMethodAsync actorMethodContext" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorMethodContext" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" />
      </Parameters>
      <Docs>
        <param name="actorMethodContext">
            <span data-ttu-id="37384-131">Ein <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" /> beschreiben die Methode, die vom Akteur Common Language Runtime nach Abschluss dieser Methode aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="37384-131">An <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" /> describing the method that will be invoked by actor runtime after this method finishes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="37384-132">Überschreiben Sie diese Methode zum Ausführen von Maßnahmen, die vor einem Akteur-Methode aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="37384-132">Override this method for performing any actions prior to an actor method is invoked.</span></span>
            <span data-ttu-id="37384-133">Diese Methode wird von Akteur Laufzeit aufgerufen, unmittelbar vor eine Akteur-Methode aufrufen.</span><span class="sxs-lookup"><span data-stu-id="37384-133">This method is invoked by actor runtime just before invoking an actor method.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="37384-134">Gibt eine <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , actor--Methode Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37384-134">Returns a <see cref="T:System.Threading.Tasks.Task">Task</see> representing pre-actor-method operation.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="37384-135">Diese Methode wird aufgerufen, indem Akteur zur Laufzeit vor: <list type="bullet"> <item> <description>eine Schnittstellenmethode Akteur aufrufen, wenn eine Clientanforderung eingeht.</description> </item> <item> <description>Aufrufen einer Methode auf <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> Schnittstelle, wenn eine Erinnerung ausgelöst wird.</description> </item> <item> <description>Einem timerrückruf aufrufen, wenn Timer ausgelöst wird.</description></item></list></span><span class="sxs-lookup"><span data-stu-id="37384-135">This method is invoked by actor runtime prior to: <list type="bullet"><item><description>Invoking an actor interface method when a client request comes.</description></item><item><description>Invoking a method on <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> interface when a reminder fires.</description></item><item><description>Invoking a timer callback when timer fires.</description></item></list></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterReminderAsync">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminder&gt; RegisterReminderAsync (string reminderName, byte[] state, TimeSpan dueTime, TimeSpan period);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder&gt; RegisterReminderAsync(string reminderName, unsigned int8[] state, valuetype System.TimeSpan dueTime, valuetype System.TimeSpan period) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Function RegisterReminderAsync (reminderName As String, state As Byte(), dueTime As TimeSpan, period As TimeSpan) As Task(Of IActorReminder)" />
      <MemberSignature Language="F#" Value="member this.RegisterReminderAsync : string * byte[] * TimeSpan * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminder&gt;" Usage="actorBase.RegisterReminderAsync (reminderName, state, dueTime, period)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.ActorBase/&lt;RegisterReminderAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminder&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reminderName" Type="System.String" />
        <Parameter Name="state" Type="System.Byte[]" />
        <Parameter Name="dueTime" Type="System.TimeSpan" />
        <Parameter Name="period" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="reminderName"><span data-ttu-id="37384-136">Der Name der Erinnerung zu registrieren.</span><span class="sxs-lookup"><span data-stu-id="37384-136">The name of the reminder to register.</span></span> <span data-ttu-id="37384-137">Der Name muss jede Akteur eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="37384-137">The name must be unique per actor.</span></span></param>
        <param name="state"><span data-ttu-id="37384-138">Benutzerstatus für den Aufruf Erinnerung übergeben.</span><span class="sxs-lookup"><span data-stu-id="37384-138">User state passed to the reminder invocation.</span></span></param>
        <param name="dueTime"><span data-ttu-id="37384-139">Die Zeitspanne für die Verzögerung, die Erinnerung zum ersten Mal aufrufen.</span><span class="sxs-lookup"><span data-stu-id="37384-139">The amount of time to delay before invoking the reminder for the first time.</span></span> <span data-ttu-id="37384-140">Geben Sie (-1) Millisekunde an, um den Aufruf zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="37384-140">Specify negative one (-1) milliseconds to disable invocation.</span></span> <span data-ttu-id="37384-141">Geben Sie 0 (null) fest, um die Erinnerung sofort nach der Registrierung aufzurufen.</span><span class="sxs-lookup"><span data-stu-id="37384-141">Specify zero (0) to invoke the reminder immediately after registration.</span></span>
            </param>
        <param name="period">
            <span data-ttu-id="37384-142">Das Zeitintervall zwischen den Aufrufen der Erinnerung nach dem ersten Aufruf.</span><span class="sxs-lookup"><span data-stu-id="37384-142">The time interval between reminder invocations after the first invocation.</span></span> <span data-ttu-id="37384-143">Geben Sie (-1) Millisekunde an, um regelmäßige Aufruf zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="37384-143">Specify negative one (-1) milliseconds to disable periodic invocation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="37384-144">Registriert eine Erinnerung mit der Akteur.</span><span class="sxs-lookup"><span data-stu-id="37384-144">Registers a reminder with the actor.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="37384-145">Eine Aufgabe, die den asynchronen Registrierungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37384-145">A task that represents the asynchronous registration operation.</span></span> <span data-ttu-id="37384-146">Das Ergebnis des Vorgangs enthält Informationen über die registrierten Erinnerung und wird verwendet, um die Erinnerung Verwendung aufgehoben <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.UnregisterReminderAsync(Microsoft.ServiceFabric.Actors.Runtime.IActorReminder)" />.</span><span class="sxs-lookup"><span data-stu-id="37384-146">The result of the task provides information about the registered reminder and is used to unregister the reminder using <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.UnregisterReminderAsync(Microsoft.ServiceFabric.Actors.Runtime.IActorReminder)" />.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="37384-147">Die Klasse, ableiten von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorBase" /> implementieren müssen <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> Erinnerung Aufrufe zu nutzen.</span><span class="sxs-lookup"><span data-stu-id="37384-147">The class deriving from <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorBase" /> must implement <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> to consume reminder invocations.</span></span> <span data-ttu-id="37384-148">Mehrere Erinnerungen können registriert werden zu einem beliebigen Zeitpunkt eindeutig identifizierte <paramref name="reminderName" />.</span><span class="sxs-lookup"><span data-stu-id="37384-148">Multiple reminders can be registered at any time, uniquely identified by <paramref name="reminderName" />.</span></span> <span data-ttu-id="37384-149">Vorhandene Erinnerungen können auch durch Aufruf dieser Methode noch einmal aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="37384-149">Existing reminders can also be updated by calling this method again.</span></span> <span data-ttu-id="37384-150">Erinnerung Aufrufe werden mit anderen Erinnerungen und andere Akteur Methode Rückrufe synchronisiert.</span><span class="sxs-lookup"><span data-stu-id="37384-150">Reminder invocations are synchronized both with other reminders and other actor method callbacks.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterTimer">
      <MemberSignature Language="C#" Value="protected Microsoft.ServiceFabric.Actors.Runtime.IActorTimer RegisterTimer (Func&lt;object,System.Threading.Tasks.Task&gt; asyncCallback, object state, TimeSpan dueTime, TimeSpan period);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class Microsoft.ServiceFabric.Actors.Runtime.IActorTimer RegisterTimer(class System.Func`2&lt;object, class System.Threading.Tasks.Task&gt; asyncCallback, object state, valuetype System.TimeSpan dueTime, valuetype System.TimeSpan period) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterTimer(System.Func{System.Object,System.Threading.Tasks.Task},System.Object,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Function RegisterTimer (asyncCallback As Func(Of Object, Task), state As Object, dueTime As TimeSpan, period As TimeSpan) As IActorTimer" />
      <MemberSignature Language="F#" Value="member this.RegisterTimer : Func&lt;obj, System.Threading.Tasks.Task&gt; * obj * TimeSpan * TimeSpan -&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorTimer" Usage="actorBase.RegisterTimer (asyncCallback, state, dueTime, period)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.IActorTimer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncCallback" Type="System.Func&lt;System.Object,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="state" Type="System.Object" />
        <Parameter Name="dueTime" Type="System.TimeSpan" />
        <Parameter Name="period" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="asyncCallback">
            <span data-ttu-id="37384-151">Ein Delegat, der eine aufzurufende Methode aufgerufen werden, wenn der Zeitgeber löst angibt.</span><span class="sxs-lookup"><span data-stu-id="37384-151">A delegate that specifies a method to be called when the timer fires.</span></span>
            <span data-ttu-id="37384-152">Er verfügt über einen Parameter: das Zustandsobjekt an RegisterTimer übergeben.</span><span class="sxs-lookup"><span data-stu-id="37384-152">It has one parameter: the state object passed to RegisterTimer.</span></span>
            <span data-ttu-id="37384-153">Es gibt eine <see cref="T:System.Threading.Tasks.Task" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37384-153">It returns a <see cref="T:System.Threading.Tasks.Task" /> representing the asynchronous operation.</span></span>
            </param>
        <param name="state"><span data-ttu-id="37384-154">Ein Objekt mit Informationen, die von der Rückrufmethode verwendet oder null sein.</span><span class="sxs-lookup"><span data-stu-id="37384-154">An object containing information to be used by the callback method, or null.</span></span></param>
        <param name="dueTime"><span data-ttu-id="37384-155">Der Anteil für die Verzögerung festzulegen, bevor der asynchrone Rückruf erstmalig aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="37384-155">The amount of time to delay before the async callback is first invoked.</span></span> <span data-ttu-id="37384-156">Geben Sie „-1“ Millisekunde an, um das Starten des Timers zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="37384-156">Specify negative one (-1) milliseconds to prevent the timer from starting.</span></span> <span data-ttu-id="37384-157">Geben Sie 0 (null) an, um den Timer sofort zu starten.</span><span class="sxs-lookup"><span data-stu-id="37384-157">Specify zero (0) to start the timer immediately.</span></span>
            </param>
        <param name="period">
            <span data-ttu-id="37384-158">Das Zeitintervall zwischen den Aufrufen des Rückrufs Async.</span><span class="sxs-lookup"><span data-stu-id="37384-158">The time interval between invocations of the async callback.</span></span> <span data-ttu-id="37384-159">Geben Sie -1 Millisekunde an, um periodisches Signalisieren zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="37384-159">Specify negative one (-1) milliseconds to disable periodic signaling.</span></span></param>
        <summary>
            <span data-ttu-id="37384-160">Registriert einen Zeitgeber für den Akteur.</span><span class="sxs-lookup"><span data-stu-id="37384-160">Registers a Timer for the actor.</span></span>
            </summary>
        <returns><span data-ttu-id="37384-161">Gibt ein IActorTimer-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37384-161">Returns IActorTimer object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceUri">
      <MemberSignature Language="C#" Value="public Uri ServiceUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ServiceUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceUri As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceUri : Uri" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ServiceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37384-162">Ruft den URI des Diensts Akteur, der dieser Akteur gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="37384-162">Gets the URI of the actor service that is hosting this actor.</span></span>
            </summary>
        <value><span data-ttu-id="37384-163">Die <see cref="T:System.Uri" /> des Akteurs-Diensts, der dieser Akteur gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="37384-163">The <see cref="T:System.Uri" /> of the actor service that is hosting this actor.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterReminderAsync">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task UnregisterReminderAsync (Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task UnregisterReminderAsync(class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.UnregisterReminderAsync(Microsoft.ServiceFabric.Actors.Runtime.IActorReminder)" />
      <MemberSignature Language="VB.NET" Value="Protected Function UnregisterReminderAsync (reminder As IActorReminder) As Task" />
      <MemberSignature Language="F#" Value="member this.UnregisterReminderAsync : Microsoft.ServiceFabric.Actors.Runtime.IActorReminder -&gt; System.Threading.Tasks.Task" Usage="actorBase.UnregisterReminderAsync reminder" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.ActorBase/&lt;UnregisterReminderAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reminder" Type="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
      </Parameters>
      <Docs>
        <param name="reminder"><span data-ttu-id="37384-164">Der Akteur Erinnerung beim Aufheben der Registrierung.</span><span class="sxs-lookup"><span data-stu-id="37384-164">The actor reminder to unregister.</span></span></param>
        <summary>
            <span data-ttu-id="37384-165">Hebt die Registrierung auf eine Erinnerung mit zuvor registriert <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />.</span><span class="sxs-lookup"><span data-stu-id="37384-165">Unregisters a reminder previously registered using <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="37384-166">Eine Aufgabe zurück, die den Aufhebung der Registrierung von asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37384-166">Returns a task that represents the asynchronous unregistration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="37384-167">Die angegebene Erinnerung ist nicht registriert.</span><span class="sxs-lookup"><span data-stu-id="37384-167">The specified reminder is not registered.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UnregisterTimer">
      <MemberSignature Language="C#" Value="protected void UnregisterTimer (Microsoft.ServiceFabric.Actors.Runtime.IActorTimer timer);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void UnregisterTimer(class Microsoft.ServiceFabric.Actors.Runtime.IActorTimer timer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.UnregisterTimer(Microsoft.ServiceFabric.Actors.Runtime.IActorTimer)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub UnregisterTimer (timer As IActorTimer)" />
      <MemberSignature Language="F#" Value="member this.UnregisterTimer : Microsoft.ServiceFabric.Actors.Runtime.IActorTimer -&gt; unit" Usage="actorBase.UnregisterTimer timer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timer" Type="Microsoft.ServiceFabric.Actors.Runtime.IActorTimer" />
      </Parameters>
      <Docs>
        <param name="timer"><span data-ttu-id="37384-168">Ein IActorTimer Timer darstellt, nicht aufgehoben werden muss.</span><span class="sxs-lookup"><span data-stu-id="37384-168">An IActorTimer representing timer that needs to be unregistered.</span></span></param>
        <summary>
            <span data-ttu-id="37384-169">Hebt die Registrierung eines Zeitgebers, der zuvor auf dieser Akteur festgelegt.</span><span class="sxs-lookup"><span data-stu-id="37384-169">Unregisters a Timer previously set on this actor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>