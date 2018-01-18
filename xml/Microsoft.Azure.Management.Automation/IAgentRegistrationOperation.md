<Type Name="IAgentRegistrationOperation" FullName="Microsoft.Azure.Management.Automation.IAgentRegistrationOperation">
  <TypeSignature Language="C#" Value="public interface IAgentRegistrationOperation" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAgentRegistrationOperation" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IAgentRegistrationOperation" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAgentRegistrationOperation" />
  <TypeSignature Language="F#" Value="type IAgentRegistrationOperation = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f902d-101">Der Dienstvorgang für Automation agentregistrierungsinformationen.</span><span class="sxs-lookup"><span data-stu-id="f902d-101">Service operation for automation agent registration information.</span></span>  <span data-ttu-id="f902d-102">(siehe http://aka.ms/azureautomationsdk/agentregistrationoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="f902d-102">(see http://aka.ms/azureautomationsdk/agentregistrationoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AgentRegistrationGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAgentRegistrationOperation.GetAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationGetResponse&gt;" Usage="iAgentRegistrationOperation.GetAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f902d-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="f902d-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f902d-104">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="f902d-104">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f902d-105">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f902d-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f902d-106">Abgerufen Sie die agentregistrierungsinformationen Automatisierung werden.</span><span class="sxs-lookup"><span data-stu-id="f902d-106">Retrieve the automation agent registration information.</span></span>  <span data-ttu-id="f902d-107">(siehe http://aka.ms/azureautomationsdk/agentregistrationoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="f902d-107">(see http://aka.ms/azureautomationsdk/agentregistrationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f902d-108">Das Antwort-Modell für den Get-Agent Informationen Registrierungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="f902d-108">The response model for the get agent registration information operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyResponse&gt; RegenerateKeyAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter keyName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyResponse&gt; RegenerateKeyAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAgentRegistrationOperation.RegenerateKeyAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKeyAsync : string * string * Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyResponse&gt;" Usage="iAgentRegistrationOperation.RegenerateKeyAsync (resourceGroupName, automationAccount, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="keyName" Type="Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f902d-109">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="f902d-109">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f902d-110">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="f902d-110">The automation account name.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f902d-111">Der Name des Registrierungsschlüssels Agent neu generiert werden</span><span class="sxs-lookup"><span data-stu-id="f902d-111">The name of the agent registration key to be regenerated</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f902d-112">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f902d-112">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f902d-113">Generieren Sie einen primären oder sekundären-Agent-Registrierungsschlüssel (http://aka.ms/azureautomationsdk/agentregistrationoperations für Weitere Informationen siehe)</span><span class="sxs-lookup"><span data-stu-id="f902d-113">Regenerate a primary or secondary agent registration key  (see http://aka.ms/azureautomationsdk/agentregistrationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f902d-114">Das Antwort-Modell für den Agent-Registrierungsschlüssel generieren Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f902d-114">The response model for the agent registration key regenerate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>