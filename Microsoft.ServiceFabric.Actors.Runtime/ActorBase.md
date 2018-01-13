<Type Name="ActorBase" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorBase">
  <TypeSignature Language="C#" Value="public abstract class ActorBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ActorBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ActorBase" />
  <TypeSignature Language="F#" Value="type ActorBase = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt die Basisklasse für Akteure dar.
            </summary>
    <remarks>
            Der Basistyp für Akteure, die allgemeine Funktionalität für Akteure, die davon Herleiten bereitstellt <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />.
            Der Status wird über Garbage Collections der Akteur und Fail-Failover beibehalten.
            Speichern und Abrufen des Status wird durch die Akteur-State-Anbieter bereitgestellt. Weitere Informationen finden Sie unter <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> .
            </remarks>
    <altmember cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />
  </Docs>
  <Members>
    <Member MemberName="ActorService">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.ActorService ActorService { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.ActorService ActorService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ActorService" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorService As ActorService" />
      <MemberSignature Language="F#" Value="member this.ActorService : Microsoft.ServiceFabric.Actors.Runtime.ActorService" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ActorService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorService</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die statusbehafteten dienstreplikats, die den Akteur gehostet wird.
            </summary>
        <value>
            Die <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ActorService" /> , die den Akteur hosting zustandsbehafteten dienstreplikats darstellt.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public string ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : string" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen der Anwendung, die den Akteur-Dienst enthält, der dieser Akteur gehostet wird.
            </summary>
        <value>Der Name der Anwendung, die den Akteur-Dienst enthält, der dieser Akteur gehostet wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEvent&lt;TEvent&gt;">
      <MemberSignature Language="C#" Value="protected TEvent GetEvent&lt;TEvent&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance !!TEvent GetEvent&lt;TEvent&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.GetEvent``1" />
      <MemberSignature Language="VB.NET" Value="Protected Function GetEvent(Of TEvent) () As TEvent" />
      <MemberSignature Language="F#" Value="member this.GetEvent : unit -&gt; 'Event" Usage="actorBase.GetEvent " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TEvent</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TEvent" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="TEvent">Der Ereignistyp-Schnittstelle.</typeparam>
        <summary>
            Ruft das Ereignis für die angegebene Schnittstelle ab.
            </summary>
        <returns>Gibt ein Ereignis, das die angegebene Schnittstelle darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReminder">
      <MemberSignature Language="C#" Value="protected Microsoft.ServiceFabric.Actors.Runtime.IActorReminder GetReminder (string reminderName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder GetReminder(string reminderName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.GetReminder(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Function GetReminder (reminderName As String) As IActorReminder" />
      <MemberSignature Language="F#" Value="member this.GetReminder : string -&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" Usage="actorBase.GetReminder reminderName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.IActorReminder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reminderName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="reminderName">Der Name der Erinnerung abgerufen werden soll.</param>
        <summary>
            Ruft die Erinnerung Akteur mit dem angegebenen Namen ab.
            </summary>
        <returns>
            Ein <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" /> , eine Akteur Erinnerung darstellt.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceFabric.Actors.ReminderNotFoundException">Die Erinnerung für den Akteur wurde nicht gefunden.</exception>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.ActorId Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.ActorId Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As ActorId" />
      <MemberSignature Language="F#" Value="member this.Id : Microsoft.ServiceFabric.Actors.ActorId" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorBase.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Identität des dieser Akteur mit dem Akteur-Dienst ab.
            </summary>
        <value>Die <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> für den Akteur.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnActivateAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnActivateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnActivateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnActivateAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnActivateAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OnActivateAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.OnActivateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="actorBase.OnActivateAsync " />
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
            Überschreiben Sie diese Methode zum Initialisieren der Elemente, Zustand initialisieren oder Zeitgeber zu registrieren. Diese Methode wird rechts aufgerufen, nachdem der Akteur aktiviert wird, und vor jeder Methode aufrufen oder Erinnerungen darauf weitergeleitet werden.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehende OnActivateAsync-Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeactivateAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnDeactivateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnDeactivateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnDeactivateAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnDeactivateAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OnDeactivateAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.OnDeactivateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="actorBase.OnDeactivateAsync " />
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
             Überschreiben Sie diese Methode, um alle Ressourcen freizugeben. Diese Methode wird aufgerufen, wenn Akteur deaktiviert (Garbage Collection durch Akteur Common Language Runtime) ist.
             Actor-Vorgänge wie Statusänderungen dürfen von dieser Methode nicht aufgerufen werden.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehende OnDeactivateAsync Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnPostActorMethodAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnPostActorMethodAsync (Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext actorMethodContext);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnPostActorMethodAsync(valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext actorMethodContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPostActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" />
      <MemberSignature Language="F#" Value="abstract member OnPostActorMethodAsync : Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext -&gt; System.Threading.Tasks.Task&#xA;override this.OnPostActorMethodAsync : Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext -&gt; System.Threading.Tasks.Task" Usage="actorBase.OnPostActorMethodAsync actorMethodContext" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorMethodContext" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" />
      </Parameters>
      <Docs>
        <param name="actorMethodContext">
            Ein <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" /> beschreiben die Methode, die vom Akteur-Laufzeit, bevor Sie diese Methode aufgerufen wurde.
            </param>
        <summary>
            Überschreiben Sie diese Methode für eine Aktion ausgeführt, nachdem eine Akteur-Methode die Ausführung beendet ist.
            Diese Methode wird aufgerufen, von Akteur Runtime eine Akteur-Methode Ausführung beendet wurde.
            </summary>
        <returns>
            Gibt eine <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , post, actor-Method-Vorgang darstellt.
            </returns>
        <remarks>
            Diese Methode wird aufgerufen, indem Akteur zur Laufzeit vor: <list type="bullet"> <item> <description>eine Schnittstellenmethode Akteur aufrufen, wenn eine Clientanforderung eingeht.</description> </item> <item> <description>Aufrufen einer Methode auf <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> Schnittstelle, wenn eine Erinnerung ausgelöst wird.</description> </item> <item> <description>Einem timerrückruf aufrufen, wenn Timer ausgelöst wird.</description></item></list></remarks>
      </Docs>
    </Member>
    <Member MemberName="OnPreActorMethodAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnPreActorMethodAsync (Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext actorMethodContext);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnPreActorMethodAsync(valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext actorMethodContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPreActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" />
      <MemberSignature Language="F#" Value="abstract member OnPreActorMethodAsync : Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext -&gt; System.Threading.Tasks.Task&#xA;override this.OnPreActorMethodAsync : Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext -&gt; System.Threading.Tasks.Task" Usage="actorBase.OnPreActorMethodAsync actorMethodContext" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorMethodContext" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" />
      </Parameters>
      <Docs>
        <param name="actorMethodContext">
            Ein <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" /> beschreiben die Methode, die vom Akteur Common Language Runtime nach Abschluss dieser Methode aufgerufen wird.
            </param>
        <summary>
            Überschreiben Sie diese Methode zum Ausführen von Maßnahmen, die vor einem Akteur-Methode aufgerufen wird.
            Diese Methode wird von Akteur Laufzeit aufgerufen, unmittelbar vor eine Akteur-Methode aufrufen.
            </summary>
        <returns>
            Gibt eine <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , actor--Methode Vorgang darstellt.
            </returns>
        <remarks>
            Diese Methode wird aufgerufen, indem Akteur zur Laufzeit vor: <list type="bullet"> <item> <description>eine Schnittstellenmethode Akteur aufrufen, wenn eine Clientanforderung eingeht.</description> </item> <item> <description>Aufrufen einer Methode auf <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> Schnittstelle, wenn eine Erinnerung ausgelöst wird.</description> </item> <item> <description>Einem timerrückruf aufrufen, wenn Timer ausgelöst wird.</description></item></list></remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterReminderAsync">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminder&gt; RegisterReminderAsync (string reminderName, byte[] state, TimeSpan dueTime, TimeSpan period);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder&gt; RegisterReminderAsync(string reminderName, unsigned int8[] state, valuetype System.TimeSpan dueTime, valuetype System.TimeSpan period) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Function RegisterReminderAsync (reminderName As String, state As Byte(), dueTime As TimeSpan, period As TimeSpan) As Task(Of IActorReminder)" />
      <MemberSignature Language="F#" Value="member this.RegisterReminderAsync : string * byte[] * TimeSpan * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminder&gt;" Usage="actorBase.RegisterReminderAsync (reminderName, state, dueTime, period)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.ActorBase/&lt;RegisterReminderAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminder&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reminderName" Type="System.String" />
        <Parameter Name="state" Type="System.Byte[]" />
        <Parameter Name="dueTime" Type="System.TimeSpan" />
        <Parameter Name="period" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="reminderName">Der Name der Erinnerung zu registrieren. Der Name muss jede Akteur eindeutig sein.</param>
        <param name="state">Benutzerstatus für den Aufruf Erinnerung übergeben.</param>
        <param name="dueTime">Die Zeitspanne für die Verzögerung, die Erinnerung zum ersten Mal aufrufen. Geben Sie (-1) Millisekunde an, um den Aufruf zu deaktivieren. Geben Sie 0 (null) fest, um die Erinnerung sofort nach der Registrierung aufzurufen.
            </param>
        <param name="period">
            Das Zeitintervall zwischen den Aufrufen der Erinnerung nach dem ersten Aufruf. Geben Sie (-1) Millisekunde an, um regelmäßige Aufruf zu deaktivieren.
            </param>
        <summary>
            Registriert eine Erinnerung mit der Akteur.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Registrierungsvorgang darstellt. Das Ergebnis des Vorgangs enthält Informationen über die registrierten Erinnerung und wird verwendet, um die Erinnerung Verwendung aufgehoben <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.UnregisterReminderAsync(Microsoft.ServiceFabric.Actors.Runtime.IActorReminder)" />.
            </returns>
        <remarks>
          <para>
            Die Klasse, ableiten von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorBase" /> implementieren müssen <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> Erinnerung Aufrufe zu nutzen. Mehrere Erinnerungen können registriert werden zu einem beliebigen Zeitpunkt eindeutig identifizierte <paramref name="reminderName" />. Vorhandene Erinnerungen können auch durch Aufruf dieser Methode noch einmal aktualisiert werden. Erinnerung Aufrufe werden mit anderen Erinnerungen und andere Akteur Methode Rückrufe synchronisiert.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterTimer">
      <MemberSignature Language="C#" Value="protected Microsoft.ServiceFabric.Actors.Runtime.IActorTimer RegisterTimer (Func&lt;object,System.Threading.Tasks.Task&gt; asyncCallback, object state, TimeSpan dueTime, TimeSpan period);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class Microsoft.ServiceFabric.Actors.Runtime.IActorTimer RegisterTimer(class System.Func`2&lt;object, class System.Threading.Tasks.Task&gt; asyncCallback, object state, valuetype System.TimeSpan dueTime, valuetype System.TimeSpan period) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterTimer(System.Func{System.Object,System.Threading.Tasks.Task},System.Object,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Function RegisterTimer (asyncCallback As Func(Of Object, Task), state As Object, dueTime As TimeSpan, period As TimeSpan) As IActorTimer" />
      <MemberSignature Language="F#" Value="member this.RegisterTimer : Func&lt;obj, System.Threading.Tasks.Task&gt; * obj * TimeSpan * TimeSpan -&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorTimer" Usage="actorBase.RegisterTimer (asyncCallback, state, dueTime, period)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.IActorTimer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncCallback" Type="System.Func&lt;System.Object,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="state" Type="System.Object" />
        <Parameter Name="dueTime" Type="System.TimeSpan" />
        <Parameter Name="period" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="asyncCallback">
            Ein Delegat, der eine aufzurufende Methode aufgerufen werden, wenn der Zeitgeber löst angibt.
            Er verfügt über einen Parameter: das Zustandsobjekt an RegisterTimer übergeben.
            Es gibt eine <see cref="T:System.Threading.Tasks.Task" /> , die den asynchronen Vorgang darstellt.
            </param>
        <param name="state">Ein Objekt mit Informationen, die von der Rückrufmethode verwendet oder null sein.</param>
        <param name="dueTime">Der Anteil für die Verzögerung festzulegen, bevor der asynchrone Rückruf erstmalig aufgerufen wird. Geben Sie „-1“ Millisekunde an, um das Starten des Timers zu verhindern. Geben Sie 0 (null) an, um den Timer sofort zu starten.
            </param>
        <param name="period">
            Das Zeitintervall zwischen den Aufrufen des Rückrufs Async. Geben Sie -1 Millisekunde an, um periodisches Signalisieren zu deaktivieren.</param>
        <summary>
            Registriert einen Zeitgeber für den Akteur.
            </summary>
        <returns>Gibt ein IActorTimer-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceUri">
      <MemberSignature Language="C#" Value="public Uri ServiceUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ServiceUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceUri As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceUri : Uri" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ServiceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den URI des Diensts Akteur, der dieser Akteur gehostet wird.
            </summary>
        <value>Die <see cref="T:System.Uri" /> des Akteurs-Diensts, der dieser Akteur gehostet wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterReminderAsync">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task UnregisterReminderAsync (Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task UnregisterReminderAsync(class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.UnregisterReminderAsync(Microsoft.ServiceFabric.Actors.Runtime.IActorReminder)" />
      <MemberSignature Language="VB.NET" Value="Protected Function UnregisterReminderAsync (reminder As IActorReminder) As Task" />
      <MemberSignature Language="F#" Value="member this.UnregisterReminderAsync : Microsoft.ServiceFabric.Actors.Runtime.IActorReminder -&gt; System.Threading.Tasks.Task" Usage="actorBase.UnregisterReminderAsync reminder" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.ActorBase/&lt;UnregisterReminderAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reminder" Type="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
      </Parameters>
      <Docs>
        <param name="reminder">Der Akteur Erinnerung beim Aufheben der Registrierung.</param>
        <summary>
            Hebt die Registrierung auf eine Erinnerung mit zuvor registriert <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />.
            </summary>
        <returns>
            Eine Aufgabe zurück, die den Aufhebung der Registrierung von asynchronen Vorgang darstellt.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
            Die angegebene Erinnerung ist nicht registriert.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UnregisterTimer">
      <MemberSignature Language="C#" Value="protected void UnregisterTimer (Microsoft.ServiceFabric.Actors.Runtime.IActorTimer timer);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void UnregisterTimer(class Microsoft.ServiceFabric.Actors.Runtime.IActorTimer timer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.UnregisterTimer(Microsoft.ServiceFabric.Actors.Runtime.IActorTimer)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub UnregisterTimer (timer As IActorTimer)" />
      <MemberSignature Language="F#" Value="member this.UnregisterTimer : Microsoft.ServiceFabric.Actors.Runtime.IActorTimer -&gt; unit" Usage="actorBase.UnregisterTimer timer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timer" Type="Microsoft.ServiceFabric.Actors.Runtime.IActorTimer" />
      </Parameters>
      <Docs>
        <param name="timer">Ein IActorTimer Timer darstellt, nicht aufgehoben werden muss.</param>
        <summary>
            Hebt die Registrierung eines Zeitgebers, der zuvor auf dieser Akteur festgelegt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>