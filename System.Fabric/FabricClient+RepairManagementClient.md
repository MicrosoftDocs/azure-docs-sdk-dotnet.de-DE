<Type Name="FabricClient+RepairManagementClient" FullName="System.Fabric.FabricClient+RepairManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.RepairManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/RepairManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.RepairManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.RepairManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.RepairManagementClient = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt Methoden zum Verwalten von Tasks reparieren.</para>
      <para>Diese Klasse unterstützt die Service Fabric-Plattform. Es ist nicht vorgesehen, direkt aus Ihrem Code aufgerufen werden.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CancelRepairTaskAsync (string repairTaskId, long version, bool requestAbort);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CancelRepairTaskAsync(string repairTaskId, int64 version, bool requestAbort) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.CancelRepairTaskAsync(System.String,System.Int64,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelRepairTaskAsync (repairTaskId As String, version As Long, requestAbort As Boolean) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.CancelRepairTaskAsync : string * int64 * bool -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.CancelRepairTaskAsync (repairTaskId, version, requestAbort)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="requestAbort" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para>Die ID des Tasks "Reparieren" werden abgebrochen.</para>
        </param>
        <param name="version">
          <para>Die aktuelle Versionsnummer des Reparaturtasks. Wenn ungleich 0 (null) ist, wird die Anforderung nur erfolgreich, wenn dieser Wert den tatsächlichen aktuellen Wert des Tasks "Reparieren" übereinstimmt. Ist der Wert gleich null, wird keine Versionsüberprüfung ausgeführt.</para>
        </param>
        <param name="requestAbort">
          <para>
            <languageKeyword>"True"</languageKeyword> , wenn die Reparatur so bald wie möglich beendet werden soll, selbst wenn sie bereits begonnen wurde ausgeführt. <languageKeyword>"False"</languageKeyword> , wenn die Reparatur abgebrochen werden sollte, nur dann, wenn die Ausführung noch nicht gestartet wurde.</para>
        </param>
        <summary>
          <para>Fordert den Abbruch des Tasks "angegebenen reparieren".</para>
        </summary>
        <returns>
          <para>Die neue Versionsnummer des Tasks "Reparieren".</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CancelRepairTaskAsync (string repairTaskId, long version, bool requestAbort, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CancelRepairTaskAsync(string repairTaskId, int64 version, bool requestAbort, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.CancelRepairTaskAsync(System.String,System.Int64,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelRepairTaskAsync : string * int64 * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.CancelRepairTaskAsync (repairTaskId, version, requestAbort, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="requestAbort" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para>Die ID des Tasks "Reparieren" werden abgebrochen.</para>
        </param>
        <param name="version">
          <para>Die aktuelle Versionsnummer des Reparaturtasks. Wenn ungleich 0 (null) ist, wird die Anforderung nur erfolgreich, wenn dieser Wert den tatsächlichen aktuellen Wert des Tasks "Reparieren" übereinstimmt. Ist der Wert gleich null, wird keine Versionsüberprüfung ausgeführt.</para>
        </param>
        <param name="requestAbort">
          <para>
            <languageKeyword>"True"</languageKeyword> , wenn die Reparatur so bald wie möglich beendet werden soll, selbst wenn sie bereits begonnen wurde ausgeführt. <languageKeyword>"False"</languageKeyword> , wenn die Reparatur abgebrochen werden sollte, nur dann, wenn die Ausführung noch nicht gestartet wurde.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Fordert den Abbruch des Tasks "angegebenen reparieren".</para>
        </summary>
        <returns>
          <para>Die neue Versionsnummer des Tasks "Reparieren".</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CreateRepairTaskAsync (System.Fabric.Repair.RepairTask repairTask);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CreateRepairTaskAsync(class System.Fabric.Repair.RepairTask repairTask) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.CreateRepairTaskAsync(System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="F#" Value="member this.CreateRepairTaskAsync : System.Fabric.Repair.RepairTask -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.CreateRepairTaskAsync repairTask" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTask" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="repairTask">
          <para> Die Beschreibung des Tasks "Reparieren" erstellt werden.</para>
        </param>
        <summary>
          <para>Erstellt einen neuen Reparaturtask an.</para>
        </summary>
        <returns>
          <para>Die Versionsnummer des Tasks neu erstellter reparieren.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CreateRepairTaskAsync (System.Fabric.Repair.RepairTask repairTask, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CreateRepairTaskAsync(class System.Fabric.Repair.RepairTask repairTask, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.CreateRepairTaskAsync(System.Fabric.Repair.RepairTask,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateRepairTaskAsync : System.Fabric.Repair.RepairTask * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.CreateRepairTaskAsync (repairTask, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTask" Type="System.Fabric.Repair.RepairTask" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTask">
          <para> Die Beschreibung des Tasks "Reparieren" erstellt werden.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine<see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para> Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Erstellt einen neuen Reparaturtask an.</para>
        </summary>
        <returns>
          <para>Die Versionsnummer des Tasks neu erstellter reparieren.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRepairTaskAsync (string repairTaskId, long version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRepairTaskAsync(string repairTaskId, int64 version) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.DeleteRepairTaskAsync(System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRepairTaskAsync (repairTaskId As String, version As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRepairTaskAsync : string * int64 -&gt; System.Threading.Tasks.Task" Usage="repairManagementClient.DeleteRepairTaskAsync (repairTaskId, version)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para>Die ID des abgeschlossenen Reparaturtasks, der gelöscht werden soll.</para>
        </param>
        <param name="version">
          <para>Die aktuelle Versionsnummer des Reparaturtasks. Wenn ungleich 0 (null) ist, wird die Anforderung nur erfolgreich, wenn dieser Wert den tatsächlichen aktuellen Wert des Tasks "Reparieren" übereinstimmt. Ist der Wert gleich null, wird keine Versionsüberprüfung ausgeführt.</para>
        </param>
        <summary>
          <para>Löscht die angegebenen reparaturaufgabe an.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRepairTaskAsync (string repairTaskId, long version, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRepairTaskAsync(string repairTaskId, int64 version, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.DeleteRepairTaskAsync(System.String,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteRepairTaskAsync : string * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="repairManagementClient.DeleteRepairTaskAsync (repairTaskId, version, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para>Die ID des abgeschlossenen Reparaturtasks, der gelöscht werden soll.</para>
        </param>
        <param name="version">
          <para>Die aktuelle Versionsnummer des Reparaturtasks. Wenn ungleich 0 (null) ist, wird die Anforderung nur erfolgreich, wenn dieser Wert den tatsächlichen aktuellen Wert des Tasks "Reparieren" übereinstimmt. Ist der Wert gleich null, wird keine Versionsüberprüfung ausgeführt.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Löscht die angegebenen reparaturaufgabe an.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceApproveRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ForceApproveRepairTaskAsync (string repairTaskId, long version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; ForceApproveRepairTaskAsync(string repairTaskId, int64 version) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.ForceApproveRepairTaskAsync(System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ForceApproveRepairTaskAsync (repairTaskId As String, version As Long) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ForceApproveRepairTaskAsync : string * int64 -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.ForceApproveRepairTaskAsync (repairTaskId, version)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para>Die ID des Tasks "Reparieren" genehmigt werden.</para>
        </param>
        <param name="version">
          <para>Die aktuelle Versionsnummer des Reparaturtasks. Wenn ungleich 0 (null) ist, wird die Anforderung nur erfolgreich, wenn dieser Wert den tatsächlichen aktuellen Wert des Tasks "Reparieren" übereinstimmt. Ist der Wert gleich null, wird keine Versionsüberprüfung ausgeführt.</para>
        </param>
        <summary>
          <para>Erzwingt die Genehmigung das angegebenen Reparaturtasks.</para>
        </summary>
        <returns>
          <para>Die neue Versionsnummer des Tasks "Reparieren".</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceApproveRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ForceApproveRepairTaskAsync (string repairTaskId, long version, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; ForceApproveRepairTaskAsync(string repairTaskId, int64 version, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.ForceApproveRepairTaskAsync(System.String,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ForceApproveRepairTaskAsync : string * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.ForceApproveRepairTaskAsync (repairTaskId, version, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para>Die ID des Tasks "Reparieren" genehmigt werden.</para>
        </param>
        <param name="version">
          <para>Die aktuelle Versionsnummer des Reparaturtasks. Wenn ungleich 0 (null) ist, wird die Anforderung nur erfolgreich, wenn dieser Wert den tatsächlichen aktuellen Wert des Tasks "Reparieren" übereinstimmt. Ist der Wert gleich null, wird keine Versionsüberprüfung ausgeführt.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Erzwingt die Genehmigung das angegebenen Reparaturtasks.</para>
        </summary>
        <returns>
          <para>Die neue Versionsnummer des Tasks "Reparieren".</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRepairTaskListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.GetRepairTaskListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRepairTaskListAsync () As Task(Of RepairTaskList)" />
      <MemberSignature Language="F#" Value="member this.GetRepairTaskListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;" Usage="repairManagementClient.GetRepairTaskListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Ruft eine Liste aller reparieren Aufgaben ab.</para>
        </summary>
        <returns>
          <para>Die Liste der Tasks für alle reparieren.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRepairTaskListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.GetRepairTaskListAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRepairTaskListAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;" Usage="repairManagementClient.GetRepairTaskListAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft eine Liste aller reparieren Aufgaben ab.</para>
        </summary>
        <returns>
          <para>Die Liste der Tasks für alle reparieren.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRepairTaskListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync (string taskIdFilter, System.Fabric.Repair.RepairTaskStateFilter stateFilter, string executorFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync(string taskIdFilter, valuetype System.Fabric.Repair.RepairTaskStateFilter stateFilter, string executorFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.GetRepairTaskListAsync(System.String,System.Fabric.Repair.RepairTaskStateFilter,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRepairTaskListAsync (taskIdFilter As String, stateFilter As RepairTaskStateFilter, executorFilter As String) As Task(Of RepairTaskList)" />
      <MemberSignature Language="F#" Value="member this.GetRepairTaskListAsync : string * System.Fabric.Repair.RepairTaskStateFilter * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;" Usage="repairManagementClient.GetRepairTaskListAsync (taskIdFilter, stateFilter, executorFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskIdFilter" Type="System.String" />
        <Parameter Name="stateFilter" Type="System.Fabric.Repair.RepairTaskStateFilter" />
        <Parameter Name="executorFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="taskIdFilter">
          <para>Das Reparaturtask-ID-Präfix, das abgeglichen werden soll.  Der Task-ID wird kein Filter angewendet, wenn der Wert null ist,</para>
        </param>
        <param name="stateFilter">
          <para>Eine bitweise Kombination der Filter-Statuswerte, die angeben, welche Aufgabe Zustände sollte in der Liste enthalten sein.</para>
        </param>
        <param name="executorFilter">
          <para>Der Name der Executor für die Reparatur, deren beanspruchte Aufgaben in der Liste enthalten sein soll. Bei null wird kein Filter auf den Namen der Executor angewendet.</para>
        </param>
        <summary>
          <para>Ruft eine Liste der Tasks reparieren, die alle angegebenen Filter entsprechen.</para>
        </summary>
        <returns>
          <para>Die Liste der Tasks reparieren, die alle angegebenen Filter entsprechen.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRepairTaskListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync (string taskIdFilter, System.Fabric.Repair.RepairTaskStateFilter stateFilter, string executorFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync(string taskIdFilter, valuetype System.Fabric.Repair.RepairTaskStateFilter stateFilter, string executorFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.GetRepairTaskListAsync(System.String,System.Fabric.Repair.RepairTaskStateFilter,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRepairTaskListAsync : string * System.Fabric.Repair.RepairTaskStateFilter * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;" Usage="repairManagementClient.GetRepairTaskListAsync (taskIdFilter, stateFilter, executorFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskIdFilter" Type="System.String" />
        <Parameter Name="stateFilter" Type="System.Fabric.Repair.RepairTaskStateFilter" />
        <Parameter Name="executorFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="taskIdFilter">
          <para>Das Reparaturtask-ID-Präfix, das abgeglichen werden soll.  Der Task-ID wird kein Filter angewendet, wenn der Wert null ist,</para>
        </param>
        <param name="stateFilter">
          <para>Eine bitweise Kombination der Filter-Statuswerte, die angeben, welche Aufgabe Zustände sollte in der Liste enthalten sein.</para>
        </param>
        <param name="executorFilter">
          <para>Der Name der Executor für die Reparatur, deren beanspruchte Aufgaben in der Liste enthalten sein soll. Bei null wird kein Filter auf den Namen der Executor angewendet.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft eine Liste der Tasks reparieren, die alle angegebenen Filter entsprechen.</para>
        </summary>
        <returns>
          <para>Die Liste der Tasks reparieren, die alle angegebenen Filter entsprechen.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRepairExecutionStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; UpdateRepairExecutionStateAsync (System.Fabric.Repair.RepairTask repairTask);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; UpdateRepairExecutionStateAsync(class System.Fabric.Repair.RepairTask repairTask) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.UpdateRepairExecutionStateAsync(System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="F#" Value="member this.UpdateRepairExecutionStateAsync : System.Fabric.Repair.RepairTask -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.UpdateRepairExecutionStateAsync repairTask" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTask" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="repairTask">Die geänderte reparaturaufgabe.</param>
        <summary>
            Aktualisiert eine reparaturaufgabe.
            </summary>
        <returns>
          <para>Die neue Versionsnummer des Tasks "Reparieren".</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRepairExecutionStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; UpdateRepairExecutionStateAsync (System.Fabric.Repair.RepairTask repairTask, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; UpdateRepairExecutionStateAsync(class System.Fabric.Repair.RepairTask repairTask, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.UpdateRepairExecutionStateAsync(System.Fabric.Repair.RepairTask,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateRepairExecutionStateAsync : System.Fabric.Repair.RepairTask * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.UpdateRepairExecutionStateAsync (repairTask, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTask" Type="System.Fabric.Repair.RepairTask" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTask">Die geänderte reparaturaufgabe.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
            Aktualisiert eine reparaturaufgabe.
            </summary>
        <returns>
          <para>Die neue Versionsnummer des Tasks "Reparieren".</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRepairTaskHealthPolicyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; UpdateRepairTaskHealthPolicyAsync (string repairTaskId, long version, Nullable&lt;bool&gt; performPreparingHealthCheck, Nullable&lt;bool&gt; performRestoringHealthCheck);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; UpdateRepairTaskHealthPolicyAsync(string repairTaskId, int64 version, valuetype System.Nullable`1&lt;bool&gt; performPreparingHealthCheck, valuetype System.Nullable`1&lt;bool&gt; performRestoringHealthCheck) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.UpdateRepairTaskHealthPolicyAsync(System.String,System.Int64,System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRepairTaskHealthPolicyAsync (repairTaskId As String, version As Long, performPreparingHealthCheck As Nullable(Of Boolean), performRestoringHealthCheck As Nullable(Of Boolean)) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.UpdateRepairTaskHealthPolicyAsync : string * int64 * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.UpdateRepairTaskHealthPolicyAsync (repairTaskId, version, performPreparingHealthCheck, performRestoringHealthCheck)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="performPreparingHealthCheck" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="performRestoringHealthCheck" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para>Die ID des Tasks "Reparieren" für die ist die Integritätsrichtlinie aktualisiert werden.</para>
        </param>
        <param name="version">
          <para>Die aktuelle Versionsnummer des Reparaturtasks. Wenn ungleich 0 (null) ist, wird die Anforderung nur erfolgreich, wenn dieser Wert den tatsächlichen aktuellen Wert des Tasks "Reparieren" übereinstimmt. Ist der Wert gleich null, wird keine Versionsüberprüfung ausgeführt.</para>
        </param>
        <param name="performPreparingHealthCheck">
          <para>
            Ein boolescher Wert NULL-Werte zulässt, der angibt, wenn der integritätsprüfung wird in der Phase Vorbereiten des Tasks "Reparieren" ausgeführt werden.
            Geben Sie <c>null</c> für diesen Parameter, wenn der vorhandene Wert nicht geändert werden sollen. Geben Sie andernfalls den gewünschten neuen Wert ein. 
            </para>
        </param>
        <param name="performRestoringHealthCheck">
          <para>
            Ein boolescher Wert NULL-Werte zulässt, der angibt, wenn der integritätsprüfung wird in der Phase Restoring des Tasks "Reparieren" ausgeführt werden.
            Geben Sie <c>null</c> für diesen Parameter, wenn der vorhandene Wert nicht geändert werden sollen. Geben Sie andernfalls den gewünschten neuen Wert ein. 
            </para>
        </param>
        <summary>
          <para>Aktualisiert die Richtlinie für Integritätsstatus des Tasks "angegebenen reparieren".</para>
        </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRepairTaskHealthPolicyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; UpdateRepairTaskHealthPolicyAsync (string repairTaskId, long version, Nullable&lt;bool&gt; performPreparingHealthCheck, Nullable&lt;bool&gt; performRestoringHealthCheck, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; UpdateRepairTaskHealthPolicyAsync(string repairTaskId, int64 version, valuetype System.Nullable`1&lt;bool&gt; performPreparingHealthCheck, valuetype System.Nullable`1&lt;bool&gt; performRestoringHealthCheck, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.UpdateRepairTaskHealthPolicyAsync(System.String,System.Int64,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateRepairTaskHealthPolicyAsync : string * int64 * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.UpdateRepairTaskHealthPolicyAsync (repairTaskId, version, performPreparingHealthCheck, performRestoringHealthCheck, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="performPreparingHealthCheck" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="performRestoringHealthCheck" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para>Die ID des Tasks "Reparieren" für die ist die Integritätsrichtlinie aktualisiert werden.</para>
        </param>
        <param name="version">
          <para>Die aktuelle Versionsnummer des Reparaturtasks. Wenn ungleich 0 (null) ist, wird die Anforderung nur erfolgreich, wenn dieser Wert den tatsächlichen aktuellen Wert des Tasks "Reparieren" übereinstimmt. Ist der Wert gleich null, wird keine Versionsüberprüfung ausgeführt.</para>
        </param>
        <param name="performPreparingHealthCheck">
          <para>
            Ein boolescher Wert NULL-Werte zulässt, der angibt, wenn der integritätsprüfung wird in der Phase Vorbereiten des Tasks "Reparieren" ausgeführt werden.
            Geben Sie <c>null</c> für diesen Parameter, wenn der vorhandene Wert nicht geändert werden sollen. Geben Sie andernfalls den entsprechenden <c>Bool</c> Wert. 
            </para>
        </param>
        <param name="performRestoringHealthCheck">
          <para>
            Ein boolescher Wert NULL-Werte zulässt, der angibt, wenn der integritätsprüfung wird in der Phase Restoring des Tasks "Reparieren" ausgeführt werden.
            Geben Sie <c>null</c> für diesen Parameter, wenn der vorhandene Wert nicht geändert werden sollen. Geben Sie andernfalls den entsprechenden <c>Bool</c> Wert. 
            </para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Aktualisiert die Richtlinie für Integritätsstatus des Tasks "angegebenen reparieren".</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>