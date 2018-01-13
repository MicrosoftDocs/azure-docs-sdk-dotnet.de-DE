<Type Name="GatewayOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class GatewayOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit GatewayOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module GatewayOperationsExtensions" />
  <TypeSignature Language="F#" Value="type GatewayOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse BeginCreateOrUpdate (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse BeginCreateOrUpdate(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As GatewayCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-101">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-102">Required.</span></span> <span data-ttu-id="0e51e-103">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-104">Required.</span></span> <span data-ttu-id="0e51e-105">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-105">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0e51e-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-106">Required.</span></span> <span data-ttu-id="0e51e-107">Die Parameter zum Erstellen oder Aktualisieren einer Data Factory-Gateway erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-107">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-108">Erstellen Sie oder aktualisieren Sie einer Data Factory-Gateway.</span><span class="sxs-lookup"><span data-stu-id="0e51e-108">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-109">Erstellen oder aktualisieren Data Factory-Gateway Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-109">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As Task(Of GatewayCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-110">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-110">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-111">Required.</span></span> <span data-ttu-id="0e51e-112">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-113">Required.</span></span> <span data-ttu-id="0e51e-114">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-114">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0e51e-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-115">Required.</span></span> <span data-ttu-id="0e51e-116">Die Parameter zum Erstellen oder Aktualisieren einer Data Factory-Gateway erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-116">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-117">Erstellen Sie oder aktualisieren Sie einer Data Factory-Gateway.</span><span class="sxs-lookup"><span data-stu-id="0e51e-117">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-118">Erstellen oder aktualisieren Data Factory-Gateway Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-118">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.BeginDelete (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-119">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-119">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-120">Required.</span></span> <span data-ttu-id="0e51e-121">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-122">Required.</span></span> <span data-ttu-id="0e51e-123">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-123">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="0e51e-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-124">Required.</span></span> <span data-ttu-id="0e51e-125">Der Name des Gateways zu löschen.</span><span class="sxs-lookup"><span data-stu-id="0e51e-125">Name of the gateway to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-126">Löschen Sie ein Data Factory-Gateway.</span><span class="sxs-lookup"><span data-stu-id="0e51e-126">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-127">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="0e51e-127">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeleteAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-128">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-128">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-129">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-129">Required.</span></span> <span data-ttu-id="0e51e-130">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-130">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-131">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-131">Required.</span></span> <span data-ttu-id="0e51e-132">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-132">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="0e51e-133">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-133">Required.</span></span> <span data-ttu-id="0e51e-134">Der Name des Gateways zu löschen.</span><span class="sxs-lookup"><span data-stu-id="0e51e-134">Name of the gateway to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-135">Löschen Sie ein Data Factory-Gateway.</span><span class="sxs-lookup"><span data-stu-id="0e51e-135">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-136">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="0e51e-136">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As GatewayCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-137">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-137">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-138">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-138">Required.</span></span> <span data-ttu-id="0e51e-139">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-139">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-140">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-140">Required.</span></span> <span data-ttu-id="0e51e-141">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-141">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0e51e-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-142">Required.</span></span> <span data-ttu-id="0e51e-143">Die Parameter zum Erstellen oder Aktualisieren einer Data Factory-Gateway erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-143">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-144">Erstellen Sie oder aktualisieren Sie einer Data Factory-Gateway.</span><span class="sxs-lookup"><span data-stu-id="0e51e-144">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-145">Erstellen oder aktualisieren Data Factory-Gateway Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-145">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As Task(Of GatewayCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-146">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-146">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-147">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-147">Required.</span></span> <span data-ttu-id="0e51e-148">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-148">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-149">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-149">Required.</span></span> <span data-ttu-id="0e51e-150">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-150">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0e51e-151">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-151">Required.</span></span> <span data-ttu-id="0e51e-152">Die Parameter zum Erstellen oder Aktualisieren einer Data Factory-Gateway erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-152">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-153">Erstellen Sie oder aktualisieren Sie einer Data Factory-Gateway.</span><span class="sxs-lookup"><span data-stu-id="0e51e-153">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-154">Erstellen oder aktualisieren Data Factory-Gateway Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-154">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-155">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-155">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-156">Required.</span></span> <span data-ttu-id="0e51e-157">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-157">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-158">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-158">Required.</span></span> <span data-ttu-id="0e51e-159">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-159">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="0e51e-160">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-160">Required.</span></span> <span data-ttu-id="0e51e-161">Der Name des Gateways zu löschen.</span><span class="sxs-lookup"><span data-stu-id="0e51e-161">Name of the gateway to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-162">Löschen Sie ein Data Factory-Gateway.</span><span class="sxs-lookup"><span data-stu-id="0e51e-162">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-163">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="0e51e-163">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-164">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-164">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-165">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-165">Required.</span></span> <span data-ttu-id="0e51e-166">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-166">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-167">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-167">Required.</span></span> <span data-ttu-id="0e51e-168">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-168">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="0e51e-169">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-169">Required.</span></span> <span data-ttu-id="0e51e-170">Der Name des Gateways zu löschen.</span><span class="sxs-lookup"><span data-stu-id="0e51e-170">Name of the gateway to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-171">Löschen Sie ein Data Factory-Gateway.</span><span class="sxs-lookup"><span data-stu-id="0e51e-171">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-172">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="0e51e-172">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse Get (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse Get(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As GatewayGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-173">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-173">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-174">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-174">Required.</span></span> <span data-ttu-id="0e51e-175">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-175">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-176">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-176">Required.</span></span> <span data-ttu-id="0e51e-177">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-177">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="0e51e-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-178">Required.</span></span> <span data-ttu-id="0e51e-179">Der Name des Gateways zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="0e51e-179">Name of the gateway to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-180">Ruft ein Data Factory-Gateway ab.</span><span class="sxs-lookup"><span data-stu-id="0e51e-180">Gets a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-181">Get Data Factory-Gateway Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-181">The Get data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of GatewayGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-182">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-182">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-183">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-183">Required.</span></span> <span data-ttu-id="0e51e-184">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-184">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-185">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-185">Required.</span></span> <span data-ttu-id="0e51e-186">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-186">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="0e51e-187">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-187">Required.</span></span> <span data-ttu-id="0e51e-188">Der Name des Gateways zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="0e51e-188">Name of the gateway to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-189">Ruft ein Data Factory-Gateway ab.</span><span class="sxs-lookup"><span data-stu-id="0e51e-189">Gets a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-190">Get Data Factory-Gateway Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-190">The Get data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse GetCreateOrUpdateStatus (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse GetCreateOrUpdateStatus(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.GetCreateOrUpdateStatus(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatus (operations As IGatewayOperations, operationStatusLink As String) As GatewayCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatus : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.GetCreateOrUpdateStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-191">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-191">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="0e51e-192">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-192">Required.</span></span> <span data-ttu-id="0e51e-193">Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="0e51e-193">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-194">Der Vorgang Get Operation Status Gibt den Status des angegebenen Vorgangs zurück.</span><span class="sxs-lookup"><span data-stu-id="0e51e-194">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="0e51e-195">Nach dem Aufrufen eines asynchronen Vorgangs, können Sie aufrufen Vorgangsstatus abrufen, um festzustellen, ob der Vorgang erfolgreich war, fehlgeschlagen ist, oder ist noch nicht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0e51e-195">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-196">Erstellen oder aktualisieren Data Factory-Gateway Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-196">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.GetCreateOrUpdateStatusAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatusAsync (operations As IGatewayOperations, operationStatusLink As String) As Task(Of GatewayCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatusAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.GetCreateOrUpdateStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-197">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-197">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="0e51e-198">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-198">Required.</span></span> <span data-ttu-id="0e51e-199">Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="0e51e-199">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-200">Der Vorgang Get Operation Status Gibt den Status des angegebenen Vorgangs zurück.</span><span class="sxs-lookup"><span data-stu-id="0e51e-200">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="0e51e-201">Nach dem Aufrufen eines asynchronen Vorgangs, können Sie aufrufen Vorgangsstatus abrufen, um festzustellen, ob der Vorgang erfolgreich war, fehlgeschlagen ist, oder ist noch nicht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0e51e-201">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-202">Erstellen oder aktualisieren Data Factory-Gateway Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-202">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse List (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse List(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String) As GatewayListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.List (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-203">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-203">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-204">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-204">Required.</span></span> <span data-ttu-id="0e51e-205">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-205">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-206">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-206">Required.</span></span> <span data-ttu-id="0e51e-207">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-207">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-208">Listen Sie aller Gateways unter einer Data Factory an auf.</span><span class="sxs-lookup"><span data-stu-id="0e51e-208">List all gateways under a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-209">Liste Data Factory-Gateways Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-209">The List data factory gateways operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String) As Task(Of GatewayListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-210">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-210">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-211">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-211">Required.</span></span> <span data-ttu-id="0e51e-212">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-212">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-213">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-213">Required.</span></span> <span data-ttu-id="0e51e-214">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-214">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-215">Listen Sie aller Gateways unter einer Data Factory an auf.</span><span class="sxs-lookup"><span data-stu-id="0e51e-215">List all gateways under a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-216">Liste Data Factory-Gateways Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-216">The List data factory gateways operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse ListAuthKeys (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse ListAuthKeys(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.ListAuthKeys(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthKeys (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As GatewayListAuthKeysResponse" />
      <MemberSignature Language="F#" Value="static member ListAuthKeys : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.ListAuthKeys (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-217">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-217">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-218">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-218">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-219">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-219">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="0e51e-220">Der Name des Gateways auf Liste Auth-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="0e51e-220">The name of the gateway to list auth keys.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-221">Liste Auth-Schlüssel des Gateways.</span><span class="sxs-lookup"><span data-stu-id="0e51e-221">List auth keys of the gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-222">Liste Data Factory-Gateway Auth Schlüssel Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-222">The List data factory gateway auth keys operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt; ListAuthKeysAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt; ListAuthKeysAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.ListAuthKeysAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthKeysAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of GatewayListAuthKeysResponse)" />
      <MemberSignature Language="F#" Value="static member ListAuthKeysAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.ListAuthKeysAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-223">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-223">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-224">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-224">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-225">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-225">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="0e51e-226">Der Name des Gateways auf Liste Auth-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="0e51e-226">The name of the gateway to list auth keys.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-227">Liste Auth-Schlüssel des Gateways.</span><span class="sxs-lookup"><span data-stu-id="0e51e-227">List auth keys of the gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-228">Liste Data Factory-Gateway Auth Schlüssel Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-228">The List data factory gateway auth keys operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateAuthKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse RegenerateAuthKey (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName, Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse RegenerateAuthKey(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName, class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RegenerateAuthKey(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateAuthKey (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String, parameters As GatewayRegenerateAuthKeyParameters) As GatewayRegenerateAuthKeyResponse" />
      <MemberSignature Language="F#" Value="static member RegenerateAuthKey : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RegenerateAuthKey (operations, resourceGroupName, dataFactoryName, gatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-229">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-229">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-230">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-230">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-231">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-231">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="0e51e-232">Der Name des Gateways auf Auth-Schlüssel erneut generieren.</span><span class="sxs-lookup"><span data-stu-id="0e51e-232">The name of the gateway to regenerate auth key.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0e51e-233">Der Name des Gateway-Auth-Schlüssels neu generiert werden.</span><span class="sxs-lookup"><span data-stu-id="0e51e-233">Name of the gateway auth key to be regenerated.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-234">Generieren Sie Gateway-Auth-Schlüssel erneut.</span><span class="sxs-lookup"><span data-stu-id="0e51e-234">Regenerate gateway auth key.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-235">Regenerate Gateway Authentication Key Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-235">The regenerate gateway auth key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateAuthKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt; RegenerateAuthKeyAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName, Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt; RegenerateAuthKeyAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName, class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RegenerateAuthKeyAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateAuthKeyAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String, parameters As GatewayRegenerateAuthKeyParameters) As Task(Of GatewayRegenerateAuthKeyResponse)" />
      <MemberSignature Language="F#" Value="static member RegenerateAuthKeyAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RegenerateAuthKeyAsync (operations, resourceGroupName, dataFactoryName, gatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-236">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-236">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-237">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-237">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-238">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-238">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="0e51e-239">Der Name des Gateways auf Auth-Schlüssel erneut generieren.</span><span class="sxs-lookup"><span data-stu-id="0e51e-239">The name of the gateway to regenerate auth key.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0e51e-240">Der Name des Gateway-Auth-Schlüssels neu generiert werden.</span><span class="sxs-lookup"><span data-stu-id="0e51e-240">Name of the gateway auth key to be regenerated.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-241">Generieren Sie Gateway-Auth-Schlüssel erneut.</span><span class="sxs-lookup"><span data-stu-id="0e51e-241">Regenerate gateway auth key.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-242">Regenerate Gateway Authentication Key Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-242">The regenerate gateway auth key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse RegenerateKey (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse RegenerateKey(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RegenerateKey(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKey (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As GatewayRegenerateKeyResponse" />
      <MemberSignature Language="F#" Value="static member RegenerateKey : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RegenerateKey (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-243">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-243">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-244">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-244">Required.</span></span> <span data-ttu-id="0e51e-245">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-245">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-246">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-246">Required.</span></span> <span data-ttu-id="0e51e-247">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-247">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="0e51e-248">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-248">Required.</span></span> <span data-ttu-id="0e51e-249">Der Name des Gateways auf Schlüssel erneut generieren.</span><span class="sxs-lookup"><span data-stu-id="0e51e-249">The name of the gateway to regenerate key.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-250">Generieren Sie gatewayschlüssel erneut.</span><span class="sxs-lookup"><span data-stu-id="0e51e-250">Regenerate gateway key.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-251">Die regenerate Gateway Schlüsselvorgang-Antwort.</span><span class="sxs-lookup"><span data-stu-id="0e51e-251">The regenerate gateway key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKeyAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of GatewayRegenerateKeyResponse)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-252">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-252">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-253">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-253">Required.</span></span> <span data-ttu-id="0e51e-254">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-254">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-255">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-255">Required.</span></span> <span data-ttu-id="0e51e-256">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-256">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="0e51e-257">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-257">Required.</span></span> <span data-ttu-id="0e51e-258">Der Name des Gateways auf Schlüssel erneut generieren.</span><span class="sxs-lookup"><span data-stu-id="0e51e-258">The name of the gateway to regenerate key.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-259">Generieren Sie gatewayschlüssel erneut.</span><span class="sxs-lookup"><span data-stu-id="0e51e-259">Regenerate gateway key.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-260">Die regenerate Gateway Schlüsselvorgang-Antwort.</span><span class="sxs-lookup"><span data-stu-id="0e51e-260">The regenerate gateway key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveConnectionInfo">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse RetrieveConnectionInfo (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse RetrieveConnectionInfo(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RetrieveConnectionInfo(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RetrieveConnectionInfo (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As GatewayConnectionInfoRetrieveResponse" />
      <MemberSignature Language="F#" Value="static member RetrieveConnectionInfo : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RetrieveConnectionInfo (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-261">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-261">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-262">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-262">Required.</span></span> <span data-ttu-id="0e51e-263">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-263">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-264">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-264">Required.</span></span> <span data-ttu-id="0e51e-265">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-265">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="0e51e-266">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-266">Required.</span></span> <span data-ttu-id="0e51e-267">Der Name des Gateways.</span><span class="sxs-lookup"><span data-stu-id="0e51e-267">Name of the gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-268">Abgerufen Sie Gateway-Verbindungsinformationen werden.</span><span class="sxs-lookup"><span data-stu-id="0e51e-268">Retrieve gateway connection information.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-269">Abrufen Gateway Verbindung Informationen Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-269">The retrieve gateway connection information operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveConnectionInfoAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt; RetrieveConnectionInfoAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt; RetrieveConnectionInfoAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RetrieveConnectionInfoAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RetrieveConnectionInfoAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of GatewayConnectionInfoRetrieveResponse)" />
      <MemberSignature Language="F#" Value="static member RetrieveConnectionInfoAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RetrieveConnectionInfoAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-270">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-270">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-271">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-271">Required.</span></span> <span data-ttu-id="0e51e-272">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-272">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-273">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-273">Required.</span></span> <span data-ttu-id="0e51e-274">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-274">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="0e51e-275">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-275">Required.</span></span> <span data-ttu-id="0e51e-276">Der Name des Gateways.</span><span class="sxs-lookup"><span data-stu-id="0e51e-276">Name of the gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-277">Abgerufen Sie Gateway-Verbindungsinformationen werden.</span><span class="sxs-lookup"><span data-stu-id="0e51e-277">Retrieve gateway connection information.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-278">Abrufen Gateway Verbindung Informationen Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-278">The retrieve gateway connection information operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse Update (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse Update(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.Update(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As GatewayCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.Update (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-279">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-279">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-280">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-280">Required.</span></span> <span data-ttu-id="0e51e-281">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-281">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-282">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-282">Required.</span></span> <span data-ttu-id="0e51e-283">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-283">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0e51e-284">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-284">Required.</span></span> <span data-ttu-id="0e51e-285">Die Parameter zum Erstellen oder Aktualisieren einer Data Factory-Gateway erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-285">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-286">Aktualisieren einer Data Factory-Gateway.</span><span class="sxs-lookup"><span data-stu-id="0e51e-286">Update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-287">Erstellen oder aktualisieren Data Factory-Gateway Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-287">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; UpdateAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; UpdateAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As Task(Of GatewayCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.UpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0e51e-288">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span><span class="sxs-lookup"><span data-stu-id="0e51e-288">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0e51e-289">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-289">Required.</span></span> <span data-ttu-id="0e51e-290">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="0e51e-290">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0e51e-291">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-291">Required.</span></span> <span data-ttu-id="0e51e-292">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="0e51e-292">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0e51e-293">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-293">Required.</span></span> <span data-ttu-id="0e51e-294">Die Parameter zum Erstellen oder Aktualisieren einer Data Factory-Gateway erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0e51e-294">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0e51e-295">Aktualisieren einer Data Factory-Gateway.</span><span class="sxs-lookup"><span data-stu-id="0e51e-295">Update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0e51e-296">Erstellen oder aktualisieren Data Factory-Gateway Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0e51e-296">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>