<Type Name="IJobOperationResultsOperations" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations">
  <TypeSignature Language="C#" Value="public interface IJobOperationResultsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IJobOperationResultsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IJobOperationResultsOperations" />
  <TypeSignature Language="F#" Value="type IJobOperationResultsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7316f-101">JobOperationResultsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="7316f-101">JobOperationResultsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; GetWithHttpMessagesAsync (string vaultName, string resourceGroupName, string jobName, string operationId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; GetWithHttpMessagesAsync(string vaultName, string resourceGroupName, string jobName, string operationId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iJobOperationResultsOperations.GetWithHttpMessagesAsync (vaultName, resourceGroupName, jobName, operationId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultName">
            <span data-ttu-id="7316f-102">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="7316f-102">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7316f-103">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7316f-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="7316f-104">Name des Auftrags, deren Ergebnis des Vorgangs wurde abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="7316f-104">Job name whose operation result has to be fetched.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="7316f-105">OperationID, der den Vorgang darstellt, dessen Ergebnis beinhaltet einen abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="7316f-105">OperationID which represents the operation whose result has to be fetched.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7316f-106">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="7316f-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7316f-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7316f-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7316f-108">Dadurch wird das Ergebnis der Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="7316f-108">Fetches the result of any operation.</span></span>
            <span data-ttu-id="7316f-109">der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="7316f-109">the operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7316f-110">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="7316f-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7316f-111">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="7316f-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>