<Type Name="IConnectionOperations" FullName="Microsoft.Azure.Management.Automation.IConnectionOperations">
  <TypeSignature Language="C#" Value="public interface IConnectionOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IConnectionOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IConnectionOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IConnectionOperations" />
  <TypeSignature Language="F#" Value="type IConnectionOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8fadb-101">Der Dienstvorgang für Automation-Verbindungen.</span><span class="sxs-lookup"><span data-stu-id="8fadb-101">Service operation for automation connections.</span></span>  <span data-ttu-id="8fadb-102">(siehe http://aka.ms/azureautomationsdk/connectionoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8fadb-102">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateResponse&gt;" Usage="iConnectionOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8fadb-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="8fadb-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8fadb-104">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="8fadb-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8fadb-105">Die Parameter für die Verbindung erstellen oder Aktualisieren zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="8fadb-105">The parameters supplied to the create or update connection operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8fadb-106">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8fadb-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8fadb-107">Erstellen Sie eine Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8fadb-107">Create a connection.</span></span>  <span data-ttu-id="8fadb-108">(siehe http://aka.ms/azureautomationsdk/connectionoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8fadb-108">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8fadb-109">Das Antwort-Modell für die Verbindungsoperation erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="8fadb-109">The response model for the create or update connection operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string connectionName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string connectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iConnectionOperations.DeleteAsync (resourceGroupName, automationAccount, connectionName, cancellationToken)" />
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
        <Parameter Name="connectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8fadb-110">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="8fadb-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8fadb-111">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="8fadb-111">The automation account name.</span></span>
            </param>
        <param name="connectionName">
            <span data-ttu-id="8fadb-112">Der Name der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8fadb-112">The name of connection.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8fadb-113">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8fadb-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8fadb-114">Löschen Sie die Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="8fadb-114">Delete the connection.</span></span>  <span data-ttu-id="8fadb-115">(siehe http://aka.ms/azureautomationsdk/connectionoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8fadb-115">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8fadb-116">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="8fadb-116">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string connectionName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string connectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionGetResponse&gt;" Usage="iConnectionOperations.GetAsync (resourceGroupName, automationAccount, connectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="connectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8fadb-117">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="8fadb-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8fadb-118">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="8fadb-118">The automation account name.</span></span>
            </param>
        <param name="connectionName">
            <span data-ttu-id="8fadb-119">Der Name der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8fadb-119">The name of connection.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8fadb-120">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8fadb-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8fadb-121">Rufen Sie die Verbindung nach Verbindungsname identifiziert.</span><span class="sxs-lookup"><span data-stu-id="8fadb-121">Retrieve the connection identified by connection name.</span></span>  <span data-ttu-id="8fadb-122">(siehe http://aka.ms/azureautomationsdk/connectionoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8fadb-122">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8fadb-123">Das Antwort-Modell für den Abrufvorgang für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8fadb-123">The response model for the get connection operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt;" Usage="iConnectionOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8fadb-124">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="8fadb-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8fadb-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="8fadb-125">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8fadb-126">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8fadb-126">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8fadb-127">Rufen Sie eine Liste der Verbindungen.</span><span class="sxs-lookup"><span data-stu-id="8fadb-127">Retrieve a list of connections.</span></span>  <span data-ttu-id="8fadb-128">(siehe http://aka.ms/azureautomationsdk/connectionoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8fadb-128">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8fadb-129">Das Antwort-Modell für den Auflistungsvorgang für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8fadb-129">The response model for the list connection operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt;" Usage="iConnectionOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="8fadb-130">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="8fadb-130">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8fadb-131">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8fadb-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8fadb-132">Rufen Sie weitere Liste der Verbindungen.</span><span class="sxs-lookup"><span data-stu-id="8fadb-132">Retrieve next list of connections.</span></span>  <span data-ttu-id="8fadb-133">(siehe http://aka.ms/azureautomationsdk/connectionoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8fadb-133">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8fadb-134">Das Antwort-Modell für den Auflistungsvorgang für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8fadb-134">The response model for the list connection operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionOperations.PatchAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iConnectionOperations.PatchAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
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
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8fadb-135">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="8fadb-135">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8fadb-136">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="8fadb-136">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8fadb-137">Die Parameter, die beim Patch ein Vorgangs für die Verbindung angegeben.</span><span class="sxs-lookup"><span data-stu-id="8fadb-137">The parameters supplied to the patch a connection operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8fadb-138">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8fadb-138">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8fadb-139">Eine Verbindung zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="8fadb-139">Update a connection.</span></span>  <span data-ttu-id="8fadb-140">(siehe http://aka.ms/azureautomationsdk/connectionoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8fadb-140">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8fadb-141">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="8fadb-141">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>