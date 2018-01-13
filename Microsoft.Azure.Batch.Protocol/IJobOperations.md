<Type Name="IJobOperations" FullName="Microsoft.Azure.Batch.Protocol.IJobOperations">
  <TypeSignature Language="C#" Value="public interface IJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IJobOperations" />
  <TypeSignature Language="F#" Value="type IJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            JobOperations-Vorgänge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;&gt; AddWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;&gt; AddWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, class Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.AddWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.JobAddParameter,Microsoft.Azure.Batch.Protocol.Models.JobAddOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.JobAddParameter * Microsoft.Azure.Batch.Protocol.Models.JobAddOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;&gt;" Usage="iJobOperations.AddWithHttpMessagesAsync (job, jobAddOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter" />
        <Parameter Name="jobAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="job">
            Der Auftrag hinzugefügt werden.
            </param>
        <param name="jobAddOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
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
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.DeleteWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;&gt;" Usage="iJobOperations.DeleteWithHttpMessagesAsync (jobId, jobDeleteOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags zu löschen.
            </param>
        <param name="jobDeleteOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
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
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DisableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;&gt; DisableWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;&gt; DisableWithHttpMessagesAsync(string jobId, valuetype Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, class Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.DisableWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.DisableJobOption,Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.DisableJobOption * Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;&gt;" Usage="iJobOperations.DisableWithHttpMessagesAsync (jobId, disableTasks, jobDisableOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="disableTasks" Type="Microsoft.Azure.Batch.Protocol.Models.DisableJobOption" />
        <Parameter Name="jobDisableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags zu deaktivieren.
            </param>
        <param name="disableTasks">
            Vorgehensweise mit aktiven Aufgaben, die dem Auftrag zugeordnet. Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "Warten"
            </param>
        <param name="jobDisableOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Deaktiviert den angegebenen Auftrag, der verhindert, dass neue Vorgänge ausgeführt wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Batch-Dienst verschiebt den Auftrag sofort in den Zustand deaktiviert.
            Batch verwendet dann den DisableTasks-Parameter, welche mit der aktuell ausgeführten Tasks des Auftrags zu tun. Der Auftrag verbleibt im Status "deaktiviert", bis der Deaktivierungsvorgang abgeschlossen ist und alle Aufgaben wurde gemäß der Option DisableTasks damit haben; der Auftrag wird an den deaktivierten Zustand. Keine neuen Tasks werden unter dem Auftrag gestartet, bis er wieder zum Zustand "aktiv" wechselt. Wenn Sie versuchen, einen Auftrag zu deaktivieren, der in einem beliebigen Zustand als aktiv ist, deaktivieren oder deaktiviert ist, schlägt die Anforderung fehl mit Statuscode 409.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;&gt; EnableWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;&gt; EnableWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.EnableWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;&gt;" Usage="iJobOperations.EnableWithHttpMessagesAsync (jobId, jobEnableOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobEnableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags zu aktivieren.
            </param>
        <param name="jobEnableOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
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
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatisticsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics,Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsHeaders&gt;&gt; GetAllLifetimeStatisticsWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.JobStatistics, class Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsHeaders&gt;&gt; GetAllLifetimeStatisticsWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.GetAllLifetimeStatisticsWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAllLifetimeStatisticsWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics, Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsHeaders&gt;&gt;" Usage="iJobOperations.GetAllLifetimeStatisticsWithHttpMessagesAsync (jobGetAllLifetimeStatisticsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics,Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobGetAllLifetimeStatisticsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobGetAllLifetimeStatisticsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
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
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetTaskCountsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts,Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders&gt;&gt; GetTaskCountsWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskCounts, class Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders&gt;&gt; GetTaskCountsWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.GetTaskCountsWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTaskCountsWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts, Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders&gt;&gt;" Usage="iJobOperations.GetTaskCountsWithHttpMessagesAsync (jobId, jobGetTaskCountsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts,Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetTaskCountsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags.
            </param>
        <param name="jobGetTaskCountsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
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
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob,Microsoft.Azure.Batch.Protocol.Models.JobGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob, class Microsoft.Azure.Batch.Protocol.Models.JobGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.GetWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob, Microsoft.Azure.Batch.Protocol.Models.JobGetHeaders&gt;&gt;" Usage="iJobOperations.GetWithHttpMessagesAsync (jobId, jobGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob,Microsoft.Azure.Batch.Protocol.Models.JobGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags.
            </param>
        <param name="jobGetOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über den angegebenen Auftrag ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListFromJobScheduleNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt; ListFromJobScheduleNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt; ListFromJobScheduleNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListFromJobScheduleNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFromJobScheduleNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt;" Usage="iJobOperations.ListFromJobScheduleNextWithHttpMessagesAsync (nextPageLink, jobListFromJobScheduleNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="jobListFromJobScheduleNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Aufträge, die unter der angegebenen Auftragszeitplan erstellt wurden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListFromJobScheduleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt; ListFromJobScheduleWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt; ListFromJobScheduleWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListFromJobScheduleWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFromJobScheduleWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt;" Usage="iJobOperations.ListFromJobScheduleWithHttpMessagesAsync (jobScheduleId, jobListFromJobScheduleOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans, von dem Sie eine Liste der Aufträge abrufen möchten.
            </param>
        <param name="jobListFromJobScheduleOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Aufträge, die unter der angegebenen Auftragszeitplan erstellt wurden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt;" Usage="iJobOperations.ListNextWithHttpMessagesAsync (nextPageLink, jobListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="jobListNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Aufträge in das angegebene Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt; ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt; ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt;" Usage="iJobOperations.ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync (nextPageLink, jobListPreparationAndReleaseTaskStatusNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
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
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt; ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt; ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt;" Usage="iJobOperations.ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync (jobId, jobListPreparationAndReleaseTaskStatusOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags.
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
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
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.JobListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.JobListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt;" Usage="iJobOperations.ListWithHttpMessagesAsync (jobListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Aufträge in das angegebene Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PatchWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;&gt; PatchWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;&gt; PatchWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.PatchWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter * Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;&gt;" Usage="iJobOperations.PatchWithHttpMessagesAsync (jobId, jobPatchParameter, jobPatchOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobPatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter" />
        <Parameter Name="jobPatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags, dessen Eigenschaften Sie aktualisieren möchten.
            </param>
        <param name="jobPatchParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="jobPatchOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
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
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TerminateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync (string jobId, string terminateReason = null, Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync(string jobId, string terminateReason, class Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.TerminateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TerminateWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;&gt;" Usage="iJobOperations.TerminateWithHttpMessagesAsync (jobId, terminateReason, jobTerminateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="jobTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags beendet werden soll.
            </param>
        <param name="terminateReason">
            Der Text, der als TerminateReason für den Auftrag angezeigt werden sollen. Der Standardwert ist "UserTerminate".
            </param>
        <param name="jobTerminateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
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
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.UpdateWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter,Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter * Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;&gt;" Usage="iJobOperations.UpdateWithHttpMessagesAsync (jobId, jobUpdateParameter, jobUpdateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobUpdateParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter" />
        <Parameter Name="jobUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags, dessen Eigenschaften Sie aktualisieren möchten.
            </param>
        <param name="jobUpdateParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="jobUpdateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
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
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>