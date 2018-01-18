<Type Name="ComputeTypeOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ComputeTypeOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ComputeTypeOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ComputeTypeOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ComputeTypeOperationsExtensions = class" />
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
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete (this Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete(class Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, computeTypeName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.BeginDelete (operations, resourceGroupName, dataFactoryName, computeTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="computeTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="287c6-101">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="287c6-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="287c6-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-102">Required.</span></span> <span data-ttu-id="287c6-103">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="287c6-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-104">Required.</span></span> <span data-ttu-id="287c6-105">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-105">The name of the data factory.</span></span>
            </param>
        <param name="computeTypeName">
            <span data-ttu-id="287c6-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-106">Required.</span></span> <span data-ttu-id="287c6-107">Der Name des der ComputeType.</span><span class="sxs-lookup"><span data-stu-id="287c6-107">The name of the computeType.</span></span>
            </param>
        <summary>
            <span data-ttu-id="287c6-108">Löschen Sie eine ComputeType-Instanz.</span><span class="sxs-lookup"><span data-stu-id="287c6-108">Delete a ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="287c6-109">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="287c6-109">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeleteAsync (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, computeTypeName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, dataFactoryName, computeTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="computeTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="287c6-110">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="287c6-110">Reference to the Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="287c6-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-111">Required.</span></span> <span data-ttu-id="287c6-112">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="287c6-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-113">Required.</span></span> <span data-ttu-id="287c6-114">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-114">The name of the data factory.</span></span>
            </param>
        <param name="computeTypeName">
            <span data-ttu-id="287c6-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-115">Required.</span></span> <span data-ttu-id="287c6-116">Der Name des der ComputeType.</span><span class="sxs-lookup"><span data-stu-id="287c6-116">The name of the computeType.</span></span>
            </param>
        <summary>
            <span data-ttu-id="287c6-117">Löschen Sie eine ComputeType-Instanz.</span><span class="sxs-lookup"><span data-stu-id="287c6-117">Delete a ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="287c6-118">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="287c6-118">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ComputeTypeCreateOrUpdateParameters) As ComputeTypeCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="287c6-119">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="287c6-119">Reference to the Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="287c6-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-120">Required.</span></span> <span data-ttu-id="287c6-121">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="287c6-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-122">Required.</span></span> <span data-ttu-id="287c6-123">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-123">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="287c6-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-124">Required.</span></span> <span data-ttu-id="287c6-125">Die Parameter zum Erstellen oder aktualisieren die Definition eines ComputeType erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-125">The parameters required to create or update a ComputeType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="287c6-126">Erstellen Sie oder aktualisieren Sie einer ComputeType.</span><span class="sxs-lookup"><span data-stu-id="287c6-126">Create or update a ComputeType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="287c6-127">Erstellen oder aktualisieren ComputeType Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="287c6-127">The create or update ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ComputeTypeCreateOrUpdateParameters) As Task(Of ComputeTypeCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="287c6-128">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="287c6-128">Reference to the Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="287c6-129">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-129">Required.</span></span> <span data-ttu-id="287c6-130">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-130">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="287c6-131">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-131">Required.</span></span> <span data-ttu-id="287c6-132">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-132">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="287c6-133">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-133">Required.</span></span> <span data-ttu-id="287c6-134">Die Parameter zum Erstellen oder aktualisieren die Definition eines ComputeType erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-134">The parameters required to create or update a ComputeType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="287c6-135">Erstellen Sie oder aktualisieren Sie einer ComputeType.</span><span class="sxs-lookup"><span data-stu-id="287c6-135">Create or update a ComputeType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="287c6-136">Erstellen oder aktualisieren ComputeType Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="287c6-136">The create or update ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName, Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName, class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.CreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContent (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, computeTypeName As String, parameters As ComputeTypeCreateOrUpdateWithRawJsonContentParameters) As ComputeTypeCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.CreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, computeTypeName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="computeTypeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="287c6-137">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="287c6-137">Reference to the Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="287c6-138">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-138">Required.</span></span> <span data-ttu-id="287c6-139">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-139">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="287c6-140">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-140">Required.</span></span> <span data-ttu-id="287c6-141">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-141">The name of the data factory.</span></span>
            </param>
        <param name="computeTypeName">
            <span data-ttu-id="287c6-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-142">Required.</span></span> <span data-ttu-id="287c6-143">Ein ComputeType-Name.</span><span class="sxs-lookup"><span data-stu-id="287c6-143">A ComputeType name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="287c6-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-144">Required.</span></span> <span data-ttu-id="287c6-145">Die Parameter zum Erstellen oder aktualisieren die Definition eines ComputeType erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-145">The parameters required to create or update a ComputeType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="287c6-146">Erstellen Sie oder aktualisieren Sie einer ComputeType.</span><span class="sxs-lookup"><span data-stu-id="287c6-146">Create or update a ComputeType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="287c6-147">Erstellen oder aktualisieren ComputeType Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="287c6-147">The create or update ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName, Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName, class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContentAsync (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, computeTypeName As String, parameters As ComputeTypeCreateOrUpdateWithRawJsonContentParameters) As Task(Of ComputeTypeCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, computeTypeName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="computeTypeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="287c6-148">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="287c6-148">Reference to the Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="287c6-149">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-149">Required.</span></span> <span data-ttu-id="287c6-150">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-150">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="287c6-151">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-151">Required.</span></span> <span data-ttu-id="287c6-152">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-152">The name of the data factory.</span></span>
            </param>
        <param name="computeTypeName">
            <span data-ttu-id="287c6-153">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-153">Required.</span></span> <span data-ttu-id="287c6-154">Ein ComputeType-Name.</span><span class="sxs-lookup"><span data-stu-id="287c6-154">A ComputeType name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="287c6-155">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-155">Required.</span></span> <span data-ttu-id="287c6-156">Die Parameter zum Erstellen oder aktualisieren die Definition eines ComputeType erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-156">The parameters required to create or update a ComputeType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="287c6-157">Erstellen Sie oder aktualisieren Sie einer ComputeType.</span><span class="sxs-lookup"><span data-stu-id="287c6-157">Create or update a ComputeType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="287c6-158">Erstellen oder aktualisieren ComputeType Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="287c6-158">The create or update ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, computeTypeName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName, computeTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="computeTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="287c6-159">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="287c6-159">Reference to the Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="287c6-160">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-160">Required.</span></span> <span data-ttu-id="287c6-161">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-161">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="287c6-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-162">Required.</span></span> <span data-ttu-id="287c6-163">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-163">The name of the data factory.</span></span>
            </param>
        <param name="computeTypeName">
            <span data-ttu-id="287c6-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-164">Required.</span></span> <span data-ttu-id="287c6-165">Der Name des der ComputeType.</span><span class="sxs-lookup"><span data-stu-id="287c6-165">The name of the computeType.</span></span>
            </param>
        <summary>
            <span data-ttu-id="287c6-166">Löschen Sie eine ComputeType-Instanz.</span><span class="sxs-lookup"><span data-stu-id="287c6-166">Delete a ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="287c6-167">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="287c6-167">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, computeTypeName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName, computeTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="computeTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="287c6-168">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="287c6-168">Reference to the Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="287c6-169">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-169">Required.</span></span> <span data-ttu-id="287c6-170">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-170">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="287c6-171">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-171">Required.</span></span> <span data-ttu-id="287c6-172">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-172">The name of the data factory.</span></span>
            </param>
        <param name="computeTypeName">
            <span data-ttu-id="287c6-173">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-173">Required.</span></span> <span data-ttu-id="287c6-174">Der Name des der ComputeType.</span><span class="sxs-lookup"><span data-stu-id="287c6-174">The name of the computeType.</span></span>
            </param>
        <summary>
            <span data-ttu-id="287c6-175">Löschen Sie eine ComputeType-Instanz.</span><span class="sxs-lookup"><span data-stu-id="287c6-175">Delete a ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="287c6-176">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="287c6-176">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetResponse Get (this Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetResponse Get(class Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ComputeTypeGetParameters) As ComputeTypeGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="287c6-177">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="287c6-177">Reference to the Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="287c6-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-178">Required.</span></span> <span data-ttu-id="287c6-179">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-179">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="287c6-180">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-180">Required.</span></span> <span data-ttu-id="287c6-181">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-181">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="287c6-182">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-182">Required.</span></span> <span data-ttu-id="287c6-183">Parameter, die angibt, wie eine Definition ComputeType abrufen.</span><span class="sxs-lookup"><span data-stu-id="287c6-183">Parameters specifying how to get a ComputeType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="287c6-184">Ruft eine ComputeType-Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="287c6-184">Gets a ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="287c6-185">Vorgangsantwort ComputeType abrufen.</span><span class="sxs-lookup"><span data-stu-id="287c6-185">The Get ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ComputeTypeGetParameters) As Task(Of ComputeTypeGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeGetParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="287c6-186">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="287c6-186">Reference to the Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="287c6-187">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-187">Required.</span></span> <span data-ttu-id="287c6-188">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-188">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="287c6-189">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-189">Required.</span></span> <span data-ttu-id="287c6-190">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-190">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="287c6-191">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-191">Required.</span></span> <span data-ttu-id="287c6-192">Parameter, die angibt, wie eine Definition ComputeType abrufen.</span><span class="sxs-lookup"><span data-stu-id="287c6-192">Parameters specifying how to get a ComputeType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="287c6-193">Ruft eine ComputeType-Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="287c6-193">Gets a ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="287c6-194">Vorgangsantwort ComputeType abrufen.</span><span class="sxs-lookup"><span data-stu-id="287c6-194">The Get ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse List (this Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse List(class Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ComputeTypeListParameters) As ComputeTypeListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.List (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="287c6-195">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="287c6-195">Reference to the Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="287c6-196">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-196">Required.</span></span> <span data-ttu-id="287c6-197">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-197">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="287c6-198">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-198">Required.</span></span> <span data-ttu-id="287c6-199">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-199">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="287c6-200">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-200">Required.</span></span> <span data-ttu-id="287c6-201">Parameter, die angibt, wie eine Liste der ComputeType Definitionen für eine Auflistungsvorgang zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="287c6-201">Parameters specifying how to return a list of ComputeType definitions for a List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="287c6-202">Ruft eine ComputeType-Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="287c6-202">Gets a ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="287c6-203">Die Liste ComputeType Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="287c6-203">The List ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ComputeTypeListParameters) As Task(Of ComputeTypeListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="287c6-204">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="287c6-204">Reference to the Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="287c6-205">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-205">Required.</span></span> <span data-ttu-id="287c6-206">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-206">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="287c6-207">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-207">Required.</span></span> <span data-ttu-id="287c6-208">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="287c6-208">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="287c6-209">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-209">Required.</span></span> <span data-ttu-id="287c6-210">Parameter, die angibt, wie eine Liste der ComputeType Definitionen für eine Auflistungsvorgang zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="287c6-210">Parameters specifying how to return a list of ComputeType definitions for a List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="287c6-211">Ruft eine ComputeType-Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="287c6-211">Gets a ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="287c6-212">Die Liste ComputeType Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="287c6-212">The List ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse ListNext (this Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse ListNext(class Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IComputeTypeOperations, nextLink As String) As ComputeTypeListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="287c6-213">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="287c6-213">Reference to the Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="287c6-214">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-214">Required.</span></span> <span data-ttu-id="287c6-215">Die Url zur nächsten Seite ComputeTypes.</span><span class="sxs-lookup"><span data-stu-id="287c6-215">The url to the next ComputeTypes page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="287c6-216">Ruft die nächste Seite der ComputeType Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="287c6-216">Gets the next page of ComputeType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="287c6-217">Die Liste ComputeType Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="287c6-217">The List ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IComputeTypeOperations, nextLink As String) As Task(Of ComputeTypeListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.ComputeTypeOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="287c6-218">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="287c6-218">Reference to the Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="287c6-219">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="287c6-219">Required.</span></span> <span data-ttu-id="287c6-220">Die Url zur nächsten Seite ComputeTypes.</span><span class="sxs-lookup"><span data-stu-id="287c6-220">The url to the next ComputeTypes page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="287c6-221">Ruft die nächste Seite der ComputeType Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="287c6-221">Gets the next page of ComputeType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="287c6-222">Die Liste ComputeType Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="287c6-222">The List ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>