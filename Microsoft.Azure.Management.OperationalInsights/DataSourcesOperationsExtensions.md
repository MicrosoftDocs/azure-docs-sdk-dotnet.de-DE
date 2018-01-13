<Type Name="DataSourcesOperationsExtensions" FullName="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataSourcesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataSourcesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataSourcesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataSourcesOperationsExtensions = class" />
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
            <span data-ttu-id="c32ad-101">Erweiterungsmethoden für DataSourcesOperations.</span><span class="sxs-lookup"><span data-stu-id="c32ad-101">Extension methods for DataSourcesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.DataSource CreateOrUpdate (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, Microsoft.Azure.Management.OperationalInsights.Models.DataSource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.DataSource CreateOrUpdate(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, class Microsoft.Azure.Management.OperationalInsights.Models.DataSource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.DataSource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDataSourcesOperations, resourceGroupName As String, workspaceName As String, dataSourceName As String, parameters As DataSource) As DataSource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.DataSource -&gt; Microsoft.Azure.Management.OperationalInsights.Models.DataSource" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, workspaceName, dataSourceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.DataSource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c32ad-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c32ad-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c32ad-103">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c32ad-103">The name of the resource group to get.</span></span> <span data-ttu-id="c32ad-104">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="c32ad-104">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="c32ad-105">Name des der Protokollanalyse-Arbeitsbereich, die die Datenquelle enthält</span><span class="sxs-lookup"><span data-stu-id="c32ad-105">Name of the Log Analytics Workspace that will contain the datasource</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="c32ad-106">Der Name der Datasource-Ressource.</span><span class="sxs-lookup"><span data-stu-id="c32ad-106">The name of the datasource resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c32ad-107">Die Parameter zum Erstellen oder Aktualisieren einer Datenquelle erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c32ad-107">The parameters required to create or update a datasource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c32ad-108">Erstellen oder Aktualisieren einer Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="c32ad-108">Create or update a data source.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, Microsoft.Azure.Management.OperationalInsights.Models.DataSource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, class Microsoft.Azure.Management.OperationalInsights.Models.DataSource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.DataSource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.DataSource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, workspaceName, dataSourceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.DataSource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c32ad-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c32ad-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c32ad-110">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c32ad-110">The name of the resource group to get.</span></span> <span data-ttu-id="c32ad-111">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="c32ad-111">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="c32ad-112">Name des der Protokollanalyse-Arbeitsbereich, die die Datenquelle enthält</span><span class="sxs-lookup"><span data-stu-id="c32ad-112">Name of the Log Analytics Workspace that will contain the datasource</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="c32ad-113">Der Name der Datasource-Ressource.</span><span class="sxs-lookup"><span data-stu-id="c32ad-113">The name of the datasource resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c32ad-114">Die Parameter zum Erstellen oder Aktualisieren einer Datenquelle erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c32ad-114">The parameters required to create or update a datasource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c32ad-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c32ad-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c32ad-116">Erstellen oder Aktualisieren einer Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="c32ad-116">Create or update a data source.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.Delete(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IDataSourcesOperations, resourceGroupName As String, workspaceName As String, dataSourceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.Delete (operations, resourceGroupName, workspaceName, dataSourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c32ad-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c32ad-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c32ad-118">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c32ad-118">The name of the resource group to get.</span></span> <span data-ttu-id="c32ad-119">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="c32ad-119">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="c32ad-120">Der Name des der Protokollanalyse-Arbeitsbereich, die die Datenquelle enthält.</span><span class="sxs-lookup"><span data-stu-id="c32ad-120">Name of the Log Analytics Workspace that contains the datasource.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="c32ad-121">Der Name der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="c32ad-121">Name of the datasource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c32ad-122">Löscht eine datenquellinstanz an.</span><span class="sxs-lookup"><span data-stu-id="c32ad-122">Deletes a data source instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.DeleteAsync (operations, resourceGroupName, workspaceName, dataSourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c32ad-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c32ad-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c32ad-124">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c32ad-124">The name of the resource group to get.</span></span> <span data-ttu-id="c32ad-125">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="c32ad-125">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="c32ad-126">Der Name des der Protokollanalyse-Arbeitsbereich, die die Datenquelle enthält.</span><span class="sxs-lookup"><span data-stu-id="c32ad-126">Name of the Log Analytics Workspace that contains the datasource.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="c32ad-127">Der Name der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="c32ad-127">Name of the datasource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c32ad-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c32ad-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c32ad-129">Löscht eine datenquellinstanz an.</span><span class="sxs-lookup"><span data-stu-id="c32ad-129">Deletes a data source instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.DataSource Get (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.DataSource Get(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.Get(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDataSourcesOperations, resourceGroupName As String, workspaceName As String, dataSourceName As String) As DataSource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.DataSource" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.Get (operations, resourceGroupName, workspaceName, dataSourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c32ad-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c32ad-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c32ad-131">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c32ad-131">The name of the resource group to get.</span></span> <span data-ttu-id="c32ad-132">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="c32ad-132">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="c32ad-133">Der Name des der Protokollanalyse-Arbeitsbereich, die die Datenquelle enthält.</span><span class="sxs-lookup"><span data-stu-id="c32ad-133">Name of the Log Analytics Workspace that contains the datasource.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="c32ad-134">Name der Datenquelle</span><span class="sxs-lookup"><span data-stu-id="c32ad-134">Name of the datasource</span></span>
            </param>
        <summary>
            <span data-ttu-id="c32ad-135">Ruft die Datenquelleninstanz ab.</span><span class="sxs-lookup"><span data-stu-id="c32ad-135">Gets a datasource instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; GetAsync (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; GetAsync(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.GetAsync(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.GetAsync (operations, resourceGroupName, workspaceName, dataSourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c32ad-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c32ad-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c32ad-137">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c32ad-137">The name of the resource group to get.</span></span> <span data-ttu-id="c32ad-138">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="c32ad-138">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="c32ad-139">Der Name des der Protokollanalyse-Arbeitsbereich, die die Datenquelle enthält.</span><span class="sxs-lookup"><span data-stu-id="c32ad-139">Name of the Log Analytics Workspace that contains the datasource.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="c32ad-140">Name der Datenquelle</span><span class="sxs-lookup"><span data-stu-id="c32ad-140">Name of the datasource</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c32ad-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c32ad-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c32ad-142">Ruft die Datenquelleninstanz ab.</span><span class="sxs-lookup"><span data-stu-id="c32ad-142">Gets a datasource instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspace">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; ListByWorkspace (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; odataQuery, string resourceGroupName, string workspaceName, string skiptoken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; ListByWorkspace(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; odataQuery, string resourceGroupName, string workspaceName, string skiptoken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspace(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByWorkspace (operations As IDataSourcesOperations, odataQuery As ODataQuery(Of DataSourceFilter), resourceGroupName As String, workspaceName As String, Optional skiptoken As String = null) As IPage(Of DataSource)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspace : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspace (operations, odataQuery, resourceGroupName, workspaceName, skiptoken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt;" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c32ad-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c32ad-143">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="c32ad-144">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="c32ad-144">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c32ad-145">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c32ad-145">The name of the resource group to get.</span></span> <span data-ttu-id="c32ad-146">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="c32ad-146">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="c32ad-147">Der Arbeitsbereich, der die Datenquellen enthält.</span><span class="sxs-lookup"><span data-stu-id="c32ad-147">The workspace that contains the data sources.</span></span>
            </param>
        <param name="skiptoken">
            <span data-ttu-id="c32ad-148">Die Auflistung von Datenquelleninstanzen Ausgangspunkt.</span><span class="sxs-lookup"><span data-stu-id="c32ad-148">Starting point of the collection of data source instances.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c32ad-149">Ruft die erste Seite des Datenquelleninstanzen in einem Arbeitsbereich mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="c32ad-149">Gets the first page of data source instances in a workspace with the link to the next page.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt; ListByWorkspaceAsync (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; odataQuery, string resourceGroupName, string workspaceName, string skiptoken = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt; ListByWorkspaceAsync(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; odataQuery, string resourceGroupName, string workspaceName, string skiptoken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceAsync(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter},System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceAsync : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceAsync (operations, odataQuery, resourceGroupName, workspaceName, skiptoken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions/&lt;ListByWorkspaceAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt;" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c32ad-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c32ad-150">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="c32ad-151">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="c32ad-151">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c32ad-152">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c32ad-152">The name of the resource group to get.</span></span> <span data-ttu-id="c32ad-153">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="c32ad-153">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="c32ad-154">Der Arbeitsbereich, der die Datenquellen enthält.</span><span class="sxs-lookup"><span data-stu-id="c32ad-154">The workspace that contains the data sources.</span></span>
            </param>
        <param name="skiptoken">
            <span data-ttu-id="c32ad-155">Die Auflistung von Datenquelleninstanzen Ausgangspunkt.</span><span class="sxs-lookup"><span data-stu-id="c32ad-155">Starting point of the collection of data source instances.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c32ad-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c32ad-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c32ad-157">Ruft die erste Seite des Datenquelleninstanzen in einem Arbeitsbereich mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="c32ad-157">Gets the first page of data source instances in a workspace with the link to the next page.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; ListByWorkspaceNext (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; ListByWorkspaceNext(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceNext(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByWorkspaceNext (operations As IDataSourcesOperations, nextPageLink As String) As IPage(Of DataSource)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceNext : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c32ad-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c32ad-158">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c32ad-159">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c32ad-159">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c32ad-160">Ruft die erste Seite des Datenquelleninstanzen in einem Arbeitsbereich mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="c32ad-160">Gets the first page of data source instances in a workspace with the link to the next page.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt; ListByWorkspaceNextAsync (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt; ListByWorkspaceNextAsync(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceNextAsync(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceNextAsync : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions/&lt;ListByWorkspaceNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c32ad-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c32ad-161">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c32ad-162">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c32ad-162">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c32ad-163">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c32ad-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c32ad-164">Ruft die erste Seite des Datenquelleninstanzen in einem Arbeitsbereich mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="c32ad-164">Gets the first page of data source instances in a workspace with the link to the next page.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>