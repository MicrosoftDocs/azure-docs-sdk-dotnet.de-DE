<Type Name="IComputeTypeOperations" FullName="Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations">
  <TypeSignature Language="C#" Value="public interface IComputeTypeOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IComputeTypeOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IComputeTypeOperations" />
  <TypeSignature Language="F#" Value="type IComputeTypeOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="eb2e1-101">Vorgänge zum Verwalten von Data Factory ComputeTypes.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-101">Operations for managing data factory ComputeTypes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string computeTypeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string computeTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iComputeTypeOperations.BeginDeleteAsync (resourceGroupName, dataFactoryName, computeTypeName, cancellationToken)" />
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
        <Parameter Name="computeTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eb2e1-102">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eb2e1-103">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-103">The name of the data factory.</span></span>
            </param>
        <param name="computeTypeName">
            <span data-ttu-id="eb2e1-104">Der Name des der ComputeType.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-104">The name of the computeType.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb2e1-105">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb2e1-106">Löschen Sie eine ComputeType-Instanz.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-106">Delete a ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb2e1-107">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-107">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt;" Usage="iComputeTypeOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eb2e1-108">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-108">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eb2e1-109">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-109">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eb2e1-110">Die Parameter zum Erstellen oder aktualisieren die Definition eines ComputeType erforderlich.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-110">The parameters required to create or update a ComputeType definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb2e1-111">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-111">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb2e1-112">Erstellen Sie oder aktualisieren Sie einer ComputeType.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-112">Create or update a ComputeType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb2e1-113">Erstellen oder aktualisieren ComputeType Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-113">The create or update ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string computeTypeName, Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string computeTypeName, class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt;" Usage="iComputeTypeOperations.CreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, computeTypeName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="computeTypeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eb2e1-114">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-114">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eb2e1-115">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-115">The name of the data factory.</span></span>
            </param>
        <param name="computeTypeName">
            <span data-ttu-id="eb2e1-116">Ein ComputeType-Name.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-116">A ComputeType name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eb2e1-117">Die Parameter zum Erstellen oder aktualisieren die Definition eines ComputeType erforderlich.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-117">The parameters required to create or update a ComputeType definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb2e1-118">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb2e1-119">Erstellen Sie oder aktualisieren Sie einer ComputeType.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-119">Create or update a ComputeType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb2e1-120">Erstellen oder aktualisieren ComputeType Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-120">The create or update ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string computeTypeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string computeTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iComputeTypeOperations.DeleteAsync (resourceGroupName, dataFactoryName, computeTypeName, cancellationToken)" />
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
        <Parameter Name="computeTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eb2e1-121">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eb2e1-122">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-122">The name of the data factory.</span></span>
            </param>
        <param name="computeTypeName">
            <span data-ttu-id="eb2e1-123">Der Name des der ComputeType.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-123">The name of the computeType.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb2e1-124">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb2e1-125">Löschen Sie eine ComputeType-Instanz.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-125">Delete a ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb2e1-126">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-126">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.GetAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetResponse&gt;" Usage="iComputeTypeOperations.GetAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eb2e1-127">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-127">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eb2e1-128">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-128">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eb2e1-129">Parameter, die angibt, wie eine Definition ComputeType abrufen.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-129">Parameters specifying how to get a ComputeType definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb2e1-130">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-130">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb2e1-131">Ruft eine ComputeType-Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-131">Gets a ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb2e1-132">Vorgangsantwort ComputeType abrufen.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-132">The Get ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse&gt;" Usage="iComputeTypeOperations.ListAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eb2e1-133">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-133">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="eb2e1-134">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-134">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eb2e1-135">Parameter, die angibt, wie eine Liste der ComputeType Definitionen für eine Auflistungsvorgang zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-135">Parameters specifying how to return a list of ComputeType definitions for a List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb2e1-136">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-136">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb2e1-137">Ruft eine ComputeType-Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-137">Gets a ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb2e1-138">Die Liste ComputeType Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-138">The List ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse&gt;" Usage="iComputeTypeOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="eb2e1-139">Die Url zur nächsten Seite ComputeTypes.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-139">The url to the next ComputeTypes page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb2e1-140">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-140">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb2e1-141">Ruft die nächste Seite der ComputeType Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-141">Gets the next page of ComputeType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb2e1-142">Die Liste ComputeType Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="eb2e1-142">The List ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>