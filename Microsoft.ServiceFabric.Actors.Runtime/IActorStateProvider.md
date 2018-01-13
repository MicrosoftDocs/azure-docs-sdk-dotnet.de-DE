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
            Stellt die Schnittstelle, die ein Akteur State-Anbieter für Akteur-Laufzeit für die Kommunikation zu implementieren muss. 
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
        <param name="actorId">Die ID des Akteurs, die aktiviert wird.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Wird aufgerufen, im Rahmen des Aktivierungsprozesses des Akteurs, mit der angegebenen Akteur-ID.
            </summary>
        <returns>Eine Aufgabe, die asynchrone Akteur Aktivierung Benachrichtigung Verarbeitung darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="actorId">Die ID des Akteurs, deren Zustand Vorhandensein überprüft.</param>
        <param name="stateName">Name des Zustands Akteur Vorhandensein überprüft.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Überprüft, ob zustandsanbieter Akteur eine actorzustands mit dem angegebenen Zustand Namen für die angegebene Akteur-ID enthält
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Vorgang darstellt. Der Wert von TResult-Parameter ist <c>"true"</c> Wenn Status mit dem angegebenen Namen vorhanden andernfalls ist <c>"false"</c>.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="actorId">Die ID des Akteurs, der die Erinnerung gelöscht.</param>
        <param name="reminderName">Der Name der Erinnerung zu löschen.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Löscht die Erinnerung Akteur, mit dem Namen angegebenen Erinnerung, falls vorhanden
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="actorId">Die ID des Akteurs, für die enumerable erstellt.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Erstellt ein aufzählbares Objekt von der alle Statusnamen angegebenen Akteur-ID zugeordnet ist
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
        <param name="numItemsToReturn">Die Anzahl der zurückzugebenden angeforderten Elemente.</param>
        <param name="continuationToken">
            Ein Fortsetzungstoken, um die Ergebnisse von Abfragen zu starten.
            Ein null-Wert des Fortsetzungstokens bedeutet Zurückgeben von Werten Form Anfang starten.
            </param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Ruft die angeforderte Anzahl von der Akteur-ID aus der State-Anbieter ab.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang des Aufrufs an Server darstellt.</returns>
        <remarks>
            Die <paramref name="continuationToken" /> ist relativ zu den Status der Akteur State-Anbieter zum Zeitpunkt des Aufrufs dieser API. Wenn sich der Status der Akteur Zustand des Anbieters auftritt (d. h. neue Akteure aktiviert sind oder vorhandene Akteure gelöscht werden) in der Zwischenzeit aufruft, um diese API als auch die Fortsetzung Token vom vorherigen Aufruf (bevor der Status geändert wurde) angegeben ist, wird im Ergebnis können Einträge enthalten in vorherigen Aufrufen bereits abgerufen wurden.
            </remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="actorTypeInformation">Geben Sie die Informationen der Akteurklasse</param>
        <summary>
            Initialisiert die Akteur-State-Anbieter mit Typinformationen des Akteurs Typs zugeordnet.
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
        <param name="cancellationToken">Abbruchtoken für asynchrone Ladevorgang.</param>
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
        <typeparam name="T">Der Typ des Werts des actorzustands angegebenen Zustand zugeordnet.</typeparam>
        <param name="actorId">Die ID des Akteurs, für das Laden des Zustands.</param>
        <param name="stateName">Name des Zustands Akteur geladen.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Lädt den Namen angegebenen Zustand für die angegebene Akteur-ID zugeordneten Akteur-Zustand
            </summary>
        <returns>
            Eine Aufgabe, die den asynchrone Ladevorgang darstellt. Der Wert von TResult-Parameter enthält Wert des actorzustands angegebenen Zustand zugeordnet.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException">Akteur Zustand, der mit dem angegebenen Namen ist nicht vorhanden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="actorId">ID des Akteurs, der Erinnerung besitzen</param>
        <param name="reminder">Akteur Erinnerung, die erfolgreich abgeschlossen.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Wird aufgerufen, wenn eine Erinnerung ausgelöst wird, und schließt die Ausführung der zugehörige Rückruf <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" /> erfolgreich.
            </summary>
        <returns>
            Eine Aufgabe, die asynchrone Erinnerung Rückruf abgeschlossenen Benachrichtigung Verarbeitung darstellt.
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
        <param name="actorId">Die ID des Akteurs, für den Status zu entfernt.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Entfernt alle vorhandenen Status und Erinnerungen angegebenen Akteur-ID automatisch zugeordnet.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="actorId">Die ID des Akteurs, für die die Erinnerung zu speichern.</param>
        <param name="reminder">Akteur Erinnerung zu speichern.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Speichert die angegebenen Akteur ID Erinnerung an. Wenn eine Akteur Erinnerung mit dem angegebenen Namen nicht vorhanden ist, fügt es hinzu, dass die Akteur Erinnerung andernfalls vorhandenen Akteur Erinnerung mit demselben Namen aktualisiert wird. 
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Speichervorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="actorId">Die ID des Akteurs, für die die statusänderungen zu speichern.</param>
        <param name="stateChanges">Die Auflistung von Zustandsänderungen zu speichern.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Speichert den angegebenen Berechtigungssatz Akteur Zustandsänderungen für die angegebene Akteur-ID atomar.
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
  </Members>
</Type>