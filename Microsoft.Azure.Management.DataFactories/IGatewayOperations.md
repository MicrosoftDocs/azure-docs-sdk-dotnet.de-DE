<Type Name="IGatewayOperations" FullName="Microsoft.Azure.Management.DataFactories.IGatewayOperations">
  <TypeSignature Language="C#" Value="public interface IGatewayOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IGatewayOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.IGatewayOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IGatewayOperations" />
  <TypeSignature Language="F#" Value="type IGatewayOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="eeac1-101">Vorgänge zum Verwalten von Data Factory-Gateways.</span><span class="sxs-lookup"><span data-stu-id="eeac1-101">Operations for managing data factory gateways.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.BeginCreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="iGatewayOperations.BeginCreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eeac1-102">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eeac1-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eeac1-103">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="eeac1-103">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eeac1-104">Die Parameter zum Erstellen oder Aktualisieren einer Data Factory-Gateway erforderlich.</span><span class="sxs-lookup"><span data-stu-id="eeac1-104">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eeac1-105">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eeac1-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eeac1-106">Erstellen Sie oder aktualisieren Sie einer Data Factory-Gateway.</span><span class="sxs-lookup"><span data-stu-id="eeac1-106">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eeac1-107">Erstellen oder aktualisieren Data Factory-Gateway Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="eeac1-107">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iGatewayOperations.BeginDeleteAsync (resourceGroupName, dataFactoryName, gatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eeac1-108">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eeac1-108">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eeac1-109">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="eeac1-109">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="eeac1-110">Der Name des Gateways zu löschen.</span><span class="sxs-lookup"><span data-stu-id="eeac1-110">Name of the gateway to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eeac1-111">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eeac1-111">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eeac1-112">Löschen Sie ein Data Factory-Gateway.</span><span class="sxs-lookup"><span data-stu-id="eeac1-112">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eeac1-113">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="eeac1-113">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="iGatewayOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eeac1-114">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eeac1-114">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eeac1-115">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="eeac1-115">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eeac1-116">Die Parameter zum Erstellen oder Aktualisieren einer Data Factory-Gateway erforderlich.</span><span class="sxs-lookup"><span data-stu-id="eeac1-116">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eeac1-117">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eeac1-117">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eeac1-118">Erstellen Sie oder aktualisieren Sie einer Data Factory-Gateway.</span><span class="sxs-lookup"><span data-stu-id="eeac1-118">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eeac1-119">Erstellen oder aktualisieren Data Factory-Gateway Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="eeac1-119">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iGatewayOperations.DeleteAsync (resourceGroupName, dataFactoryName, gatewayName, cancellationToken)" />
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
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eeac1-120">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eeac1-120">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eeac1-121">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="eeac1-121">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="eeac1-122">Der Name des Gateways zu löschen.</span><span class="sxs-lookup"><span data-stu-id="eeac1-122">Name of the gateway to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eeac1-123">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eeac1-123">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eeac1-124">Löschen Sie ein Data Factory-Gateway.</span><span class="sxs-lookup"><span data-stu-id="eeac1-124">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eeac1-125">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="eeac1-125">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt;" Usage="iGatewayOperations.GetAsync (resourceGroupName, dataFactoryName, gatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eeac1-126">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eeac1-126">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eeac1-127">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="eeac1-127">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="eeac1-128">Der Name des Gateways zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="eeac1-128">Name of the gateway to get.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eeac1-129">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eeac1-129">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eeac1-130">Ruft ein Data Factory-Gateway ab.</span><span class="sxs-lookup"><span data-stu-id="eeac1-130">Gets a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eeac1-131">Get Data Factory-Gateway Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="eeac1-131">The Get data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCreateOrUpdateStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="iGatewayOperations.GetCreateOrUpdateStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            <span data-ttu-id="eeac1-132">Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="eeac1-132">Location value returned by the Begin operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eeac1-133">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eeac1-133">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eeac1-134">Der Vorgang Get Operation Status Gibt den Status des angegebenen Vorgangs zurück.</span><span class="sxs-lookup"><span data-stu-id="eeac1-134">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="eeac1-135">Nach dem Aufrufen eines asynchronen Vorgangs, können Sie aufrufen Vorgangsstatus abrufen, um festzustellen, ob der Vorgang erfolgreich war, fehlgeschlagen ist, oder ist noch nicht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="eeac1-135">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eeac1-136">Erstellen oder aktualisieren Data Factory-Gateway Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="eeac1-136">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt;" Usage="iGatewayOperations.ListAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eeac1-137">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eeac1-137">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eeac1-138">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="eeac1-138">A unique data factory instance name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eeac1-139">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eeac1-139">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eeac1-140">Listen Sie aller Gateways unter einer Data Factory an auf.</span><span class="sxs-lookup"><span data-stu-id="eeac1-140">List all gateways under a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eeac1-141">Liste Data Factory-Gateways Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="eeac1-141">The List data factory gateways operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthKeysAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt; ListAuthKeysAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt; ListAuthKeysAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.ListAuthKeysAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAuthKeysAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt;" Usage="iGatewayOperations.ListAuthKeysAsync (resourceGroupName, dataFactoryName, gatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eeac1-142">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eeac1-142">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eeac1-143">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="eeac1-143">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="eeac1-144">Der Name des Gateways auf Liste Auth-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="eeac1-144">The name of the gateway to list auth keys.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eeac1-145">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eeac1-145">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eeac1-146">Liste Auth-Schlüssel des Gateways.</span><span class="sxs-lookup"><span data-stu-id="eeac1-146">List auth keys of the gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eeac1-147">Liste Data Factory-Gateway Auth Schlüssel Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="eeac1-147">The List data factory gateway auth keys operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateAuthKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt; RegenerateAuthKeyAsync (string resourceGroupName, string dataFactoryName, string gatewayName, Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt; RegenerateAuthKeyAsync(string resourceGroupName, string dataFactoryName, string gatewayName, class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.RegenerateAuthKeyAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateAuthKeyAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt;" Usage="iGatewayOperations.RegenerateAuthKeyAsync (resourceGroupName, dataFactoryName, gatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eeac1-148">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eeac1-148">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eeac1-149">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="eeac1-149">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="eeac1-150">Der Name des Gateways auf Auth-Schlüssel erneut generieren.</span><span class="sxs-lookup"><span data-stu-id="eeac1-150">The name of the gateway to regenerate auth key.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eeac1-151">Der Name des Gateway-Auth-Schlüssels neu generiert werden.</span><span class="sxs-lookup"><span data-stu-id="eeac1-151">Name of the gateway auth key to be regenerated.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eeac1-152">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eeac1-152">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eeac1-153">Generieren Sie Gateway-Auth-Schlüssel erneut.</span><span class="sxs-lookup"><span data-stu-id="eeac1-153">Regenerate gateway auth key.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eeac1-154">Regenerate Gateway Authentication Key Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="eeac1-154">The regenerate gateway auth key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt; RegenerateKeyAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt; RegenerateKeyAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.RegenerateKeyAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKeyAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt;" Usage="iGatewayOperations.RegenerateKeyAsync (resourceGroupName, dataFactoryName, gatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eeac1-155">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eeac1-155">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eeac1-156">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="eeac1-156">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="eeac1-157">Der Name des Gateways auf Schlüssel erneut generieren.</span><span class="sxs-lookup"><span data-stu-id="eeac1-157">The name of the gateway to regenerate key.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eeac1-158">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eeac1-158">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eeac1-159">Generieren Sie gatewayschlüssel erneut.</span><span class="sxs-lookup"><span data-stu-id="eeac1-159">Regenerate gateway key.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eeac1-160">Die regenerate Gateway Schlüsselvorgang-Antwort.</span><span class="sxs-lookup"><span data-stu-id="eeac1-160">The regenerate gateway key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveConnectionInfoAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt; RetrieveConnectionInfoAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt; RetrieveConnectionInfoAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.RetrieveConnectionInfoAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RetrieveConnectionInfoAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt;" Usage="iGatewayOperations.RetrieveConnectionInfoAsync (resourceGroupName, dataFactoryName, gatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eeac1-161">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eeac1-161">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eeac1-162">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="eeac1-162">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="eeac1-163">Der Name des Gateways.</span><span class="sxs-lookup"><span data-stu-id="eeac1-163">Name of the gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eeac1-164">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eeac1-164">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eeac1-165">Abgerufen Sie Gateway-Verbindungsinformationen werden.</span><span class="sxs-lookup"><span data-stu-id="eeac1-165">Retrieve gateway connection information.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eeac1-166">Abrufen Gateway Verbindung Informationen Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="eeac1-166">The retrieve gateway connection information operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; UpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; UpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.UpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="iGatewayOperations.UpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eeac1-167">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eeac1-167">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eeac1-168">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="eeac1-168">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eeac1-169">Die Parameter zum Erstellen oder Aktualisieren einer Data Factory-Gateway erforderlich.</span><span class="sxs-lookup"><span data-stu-id="eeac1-169">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eeac1-170">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eeac1-170">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eeac1-171">Aktualisieren einer Data Factory-Gateway.</span><span class="sxs-lookup"><span data-stu-id="eeac1-171">Update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eeac1-172">Erstellen oder aktualisieren Data Factory-Gateway Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="eeac1-172">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>