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
            Stellt einen Akteur, der mehrere zuverlässige "benannte" Status zugeordnet aufweisen kann.
            </summary>
    <remarks>
            Der Status wird über Garbage Collections der Akteur und Fail-Failover beibehalten. Speichern und Abrufen des Zustands wird von der Akteur-State-Anbieter bereitgestellt <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />.
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
            Die <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorService" /> dieser Akteur-Instanz gehostet wird.
            </param>
        <param name="actorId">
            Die <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> für diese Instanz Akteur.
            </param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />-Klasse.
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
            Speichert alle statusänderungen (Hinzufügen/Aktualisieren/Entfernen), die seit dem letzten Aufruf von <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.Actor.SaveStateAsync" />, zu der Akteur State-Anbieter, die der Akteur zugeordnet.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Speichervorgang darstellt.</returns>
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
            Ruft den Status-Manager für <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" /> die zum Abrufen/Hinzufügen/Aktualisieren/Entfernen mit dem Namen Zustände verwendet werden können.
            </summary>
        <value>
            Ein <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" /> die zum Verwalten des actorzustands verwendet werden können.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>