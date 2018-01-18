<Type Name="StorageInsightsOperationsExtensions" FullName="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StorageInsightsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StorageInsightsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StorageInsightsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StorageInsightsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4abe8-101">Erweiterungsmethoden für StorageInsightsOperations.</span><span class="sxs-lookup"><span data-stu-id="4abe8-101">Extension methods for StorageInsightsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight CreateOrUpdate (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName, Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight CreateOrUpdate(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName, class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IStorageInsightsOperations, resourceGroupName As String, workspaceName As String, storageInsightName As String, parameters As StorageInsight) As StorageInsight" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight -&gt; Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, workspaceName, storageInsightName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="storageInsightName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4abe8-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4abe8-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4abe8-103">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4abe8-103">The name of the resource group to get.</span></span> <span data-ttu-id="4abe8-104">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="4abe8-104">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="4abe8-105">Protokollnamen Protokollanalyse-Arbeitsbereich an, die die Ressource StorageInsightsConfigs enthält</span><span class="sxs-lookup"><span data-stu-id="4abe8-105">Log Analytics Workspace name that will contain the storageInsightsConfigs resource</span></span>
            </param>
        <param name="storageInsightName">
            <span data-ttu-id="4abe8-106">Name der Ressource storageInsightsConfigs</span><span class="sxs-lookup"><span data-stu-id="4abe8-106">Name of the storageInsightsConfigs resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4abe8-107">Die Parameter zum Erstellen oder Aktualisieren einer Insight Speicher erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4abe8-107">The parameters required to create or update a storage insight.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4abe8-108">Erstellen Sie oder aktualisieren Sie eine Speicher-Einblicke.</span><span class="sxs-lookup"><span data-stu-id="4abe8-108">Create or update a storage insight.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName, Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName, class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, workspaceName, storageInsightName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="storageInsightName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4abe8-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4abe8-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4abe8-110">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4abe8-110">The name of the resource group to get.</span></span> <span data-ttu-id="4abe8-111">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="4abe8-111">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="4abe8-112">Protokollnamen Protokollanalyse-Arbeitsbereich an, die die Ressource StorageInsightsConfigs enthält</span><span class="sxs-lookup"><span data-stu-id="4abe8-112">Log Analytics Workspace name that will contain the storageInsightsConfigs resource</span></span>
            </param>
        <param name="storageInsightName">
            <span data-ttu-id="4abe8-113">Name der Ressource storageInsightsConfigs</span><span class="sxs-lookup"><span data-stu-id="4abe8-113">Name of the storageInsightsConfigs resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4abe8-114">Die Parameter zum Erstellen oder Aktualisieren einer Insight Speicher erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4abe8-114">The parameters required to create or update a storage insight.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4abe8-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4abe8-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4abe8-116">Erstellen Sie oder aktualisieren Sie eine Speicher-Einblicke.</span><span class="sxs-lookup"><span data-stu-id="4abe8-116">Create or update a storage insight.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.Delete(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IStorageInsightsOperations, resourceGroupName As String, workspaceName As String, storageInsightName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.Delete (operations, resourceGroupName, workspaceName, storageInsightName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="storageInsightName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4abe8-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4abe8-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4abe8-118">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4abe8-118">The name of the resource group to get.</span></span> <span data-ttu-id="4abe8-119">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="4abe8-119">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="4abe8-120">Protokoll-Protokollanalyse-Arbeitsbereich an, der die StorageInsightsConfigs-Ressource</span><span class="sxs-lookup"><span data-stu-id="4abe8-120">Log Analytics Workspace name that contains the storageInsightsConfigs resource</span></span>
            </param>
        <param name="storageInsightName">
            <span data-ttu-id="4abe8-121">Name der Ressource storageInsightsConfigs</span><span class="sxs-lookup"><span data-stu-id="4abe8-121">Name of the storageInsightsConfigs resource</span></span>
            </param>
        <summary>
            <span data-ttu-id="4abe8-122">Löscht eine Ressource storageInsightsConfigs</span><span class="sxs-lookup"><span data-stu-id="4abe8-122">Deletes a storageInsightsConfigs resource</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.DeleteAsync (operations, resourceGroupName, workspaceName, storageInsightName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="storageInsightName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4abe8-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4abe8-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4abe8-124">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4abe8-124">The name of the resource group to get.</span></span> <span data-ttu-id="4abe8-125">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="4abe8-125">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="4abe8-126">Protokoll-Protokollanalyse-Arbeitsbereich an, der die StorageInsightsConfigs-Ressource</span><span class="sxs-lookup"><span data-stu-id="4abe8-126">Log Analytics Workspace name that contains the storageInsightsConfigs resource</span></span>
            </param>
        <param name="storageInsightName">
            <span data-ttu-id="4abe8-127">Name der Ressource storageInsightsConfigs</span><span class="sxs-lookup"><span data-stu-id="4abe8-127">Name of the storageInsightsConfigs resource</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4abe8-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4abe8-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4abe8-129">Löscht eine Ressource storageInsightsConfigs</span><span class="sxs-lookup"><span data-stu-id="4abe8-129">Deletes a storageInsightsConfigs resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight Get (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight Get(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.Get(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IStorageInsightsOperations, resourceGroupName As String, workspaceName As String, storageInsightName As String) As StorageInsight" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.Get (operations, resourceGroupName, workspaceName, storageInsightName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="storageInsightName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4abe8-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4abe8-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4abe8-131">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4abe8-131">The name of the resource group to get.</span></span> <span data-ttu-id="4abe8-132">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="4abe8-132">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="4abe8-133">Protokoll-Protokollanalyse-Arbeitsbereich an, der die StorageInsightsConfigs-Ressource</span><span class="sxs-lookup"><span data-stu-id="4abe8-133">Log Analytics Workspace name that contains the storageInsightsConfigs resource</span></span>
            </param>
        <param name="storageInsightName">
            <span data-ttu-id="4abe8-134">Name der Ressource storageInsightsConfigs</span><span class="sxs-lookup"><span data-stu-id="4abe8-134">Name of the storageInsightsConfigs resource</span></span>
            </param>
        <summary>
            <span data-ttu-id="4abe8-135">Ruft eine Instanz des Storage Insight ab.</span><span class="sxs-lookup"><span data-stu-id="4abe8-135">Gets a storage insight instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt; GetAsync (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt; GetAsync(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.GetAsync(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.GetAsync (operations, resourceGroupName, workspaceName, storageInsightName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="storageInsightName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4abe8-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4abe8-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4abe8-137">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4abe8-137">The name of the resource group to get.</span></span> <span data-ttu-id="4abe8-138">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="4abe8-138">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="4abe8-139">Protokoll-Protokollanalyse-Arbeitsbereich an, der die StorageInsightsConfigs-Ressource</span><span class="sxs-lookup"><span data-stu-id="4abe8-139">Log Analytics Workspace name that contains the storageInsightsConfigs resource</span></span>
            </param>
        <param name="storageInsightName">
            <span data-ttu-id="4abe8-140">Name der Ressource storageInsightsConfigs</span><span class="sxs-lookup"><span data-stu-id="4abe8-140">Name of the storageInsightsConfigs resource</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4abe8-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4abe8-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4abe8-142">Ruft eine Instanz des Storage Insight ab.</span><span class="sxs-lookup"><span data-stu-id="4abe8-142">Gets a storage insight instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspace">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt; ListByWorkspace (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt; ListByWorkspace(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.ListByWorkspace(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByWorkspace (operations As IStorageInsightsOperations, resourceGroupName As String, workspaceName As String) As IPage(Of StorageInsight)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspace : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.ListByWorkspace (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4abe8-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4abe8-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4abe8-144">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4abe8-144">The name of the resource group to get.</span></span> <span data-ttu-id="4abe8-145">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="4abe8-145">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="4abe8-146">Protokollnamen Protokollanalyse-Arbeitsbereich an, die die Ressource StorageInsightsConfigs enthält</span><span class="sxs-lookup"><span data-stu-id="4abe8-146">Log Analytics Workspace name that will contain the storageInsightsConfigs resource</span></span>
            </param>
        <summary>
            <span data-ttu-id="4abe8-147">Listet die Storage Insight-Instanzen innerhalb eines Arbeitsbereichs</span><span class="sxs-lookup"><span data-stu-id="4abe8-147">Lists the storage insight instances within a workspace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt; ListByWorkspaceAsync (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt; ListByWorkspaceAsync(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.ListByWorkspaceAsync(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceAsync : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.ListByWorkspaceAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions/&lt;ListByWorkspaceAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4abe8-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4abe8-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4abe8-149">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4abe8-149">The name of the resource group to get.</span></span> <span data-ttu-id="4abe8-150">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="4abe8-150">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="4abe8-151">Protokollnamen Protokollanalyse-Arbeitsbereich an, die die Ressource StorageInsightsConfigs enthält</span><span class="sxs-lookup"><span data-stu-id="4abe8-151">Log Analytics Workspace name that will contain the storageInsightsConfigs resource</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4abe8-152">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4abe8-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4abe8-153">Listet die Storage Insight-Instanzen innerhalb eines Arbeitsbereichs</span><span class="sxs-lookup"><span data-stu-id="4abe8-153">Lists the storage insight instances within a workspace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt; ListByWorkspaceNext (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt; ListByWorkspaceNext(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.ListByWorkspaceNext(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByWorkspaceNext (operations As IStorageInsightsOperations, nextPageLink As String) As IPage(Of StorageInsight)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceNext : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.ListByWorkspaceNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4abe8-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4abe8-154">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4abe8-155">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4abe8-155">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4abe8-156">Listet die Storage Insight-Instanzen innerhalb eines Arbeitsbereichs</span><span class="sxs-lookup"><span data-stu-id="4abe8-156">Lists the storage insight instances within a workspace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt; ListByWorkspaceNextAsync (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt; ListByWorkspaceNextAsync(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.ListByWorkspaceNextAsync(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceNextAsync : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.ListByWorkspaceNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions/&lt;ListByWorkspaceNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4abe8-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4abe8-157">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4abe8-158">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4abe8-158">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4abe8-159">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4abe8-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4abe8-160">Listet die Storage Insight-Instanzen innerhalb eines Arbeitsbereichs</span><span class="sxs-lookup"><span data-stu-id="4abe8-160">Lists the storage insight instances within a workspace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>