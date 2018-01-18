<Type Name="VolatileActorStateProvider" FullName="Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider">
  <TypeSignature Language="C#" Value="public class VolatileActorStateProvider : Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider, Microsoft.ServiceFabric.Data.IStateProviderReplica2, System.Fabric.IStateProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VolatileActorStateProvider extends System.Object implements class Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider, class Microsoft.ServiceFabric.Data.IStateProviderReplica, class Microsoft.ServiceFabric.Data.IStateProviderReplica2, class System.Fabric.IStateProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class VolatileActorStateProvider&#xA;Implements IActorStateProvider, IStateProvider, IStateProviderReplica2" />
  <TypeSignature Language="F#" Value="type VolatileActorStateProvider = class&#xA;    interface IActorStateProvider&#xA;    interface IStateProviderReplica2&#xA;    interface IStateProviderReplica&#xA;    interface IStateProvider&#xA;    interface VolatileLogicalTimeManager.ISnapshotHandler&#xA;    interface IActorStateProviderInternal" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IStateProviderReplica2</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Fabric.IStateProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="5904d-101">Stellt eine Implementierung von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> , in denen actorzustands im Arbeitsspeicher beibehalten wird und flüchtig ist.</span><span class="sxs-lookup"><span data-stu-id="5904d-101">Provides an implementation of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> where actor state is kept in-memory and is volatile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VolatileActorStateProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5904d-102">Erstellt eine Instanz von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.</span><span class="sxs-lookup"><span data-stu-id="5904d-102">Creates an instance of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VolatileActorStateProvider (System.Fabric.ReplicatorSettings replicatorSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ReplicatorSettings replicatorSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.#ctor(System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider : System.Fabric.ReplicatorSettings -&gt; Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" Usage="new Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider replicatorSettings" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="replicatorSettings">
            <span data-ttu-id="5904d-103">Ein <see cref="T:System.Fabric.ReplicatorSettings" /> , Replikator Einstellungen beschreibt.</span><span class="sxs-lookup"><span data-stu-id="5904d-103">A <see cref="T:System.Fabric.ReplicatorSettings" /> that describes replicator settings.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5904d-104">Erstellt eine Instanz des <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" /> Replikator Einstellungen angegeben.</span><span class="sxs-lookup"><span data-stu-id="5904d-104">Creates an instance of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" /> with specified replicator settings.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.ActorActivatedAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#ActorActivatedAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider/&lt;Microsoft-ServiceFabric-Actors-Runtime-IActorStateProvider-ActorActivatedAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="5904d-105">Die ID des Akteurs, die aktiviert wird.</span><span class="sxs-lookup"><span data-stu-id="5904d-105">ID of the actor that is activated.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5904d-106">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5904d-106">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-107">Diese Methode wird im Rahmen des Aktivierungsprozesses des Akteurs, mit der angegebenen Id. aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="5904d-107">This method is invoked as part of the activation process of the actor with the specified Id.</span></span> 
            </summary>
        <returns> <span data-ttu-id="5904d-108">Eine Aufgabe, die asynchrone Benachrichtigung Verarbeitung von Akteur Aktivierung darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-108">A task that represents the asynchronous Actor activation notification processing.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="5904d-109">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5904d-109">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ContainsStateAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;bool&gt; IActorStateProvider.ContainsStateAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ContainsStateAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#ContainsStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ContainsStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
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
        <param name="actorId"><span data-ttu-id="5904d-110">Die ID des Akteurs, deren Zustand Vorhandensein überprüft werden soll.</span><span class="sxs-lookup"><span data-stu-id="5904d-110">The ID of the actor for which to check state existence.</span></span></param>
        <param name="stateName"><span data-ttu-id="5904d-111">Der Name des Zustands Akteur Vorhandensein überprüft werden soll.</span><span class="sxs-lookup"><span data-stu-id="5904d-111">The name of the actor state to check for existence.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5904d-112">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5904d-112">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-113">Überprüft, ob zustandsanbieter Akteur eine actorzustands mit dem angegebenen Namen enthält.</span><span class="sxs-lookup"><span data-stu-id="5904d-113">Checks whether actor state provider contains an actor state with specified state name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5904d-114">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-114">A task that represents the asynchronous check operation.</span></span> <span data-ttu-id="5904d-115">Der Wert von TResult-Parameter ist <c>"true"</c> Wenn Status mit dem angegebenen Namen vorhanden andernfalls ist <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="5904d-115">The value of TResult parameter is <c>true</c> if state with specified name exists otherwise <c>false</c>.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="5904d-116">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5904d-116">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteReminderAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.DeleteReminderAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, string reminderName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteReminderAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, string reminderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#DeleteReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
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
        <param name="actorId"><span data-ttu-id="5904d-117">Die ID des Akteurs, der die Erinnerung gelöscht.</span><span class="sxs-lookup"><span data-stu-id="5904d-117">The ID of the actor for which to delete the reminder.</span></span></param>
        <param name="reminderName"><span data-ttu-id="5904d-118">Der Name der Erinnerung zu löschen.</span><span class="sxs-lookup"><span data-stu-id="5904d-118">The name of the reminder to delete.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5904d-119">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5904d-119">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-120">Löscht die angegebene Akteur Erinnerung an, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5904d-120">Deletes the specified actor reminder if it exists.</span></span>
            </summary>
        <returns><span data-ttu-id="5904d-121">Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-121">A task that represents the asynchronous delete operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="5904d-122">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5904d-122">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteRemindersAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.DeleteRemindersAsync (System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection&lt;string&gt;&gt; reminderNames, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteRemindersAsync(class System.Collections.Generic.IReadOnlyDictionary`2&lt;class Microsoft.ServiceFabric.Actors.ActorId, class System.Collections.Generic.IReadOnlyCollection`1&lt;string&gt;&gt; reminderNames, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#DeleteRemindersAsync(System.Collections.Generic.IReadOnlyDictionary{Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{System.String}},System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteRemindersAsync(System.Collections.Generic.IReadOnlyDictionary{Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
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
        <param name="reminderNames"><span data-ttu-id="5904d-123">Der Satz von Erinnerungen zu löschen.</span><span class="sxs-lookup"><span data-stu-id="5904d-123">The set of reminders to delete.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5904d-124">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5904d-124">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-125">Löscht den angegebenen Berechtigungssatz Erinnerungen an.</span><span class="sxs-lookup"><span data-stu-id="5904d-125">Deletes the specified set of reminders.</span></span>
            </summary>
        <returns><span data-ttu-id="5904d-126">Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-126">A task that represents the asynchronous delete operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="5904d-127">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5904d-127">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.EnumerateStateNamesAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; IActorStateProvider.EnumerateStateNamesAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.EnumerateStateNamesAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#EnumerateStateNamesAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.EnumerateStateNamesAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
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
        <param name="actorId"><span data-ttu-id="5904d-128">Die ID des Akteurs, für die enumerable erstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-128">The ID of the actor for which to create enumerable.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5904d-129">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5904d-129">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-130">Erstellt ein aufzählbares Objekt von allen zugeordneten angegebenen Akteur Ländernamen.</span><span class="sxs-lookup"><span data-stu-id="5904d-130">Creates an enumerable of all the state names associated with specified actor.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5904d-131">Eine Aufgabe, die den asynchronen Enumerationsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-131">A task that represents the asynchronous enumeration operation.</span></span> <span data-ttu-id="5904d-132">Der Wert von TResult-Parameter ist ein aufzählbares Objekt von dem alle Namen angegebenen Akteur zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="5904d-132">The value of TResult parameter is an enumerable of all state names associated with specified actor.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="5904d-133">Der Enumerator, der vom Akteur State-Anbieter zurückgegebene sicher gleichzeitig mit der Lesevorgänge verwendet wird und schreibt in die State-Anbieter.</span><span class="sxs-lookup"><span data-stu-id="5904d-133">The enumerator returned from actor state provider is safe to use concurrently with reads and writes to the state provider.</span></span> <span data-ttu-id="5904d-134">Es stellt eine Momentaufnahme für die konsistente Sicht der State-Anbieter dar.</span><span class="sxs-lookup"><span data-stu-id="5904d-134">It represents a snapshot consistent view of the state provider.</span></span>
            </remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="5904d-135">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5904d-135">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.GetActorsAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;&gt; IActorStateProvider.GetActorsAsync (int itemsCount, Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Query.PagedResult`1&lt;class Microsoft.ServiceFabric.Actors.ActorId&gt;&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.GetActorsAsync(int32 itemsCount, class Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#GetActorsAsync(System.Int32,Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.GetActorsAsync(System.Int32,Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="itemsCount" Type="System.Int32" />
        <Parameter Name="continuationToken" Type="Microsoft.ServiceFabric.Actors.Query.ContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="itemsCount"><span data-ttu-id="5904d-136">Die Anzahl der zurückzugebenden angeforderten Elemente.</span><span class="sxs-lookup"><span data-stu-id="5904d-136">Number of items requested to be returned.</span></span></param>
        <param name="continuationToken">
            <span data-ttu-id="5904d-137">Ein Fortsetzungstoken, um die Ergebnisse von Abfragen zu starten.</span><span class="sxs-lookup"><span data-stu-id="5904d-137">A continuation token to start querying the results from.</span></span>
            <span data-ttu-id="5904d-138">Ein null-Wert des Fortsetzungstokens bedeutet Zurückgeben von Werten Form Anfang starten.</span><span class="sxs-lookup"><span data-stu-id="5904d-138">A null value of continuation token means start returning values form the beginning.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="5904d-139">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5904d-139">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-140">Ruft den ActorIds aus der State-Anbieter ab.</span><span class="sxs-lookup"><span data-stu-id="5904d-140">Gets ActorIds from the State Provider.</span></span>
            </summary>
        <returns><span data-ttu-id="5904d-141">Eine Aufgabe, die den asynchronen Vorgang des Aufrufs an Server darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-141">A task that represents the asynchronous operation of call to server.</span></span></returns>
        <remarks>
            <span data-ttu-id="5904d-142">Die <paramref name="continuationToken" /> ist relativ zu den Status der Akteur State-Anbieter zum Zeitpunkt des Aufrufs dieser API.</span><span class="sxs-lookup"><span data-stu-id="5904d-142">The <paramref name="continuationToken" /> is relative to the state of actor state provider at the time of invocation of this API.</span></span> <span data-ttu-id="5904d-143">Wenn sich der Status der Akteur Zustand des Anbieters auftritt (d. h. neue Akteure aktiviert sind oder vorhandene Akteure gelöscht werden) in der Zwischenzeit aufruft, um diese API als auch die Fortsetzung Token vom vorherigen Aufruf (bevor der Status geändert wurde) angegeben ist, wird im Ergebnis können Einträge enthalten in vorherigen Aufrufen bereits abgerufen wurden.</span><span class="sxs-lookup"><span data-stu-id="5904d-143">If the state of actor state provider changes (i.e. new actors are activated or existing actors are deleted) in between calls to this API and the continuation token from previous call (before the state was modified) is supplied, the result may contain entries that were already fetched in previous calls.</span></span>
            </remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="5904d-144">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5904d-144">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.Initialize">
      <MemberSignature Language="C#" Value="void IActorStateProvider.Initialize (Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInfo);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.Initialize(class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#Initialize(Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation)" />
      <MemberSignature Language="VB.NET" Value="Sub Initialize (actorTypeInfo As ActorTypeInformation) Implements IActorStateProvider.Initialize" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.Initialize(Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorTypeInfo" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />
      </Parameters>
      <Docs>
        <param name="actorTypeInfo"><span data-ttu-id="5904d-145">Geben Sie die Informationen der Akteurklasse</span><span class="sxs-lookup"><span data-stu-id="5904d-145">Type information of the actor class</span></span></param>
        <summary>
            <span data-ttu-id="5904d-146">Initialisiert die Akteur-State-Anbieter mit Typinformationen des Akteurs Typs zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="5904d-146">Initializes the actor state provider with type information of the actor type associated with it.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadRemindersAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt; IActorStateProvider.LoadRemindersAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadRemindersAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#LoadRemindersAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadRemindersAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
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
        <param name="cancellationToken"><span data-ttu-id="5904d-147">Das Abbruchtoken, das für asynchrone Ladevorgang.</span><span class="sxs-lookup"><span data-stu-id="5904d-147">The cancellation token for asynchronous load operation.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-148">Lädt alle Erinnerungen, die in der Akteur-State-Anbieter enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="5904d-148">Loads all the reminders contained in the actor state provider.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5904d-149">Eine Aufgabe, die den asynchrone Ladevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-149">A task that represents the asynchronous load operation.</span></span> <span data-ttu-id="5904d-150">Der Wert von TResult-Parameter ist eine Auflistung von alle Akteur Erinnerungen in der Akteur-State-Anbieter enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="5904d-150">The value of TResult parameter is a collection of all actor reminders contained in the actor state provider.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="5904d-151">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5904d-151">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IActorStateProvider.LoadStateAsync&lt;T&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadStateAsync&lt;T&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#LoadStateAsync``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadStateAsync``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
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
        <typeparam name="T"><span data-ttu-id="5904d-152">Der Typ des Werts des actorzustands angegebenen Zustand zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="5904d-152">Type of value of actor state associated with given state name.</span></span></typeparam>
        <param name="actorId"><span data-ttu-id="5904d-153">Die ID des Akteurs, für das Laden des Zustands.</span><span class="sxs-lookup"><span data-stu-id="5904d-153">The ID of the actor for which to load the state.</span></span></param>
        <param name="stateName"><span data-ttu-id="5904d-154">Der Name des Zustands Akteur geladen.</span><span class="sxs-lookup"><span data-stu-id="5904d-154">The name of the actor state to load.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5904d-155">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5904d-155">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-156">Lädt den Akteur-Zustand, der dem angegebenen Zustand zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="5904d-156">Loads the actor state associated with the specified state name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5904d-157">Eine Aufgabe, die den asynchrone Ladevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-157">A task that represents the asynchronous load operation.</span></span> <span data-ttu-id="5904d-158">Der Wert von TResult-Parameter enthält Wert des actorzustands angegebenen Zustand zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="5904d-158">The value of TResult parameter contains value of actor state associated with given state name.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException"><span data-ttu-id="5904d-159">Der Akteur Zustand, der mit dem angegebenen Namen ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5904d-159">The actor state associated with specified state name does not exist.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="5904d-160">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5904d-160">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ReminderCallbackCompletedAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.ReminderCallbackCompletedAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ReminderCallbackCompletedAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#ReminderCallbackCompletedAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ReminderCallbackCompletedAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
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
        <param name="actorId"><span data-ttu-id="5904d-161">ID des Akteurs, der Erinnerung besitzen</span><span class="sxs-lookup"><span data-stu-id="5904d-161">ID of the actor which own reminder</span></span></param>
        <param name="reminder"><span data-ttu-id="5904d-162">Akteur Erinnerung, die erfolgreich abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="5904d-162">Actor reminder that completed successfully.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5904d-163">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5904d-163">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-164">Diese Methode wird aufgerufen, wenn eine Erinnerung ausgelöst wird, schließt die Ausführung der zugehörige Rückruf <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" /> erfolgreich.</span><span class="sxs-lookup"><span data-stu-id="5904d-164">This method is invoked when a reminder fires and finishes executing its callback <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" /> successfully.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5904d-165">Eine Aufgabe, die asynchrone Erinnerung Rückruf abgeschlossenen Benachrichtigung Verarbeitung darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-165">A task that represents the asynchronous reminder callback completed notification processing.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.RemoveActorAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#RemoveActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider/&lt;Microsoft-ServiceFabric-Actors-Runtime-IActorStateProvider-RemoveActorAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="5904d-166">Die ID des Akteurs, für den Status zu entfernt.</span><span class="sxs-lookup"><span data-stu-id="5904d-166">ID of the actor for which to remove state.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5904d-167">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5904d-167">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-168">Entfernt alle vorhandenen Status und Erinnerungen angegebenen Akteur atomar zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="5904d-168">Removes all the existing states and reminders associated with specified actor atomically.</span></span>
            </summary>
        <returns><span data-ttu-id="5904d-169">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-169">A task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="5904d-170">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5904d-170">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveReminderAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.SaveReminderAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveReminderAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#SaveReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
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
        <param name="actorId"><span data-ttu-id="5904d-171">Die ID des Akteurs, für die die Erinnerung zu speichern.</span><span class="sxs-lookup"><span data-stu-id="5904d-171">The ID of the actor for which to save the reminder.</span></span></param>
        <param name="reminder"><span data-ttu-id="5904d-172">Der Akteur Erinnerung zu speichern.</span><span class="sxs-lookup"><span data-stu-id="5904d-172">The actor reminder to save.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5904d-173">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5904d-173">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-174">Speichert die angegebenen Akteur Erinnerung an.</span><span class="sxs-lookup"><span data-stu-id="5904d-174">Saves the specified actor reminder.</span></span> <span data-ttu-id="5904d-175">Wenn eine Akteur Erinnerung mit dem angegebenen Namen nicht vorhanden ist, fügt es hinzu, dass die Akteur Erinnerung andernfalls vorhandenen Akteur Erinnerung mit demselben Namen aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="5904d-175">If an actor reminder with given name does not exist, it adds the actor reminder otherwise existing actor reminder with same name is updated.</span></span> 
            </summary>
        <returns><span data-ttu-id="5904d-176">Eine Aufgabe, die den asynchronen Speichervorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-176">A task that represents the asynchronous save operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="5904d-177">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5904d-177">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.SaveStateAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; stateChanges, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class System.Collections.Generic.IReadOnlyCollection`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; stateChanges, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#SaveStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange},System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider/&lt;Microsoft-ServiceFabric-Actors-Runtime-IActorStateProvider-SaveStateAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="stateChanges" Type="System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="5904d-178">Die ID des Akteurs, für die die statusänderungen zu speichern.</span><span class="sxs-lookup"><span data-stu-id="5904d-178">The ID of the actor for which to save the state changes.</span></span></param>
        <param name="stateChanges"><span data-ttu-id="5904d-179">Die Auflistung von Zustandsänderungen zu speichern.</span><span class="sxs-lookup"><span data-stu-id="5904d-179">The collection of state changes to save.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5904d-180">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5904d-180">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-181">Speichert den angegebenen Berechtigungssatz Akteur Zustandsänderungen atomar an.</span><span class="sxs-lookup"><span data-stu-id="5904d-181">Saves the specified set of actor state changes atomically.</span></span>
            </summary>
        <returns><span data-ttu-id="5904d-182">Eine Aufgabe, die den asynchronen Speichervorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-182">A task that represents the asynchronous save operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="5904d-183">Die Auflistung von Zustandsänderungen sollte nur ein Element für einen bestimmten Zustand enthalten.</span><span class="sxs-lookup"><span data-stu-id="5904d-183">The collection of state changes should contain only one item for a given state name.</span></span>
            <span data-ttu-id="5904d-184">Der Speichervorgang Vorgang schlägt fehl, auf den Versuch, eine actorzustands hinzuzufügen, die bereits vorhanden ist oder aktualisieren/entfernen einen Akteur-Zustand, der nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5904d-184">The save operation will fail on trying to add an actor state which already exists or update/remove an actor state which does not exist.</span></span>
            </remarks>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="5904d-185">Wenn <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" /> ist<see cref="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.None" /></span><span class="sxs-lookup"><span data-stu-id="5904d-185">When <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" /> is <see cref="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.None" /></span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="5904d-186">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5904d-186">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements IStateProviderReplica.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5904d-187">Bricht einen Zustand Anbieter Replikat erzwungen ab.</span><span class="sxs-lookup"><span data-stu-id="5904d-187">Forcefully abort the state provider replica.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="5904d-188">Dies tritt normalerweise auf, wenn auf dem Knoten ein dauerhafter Fehler erkannt wird oder wenn das Replikat Lebenszyklus aufgrund von internen Fehlern von Service Fabric zuverlässig verwalten kann.</span><span class="sxs-lookup"><span data-stu-id="5904d-188">This generally occurs when a permanent fault is detected on the node, or when Service Fabric cannot reliably manage the replica's life-cycle due to internal failures.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.BackupAsync (Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Function BackupAsync (backupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean))) As Task Implements IStateProviderReplica.BackupAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="backupCallback"><span data-ttu-id="5904d-189">Rückruf, der aufgerufen wird, wenn sich der Sicherungsordner lokal erstellt wurde, und kann jetzt aus dem Knoten verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="5904d-189">Callback to be called when the backup folder has been created locally and is ready to be moved out of the node.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-190">Führt eine vollständige Sicherung der Status, die von dieser Akteur State-Anbieter verwaltet werden</span><span class="sxs-lookup"><span data-stu-id="5904d-190">Performs a full backup of state managed by this actor state provider</span></span>
            </summary>
        <returns><span data-ttu-id="5904d-191">Eine Aufgabe, die den asynchronen backup-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-191">Task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="5904d-192">Sicherung/Wiederherstellung wird nicht von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.</span><span class="sxs-lookup"><span data-stu-id="5904d-192">Backup/restore is not supported by <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.BackupAsync (Microsoft.ServiceFabric.Data.BackupOption option, TimeSpan timeout, System.Threading.CancellationToken cancellationToken, Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupOption option, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken, class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="option" Type="Microsoft.ServiceFabric.Data.BackupOption" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="option"><span data-ttu-id="5904d-193">Die Option für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="5904d-193">The option for the backup.</span></span></param>
        <param name="timeout"><span data-ttu-id="5904d-194">Das Timeout für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="5904d-194">The timeout for the backup.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5904d-195">Das Abbruchtoken, das für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="5904d-195">The cancellation token for the backup.</span></span></param>
        <param name="backupCallback"><span data-ttu-id="5904d-196">Der Rückruf aufgerufen werden, sobald der Sicherungsordner bereit ist.</span><span class="sxs-lookup"><span data-stu-id="5904d-196">The callback to be called once the backup folder is ready.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-197">Führt die Sicherung des Zustands, die von diesem Anbieter der Akteur Zustand verwaltet.</span><span class="sxs-lookup"><span data-stu-id="5904d-197">Performs backup of state managed by this actor sate provider.</span></span>
            </summary>
        <returns><span data-ttu-id="5904d-198">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-198">Task that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="5904d-199">Sicherung/Wiederherstellung wird nicht von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.</span><span class="sxs-lookup"><span data-stu-id="5904d-199">Backup/restore is not supported by <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider/&lt;Microsoft-ServiceFabric-Data-IStateProviderReplica-ChangeRoleAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole"><span data-ttu-id="5904d-200">Die neue replikatrolle, z. B. Primary oder Secondary sein.</span><span class="sxs-lookup"><span data-stu-id="5904d-200">The new replica role, such as primary or secondary.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5904d-201">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5904d-201">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-202">Dem State-Anbieter-Replikat zu benachrichtigen, dass seine Rolle geändert hat, z. B. um Primary oder Secondary sein.</span><span class="sxs-lookup"><span data-stu-id="5904d-202">Notify the state provider replica that its role is changing, for example to Primary or Secondary.</span></span>
            </summary>
        <returns><span data-ttu-id="5904d-203">Eine Aufgabe, die den asynchronen Rolle Änderungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-203">Task that represents the asynchronous change role operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="5904d-204">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5904d-204">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-205">Geschlossen Sie das Replikat der State-Anbieter ordnungsgemäß werden.</span><span class="sxs-lookup"><span data-stu-id="5904d-205">Gracefully close the state provider replica.</span></span>
            </summary>
        <returns><span data-ttu-id="5904d-206">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-206">Task that represents the asynchronous close operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="5904d-207">Dies tritt normalerweise auf, wenn das Replikat Code ein Upgrade wird, das Replikat aufgrund des Lastenausgleichs verschoben wird oder ein vorübergehender Fehler erkannt wird.</span><span class="sxs-lookup"><span data-stu-id="5904d-207">This generally occurs when the replica's code is being upgrade, the replica is being moved due to load balancing, or a transient fault is detected.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Sub Initialize (initializationParameters As StatefulServiceInitializationParameters) Implements IStateProviderReplica.Initialize" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters"><span data-ttu-id="5904d-208">Initialisierungsinformationen für Dienst z. B. Dienstnamen, Partitions-Id, Replikat-Id und Code-Paketinformationen.</span><span class="sxs-lookup"><span data-stu-id="5904d-208">Service initialization information such as service name, partition id, replica id, and code package information.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-209">Das Status Anbieter Replikat unter Verwendung des Diensts Initialisierung zu initialisieren.</span><span class="sxs-lookup"><span data-stu-id="5904d-209">Initialize the state provider replica using the service initialization information.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="5904d-210">Keine komplexen Verarbeitung sollte bei der Initialisierung erfolgen.</span><span class="sxs-lookup"><span data-stu-id="5904d-210">No complex processing should be done during Initialize.</span></span> <span data-ttu-id="5904d-211">Teuer oder lang ausgeführte Initialisierung sollte im OpenAsync erfolgen.</span><span class="sxs-lookup"><span data-stu-id="5904d-211">Expensive or long-running initialization should be done in OpenAsync.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; IStateProviderReplica.OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="partition" Type="System.Fabric.IStatefulServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode"><span data-ttu-id="5904d-212">Gibt an, ob es sich um ein neues oder vorhandenes Replikat handelt.</span><span class="sxs-lookup"><span data-stu-id="5904d-212">Indicates whether this is a new or existing replica.</span></span></param>
        <param name="partition"><span data-ttu-id="5904d-213">Die Partition dieses Replikat gehört.</span><span class="sxs-lookup"><span data-stu-id="5904d-213">The partition this replica belongs to.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5904d-214">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5904d-214">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-215">Öffnen Sie das Replikat des Status-Anbieter für die Verwendung an.</span><span class="sxs-lookup"><span data-stu-id="5904d-215">Open the state provider replica for use.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5904d-216">Eine Aufgabe, die den asynchronen Öffnungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-216">Task that represents the asynchronous open operation.</span></span> <span data-ttu-id="5904d-217">Das Ergebnis enthält Replikator für die Replikation des Status zwischen Replikaten Anbieter Status in der Partition verantwortlich.</span><span class="sxs-lookup"><span data-stu-id="5904d-217">The result contains the replicator responsible for replicating state between other state provider replicas in the partition.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="5904d-218">Erweiterte Status anbieterinitialisierung, die Aufgaben zu diesem Zeitpunkt gestartet werden können.</span><span class="sxs-lookup"><span data-stu-id="5904d-218">Extended state provider initialization tasks can be started at this time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.RestoreAsync (string backupFolderPath);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(string backupFolderPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#RestoreAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function RestoreAsync (backupFolderPath As String) As Task Implements IStateProviderReplica.RestoreAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            <span data-ttu-id="5904d-219">Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="5904d-219">The directory where the replica is to be restored from.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5904d-220">Wiederherstellen eine Sicherung von <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> oder <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span><span class="sxs-lookup"><span data-stu-id="5904d-220">Restore a backup taken by <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> or <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span>
            </summary>
        <returns><span data-ttu-id="5904d-221">Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-221">Task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="5904d-222">Sicherung/Wiederherstellung wird nicht von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.</span><span class="sxs-lookup"><span data-stu-id="5904d-222">Backup/restore is not supported by <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.RestoreAsync (string backupFolderPath, Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(string backupFolderPath, valuetype Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
        <Parameter Name="restorePolicy" Type="Microsoft.ServiceFabric.Data.RestorePolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            <span data-ttu-id="5904d-223">Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="5904d-223">The directory where the replica is to be restored from.</span></span>
            </param>
        <param name="restorePolicy"><span data-ttu-id="5904d-224">Die Richtlinie für die Wiederherstellung.</span><span class="sxs-lookup"><span data-stu-id="5904d-224">The restore policy.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5904d-225">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="5904d-225">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5904d-226">Wiederherstellen eine Sicherung von <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> oder <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span><span class="sxs-lookup"><span data-stu-id="5904d-226">Restore a backup taken by <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> or <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span>
            </summary>
        <returns><span data-ttu-id="5904d-227">Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-227">Task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="5904d-228">Sicherung/Wiederherstellung wird nicht von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.</span><span class="sxs-lookup"><span data-stu-id="5904d-228">Backup/restore is not supported by <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; OnDataLossAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; OnDataLossAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.OnDataLossAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnDataLossAsync As Func(Of CancellationToken, Task(Of Boolean))" />
      <MemberSignature Language="F#" Value="member this.OnDataLossAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt;" Usage="Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.OnDataLossAsync" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5904d-229">Ruft ab oder legt die Funktion aufgerufen wird, während der potenziellen Datenverlust.</span><span class="sxs-lookup"><span data-stu-id="5904d-229">Gets or sets the function called during suspected data-loss.</span></span>
            </summary>
        <value>
            <span data-ttu-id="5904d-230">Eine Funktion, die Rückruffunktion Datenverlust darstellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-230">A function representing data-loss callback function.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.OnRestoreCompletedAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnRestoreCompletedAsync As Func(Of CancellationToken, Task)" />
      <MemberSignature Language="F#" Value="member this.OnRestoreCompletedAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&gt;" Usage="Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.OnRestoreCompletedAsync" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5904d-231">Funktion mit dem Namen nach Wiederherstellung wurde auf dem Replikat ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="5904d-231">Function called post restore has been performed on the replica.</span></span>
            </summary>
        <value>
            <span data-ttu-id="5904d-232">Eine Funktion, bei der Wiederherstellung abgeschlossen Rückruffunktion.</span><span class="sxs-lookup"><span data-stu-id="5904d-232">A function representing on restore completed callback function.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IStateProvider.GetCopyContext">
      <MemberSignature Language="C#" Value="System.Fabric.IOperationDataStream IStateProvider.GetCopyContext ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Fabric.IOperationDataStream System.Fabric.IStateProvider.GetCopyContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.System#Fabric#IStateProvider#GetCopyContext" />
      <MemberSignature Language="VB.NET" Value="Function GetCopyContext () As IOperationDataStream Implements IStateProvider.GetCopyContext" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStateProvider.GetCopyContext</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationDataStream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="5904d-233">Kontext auf einem sekundären Replikat erhält, nachdem es erstellt und geöffnet, um den Kontext mit dem primären Replikat zu senden.</span><span class="sxs-lookup"><span data-stu-id="5904d-233">Obtains context on a Secondary replica after it is created and opened to send context to the Primary replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5904d-234">Gibt <see cref="T:System.Fabric.IOperationDataStream" />zurück.</span><span class="sxs-lookup"><span data-stu-id="5904d-234">Returns <see cref="T:System.Fabric.IOperationDataStream" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="5904d-235">Das primäre Replikat analysiert den Kontext und zurücksendet Status über <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />.</span><span class="sxs-lookup"><span data-stu-id="5904d-235">The Primary replica analyzes the context and sends back state via <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />.</span></span></para>
          <para>
            <span data-ttu-id="5904d-236"><see cref="M:System.Fabric.IStateProvider.GetCopyContext" />wird aufgerufen, auf neu erstellt werden, inaktive sekundäre Replikate und bietet einen Mechanismus zum asynchron eine bidirektionale Konversation mit dem primären Replikat hergestellt.</span><span class="sxs-lookup"><span data-stu-id="5904d-236"><see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> is called on newly created, idle Secondary replicas and provides a mechanism to asynchronously establish a bidirectional conversation with the Primary replica.</span></span> <span data-ttu-id="5904d-237">Das sekundäre Replikat sendet <see cref="T:System.Fabric.OperationData" /> Objekte, die mit dem das primäre Replikat den Status des Sammelns von Kontext auf dem sekundären Replikat bestimmen kann.</span><span class="sxs-lookup"><span data-stu-id="5904d-237">The Secondary replica sends <see cref="T:System.Fabric.OperationData" /> objects with which the Primary replica can determine the progress of collecting context on the Secondary replica.</span></span> <span data-ttu-id="5904d-238">Das primäre Replikat sendet seinerseits den erforderlichen Zustand zurück.</span><span class="sxs-lookup"><span data-stu-id="5904d-238">The Primary replica responds by sending the required state back.</span></span>
                <span data-ttu-id="5904d-239">Finden Sie unter <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> an das primäre Replikat für die andere Hälfte des Austausches.</span><span class="sxs-lookup"><span data-stu-id="5904d-239">See <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> at the Primary replica for the other half of the exchange.</span></span> </para>
          <para><span data-ttu-id="5904d-240">Für InMemory-Dienste die <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> Methode wird nicht aufgerufen, da der Status der sekundären Replikate bekannt ist (sie sind leer und benötigen alle Status).</span><span class="sxs-lookup"><span data-stu-id="5904d-240">For in-memory services, the <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> method is not called, as the state of the Secondary replicas is known (they are empty and will require all of the state).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IStateProvider.GetCopyState">
      <MemberSignature Language="C#" Value="System.Fabric.IOperationDataStream IStateProvider.GetCopyState (long upToSequenceNumber, System.Fabric.IOperationDataStream copyContext);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Fabric.IOperationDataStream System.Fabric.IStateProvider.GetCopyState(int64 upToSequenceNumber, class System.Fabric.IOperationDataStream copyContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.System#Fabric#IStateProvider#GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />
      <MemberSignature Language="VB.NET" Value="Function GetCopyState (upToSequenceNumber As Long, copyContext As IOperationDataStream) As IOperationDataStream Implements IStateProvider.GetCopyState" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationDataStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upToSequenceNumber" Type="System.Int64" />
        <Parameter Name="copyContext" Type="System.Fabric.IOperationDataStream" />
      </Parameters>
      <Docs>
        <param name="upToSequenceNumber">
          <para><span data-ttu-id="5904d-241">Die maximale letzte Sequenznummer (LSN), die im Stream über Kopiervorgang platziert werden, sollten die <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="5904d-241">The maximum last sequence number (LSN) that should be placed in the copy stream via the <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> method.</span></span>
            <span data-ttu-id="5904d-242">LSNs, die größer als diese Zahl werden an das sekundäre Replikat als Teil der replikationsdatenstrom über übermittelt die <see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="5904d-242">LSNs greater than this number are delivered to the Secondary replica as a part of the replication stream via the <see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" /> method.</span></span></para>
        </param>
        <param name="copyContext">
          <para><span data-ttu-id="5904d-243">Ein <see cref="T:System.Fabric.IOperationDataStream" /> , enthält die <see cref="T:System.Fabric.OperationData" /> Objekte, die vom sekundären Replikat erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5904d-243">An <see cref="T:System.Fabric.IOperationDataStream" /> that contains the <see cref="T:System.Fabric.OperationData" /> objects that are created by the Secondary replica.</span></span> </para>
        </param>
        <summary>
          <para><span data-ttu-id="5904d-244">Ruft den Status für ein primäres Replikat, das erforderlich sind, um ein sekundäres Replikat zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="5904d-244">Obtains the state on a Primary replica that is required to build a Secondary replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5904d-245">Gibt <see cref="T:System.Fabric.IOperationDataStream" />zurück.</span><span class="sxs-lookup"><span data-stu-id="5904d-245">Returns <see cref="T:System.Fabric.IOperationDataStream" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="5904d-246">Ebenso wie <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> ermöglicht das sekundäre Replikat das primäre Replikat über Kontext an ein <see cref="T:System.Fabric.IOperationDataStream" />, <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> ermöglicht das primäre Replikat antwortet ein <see cref="T:System.Fabric.IOperationDataStream" />.</span><span class="sxs-lookup"><span data-stu-id="5904d-246">Just as <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> enables the Secondary replica to send context to the Primary replica via an <see cref="T:System.Fabric.IOperationDataStream" />, <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> enables the Primary replica to respond with an <see cref="T:System.Fabric.IOperationDataStream" />.</span></span> <span data-ttu-id="5904d-247">Der Datenstrom enthält Objekte, die an das sekundäre Replikat über übermittelt werden die <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> Methode der <see cref="T:System.Fabric.FabricReplicator" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="5904d-247">The stream contains objects that are delivered to the Secondary replica via the <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> method of the <see cref="T:System.Fabric.FabricReplicator" /> class.</span></span> <span data-ttu-id="5904d-248">Implementieren Sie die Objekte <see cref="T:System.Fabric.IOperation" /> und die angegebenen Daten enthalten.</span><span class="sxs-lookup"><span data-stu-id="5904d-248">The objects implement <see cref="T:System.Fabric.IOperation" /> and contain the specified data.</span></span> </para>
          <para> <span data-ttu-id="5904d-249">Wenn das primäre Replikat dieser Aufruf empfängt, sollte er erstellen und Zurückgeben einer anderen <see cref="T:System.Fabric.IOperationDataStream" /> enthält <see cref="T:System.Fabric.OperationData" />.</span><span class="sxs-lookup"><span data-stu-id="5904d-249">When the Primary replica receives this call, it should create and return another <see cref="T:System.Fabric.IOperationDataStream" /> that contains <see cref="T:System.Fabric.OperationData" />.</span></span> <span data-ttu-id="5904d-250"><see cref="T:System.Fabric.OperationData" />Stellt dar, die das sekundäre Replikat benötigt wird, um den aktuellen Stand zu bereitgestellten Daten/Status <paramref name="upToSequenceNumber" /> maximale LSN.</span><span class="sxs-lookup"><span data-stu-id="5904d-250"><see cref="T:System.Fabric.OperationData" /> represents the data/state that the Secondary replica requires to catch up to the provided <paramref name="upToSequenceNumber" /> maximum LSN.</span></span> <span data-ttu-id="5904d-251">Wie viel und welchen Status hat, Versand kann bestimmt werden, über die Kontextinformationen, die das sekundäre Replikat über bereitstellt <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="5904d-251">How much and which state has to be sent can be determined via the context information that the Secondary replica provides via <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> method.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IStateProvider.GetLastCommittedSequenceNumber">
      <MemberSignature Language="C#" Value="long IStateProvider.GetLastCommittedSequenceNumber ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance int64 System.Fabric.IStateProvider.GetLastCommittedSequenceNumber() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.System#Fabric#IStateProvider#GetLastCommittedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Function GetLastCommittedSequenceNumber () As Long Implements IStateProvider.GetLastCommittedSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStateProvider.GetLastCommittedSequenceNumber</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="5904d-252">Ruft die letzte Sequenznummer, die der Dienst ein Commit ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="5904d-252">Obtains the last sequence number that the service has committed.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="5904d-253">Gibt <see cref="T:System.Int64" />zurück.</span><span class="sxs-lookup"><span data-stu-id="5904d-253">Returns <see cref="T:System.Int64" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="5904d-254">Diese Methode wird von einem Dienst aufgerufen, wenn zuerst gestartet wurde, gestartet werden soll, für den Fall, dass sie persistenten Status hat und vermutlich Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="5904d-254">This method is called on a service when it first starts up, in case it has any persistent state, and when data loss is suspected.</span></span> <span data-ttu-id="5904d-255">Beim Start eines zustandsbehafteten dienstreplikats, hat er die Option zum Wiederherstellen von Daten, die beibehalten wurden möglicherweise von früheren Updates.</span><span class="sxs-lookup"><span data-stu-id="5904d-255">When a stateful service replica starts up, it has the option to restore any data that might have persisted from previous updates.</span></span>
            <span data-ttu-id="5904d-256">Wenn ein Zustand, der auf diese Weise wiederhergestellt werden, ist seines aktuellen Fortschritts die letzte geschriebene Sequenznummer für diese Daten an.</span><span class="sxs-lookup"><span data-stu-id="5904d-256">If it restores some state in this manner, its current progress is the last written sequence number for that data.</span></span> <span data-ttu-id="5904d-257">Volatile-Dienst kann einfach 0 zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="5904d-257">A volatile service can simply return 0.</span></span>
            <span data-ttu-id="5904d-258">Beachten Sie, dass diese Methode nicht aufgerufen wird, um eine neue primäre Wahl während eines Failovers, zu bestimmen, da der aktuelle Status für die ein Commit ausgeführt wurde bereits bekannt ist die <see cref="T:System.Fabric.FabricReplicator" /> Klasse zu diesem Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="5904d-258">Note that this method is not called to determine a new primary election during fail-over, because the current committed progress is already known by the <see cref="T:System.Fabric.FabricReplicator" /> class at that time.</span></span> </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IStateProvider.OnDataLossAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;bool&gt; IStateProvider.OnDataLossAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; System.Fabric.IStateProvider.OnDataLossAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.System#Fabric#IStateProvider#OnDataLossAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStateProvider.OnDataLossAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="5904d-259">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5904d-259">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="5904d-260">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5904d-260">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="5904d-261">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="5904d-261">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5904d-262">Gibt an, dass ein schreibquorums Replikate in dieser Replikatsatz verloren gegangen ist und daher Datenverlust aufgetreten sind.</span><span class="sxs-lookup"><span data-stu-id="5904d-262">Indicates that a write quorum of replicas in this replica set  has been lost, and that therefore data loss might have occurred.</span></span> <span data-ttu-id="5904d-263">Die Replikatgruppe besteht aus der Mehrheit der Replikate, die das primäre Replikat enthält.</span><span class="sxs-lookup"><span data-stu-id="5904d-263">The replica set consists of a majority of replicas, which includes the Primary replica.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="5904d-264">Gibt <see cref="T:System.Threading.Tasks.Task`1" /> des Typs <see cref="T:System.Boolean" />, Wert, der angibt, ob der Zustand geändert hat.</span><span class="sxs-lookup"><span data-stu-id="5904d-264">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type <see cref="T:System.Boolean" />, that indicates whether state changed.</span></span> <span data-ttu-id="5904d-265">Die Methode gibt "true", falls es sich ändert, oder wenn es nicht geändert hat, gibt die Methode "false" zurück.</span><span class="sxs-lookup"><span data-stu-id="5904d-265">When it changed, the method returns true or when it did not change, the method returns false.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="5904d-266">Wenn die Service Fabric-Laufzeit einen Fehler des ein Quorum der Replikate, der das primäre Replikat enthält berücksichtigt, wählt ein neues primäres Replikat und sofort ruft diese Methode auf dem neuen primären Replikat.</span><span class="sxs-lookup"><span data-stu-id="5904d-266">When the Service Fabric runtime observes the failure of a quorum of replicas, which includes the Primary replica, it elects a new Primary replica and immediately calls this method on the new Primary replica.</span></span> <span data-ttu-id="5904d-267">Ein primäres Replikat, das eines möglichen Datenverlusts informiert ist die Möglichkeit, den Zustand aus einer externen Datenquelle wiederherstellen oder kann weiterhin mit dem Status ausgeführt wird, die derzeit.</span><span class="sxs-lookup"><span data-stu-id="5904d-267">A Primary replica that is informed of possible data loss can choose to restore its state from some external data source or can continue to run with the state that it currently has.</span></span> <span data-ttu-id="5904d-268">Wenn der Dienst mit seinem aktuellen Zustand ausgeführt werden weiterhin, sollte es "false" von dieser Methode zurückgeben, der gibt an, dass keine Änderung vorgenommen wurde.</span><span class="sxs-lookup"><span data-stu-id="5904d-268">If the service continues to run with its current state, it should return false from this method, which indicates that no state change has been made.</span></span> <span data-ttu-id="5904d-269">Wenn es wiederhergestellt oder geändert Datenbankzustands, z. B. unvollständige Arbeit ein Rollback sollte "true" zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="5904d-269">If it has restored or altered its state, such as rolling back incomplete work, it should return true.</span></span> <span data-ttu-id="5904d-270">Wenn "true" zurückgegeben wird, muss der Status in den anderen Replikaten angenommen werden, falsch zu sein.</span><span class="sxs-lookup"><span data-stu-id="5904d-270">If true is returned, then the state in other replicas must be assumed to be incorrect.</span></span>
            <span data-ttu-id="5904d-271">Aus diesem Grund die Service Fabric-Laufzeit die anderen Replikaten in der Replikatgruppe entfernt und erneut erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5904d-271">Therefore, the Service Fabric runtime removes the other replicas from the replica set and recreates them.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IStateProvider.UpdateEpochAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProvider.UpdateEpochAsync (System.Fabric.Epoch epoch, long previousEpochLastSequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task System.Fabric.IStateProvider.UpdateEpochAsync(valuetype System.Fabric.Epoch epoch, int64 previousEpochLastSequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.System#Fabric#IStateProvider#UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="previousEpochLastSequenceNumber" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para><span data-ttu-id="5904d-272">Die neue <see cref="T:System.Fabric.Epoch" />.</span><span class="sxs-lookup"><span data-stu-id="5904d-272">The new <see cref="T:System.Fabric.Epoch" />.</span></span></para>
        </param>
        <param name="previousEpochLastSequenceNumber">
          <para> <span data-ttu-id="5904d-273">Die maximale Sequenznummer (LSN), die in der vorherigen Epoche beobachtet wurden sollten.</span><span class="sxs-lookup"><span data-stu-id="5904d-273">The maximum sequence number (LSN) that should have been observed in the previous epoch.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="5904d-274">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5904d-274">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="5904d-275">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5904d-275">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="5904d-276">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="5904d-276">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5904d-277">Ein Replikat zeigt an, dass die Konfiguration einer Replikatgruppe aufgrund einer Änderung der geändert oder ändern, mit dem primären Replikat versucht.</span><span class="sxs-lookup"><span data-stu-id="5904d-277">Indicates to a replica that the configuration of a replica set has changed due to a change or attempted change to the Primary replica.</span></span> <span data-ttu-id="5904d-278">Die Änderung tritt aufgrund eines Fehlers oder Lastenausgleich des vorherigen primären Replikats.</span><span class="sxs-lookup"><span data-stu-id="5904d-278">The change occurs due to failure or load balancing of the previous Primary replica.</span></span> <span data-ttu-id="5904d-279">Epoche Änderungen fungieren als einer Barrier-Klasse, indem Sie segmentieren Vorgänge in die genaue Konfiguration Zeiträume, in denen sie von einem bestimmten primären Replikat gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="5904d-279">Epoch changes act as a barrier by segmenting operations into the exact configuration periods in which they were sent by a specific Primary replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5904d-280">Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</span><span class="sxs-lookup"><span data-stu-id="5904d-280">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="5904d-281">Diese Methode wird aufgerufen, weil das primäre Replikat der Replikatgruppe geändert hat, oder eine Änderung Angriffsversuch.</span><span class="sxs-lookup"><span data-stu-id="5904d-281">This method is called because the Primary replica of the replica set has changed, or a change was attempted.</span></span> <span data-ttu-id="5904d-282">Sekundäre Replikate empfangen diese Methode, wenn sie sind im Begriff, das neue primäre Replikat oder, wenn sie nicht zum neuen primären Replikat sind, sie erhalten sie beim Versuch, das neue primäre Replikat aus dem replikationsdatenstrom den ersten Vorgang entnommen werden.</span><span class="sxs-lookup"><span data-stu-id="5904d-282">Secondary replicas receive this method either when they are about to become the new Primary replica, or, if they are not the new Primary replica, they receive it when they attempt to get the first operation from the new Primary replica from the replication stream.</span></span> <span data-ttu-id="5904d-283">Diese Methode möglicherweise von primäre Replikaten gelegentlich angezeigt werden, wenn versucht wird, das primäre Replikat auszutauschen, was nicht gelingt.</span><span class="sxs-lookup"><span data-stu-id="5904d-283">Primary replicas might occasionally receive this method if there is an attempt to swap the Primary replica, which fails.</span></span></para>
          <para><span data-ttu-id="5904d-284">Die Informationen in der <see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" /> -Methode ermöglicht dem Dienst um einen Vektor Status aufrecht ist eine Liste der einzelnen Epoche, die das Replikat empfangen hat und die maximale LSN, die sie enthalten.</span><span class="sxs-lookup"><span data-stu-id="5904d-284">The information in the <see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" /> method enables the service to maintain a progress vector, which is a list of each epoch that the replica has received, and the maximum LSN that they contained.</span></span> <span data-ttu-id="5904d-285">Die Bearbeitung Vektordaten werden zusammen mit den aktuellen angewendeten maximale LSN eignet sich für ein sekundäres Replikat zu beschreiben, wie weit der Vorgang fortgeschritten ist während des Kopiervorgangs zu senden.</span><span class="sxs-lookup"><span data-stu-id="5904d-285">The progress vector data along with the current applied maximum LSN is useful for a Secondary replica to send during the copy operation  to describe how far the operation has progressed.</span></span> <span data-ttu-id="5904d-286">Vergleichen von Fortschritt Vektoren, die während des Kopiervorgangs von sekundären Replikaten empfangen werden kann primäre Replikaten zu bestimmen, ob das sekundäre Replikat auf dem neuesten Stand ist, welchen Status an das sekundäre Replikat gesendet werden muss und gibt an, ob das sekundäre Replikat "false" Fortschritt erzielt hat.</span><span class="sxs-lookup"><span data-stu-id="5904d-286">Comparing progress vectors that are received from Secondary replicas during the copy operation enables Primary replicas to determine whether the Secondary replica is up-to-date, what state must be sent to the Secondary replica, and whether the Secondary replica has made false progress.</span></span> <span data-ttu-id="5904d-287">"False" Status bedeutet, dass es sich bei eine LSN in einer vorherigen Epoche größer als die LSN war, in denen das primäre Replikat empfängt.</span><span class="sxs-lookup"><span data-stu-id="5904d-287">False progress means that an LSN in a previous epoch was greater than the LSN that the Primary replica receives.</span></span> </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>