<Type Name="IJobScheduleOperations" FullName="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations">
  <TypeSignature Language="C#" Value="public interface IJobScheduleOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IJobScheduleOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IJobScheduleOperations" />
  <TypeSignature Language="F#" Value="type IJobScheduleOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            JobScheduleOperations-Vorgänge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders&gt;&gt; AddWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter cloudJobSchedule, Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions jobScheduleAddOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders&gt;&gt; AddWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter cloudJobSchedule, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions jobScheduleAddOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.AddWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter,Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter * Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders&gt;&gt;" Usage="iJobScheduleOperations.AddWithHttpMessagesAsync (cloudJobSchedule, jobScheduleAddOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cloudJobSchedule" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter" />
        <Parameter Name="jobScheduleAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cloudJobSchedule">
            Der Auftragszeitplan hinzugefügt werden.
            </param>
        <param name="jobScheduleAddOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Das angegebene Konto hinzugefügt Zeitplan für einen Auftrag.
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
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions jobScheduleDeleteOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions jobScheduleDeleteOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.DeleteWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders&gt;&gt;" Usage="iJobScheduleOperations.DeleteWithHttpMessagesAsync (jobScheduleId, jobScheduleDeleteOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu löschen.
            </param>
        <param name="jobScheduleDeleteOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen Zeitplan für Aufträge aus dem angegebenen Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie einen Auftragszeitplan löschen, löscht diese auch alle Aufträge und Aufgaben unter diesen Zeitplan an. Wenn Aufgaben gelöscht werden, werden auch alle Dateien in ihren Arbeitsverzeichnissen auf den Serverknoten gelöscht (während der Beibehaltungsdauer wird ignoriert). Die Auftrag-Zeitplan-Statistiken sind nicht mehr zugegriffen werden kann, sobald der Auftragszeitplan gelöscht wurde, obwohl sie weiterhin zum Konto lebensdauerstatistiken hinzugezählt werden.
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders&gt;&gt; DisableWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions jobScheduleDisableOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders&gt;&gt; DisableWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions jobScheduleDisableOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.DisableWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders&gt;&gt;" Usage="iJobScheduleOperations.DisableWithHttpMessagesAsync (jobScheduleId, jobScheduleDisableOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleDisableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu deaktivieren.
            </param>
        <param name="jobScheduleDisableOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Deaktiviert einen Auftragszeitplan.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Keine neuen Aufträge werden erstellt werden, bis wieder der Auftragszeitplan aktiviert ist.
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders&gt;&gt; EnableWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions jobScheduleEnableOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders&gt;&gt; EnableWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions jobScheduleEnableOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.EnableWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders&gt;&gt;" Usage="iJobScheduleOperations.EnableWithHttpMessagesAsync (jobScheduleId, jobScheduleEnableOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleEnableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu aktivieren.
            </param>
        <param name="jobScheduleEnableOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ermöglicht einen Auftragszeitplan.
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
    <Member MemberName="ExistsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool,Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsHeaders&gt;&gt; ExistsWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions jobScheduleExistsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;bool, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsHeaders&gt;&gt; ExistsWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions jobScheduleExistsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.ExistsWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool, Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsHeaders&gt;&gt;" Usage="iJobScheduleOperations.ExistsWithHttpMessagesAsync (jobScheduleId, jobScheduleExistsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Boolean,Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleExistsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans, die Sie überprüfen möchten.
            </param>
        <param name="jobScheduleExistsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft, ob der angegebene Auftrag-Zeitplan vorhanden ist.
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
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule,Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions jobScheduleGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions jobScheduleGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.GetWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule, Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders&gt;&gt;" Usage="iJobScheduleOperations.GetWithHttpMessagesAsync (jobScheduleId, jobScheduleGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule,Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu erhalten.
            </param>
        <param name="jobScheduleGetOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über den angegebenen Auftrag-Zeitplan ab.
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions jobScheduleListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions jobScheduleListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;, Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt;" Usage="iJobScheduleOperations.ListNextWithHttpMessagesAsync (nextPageLink, jobScheduleListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobScheduleListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="jobScheduleListNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Auftragszeitpläne im angegebenen Konto.
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
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions jobScheduleListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions jobScheduleListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.ListWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;, Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt;" Usage="iJobScheduleOperations.ListWithHttpMessagesAsync (jobScheduleListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Auftragszeitpläne im angegebenen Konto.
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt;&gt; PatchWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter jobSchedulePatchParameter, Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions jobSchedulePatchOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt;&gt; PatchWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter jobSchedulePatchParameter, class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions jobSchedulePatchOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.PatchWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter * Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt;&gt;" Usage="iJobScheduleOperations.PatchWithHttpMessagesAsync (jobScheduleId, jobSchedulePatchParameter, jobSchedulePatchOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobSchedulePatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter" />
        <Parameter Name="jobSchedulePatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu aktualisieren.
            </param>
        <param name="jobSchedulePatchParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="jobSchedulePatchOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Eigenschaften des Zeitplans angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dies ersetzt nur die Eigenschaften des Auftragszeitplans in der Anforderung angegeben. Die Zeitplan-Eigenschaft nicht mit dieser Anforderung angegeben ist, wird der Batch-Dienst z. B. den Zeitplan des vorhandenen beibehalten. Änderungen an einem Auftrag planen nur Auswirkungen auf Aufträge im Zeitplan erstellt werden, nachdem das Update stattgefunden hat; derzeit ausgeführte Aufträge sind nicht betroffen.
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions jobScheduleTerminateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions jobScheduleTerminateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.TerminateWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TerminateWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders&gt;&gt;" Usage="iJobScheduleOperations.TerminateWithHttpMessagesAsync (jobScheduleId, jobScheduleTerminateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            Die ID der der Auftragszeitplan beendet wird.
            </param>
        <param name="jobScheduleTerminateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Beendet einen Auftragszeitplan.
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
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter jobScheduleUpdateParameter, Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions jobScheduleUpdateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter jobScheduleUpdateParameter, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions jobScheduleUpdateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.UpdateWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter,Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter * Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders&gt;&gt;" Usage="iJobScheduleOperations.UpdateWithHttpMessagesAsync (jobScheduleId, jobScheduleUpdateParameter, jobScheduleUpdateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleUpdateParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter" />
        <Parameter Name="jobScheduleUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu aktualisieren.
            </param>
        <param name="jobScheduleUpdateParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="jobScheduleUpdateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Eigenschaften des Zeitplans angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dadurch wird vollständig ersetzt alle aktualisierbaren Eigenschaften des Auftragszeitplans. Wenn der Zeitplan-Eigenschaft nicht mit dieser Anforderung angegeben ist, wird der Batch-Dienst z. B. den Zeitplan des vorhandenen entfernt. Änderungen an einem Auftrag planen nur Auswirkungen auf Aufträge im Zeitplan erstellt werden, nachdem das Update stattgefunden hat; derzeit ausgeführte Aufträge sind nicht betroffen.
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