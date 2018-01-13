<Type Name="JobOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für JobOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders Add (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders Add(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, class Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Add(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobAddParameter,Microsoft.Azure.Batch.Protocol.Models.JobAddOptions)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobAddParameter * Microsoft.Azure.Batch.Protocol.Models.JobAddOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Add (operations, job, jobAddOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="job" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter" />
        <Parameter Name="jobAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="job">
            Der Auftrag hinzugefügt werden.
            </param>
        <param name="jobAddOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Das angegebene Konto hinzugefügt einen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Batch-Dienst unterstützt zwei Möglichkeiten, die Arbeit, die im Rahmen eines Auftrags zu steuern. In der ersten Methode gibt der Benutzer eine Auftrags-Manager-Aufgabe. Der Batch-Dienst startet diese Aufgabe aus, wenn er beim Starten des Auftrags bereit ist. Die Auftrags-Manager-Aufgabe steuert alle anderen Aufgaben, die unter dieser Auftrag ausgeführt wird, über die Task-APIs. Bei der zweiten Methode steuert der Benutzer die Ausführung von Aufgaben unter einem aktiven Auftrag direkt über die Task-APIs. Beachten Sie außerdem: beim Benennen von Aufträgen zu vermeiden, darunter vertrauliche Daten wie Benutzernamen oder für den geheimen Projektnamen. Diese Informationen erscheinen im Telemetrie-Protokolle an Microsoft Support-Mitarbeiter zugegriffen werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt; AddAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt; AddAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, class Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.AddAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobAddParameter,Microsoft.Azure.Batch.Protocol.Models.JobAddOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobAddParameter * Microsoft.Azure.Batch.Protocol.Models.JobAddOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.AddAsync (operations, job, jobAddOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;AddAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="job" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter" />
        <Parameter Name="jobAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="job">
            Der Auftrag hinzugefügt werden.
            </param>
        <param name="jobAddOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Das angegebene Konto hinzugefügt einen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Batch-Dienst unterstützt zwei Möglichkeiten, die Arbeit, die im Rahmen eines Auftrags zu steuern. In der ersten Methode gibt der Benutzer eine Auftrags-Manager-Aufgabe. Der Batch-Dienst startet diese Aufgabe aus, wenn er beim Starten des Auftrags bereit ist. Die Auftrags-Manager-Aufgabe steuert alle anderen Aufgaben, die unter dieser Auftrag ausgeführt wird, über die Task-APIs. Bei der zweiten Methode steuert der Benutzer die Ausführung von Aufgaben unter einem aktiven Auftrag direkt über die Task-APIs. Beachten Sie außerdem: beim Benennen von Aufträgen zu vermeiden, darunter vertrauliche Daten wie Benutzernamen oder für den geheimen Projektnamen. Diese Informationen erscheinen im Telemetrie-Protokolle an Microsoft Support-Mitarbeiter zugegriffen werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders Delete (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders Delete(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Delete(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Delete (operations, jobId, jobDeleteOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags zu löschen.
            </param>
        <param name="jobDeleteOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Löscht einen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Löschen eines Auftrags werden auch alle Aufgaben, die Teil von diesem Auftrag sind, und alle Auftragsstatistik gelöscht. Dies wird auch die Beibehaltungsdauer für Aufgabendaten; d. h., wenn der Auftrag Aufgaben enthält, der weiterhin auf Serverknoten beibehalten werden, Batch-Dienste löscht Arbeitsverzeichnisse für diese Vorgänge und alle ihre Inhalte.  Wenn eine Auftrag löschen-Anforderung empfangen wird, wird der Batch-Dienst der Auftrag zum Löschen von Status an. Alle Update-Vorgänge für einen Auftrag, der gelöscht wird, schlagen mit Statuscode 409 (Konflikt) mit zusätzlichen Informationen, der angibt, dass der Auftrag gelöscht wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.DeleteAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.DeleteAsync (operations, jobId, jobDeleteOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags zu löschen.
            </param>
        <param name="jobDeleteOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Löschen eines Auftrags werden auch alle Aufgaben, die Teil von diesem Auftrag sind, und alle Auftragsstatistik gelöscht. Dies wird auch die Beibehaltungsdauer für Aufgabendaten; d. h., wenn der Auftrag Aufgaben enthält, der weiterhin auf Serverknoten beibehalten werden, Batch-Dienste löscht Arbeitsverzeichnisse für diese Vorgänge und alle ihre Inhalte.  Wenn eine Auftrag löschen-Anforderung empfangen wird, wird der Batch-Dienst der Auftrag zum Löschen von Status an. Alle Update-Vorgänge für einen Auftrag, der gelöscht wird, schlagen mit Statuscode 409 (Konflikt) mit zusätzlichen Informationen, der angibt, dass der Auftrag gelöscht wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Disable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders Disable (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders Disable(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, valuetype Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, class Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Disable(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.DisableJobOption,Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions)" />
      <MemberSignature Language="F#" Value="static member Disable : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.DisableJobOption * Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Disable (operations, jobId, disableTasks, jobDisableOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="disableTasks" Type="Microsoft.Azure.Batch.Protocol.Models.DisableJobOption" />
        <Parameter Name="jobDisableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags zu deaktivieren.
            </param>
        <param name="disableTasks">
            Vorgehensweise mit aktiven Aufgaben, die dem Auftrag zugeordnet. Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "Warten"
            </param>
        <param name="jobDisableOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Deaktiviert den angegebenen Auftrag, der verhindert, dass neue Vorgänge ausgeführt wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Batch-Dienst verschiebt den Auftrag sofort in den Zustand deaktiviert. Batch verwendet dann den DisableTasks-Parameter, welche mit der aktuell ausgeführten Tasks des Auftrags zu tun. Der Auftrag verbleibt im Status "deaktiviert", bis der Deaktivierungsvorgang abgeschlossen ist und alle Aufgaben wurde gemäß der Option DisableTasks damit haben; der Auftrag wird an den deaktivierten Zustand. Keine neuen Tasks werden unter dem Auftrag gestartet, bis er wieder zum Zustand "aktiv" wechselt. Wenn Sie versuchen, einen Auftrag zu deaktivieren, der in einem beliebigen Zustand als aktiv ist, deaktivieren oder deaktiviert ist, schlägt die Anforderung fehl mit Statuscode 409.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt; DisableAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt; DisableAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, valuetype Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, class Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.DisableAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.DisableJobOption,Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.DisableJobOption * Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.DisableAsync (operations, jobId, disableTasks, jobDisableOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;DisableAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="disableTasks" Type="Microsoft.Azure.Batch.Protocol.Models.DisableJobOption" />
        <Parameter Name="jobDisableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags zu deaktivieren.
            </param>
        <param name="disableTasks">
            Vorgehensweise mit aktiven Aufgaben, die dem Auftrag zugeordnet. Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "Warten"
            </param>
        <param name="jobDisableOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Deaktiviert den angegebenen Auftrag, der verhindert, dass neue Vorgänge ausgeführt wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Batch-Dienst verschiebt den Auftrag sofort in den Zustand deaktiviert. Batch verwendet dann den DisableTasks-Parameter, welche mit der aktuell ausgeführten Tasks des Auftrags zu tun. Der Auftrag verbleibt im Status "deaktiviert", bis der Deaktivierungsvorgang abgeschlossen ist und alle Aufgaben wurde gemäß der Option DisableTasks damit haben; der Auftrag wird an den deaktivierten Zustand. Keine neuen Tasks werden unter dem Auftrag gestartet, bis er wieder zum Zustand "aktiv" wechselt. Wenn Sie versuchen, einen Auftrag zu deaktivieren, der in einem beliebigen Zustand als aktiv ist, deaktivieren oder deaktiviert ist, schlägt die Anforderung fehl mit Statuscode 409.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Enable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders Enable (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders Enable(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Enable(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions)" />
      <MemberSignature Language="F#" Value="static member Enable : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Enable (operations, jobId, jobEnableOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobEnableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags zu aktivieren.
            </param>
        <param name="jobEnableOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Aktiviert den angegebenen Auftrag, neue Aufgaben ausführen.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie diese API aufrufen, legt der Batch-Dienst ein deaktiviertes Auftrags auf ausschöpfen Zustand fest. Nachdem dieser Vorgang abgeschlossen ist, geht der Auftrag in den aktiven Status und die Planung neuer Aufgaben unter der Auftrag fortgesetzt wird. Der Batch-Dienst lässt sich nicht auf eine Aufgabe im Zustand "active" mehr als sieben Tage lang verbleiben aus. Wenn Sie ein Auftrags mit aktiven Aufgaben, die mehr als 7 Tage zurückliegen hinzugefügt wurden aktivieren, werden diese Aufgaben deshalb nicht ausgeführt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt; EnableAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt; EnableAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.EnableAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.EnableAsync (operations, jobId, jobEnableOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;EnableAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobEnableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags zu aktivieren.
            </param>
        <param name="jobEnableOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktiviert den angegebenen Auftrag, neue Aufgaben ausführen.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie diese API aufrufen, legt der Batch-Dienst ein deaktiviertes Auftrags auf ausschöpfen Zustand fest. Nachdem dieser Vorgang abgeschlossen ist, geht der Auftrag in den aktiven Status und die Planung neuer Aufgaben unter der Auftrag fortgesetzt wird. Der Batch-Dienst lässt sich nicht auf eine Aufgabe im Zustand "active" mehr als sieben Tage lang verbleiben aus. Wenn Sie ein Auftrags mit aktiven Aufgaben, die mehr als 7 Tage zurückliegen hinzugefügt wurden aktivieren, werden diese Aufgaben deshalb nicht ausgeführt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CloudJob Get (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CloudJob Get(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudJob" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Get (operations, jobId, jobGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags.
            </param>
        <param name="jobGetOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft Informationen über den angegebenen Auftrag ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatistics">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobStatistics GetAllLifetimeStatistics (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobStatistics GetAllLifetimeStatistics(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAllLifetimeStatistics(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions)" />
      <MemberSignature Language="F#" Value="static member GetAllLifetimeStatistics : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobStatistics" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAllLifetimeStatistics (operations, jobGetAllLifetimeStatisticsOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobGetAllLifetimeStatisticsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobGetAllLifetimeStatisticsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Zusammenfassung lebensdauerstatistiken für alle Aufträge in das angegebene Konto abgerufen.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Statistiken werden für alle Aufträge aggregiert, die jemals im Konto, von der kontoerstellung bis zum letzten Zeitpunkt des Updates der Statistik vorhanden waren.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatisticsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics&gt; GetAllLifetimeStatisticsAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobStatistics&gt; GetAllLifetimeStatisticsAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAllLifetimeStatisticsAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAllLifetimeStatisticsAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAllLifetimeStatisticsAsync (operations, jobGetAllLifetimeStatisticsOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;GetAllLifetimeStatisticsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobGetAllLifetimeStatisticsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobGetAllLifetimeStatisticsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zusammenfassung lebensdauerstatistiken für alle Aufträge in das angegebene Konto abgerufen.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Statistiken werden für alle Aufträge aggregiert, die jemals im Konto, von der kontoerstellung bis zum letzten Zeitpunkt des Updates der Statistik vorhanden waren.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAsync (operations, jobId, jobGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags.
            </param>
        <param name="jobGetOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über den angegebenen Auftrag ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskCounts">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskCounts GetTaskCounts (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskCounts GetTaskCounts(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetTaskCounts(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions)" />
      <MemberSignature Language="F#" Value="static member GetTaskCounts : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskCounts" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetTaskCounts (operations, jobId, jobGetTaskCountsOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskCounts</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetTaskCountsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags.
            </param>
        <param name="jobGetTaskCountsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft die Anzahl der Task für den angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Aufgabe Anzahlen bieten eine Anzahl der Aufgaben nach dem Zustand Aktiv, laufenden oder abgeschlossenen Aufgabe sowie die Anzahl der Aufgaben, die erfolgreich war oder nicht. Aufgaben im Status "vorbereitet" werden als Ausführung gezählt. Wenn die ValidationStatus nicht überprüfte ist, klicken Sie dann wurde der Batch-Dienst nicht zum Überprüfen, dass für die Task-Status in der Liste Aufgaben-API gemeldeten Status zählt können. Die ValidationStatus möglicherweise nicht überprüfte sein, wenn der Auftrag über 200.000 Aufgaben enthält.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskCountsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts&gt; GetTaskCountsAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskCounts&gt; GetTaskCountsAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetTaskCountsAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTaskCountsAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetTaskCountsAsync (operations, jobId, jobGetTaskCountsOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;GetTaskCountsAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetTaskCountsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags.
            </param>
        <param name="jobGetTaskCountsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Anzahl der Task für den angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Aufgabe Anzahlen bieten eine Anzahl der Aufgaben nach dem Zustand Aktiv, laufenden oder abgeschlossenen Aufgabe sowie die Anzahl der Aufgaben, die erfolgreich war oder nicht. Aufgaben im Status "vorbereitet" werden als Ausführung gezählt. Wenn die ValidationStatus nicht überprüfte ist, klicken Sie dann wurde der Batch-Dienst nicht zum Überprüfen, dass für die Task-Status in der Liste Aufgaben-API gemeldeten Status zählt können. Die ValidationStatus möglicherweise nicht überprüfte sein, wenn der Auftrag über 200.000 Aufgaben enthält.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; List (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; List(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.List (operations, jobListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Zeigt eine Liste aller Aufträge in das angegebene Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListAsync (operations, jobListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Aufträge in das angegebene Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromJobSchedule">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListFromJobSchedule (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListFromJobSchedule(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobSchedule(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions)" />
      <MemberSignature Language="F#" Value="static member ListFromJobSchedule : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobSchedule (operations, jobScheduleId, jobListFromJobScheduleOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans, von dem Sie eine Liste der Aufträge abrufen möchten.
            </param>
        <param name="jobListFromJobScheduleOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Listet die Aufträge, die unter der angegebenen Auftragszeitplan erstellt wurden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromJobScheduleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListFromJobScheduleAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListFromJobScheduleAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFromJobScheduleAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleAsync (operations, jobScheduleId, jobListFromJobScheduleOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListFromJobScheduleAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans, von dem Sie eine Liste der Aufträge abrufen möchten.
            </param>
        <param name="jobListFromJobScheduleOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Aufträge, die unter der angegebenen Auftragszeitplan erstellt wurden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromJobScheduleNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListFromJobScheduleNext (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListFromJobScheduleNext(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleNext(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListFromJobScheduleNext : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleNext (operations, nextPageLink, jobListFromJobScheduleNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="jobListFromJobScheduleNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Listet die Aufträge, die unter der angegebenen Auftragszeitplan erstellt wurden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromJobScheduleNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListFromJobScheduleNextAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListFromJobScheduleNextAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleNextAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFromJobScheduleNextAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleNextAsync (operations, nextPageLink, jobListFromJobScheduleNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListFromJobScheduleNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="jobListFromJobScheduleNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Aufträge, die unter der angegebenen Auftragszeitplan erstellt wurden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListNext (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListNext(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListNext (operations, nextPageLink, jobListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="jobListNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Zeigt eine Liste aller Aufträge in das angegebene Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListNextAsync (operations, nextPageLink, jobListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="jobListNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Aufträge in das angegebene Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPreparationAndReleaseTaskStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt; ListPreparationAndReleaseTaskStatus (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt; ListPreparationAndReleaseTaskStatus(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatus(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions)" />
      <MemberSignature Language="F#" Value="static member ListPreparationAndReleaseTaskStatus : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatus (operations, jobId, jobListPreparationAndReleaseTaskStatusOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags.
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Listet den Ausführungsstatus des Tasks Auftrag Vorbereitung und Version der Auftrag für den angegebenen Auftrag über den Compute-Knoten, auf denen der Auftrag ausgeführt wurde.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Diese API gibt des Aufgabenstatus Auftrag Vorbereitung und Version des Auftrags auf allen Serverknoten, die die Auftrag zur Vorbereitung oder Auftrag Release Aufgabe ausgeführt haben. Dies schließt die Knoten, die zwischenzeitlich aus dem Pool entfernt wurden. Wenn diese API in einem Auftrag besitzt kein Auftrag Vorbereitung oder Auftrag Release Task aufgerufen wird, gibt der Batch-Dienst HTTP-Statuscode 409 (Konflikt) mit einem Fehlercode von JobPreparationTaskNotSpecified zurück.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPreparationAndReleaseTaskStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt; ListPreparationAndReleaseTaskStatusAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt; ListPreparationAndReleaseTaskStatusAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPreparationAndReleaseTaskStatusAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusAsync (operations, jobId, jobListPreparationAndReleaseTaskStatusOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListPreparationAndReleaseTaskStatusAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags.
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet den Ausführungsstatus des Tasks Auftrag Vorbereitung und Version der Auftrag für den angegebenen Auftrag über den Compute-Knoten, auf denen der Auftrag ausgeführt wurde.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Diese API gibt des Aufgabenstatus Auftrag Vorbereitung und Version des Auftrags auf allen Serverknoten, die die Auftrag zur Vorbereitung oder Auftrag Release Aufgabe ausgeführt haben. Dies schließt die Knoten, die zwischenzeitlich aus dem Pool entfernt wurden. Wenn diese API in einem Auftrag besitzt kein Auftrag Vorbereitung oder Auftrag Release Task aufgerufen wird, gibt der Batch-Dienst HTTP-Statuscode 409 (Konflikt) mit einem Fehlercode von JobPreparationTaskNotSpecified zurück.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPreparationAndReleaseTaskStatusNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt; ListPreparationAndReleaseTaskStatusNext (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt; ListPreparationAndReleaseTaskStatusNext(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusNext(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListPreparationAndReleaseTaskStatusNext : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusNext (operations, nextPageLink, jobListPreparationAndReleaseTaskStatusNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Listet den Ausführungsstatus des Tasks Auftrag Vorbereitung und Version der Auftrag für den angegebenen Auftrag über den Compute-Knoten, auf denen der Auftrag ausgeführt wurde.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Diese API gibt des Aufgabenstatus Auftrag Vorbereitung und Version des Auftrags auf allen Serverknoten, die die Auftrag zur Vorbereitung oder Auftrag Release Aufgabe ausgeführt haben. Dies schließt die Knoten, die zwischenzeitlich aus dem Pool entfernt wurden. Wenn diese API in einem Auftrag besitzt kein Auftrag Vorbereitung oder Auftrag Release Task aufgerufen wird, gibt der Batch-Dienst HTTP-Statuscode 409 (Konflikt) mit einem Fehlercode von JobPreparationTaskNotSpecified zurück.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPreparationAndReleaseTaskStatusNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt; ListPreparationAndReleaseTaskStatusNextAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt; ListPreparationAndReleaseTaskStatusNextAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusNextAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPreparationAndReleaseTaskStatusNextAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusNextAsync (operations, nextPageLink, jobListPreparationAndReleaseTaskStatusNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListPreparationAndReleaseTaskStatusNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet den Ausführungsstatus des Tasks Auftrag Vorbereitung und Version der Auftrag für den angegebenen Auftrag über den Compute-Knoten, auf denen der Auftrag ausgeführt wurde.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Diese API gibt des Aufgabenstatus Auftrag Vorbereitung und Version des Auftrags auf allen Serverknoten, die die Auftrag zur Vorbereitung oder Auftrag Release Aufgabe ausgeführt haben. Dies schließt die Knoten, die zwischenzeitlich aus dem Pool entfernt wurden. Wenn diese API in einem Auftrag besitzt kein Auftrag Vorbereitung oder Auftrag Release Task aufgerufen wird, gibt der Batch-Dienst HTTP-Statuscode 409 (Konflikt) mit einem Fehlercode von JobPreparationTaskNotSpecified zurück.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders Patch (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders Patch(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Patch(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions)" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter * Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Patch (operations, jobId, jobPatchParameter, jobPatchOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobPatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter" />
        <Parameter Name="jobPatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, dessen Eigenschaften Sie aktualisieren möchten.
            </param>
        <param name="jobPatchParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="jobPatchOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Aktualisiert die Eigenschaften des angegebenen Auftrags.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dies ersetzt die Auftragseigenschaften in der Anforderung angegeben. Beispielsweise behält Wenn weist Einschränkungen auf der Auftrag und eine Anforderung keine Einschränkungen-Element gibt, klicken Sie dann der Auftrag die vorhandenen Einschränkungen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt; PatchAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt; PatchAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.PatchAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter * Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.PatchAsync (operations, jobId, jobPatchParameter, jobPatchOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;PatchAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobPatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter" />
        <Parameter Name="jobPatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, dessen Eigenschaften Sie aktualisieren möchten.
            </param>
        <param name="jobPatchParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="jobPatchOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Eigenschaften des angegebenen Auftrags.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dies ersetzt die Auftragseigenschaften in der Anforderung angegeben. Beispielsweise behält Wenn weist Einschränkungen auf der Auftrag und eine Anforderung keine Einschränkungen-Element gibt, klicken Sie dann der Auftrag die vorhandenen Einschränkungen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders Terminate (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, string terminateReason = null, Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders Terminate(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, string terminateReason, class Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Terminate(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions)" />
      <MemberSignature Language="F#" Value="static member Terminate : Microsoft.Azure.Batch.Protocol.IJobOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Terminate (operations, jobId, terminateReason, jobTerminateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="jobTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags beendet werden soll.
            </param>
        <param name="terminateReason">
            Der Text, der als TerminateReason für den Auftrag angezeigt werden sollen. Der Standardwert ist "UserTerminate".
            </param>
        <param name="jobTerminateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Beendet den angegebenen Auftrag als abgeschlossen gekennzeichnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn eine Auftrag beenden-Anforderung empfangen wird, wird der Batch-Dienst der Auftrag in den abschließenden Zustand. Der Batch-Dienst aktiven oder ausgeführten Aufgaben im Zusammenhang mit der Auftrag beendet und führt alle erforderlichen Aufgaben für die Version des Auftrags. Der Auftrag wird in den abgeschlossenen Zustand versetzt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt; TerminateAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, string terminateReason = null, Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt; TerminateAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, string terminateReason, class Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.TerminateAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TerminateAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.TerminateAsync (operations, jobId, terminateReason, jobTerminateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;TerminateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="jobTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags beendet werden soll.
            </param>
        <param name="terminateReason">
            Der Text, der als TerminateReason für den Auftrag angezeigt werden sollen. Der Standardwert ist "UserTerminate".
            </param>
        <param name="jobTerminateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Beendet den angegebenen Auftrag als abgeschlossen gekennzeichnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn eine Auftrag beenden-Anforderung empfangen wird, wird der Batch-Dienst der Auftrag in den abschließenden Zustand. Der Batch-Dienst aktiven oder ausgeführten Aufgaben im Zusammenhang mit der Auftrag beendet und führt alle erforderlichen Aufgaben für die Version des Auftrags. Der Auftrag wird in den abgeschlossenen Zustand versetzt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders Update (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders Update(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Update(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter,Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter * Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Update (operations, jobId, jobUpdateParameter, jobUpdateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobUpdateParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter" />
        <Parameter Name="jobUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, dessen Eigenschaften Sie aktualisieren möchten.
            </param>
        <param name="jobUpdateParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="jobUpdateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Aktualisiert die Eigenschaften des angegebenen Auftrags.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Vollständig ersetzt alle aktualisierbaren Eigenschaften des Auftrags. Beispielsweise entfernt verfügt der Auftrag zugeordnete Einschränkungen und Einschränkungen bei dieser Anforderung nicht angegeben ist, klicken Sie dann der Batch-Dienst die vorhandenen Einschränkungen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt; UpdateAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt; UpdateAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.UpdateAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter,Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter * Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.UpdateAsync (operations, jobId, jobUpdateParameter, jobUpdateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;UpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobUpdateParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter" />
        <Parameter Name="jobUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, dessen Eigenschaften Sie aktualisieren möchten.
            </param>
        <param name="jobUpdateParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="jobUpdateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Eigenschaften des angegebenen Auftrags.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Vollständig ersetzt alle aktualisierbaren Eigenschaften des Auftrags. Beispielsweise entfernt verfügt der Auftrag zugeordnete Einschränkungen und Einschränkungen bei dieser Anforderung nicht angegeben ist, klicken Sie dann der Batch-Dienst die vorhandenen Einschränkungen.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>