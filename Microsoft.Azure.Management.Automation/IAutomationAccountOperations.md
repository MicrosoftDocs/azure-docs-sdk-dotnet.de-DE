<Type Name="IAutomationAccountOperations" FullName="Microsoft.Azure.Management.Automation.IAutomationAccountOperations">
  <TypeSignature Language="C#" Value="public interface IAutomationAccountOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAutomationAccountOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IAutomationAccountOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAutomationAccountOperations" />
  <TypeSignature Language="F#" Value="type IAutomationAccountOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Der Dienstvorgang für Automation-Konten.  (siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, class Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAutomationAccountOperations.CreateOrUpdateAsync(System.String,Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse&gt;" Usage="iAutomationAccountOperations.CreateOrUpdateAsync (resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="parameters">
            Parameter für das Automation-Konto erstellen oder aktualisieren bereitgestellt.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie ein Automation-Konto.  (siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für den Vorgang der Konto erstellen oder aktualisieren.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccountName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAutomationAccountOperations.DeleteAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iAutomationAccountOperations.DeleteAsync (resourceGroupName, automationAccountName, cancellationToken)" />
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
        <Parameter Name="automationAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccountName">
            Automation-Kontonamen.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie ein Automation-Konto.  (siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)
            </summary>
        <returns>
            Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAutomationAccountOperations.GetAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse&gt;" Usage="iAutomationAccountOperations.GetAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Abgerufen Sie der Name von Konto werden.  (siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für den Abrufvorgang für das Konto.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt; ListAsync (string resourceGroupName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt; ListAsync(string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAutomationAccountOperations.ListAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt;" Usage="iAutomationAccountOperations.ListAsync (resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Rufen Sie eine Liste von Konten.  (siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für die Konto-Auflistungsvorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAutomationAccountOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt;" Usage="iAutomationAccountOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt;</ReturnType>
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
            Abgerufen Sie weitere Liste der Konten werden.  (siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für die Konto-Auflistungsvorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse&gt; PatchAsync (string resourceGroupName, Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse&gt; PatchAsync(string resourceGroupName, class Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAutomationAccountOperations.PatchAsync(System.String,Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse&gt;" Usage="iAutomationAccountOperations.PatchAsync (resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="parameters">
            Parameter für die Patch-Automation-Konto bereitgestellt.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie ein Automation-Konto.  (siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für den Erstellungsvorgang für das Konto.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>