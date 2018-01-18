<Type Name="IProtectedItemOperationStatusesOperations" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations">
  <TypeSignature Language="C#" Value="public interface IProtectedItemOperationStatusesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IProtectedItemOperationStatusesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IProtectedItemOperationStatusesOperations" />
  <TypeSignature Language="F#" Value="type IProtectedItemOperationStatusesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e61ab-101">ProtectedItemOperationStatusesOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="e61ab-101">ProtectedItemOperationStatusesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;&gt; GetWithHttpMessagesAsync (string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string operationId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;&gt; GetWithHttpMessagesAsync(string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string operationId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;&gt;" Usage="iProtectedItemOperationStatusesOperations.GetWithHttpMessagesAsync (vaultName, resourceGroupName, fabricName, containerName, protectedItemName, operationId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultName">
            <span data-ttu-id="e61ab-102">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="e61ab-102">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e61ab-103">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="e61ab-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="e61ab-104">Name des Fabric, das Sichern des Elements zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="e61ab-104">Fabric name associated with the backup item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="e61ab-105">Der Containername das Sichern des Elements zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="e61ab-105">Container name associated with the backup item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="e61ab-106">Sichern des Elementname, deren Details werden abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="e61ab-106">Backup item name whose details are to be fetched.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="e61ab-107">OperationID darstellt, den Vorgang, deren Status abgerufen werden muss.</span><span class="sxs-lookup"><span data-stu-id="e61ab-107">OperationID represents the operation whose status needs to be fetched.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e61ab-108">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e61ab-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e61ab-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e61ab-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e61ab-110">Ruft den Status eines Vorgangs wie z. B. das Auslösen einer sicherungs wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="e61ab-110">Fetches the status of an operation such as triggering a backup, restore.</span></span> <span data-ttu-id="e61ab-111">Der Status kann in Bearbeitung, abgeschlossen oder fehlerhaft sein.</span><span class="sxs-lookup"><span data-stu-id="e61ab-111">The status can be in progress, completed or failed.</span></span> <span data-ttu-id="e61ab-112">Sie können die OperationStatus-Enumeration für alle möglichen Status des Vorgangs verweisen.</span><span class="sxs-lookup"><span data-stu-id="e61ab-112">You can refer to the OperationStatus enum for all the possible states of the operation.</span></span> <span data-ttu-id="e61ab-113">Einige Vorgänge Aufträge erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="e61ab-113">Some operations create jobs.</span></span> <span data-ttu-id="e61ab-114">Diese Methode gibt die Liste der Aufträge, die dem Vorgang zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="e61ab-114">This method returns the list of jobs associated with the operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e61ab-115">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e61ab-115">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e61ab-116">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e61ab-116">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e61ab-117">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e61ab-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>