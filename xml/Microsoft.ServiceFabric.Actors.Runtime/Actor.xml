<Type Name="Actor" FullName="Microsoft.ServiceFabric.Actors.Runtime.Actor">
  <TypeSignature Language="C#" Value="public abstract class Actor : Microsoft.ServiceFabric.Actors.Runtime.ActorBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Actor extends Microsoft.ServiceFabric.Actors.Runtime.ActorBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Actor&#xA;Inherits ActorBase" />
  <TypeSignature Language="F#" Value="type Actor = class&#xA;    inherit ActorBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Actors.Runtime.ActorBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6fd31-101">Stellt einen Akteur, der mehrere zuverlässige "benannte" Status zugeordnet aufweisen kann.</span><span class="sxs-lookup"><span data-stu-id="6fd31-101">Represents an actor that can have multiple reliable 'named' states associated with it.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="6fd31-102">Der Status wird über Garbage Collections der Akteur und Fail-Failover beibehalten.</span><span class="sxs-lookup"><span data-stu-id="6fd31-102">The state is preserved across actor garbage collections and fail-overs.</span></span> <span data-ttu-id="6fd31-103">Speichern und Abrufen des Zustands wird von der Akteur-State-Anbieter bereitgestellt <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />.</span><span class="sxs-lookup"><span data-stu-id="6fd31-103">The storage and retrieval of the state is provided by the actor state provider <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />.</span></span>
            </remarks>
    <altmember cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorBase" />
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Actor (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService, Microsoft.ServiceFabric.Actors.ActorId actorId);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService, class Microsoft.ServiceFabric.Actors.ActorId actorId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.Actor.#ctor(Microsoft.ServiceFabric.Actors.Runtime.ActorService,Microsoft.ServiceFabric.Actors.ActorId)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.Actor : Microsoft.ServiceFabric.Actors.Runtime.ActorService * Microsoft.ServiceFabric.Actors.ActorId -&gt; Microsoft.ServiceFabric.Actors.Runtime.Actor" Usage="new Microsoft.ServiceFabric.Actors.Runtime.Actor (actorService, actorId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
      </Parameters>
      <Docs>
        <param name="actorService">
            <span data-ttu-id="6fd31-104">Die <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorService" /> dieser Akteur-Instanz gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="6fd31-104">The <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorService" /> that will host this actor instance.</span></span>
            </param>
        <param name="actorId">
            <span data-ttu-id="6fd31-105">Die <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> für diese Instanz Akteur.</span><span class="sxs-lookup"><span data-stu-id="6fd31-105">The <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> for this actor instance.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6fd31-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6fd31-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveStateAsync">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task SaveStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task SaveStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.Actor.SaveStateAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Function SaveStateAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.SaveStateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="actor.SaveStateAsync " />
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
            <span data-ttu-id="6fd31-107">Speichert alle statusänderungen (Hinzufügen/Aktualisieren/Entfernen), die seit dem letzten Aufruf von <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.Actor.SaveStateAsync" />, zu der Akteur State-Anbieter, die der Akteur zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="6fd31-107">Saves all the state changes (add/update/remove) that were made since last call to <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.Actor.SaveStateAsync" />, to the actor state provider associated with the actor.</span></span>
            </summary>
        <returns><span data-ttu-id="6fd31-108">Eine Aufgabe, die den asynchronen Speichervorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6fd31-108">A task that represents the asynchronous save operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateManager">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager StateManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager StateManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.Actor.StateManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateManager As IActorStateManager" />
      <MemberSignature Language="F#" Value="member this.StateManager : Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" Usage="Microsoft.ServiceFabric.Actors.Runtime.Actor.StateManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fd31-109">Ruft den Status-Manager für <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" /> die zum Abrufen/Hinzufügen/Aktualisieren/Entfernen mit dem Namen Zustände verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="6fd31-109">Gets the state manager for <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" /> which can be used to get/add/update/remove named states.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6fd31-110">Ein <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" /> die zum Verwalten des actorzustands verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="6fd31-110">An <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" /> which can be used to manage actor state.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>