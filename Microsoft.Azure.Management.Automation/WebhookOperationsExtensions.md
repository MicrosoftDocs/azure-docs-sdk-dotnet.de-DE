<Type Name="WebhookOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class WebhookOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit WebhookOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module WebhookOperationsExtensions" />
  <TypeSignature Language="F#" Value="type WebhookOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, parameters As WebhookCreateOrUpdateParameters) As WebhookCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Erforderlich. Der Name des Automation-Konto.
            </param>
        <param name="parameters">
            Erforderlich. Das Erstellen oder Aktualisieren der Parameter für Webhook.
            </param>
        <summary>
            Erstellen des webhooks Webhook namentlich identifiziert.  (siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für den Webhook erstellen oder aktualisieren.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, parameters As WebhookCreateOrUpdateParameters) As Task(Of WebhookCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Erforderlich. Der Name des Automation-Konto.
            </param>
        <param name="parameters">
            Erforderlich. Das Erstellen oder Aktualisieren der Parameter für Webhook.
            </param>
        <summary>
            Erstellen des webhooks Webhook namentlich identifiziert.  (siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für den Webhook erstellen oder aktualisieren.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, webhookName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Erforderlich. Der Name des Automation-Konto.
            </param>
        <param name="webhookName">
            Erforderlich. Den webhooknamen.
            </param>
        <summary>
            Löschen des webhooks anhand des Namens an.  (siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)
            </summary>
        <returns>
            Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, webhookName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Erforderlich. Der Name des Automation-Konto.
            </param>
        <param name="webhookName">
            Erforderlich. Den webhooknamen.
            </param>
        <summary>
            Löschen des webhooks anhand des Namens an.  (siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)
            </summary>
        <returns>
            Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateUri">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse GenerateUri (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse GenerateUri(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GenerateUri(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateUri (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String) As WebhookGenerateUriResponse" />
      <MemberSignature Language="F#" Value="static member GenerateUri : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GenerateUri (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. Der Name der Ressourcengruppe.
            </param>
        <param name="automationAccount">
            Erforderlich. Der Name des Automation-Konto.
            </param>
        <summary>
            Generiert einen Uri für die Verwendung in einen Webhook zu erstellen.  (siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für die Webhook-Get-Uri-Antwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateUriAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse&gt; GenerateUriAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse&gt; GenerateUriAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GenerateUriAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateUriAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String) As Task(Of WebhookGenerateUriResponse)" />
      <MemberSignature Language="F#" Value="static member GenerateUriAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GenerateUriAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. Der Name der Ressourcengruppe.
            </param>
        <param name="automationAccount">
            Erforderlich. Der Name des Automation-Konto.
            </param>
        <summary>
            Generiert einen Uri für die Verwendung in einen Webhook zu erstellen.  (siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für die Webhook-Get-Uri-Antwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookGetResponse Get (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookGetResponse Get(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, webhookName As String) As WebhookGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.WebhookGetResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Get (operations, resourceGroupName, automationAccount, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Erforderlich. Der Name des Automation-Konto.
            </param>
        <param name="webhookName">
            Erforderlich. Den webhooknamen.
            </param>
        <summary>
            Abrufen des webhooks Webhook namentlich identifiziert.  (siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für den Webhook Abrufvorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, webhookName As String) As Task(Of WebhookGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Erforderlich. Der Name des Automation-Konto.
            </param>
        <param name="webhookName">
            Erforderlich. Den webhooknamen.
            </param>
        <summary>
            Abrufen des webhooks Webhook namentlich identifiziert.  (siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für den Webhook Abrufvorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookListResponse List (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookListResponse List(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.List(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As WebhookListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.WebhookListResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.List (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Erforderlich. Der Name des Automation-Konto.
            </param>
        <param name="runbookName">
            Optional. Der Automation-Runbook-Name.
            </param>
        <summary>
            Rufen Sie eine Liste von Webhooks.  (siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für die Liste Webhook-Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of WebhookListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Erforderlich. Der Name des Automation-Konto.
            </param>
        <param name="runbookName">
            Optional. Der Automation-Runbook-Name.
            </param>
        <summary>
            Rufen Sie eine Liste von Webhooks.  (siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für die Liste Webhook-Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookListResponse ListNext (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookListResponse ListNext(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IWebhookOperations, nextLink As String) As WebhookListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IWebhookOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.WebhookListResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.
            </param>
        <param name="nextLink">
            Erforderlich. Der Link zum Abrufen des nächsten Satzes von Elementen.
            </param>
        <summary>
            Abgerufen Sie weitere Liste der Webhooks werden.  (siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für die Liste Webhook-Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IWebhookOperations, nextLink As String) As Task(Of WebhookListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.
            </param>
        <param name="nextLink">
            Erforderlich. Der Link zum Abrufen des nächsten Satzes von Elementen.
            </param>
        <summary>
            Abgerufen Sie weitere Liste der Webhooks werden.  (siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für die Liste Webhook-Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookGetResponse Patch (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookGetResponse Patch(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, parameters As WebhookPatchParameters) As WebhookGetResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters -&gt; Microsoft.Azure.Management.Automation.Models.WebhookGetResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Patch (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Erforderlich. Der Name des Automation-Konto.
            </param>
        <param name="parameters">
            Erforderlich. Die Patch-Parameter für Webhook.
            </param>
        <summary>
            Patch des webhooks Webhook namentlich identifiziert.  (siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für den Webhook Abrufvorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, parameters As WebhookPatchParameters) As Task(Of WebhookGetResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.PatchAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Erforderlich. Der Name des Automation-Konto.
            </param>
        <param name="parameters">
            Erforderlich. Die Patch-Parameter für Webhook.
            </param>
        <summary>
            Patch des webhooks Webhook namentlich identifiziert.  (siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für den Webhook Abrufvorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>