<Type Name="IConnectionTypeOperations" FullName="Microsoft.Azure.Management.Automation.IConnectionTypeOperations">
  <TypeSignature Language="C#" Value="public interface IConnectionTypeOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IConnectionTypeOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IConnectionTypeOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IConnectionTypeOperations" />
  <TypeSignature Language="F#" Value="type IConnectionTypeOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d6e7a-101">Der Dienstvorgang für Automation Connectiontypes.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-101">Service operation for automation connectiontypes.</span></span>  <span data-ttu-id="d6e7a-102">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="d6e7a-102">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionTypeOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse&gt;" Usage="iConnectionTypeOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d6e7a-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="d6e7a-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d6e7a-104">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d6e7a-105">Die Parameter für den Verbindungstyp CREATE- oder Update zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-105">The parameters supplied to the create or update connectiontype operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d6e7a-106">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d6e7a-107">Erstellen Sie einen Verbindungstyp.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-107">Create a connectiontype.</span></span>  <span data-ttu-id="d6e7a-108">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="d6e7a-108">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d6e7a-109">Das Antwort-Modell für den Vorgang erstellen oder aktualisieren Verbindung Typ.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-109">The response model for the create or update connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string connectionTypeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string connectionTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionTypeOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iConnectionTypeOperations.DeleteAsync (resourceGroupName, automationAccount, connectionTypeName, cancellationToken)" />
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
        <Parameter Name="connectionTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d6e7a-110">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="d6e7a-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d6e7a-111">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-111">The automation account name.</span></span>
            </param>
        <param name="connectionTypeName">
            <span data-ttu-id="d6e7a-112">Der Name der Verbindungstyp.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-112">The name of connectiontype.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d6e7a-113">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d6e7a-114">Löschen Sie den Verbindungstyp an.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-114">Delete the connectiontype.</span></span>  <span data-ttu-id="d6e7a-115">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="d6e7a-115">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d6e7a-116">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-116">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string connectionTypeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string connectionTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionTypeOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse&gt;" Usage="iConnectionTypeOperations.GetAsync (resourceGroupName, automationAccount, connectionTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="connectionTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d6e7a-117">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="d6e7a-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d6e7a-118">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-118">The automation account name.</span></span>
            </param>
        <param name="connectionTypeName">
            <span data-ttu-id="d6e7a-119">Der Name der Verbindungstyp.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-119">The name of connectiontype.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d6e7a-120">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d6e7a-121">Rufen Sie den Verbindungstyp Verbindungstyp namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-121">Retrieve the connectiontype identified by connectiontype name.</span></span>
            <span data-ttu-id="d6e7a-122">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="d6e7a-122">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d6e7a-123">Das Antwort-Modell für den Abrufvorgang für Verbindung Typ.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-123">The response model for the get connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionTypeOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt;" Usage="iConnectionTypeOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d6e7a-124">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="d6e7a-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d6e7a-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-125">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d6e7a-126">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-126">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d6e7a-127">Eine Liste der Connectiontypes abzurufen.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-127">Retrieve a list of connectiontypes.</span></span>  <span data-ttu-id="d6e7a-128">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="d6e7a-128">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d6e7a-129">Das Antwort-Modell für den Typ des auflistungsvorgangs-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-129">The response model for the list connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionTypeOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt;" Usage="iConnectionTypeOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="d6e7a-130">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-130">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d6e7a-131">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d6e7a-132">Abgerufen Sie weitere Liste der Connectiontypes werden.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-132">Retrieve next list of connectiontypes.</span></span>  <span data-ttu-id="d6e7a-133">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="d6e7a-133">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d6e7a-134">Das Antwort-Modell für den Typ des auflistungsvorgangs-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="d6e7a-134">The response model for the list connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>