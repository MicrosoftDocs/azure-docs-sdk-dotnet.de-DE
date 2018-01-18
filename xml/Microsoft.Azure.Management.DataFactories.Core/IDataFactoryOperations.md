<Type Name="IDataFactoryOperations" FullName="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations">
  <TypeSignature Language="C#" Value="public interface IDataFactoryOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataFactoryOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataFactoryOperations" />
  <TypeSignature Language="F#" Value="type IDataFactoryOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fcc35-101">Vorgänge zum Verwalten von Data Factorys.</span><span class="sxs-lookup"><span data-stu-id="fcc35-101">Operations for managing data factories.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.BeginCreateOrUpdateAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAsync : string * Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;" Usage="iDataFactoryOperations.BeginCreateOrUpdateAsync (resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fcc35-102">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="fcc35-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fcc35-103">Die Parameter zum Erstellen oder Aktualisieren einer Data Factory erforderlich.</span><span class="sxs-lookup"><span data-stu-id="fcc35-103">The parameters required to create or update a data factory.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fcc35-104">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fcc35-104">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fcc35-105">Erstellen oder Aktualisieren einer Data Factory.</span><span class="sxs-lookup"><span data-stu-id="fcc35-105">Create or update a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fcc35-106">Erstellen oder aktualisieren Data Factory Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="fcc35-106">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.CreateOrUpdateAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;" Usage="iDataFactoryOperations.CreateOrUpdateAsync (resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fcc35-107">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="fcc35-107">The resource group name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fcc35-108">Die Parameter zum Erstellen oder Aktualisieren einer Data Factory erforderlich.</span><span class="sxs-lookup"><span data-stu-id="fcc35-108">The parameters required to create or update a data factory.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fcc35-109">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fcc35-109">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fcc35-110">Erstellen oder Aktualisieren einer Data Factory.</span><span class="sxs-lookup"><span data-stu-id="fcc35-110">Create or update a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fcc35-111">Erstellen oder aktualisieren Data Factory Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="fcc35-111">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.DeleteAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iDataFactoryOperations.DeleteAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fcc35-112">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="fcc35-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="fcc35-113">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="fcc35-113">A unique data factory instance name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fcc35-114">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fcc35-114">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fcc35-115">Löschen Sie eine Data Factory-Instanz.</span><span class="sxs-lookup"><span data-stu-id="fcc35-115">Delete a data factory instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fcc35-116">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="fcc35-116">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.GetAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt;" Usage="iDataFactoryOperations.GetAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fcc35-117">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="fcc35-117">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="fcc35-118">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="fcc35-118">A unique data factory instance name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fcc35-119">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fcc35-119">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fcc35-120">Ruft eine Instanz einer Factory ab.</span><span class="sxs-lookup"><span data-stu-id="fcc35-120">Gets a data factory instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fcc35-121">Get Data Factory Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="fcc35-121">The Get data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCreateOrUpdateStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;" Usage="iDataFactoryOperations.GetCreateOrUpdateStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            <span data-ttu-id="fcc35-122">Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="fcc35-122">Location value returned by the Begin operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fcc35-123">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fcc35-123">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fcc35-124">Der Vorgang Get Operation Status Gibt den Status des angegebenen Vorgangs zurück.</span><span class="sxs-lookup"><span data-stu-id="fcc35-124">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="fcc35-125">Nach dem Aufrufen eines asynchronen Vorgangs, können Sie aufrufen Vorgangsstatus abrufen, um festzustellen, ob der Vorgang erfolgreich war, fehlgeschlagen ist, oder ist noch nicht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="fcc35-125">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fcc35-126">Erstellen oder aktualisieren Data Factory Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="fcc35-126">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListAsync (string resourceGroupName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListAsync(string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.ListAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;" Usage="iDataFactoryOperations.ListAsync (resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fcc35-127">Der Ressourcengruppenname von Data-Factorys.</span><span class="sxs-lookup"><span data-stu-id="fcc35-127">The resource group name of the data factories.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fcc35-128">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fcc35-128">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fcc35-129">Ruft die erste Seite der Data Factory-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="fcc35-129">Gets the first page of data factory instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fcc35-130">Liste Data Factorys Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="fcc35-130">The List data factories operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;" Usage="iDataFactoryOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="fcc35-131">Die Url mit der nächsten Seite des Data-Factorys.</span><span class="sxs-lookup"><span data-stu-id="fcc35-131">The url to the next data factories page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fcc35-132">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fcc35-132">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fcc35-133">Ruft die nächste Seite der Data Factory-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="fcc35-133">Gets the next page of data factory instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fcc35-134">Liste Data Factorys Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="fcc35-134">The List data factories operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>