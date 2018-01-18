<Type Name="IBackupOperationResultsOperations" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations">
  <TypeSignature Language="C#" Value="public interface IBackupOperationResultsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBackupOperationResultsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBackupOperationResultsOperations" />
  <TypeSignature Language="F#" Value="type IBackupOperationResultsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="258ee-101">BackupOperationResultsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="258ee-101">BackupOperationResultsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; GetWithHttpMessagesAsync (string vaultName, string resourceGroupName, string operationId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; GetWithHttpMessagesAsync(string vaultName, string resourceGroupName, string operationId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iBackupOperationResultsOperations.GetWithHttpMessagesAsync (vaultName, resourceGroupName, operationId, customHeaders, cancellationToken)" />
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
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultName">
            <span data-ttu-id="258ee-102">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="258ee-102">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="258ee-103">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="258ee-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="258ee-104">OperationID, der den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="258ee-104">OperationID which represents the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="258ee-105">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="258ee-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="258ee-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="258ee-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="258ee-107">Enthält der Status der Delete-Vorgänge wie etwa löschen Element gesichert.</span><span class="sxs-lookup"><span data-stu-id="258ee-107">Provides the status of the delete operations such as deleting backed up item.</span></span> <span data-ttu-id="258ee-108">Nachdem der Vorgang gestartet wurde, wird der Statuscode der Antwort akzeptiert werden.</span><span class="sxs-lookup"><span data-stu-id="258ee-108">Once the operation has started, the status code in the response would be Accepted.</span></span> <span data-ttu-id="258ee-109">Es wird weiterhin in diesem Status bis zum Abschluss erreicht.</span><span class="sxs-lookup"><span data-stu-id="258ee-109">It will continue to be in this state till it reaches completion.</span></span> <span data-ttu-id="258ee-110">Bei erfolgreichem Abschluss wird der Statuscode OK sein.</span><span class="sxs-lookup"><span data-stu-id="258ee-110">On successful completion, the status code will be OK.</span></span> <span data-ttu-id="258ee-111">Diese Methode erwartet OperationID als Argument an.</span><span class="sxs-lookup"><span data-stu-id="258ee-111">This method expects OperationID as an argument.</span></span> <span data-ttu-id="258ee-112">OperationID ist Teil des Location-Header der Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="258ee-112">OperationID is part of the Location header of the operation response.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="258ee-113">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="258ee-113">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="258ee-114">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="258ee-114">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>