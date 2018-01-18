<Type Name="IRemindable" FullName="Microsoft.ServiceFabric.Actors.Runtime.IRemindable">
  <TypeSignature Language="C#" Value="public interface IRemindable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRemindable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRemindable" />
  <TypeSignature Language="F#" Value="type IRemindable = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e9a42-101">Schnittstelle, die Akteure implementieren müssen, um mit registriert Erinnerungen nutzen <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />.</span><span class="sxs-lookup"><span data-stu-id="e9a42-101">Interface that actors must implement to consume reminders registered using <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ReceiveReminderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReceiveReminderAsync (string reminderName, byte[] state, TimeSpan dueTime, TimeSpan period);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ReceiveReminderAsync(string reminderName, unsigned int8[] state, valuetype System.TimeSpan dueTime, valuetype System.TimeSpan period) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveReminderAsync (reminderName As String, state As Byte(), dueTime As TimeSpan, period As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member ReceiveReminderAsync : string * byte[] * TimeSpan * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iRemindable.ReceiveReminderAsync (reminderName, state, dueTime, period)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reminderName" Type="System.String" />
        <Parameter Name="state" Type="System.Byte[]" />
        <Parameter Name="dueTime" Type="System.TimeSpan" />
        <Parameter Name="period" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="reminderName"><span data-ttu-id="e9a42-102">Der Name der Erinnerung bereitgestellt, die während der Registrierung</span><span class="sxs-lookup"><span data-stu-id="e9a42-102">The name of reminder provided during registration</span></span></param>
        <param name="state"><span data-ttu-id="e9a42-103">Den Benutzerzustand während der Registrierung bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="e9a42-103">The user state provided during registration.</span></span></param>
        <param name="dueTime"><span data-ttu-id="e9a42-104">Der Aufruf due Standardzeitintervall während der Registrierung.</span><span class="sxs-lookup"><span data-stu-id="e9a42-104">The invocation due time provided during registration.</span></span></param>
        <param name="period"><span data-ttu-id="e9a42-105">Der Aufruf-Zeitraum, der während der Registrierung bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="e9a42-105">The invocation period provided during registration.</span></span></param>
        <summary>
            <span data-ttu-id="e9a42-106">Die Erinnerung-Aufruf wieder aufgerufen wird, wenn eine Akteur Erinnerung ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="e9a42-106">The reminder call back invoked when an actor reminder is triggered.</span></span>
            </summary>
        <returns><span data-ttu-id="e9a42-107">Eine Aufgabe, die den asynchronen Vorgang, der von diesem Rückruf ausgeführten darstellt.</span><span class="sxs-lookup"><span data-stu-id="e9a42-107">A task that represents the asynchronous operation performed by this callback.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="e9a42-108">Der Status dieser Akteur wird von der Laufzeit Akteur nach Abschluss der Aufgabe, die von dieser Methode zurückgegebene gespeichert.</span><span class="sxs-lookup"><span data-stu-id="e9a42-108">The state of this actor is saved by the actor runtime upon completion of the task returned by this method.</span></span> <span data-ttu-id="e9a42-109">Wenn beim Speichern des Zustands ein Fehler auftritt, und klicken Sie dann alle Zustände, die von dieser Akteur zwischengespeichert <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.Actor.StateManager" /> aus zuvor gespeicherten Zustand neu geladen, wenn der nächste Aufruf von Akteur-Methode oder eine Erinnerung tritt auf, und verworfen werden.</span><span class="sxs-lookup"><span data-stu-id="e9a42-109">If an error occurs while saving the state, then all state cached by this actor's <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.Actor.StateManager" /> will be discarded and reloaded from previously saved state when the next actor method or reminder invocation occurs.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>