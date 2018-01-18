<Type Name="KvsActorStateProvider" FullName="Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider">
  <TypeSignature Language="C#" Value="public sealed class KvsActorStateProvider : Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider, Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit KvsActorStateProvider extends System.Object implements class Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider, class Microsoft.ServiceFabric.Data.IStateProviderReplica, class Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class KvsActorStateProvider&#xA;Implements IActorStateProvider, IStateProviderReplica2" />
  <TypeSignature Language="F#" Value="type KvsActorStateProvider = class&#xA;    interface IActorStateProvider&#xA;    interface IStateProviderReplica2&#xA;    interface IStateProviderReplica&#xA;    interface VolatileLogicalTimeManager.ISnapshotHandler&#xA;    interface IActorStateProviderInternal" />
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
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="f5c0b-101">Stellt eine Implementierung von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> verwendet <see cref="T:System.Fabric.KeyValueStoreReplica" /> zum Speichern und den Akteur Zustand beibehalten.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-101">Provides an implementation of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> which uses <see cref="T:System.Fabric.KeyValueStoreReplica" /> to store and persist the actor state.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KvsActorStateProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f5c0b-102">Erstellt eine Instanz des <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" /> mit Standardeinstellungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-102">Creates an instance of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" /> with default settings.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KvsActorStateProvider (bool enableIncrementalBackup);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool enableIncrementalBackup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.#ctor(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (enableIncrementalBackup As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider : bool -&gt; Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" Usage="new Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider enableIncrementalBackup" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enableIncrementalBackup" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="enableIncrementalBackup">
            <span data-ttu-id="f5c0b-103">Gibt an, ob das Feature für inkrementelle Sicherung zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-103">Indicates whether to enable incremental backup feature.</span></span>
            <span data-ttu-id="f5c0b-104">Dadurch wird die <see cref="P:System.Fabric.LocalEseStoreSettings.EnableIncrementalBackup" /> Einstellung.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-104">This sets the <see cref="P:System.Fabric.LocalEseStoreSettings.EnableIncrementalBackup" /> setting.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5c0b-105">Erstellt eine Instanz des <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" /> mit den angegebenen Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-105">Creates an instance of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" /> with specified settings.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KvsActorStateProvider (bool enableIncrementalBackup, int logTruncationIntervalInMinutes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool enableIncrementalBackup, int32 logTruncationIntervalInMinutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.#ctor(System.Boolean,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (enableIncrementalBackup As Boolean, logTruncationIntervalInMinutes As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider : bool * int -&gt; Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" Usage="new Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider (enableIncrementalBackup, logTruncationIntervalInMinutes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enableIncrementalBackup" Type="System.Boolean" />
        <Parameter Name="logTruncationIntervalInMinutes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="enableIncrementalBackup">
            <span data-ttu-id="f5c0b-106">Gibt an, ob das Feature für inkrementelle Sicherung zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-106">Indicates whether to enable incremental backup feature.</span></span>
            <span data-ttu-id="f5c0b-107">Dadurch wird die <see cref="P:System.Fabric.LocalEseStoreSettings.EnableIncrementalBackup" /> Einstellung.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-107">This sets the <see cref="P:System.Fabric.LocalEseStoreSettings.EnableIncrementalBackup" /> setting.</span></span>
            </param>
        <param name="logTruncationIntervalInMinutes">
            <span data-ttu-id="f5c0b-108">Gibt das Intervall an, nach dem <see cref="T:System.Fabric.KeyValueStoreReplica" /> versucht, lokale truncate Protokolle zu speichern.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-108">Indicates the interval after which <see cref="T:System.Fabric.KeyValueStoreReplica" /> tries to truncate local store logs.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5c0b-109">Erstellt eine Instanz des <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" /> mit den angegebenen Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-109">Creates an instance of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" /> with specified settings.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f5c0b-110">Wenn eine inkrementelle Sicherung aktiviert ist, für die <see cref="T:System.Fabric.KeyValueStoreReplica" />, es verwendet keine zirkulären Puffer, um ihre Transaktionsprotokolle zu verwalten und in regelmäßigen Abständen schneidet die Protokolle sowohl am primären und sekundären Replikate.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-110">When an incremental backup is enabled for <see cref="T:System.Fabric.KeyValueStoreReplica" />, it does not use circular buffer to manage its transaction logs and periodically truncates the logs both on primary and secondary replica(s).</span></span>
            <span data-ttu-id="f5c0b-111">Der Vorgang Sicherung(en) automatisch schneidet Protokolle ab.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-111">The process of taking backup(s) automatically truncates logs.</span></span> <span data-ttu-id="f5c0b-112">Auf dem primären Replikat, wenn keine Benutzer-Sicherung für initiiert wird <paramref name="logTruncationIntervalInMinutes" />, <see cref="T:System.Fabric.KeyValueStoreReplica" /> die Protokolle automatisch abgeschnitten.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-112">On the primary replica, if no user backup is initiated for <paramref name="logTruncationIntervalInMinutes" />, <see cref="T:System.Fabric.KeyValueStoreReplica" /> automatically truncates the logs.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KvsActorStateProvider (System.Fabric.ReplicatorSettings replicatorSettings = null, System.Fabric.LocalStoreSettings localStoreSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ReplicatorSettings replicatorSettings, class System.Fabric.LocalStoreSettings localStoreSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.#ctor(System.Fabric.ReplicatorSettings,System.Fabric.LocalStoreSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider : System.Fabric.ReplicatorSettings * System.Fabric.LocalStoreSettings -&gt; Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" Usage="new Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider (replicatorSettings, localStoreSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
      </Parameters>
      <Docs>
        <param name="replicatorSettings">
            <span data-ttu-id="f5c0b-113">Ein <see cref="T:System.Fabric.ReplicatorSettings" /> , Replikator Einstellungen beschreibt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-113">A <see cref="T:System.Fabric.ReplicatorSettings" /> that describes replicator settings.</span></span>
            </param>
        <param name="localStoreSettings">
            <span data-ttu-id="f5c0b-114">Ein <see cref="T:System.Fabric.LocalStoreSettings" /> , beschreibt die Einstellungen des lokalen Schlüsselwert gespeichert.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-114">A <see cref="T:System.Fabric.LocalStoreSettings" /> that describes local key value store settings.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5c0b-115">Erstellt eine Instanz des <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" /> mit angegebenen Replikator und lokalen Schlüssel-/ Einstellungen speichern.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-115">Creates an instance of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" /> with specified replicator and local key-value store settings.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.ActorActivatedAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#ActorActivatedAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)</InterfaceMember>
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="f5c0b-116">Die ID des Akteurs, die aktiviert wird.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-116">The ID of the actor that is activated.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5c0b-117">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-117">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-118">Diese Methode wird im Rahmen des Aktivierungsprozesses des Akteurs, mit der angegebenen Id. aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-118">This method is invoked as part of the activation process of the actor with the specified Id.</span></span> 
            </summary>
        <returns> <span data-ttu-id="f5c0b-119">Eine Aufgabe, die asynchrone Benachrichtigung Verarbeitung von Akteur Aktivierung darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-119">A task that represents the asynchronous Actor activation notification processing.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f5c0b-120">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-120">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ContainsStateAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;bool&gt; IActorStateProvider.ContainsStateAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ContainsStateAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#ContainsStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
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
        <param name="actorId"><span data-ttu-id="f5c0b-121">Die ID des Akteurs, deren Zustand Vorhandensein überprüft.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-121">ID of the actor for which to check state existence.</span></span></param>
        <param name="stateName"><span data-ttu-id="f5c0b-122">Name des Zustands Akteur Vorhandensein überprüft.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-122">Name of the actor state to check for existence.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5c0b-123">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-123">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-124">Überprüft, ob die Akteur-State-Anbieter ein actorzustands mit dem angegebenen Namen enthält.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-124">Checks whether the actor state provider contains an actor state with specified state name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f5c0b-125">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-125">A task that represents the asynchronous check operation.</span></span> <span data-ttu-id="f5c0b-126">Der Wert von TResult-Parameter ist <c>"true"</c> Wenn Status mit dem angegebenen Namen vorhanden andernfalls ist <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-126">The value of TResult parameter is <c>true</c> if state with specified name exists otherwise <c>false</c>.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f5c0b-127">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-127">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteReminderAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.DeleteReminderAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, string reminderName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteReminderAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, string reminderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#DeleteReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
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
        <param name="actorId"><span data-ttu-id="f5c0b-128">Die ID des Akteurs, der die Erinnerung gelöscht.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-128">The ID of the actor for which to delete the reminder.</span></span></param>
        <param name="reminderName"><span data-ttu-id="f5c0b-129">Der Name der Erinnerung zu löschen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-129">The name of the reminder to delete.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5c0b-130">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-130">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-131">Löscht die angegebene Akteur Erinnerung an, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-131">Deletes the specified actor reminder if it exists.</span></span>
            </summary>
        <returns><span data-ttu-id="f5c0b-132">Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-132">A task that represents the asynchronous delete operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f5c0b-133">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-133">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteRemindersAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.DeleteRemindersAsync (System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection&lt;string&gt;&gt; reminderNames, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteRemindersAsync(class System.Collections.Generic.IReadOnlyDictionary`2&lt;class Microsoft.ServiceFabric.Actors.ActorId, class System.Collections.Generic.IReadOnlyCollection`1&lt;string&gt;&gt; reminderNames, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#DeleteRemindersAsync(System.Collections.Generic.IReadOnlyDictionary{Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{System.String}},System.Threading.CancellationToken)" />
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
        <param name="reminderNames"><span data-ttu-id="f5c0b-134">Der Satz von Erinnerungen zu löschen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-134">The set of reminders to delete.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5c0b-135">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-135">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-136">Löscht den angegebenen Berechtigungssatz Erinnerungen an.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-136">Deletes the specified set of reminders.</span></span>
            </summary>
        <returns><span data-ttu-id="f5c0b-137">Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-137">A task that represents the asynchronous delete operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f5c0b-138">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-138">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.EnumerateStateNamesAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; IActorStateProvider.EnumerateStateNamesAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.EnumerateStateNamesAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#EnumerateStateNamesAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
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
        <param name="actorId"><span data-ttu-id="f5c0b-139">Die ID des Akteurs, für die enumerable erstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-139">The ID of the actor for which to create enumerable.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5c0b-140">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-140">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-141">Erstellt ein aufzählbares Objekt von allen zugeordneten angegebenen Akteur Ländernamen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-141">Creates an enumerable of all the state names associated with specified actor.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f5c0b-142">Eine Aufgabe, die den asynchronen Enumerationsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-142">A task that represents the asynchronous enumeration operation.</span></span> <span data-ttu-id="f5c0b-143">Der Wert von TResult-Parameter ist ein aufzählbares Objekt von dem alle Namen angegebenen Akteur zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-143">The value of TResult parameter is an enumerable of all state names associated with specified actor.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="f5c0b-144">Der Enumerator, der vom Akteur State-Anbieter zurückgegebene sicher gleichzeitig mit der Lesevorgänge verwendet wird und schreibt in die State-Anbieter.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-144">The enumerator returned from actor state provider is safe to use concurrently with reads and writes to the state provider.</span></span> <span data-ttu-id="f5c0b-145">Es stellt eine Momentaufnahme für die konsistente Sicht der State-Anbieter dar.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-145">It represents a snapshot consistent view of the state provider.</span></span>
            </remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f5c0b-146">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-146">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.GetActorsAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;&gt; IActorStateProvider.GetActorsAsync (int numItemsToReturn, Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Query.PagedResult`1&lt;class Microsoft.ServiceFabric.Actors.ActorId&gt;&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.GetActorsAsync(int32 numItemsToReturn, class Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#GetActorsAsync(System.Int32,Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)" />
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
        <Parameter Name="numItemsToReturn" Type="System.Int32" />
        <Parameter Name="continuationToken" Type="Microsoft.ServiceFabric.Actors.Query.ContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="numItemsToReturn"><span data-ttu-id="f5c0b-147">Die Anzahl der angeforderten zurückzugebenden Elemente.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-147">The number of items requested to be returned.</span></span></param>
        <param name="continuationToken">
            <span data-ttu-id="f5c0b-148">Ein Fortsetzungstoken, um die Ergebnisse von Abfragen zu starten.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-148">A continuation token to start querying the results from.</span></span>
            <span data-ttu-id="f5c0b-149">Ein null-Wert des Fortsetzungstokens bedeutet Zurückgeben von Werten Form Anfang starten.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-149">A null value of continuation token means start returning values form the beginning.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="f5c0b-150">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-150">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-151">Ruft die ActorIds aus der State-Anbieter ab.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-151">Gets the ActorIds from the State Provider.</span></span>
            </summary>
        <returns><span data-ttu-id="f5c0b-152">Eine Aufgabe, die den asynchronen Vorgang des Aufrufs an Server darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-152">A task that represents the asynchronous operation of call to server.</span></span></returns>
        <remarks>
            <span data-ttu-id="f5c0b-153">Die <paramref name="continuationToken" /> ist relativ zu den Status der Akteur State-Anbieter zum Zeitpunkt des Aufrufs dieser API.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-153">The <paramref name="continuationToken" /> is relative to the state of actor state provider at the time of invocation of this API.</span></span> <span data-ttu-id="f5c0b-154">Wenn sich der Status der Akteur Zustand des Anbieters auftritt (d. h. neue Akteure aktiviert sind oder vorhandene Akteure gelöscht werden) in der Zwischenzeit aufruft, um diese API als auch die Fortsetzung Token vom vorherigen Aufruf (bevor der Status geändert wurde) angegeben ist, wird im Ergebnis können Einträge enthalten in vorherigen Aufrufen bereits abgerufen wurden.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-154">If the state of actor state provider changes (i.e. new actors are activated or existing actors are deleted) in between calls to this API and the continuation token from previous call (before the state was modified) is supplied, the result may contain entries that were already fetched in previous calls.</span></span>
            </remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f5c0b-155">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-155">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.Initialize">
      <MemberSignature Language="C#" Value="void IActorStateProvider.Initialize (Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInformation);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.Initialize(class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#Initialize(Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation)" />
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
        <Parameter Name="actorTypeInformation" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />
      </Parameters>
      <Docs>
        <param name="actorTypeInformation"><span data-ttu-id="f5c0b-156">Geben Sie die Informationen der Akteurklasse</span><span class="sxs-lookup"><span data-stu-id="f5c0b-156">Type information of the actor class</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-157">Initialisiert die Akteur-State-Anbieter mit Typinformationen des Akteurs Typs zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-157">Initializes the actor state provider with type information of the actor type associated with it.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadRemindersAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt; IActorStateProvider.LoadRemindersAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadRemindersAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#LoadRemindersAsync(System.Threading.CancellationToken)" />
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
        <param name="cancellationToken"><span data-ttu-id="f5c0b-158">Abbruchtoken für asynchrone Ladevorgang.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-158">Cancellation token for asynchronous load operation.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-159">Lädt alle Erinnerungen, die in der Akteur-State-Anbieter enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-159">Loads all the reminders contained in the actor state provider.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f5c0b-160">Eine Aufgabe, die den asynchrone Ladevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-160">A task that represents the asynchronous load operation.</span></span> <span data-ttu-id="f5c0b-161">Der Wert von TResult-Parameter ist eine Auflistung von alle Akteur Erinnerungen in der Akteur-State-Anbieter enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-161">The value of TResult parameter is a collection of all actor reminders contained in the actor state provider.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f5c0b-162">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-162">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IActorStateProvider.LoadStateAsync&lt;T&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadStateAsync&lt;T&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#LoadStateAsync``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
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
        <typeparam name="T"><span data-ttu-id="f5c0b-163">Der Typ des Werts des actorzustands angegebenen Zustand zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-163">The type of value of actor state associated with given state name.</span></span></typeparam>
        <param name="actorId"><span data-ttu-id="f5c0b-164">Die ID des Akteurs, für das Laden des Zustands.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-164">The ID of the actor for which to load the state.</span></span></param>
        <param name="stateName"><span data-ttu-id="f5c0b-165">Der Name des Zustands Akteur geladen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-165">The name of the actor state to load.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5c0b-166">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-166">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-167">Lädt den Akteur-Zustand, der dem angegebenen Zustand zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-167">Loads the actor state associated with the specified state name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f5c0b-168">Eine Aufgabe, die den asynchrone Ladevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-168">A task that represents the asynchronous load operation.</span></span> <span data-ttu-id="f5c0b-169">Der Wert von TResult-Parameter enthält Wert des actorzustands angegebenen Zustand zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-169">The value of TResult parameter contains value of actor state associated with given state name.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException"><span data-ttu-id="f5c0b-170">Der Akteur Zustand, der mit dem angegebenen Namen ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-170">The actor state associated with specified state name does not exist.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f5c0b-171">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-171">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ReminderCallbackCompletedAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.ReminderCallbackCompletedAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ReminderCallbackCompletedAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#ReminderCallbackCompletedAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)" />
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
        <param name="actorId"><span data-ttu-id="f5c0b-172">Die ID des Akteurs, der Erinnerung besitzen</span><span class="sxs-lookup"><span data-stu-id="f5c0b-172">The ID of the actor which own reminder</span></span></param>
        <param name="reminder"><span data-ttu-id="f5c0b-173">Der Akteur-Erinnerung, die erfolgreich abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-173">The actor reminder that completed successfully.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5c0b-174">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-174">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-175">Diese Methode wird aufgerufen, wenn eine Erinnerung ausgelöst wird, schließt die Ausführung der zugehörige Rückruf <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" /> erfolgreich.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-175">This method is invoked when a reminder fires and finishes executing its callback <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" /> successfully.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f5c0b-176">Eine Aufgabe, die asynchrone Erinnerung Rückruf abgeschlossenen Benachrichtigung Verarbeitung darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-176">A task that represents the asynchronous reminder callback completed notification processing.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.RemoveActorAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#RemoveActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)</InterfaceMember>
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="f5c0b-177">Die ID des Akteurs, für den Status zu entfernt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-177">ID of the actor for which to remove state.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5c0b-178">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-178">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-179">Entfernt alle vorhandenen Status und Erinnerungen angegebenen Akteur atomar zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-179">Removes all the existing states and reminders associated with specified actor atomically.</span></span>
            </summary>
        <returns><span data-ttu-id="f5c0b-180">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-180">A task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f5c0b-181">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-181">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveReminderAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.SaveReminderAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveReminderAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#SaveReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)" />
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
        <param name="actorId"><span data-ttu-id="f5c0b-182">Die ID des Akteurs, für die die Erinnerung zu speichern.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-182">The ID of the actor for which to save the reminder.</span></span></param>
        <param name="reminder"><span data-ttu-id="f5c0b-183">Der Akteur Erinnerung zu speichern.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-183">The actor reminder to save.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5c0b-184">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-184">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-185">Speichert die angegebenen Akteur Erinnerung an.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-185">Saves the specified actor reminder.</span></span> <span data-ttu-id="f5c0b-186">Wenn eine Akteur Erinnerung mit dem angegebenen Namen nicht vorhanden ist, fügt es hinzu, dass die Akteur Erinnerung andernfalls vorhandenen Akteur Erinnerung mit demselben Namen aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-186">If an actor reminder with given name does not exist, it adds the actor reminder otherwise existing actor reminder with same name is updated.</span></span> 
            </summary>
        <returns><span data-ttu-id="f5c0b-187">Eine Aufgabe, die den asynchronen Speichervorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-187">A task that represents the asynchronous save operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f5c0b-188">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-188">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.SaveStateAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; stateChanges, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class System.Collections.Generic.IReadOnlyCollection`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; stateChanges, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#SaveStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange},System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange},System.Threading.CancellationToken)</InterfaceMember>
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
        <Parameter Name="stateChanges" Type="System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="f5c0b-189">Die ID des Akteurs, für die die statusänderungen zu speichern.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-189">ID of the actor for which to save the state changes.</span></span></param>
        <param name="stateChanges"><span data-ttu-id="f5c0b-190">Die Auflistung von Zustandsänderungen zu speichern.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-190">Collection of state changes to save.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5c0b-191">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-191">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-192">Speichert den angegebenen Berechtigungssatz Akteur Zustandsänderungen atomar an.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-192">Saves the specified set of actor state changes atomically.</span></span>
            </summary>
        <returns><span data-ttu-id="f5c0b-193">Eine Aufgabe, die den asynchronen Speichervorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-193">A task that represents the asynchronous save operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="f5c0b-194">Die Auflistung von Zustandsänderungen sollte nur ein Element für einen bestimmten Zustand enthalten.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-194">The collection of state changes should contain only one item for a given state name.</span></span>
            <span data-ttu-id="f5c0b-195">Der Speichervorgang Vorgang schlägt fehl, auf den Versuch, eine actorzustands hinzuzufügen, die bereits vorhanden ist oder aktualisieren/entfernen einen Akteur-Zustand, der nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-195">The save operation will fail on trying to add an actor state which already exists or update/remove an actor state which does not exist.</span></span>
            </remarks>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="f5c0b-196">Wenn <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" /> ist<see cref="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.None" /></span><span class="sxs-lookup"><span data-stu-id="f5c0b-196">When <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" /> is <see cref="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.None" /></span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f5c0b-197">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-197">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#Abort" />
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
            <span data-ttu-id="f5c0b-198">Bricht einen Zustand Anbieter Replikat erzwungen ab.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-198">Forcefully abort the state provider replica.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f5c0b-199">Dies tritt normalerweise auf, wenn auf dem Knoten ein dauerhafter Fehler erkannt wird oder wenn das Replikat Lebenszyklus aufgrund von internen Fehlern von Service Fabric zuverlässig verwalten kann.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-199">This generally occurs when a permanent fault is detected on the node, or when Service Fabric cannot reliably manage the replica's life-cycle due to internal failures.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.BackupAsync (Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
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
        <param name="backupCallback"><span data-ttu-id="f5c0b-200">Rückruf, der aufgerufen wird, wenn sich der Sicherungsordner lokal erstellt wurde, und kann jetzt aus dem Knoten verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-200">Callback to be called when the backup folder has been created locally and is ready to be moved out of the node.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-201">Führt eine vollständige Sicherung alle zuverlässigen Zustand von dieser Akteur Zustand Anbieter verwaltet werden.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-201">Performs a full backup of all reliable state managed by this actor sate provider.</span></span>
            </summary>
        <returns><span data-ttu-id="f5c0b-202">Eine Aufgabe, die den asynchronen backup-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-202">Task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="f5c0b-203">Eine vollständige Sicherung wird mit einem Timeout einer Stunde ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-203">A FULL backup will be performed with a one-hour timeout.</span></span>
            <span data-ttu-id="f5c0b-204">Boolescher Wert zurückgegeben, die für die BackupCallback Geben Sie an, ob der Dienst konnte erfolgreich den Sicherungsordner in einem externen Speicherort zu verschieben.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-204">Boolean returned by the backupCallback indicate whether the service was able to successfully move the backup folder to an external location.</span></span>
            <span data-ttu-id="f5c0b-205">Wenn "false" zurückgegeben wird, löst BackupAsync InvalidOperationException aus der entsprechenden Fehlermeldung BackupCallback "false" zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-205">If false is returned, BackupAsync throws InvalidOperationException with the relevant message indicating backupCallback returned false.</span></span>
            <span data-ttu-id="f5c0b-206">Darüber hinaus wird Sicherung als fehlgeschlagen markiert.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-206">Also, backup will be marked as unsuccessful.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.BackupAsync (Microsoft.ServiceFabric.Data.BackupOption option, TimeSpan timeout, System.Threading.CancellationToken cancellationToken, Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupOption option, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken, class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider/&lt;Microsoft-ServiceFabric-Data-IStateProviderReplica-BackupAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
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
        <param name="option"><span data-ttu-id="f5c0b-207">Die Option für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-207">The option for the backup.</span></span></param>
        <param name="timeout"><span data-ttu-id="f5c0b-208">Das Timeout für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-208">The timeout for the backup.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5c0b-209">Das Abbruchtoken, das für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-209">The cancellation token for the backup.</span></span></param>
        <param name="backupCallback"><span data-ttu-id="f5c0b-210">Der Rückruf aufgerufen werden, sobald der Sicherungsordner bereit ist.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-210">The callback to be called once the backup folder is ready.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-211">Führt die Sicherung des zuverlässigen Zustand von dieser Akteur Zustand Anbieter verwaltet werden.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-211">Performs backup of reliable state managed by this actor sate provider.</span></span>
            </summary>
        <returns><span data-ttu-id="f5c0b-212">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-212">Task that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="f5c0b-213">KVSActorStateProvider-Sicherung und unterstützt nur vollständige Sicherung aus.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-213">KVSActorStateProvider Backup only support Full backup.</span></span> <span data-ttu-id="f5c0b-214">KVS einem BackupInfo enthält keine Sicherungsversion.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-214">KVS BackupInfo does not contain backup version.</span></span>
            <span data-ttu-id="f5c0b-215">Die Version der Sicherung wird festgelegt, ungültig.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-215">The Backup version is set to invalid.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
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
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider/&lt;Microsoft-ServiceFabric-Data-IStateProviderReplica-ChangeRoleAsync&gt;d__60))</AttributeName>
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
        <param name="newRole"><span data-ttu-id="f5c0b-216">Die neue replikatrolle, z. B. Primary oder Secondary sein.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-216">The new replica role, such as primary or secondary.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5c0b-217">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-217">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-218">Dem State-Anbieter-Replikat zu benachrichtigen, dass seine Rolle geändert hat, z. B. um Primary oder Secondary sein.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-218">Notify the state provider replica that its role is changing, for example to Primary or Secondary.</span></span>
            </summary>
        <returns><span data-ttu-id="f5c0b-219">Eine Aufgabe, die den asynchronen Rolle Änderungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-219">Task that represents the asynchronous change role operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider/&lt;Microsoft-ServiceFabric-Data-IStateProviderReplica-CloseAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f5c0b-220">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-220">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-221">Geschlossen Sie das Replikat der State-Anbieter ordnungsgemäß werden.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-221">Gracefully close the state provider replica.</span></span>
            </summary>
        <returns><span data-ttu-id="f5c0b-222">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-222">Task that represents the asynchronous close operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="f5c0b-223">Dies tritt normalerweise auf, wenn das Replikat Code ein Upgrade wird, das Replikat aufgrund des Lastenausgleichs verschoben wird oder ein vorübergehender Fehler erkannt wird.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-223">This generally occurs when the replica's code is being upgrade, the replica is being moved due to load balancing, or a transient fault is detected.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
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
        <param name="initializationParameters">
            <span data-ttu-id="f5c0b-224">Initialisierungsinformationen für Dienst z. B. Dienstnamen, Partitions-Id, Replikat-Id und Code-Paketinformationen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-224">Service initialization information such as service name, partition id, replica id, and code package information.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5c0b-225">Das Status Anbieter Replikat unter Verwendung des Diensts Initialisierung zu initialisieren.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-225">Initialize the state provider replica using the service initialization information.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f5c0b-226">Keine komplexen Verarbeitung sollte bei der Initialisierung erfolgen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-226">No complex processing should be done during Initialize.</span></span> <span data-ttu-id="f5c0b-227">Teuer oder lang ausgeführte Initialisierung sollte im OpenAsync erfolgen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-227">Expensive or long-running initialization should be done in OpenAsync.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; IStateProviderReplica.OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
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
        <param name="openMode"><span data-ttu-id="f5c0b-228">Gibt an, ob es sich um ein neues oder vorhandenes Replikat handelt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-228">Indicates whether this is a new or existing replica.</span></span></param>
        <param name="partition"><span data-ttu-id="f5c0b-229">Die Partition dieses Replikat gehört.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-229">The partition this replica belongs to.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5c0b-230">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-230">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-231">Öffnen Sie das Replikat des Status-Anbieter für die Verwendung an.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-231">Open the state provider replica for use.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f5c0b-232">Eine Aufgabe, die den asynchronen Öffnungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-232">Task that represents the asynchronous open operation.</span></span> <span data-ttu-id="f5c0b-233">Das Ergebnis enthält Replikator für die Replikation des Status zwischen Replikaten Anbieter Status in der Partition verantwortlich.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-233">The result contains the replicator responsible for replicating state between other state provider replicas in the partition.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="f5c0b-234">Erweiterte Status anbieterinitialisierung, die Aufgaben zu diesem Zeitpunkt gestartet werden können.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-234">Extended state provider initialization tasks can be started at this time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.RestoreAsync (string backupFolderPath);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(string backupFolderPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#RestoreAsync(System.String)" />
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
            <span data-ttu-id="f5c0b-235">Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-235">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="f5c0b-236">Dieser Parameter kann nicht null, leer oder enthält nur Leerzeichen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-236">This parameter cannot be null, empty or contain just whitespace.</span></span> <span data-ttu-id="f5c0b-237">UNC-Pfade können auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-237">UNC paths may also be provided.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5c0b-238">Wiederherstellen eine Sicherung von <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> oder <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-238">Restore a backup taken by <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> or <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f5c0b-239">Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-239">Task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.RestoreAsync (string backupFolderPath, Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(string backupFolderPath, valuetype Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="f5c0b-240">Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-240">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="f5c0b-241">Dieser Parameter kann nicht null, leer oder enthält nur Leerzeichen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-241">This parameter cannot be null, empty or contain just whitespace.</span></span> <span data-ttu-id="f5c0b-242">UNC-Pfade können auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-242">UNC paths may also be provided.</span></span>
            </param>
        <param name="restorePolicy"><span data-ttu-id="f5c0b-243">Die Richtlinie für die Wiederherstellung.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-243">The restore policy.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5c0b-244">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-244">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="f5c0b-245">Wiederherstellen eine Sicherung von <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> oder <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-245">Restore a backup taken by <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> or <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f5c0b-246">Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-246">Task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; OnDataLossAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; OnDataLossAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.OnDataLossAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnDataLossAsync As Func(Of CancellationToken, Task(Of Boolean))" />
      <MemberSignature Language="F#" Value="member this.OnDataLossAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt;" Usage="Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.OnDataLossAsync" />
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
            <span data-ttu-id="f5c0b-247">Die Funktion aufgerufen wird, während der Verdacht Datenverlust.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-247">The function called during suspected data-loss.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f5c0b-248">Eine Funktion, die Rückruffunktion Datenverlust darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-248">A function representing data-loss callback function.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.OnRestoreCompletedAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnRestoreCompletedAsync As Func(Of CancellationToken, Task)" />
      <MemberSignature Language="F#" Value="member this.OnRestoreCompletedAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&gt;" Usage="Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.OnRestoreCompletedAsync" />
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
            <span data-ttu-id="f5c0b-249">Funktion wird aufgerufen, nachdem die Datenträgerpartition – Status automatisch vom System wiederhergestellt wurde</span><span class="sxs-lookup"><span data-stu-id="f5c0b-249">Function called after the partition state has been restored automatically by the system</span></span>
            </summary>
        <value>
            <span data-ttu-id="f5c0b-250">Eine Funktion, bei der Wiederherstellung abgeschlossen Rückruffunktion.</span><span class="sxs-lookup"><span data-stu-id="f5c0b-250">A function representing on restore completed callback function.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>