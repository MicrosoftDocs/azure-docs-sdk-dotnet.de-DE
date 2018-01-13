<Type Name="IJobOperations" FullName="Microsoft.Azure.Management.Automation.IJobOperations">
  <TypeSignature Language="C#" Value="public interface IJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IJobOperations" />
  <TypeSignature Language="F#" Value="type IJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Der Dienstvorgang für Automation-Aufträge.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobCreateResponse&gt; CreateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.JobCreateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobCreateResponse&gt; CreateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.JobCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.CreateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : string * string * Microsoft.Azure.Management.Automation.Models.JobCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobCreateResponse&gt;" Usage="iJobOperations.CreateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobCreateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="parameters">
            Die Parameter für den Auftragsvorgang erstellen angegeben.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie einen Auftrag des Runbooks.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für den Auftragsvorgang erstellen.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, Guid jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.GetAsync(System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetResponse&gt;" Usage="iJobOperations.GetAsync (resourceGroupName, automationAccount, jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="jobId">
            Die Id des Auftrags.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Abgerufen Sie den Auftrag mit der Auftrags-Id werden.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für den Get Job-Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse&gt; GetOutputAsync (string resourceGroupName, string automationAccount, Guid jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse&gt; GetOutputAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.GetOutputAsync(System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOutputAsync : string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse&gt;" Usage="iJobOperations.GetOutputAsync (resourceGroupName, automationAccount, jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="jobId">
            Die Id des Auftrags.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Abrufen der Auftragsausgabe durch Auftrags-Id identifiziert.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für die Get-Job Vorgang ausgegeben werden.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRunbookContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse&gt; GetRunbookContentAsync (string resourceGroupName, string automationAccount, Guid jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse&gt; GetRunbookContentAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.GetRunbookContentAsync(System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetRunbookContentAsync : string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse&gt;" Usage="iJobOperations.GetRunbookContentAsync (resourceGroupName, automationAccount, jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="jobId">
            Die Id des Auftrags.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Abrufen des runbookinhalts aus der der Auftrag mit der Auftrags-Id an.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für den runbookinhalt Get Job-Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.JobListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.JobListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.Automation.Models.JobListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt;" Usage="iJobOperations.ListAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="parameters">
            Die Parameter für die Liste zur Verfügung gestellt.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Rufen Sie eine Liste der Aufträge an.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für die Liste Job-Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt;" Usage="iJobOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            Der Link zum Abrufen des nächsten Satzes von Elementen.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Abgerufen Sie weitere Liste der Aufträge werden.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für die Liste Job-Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync (string resourceGroupName, string automationAccount, Guid jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.ResumeAsync(System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResumeAsync : string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iJobOperations.ResumeAsync (resourceGroupName, automationAccount, jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="jobId">
            Die Id des Auftrags.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Den Auftrag mit JobId wird fortgesetzt.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)
            </summary>
        <returns>
            Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; StopAsync (string resourceGroupName, string automationAccount, Guid jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; StopAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.StopAsync(System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopAsync : string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iJobOperations.StopAsync (resourceGroupName, automationAccount, jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="jobId">
            Die Id des Auftrags.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Den Auftrag mit JobId zu beenden.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)
            </summary>
        <returns>
            Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync (string resourceGroupName, string automationAccount, Guid jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.SuspendAsync(System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuspendAsync : string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iJobOperations.SuspendAsync (resourceGroupName, automationAccount, jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="jobId">
            Die Id des Auftrags.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Anhalten des Auftrags mit JobId an.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)
            </summary>
        <returns>
            Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>