<Type Name="ITaskOperations" FullName="Microsoft.Azure.Batch.Protocol.ITaskOperations">
  <TypeSignature Language="C#" Value="public interface ITaskOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITaskOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.ITaskOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITaskOperations" />
  <TypeSignature Language="F#" Value="type ITaskOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            TaskOperations-Vorgänge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddCollectionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult,Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt; AddCollectionWithHttpMessagesAsync (string jobId, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt; AddCollectionWithHttpMessagesAsync(string jobId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.AddCollectionWithHttpMessagesAsync(System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter},Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddCollectionWithHttpMessagesAsync : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult, Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt;" Usage="iTaskOperations.AddCollectionWithHttpMessagesAsync (jobId, value, taskAddCollectionOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult,Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;" />
        <Parameter Name="taskAddCollectionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags, der die Auflistung der ist, hinzugefügt werden.
            </param>
        <param name="value">
            Die Auflistung von Aufgaben hinzufügen. Die serialisierte Gesamtgröße dieser Auflistung muss kleiner als 4 MB sein. Ist er größer als 4MB (z. B., wenn jede Aufgabe 100 Ressourcendateien oder Umgebungsvariablen verfügt), wird die Anforderung schlägt fehl mit Code "RequestBodyTooLarge" und mit weniger Vorgänge erneut wiederholt werden sollen.
            </param>
        <param name="taskAddCollectionOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Fügt eine Auflistung von Aufgaben an den angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Beachten Sie, dass jede Aufgabe eine eindeutige ID aufweisen muss Der Batch-Dienst möglicherweise nicht die Ergebnisse für jede Aufgabe in der gleichen Reihenfolge zurück, die die Aufgaben in dieser Anforderung gesendet wurden. Wenn der Server ein Timeout eintritt, oder die Verbindung, während der Anforderung geschlossen wird, die Anforderung teilweise oder vollständig verarbeitet war möglicherweise oder überhaupt nicht. In solchen Fällen sollte der Benutzer die Anforderung erneut senden. Beachten Sie, dass es bis zu dem Benutzer, Fehler richtig zu behandeln, wenn eine Anforderung erneut gesendet wird. Beispielsweise sollten Sie die gleichen Aufgaben-IDs bei einer Wiederholung verwenden, damit, dass wenn der vorherige Vorgang erfolgreich war, die Wiederholung nicht unerwartet zusätzliche Aufgaben erstellt wird. Wenn die Antwort alle Aufgaben, die Fehler beim Hinzufügen enthält, kann ein Client die Anforderung erneut ausführen. In einer Wiederholung ist es am effizientesten, nur Vorgänge, die nicht hinzufügen, und klicken Sie, um Aufgaben zu unterdrücken, die beim ersten Versuch erfolgreich hinzugefügt wurden, erneut zu senden. Die maximale Lebensdauer einer Aufgabe vom hinzufügen bis zum Abschluss beträgt 7 Tage.
            Wenn eine Aufgabe nicht abgeschlossen wurde, innerhalb von 7 Tagen hinzugefügt wird, dass durch die Batch-Dienst und der linken Seite beendet werden, wurde in unabhängig von Ihrem Status er zu diesem Zeitpunkt.
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
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;&gt; AddWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;&gt; AddWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, class Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.AddWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter,Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter * Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;&gt;" Usage="iTaskOperations.AddWithHttpMessagesAsync (jobId, task, taskAddOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="task" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" />
        <Parameter Name="taskAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags, zu dem die Aufgabe ist, hinzugefügt werden.
            </param>
        <param name="task">
            Die Aufgabe hinzugefügt werden.
            </param>
        <param name="taskAddOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Fügt eine Aufgabe zum angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Die maximale Lebensdauer einer Aufgabe vom hinzufügen bis zum Abschluss beträgt 7 Tage. Wenn eine Aufgabe nicht abgeschlossen wurde, innerhalb von 7 Tagen hinzugefügt wird, dass durch die Batch-Dienst und der linken Seite beendet werden, wurde in unabhängig von Ihrem Status er zu diesem Zeitpunkt.
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.DeleteWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;&gt;" Usage="iTaskOperations.DeleteWithHttpMessagesAsync (jobId, taskId, taskDeleteOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags, aus dem die Aufgabe zu löschen.
            </param>
        <param name="taskId">
            Die ID des Vorgangs zu löschen.
            </param>
        <param name="taskDeleteOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine Aufgabe aus dem angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn eine Aufgabe gelöscht wird, werden alle Dateien im Verzeichnis auf den Computeknoten, in dem es ausgeführt wurde (unabhängig von der Aufbewahrungsdauer) ebenfalls gelöscht. Für Vorgänge mit mehreren Instanzen gilt der Löschvorgang für den Task synchron an die primäre Aufgabe; Unteraufgaben und die Dateien werden asynchron im Hintergrund gelöscht.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask,Microsoft.Azure.Batch.Protocol.Models.TaskGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask, class Microsoft.Azure.Batch.Protocol.Models.TaskGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.GetWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask, Microsoft.Azure.Batch.Protocol.Models.TaskGetHeaders&gt;&gt;" Usage="iTaskOperations.GetWithHttpMessagesAsync (jobId, taskId, taskGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask,Microsoft.Azure.Batch.Protocol.Models.TaskGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID des Tasks, zu dem Informationen abgerufen werden sollen.
            </param>
        <param name="taskGetOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über den angegebenen Vorgang ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe. Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.
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
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, class Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;" Usage="iTaskOperations.ListNextWithHttpMessagesAsync (nextPageLink, taskListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="taskListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="taskListNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Aufgaben, die dem angegebenen Auftrag zugeordnet sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe. Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.
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
    <Member MemberName="ListSubtasksWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt; ListSubtasksWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt; ListSubtasksWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.ListSubtasksWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSubtasksWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult, Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt;" Usage="iTaskOperations.ListSubtasksWithHttpMessagesAsync (jobId, taskId, taskListSubtasksOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskListSubtasksOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags.
            </param>
        <param name="taskId">
            Die ID des Tasks.
            </param>
        <param name="taskListSubtasksOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller die Unteraufgaben an, die der Aufgabe angegebenen mit mehreren Instanzen zugeordnet sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn der Vorgang nicht um eine Aufgabe mit mehreren Instanzen ist zurück dies eine leere Auflistung.
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt; ListWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, class Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt; ListWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.ListWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.TaskListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;" Usage="iTaskOperations.ListWithHttpMessagesAsync (jobId, taskListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags.
            </param>
        <param name="taskListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Aufgaben, die dem angegebenen Auftrag zugeordnet sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe. Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.
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
    <Member MemberName="ReactivateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt; ReactivateWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt; ReactivateWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.ReactivateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReactivateWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt;" Usage="iTaskOperations.ReactivateWithHttpMessagesAsync (jobId, taskId, taskReactivateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskReactivateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID des Tasks zu reaktivieren.
            </param>
        <param name="taskReactivateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Reaktiviert eine Aufgabe, sodass es erneut ausführen, auch wenn die Anzahl der Wiederholungsversuche ausgeschöpft ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Reaktivierung wird eine Aufgabe berechtigt ist, bis die maximale Anzahl von Wiederholungsversuchen zum Vorgang wiederholt werden. Der Status der Aufgabe wird in aktiv geändert. Wie die Aufgabe nicht mehr in den Zustand abgeschlossen ist, ist keine vorherigen beenden Code oder das Fehlschlagen der Informationen nach der Reaktivierung nicht mehr verfügbar. Jedes Mal, wenn eine Aufgabe erneut aktiviert wird, wird die Wiederholungsanzahl auf 0 zurückgesetzt.
            Reaktivierung fehl für Aufgaben, die nicht abgeschlossen oder zuvor erfolgreich (mit Exitcode 0) abgeschlossen.
            Darüber hinaus schlägt er fehl, wenn der Auftrag abgeschlossen wurde (oder beenden oder löschen).
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.TerminateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TerminateWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;&gt;" Usage="iTaskOperations.TerminateWithHttpMessagesAsync (jobId, taskId, taskTerminateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID des Tasks beendet werden soll.
            </param>
        <param name="taskTerminateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Beendet die angegebene Aufgabe an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn die Aufgabe beendet wurde, wird in den abgeschlossenen Zustand verschoben.
            Für Vorgänge mit mehreren Instanzen gilt der Vorgang "Beenden" Task synchron an die primäre Aufgabe. Unteraufgaben werden dann asynchron im Hintergrund beendet.
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt;" Usage="iTaskOperations.UpdateWithHttpMessagesAsync (jobId, taskId, constraints, taskUpdateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="taskUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID des Tasks aktualisiert.
            </param>
        <param name="constraints">
            Einschränkungen, die für diese Aufgabe gelten. Wenn nicht angegeben, wird die Aufgabe das Default-Einschränkungen angegeben. Für Vorgänge mit mehreren Instanzen aktualisieren die Aufbewahrungsdauer gilt nur für die primäre Aufgabe und Teilvorgänge nicht.
            </param>
        <param name="taskUpdateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Eigenschaften der angegebenen Aufgabe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
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