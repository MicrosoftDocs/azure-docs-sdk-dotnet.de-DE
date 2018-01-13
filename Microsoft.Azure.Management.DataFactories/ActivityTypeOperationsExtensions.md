<Type Name="ActivityTypeOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ActivityTypeOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActivityTypeOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ActivityTypeOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ActivityTypeOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, activityTypeName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.BeginDelete (operations, resourceGroupName, dataFactoryName, activityTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c899-101">Verweis auf die Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="2c899-101">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c899-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-102">Required.</span></span> <span data-ttu-id="2c899-103">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="2c899-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-104">Required.</span></span> <span data-ttu-id="2c899-105">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-105">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="2c899-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-106">Required.</span></span> <span data-ttu-id="2c899-107">Der Name des der ActivityType.</span><span class="sxs-lookup"><span data-stu-id="2c899-107">The name of the activityType.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c899-108">Löschen einer ActivityType-Instanz.</span><span class="sxs-lookup"><span data-stu-id="2c899-108">Delete an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c899-109">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="2c899-109">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeleteAsync (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, activityTypeName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, dataFactoryName, activityTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c899-110">Verweis auf die Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="2c899-110">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c899-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-111">Required.</span></span> <span data-ttu-id="2c899-112">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="2c899-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-113">Required.</span></span> <span data-ttu-id="2c899-114">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-114">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="2c899-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-115">Required.</span></span> <span data-ttu-id="2c899-116">Der Name des der ActivityType.</span><span class="sxs-lookup"><span data-stu-id="2c899-116">The name of the activityType.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c899-117">Löschen einer ActivityType-Instanz.</span><span class="sxs-lookup"><span data-stu-id="2c899-117">Delete an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c899-118">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="2c899-118">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ActivityTypeCreateOrUpdateParameters) As ActivityTypeCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c899-119">Verweis auf die Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="2c899-119">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c899-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-120">Required.</span></span> <span data-ttu-id="2c899-121">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="2c899-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-122">Required.</span></span> <span data-ttu-id="2c899-123">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-123">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c899-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-124">Required.</span></span> <span data-ttu-id="2c899-125">Die Parameter zum Erstellen oder Aktualisieren einer ActivityType-Definition erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-125">The parameters required to create or update an ActivityType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c899-126">Erstellen Sie oder aktualisieren Sie einer ActivityType.</span><span class="sxs-lookup"><span data-stu-id="2c899-126">Create or update an ActivityType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c899-127">Erstellen oder aktualisieren ActivityType Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2c899-127">The create or update ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ActivityTypeCreateOrUpdateParameters) As Task(Of ActivityTypeCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c899-128">Verweis auf die Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="2c899-128">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c899-129">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-129">Required.</span></span> <span data-ttu-id="2c899-130">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-130">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="2c899-131">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-131">Required.</span></span> <span data-ttu-id="2c899-132">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-132">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c899-133">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-133">Required.</span></span> <span data-ttu-id="2c899-134">Die Parameter zum Erstellen oder Aktualisieren einer ActivityType-Definition erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-134">The parameters required to create or update an ActivityType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c899-135">Erstellen Sie oder aktualisieren Sie einer ActivityType.</span><span class="sxs-lookup"><span data-stu-id="2c899-135">Create or update an ActivityType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c899-136">Erstellen oder aktualisieren ActivityType Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2c899-136">The create or update ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.CreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContent (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, activityTypeName As String, parameters As ActivityTypeCreateOrUpdateWithRawJsonContentParameters) As ActivityTypeCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.CreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, activityTypeName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c899-137">Verweis auf die Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="2c899-137">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c899-138">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-138">Required.</span></span> <span data-ttu-id="2c899-139">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-139">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="2c899-140">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-140">Required.</span></span> <span data-ttu-id="2c899-141">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-141">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="2c899-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-142">Required.</span></span> <span data-ttu-id="2c899-143">Der Name einer ActivityType.</span><span class="sxs-lookup"><span data-stu-id="2c899-143">An ActivityType name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c899-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-144">Required.</span></span> <span data-ttu-id="2c899-145">Die Parameter zum Erstellen oder Aktualisieren einer ActivityType-Definition erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-145">The parameters required to create or update an ActivityType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c899-146">Erstellen Sie oder aktualisieren Sie einer ActivityType.</span><span class="sxs-lookup"><span data-stu-id="2c899-146">Create or update an ActivityType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c899-147">Erstellen oder aktualisieren ActivityType Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2c899-147">The create or update ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContentAsync (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, activityTypeName As String, parameters As ActivityTypeCreateOrUpdateWithRawJsonContentParameters) As Task(Of ActivityTypeCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, activityTypeName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c899-148">Verweis auf die Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="2c899-148">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c899-149">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-149">Required.</span></span> <span data-ttu-id="2c899-150">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-150">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="2c899-151">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-151">Required.</span></span> <span data-ttu-id="2c899-152">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-152">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="2c899-153">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-153">Required.</span></span> <span data-ttu-id="2c899-154">Der Name einer ActivityType.</span><span class="sxs-lookup"><span data-stu-id="2c899-154">An ActivityType name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c899-155">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-155">Required.</span></span> <span data-ttu-id="2c899-156">Die Parameter zum Erstellen oder Aktualisieren einer ActivityType-Definition erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-156">The parameters required to create or update an ActivityType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c899-157">Erstellen Sie oder aktualisieren Sie einer ActivityType.</span><span class="sxs-lookup"><span data-stu-id="2c899-157">Create or update an ActivityType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c899-158">Erstellen oder aktualisieren ActivityType Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2c899-158">The create or update ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, activityTypeName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName, activityTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c899-159">Verweis auf die Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="2c899-159">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c899-160">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-160">Required.</span></span> <span data-ttu-id="2c899-161">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-161">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="2c899-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-162">Required.</span></span> <span data-ttu-id="2c899-163">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-163">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="2c899-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-164">Required.</span></span> <span data-ttu-id="2c899-165">Der Name des der ActivityType.</span><span class="sxs-lookup"><span data-stu-id="2c899-165">The name of the activityType.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c899-166">Löschen einer ActivityType-Instanz.</span><span class="sxs-lookup"><span data-stu-id="2c899-166">Delete an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c899-167">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="2c899-167">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, activityTypeName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName, activityTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c899-168">Verweis auf die Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="2c899-168">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c899-169">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-169">Required.</span></span> <span data-ttu-id="2c899-170">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-170">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="2c899-171">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-171">Required.</span></span> <span data-ttu-id="2c899-172">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-172">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="2c899-173">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-173">Required.</span></span> <span data-ttu-id="2c899-174">Der Name des der ActivityType.</span><span class="sxs-lookup"><span data-stu-id="2c899-174">The name of the activityType.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c899-175">Löschen einer ActivityType-Instanz.</span><span class="sxs-lookup"><span data-stu-id="2c899-175">Delete an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c899-176">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="2c899-176">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse Get (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse Get(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ActivityTypeGetParameters) As ActivityTypeGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters -&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c899-177">Verweis auf die Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="2c899-177">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c899-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-178">Required.</span></span> <span data-ttu-id="2c899-179">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-179">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="2c899-180">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-180">Required.</span></span> <span data-ttu-id="2c899-181">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-181">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c899-182">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-182">Required.</span></span> <span data-ttu-id="2c899-183">Parameter, die zum Abrufen einer ActivityType-Definition angibt.</span><span class="sxs-lookup"><span data-stu-id="2c899-183">Parameters specifying how to get an ActivityType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c899-184">Ruft eine ActivityType-Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="2c899-184">Gets an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c899-185">Die ActivityType Get Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="2c899-185">The Get ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ActivityTypeGetParameters) As Task(Of ActivityTypeGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c899-186">Verweis auf die Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="2c899-186">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c899-187">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-187">Required.</span></span> <span data-ttu-id="2c899-188">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-188">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="2c899-189">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-189">Required.</span></span> <span data-ttu-id="2c899-190">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-190">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c899-191">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-191">Required.</span></span> <span data-ttu-id="2c899-192">Parameter, die zum Abrufen einer ActivityType-Definition angibt.</span><span class="sxs-lookup"><span data-stu-id="2c899-192">Parameters specifying how to get an ActivityType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c899-193">Ruft eine ActivityType-Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="2c899-193">Gets an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c899-194">Die ActivityType Get Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="2c899-194">The Get ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse List (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse List(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ActivityTypeListParameters) As ActivityTypeListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters -&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.List (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c899-195">Verweis auf die Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="2c899-195">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c899-196">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-196">Required.</span></span> <span data-ttu-id="2c899-197">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-197">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="2c899-198">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-198">Required.</span></span> <span data-ttu-id="2c899-199">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-199">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c899-200">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-200">Required.</span></span> <span data-ttu-id="2c899-201">Parameter, die angibt, wie eine Liste der ActivityType-Definitionen zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="2c899-201">Parameters specifying how to return a list of ActivityType definitions.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c899-202">Ruft die erste Seite der ActivityType-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="2c899-202">Gets the first page of ActivityType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c899-203">Die Liste ActivityType Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="2c899-203">The List ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ActivityTypeListParameters) As Task(Of ActivityTypeListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c899-204">Verweis auf die Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="2c899-204">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c899-205">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-205">Required.</span></span> <span data-ttu-id="2c899-206">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-206">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="2c899-207">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-207">Required.</span></span> <span data-ttu-id="2c899-208">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="2c899-208">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c899-209">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-209">Required.</span></span> <span data-ttu-id="2c899-210">Parameter, die angibt, wie eine Liste der ActivityType-Definitionen zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="2c899-210">Parameters specifying how to return a list of ActivityType definitions.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c899-211">Ruft die erste Seite der ActivityType-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="2c899-211">Gets the first page of ActivityType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c899-212">Die Liste ActivityType Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="2c899-212">The List ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse ListNext (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse ListNext(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IActivityTypeOperations, nextLink As String) As ActivityTypeListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c899-213">Verweis auf die Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="2c899-213">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="2c899-214">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-214">Required.</span></span> <span data-ttu-id="2c899-215">Die Url zur nächsten Seite "activitytypes".</span><span class="sxs-lookup"><span data-stu-id="2c899-215">The url to the next ActivityTypes page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c899-216">Ruft die nächste Seite der ActivityType-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="2c899-216">Gets the next page of ActivityType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c899-217">Die Liste ActivityType Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="2c899-217">The List ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IActivityTypeOperations, nextLink As String) As Task(Of ActivityTypeListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c899-218">Verweis auf die Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="2c899-218">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="2c899-219">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2c899-219">Required.</span></span> <span data-ttu-id="2c899-220">Die Url zur nächsten Seite "activitytypes".</span><span class="sxs-lookup"><span data-stu-id="2c899-220">The url to the next ActivityTypes page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c899-221">Ruft die nächste Seite der ActivityType-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="2c899-221">Gets the next page of ActivityType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c899-222">Die Liste ActivityType Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="2c899-222">The List ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>