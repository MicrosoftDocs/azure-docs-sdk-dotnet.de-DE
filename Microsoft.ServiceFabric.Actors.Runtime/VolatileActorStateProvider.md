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
            Stellt eine Implementierung von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> , in denen actorzustands im Arbeitsspeicher beibehalten wird und flüchtig ist.
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
            Erstellt eine Instanz von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.
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
            Ein <see cref="T:System.Fabric.ReplicatorSettings" /> , Replikator Einstellungen beschreibt.
            </param>
        <summary>
            Erstellt eine Instanz des <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" /> Replikator Einstellungen angegeben.
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
        <param name="actorId">Die ID des Akteurs, die aktiviert wird.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Diese Methode wird im Rahmen des Aktivierungsprozesses des Akteurs, mit der angegebenen Id. aufgerufen. 
            </summary>
        <returns> Eine Aufgabe, die asynchrone Benachrichtigung Verarbeitung von Akteur Aktivierung darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="actorId">Die ID des Akteurs, deren Zustand Vorhandensein überprüft werden soll.</param>
        <param name="stateName">Der Name des Zustands Akteur Vorhandensein überprüft werden soll.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Überprüft, ob zustandsanbieter Akteur eine actorzustands mit dem angegebenen Namen enthält.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Vorgang darstellt. Der Wert von TResult-Parameter ist <c>"true"</c> Wenn Status mit dem angegebenen Namen vorhanden andernfalls ist <c>"false"</c>.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="actorId">Die ID des Akteurs, der die Erinnerung gelöscht.</param>
        <param name="reminderName">Der Name der Erinnerung zu löschen.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Löscht die angegebene Akteur Erinnerung an, falls vorhanden.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="reminderNames">Der Satz von Erinnerungen zu löschen.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Löscht den angegebenen Berechtigungssatz Erinnerungen an.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="actorId">Die ID des Akteurs, für die enumerable erstellt.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Erstellt ein aufzählbares Objekt von allen zugeordneten angegebenen Akteur Ländernamen.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Enumerationsvorgang darstellt. Der Wert von TResult-Parameter ist ein aufzählbares Objekt von dem alle Namen angegebenen Akteur zugeordnet.
            </returns>
        <remarks>
            Der Enumerator, der vom Akteur State-Anbieter zurückgegebene sicher gleichzeitig mit der Lesevorgänge verwendet wird und schreibt in die State-Anbieter. Es stellt eine Momentaufnahme für die konsistente Sicht der State-Anbieter dar.
            </remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="itemsCount">Die Anzahl der zurückzugebenden angeforderten Elemente.</param>
        <param name="continuationToken">
            Ein Fortsetzungstoken, um die Ergebnisse von Abfragen zu starten.
            Ein null-Wert des Fortsetzungstokens bedeutet Zurückgeben von Werten Form Anfang starten.
            </param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Ruft den ActorIds aus der State-Anbieter ab.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang des Aufrufs an Server darstellt.</returns>
        <remarks>
            Die <paramref name="continuationToken" /> ist relativ zu den Status der Akteur State-Anbieter zum Zeitpunkt des Aufrufs dieser API. Wenn sich der Status der Akteur Zustand des Anbieters auftritt (d. h. neue Akteure aktiviert sind oder vorhandene Akteure gelöscht werden) in der Zwischenzeit aufruft, um diese API als auch die Fortsetzung Token vom vorherigen Aufruf (bevor der Status geändert wurde) angegeben ist, wird im Ergebnis können Einträge enthalten in vorherigen Aufrufen bereits abgerufen wurden.
            </remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="actorTypeInfo">Geben Sie die Informationen der Akteurklasse</param>
        <summary>
            Initialisiert die Akteur-State-Anbieter mit Typinformationen des Akteurs Typs zugeordnet.
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
        <param name="cancellationToken">Das Abbruchtoken, das für asynchrone Ladevorgang.</param>
        <summary>
            Lädt alle Erinnerungen, die in der Akteur-State-Anbieter enthalten sind.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchrone Ladevorgang darstellt. Der Wert von TResult-Parameter ist eine Auflistung von alle Akteur Erinnerungen in der Akteur-State-Anbieter enthalten sind.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <typeparam name="T">Der Typ des Werts des actorzustands angegebenen Zustand zugeordnet.</typeparam>
        <param name="actorId">Die ID des Akteurs, für das Laden des Zustands.</param>
        <param name="stateName">Der Name des Zustands Akteur geladen.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Lädt den Akteur-Zustand, der dem angegebenen Zustand zugeordnet.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchrone Ladevorgang darstellt. Der Wert von TResult-Parameter enthält Wert des actorzustands angegebenen Zustand zugeordnet.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException">Der Akteur Zustand, der mit dem angegebenen Namen ist nicht vorhanden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="actorId">ID des Akteurs, der Erinnerung besitzen</param>
        <param name="reminder">Akteur Erinnerung, die erfolgreich abgeschlossen.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Diese Methode wird aufgerufen, wenn eine Erinnerung ausgelöst wird, schließt die Ausführung der zugehörige Rückruf <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" /> erfolgreich.
            </summary>
        <returns>
            Eine Aufgabe, die asynchrone Erinnerung Rückruf abgeschlossenen Benachrichtigung Verarbeitung darstellt.
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
        <param name="actorId">Die ID des Akteurs, für den Status zu entfernt.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Entfernt alle vorhandenen Status und Erinnerungen angegebenen Akteur atomar zugeordnet.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="actorId">Die ID des Akteurs, für die die Erinnerung zu speichern.</param>
        <param name="reminder">Der Akteur Erinnerung zu speichern.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Speichert die angegebenen Akteur Erinnerung an. Wenn eine Akteur Erinnerung mit dem angegebenen Namen nicht vorhanden ist, fügt es hinzu, dass die Akteur Erinnerung andernfalls vorhandenen Akteur Erinnerung mit demselben Namen aktualisiert wird. 
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Speichervorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="actorId">Die ID des Akteurs, für die die statusänderungen zu speichern.</param>
        <param name="stateChanges">Die Auflistung von Zustandsänderungen zu speichern.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Speichert den angegebenen Berechtigungssatz Akteur Zustandsänderungen atomar an.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Speichervorgang darstellt.</returns>
        <remarks>
            Die Auflistung von Zustandsänderungen sollte nur ein Element für einen bestimmten Zustand enthalten.
            Der Speichervorgang Vorgang schlägt fehl, auf den Versuch, eine actorzustands hinzuzufügen, die bereits vorhanden ist oder aktualisieren/entfernen einen Akteur-Zustand, der nicht vorhanden ist.
            </remarks>
        <exception cref="T:System.InvalidOperationException">
            Wenn <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" /> ist<see cref="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.None" /></exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
            Bricht einen Zustand Anbieter Replikat erzwungen ab.
            </summary>
        <remarks>
            Dies tritt normalerweise auf, wenn auf dem Knoten ein dauerhafter Fehler erkannt wird oder wenn das Replikat Lebenszyklus aufgrund von internen Fehlern von Service Fabric zuverlässig verwalten kann.
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
        <param name="backupCallback">Rückruf, der aufgerufen wird, wenn sich der Sicherungsordner lokal erstellt wurde, und kann jetzt aus dem Knoten verschoben werden.</param>
        <summary>
            Führt eine vollständige Sicherung der Status, die von dieser Akteur State-Anbieter verwaltet werden
            </summary>
        <returns>Eine Aufgabe, die den asynchronen backup-Vorgang darstellt.</returns>
        <remarks>
            Sicherung/Wiederherstellung wird nicht von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.
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
        <param name="option">Die Option für die Sicherung.</param>
        <param name="timeout">Das Timeout für die Sicherung.</param>
        <param name="cancellationToken">Das Abbruchtoken, das für die Sicherung.</param>
        <param name="backupCallback">Der Rückruf aufgerufen werden, sobald der Sicherungsordner bereit ist.</param>
        <summary>
            Führt die Sicherung des Zustands, die von diesem Anbieter der Akteur Zustand verwaltet.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>
            Sicherung/Wiederherstellung wird nicht von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.
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
        <param name="newRole">Die neue replikatrolle, z. B. Primary oder Secondary sein.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Dem State-Anbieter-Replikat zu benachrichtigen, dass seine Rolle geändert hat, z. B. um Primary oder Secondary sein.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Rolle Änderungsvorgang darstellt.</returns>
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
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Geschlossen Sie das Replikat der State-Anbieter ordnungsgemäß werden.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>
            Dies tritt normalerweise auf, wenn das Replikat Code ein Upgrade wird, das Replikat aufgrund des Lastenausgleichs verschoben wird oder ein vorübergehender Fehler erkannt wird.
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
        <param name="initializationParameters">Initialisierungsinformationen für Dienst z. B. Dienstnamen, Partitions-Id, Replikat-Id und Code-Paketinformationen.</param>
        <summary>
            Das Status Anbieter Replikat unter Verwendung des Diensts Initialisierung zu initialisieren.
            </summary>
        <remarks>
            Keine komplexen Verarbeitung sollte bei der Initialisierung erfolgen. Teuer oder lang ausgeführte Initialisierung sollte im OpenAsync erfolgen.
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
        <param name="openMode">Gibt an, ob es sich um ein neues oder vorhandenes Replikat handelt.</param>
        <param name="partition">Die Partition dieses Replikat gehört.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Öffnen Sie das Replikat des Status-Anbieter für die Verwendung an.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Öffnungsvorgang darstellt. Das Ergebnis enthält Replikator für die Replikation des Status zwischen Replikaten Anbieter Status in der Partition verantwortlich.
            </returns>
        <remarks>
            Erweiterte Status anbieterinitialisierung, die Aufgaben zu diesem Zeitpunkt gestartet werden können.
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
            Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.
            </param>
        <summary>
            Wiederherstellen eine Sicherung von <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> oder <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</returns>
        <remarks>
            Sicherung/Wiederherstellung wird nicht von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.
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
            Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.
            </param>
        <param name="restorePolicy">Die Richtlinie für die Wiederherstellung.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Wiederherstellen eine Sicherung von <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> oder <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</returns>
        <remarks>
            Sicherung/Wiederherstellung wird nicht von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.
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
            Ruft ab oder legt die Funktion aufgerufen wird, während der potenziellen Datenverlust.
            </summary>
        <value>
            Eine Funktion, die Rückruffunktion Datenverlust darstellt.
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
            Funktion mit dem Namen nach Wiederherstellung wurde auf dem Replikat ausgeführt.
            </summary>
        <value>
            Eine Funktion, bei der Wiederherstellung abgeschlossen Rückruffunktion.
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
          <para>Kontext auf einem sekundären Replikat erhält, nachdem es erstellt und geöffnet, um den Kontext mit dem primären Replikat zu senden.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Fabric.IOperationDataStream" />zurück.</para>
        </returns>
        <remarks>
          <para>Das primäre Replikat analysiert den Kontext und zurücksendet Status über <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />.</para>
          <para>
            <see cref="M:System.Fabric.IStateProvider.GetCopyContext" />wird aufgerufen, auf neu erstellt werden, inaktive sekundäre Replikate und bietet einen Mechanismus zum asynchron eine bidirektionale Konversation mit dem primären Replikat hergestellt. Das sekundäre Replikat sendet <see cref="T:System.Fabric.OperationData" /> Objekte, die mit dem das primäre Replikat den Status des Sammelns von Kontext auf dem sekundären Replikat bestimmen kann. Das primäre Replikat sendet seinerseits den erforderlichen Zustand zurück.
                Finden Sie unter <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> an das primäre Replikat für die andere Hälfte des Austausches. </para>
          <para>Für InMemory-Dienste die <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> Methode wird nicht aufgerufen, da der Status der sekundären Replikate bekannt ist (sie sind leer und benötigen alle Status).</para>
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
          <para>Die maximale letzte Sequenznummer (LSN), die im Stream über Kopiervorgang platziert werden, sollten die <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> Methode.
            LSNs, die größer als diese Zahl werden an das sekundäre Replikat als Teil der replikationsdatenstrom über übermittelt die <see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" /> Methode.</para>
        </param>
        <param name="copyContext">
          <para>Ein <see cref="T:System.Fabric.IOperationDataStream" /> , enthält die <see cref="T:System.Fabric.OperationData" /> Objekte, die vom sekundären Replikat erstellt werden. </para>
        </param>
        <summary>
          <para>Ruft den Status für ein primäres Replikat, das erforderlich sind, um ein sekundäres Replikat zu erstellen.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Fabric.IOperationDataStream" />zurück.</para>
        </returns>
        <remarks>
          <para>Ebenso wie <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> ermöglicht das sekundäre Replikat das primäre Replikat über Kontext an ein <see cref="T:System.Fabric.IOperationDataStream" />, <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> ermöglicht das primäre Replikat antwortet ein <see cref="T:System.Fabric.IOperationDataStream" />. Der Datenstrom enthält Objekte, die an das sekundäre Replikat über übermittelt werden die <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> Methode der <see cref="T:System.Fabric.FabricReplicator" /> Klasse. Implementieren Sie die Objekte <see cref="T:System.Fabric.IOperation" /> und die angegebenen Daten enthalten. </para>
          <para> Wenn das primäre Replikat dieser Aufruf empfängt, sollte er erstellen und Zurückgeben einer anderen <see cref="T:System.Fabric.IOperationDataStream" /> enthält <see cref="T:System.Fabric.OperationData" />. <see cref="T:System.Fabric.OperationData" />Stellt dar, die das sekundäre Replikat benötigt wird, um den aktuellen Stand zu bereitgestellten Daten/Status <paramref name="upToSequenceNumber" /> maximale LSN. Wie viel und welchen Status hat, Versand kann bestimmt werden, über die Kontextinformationen, die das sekundäre Replikat über bereitstellt <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> Methode.</para>
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
          <para>Ruft die letzte Sequenznummer, die der Dienst ein Commit ausgeführt wurde. </para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Int64" />zurück.</para>
        </returns>
        <remarks>
          <para>Diese Methode wird von einem Dienst aufgerufen, wenn zuerst gestartet wurde, gestartet werden soll, für den Fall, dass sie persistenten Status hat und vermutlich Daten verloren gehen. Beim Start eines zustandsbehafteten dienstreplikats, hat er die Option zum Wiederherstellen von Daten, die beibehalten wurden möglicherweise von früheren Updates.
            Wenn ein Zustand, der auf diese Weise wiederhergestellt werden, ist seines aktuellen Fortschritts die letzte geschriebene Sequenznummer für diese Daten an. Volatile-Dienst kann einfach 0 zurückgeben.
            Beachten Sie, dass diese Methode nicht aufgerufen wird, um eine neue primäre Wahl während eines Failovers, zu bestimmen, da der aktuelle Status für die ein Commit ausgeführt wurde bereits bekannt ist die <see cref="T:System.Fabric.FabricReplicator" /> Klasse zu diesem Zeitpunkt. </para>
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
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Gibt an, dass ein schreibquorums Replikate in dieser Replikatsatz verloren gegangen ist und daher Datenverlust aufgetreten sind. Die Replikatgruppe besteht aus der Mehrheit der Replikate, die das primäre Replikat enthält. </para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task`1" /> des Typs <see cref="T:System.Boolean" />, Wert, der angibt, ob der Zustand geändert hat. Die Methode gibt "true", falls es sich ändert, oder wenn es nicht geändert hat, gibt die Methode "false" zurück.</para>
        </returns>
        <remarks>
          <para>Wenn die Service Fabric-Laufzeit einen Fehler des ein Quorum der Replikate, der das primäre Replikat enthält berücksichtigt, wählt ein neues primäres Replikat und sofort ruft diese Methode auf dem neuen primären Replikat. Ein primäres Replikat, das eines möglichen Datenverlusts informiert ist die Möglichkeit, den Zustand aus einer externen Datenquelle wiederherstellen oder kann weiterhin mit dem Status ausgeführt wird, die derzeit. Wenn der Dienst mit seinem aktuellen Zustand ausgeführt werden weiterhin, sollte es "false" von dieser Methode zurückgeben, der gibt an, dass keine Änderung vorgenommen wurde. Wenn es wiederhergestellt oder geändert Datenbankzustands, z. B. unvollständige Arbeit ein Rollback sollte "true" zurückgeben. Wenn "true" zurückgegeben wird, muss der Status in den anderen Replikaten angenommen werden, falsch zu sein.
            Aus diesem Grund die Service Fabric-Laufzeit die anderen Replikaten in der Replikatgruppe entfernt und erneut erstellt werden.</para>
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
          <para>Die neue <see cref="T:System.Fabric.Epoch" />.</para>
        </param>
        <param name="previousEpochLastSequenceNumber">
          <para> Die maximale Sequenznummer (LSN), die in der vorherigen Epoche beobachtet wurden sollten.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ein Replikat zeigt an, dass die Konfiguration einer Replikatgruppe aufgrund einer Änderung der geändert oder ändern, mit dem primären Replikat versucht. Die Änderung tritt aufgrund eines Fehlers oder Lastenausgleich des vorherigen primären Replikats. Epoche Änderungen fungieren als einer Barrier-Klasse, indem Sie segmentieren Vorgänge in die genaue Konfiguration Zeiträume, in denen sie von einem bestimmten primären Replikat gesendet wurden.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</para>
        </returns>
        <remarks>
          <para>Diese Methode wird aufgerufen, weil das primäre Replikat der Replikatgruppe geändert hat, oder eine Änderung Angriffsversuch. Sekundäre Replikate empfangen diese Methode, wenn sie sind im Begriff, das neue primäre Replikat oder, wenn sie nicht zum neuen primären Replikat sind, sie erhalten sie beim Versuch, das neue primäre Replikat aus dem replikationsdatenstrom den ersten Vorgang entnommen werden. Diese Methode möglicherweise von primäre Replikaten gelegentlich angezeigt werden, wenn versucht wird, das primäre Replikat auszutauschen, was nicht gelingt.</para>
          <para>Die Informationen in der <see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" /> -Methode ermöglicht dem Dienst um einen Vektor Status aufrecht ist eine Liste der einzelnen Epoche, die das Replikat empfangen hat und die maximale LSN, die sie enthalten. Die Bearbeitung Vektordaten werden zusammen mit den aktuellen angewendeten maximale LSN eignet sich für ein sekundäres Replikat zu beschreiben, wie weit der Vorgang fortgeschritten ist während des Kopiervorgangs zu senden. Vergleichen von Fortschritt Vektoren, die während des Kopiervorgangs von sekundären Replikaten empfangen werden kann primäre Replikaten zu bestimmen, ob das sekundäre Replikat auf dem neuesten Stand ist, welchen Status an das sekundäre Replikat gesendet werden muss und gibt an, ob das sekundäre Replikat "false" Fortschritt erzielt hat. "False" Status bedeutet, dass es sich bei eine LSN in einer vorherigen Epoche größer als die LSN war, in denen das primäre Replikat empfängt. </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>