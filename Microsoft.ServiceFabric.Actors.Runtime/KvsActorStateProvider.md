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
            Stellt eine Implementierung von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> verwendet <see cref="T:System.Fabric.KeyValueStoreReplica" /> zum Speichern und den Akteur Zustand beibehalten.
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
            Erstellt eine Instanz des <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" /> mit Standardeinstellungen.
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
            Gibt an, ob das Feature für inkrementelle Sicherung zu aktivieren.
            Dadurch wird die <see cref="P:System.Fabric.LocalEseStoreSettings.EnableIncrementalBackup" /> Einstellung.
            </param>
        <summary>
            Erstellt eine Instanz des <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" /> mit den angegebenen Einstellungen.
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
            Gibt an, ob das Feature für inkrementelle Sicherung zu aktivieren.
            Dadurch wird die <see cref="P:System.Fabric.LocalEseStoreSettings.EnableIncrementalBackup" /> Einstellung.
            </param>
        <param name="logTruncationIntervalInMinutes">
            Gibt das Intervall an, nach dem <see cref="T:System.Fabric.KeyValueStoreReplica" /> versucht, lokale truncate Protokolle zu speichern.
            </param>
        <summary>
            Erstellt eine Instanz des <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" /> mit den angegebenen Einstellungen.
            </summary>
        <remarks>
            Wenn eine inkrementelle Sicherung aktiviert ist, für die <see cref="T:System.Fabric.KeyValueStoreReplica" />, es verwendet keine zirkulären Puffer, um ihre Transaktionsprotokolle zu verwalten und in regelmäßigen Abständen schneidet die Protokolle sowohl am primären und sekundären Replikate.
            Der Vorgang Sicherung(en) automatisch schneidet Protokolle ab. Auf dem primären Replikat, wenn keine Benutzer-Sicherung für initiiert wird <paramref name="logTruncationIntervalInMinutes" />, <see cref="T:System.Fabric.KeyValueStoreReplica" /> die Protokolle automatisch abgeschnitten.
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
            Ein <see cref="T:System.Fabric.ReplicatorSettings" /> , Replikator Einstellungen beschreibt.
            </param>
        <param name="localStoreSettings">
            Ein <see cref="T:System.Fabric.LocalStoreSettings" /> , beschreibt die Einstellungen des lokalen Schlüsselwert gespeichert.
            </param>
        <summary>
            Erstellt eine Instanz des <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" /> mit angegebenen Replikator und lokalen Schlüssel-/ Einstellungen speichern.
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
        <param name="actorId">Die ID des Akteurs, deren Zustand Vorhandensein überprüft.</param>
        <param name="stateName">Name des Zustands Akteur Vorhandensein überprüft.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Überprüft, ob die Akteur-State-Anbieter ein actorzustands mit dem angegebenen Namen enthält.
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
        <param name="numItemsToReturn">Die Anzahl der angeforderten zurückzugebenden Elemente.</param>
        <param name="continuationToken">
            Ein Fortsetzungstoken, um die Ergebnisse von Abfragen zu starten.
            Ein null-Wert des Fortsetzungstokens bedeutet Zurückgeben von Werten Form Anfang starten.
            </param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Ruft die ActorIds aus der State-Anbieter ab.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang des Aufrufs an Server darstellt.</returns>
        <remarks>
            Die <paramref name="continuationToken" /> ist relativ zu den Status der Akteur State-Anbieter zum Zeitpunkt des Aufrufs dieser API. Wenn sich der Status der Akteur Zustand des Anbieters auftritt (d. h. neue Akteure aktiviert sind oder vorhandene Akteure gelöscht werden) in der Zwischenzeit aufruft, um diese API als auch die Fortsetzung Token vom vorherigen Aufruf (bevor der Status geändert wurde) angegeben ist, wird im Ergebnis können Einträge enthalten in vorherigen Aufrufen bereits abgerufen wurden.
            </remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
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
        <param name="actorTypeInformation">Geben Sie die Informationen der Akteurklasse</param>
        <summary>
            Initialisiert die Akteur-State-Anbieter mit Typinformationen des Akteurs Typs zugeordnet.
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
        <typeparam name="T">Der Typ des Werts des actorzustands angegebenen Zustand zugeordnet werden soll.</typeparam>
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
        <param name="actorId">Die ID des Akteurs, der Erinnerung besitzen</param>
        <param name="reminder">Der Akteur-Erinnerung, die erfolgreich abgeschlossen.</param>
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
        <param name="backupCallback">Rückruf, der aufgerufen wird, wenn sich der Sicherungsordner lokal erstellt wurde, und kann jetzt aus dem Knoten verschoben werden.</param>
        <summary>
            Führt eine vollständige Sicherung alle zuverlässigen Zustand von dieser Akteur Zustand Anbieter verwaltet werden.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen backup-Vorgang darstellt.</returns>
        <remarks>
            Eine vollständige Sicherung wird mit einem Timeout einer Stunde ausgeführt.
            Boolescher Wert zurückgegeben, die für die BackupCallback Geben Sie an, ob der Dienst konnte erfolgreich den Sicherungsordner in einem externen Speicherort zu verschieben.
            Wenn "false" zurückgegeben wird, löst BackupAsync InvalidOperationException aus der entsprechenden Fehlermeldung BackupCallback "false" zurückgegeben.
            Darüber hinaus wird Sicherung als fehlgeschlagen markiert.
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
        <param name="option">Die Option für die Sicherung.</param>
        <param name="timeout">Das Timeout für die Sicherung.</param>
        <param name="cancellationToken">Das Abbruchtoken, das für die Sicherung.</param>
        <param name="backupCallback">Der Rückruf aufgerufen werden, sobald der Sicherungsordner bereit ist.</param>
        <summary>
            Führt die Sicherung des zuverlässigen Zustand von dieser Akteur Zustand Anbieter verwaltet werden.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>
            KVSActorStateProvider-Sicherung und unterstützt nur vollständige Sicherung aus. KVS einem BackupInfo enthält keine Sicherungsversion.
            Die Version der Sicherung wird festgelegt, ungültig.
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
            Initialisierungsinformationen für Dienst z. B. Dienstnamen, Partitions-Id, Replikat-Id und Code-Paketinformationen.
            </param>
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
            Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.
            Dieser Parameter kann nicht null, leer oder enthält nur Leerzeichen. UNC-Pfade können auch angegeben werden.
            </param>
        <summary>
            Wiederherstellen eine Sicherung von <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> oder <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</returns>
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
            Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.
            Dieser Parameter kann nicht null, leer oder enthält nur Leerzeichen. UNC-Pfade können auch angegeben werden.
            </param>
        <param name="restorePolicy">Die Richtlinie für die Wiederherstellung.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Wiederherstellen eine Sicherung von <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> oder <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</returns>
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
            Die Funktion aufgerufen wird, während der Verdacht Datenverlust.
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
            Funktion wird aufgerufen, nachdem die Datenträgerpartition – Status automatisch vom System wiederhergestellt wurde
            </summary>
        <value>
            Eine Funktion, bei der Wiederherstellung abgeschlossen Rückruffunktion.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>