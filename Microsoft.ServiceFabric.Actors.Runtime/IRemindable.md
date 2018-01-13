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
            Schnittstelle, die Akteure implementieren müssen, um mit registriert Erinnerungen nutzen <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />.
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
        <param name="reminderName">Der Name der Erinnerung bereitgestellt, die während der Registrierung</param>
        <param name="state">Den Benutzerzustand während der Registrierung bereitgestellt wird.</param>
        <param name="dueTime">Der Aufruf due Standardzeitintervall während der Registrierung.</param>
        <param name="period">Der Aufruf-Zeitraum, der während der Registrierung bereitgestellt wird.</param>
        <summary>
            Die Erinnerung-Aufruf wieder aufgerufen wird, wenn eine Akteur Erinnerung ausgelöst wird.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang, der von diesem Rückruf ausgeführten darstellt.</returns>
        <remarks>
          <para>Der Status dieser Akteur wird von der Laufzeit Akteur nach Abschluss der Aufgabe, die von dieser Methode zurückgegebene gespeichert. Wenn beim Speichern des Zustands ein Fehler auftritt, und klicken Sie dann alle Zustände, die von dieser Akteur zwischengespeichert <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.Actor.StateManager" /> aus zuvor gespeicherten Zustand neu geladen, wenn der nächste Aufruf von Akteur-Methode oder eine Erinnerung tritt auf, und verworfen werden.
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>