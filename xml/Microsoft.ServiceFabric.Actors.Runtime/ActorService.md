<Type Name="ActorService" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorService">
  <TypeSignature Language="C#" Value="public class ActorService : Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase, Microsoft.ServiceFabric.Actors.IActorService, Microsoft.ServiceFabric.Services.Remoting.IService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActorService extends Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase implements class Microsoft.ServiceFabric.Actors.IActorService, class Microsoft.ServiceFabric.Services.Remoting.IService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorService&#xA;Inherits StatefulServiceBase&#xA;Implements IActorService, IService" />
  <TypeSignature Language="F#" Value="type ActorService = class&#xA;    inherit StatefulServiceBase&#xA;    interface IActorService&#xA;    interface IService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Actors.IActorService</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="d060c-101">Stellt die Basisklasse für Microsoft Service Fabric-basierten zuverlässige Akteure Dienst dar.</span><span class="sxs-lookup"><span data-stu-id="d060c-101">Represents the base class for Microsoft Service Fabric based reliable actors service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="d060c-102">Leiten Sie von dieser Klasse, die einen eigenen benutzerdefinierten Akteur-Dienst zu implementieren, wenn Sie alle Verhalten des Diensts für die Akteure außer Kraft setzen möchten.</span><span class="sxs-lookup"><span data-stu-id="d060c-102">Derive from this class to implement your own custom actor service if you want to override any service level behavior for your actors.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorService (System.Fabric.StatefulServiceContext context, Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInfo, Func&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorService,Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.ActorBase&gt; actorFactory = null, Func&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorBase,Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider,Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager&gt; stateManagerFactory = null, Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider stateProvider = null, Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings settings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.StatefulServiceContext context, class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInfo, class System.Func`3&lt;class Microsoft.ServiceFabric.Actors.Runtime.ActorService, class Microsoft.ServiceFabric.Actors.ActorId, class Microsoft.ServiceFabric.Actors.Runtime.ActorBase&gt; actorFactory, class System.Func`3&lt;class Microsoft.ServiceFabric.Actors.Runtime.ActorBase, class Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider, class Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager&gt; stateManagerFactory, class Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider stateProvider, class Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorService.#ctor(System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation,System.Func{Microsoft.ServiceFabric.Actors.Runtime.ActorService,Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.ActorBase},System.Func{Microsoft.ServiceFabric.Actors.Runtime.ActorBase,Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider,Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager},Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider,Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (context As StatefulServiceContext, actorTypeInfo As ActorTypeInformation, Optional actorFactory As Func(Of ActorService, ActorId, ActorBase) = null, Optional stateManagerFactory As Func(Of ActorBase, IActorStateProvider, IActorStateManager) = null, Optional stateProvider As IActorStateProvider = null, Optional settings As ActorServiceSettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.ActorService : System.Fabric.StatefulServiceContext * Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation * Func&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorService, Microsoft.ServiceFabric.Actors.ActorId, Microsoft.ServiceFabric.Actors.Runtime.ActorBase&gt; * Func&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorBase, Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider, Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager&gt; * Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider * Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings -&gt; Microsoft.ServiceFabric.Actors.Runtime.ActorService" Usage="new Microsoft.ServiceFabric.Actors.Runtime.ActorService (context, actorTypeInfo, actorFactory, stateManagerFactory, stateProvider, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="context" Type="System.Fabric.StatefulServiceContext" />
        <Parameter Name="actorTypeInfo" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />
        <Parameter Name="actorFactory" Type="System.Func&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorService,Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.ActorBase&gt;" />
        <Parameter Name="stateManagerFactory" Type="System.Func&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorBase,Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider,Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager&gt;" />
        <Parameter Name="stateProvider" Type="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />
        <Parameter Name="settings" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings" />
      </Parameters>
      <Docs>
        <param name="context"><span data-ttu-id="d060c-103">Der Kontext der Akteur-Dienst wird unter ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="d060c-103">Service context the actor service is operating under.</span></span></param>
        <param name="actorTypeInfo"><span data-ttu-id="d060c-104">Die Typinformationen des Darstellers.</span><span class="sxs-lookup"><span data-stu-id="d060c-104">The type information of the Actor.</span></span></param>
        <param name="actorFactory"><span data-ttu-id="d060c-105">Die Factorymethode zum Erstellen von Akteur-Objekten.</span><span class="sxs-lookup"><span data-stu-id="d060c-105">The factory method to create Actor objects.</span></span></param>
        <param name="stateManagerFactory"><span data-ttu-id="d060c-106">Die Factorymethode zum Erstellen<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" /></span><span class="sxs-lookup"><span data-stu-id="d060c-106">The factory method to create <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" /></span></span></param>
        <param name="stateProvider"><span data-ttu-id="d060c-107">Die State-Anbieter zum Speichern und den Status der Akteur-Objekte zugreifen.</span><span class="sxs-lookup"><span data-stu-id="d060c-107">The state provider to store and access the state of the Actor objects.</span></span></param>
        <param name="settings"><span data-ttu-id="d060c-108">Die Einstellungen verwendet, um das Verhalten des Diensts Akteur zu konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="d060c-108">The settings used to configure the behavior of the Actor service.</span></span></param>
        <summary>
            <span data-ttu-id="d060c-109">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorService" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d060c-109">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorService" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorTypeInformation">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation ActorTypeInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation ActorTypeInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorService.ActorTypeInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorTypeInformation As ActorTypeInformation" />
      <MemberSignature Language="F#" Value="member this.ActorTypeInformation : Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorService.ActorTypeInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d060c-110">Ruft die ActorTypeInformation für Akteur-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="d060c-110">Gets the ActorTypeInformation for actor service.</span></span>
            </summary>
        <value>
          <span data-ttu-id="d060c-111"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />für die der Akteur, der vom Dienst Replikat gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="d060c-111"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" /> for the actor hosted by the service replica.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceReplicaListeners">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; CreateServiceReplicaListeners ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; CreateServiceReplicaListeners() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorService.CreateServiceReplicaListeners" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateServiceReplicaListeners () As IEnumerable(Of ServiceReplicaListener)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceReplicaListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;" Usage="actorService.CreateServiceReplicaListeners " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d060c-112">Überschreibt <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.CreateServiceReplicaListeners" />.</span><span class="sxs-lookup"><span data-stu-id="d060c-112">Overrides <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.CreateServiceReplicaListeners" />.</span></span>
            </summary>
        <returns><span data-ttu-id="d060c-113">Endpunkt Zeichenfolgenpaare wie {"Endpunkte": {"Listener1": "Endpoint1", "Listener2": "Endpoint2"...}}</span><span class="sxs-lookup"><span data-stu-id="d060c-113">Endpoint string pairs like {"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.IActorService.DeleteActorAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorService.DeleteActorAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.IActorService.DeleteActorAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorService.Microsoft#ServiceFabric#Actors#IActorService#DeleteActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.IActorService.DeleteActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.ActorService/&lt;Microsoft-ServiceFabric-Actors-IActorService-DeleteActorAsync&gt;d__35))</AttributeName>
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
        <param name="actorId"><span data-ttu-id="d060c-114">Die <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> des Akteurs gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="d060c-114">The <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> of the actor to be deleted.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d060c-115">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="d060c-115">Propagates notification that operations should be canceled.</span></span></param>
        <summary>
            <span data-ttu-id="d060c-116">Einen Akteur löscht aus dem Akteur-Dienst.</span><span class="sxs-lookup"><span data-stu-id="d060c-116">Deletes an Actor from the Actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="d060c-117">Eine Aufgabe, die den asynchronen Vorgang des Aufrufs an Server darstellt.</span><span class="sxs-lookup"><span data-stu-id="d060c-117">A task that represents the asynchronous operation of call to server.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="d060c-118">Akteur active werden deaktiviert, und der Zustand von zustandsanbieter werden ebenfalls gelöscht.</span><span class="sxs-lookup"><span data-stu-id="d060c-118">An active actor, will be deactivated and its state will also be deleted from state provider.</span></span></para>
          <para><span data-ttu-id="d060c-119">Ein Status des actorzustands wird von zustandsanbieter gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="d060c-119">An in-active actor's state will be deleted from state provider.</span></span></para>
          <para><span data-ttu-id="d060c-120">Wenn für eine nicht existierende Akteur-Id in das System Diese Methode aufgerufen wird, kann er nicht ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="d060c-120">If this method is called for a non-existent actor id in the system, it will be a no-op.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.IActorService.GetActorsAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.Query.ActorInformation&gt;&gt; IActorService.GetActorsAsync (Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Query.PagedResult`1&lt;class Microsoft.ServiceFabric.Actors.Query.ActorInformation&gt;&gt; Microsoft.ServiceFabric.Actors.IActorService.GetActorsAsync(class Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorService.Microsoft#ServiceFabric#Actors#IActorService#GetActorsAsync(Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.IActorService.GetActorsAsync(Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.Query.ActorInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="Microsoft.ServiceFabric.Actors.Query.ContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="continuationToken"><span data-ttu-id="d060c-121">Ein Fortsetzungstoken, um die Ergebnisse von Abfragen zu starten.</span><span class="sxs-lookup"><span data-stu-id="d060c-121">A continuation token to start querying the results from.</span></span>
            <span data-ttu-id="d060c-122">Ein null-Wert des Fortsetzungstokens bedeutet Zurückgeben von Werten Form Anfang starten.</span><span class="sxs-lookup"><span data-stu-id="d060c-122">A null value of continuation token means start returning values form the beginning.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d060c-123">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="d060c-123">Propagates notification that operations should be canceled.</span></span></param>
        <summary>
            <span data-ttu-id="d060c-124">Ruft die Liste von Akteuren durch Abfragen des Akteur-Diensts ab.</span><span class="sxs-lookup"><span data-stu-id="d060c-124">Gets the list of Actors by querying the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="d060c-125">Eine Aufgabe, die den asynchronen Vorgang des Aufrufs an Server darstellt.</span><span class="sxs-lookup"><span data-stu-id="d060c-125">A task that represents the asynchronous operation of call to server.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorService.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="actorService.OnAbort " />
      <MemberType>Method</MemberType>
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
            <span data-ttu-id="d060c-126">Überschreibt <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnAbort" />.</span><span class="sxs-lookup"><span data-stu-id="d060c-126">Overrides <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnAbort" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnChangeRoleAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorService.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="actorService.OnChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.ActorService/&lt;OnChangeRoleAsync&gt;d__39))</AttributeName>
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
        <param name="newRole"><span data-ttu-id="d060c-127">Die neue Rolle für das Replikat.</span><span class="sxs-lookup"><span data-stu-id="d060c-127">The new role for the replica.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d060c-128">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="d060c-128">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="d060c-129">Überschreibt <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="d060c-129">Overrides <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="d060c-130">Eine Aufgabe, die den asynchronen Vorgang ausgeführt, wenn das Replikat das primäre Element wird darstellt.</span><span class="sxs-lookup"><span data-stu-id="d060c-130">A task that represents the asynchronous operation performed when the replica becomes primary.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnCloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnCloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorService.OnCloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="actorService.OnCloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.ActorService/&lt;OnCloseAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="d060c-131">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="d060c-131">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="d060c-132">Überschreibt <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnCloseAsync(System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="d060c-132">Overrides <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnCloseAsync(System.Threading.CancellationToken)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="d060c-133">Eine Aufgabe, die den asynchronen Vorgang ausgeführt, wenn das Replikat geschlossenem darstellt.</span><span class="sxs-lookup"><span data-stu-id="d060c-133">A task that represents the asynchronous operation performed when the replica is closed.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotingListener">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.RemotingListener RemotingListener { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingListener RemotingListener" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorService.RemotingListener" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemotingListener As RemotingListener" />
      <MemberSignature Language="F#" Value="member this.RemotingListener : Microsoft.ServiceFabric.Services.Remoting.RemotingListener" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorService.RemotingListener" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingListener</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d060c-134">Dies bestimmt, welche Version des Listeners der Akteur-Dienst (V1, V2or Compact) verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="d060c-134">This determines which version(V1,V2or Compact) of actor service listener is being used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task RunAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task RunAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorService.RunAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="actorService.RunAsync cancellationToken" />
      <MemberType>Method</MemberType>
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
        <param name="cancellationToken"><span data-ttu-id="d060c-135">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="d060c-135">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="d060c-136">Überschreibt <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="d060c-136">Overrides <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d060c-137">Eine Aufgabe, die den asynchronen Vorgang des Ladens von Erinnerungen, wenn das Replikat das primäre Element wird darstellt.</span><span class="sxs-lookup"><span data-stu-id="d060c-137">A task that represents the asynchronous operation of loading reminders when the replica becomes primary.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="d060c-138">Wenn Sie diese Methode außer Kraft setzen müssen, stellen Sie sicher, diese Methode aus der überschriebenen Methode aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="d060c-138">If you need to override this method, please make sure to call this method from your overridden method.</span></span>
            <span data-ttu-id="d060c-139">Außerdem sicherstellen, dass Ihre Implementierung der außer Kraft gesetzte Methode entspricht der Richtlinie für die angegebene <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="d060c-139">Also make sure your implementation of overridden method conforms to the guideline specified for <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />.</span></span> 
            <span data-ttu-id="d060c-140"><para>Unterlassen kann dazu führen, dass Failover, eine Neukonfiguration oder ein Upgrade des Ihrer Akteur zum Hängenbleiben und Verfügbarkeit Ihres Diensts auswirken kann.</para></span><span class="sxs-lookup"><span data-stu-id="d060c-140"><para> Failing to do so can cause failover, reconfiguration or upgrade of your actor service to get stuck and can impact availibility of your service. </para></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings Settings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorService.Settings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Settings As ActorServiceSettings" />
      <MemberSignature Language="F#" Value="member this.Settings : Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorService.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d060c-141">Ruft die Einstellungen für den Dienst Akteur ab.</span><span class="sxs-lookup"><span data-stu-id="d060c-141">Gets the settings for the actor service.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="d060c-142">Einstellungen für den Akteur-Dienst.</span><span class="sxs-lookup"><span data-stu-id="d060c-142">Settings for the actor service.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateProvider">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider StateProvider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider StateProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorService.StateProvider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateProvider As IActorStateProvider" />
      <MemberSignature Language="F#" Value="member this.StateProvider : Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorService.StateProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d060c-143">Ruft eine <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> , die State-Anbieter für den Dienst Akteur darstellt.</span><span class="sxs-lookup"><span data-stu-id="d060c-143">Gets a <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> that represents the state provider for the actor service.</span></span>
            </summary>
        <value>
          <span data-ttu-id="d060c-144"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />die State-Anbieter für den Dienst Akteur darstellt.</span><span class="sxs-lookup"><span data-stu-id="d060c-144"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> representing the state provider for the actor service.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>