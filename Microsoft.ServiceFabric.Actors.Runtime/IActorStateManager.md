<Type Name="IActorStateManager" FullName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager">
  <TypeSignature Language="C#" Value="public interface IActorStateManager" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorStateManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorStateManager" />
  <TypeSignature Language="F#" Value="type IActorStateManager = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Schnittstelle, die Methoden zum Verwalten der Status der verfügbar macht eine <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />.
            Diese Schnittstelle wird implementiert, indem <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.Actor.StateManager" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddOrUpdateStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; AddOrUpdateStateAsync&lt;T&gt; (string stateName, T addValue, Func&lt;string,T,T&gt; updateValueFactory, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; AddOrUpdateStateAsync&lt;T&gt;(string stateName, !!T addValue, class System.Func`3&lt;string, !!T, !!T&gt; updateValueFactory, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.AddOrUpdateStateAsync``1(System.String,``0,System.Func{System.String,``0,``0},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddOrUpdateStateAsync : string * 'T * Func&lt;string, 'T, 'T&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iActorStateManager.AddOrUpdateStateAsync (stateName, addValue, updateValueFactory, cancellationToken)" />
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
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="addValue" Type="T" />
        <Parameter Name="updateValueFactory" Type="System.Func&lt;System.String,T,T&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">Typ des Werts angegebene Statusname zugeordnet.</typeparam>
        <param name="stateName">Der Name des Zustands Akteur hinzufügen oder aktualisieren.</param>
        <param name="addValue">Der Wert des Darstellers Status hinzufügen, wenn er nicht vorhanden ist.</param>
        <param name="updateValueFactory">Factory-Funktion zum Generieren der Wert des actorzustands aktualisieren, wenn er vorhanden ist.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Fügt einen Akteur Zustand mit der angegebenen Zustand, wenn er noch nicht vorhanden oder mit dem Namen des angegebenen Zustand, wird der Status aktualisiert, falls vorhanden. 
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen hinzufügen/aktualisieren Vorgang darstellt. Der Wert von TResult-Parameter enthält Wert des actorzustands, die hinzugefügt/aktualisiert wurde.
            </returns>
        <remarks>
            Der Typ der Statuswert <typeparamref name="T" /> muss <see href="https://msdn.microsoft.com/library/ms731923.aspx">Datenvertrag</see> serialisierbar.
            </remarks>
        <exception cref="T:System.ArgumentNullException"> Der Name des angegebenen Zustand ist null.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
      </Docs>
    </Member>
    <Member MemberName="AddStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddStateAsync&lt;T&gt; (string stateName, T value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddStateAsync&lt;T&gt;(string stateName, !!T value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.AddStateAsync``1(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddStateAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.AddStateAsync (stateName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">Typ des Werts angegebene Statusname zugeordnet.</typeparam>
        <param name="stateName">Name des Zustands Akteur hinzufügen.</param>
        <param name="value">Wert des Darstellers Status hinzufügen.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Fügt einen Akteur State mit angegebenen Status.
            </summary>
        <returns>
            Das Hinzufügen einer Aufgabe, die den asynchronen darstellt.
            </returns>
        <remarks>
            Der Typ der Statuswert <typeparamref name="T" /> muss <see href="https://msdn.microsoft.com/library/ms731923.aspx">Datenvertrag</see> serialisierbar.
            </remarks>
        <exception cref="T:System.InvalidOperationException">
            Ein actorzustands mit Status Name ist bereits vorhanden.
            </exception>
        <exception cref="T:System.ArgumentNullException">Der Name des angegebenen Zustand ist null.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
      </Docs>
    </Member>
    <Member MemberName="ClearCacheAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ClearCacheAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearCacheAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.ClearCacheAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ClearCacheAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.ClearCacheAsync cancellationToken" />
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
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Löscht alle zwischengespeicherten Akteur-Status und Vorgänge nachzufolgen <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" /> seit der letzten Status beim Speichervorgang.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Cache löschen Vorgang darstellt.
            </returns>
        <remarks>
            Alle Vorgänge, die für ausgeführt <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" /> seit dem letzten Speichern des auf das Löschen des Zwischenspeichers deaktiviert sind, und wird im nächsten Speichervorgang nicht enthalten sein.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainsStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsStateAsync (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsStateAsync(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.ContainsStateAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContainsStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iActorStateManager.ContainsStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateName">Der Name des Zustands, Akteur.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Überprüft, ob ein actorzustands mit dem angegebenen Namen vorhanden ist.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Vorgang darstellt. Der Wert von TResult-Parameter ist <c>"true"</c> Wenn Status mit dem angegebenen Namen vorhanden andernfalls ist <c>"false"</c>.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> Der Name des angegebenen Zustand ist null.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddStateAsync&lt;T&gt; (string stateName, T value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddStateAsync&lt;T&gt;(string stateName, !!T value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.GetOrAddStateAsync``1(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddStateAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iActorStateManager.GetOrAddStateAsync (stateName, value, cancellationToken)" />
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
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">Typ des Werts angegebene Statusname zugeordnet.</typeparam>
        <param name="stateName">Der Name des Zustands Akteur zum Abrufen oder hinzufügen.</param>
        <param name="value">Der Wert des Darstellers Status hinzufügen, wenn er nicht vorhanden ist.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Ruft eine actorzustands mit dem Namen angegebenen Status ab, falls vorhanden. Wenn sie nicht vorhanden ist, erstellt und der Zustand "Neu" mit dem angegebenen Namen und Wert.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen stellt abrufen oder hinzufügen. Der Wert von TResult-Parameter den Wert des actorzustands mit enthält gegeben Statusname.
            </returns>
        <remarks>
            Der Typ der Statuswert <typeparamref name="T" /> muss <see href="https://msdn.microsoft.com/library/ms731923.aspx">Datenvertrag</see> serialisierbar.
            </remarks>
        <exception cref="T:System.ArgumentNullException"> Der Name des angegebenen Zustand ist null.
            Geben Sie eine gültigen Status Namenszeichenfolge.</exception>
        <exception cref="T:System.OperationCanceledException">Die Anforderung wurde abgebrochen, unter Verwendung des angegebenen <paramref name="cancellationToken" />.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetStateAsync&lt;T&gt; (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetStateAsync&lt;T&gt;(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.GetStateAsync``1(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iActorStateManager.GetStateAsync (stateName, cancellationToken)" />
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
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">Typ des Werts angegebene Statusname zugeordnet.</typeparam>
        <param name="stateName">Name des abzurufenden Akteur Status.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Ruft ein Akteur Status mit dem angegebenen Namen ab.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Ladevorgang darstellt. Der Wert von TResult-Parameter den Wert des actorzustands mit enthält gegeben Statusname.
            </returns>
        <remarks>
            Der Typ der Statuswert <typeparamref name="T" /> muss <see href="https://msdn.microsoft.com/library/ms731923.aspx">Datenvertrag</see> serialisierbar.
            </remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException">
            Ein actorzustands mit Status Name ist nicht vorhanden.
            </exception>
        <exception cref="T:System.ArgumentNullException">Der Name des angegebenen Zustand ist null.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetStateNamesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; GetStateNamesAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; GetStateNamesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.GetStateNamesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStateNamesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;string&gt;&gt;" Usage="iActorStateManager.GetStateNamesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Erstellt ein aufzählbares Objekt von allen Akteur Ländernamen für aktuelle Akteur.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Enumerationsvorgang darstellt. Der Wert von TResult-Parameter ist ein aufzählbares Objekt von allen Akteur Ländernamen.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveStateAsync (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveStateAsync(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.RemoveStateAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.RemoveStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateName">Name des Zustands Akteur zu entfernen.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Entfernt ein actorzustands mit dem angegebenen Namen.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException">
            Ein actorzustands mit Status Name ist nicht vorhanden.
            </exception>
        <exception cref="T:System.ArgumentNullException"> Der Name des angegebenen Zustand ist null. </exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
      </Docs>
    </Member>
    <Member MemberName="SaveStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveStateAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SaveStateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.SaveStateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SaveStateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.SaveStateAsync cancellationToken" />
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
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Speichert alle zwischengespeicherten statusänderungen (Hinzufügen/Aktualisieren/Entfernen), die seit dem letzten Aufruf von <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.SaveStateAsync(System.Threading.CancellationToken)" /> von Akteur Runtime oder vom Benutzer explizit.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Speichervorgang darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetStateAsync&lt;T&gt; (string stateName, T value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetStateAsync&lt;T&gt;(string stateName, !!T value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.SetStateAsync``1(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStateAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.SetStateAsync (stateName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">Typ des Werts angegebene Statusname zugeordnet.</typeparam>
        <param name="stateName">Name des Zustands Akteur festlegen.</param>
        <param name="value">Der Wert des Darstellers Status.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Legt ein Akteur Zuständen mit angegebenen Statusname angegebenen Wert.
            Wenn ein Akteur Status mit dem angegebenen Namen nicht vorhanden ist, wird er hinzugefügt.
            </summary>
        <returns>
            Eine Aufgabe, die asynchrone Operation darstellt.
            </returns>
        <remarks>
            Der Typ der Statuswert <typeparamref name="T" /> muss <see href="https://msdn.microsoft.com/library/ms731923.aspx">Datenvertrag</see> serialisierbar.
            </remarks>
        <exception cref="T:System.ArgumentNullException">Der Name des angegebenen Zustand ist null.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
      </Docs>
    </Member>
    <Member MemberName="TryAddStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryAddStateAsync&lt;T&gt; (string stateName, T value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryAddStateAsync&lt;T&gt;(string stateName, !!T value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.TryAddStateAsync``1(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryAddStateAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iActorStateManager.TryAddStateAsync (stateName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">Typ des Werts angegebene Statusname zugeordnet.</typeparam>
        <param name="stateName">Name des Zustands Akteur hinzufügen.</param>
        <param name="value">Wert des Darstellers Status hinzufügen.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.
            Dies ist optional und wird standardmäßig auf<see cref="P:System.Threading.CancellationToken.None" /></param>
        <summary>
            Versuche, einen Akteur hinzuzufügen Zuständen mit angegebenen Statusname und Wert. Gibt "false" werden, wenn ein Akteur Status mit dem gleichen Namen ist bereits vorhanden. 
            </summary>
        <returns>
            Das Hinzufügen einer booleschen Aufgabe, die den asynchronen darstellt. Gibt "true" Wenn der Wert erfolgreich hinzugefügt und "false", wenn ein Akteur Status mit dem gleichen Namen bereits vorhanden ist.
            </returns>
        <remarks>
            Der Typ der Statuswert <typeparamref name="T" /> muss <see href="https://msdn.microsoft.com/library/ms731923.aspx">Datenvertrag</see> serialisierbar.
            </remarks>
        <exception cref="T:System.ArgumentNullException">Der Name des angegebenen Zustand ist null.
            Geben Sie eine gültigen Status Namenszeichenfolge.</exception>
        <exception cref="T:System.OperationCanceledException">Die Anforderung wurde abgebrochen, unter Verwendung des angegebenen <paramref name="cancellationToken" />.</exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryGetStateAsync&lt;T&gt; (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; TryGetStateAsync&lt;T&gt;(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.TryGetStateAsync``1(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryGetStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iActorStateManager.TryGetStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">Typ des Werts angegebene Statusname zugeordnet.</typeparam>
        <param name="stateName">Name des abzurufenden Akteur Status.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Versucht, eine actorzustands mit dem angegebenen Namen abzurufen.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Ladevorgang darstellt. Der Wert von TResult-Parameter enthält <see cref="T:Microsoft.ServiceFabric.Data.ConditionalValue`1" /> , der angibt, ob die actorzustands vorhanden ist und der Wert des actorzustands vorhanden.
            </returns>
        <remarks>
            Der Typ der Statuswert <typeparamref name="T" /> muss <see href="https://msdn.microsoft.com/library/ms731923.aspx">Datenvertrag</see> serialisierbar.
            </remarks>
        <exception cref="T:System.ArgumentNullException">Der Name des angegebenen Zustand ist null.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
      </Docs>
    </Member>
    <Member MemberName="TryRemoveStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryRemoveStateAsync (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryRemoveStateAsync(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.TryRemoveStateAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryRemoveStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iActorStateManager.TryRemoveStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateName">Name des Zustands Akteur zu entfernen.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Versucht, eine actorzustands mit dem angegebenen Namen zu entfernen.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt. Der Wert von TResult-Parameter gibt an, ob der Zustand erfolgreich entfernt wurde.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> Der Name des angegebenen Zustand ist null.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
      </Docs>
    </Member>
  </Members>
</Type>