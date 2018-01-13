<Type Name="IPoolOperations" FullName="Microsoft.Azure.Batch.Protocol.IPoolOperations">
  <TypeSignature Language="C#" Value="public interface IPoolOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPoolOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IPoolOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPoolOperations" />
  <TypeSignature Language="F#" Value="type IPoolOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            PoolOperations-Vorgänge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;&gt; AddWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter pool, Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions poolAddOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;&gt; AddWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter pool, class Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions poolAddOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.AddWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter,Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter * Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;&gt;" Usage="iPoolOperations.AddWithHttpMessagesAsync (pool, poolAddOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pool" Type="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter" />
        <Parameter Name="poolAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="pool">
            Der Pool hinzugefügt werden.
            </param>
        <param name="poolAddOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Das angegebene Konto hinzugefügt ein Pool.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Beim Benennen von Pools zu vermeiden, darunter vertrauliche Daten wie Benutzernamen oder für den geheimen Projektnamen. Diese Informationen erscheinen im Telemetrie-Protokolle an Microsoft Support-Mitarbeiter zugegriffen werden kann.
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions poolDeleteOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions poolDeleteOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.DeleteWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt;&gt;" Usage="iPoolOperations.DeleteWithHttpMessagesAsync (poolId, poolDeleteOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools gelöscht werden soll.
            </param>
        <param name="poolDeleteOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen Pool aus dem angegebenen Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie anfordern, dass ein Pool gelöscht werden, die folgenden Aktionen ausgeführt: der Zustand Pool ist festgelegt, zu löschen; Alle größenänderungsvorgang für den Pool beendet werden. der Batch-Dienst gestartet wird, Ändern der Größe des Pools Knoten NULL; Alle Aufgaben, die auf vorhandenen Knoten ausgeführt werden beendet und in die Warteschlange (wie bei der ein größenänderungsvorgang für den Pool mit der Standardoption wieder in Warteschlange angefordert worden); Schließlich wird der Pool aus dem System entfernt. Da Ausführen von Tasks in die Warteschlange sind, kann Benutzer diese Aufgaben erneut ausführen durch ihren Auftrag um einen anderen Pool als Ziel aktualisieren. Die Aufgaben können Sie in den neuen Pool ausführen. Wenn Sie das Verhalten wieder in Warteschlange überschreiben möchten, sollten Sie poolgrößenänderung explizit, um den Pool auf 0 (null) Größe zu verkleinern, bevor Sie den Pool löschen aufrufen. Wenn Sie für einen Pool im Status "gelöscht" aktualisieren, Patches oder Löschen von API-aufrufen, wird es mit dem HTTP-Statuscode 409 mit Fehlercode PoolBeingDeleted fehl.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScaleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt;&gt; DisableAutoScaleWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions poolDisableAutoScaleOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt;&gt; DisableAutoScaleWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions poolDisableAutoScaleOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.DisableAutoScaleWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableAutoScaleWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt;&gt;" Usage="iPoolOperations.DisableAutoScaleWithHttpMessagesAsync (poolId, poolDisableAutoScaleOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolDisableAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Speicherpools auf dem die automatische Skalierung deaktiviert.
            </param>
        <param name="poolDisableAutoScaleOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Deaktiviert die automatische Skalierung für einen Pool.
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
    <Member MemberName="EnableAutoScaleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;&gt; EnableAutoScaleWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter poolEnableAutoScaleParameter, Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions poolEnableAutoScaleOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;&gt; EnableAutoScaleWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter poolEnableAutoScaleParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions poolEnableAutoScaleOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.EnableAutoScaleWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableAutoScaleWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter * Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;&gt;" Usage="iPoolOperations.EnableAutoScaleWithHttpMessagesAsync (poolId, poolEnableAutoScaleParameter, poolEnableAutoScaleOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolEnableAutoScaleParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter" />
        <Parameter Name="poolEnableAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools für die automatische Skalierung aktiviert.
            </param>
        <param name="poolEnableAutoScaleParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="poolEnableAutoScaleOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ermöglicht die automatische Skalierung für einen Pool.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können keine Aktivieren der automatischen Skalierung für einen Pool, wenn ein größenänderungsvorgang für den Pool ausgeführt wird. Wenn automatische Skalierung des Pools derzeit deaktiviert ist, müssen Sie eine gültige automatische Skalierung Formel als Teil der Anforderung angeben. Wenn automatische Skalierung des Pools bereits aktiviert ist, können Sie eine neue Formel für automatische Skalierung und/oder eine neue Evaluierung Intervall angeben. Diese API kann nicht für den gleichen Pool verwendet werden mehr als einmal alle 30 Sekunden aufgerufen werden.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScaleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleHeaders&gt;&gt; EvaluateAutoScaleWithHttpMessagesAsync (string poolId, string autoScaleFormula, Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions poolEvaluateAutoScaleOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun, class Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleHeaders&gt;&gt; EvaluateAutoScaleWithHttpMessagesAsync(string poolId, string autoScaleFormula, class Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions poolEvaluateAutoScaleOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.EvaluateAutoScaleWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EvaluateAutoScaleWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun, Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleHeaders&gt;&gt;" Usage="iPoolOperations.EvaluateAutoScaleWithHttpMessagesAsync (poolId, autoScaleFormula, poolEvaluateAutoScaleOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoScaleFormula" Type="System.String" />
        <Parameter Name="poolEvaluateAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Speicherpools auf dem die Formel für automatische Skalierung ausgewertet werden soll.
            </param>
        <param name="autoScaleFormula">
            Die Formel für die gewünschte Anzahl von Serverknoten im Pool.
            Die Formel überprüft wurde und seine Ergebnisse berechnet, jedoch nicht an den Pool angewendet wird. Um die Formel für den Pool anzuwenden, "Aktivieren der automatischen Skalierung für einen Pool". Weitere Informationen zum Angeben dieser Formel finden Sie unter automatisch skalieren Serverknoten in einem Azure Batch-Pool (https://azure.microsoft.com/en-us/documentation/articles/batch-automatic-scaling).
            </param>
        <param name="poolEvaluateAutoScaleOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft das Ergebnis der Auswertung einer Automatisches Formel für den Pool Skalierung.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Diese API ist in erster Linie für eine Formel für automatische Skalierung überprüfen, wie sie einfach das Ergebnis zurückgibt, ohne die Formel für den Pool.
            Der Pool muss die automatische Skalierung aktiviert, um eine Formel auswerten aufweisen.
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
    <Member MemberName="ExistsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool,Microsoft.Azure.Batch.Protocol.Models.PoolExistsHeaders&gt;&gt; ExistsWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions poolExistsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;bool, class Microsoft.Azure.Batch.Protocol.Models.PoolExistsHeaders&gt;&gt; ExistsWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions poolExistsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ExistsWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool, Microsoft.Azure.Batch.Protocol.Models.PoolExistsHeaders&gt;&gt;" Usage="iPoolOperations.ExistsWithHttpMessagesAsync (poolId, poolExistsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Boolean,Microsoft.Azure.Batch.Protocol.Models.PoolExistsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolExistsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID der dem Pool abgerufen werden soll.
            </param>
        <param name="poolExistsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die grundlegende Eigenschaften eines Pools.
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
    <Member MemberName="GetAllLifetimeStatisticsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStatistics,Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsHeaders&gt;&gt; GetAllLifetimeStatisticsWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions poolGetAllLifetimeStatisticsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolStatistics, class Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsHeaders&gt;&gt; GetAllLifetimeStatisticsWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions poolGetAllLifetimeStatisticsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.GetAllLifetimeStatisticsWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAllLifetimeStatisticsWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStatistics, Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsHeaders&gt;&gt;" Usage="iPoolOperations.GetAllLifetimeStatisticsWithHttpMessagesAsync (poolGetAllLifetimeStatisticsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStatistics,Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolGetAllLifetimeStatisticsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolGetAllLifetimeStatisticsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Lebensdauer zusammenfassungsstatistiken für alle Pools im angegebenen Konto ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Statistiken werden für alle Pools aggregiert, die jemals im Konto, von der kontoerstellung bis zum letzten Zeitpunkt des Updates der Statistik vorhanden waren.
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool,Microsoft.Azure.Batch.Protocol.Models.PoolGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions poolGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool, class Microsoft.Azure.Batch.Protocol.Models.PoolGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions poolGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.GetWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool, Microsoft.Azure.Batch.Protocol.Models.PoolGetHeaders&gt;&gt;" Usage="iPoolOperations.GetWithHttpMessagesAsync (poolId, poolGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool,Microsoft.Azure.Batch.Protocol.Models.PoolGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID der dem Pool abgerufen werden soll.
            </param>
        <param name="poolGetOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über den angegebenen Pool ab.
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions poolListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;, class Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions poolListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;, Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt;" Usage="iPoolOperations.ListNextWithHttpMessagesAsync (nextPageLink, poolListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="poolListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="poolListNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle Pools im angegebenen Konto.
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
    <Member MemberName="ListUsageMetricsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt; ListUsageMetricsNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions poolListUsageMetricsNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt; ListUsageMetricsNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions poolListUsageMetricsNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ListUsageMetricsNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListUsageMetricsNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt;" Usage="iPoolOperations.ListUsageMetricsNextWithHttpMessagesAsync (nextPageLink, poolListUsageMetricsNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="poolListUsageMetricsNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="poolListUsageMetricsNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Nutzungsdaten von Pool über einzelne Zeitintervalle, für das angegebene Konto aggregiert.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie eine $filter-Klausel, z. B. eine PoolId nicht angeben, enthält die Antwort alle Pools, die vorhanden waren in das Konto im Zeitraum von Intervallen zurückgegebenen Aggregation an. Wenn Sie keiner $filter-Klausel, einschließlich einer StartTime und EndTime diese Filter standardmäßig die Start- und Endzeiten des letzten aggregationsintervalls derzeit verfügbaren angeben; Das heißt, ist nur im letzte aggregationsintervall zurückgegeben.
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
    <Member MemberName="ListUsageMetricsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt; ListUsageMetricsWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions poolListUsageMetricsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt; ListUsageMetricsWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions poolListUsageMetricsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ListUsageMetricsWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListUsageMetricsWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt;" Usage="iPoolOperations.ListUsageMetricsWithHttpMessagesAsync (poolListUsageMetricsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolListUsageMetricsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolListUsageMetricsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Nutzungsdaten von Pool über einzelne Zeitintervalle, für das angegebene Konto aggregiert.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie eine $filter-Klausel, z. B. eine PoolId nicht angeben, enthält die Antwort alle Pools, die vorhanden waren in das Konto im Zeitraum von Intervallen zurückgegebenen Aggregation an. Wenn Sie keiner $filter-Klausel, einschließlich einer StartTime und EndTime diese Filter standardmäßig die Start- und Endzeiten des letzten aggregationsintervalls derzeit verfügbaren angeben; Das heißt, ist nur im letzte aggregationsintervall zurückgegeben.
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.PoolListOptions poolListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;, class Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.PoolListOptions poolListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ListWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.PoolListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.PoolListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;, Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt;" Usage="iPoolOperations.ListWithHttpMessagesAsync (poolListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle Pools im angegebenen Konto.
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;&gt; PatchWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter poolPatchParameter, Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions poolPatchOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;&gt; PatchWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter poolPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions poolPatchOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.PatchWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter,Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter * Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;&gt;" Usage="iPoolOperations.PatchWithHttpMessagesAsync (poolId, poolPatchParameter, poolPatchOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolPatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter" />
        <Parameter Name="poolPatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools aktualisieren.
            </param>
        <param name="poolPatchParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="poolPatchOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Eigenschaften des angegebenen Pools.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dies ersetzt nur die Pooleigenschaften, die in der Anforderung angegeben.
            Z. B. behält, wenn der Pool eine Startaufgabe zugeordnet wurde, und eine Anforderung keine Start-Task-Element, klicken Sie dann der Pool die vorhandene Startaufgabe.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt;&gt; RemoveNodesWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter nodeRemoveParameter, Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions poolRemoveNodesOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt;&gt; RemoveNodesWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter nodeRemoveParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions poolRemoveNodesOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.RemoveNodesWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter,Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveNodesWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter * Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt;&gt;" Usage="iPoolOperations.RemoveNodesWithHttpMessagesAsync (poolId, nodeRemoveParameter, poolRemoveNodesOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeRemoveParameter" Type="Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter" />
        <Parameter Name="poolRemoveNodesOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools, von dem Sie die Knoten entfernen möchten.
            </param>
        <param name="nodeRemoveParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="poolRemoveNodesOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Entfernt einen Serverknoten aus dem angegebenen Pool.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dieser Vorgang kann nur ausgeführt, wenn es sich bei der Zuordnungsstatus des Pools gleichmäßig ist. Wenn dieser Vorgang ausgeführt wird, wechselt der Zuordnung von stabilen zum Ändern der Größe.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResizeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;&gt; ResizeWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter poolResizeParameter, Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions poolResizeOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;&gt; ResizeWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter poolResizeParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions poolResizeOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ResizeWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter,Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResizeWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter * Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;&gt;" Usage="iPoolOperations.ResizeWithHttpMessagesAsync (poolId, poolResizeParameter, poolResizeOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolResizeParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter" />
        <Parameter Name="poolResizeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools, um die Größe.
            </param>
        <param name="poolResizeParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="poolResizeOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ändert die Anzahl von Compute-Knoten, die zu einem Pool zugewiesen sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können einen Pool nur ändern, wenn seine Zuordnungsstatus gleichmäßig ist. Wenn der Pool bereits Größe ist, tritt ein Anforderungsfehler mit Statuscode ""
            409. Wenn die Größe ändern Sie eines Pools, den Pool Zuordnung statusänderungen von stabilen zum Ändern der Größe. Pools, die für die automatische Skalierung konfiguriert sind, kann nicht geändert werden. Wenn Sie dies versuchen, gibt der Batch-Dienst einen Fehler 409 zurück. Wenn Sie einen Pool abwärts verkleinern, wählt der Batch-Dienst die Knoten aus, zu entfernen. Um bestimmte Knoten zu entfernen, verwenden Sie stattdessen den Pool Entfernen von Knoten API.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StopResizeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt;&gt; StopResizeWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions poolStopResizeOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt;&gt; StopResizeWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions poolStopResizeOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.StopResizeWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopResizeWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt;&gt;" Usage="iPoolOperations.StopResizeWithHttpMessagesAsync (poolId, poolStopResizeOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolStopResizeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools, dessen Größenänderung Sie beenden möchten.
            </param>
        <param name="poolStopResizeOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Beendet einen aktiven größenänderungsvorgang für den Pool an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dies wird den Pool nicht auf den ursprünglichen Zustand vor der Größenänderung wiederhergestellt: nur beendet wird, keine weiteren Änderungen vorgenommen werden, und der Pool behält den aktuellen Zustand. Nach dem Beenden stabilisiert der Pool an die Anzahl der Knoten, den sie an, wenn der Beendigungsvorgang abgeschlossen wurde. Während des Beendigungsvorgangs ändert den Zuordnungsstatus des Pools zunächst zu beenden und dann zu gleichmäßig. Ein größenänderungsvorgang muss eine explizite Resize Pool-Anfrage nicht. Diese API kann auch verwendet werden, auf die anfängliche Größe des Pools anhalten, wenn es erstellt wird.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdatePropertiesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt;&gt; UpdatePropertiesWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter poolUpdatePropertiesParameter, Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions poolUpdatePropertiesOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt;&gt; UpdatePropertiesWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter poolUpdatePropertiesParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions poolUpdatePropertiesOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.UpdatePropertiesWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter,Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdatePropertiesWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter * Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt;&gt;" Usage="iPoolOperations.UpdatePropertiesWithHttpMessagesAsync (poolId, poolUpdatePropertiesParameter, poolUpdatePropertiesOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolUpdatePropertiesParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter" />
        <Parameter Name="poolUpdatePropertiesOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools aktualisieren.
            </param>
        <param name="poolUpdatePropertiesParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="poolUpdatePropertiesOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Eigenschaften des angegebenen Pools.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Vollständig ersetzt alle aktualisierbaren Eigenschaften des Pools. Z. B. wenn der Pool eine Startaufgabe zugeordnet und Startaufgabe nicht mit dieser Anforderung angegeben ist, entfernen Sie dann der Batch-Dienst wird die vorhandene Startaufgabe.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpgradeOSWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;&gt; UpgradeOSWithHttpMessagesAsync (string poolId, string targetOSVersion, Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions poolUpgradeOSOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;&gt; UpgradeOSWithHttpMessagesAsync(string poolId, string targetOSVersion, class Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions poolUpgradeOSOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.UpgradeOSWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpgradeOSWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;&gt;" Usage="iPoolOperations.UpgradeOSWithHttpMessagesAsync (poolId, targetOSVersion, poolUpgradeOSOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="poolUpgradeOSOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools aktualisieren.
            </param>
        <param name="targetOSVersion">
            Die Azure-Gastbetriebssystemversion, die auf den virtuellen Computern im Pool installiert werden soll.
            </param>
        <param name="poolUpgradeOSOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert das Betriebssystem des angegebenen Pools.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Während eines Upgrades Berechnen der Batch-dienstupgrades jeder Knoten im Pool. Wenn Compute-Knoten für das Upgrade ausgewählt ist, sind alle Aufgaben, die auf diesem Knoten ausgeführt wird aus dem Knoten entfernt und zurück an die Warteschlange erneut höher (oder auf einem anderen Serverknoten) ausgeführt wird. Der Knoten wird nicht verfügbar sein, bis das Upgrade abgeschlossen ist. Dieser Vorgang führt zu vorübergehend reduzierte Pool-Kapazität, wie Knoten außer Betrieb genommen werden, aktualisiert werden. Obwohl die Batch-Dienst versucht wird, um zu vermeiden, aktualisieren alle Serverknoten zur gleichen Zeit, garantiert jedoch nicht dazu (vor allem für kleine Pools); aus diesem Grund möglicherweise der Pool vorübergehend nicht verfügbar, um Aufgaben auszuführen. Wenn dieser Vorgang ausgeführt wird, wechselt der Pool zu aktualisieren. Wenn alle compute-Knoten die Aktualisierung beendet haben, wird der Poolstatus auf aktiv zurückgegeben. Während des Upgrades ausgeführt wird, gibt dem Pool CurrentOSVersion TargetOSVersion widerspiegelt, die Betriebssystemversion, der Knoten zu aktualisieren, dass Knoten ein Upgrade von der Betriebssystemversion an. Nachdem das Upgrade abgeschlossen ist, wird CurrentOSVersion aktualisiert, entsprechend der Version des Betriebssystems nun auf allen Knoten ausgeführt wird. Dieser Vorgang kann nur auf mit der Eigenschaft CloudServiceConfiguration erstellten Ressourcenpools aufgerufen werden.
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