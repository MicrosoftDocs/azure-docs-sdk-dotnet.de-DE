<Type Name="ITestJobOperations" FullName="Microsoft.Azure.Management.Automation.ITestJobOperations">
  <TypeSignature Language="C#" Value="public interface ITestJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITestJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ITestJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITestJobOperations" />
  <TypeSignature Language="F#" Value="type ITestJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Der Dienstvorgang für Automation Testaufträge.  (siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt; CreateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt; CreateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ITestJobOperations.CreateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : string * string * Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt;" Usage="iTestJobOperations.CreateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters" />
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
            Für den Create Test Job-Vorgang angegebene Parameter.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Erstellen eines Testauftrags des Runbooks.  (siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für das Erstellen, Testen Job-Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ITestJobOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt;" Usage="iTestJobOperations.GetAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="runbookName">
            Der Runbook-Name.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Abrufen des Testauftrags für das angegebene Runbook an.  (siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für die Get Job-Vorgang zu testen.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ITestJobOperations.ResumeAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResumeAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iTestJobOperations.ResumeAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
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
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="runbookName">
            Der Runbook-Name.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Fortsetzen des Testauftrags an.  (siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)
            </summary>
        <returns>
            Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; StopAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; StopAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ITestJobOperations.StopAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iTestJobOperations.StopAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
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
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="runbookName">
            Der Runbook-Name.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Beenden des Testauftrags an.  (siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)
            </summary>
        <returns>
            Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ITestJobOperations.SuspendAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuspendAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iTestJobOperations.SuspendAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
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
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="runbookName">
            Der Runbook-Name.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Anhalten des Testauftrags an.  (siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)
            </summary>
        <returns>
            Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>