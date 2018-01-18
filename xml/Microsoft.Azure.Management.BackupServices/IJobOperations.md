<Type Name="IJobOperations" FullName="Microsoft.Azure.Management.BackupServices.IJobOperations">
  <TypeSignature Language="C#" Value="public interface IJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IJobOperations" />
  <TypeSignature Language="F#" Value="type IJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dd63e-101">Definition der auftragsvorgänge für Azure backup-Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="dd63e-101">Definition of Job operations for Azure backup extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMJobDetails&gt; GetAsync (string resourceGroupName, string resourceName, string name, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMJobDetails&gt; GetAsync(string resourceGroupName, string resourceName, string name, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IJobOperations.GetAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMJobDetails&gt;" Usage="iJobOperations.GetAsync (resourceGroupName, resourceName, name, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMJobDetails&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="name">
            <span data-ttu-id="dd63e-102">Der Name des Auftrags, deren Details abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="dd63e-102">Name of the job whose details should be retrieved.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="dd63e-103">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="dd63e-103">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dd63e-104">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="dd63e-104">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dd63e-105">Details eines bestimmten Auftrags abrufen.</span><span class="sxs-lookup"><span data-stu-id="dd63e-105">Get details of a particular job.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dd63e-106">Antwort-Modell für den Auftragsvorgang-details</span><span class="sxs-lookup"><span data-stu-id="dd63e-106">Response model for job details operation</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMJobList&gt; ListAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CSMJobQueryObject parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMJobList&gt; ListAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CSMJobQueryObject parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IJobOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMJobQueryObject,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CSMJobQueryObject * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMJobList&gt;" Usage="iJobOperations.ListAsync (resourceGroupName, resourceName, parameters, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMJobList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMJobQueryObject" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="parameters">
            <span data-ttu-id="dd63e-107">Auftrag Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="dd63e-107">Job query parameter.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="dd63e-108">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="dd63e-108">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dd63e-109">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="dd63e-109">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dd63e-110">Ruft die Liste aller Aufträge, die vom angegebenen Filter abgefragt.</span><span class="sxs-lookup"><span data-stu-id="dd63e-110">Get the list of all jobs queried by specified filters.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dd63e-111">PowerShell-Response-Objekt</span><span class="sxs-lookup"><span data-stu-id="dd63e-111">Powershell response object</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; StopAsync (string resourceGroupName, string resourceName, string name, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; StopAsync(string resourceGroupName, string resourceName, string name, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IJobOperations.StopAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iJobOperations.StopAsync (resourceGroupName, resourceName, name, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="name">
            <span data-ttu-id="dd63e-112">Der Name des Auftrags, der beendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="dd63e-112">Name of the job which should be stopped.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="dd63e-113">Benutzerdefinierte Anforderungsheader für den Aufruf.</span><span class="sxs-lookup"><span data-stu-id="dd63e-113">Custom request headers to make the call.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dd63e-114">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="dd63e-114">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dd63e-115">Abbruch eines Auftrags auslösen.</span><span class="sxs-lookup"><span data-stu-id="dd63e-115">Trigger cancellation of a job.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dd63e-116">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="dd63e-116">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>