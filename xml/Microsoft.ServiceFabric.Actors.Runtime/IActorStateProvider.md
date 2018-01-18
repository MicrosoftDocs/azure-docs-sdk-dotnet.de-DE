<Type Name="IActorStateProvider" FullName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider">
  <TypeSignature Language="C#" Value="public interface IActorStateProvider : Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorStateProvider implements class Microsoft.ServiceFabric.Data.IStateProviderReplica, class Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorStateProvider&#xA;Implements IStateProviderReplica2" />
  <TypeSignature Language="F#" Value="type IActorStateProvider = interface&#xA;    interface IStateProviderReplica2&#xA;    interface IStateProviderReplica" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IStateProviderReplica2</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="e414e-101">Stellt die Schnittstelle, die ein Akteur State-Anbieter für Akteur-Laufzeit für die Kommunikation zu implementieren muss.</span><span class="sxs-lookup"><span data-stu-id="e414e-101">Represents the interface that an actor state provider needs to implement for actor runtime to communicate with it.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ActorActivatedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ActorActivatedAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ActorActivatedAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ActorActivatedAsync : Microsoft.ServiceFabric.Actors.ActorId * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.ActorActivatedAsync (actorId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="e414e-102">Die ID des Akteurs, die aktiviert wird.</span><span class="sxs-lookup"><span data-stu-id="e414e-102">ID of the actor that is activated.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e414e-103">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="e414e-103">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e414e-104">Wird aufgerufen, im Rahmen des Aktivierungsprozesses des Akteurs, mit der angegebenen Akteur-ID.</span><span class="sxs-lookup"><span data-stu-id="e414e-104">Invoked as part of the activation process of the actor with the specified actor ID.</span></span>
            </summary>
        <returns><span data-ttu-id="e414e-105">Eine Aufgabe, die asynchrone Akteur Aktivierung Benachrichtigung Verarbeitung darstellt.</span><span class="sxs-lookup"><span data-stu-id="e414e-105">A task that represents the asynchronous actor activation notification processing.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="e414e-106">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="e414e-106">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ContainsStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsStateAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsStateAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ContainsStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContainsStateAsync : Microsoft.ServiceFabric.Actors.ActorId * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iActorStateProvider.ContainsStateAsync (actorId, stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="e414e-107">Die ID des Akteurs, deren Zustand Vorhandensein überprüft.</span><span class="sxs-lookup"><span data-stu-id="e414e-107">ID of the actor for which to check state existence.</span></span></param>
        <param name="stateName"><span data-ttu-id="e414e-108">Name des Zustands Akteur Vorhandensein überprüft.</span><span class="sxs-lookup"><span data-stu-id="e414e-108">Name of the actor state to check for existence.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e414e-109">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="e414e-109">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e414e-110">Überprüft, ob zustandsanbieter Akteur eine actorzustands mit dem angegebenen Zustand Namen für die angegebene Akteur-ID enthält</span><span class="sxs-lookup"><span data-stu-id="e414e-110">Checks whether actor state provider contains an actor state with specified state name for the specified actor ID.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e414e-111">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="e414e-111">A task that represents the asynchronous check operation.</span></span> <span data-ttu-id="e414e-112">Der Wert von TResult-Parameter ist <c>"true"</c> Wenn Status mit dem angegebenen Namen vorhanden andernfalls ist <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="e414e-112">The value of TResult parameter is <c>true</c> if state with specified name exists otherwise <c>false</c>.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="e414e-113">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="e414e-113">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteReminderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteReminderAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, string reminderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteReminderAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, string reminderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteReminderAsync : Microsoft.ServiceFabric.Actors.ActorId * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.DeleteReminderAsync (actorId, reminderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="reminderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="e414e-114">Die ID des Akteurs, der die Erinnerung gelöscht.</span><span class="sxs-lookup"><span data-stu-id="e414e-114">ID of the actor for which to delete the reminder.</span></span></param>
        <param name="reminderName"><span data-ttu-id="e414e-115">Der Name der Erinnerung zu löschen.</span><span class="sxs-lookup"><span data-stu-id="e414e-115">Name of the reminder to delete.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e414e-116">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="e414e-116">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e414e-117">Löscht die Erinnerung Akteur, mit dem Namen angegebenen Erinnerung, falls vorhanden</span><span class="sxs-lookup"><span data-stu-id="e414e-117">Deletes the actor reminder with the given reminder name if it exists</span></span>
            </summary>
        <returns><span data-ttu-id="e414e-118">Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="e414e-118">A task that represents the asynchronous delete operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="e414e-119">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="e414e-119">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteRemindersAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRemindersAsync (System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection&lt;string&gt;&gt; reminderNames, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteRemindersAsync(class System.Collections.Generic.IReadOnlyDictionary`2&lt;class Microsoft.ServiceFabric.Actors.ActorId, class System.Collections.Generic.IReadOnlyCollection`1&lt;string&gt;&gt; reminderNames, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteRemindersAsync(System.Collections.Generic.IReadOnlyDictionary{Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteRemindersAsync : System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.ServiceFabric.Actors.ActorId, System.Collections.Generic.IReadOnlyCollection&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.DeleteRemindersAsync (reminderNames, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reminderNames" Type="System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="reminderNames"><span data-ttu-id="e414e-120">Der Satz von Erinnerungen zu löschen.</span><span class="sxs-lookup"><span data-stu-id="e414e-120">The set of reminders to delete.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e414e-121">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="e414e-121">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e414e-122">Löscht den angegebenen Berechtigungssatz Erinnerungen an.</span><span class="sxs-lookup"><span data-stu-id="e414e-122">Deletes the specified set of reminders.</span></span>
            </summary>
        <returns><span data-ttu-id="e414e-123">Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="e414e-123">A task that represents the asynchronous delete operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="e414e-124">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="e414e-124">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="EnumerateStateNamesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; EnumerateStateNamesAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; EnumerateStateNamesAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.EnumerateStateNamesAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnumerateStateNamesAsync : Microsoft.ServiceFabric.Actors.ActorId * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;string&gt;&gt;" Usage="iActorStateProvider.EnumerateStateNamesAsync (actorId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="e414e-125">Die ID des Akteurs, für die enumerable erstellt.</span><span class="sxs-lookup"><span data-stu-id="e414e-125">ID of the actor for which to create enumerable.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e414e-126">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="e414e-126">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e414e-127">Erstellt ein aufzählbares Objekt von der alle Statusnamen angegebenen Akteur-ID zugeordnet ist</span><span class="sxs-lookup"><span data-stu-id="e414e-127">Creates an enumerable of all the state names associated with specified actor ID.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e414e-128">Eine Aufgabe, die den asynchronen Enumerationsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="e414e-128">A task that represents the asynchronous enumeration operation.</span></span> <span data-ttu-id="e414e-129">Der Wert von TResult-Parameter ist ein aufzählbares Objekt von dem alle Namen angegebenen Akteur zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="e414e-129">The value of TResult parameter is an enumerable of all state names associated with specified actor.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="e414e-130">Der Enumerator, der vom Akteur State-Anbieter zurückgegebene sicher gleichzeitig mit der Lesevorgänge verwendet wird und schreibt in die State-Anbieter.</span><span class="sxs-lookup"><span data-stu-id="e414e-130">The enumerator returned from actor state provider is safe to use concurrently with reads and writes to the state provider.</span></span> <span data-ttu-id="e414e-131">Es stellt eine Momentaufnahme für die konsistente Sicht der State-Anbieter dar.</span><span class="sxs-lookup"><span data-stu-id="e414e-131">It represents a snapshot consistent view of the state provider.</span></span>
            </remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="e414e-132">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="e414e-132">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetActorsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;&gt; GetActorsAsync (int numItemsToReturn, Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Query.PagedResult`1&lt;class Microsoft.ServiceFabric.Actors.ActorId&gt;&gt; GetActorsAsync(int32 numItemsToReturn, class Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.GetActorsAsync(System.Int32,Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetActorsAsync : int * Microsoft.ServiceFabric.Actors.Query.ContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;&gt;" Usage="iActorStateProvider.GetActorsAsync (numItemsToReturn, continuationToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="numItemsToReturn" Type="System.Int32" />
        <Parameter Name="continuationToken" Type="Microsoft.ServiceFabric.Actors.Query.ContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="numItemsToReturn"><span data-ttu-id="e414e-133">Die Anzahl der zurückzugebenden angeforderten Elemente.</span><span class="sxs-lookup"><span data-stu-id="e414e-133">Number of items requested to be returned.</span></span></param>
        <param name="continuationToken">
            <span data-ttu-id="e414e-134">Ein Fortsetzungstoken, um die Ergebnisse von Abfragen zu starten.</span><span class="sxs-lookup"><span data-stu-id="e414e-134">A continuation token to start querying the results from.</span></span>
            <span data-ttu-id="e414e-135">Ein null-Wert des Fortsetzungstokens bedeutet Zurückgeben von Werten Form Anfang starten.</span><span class="sxs-lookup"><span data-stu-id="e414e-135">A null value of continuation token means start returning values form the beginning.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="e414e-136">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="e414e-136">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e414e-137">Ruft die angeforderte Anzahl von der Akteur-ID aus der State-Anbieter ab.</span><span class="sxs-lookup"><span data-stu-id="e414e-137">Gets the requested number of ActorID's from the state provider.</span></span>
            </summary>
        <returns><span data-ttu-id="e414e-138">Eine Aufgabe, die den asynchronen Vorgang des Aufrufs an Server darstellt.</span><span class="sxs-lookup"><span data-stu-id="e414e-138">A task that represents the asynchronous operation of call to server.</span></span></returns>
        <remarks>
            <span data-ttu-id="e414e-139">Die <paramref name="continuationToken" /> ist relativ zu den Status der Akteur State-Anbieter zum Zeitpunkt des Aufrufs dieser API.</span><span class="sxs-lookup"><span data-stu-id="e414e-139">The <paramref name="continuationToken" /> is relative to the state of actor state provider at the time of invocation of this API.</span></span> <span data-ttu-id="e414e-140">Wenn sich der Status der Akteur Zustand des Anbieters auftritt (d. h. neue Akteure aktiviert sind oder vorhandene Akteure gelöscht werden) in der Zwischenzeit aufruft, um diese API als auch die Fortsetzung Token vom vorherigen Aufruf (bevor der Status geändert wurde) angegeben ist, wird im Ergebnis können Einträge enthalten in vorherigen Aufrufen bereits abgerufen wurden.</span><span class="sxs-lookup"><span data-stu-id="e414e-140">If the state of actor state provider changes (i.e. new actors are activated or existing actors are deleted) in between calls to this API and the continuation token from previous call (before the state was modified) is supplied, the result may contain entries that were already fetched in previous calls.</span></span>
            </remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="e414e-141">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="e414e-141">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.Initialize(Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation -&gt; unit" Usage="iActorStateProvider.Initialize actorTypeInformation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorTypeInformation" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />
      </Parameters>
      <Docs>
        <param name="actorTypeInformation"><span data-ttu-id="e414e-142">Geben Sie die Informationen der Akteurklasse</span><span class="sxs-lookup"><span data-stu-id="e414e-142">Type information of the actor class</span></span></param>
        <summary>
            <span data-ttu-id="e414e-143">Initialisiert die Akteur-State-Anbieter mit Typinformationen des Akteurs Typs zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="e414e-143">Initializes the actor state provider with type information of the actor type associated with it.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadRemindersAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt; LoadRemindersAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt; LoadRemindersAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadRemindersAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member LoadRemindersAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt;" Usage="iActorStateProvider.LoadRemindersAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="e414e-144">Abbruchtoken für asynchrone Ladevorgang.</span><span class="sxs-lookup"><span data-stu-id="e414e-144">Cancellation token for asynchronous load operation.</span></span></param>
        <summary>
            <span data-ttu-id="e414e-145">Lädt alle Erinnerungen, die in der Akteur-State-Anbieter enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="e414e-145">Loads all the reminders contained in the actor state provider.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e414e-146">Eine Aufgabe, die den asynchrone Ladevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="e414e-146">A task that represents the asynchronous load operation.</span></span> <span data-ttu-id="e414e-147">Der Wert von TResult-Parameter ist eine Auflistung von alle Akteur Erinnerungen in der Akteur-State-Anbieter enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="e414e-147">The value of TResult parameter is a collection of all actor reminders contained in the actor state provider.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="e414e-148">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="e414e-148">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="LoadStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; LoadStateAsync&lt;T&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; LoadStateAsync&lt;T&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadStateAsync``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member LoadStateAsync : Microsoft.ServiceFabric.Actors.ActorId * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iActorStateProvider.LoadStateAsync (actorId, stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="e414e-149">Der Typ des Werts des actorzustands angegebenen Zustand zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="e414e-149">Type of value of actor state associated with given state name.</span></span></typeparam>
        <param name="actorId"><span data-ttu-id="e414e-150">Die ID des Akteurs, für das Laden des Zustands.</span><span class="sxs-lookup"><span data-stu-id="e414e-150">ID of the actor for which to load the state.</span></span></param>
        <param name="stateName"><span data-ttu-id="e414e-151">Name des Zustands Akteur geladen.</span><span class="sxs-lookup"><span data-stu-id="e414e-151">Name of the actor state to load.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e414e-152">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="e414e-152">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e414e-153">Lädt den Namen angegebenen Zustand für die angegebene Akteur-ID zugeordneten Akteur-Zustand</span><span class="sxs-lookup"><span data-stu-id="e414e-153">Loads the actor state associated with the specified state name for the specified actor ID.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e414e-154">Eine Aufgabe, die den asynchrone Ladevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="e414e-154">A task that represents the asynchronous load operation.</span></span> <span data-ttu-id="e414e-155">Der Wert von TResult-Parameter enthält Wert des actorzustands angegebenen Zustand zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="e414e-155">The value of TResult parameter contains value of actor state associated with given state name.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException"><span data-ttu-id="e414e-156">Akteur Zustand, der mit dem angegebenen Namen ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="e414e-156">Actor state associated with specified state name does not exist.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="e414e-157">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="e414e-157">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ReminderCallbackCompletedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReminderCallbackCompletedAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ReminderCallbackCompletedAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ReminderCallbackCompletedAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReminderCallbackCompletedAsync : Microsoft.ServiceFabric.Actors.ActorId * Microsoft.ServiceFabric.Actors.Runtime.IActorReminder * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.ReminderCallbackCompletedAsync (actorId, reminder, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="reminder" Type="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="e414e-158">ID des Akteurs, der Erinnerung besitzen</span><span class="sxs-lookup"><span data-stu-id="e414e-158">ID of the actor which own reminder</span></span></param>
        <param name="reminder"><span data-ttu-id="e414e-159">Akteur Erinnerung, die erfolgreich abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="e414e-159">Actor reminder that completed successfully.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e414e-160">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="e414e-160">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e414e-161">Wird aufgerufen, wenn eine Erinnerung ausgelöst wird, und schließt die Ausführung der zugehörige Rückruf <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" /> erfolgreich.</span><span class="sxs-lookup"><span data-stu-id="e414e-161">Invoked when a reminder fires and finishes executing its callback <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" /> successfully.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e414e-162">Eine Aufgabe, die asynchrone Erinnerung Rückruf abgeschlossenen Benachrichtigung Verarbeitung darstellt.</span><span class="sxs-lookup"><span data-stu-id="e414e-162">A task that represents the asynchronous reminder callback completed notification processing.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveActorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveActorAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveActorAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveActorAsync : Microsoft.ServiceFabric.Actors.ActorId * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.RemoveActorAsync (actorId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="e414e-163">Die ID des Akteurs, für den Status zu entfernt.</span><span class="sxs-lookup"><span data-stu-id="e414e-163">ID of the actor for which to remove state.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e414e-164">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="e414e-164">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e414e-165">Entfernt alle vorhandenen Status und Erinnerungen angegebenen Akteur-ID automatisch zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="e414e-165">Removes all the existing states and reminders associated with specified actor ID atomically.</span></span>
            </summary>
        <returns><span data-ttu-id="e414e-166">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="e414e-166">A task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="e414e-167">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="e414e-167">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SaveReminderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveReminderAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SaveReminderAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SaveReminderAsync : Microsoft.ServiceFabric.Actors.ActorId * Microsoft.ServiceFabric.Actors.Runtime.IActorReminder * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.SaveReminderAsync (actorId, reminder, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="reminder" Type="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="e414e-168">Die ID des Akteurs, für die die Erinnerung zu speichern.</span><span class="sxs-lookup"><span data-stu-id="e414e-168">ID of the actor for which to save the reminder.</span></span></param>
        <param name="reminder"><span data-ttu-id="e414e-169">Akteur Erinnerung zu speichern.</span><span class="sxs-lookup"><span data-stu-id="e414e-169">Actor reminder to save.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e414e-170">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="e414e-170">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e414e-171">Speichert die angegebenen Akteur ID Erinnerung an.</span><span class="sxs-lookup"><span data-stu-id="e414e-171">Saves the specified actor ID reminder.</span></span> <span data-ttu-id="e414e-172">Wenn eine Akteur Erinnerung mit dem angegebenen Namen nicht vorhanden ist, fügt es hinzu, dass die Akteur Erinnerung andernfalls vorhandenen Akteur Erinnerung mit demselben Namen aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="e414e-172">If an actor reminder with given name does not exist, it adds the actor reminder otherwise existing actor reminder with same name is updated.</span></span> 
            </summary>
        <returns><span data-ttu-id="e414e-173">Eine Aufgabe, die den asynchronen Speichervorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="e414e-173">A task that represents the asynchronous save operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="e414e-174">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="e414e-174">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SaveStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveStateAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; stateChanges, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SaveStateAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class System.Collections.Generic.IReadOnlyCollection`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; stateChanges, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SaveStateAsync : Microsoft.ServiceFabric.Actors.ActorId * System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.SaveStateAsync (actorId, stateChanges, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="stateChanges" Type="System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="e414e-175">Die ID des Akteurs, für die die statusänderungen zu speichern.</span><span class="sxs-lookup"><span data-stu-id="e414e-175">ID of the actor for which to save the state changes.</span></span></param>
        <param name="stateChanges"><span data-ttu-id="e414e-176">Die Auflistung von Zustandsänderungen zu speichern.</span><span class="sxs-lookup"><span data-stu-id="e414e-176">Collection of state changes to save.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e414e-177">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="e414e-177">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e414e-178">Speichert den angegebenen Berechtigungssatz Akteur Zustandsänderungen für die angegebene Akteur-ID atomar.</span><span class="sxs-lookup"><span data-stu-id="e414e-178">Saves the specified set of actor state changes for the specified actor ID atomically.</span></span>
            </summary>
        <returns><span data-ttu-id="e414e-179">Eine Aufgabe, die den asynchronen Speichervorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="e414e-179">A task that represents the asynchronous save operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="e414e-180">Die Auflistung von Zustandsänderungen sollte nur ein Element für einen bestimmten Zustand enthalten.</span><span class="sxs-lookup"><span data-stu-id="e414e-180">The collection of state changes should contain only one item for a given state name.</span></span>
            <span data-ttu-id="e414e-181">Der Speichervorgang Vorgang schlägt fehl, auf den Versuch, eine actorzustands hinzuzufügen, die bereits vorhanden ist oder aktualisieren/entfernen einen Akteur-Zustand, der nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="e414e-181">The save operation will fail on trying to add an actor state which already exists or update/remove an actor state which does not exist.</span></span>
            </remarks>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="e414e-182">Wenn <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" /> ist<see cref="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.None" /></span><span class="sxs-lookup"><span data-stu-id="e414e-182">When <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" /> is <see cref="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.None" /></span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="e414e-183">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="e414e-183">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>