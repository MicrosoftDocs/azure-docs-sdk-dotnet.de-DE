<Type Name="IExportJobsOperationResultsOperations" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations">
  <TypeSignature Language="C#" Value="public interface IExportJobsOperationResultsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IExportJobsOperationResultsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IExportJobsOperationResultsOperations" />
  <TypeSignature Language="F#" Value="type IExportJobsOperationResultsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1e9ee-101">ExportJobsOperationResultsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="1e9ee-101">ExportJobsOperationResultsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource&gt;&gt; GetWithHttpMessagesAsync (string vaultName, string resourceGroupName, string operationId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource&gt;&gt; GetWithHttpMessagesAsync(string vaultName, string resourceGroupName, string operationId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource&gt;&gt;" Usage="iExportJobsOperationResultsOperations.GetWithHttpMessagesAsync (vaultName, resourceGroupName, operationId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultName">
            <span data-ttu-id="1e9ee-102">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="1e9ee-102">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e9ee-103">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="1e9ee-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="1e9ee-104">OperationID des exportauftrags dar.</span><span class="sxs-lookup"><span data-stu-id="1e9ee-104">OperationID which represents the export job.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1e9ee-105">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="1e9ee-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1e9ee-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1e9ee-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e9ee-107">Ruft das Ergebnis des Vorgangs des Vorgangs durch Exportieren Aufträge API ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="1e9ee-107">Gets the operation result of operation triggered by Export Jobs API.</span></span> <span data-ttu-id="1e9ee-108">Wenn der Vorgang erfolgreich ist, enthält er auch URL des Blob und einen SAS-Schlüssel, auf die gleiche.</span><span class="sxs-lookup"><span data-stu-id="1e9ee-108">If the operation is successful, then it also contains URL of a Blob and a SAS key to access the same.</span></span> <span data-ttu-id="1e9ee-109">Das Blob enthält, in die serialisierte JSON-Format exportierte Aufträgen.</span><span class="sxs-lookup"><span data-stu-id="1e9ee-109">The blob contains exported jobs in JSON serialized format.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1e9ee-110">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="1e9ee-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1e9ee-111">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="1e9ee-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1e9ee-112">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="1e9ee-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>