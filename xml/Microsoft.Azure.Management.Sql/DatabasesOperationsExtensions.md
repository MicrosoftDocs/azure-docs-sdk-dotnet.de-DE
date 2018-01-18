<Type Name="DatabasesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DatabasesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DatabasesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DatabasesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DatabasesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0b2f4-101">Erweiterungsmethoden für DatabasesOperations.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-101">Extension methods for DatabasesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateImportOperation">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ImportExportResponse BeginCreateImportOperation (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ImportExportResponse BeginCreateImportOperation(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginCreateImportOperation(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateImportOperation (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As ImportExtensionRequest) As ImportExportResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateImportOperation : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest -&gt; Microsoft.Azure.Management.Sql.Models.ImportExportResponse" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginCreateImportOperation (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ImportExportResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-105">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-106">Der Name der Datenbank, die in importieren</span><span class="sxs-lookup"><span data-stu-id="0b2f4-106">The name of the database to import into</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-107">Die erforderlichen Parameter für eine bacpac-Datei in eine Datenbank importieren.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-107">The required parameters for importing a Bacpac into a database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-108">Erstellt einen Importvorgang, der eine bacpac-Datei in einer vorhandenen Datenbank importiert.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-108">Creates an import operation that imports a bacpac into an existing database.</span></span> <span data-ttu-id="0b2f4-109">Die vorhandene Datenbank muss leer sein.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-109">The existing database must be empty.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateImportOperationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt; BeginCreateImportOperationAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt; BeginCreateImportOperationAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginCreateImportOperationAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateImportOperationAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginCreateImportOperationAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;BeginCreateImportOperationAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-111">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-111">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-112">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-112">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-113">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-113">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-114">Der Name der Datenbank, die in importieren</span><span class="sxs-lookup"><span data-stu-id="0b2f4-114">The name of the database to import into</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-115">Die erforderlichen Parameter für eine bacpac-Datei in eine Datenbank importieren.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-115">The required parameters for importing a Bacpac into a database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-116">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-117">Erstellt einen Importvorgang, der eine bacpac-Datei in einer vorhandenen Datenbank importiert.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-117">Creates an import operation that imports a bacpac into an existing database.</span></span> <span data-ttu-id="0b2f4-118">Die vorhandene Datenbank muss leer sein.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-118">The existing database must be empty.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Database BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.Database parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Database BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.Database parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.Database)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As Database) As Database" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.Database -&gt; Microsoft.Azure.Management.Sql.Models.Database" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Database</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.Database" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-120">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-120">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-121">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-121">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-122">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-122">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-123">Der Name der Datenbank verarbeitet werden sollen (aktualisiert oder erstellt wurde).</span><span class="sxs-lookup"><span data-stu-id="0b2f4-123">The name of the database to be operated on (updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-124">Die erforderlichen Parameter zum Erstellen oder Aktualisieren einer Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-124">The required parameters for creating or updating a database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-125">Erstellt eine neue Datenbank oder aktualisiert eine bereits vorhandene Datenbank</span><span class="sxs-lookup"><span data-stu-id="0b2f4-125">Creates a new database or updates an existing database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.Database parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.Database parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.Database,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.Database * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.Database" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-127">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-127">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-128">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-128">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-129">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-129">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-130">Der Name der Datenbank verarbeitet werden sollen (aktualisiert oder erstellt wurde).</span><span class="sxs-lookup"><span data-stu-id="0b2f4-130">The name of the database to be operated on (updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-131">Die erforderlichen Parameter zum Erstellen oder Aktualisieren einer Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-131">The required parameters for creating or updating a database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-133">Erstellt eine neue Datenbank oder aktualisiert eine bereits vorhandene Datenbank</span><span class="sxs-lookup"><span data-stu-id="0b2f4-133">Creates a new database or updates an existing database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExport">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ImportExportResponse BeginExport (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.ExportRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ImportExportResponse BeginExport(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.ExportRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginExport(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ExportRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginExport (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As ExportRequest) As ImportExportResponse" />
      <MemberSignature Language="F#" Value="static member BeginExport : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ExportRequest -&gt; Microsoft.Azure.Management.Sql.Models.ImportExportResponse" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginExport (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ImportExportResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ExportRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-135">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-135">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-136">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-136">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-137">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-137">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-138">Der Name der zu exportierenden Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-138">The name of the database to be exported.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-139">Die erforderlichen Parameter für eine Datenbank exportieren.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-139">The required parameters for exporting a database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-140">Wird eine Datenbank in eine bacpac-Datei exportiert.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-140">Exports a database to a bacpac.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt; BeginExportAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.ExportRequest parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt; BeginExportAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.ExportRequest parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginExportAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ExportRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginExportAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ExportRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginExportAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;BeginExportAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ExportRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-142">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-142">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-143">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-143">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-144">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-144">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-145">Der Name der zu exportierenden Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-145">The name of the database to be exported.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-146">Die erforderlichen Parameter für eine Datenbank exportieren.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-146">The required parameters for exporting a database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-147">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-148">Wird eine Datenbank in eine bacpac-Datei exportiert.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-148">Exports a database to a bacpac.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginImport">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ImportExportResponse BeginImport (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ImportRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ImportExportResponse BeginImport(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ImportRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginImport(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ImportRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginImport (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, parameters As ImportRequest) As ImportExportResponse" />
      <MemberSignature Language="F#" Value="static member BeginImport : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * Microsoft.Azure.Management.Sql.Models.ImportRequest -&gt; Microsoft.Azure.Management.Sql.Models.ImportExportResponse" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginImport (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ImportExportResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ImportRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-149">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-150">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-150">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-151">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-151">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-152">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-152">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-153">Die erforderlichen Parameter für eine bacpac-Datei in eine Datenbank importieren.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-153">The required parameters for importing a Bacpac into a database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-154">Importiert eine bacpac-Datei in eine neue Datenbank an.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-154">Imports a bacpac into a new database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginImportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt; BeginImportAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ImportRequest parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt; BeginImportAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ImportRequest parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginImportAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ImportRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginImportAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * Microsoft.Azure.Management.Sql.Models.ImportRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginImportAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;BeginImportAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ImportRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-156">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-156">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-157">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-157">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-158">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-158">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-159">Die erforderlichen Parameter für eine bacpac-Datei in eine Datenbank importieren.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-159">The required parameters for importing a Bacpac into a database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-160">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-161">Importiert eine bacpac-Datei in eine neue Datenbank an.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-161">Imports a bacpac into a new database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPause">
      <MemberSignature Language="C#" Value="public static void BeginPause (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginPause(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginPause(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginPause (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String)" />
      <MemberSignature Language="F#" Value="static member BeginPause : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginPause (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-163">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-163">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-164">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-164">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-165">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-165">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-166">Der Name des Datawarehouse anhalten.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-166">The name of the data warehouse to pause.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-167">Hält ein Datawarehouse.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-167">Pauses a data warehouse.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPauseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginPauseAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginPauseAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginPauseAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPauseAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginPauseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;BeginPauseAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-169">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-169">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-170">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-170">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-171">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-171">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-172">Der Name des Datawarehouse anhalten.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-172">The name of the data warehouse to pause.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-173">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-174">Hält ein Datawarehouse.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-174">Pauses a data warehouse.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResume">
      <MemberSignature Language="C#" Value="public static void BeginResume (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginResume(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginResume(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginResume (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String)" />
      <MemberSignature Language="F#" Value="static member BeginResume : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginResume (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-175">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-176">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-176">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-177">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-177">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-178">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-178">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-179">Der Name des Datawarehouse fortgesetzt.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-179">The name of the data warehouse to resume.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-180">Wird ein Datawarehouse fortgesetzt.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-180">Resumes a data warehouse.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginResumeAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginResumeAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginResumeAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResumeAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginResumeAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;BeginResumeAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-181">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-181">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-182">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-182">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-183">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-183">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-184">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-184">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-185">Der Name des Datawarehouse fortgesetzt.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-185">The name of the data warehouse to resume.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-186">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-187">Wird ein Datawarehouse fortgesetzt.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-187">Resumes a data warehouse.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Database BeginUpdate (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.DatabaseUpdate parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Database BeginUpdate(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.DatabaseUpdate parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DatabaseUpdate)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As DatabaseUpdate) As Database" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.DatabaseUpdate -&gt; Microsoft.Azure.Management.Sql.Models.Database" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginUpdate (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Database</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-188">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-189">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-189">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-190">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-190">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-191">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-191">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-192">Der Name der Datenbank aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-192">The name of the database to be updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-193">Die erforderlichen Parameter für eine Datenbank aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-193">The required parameters for updating a database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-194">Aktualisiert eine vorhandene Datenbank</span><span class="sxs-lookup"><span data-stu-id="0b2f4-194">Updates an existing database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.DatabaseUpdate parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.DatabaseUpdate parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DatabaseUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.DatabaseUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;BeginUpdateAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-196">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-196">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-197">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-197">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-198">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-198">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-199">Der Name der Datenbank aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-199">The name of the database to be updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-200">Die erforderlichen Parameter für eine Datenbank aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-200">The required parameters for updating a database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-201">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-201">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-202">Aktualisiert eine vorhandene Datenbank</span><span class="sxs-lookup"><span data-stu-id="0b2f4-202">Updates an existing database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateImportOperation">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ImportExportResponse CreateImportOperation (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ImportExportResponse CreateImportOperation(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.CreateImportOperation(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateImportOperation (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As ImportExtensionRequest) As ImportExportResponse" />
      <MemberSignature Language="F#" Value="static member CreateImportOperation : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest -&gt; Microsoft.Azure.Management.Sql.Models.ImportExportResponse" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.CreateImportOperation (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ImportExportResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-203">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-203">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-204">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-204">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-205">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-205">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-206">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-206">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-207">Der Name der Datenbank, die in importieren</span><span class="sxs-lookup"><span data-stu-id="0b2f4-207">The name of the database to import into</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-208">Die erforderlichen Parameter für eine bacpac-Datei in eine Datenbank importieren.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-208">The required parameters for importing a Bacpac into a database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-209">Erstellt einen Importvorgang, der eine bacpac-Datei in einer vorhandenen Datenbank importiert.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-209">Creates an import operation that imports a bacpac into an existing database.</span></span> <span data-ttu-id="0b2f4-210">Die vorhandene Datenbank muss leer sein.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-210">The existing database must be empty.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateImportOperationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt; CreateImportOperationAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt; CreateImportOperationAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.CreateImportOperationAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateImportOperationAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.CreateImportOperationAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;CreateImportOperationAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-211">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-211">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-212">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-212">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-213">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-213">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-214">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-214">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-215">Der Name der Datenbank, die in importieren</span><span class="sxs-lookup"><span data-stu-id="0b2f4-215">The name of the database to import into</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-216">Die erforderlichen Parameter für eine bacpac-Datei in eine Datenbank importieren.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-216">The required parameters for importing a Bacpac into a database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-217">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-218">Erstellt einen Importvorgang, der eine bacpac-Datei in einer vorhandenen Datenbank importiert.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-218">Creates an import operation that imports a bacpac into an existing database.</span></span> <span data-ttu-id="0b2f4-219">Die vorhandene Datenbank muss leer sein.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-219">The existing database must be empty.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Database CreateOrUpdate (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.Database parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Database CreateOrUpdate(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.Database parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.Database)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As Database) As Database" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.Database -&gt; Microsoft.Azure.Management.Sql.Models.Database" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Database</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.Database" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-220">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-220">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-221">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-221">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-222">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-222">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-223">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-223">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-224">Der Name der Datenbank verarbeitet werden sollen (aktualisiert oder erstellt wurde).</span><span class="sxs-lookup"><span data-stu-id="0b2f4-224">The name of the database to be operated on (updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-225">Die erforderlichen Parameter zum Erstellen oder Aktualisieren einer Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-225">The required parameters for creating or updating a database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-226">Erstellt eine neue Datenbank oder aktualisiert eine bereits vorhandene Datenbank</span><span class="sxs-lookup"><span data-stu-id="0b2f4-226">Creates a new database or updates an existing database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.Database parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.Database parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.Database,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.Database * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.Database" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-227">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-227">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-228">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-228">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-229">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-229">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-230">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-230">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-231">Der Name der Datenbank verarbeitet werden sollen (aktualisiert oder erstellt wurde).</span><span class="sxs-lookup"><span data-stu-id="0b2f4-231">The name of the database to be operated on (updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-232">Die erforderlichen Parameter zum Erstellen oder Aktualisieren einer Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-232">The required parameters for creating or updating a database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-233">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-233">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-234">Erstellt eine neue Datenbank oder aktualisiert eine bereits vorhandene Datenbank</span><span class="sxs-lookup"><span data-stu-id="0b2f4-234">Creates a new database or updates an existing database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.Delete (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-235">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-235">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-236">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-236">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-237">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-237">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-238">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-238">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-239">Der Name der Datenbank gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-239">The name of the database to be deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-240">Löscht eine Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-240">Deletes a database.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;DeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-241">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-241">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-242">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-242">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-243">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-243">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-244">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-244">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-245">Der Name der Datenbank gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-245">The name of the database to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-246">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-246">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-247">Löscht eine Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-247">Deletes a database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Export">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ImportExportResponse Export (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.ExportRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ImportExportResponse Export(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.ExportRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.Export(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ExportRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Export (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As ExportRequest) As ImportExportResponse" />
      <MemberSignature Language="F#" Value="static member Export : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ExportRequest -&gt; Microsoft.Azure.Management.Sql.Models.ImportExportResponse" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.Export (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ImportExportResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ExportRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-248">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-248">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-249">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-249">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-250">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-250">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-251">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-251">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-252">Der Name der zu exportierenden Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-252">The name of the database to be exported.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-253">Die erforderlichen Parameter für eine Datenbank exportieren.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-253">The required parameters for exporting a database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-254">Wird eine Datenbank in eine bacpac-Datei exportiert.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-254">Exports a database to a bacpac.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt; ExportAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.ExportRequest parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt; ExportAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.ExportRequest parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ExportAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ExportRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ExportRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ExportAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;ExportAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ExportRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-255">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-255">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-256">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-256">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-257">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-257">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-258">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-258">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-259">Der Name der zu exportierenden Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-259">The name of the database to be exported.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-260">Die erforderlichen Parameter für eine Datenbank exportieren.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-260">The required parameters for exporting a database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-261">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-261">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-262">Wird eine Datenbank in eine bacpac-Datei exportiert.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-262">Exports a database to a bacpac.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Database Get (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Database Get(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String, Optional expand As String = null) As Database" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.Database" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Database</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-263">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-263">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-264">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-264">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-265">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-265">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-266">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-266">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-267">Der Name der Datenbank abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-267">The name of the database to be retrieved.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="0b2f4-268">Eine durch Trennzeichen getrennte Liste von untergeordneten Objekten in der Antwort zu erweitern.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-268">A comma separated list of child objects to expand in the response.</span></span> <span data-ttu-id="0b2f4-269">Möglichen Eigenschaften: ServiceTierAdvisors TransparentDataEncryption.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-269">Possible properties: serviceTierAdvisors, transparentDataEncryption.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-270">Ruft eine Datenbank ab</span><span class="sxs-lookup"><span data-stu-id="0b2f4-270">Gets a database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt; GetAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt; GetAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;GetAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-271">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-271">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-272">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-272">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-273">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-273">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-274">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-274">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-275">Der Name der Datenbank abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-275">The name of the database to be retrieved.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="0b2f4-276">Eine durch Trennzeichen getrennte Liste von untergeordneten Objekten in der Antwort zu erweitern.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-276">A comma separated list of child objects to expand in the response.</span></span> <span data-ttu-id="0b2f4-277">Möglichen Eigenschaften: ServiceTierAdvisors TransparentDataEncryption.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-277">Possible properties: serviceTierAdvisors, transparentDataEncryption.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-278">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-278">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-279">Ruft eine Datenbank ab</span><span class="sxs-lookup"><span data-stu-id="0b2f4-279">Gets a database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByElasticPool">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Database GetByElasticPool (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Database GetByElasticPool(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.GetByElasticPool(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetByElasticPool (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, elasticPoolName As String, databaseName As String) As Database" />
      <MemberSignature Language="F#" Value="static member GetByElasticPool : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.Database" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.GetByElasticPool (operations, resourceGroupName, serverName, elasticPoolName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Database</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-280">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-280">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-281">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-281">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-282">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-282">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-283">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-283">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="0b2f4-284">Der Name des elastischen Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-284">The name of the elastic pool to be retrieved.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-285">Der Name der Datenbank abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-285">The name of the database to be retrieved.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-286">Ruft eine Datenbank in einem Pool für elastische Datenbanken ab</span><span class="sxs-lookup"><span data-stu-id="0b2f4-286">Gets a database inside of an elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByElasticPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt; GetByElasticPoolAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt; GetByElasticPoolAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.GetByElasticPoolAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetByElasticPoolAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.GetByElasticPoolAsync (operations, resourceGroupName, serverName, elasticPoolName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;GetByElasticPoolAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-287">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-287">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-288">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-288">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-289">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-289">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-290">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-290">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="0b2f4-291">Der Name des elastischen Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-291">The name of the elastic pool to be retrieved.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-292">Der Name der Datenbank abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-292">The name of the database to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-293">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-293">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-294">Ruft eine Datenbank in einem Pool für elastische Datenbanken ab</span><span class="sxs-lookup"><span data-stu-id="0b2f4-294">Gets a database inside of an elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByRecommendedElasticPool">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Database GetByRecommendedElasticPool (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Database GetByRecommendedElasticPool(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.GetByRecommendedElasticPool(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetByRecommendedElasticPool (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, recommendedElasticPoolName As String, databaseName As String) As Database" />
      <MemberSignature Language="F#" Value="static member GetByRecommendedElasticPool : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.Database" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.GetByRecommendedElasticPool (operations, resourceGroupName, serverName, recommendedElasticPoolName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Database</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-295">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-295">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-296">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-296">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-297">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-297">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-298">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-298">The name of the server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="0b2f4-299">Der Name des elastischen Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-299">The name of the elastic pool to be retrieved.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-300">Der Name der Datenbank abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-300">The name of the database to be retrieved.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-301">Ruft eine Datenbank in einem empfohlenen Pool für elastische Datenbanken ab</span><span class="sxs-lookup"><span data-stu-id="0b2f4-301">Gets a database inside of a recommented elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByRecommendedElasticPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt; GetByRecommendedElasticPoolAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt; GetByRecommendedElasticPoolAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.GetByRecommendedElasticPoolAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetByRecommendedElasticPoolAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.GetByRecommendedElasticPoolAsync (operations, resourceGroupName, serverName, recommendedElasticPoolName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;GetByRecommendedElasticPoolAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-302">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-302">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-303">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-303">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-304">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-304">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-305">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-305">The name of the server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="0b2f4-306">Der Name des elastischen Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-306">The name of the elastic pool to be retrieved.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-307">Der Name der Datenbank abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-307">The name of the database to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-308">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-308">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-309">Ruft eine Datenbank in einem empfohlenen Pool für elastische Datenbanken ab</span><span class="sxs-lookup"><span data-stu-id="0b2f4-309">Gets a database inside of a recommented elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Import">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ImportExportResponse Import (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ImportRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ImportExportResponse Import(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ImportRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.Import(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ImportRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Import (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, parameters As ImportRequest) As ImportExportResponse" />
      <MemberSignature Language="F#" Value="static member Import : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * Microsoft.Azure.Management.Sql.Models.ImportRequest -&gt; Microsoft.Azure.Management.Sql.Models.ImportExportResponse" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.Import (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ImportExportResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ImportRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-310">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-310">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-311">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-311">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-312">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-312">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-313">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-313">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-314">Die erforderlichen Parameter für eine bacpac-Datei in eine Datenbank importieren.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-314">The required parameters for importing a Bacpac into a database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-315">Importiert eine bacpac-Datei in eine neue Datenbank an.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-315">Imports a bacpac into a new database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt; ImportAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ImportRequest parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt; ImportAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ImportRequest parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ImportAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ImportRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * Microsoft.Azure.Management.Sql.Models.ImportRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ImportAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;ImportAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ImportRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-316">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-316">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-317">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-317">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-318">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-318">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-319">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-319">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-320">Die erforderlichen Parameter für eine bacpac-Datei in eine Datenbank importieren.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-320">The required parameters for importing a Bacpac into a database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-321">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-321">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-322">Importiert eine bacpac-Datei in eine neue Datenbank an.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-322">Imports a bacpac into a new database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByElasticPool">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt; ListByElasticPool (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string elasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt; ListByElasticPool(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string elasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListByElasticPool(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByElasticPool (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, elasticPoolName As String) As IEnumerable(Of Database)" />
      <MemberSignature Language="F#" Value="static member ListByElasticPool : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListByElasticPool (operations, resourceGroupName, serverName, elasticPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-323">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-323">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-324">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-324">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-325">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-325">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-326">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-326">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="0b2f4-327">Der Name des elastischen Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-327">The name of the elastic pool to be retrieved.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-328">Gibt eine Liste der Datenbanken in einem Pool für elastische Datenbanken zurück.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-328">Returns a list of databases in an elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByElasticPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; ListByElasticPoolAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; ListByElasticPoolAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListByElasticPoolAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByElasticPoolAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListByElasticPoolAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;ListByElasticPoolAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-329">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-329">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-330">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-330">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-331">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-331">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-332">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-332">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="0b2f4-333">Der Name des elastischen Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-333">The name of the elastic pool to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-334">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-334">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-335">Gibt eine Liste der Datenbanken in einem Pool für elastische Datenbanken zurück.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-335">Returns a list of databases in an elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByRecommendedElasticPool">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt; ListByRecommendedElasticPool (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt; ListByRecommendedElasticPool(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListByRecommendedElasticPool(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByRecommendedElasticPool (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, recommendedElasticPoolName As String) As IEnumerable(Of Database)" />
      <MemberSignature Language="F#" Value="static member ListByRecommendedElasticPool : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListByRecommendedElasticPool (operations, resourceGroupName, serverName, recommendedElasticPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-336">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-336">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-337">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-337">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-338">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-338">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-339">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-339">The name of the server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="0b2f4-340">Der Name des empfohlenen elastischen Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-340">The name of the recommended elastic pool to be retrieved.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-341">Gibt eine Liste von Datenbanken in einem empfohlenen Pool für elastische Datenbanken zurück</span><span class="sxs-lookup"><span data-stu-id="0b2f4-341">Returns a list of databases inside a recommented elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByRecommendedElasticPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; ListByRecommendedElasticPoolAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; ListByRecommendedElasticPoolAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListByRecommendedElasticPoolAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByRecommendedElasticPoolAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListByRecommendedElasticPoolAsync (operations, resourceGroupName, serverName, recommendedElasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;ListByRecommendedElasticPoolAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-342">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-342">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-343">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-343">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-344">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-344">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-345">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-345">The name of the server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="0b2f4-346">Der Name des empfohlenen elastischen Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-346">The name of the recommended elastic pool to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-347">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-347">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-348">Gibt eine Liste von Datenbanken in einem empfohlenen Pool für elastische Datenbanken zurück</span><span class="sxs-lookup"><span data-stu-id="0b2f4-348">Returns a list of databases inside a recommented elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt; ListByServer (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string expand = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt; ListByServer(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string expand, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, Optional expand As String = null, Optional filter As String = null) As IEnumerable(Of Database)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListByServer (operations, resourceGroupName, serverName, expand, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-349">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-349">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-350">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-350">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-351">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-351">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-352">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-352">The name of the server.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="0b2f4-353">Eine durch Trennzeichen getrennte Liste von untergeordneten Objekten in der Antwort zu erweitern.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-353">A comma separated list of child objects to expand in the response.</span></span> <span data-ttu-id="0b2f4-354">Möglichen Eigenschaften: ServiceTierAdvisors TransparentDataEncryption.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-354">Possible properties: serviceTierAdvisors, transparentDataEncryption.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="0b2f4-355">Ein OData-Filterausdruck, der eine Teilmenge der Datenbanken zurückzugebenden beschreibt.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-355">An OData filter expression that describes a subset of databases to return.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-356">Gibt eine Liste der Datenbanken auf einem Server zurück</span><span class="sxs-lookup"><span data-stu-id="0b2f4-356">Returns a list of databases in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string expand = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string expand, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, expand, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;ListByServerAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-357">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-357">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-358">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-358">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-359">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-359">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-360">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-360">The name of the server.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="0b2f4-361">Eine durch Trennzeichen getrennte Liste von untergeordneten Objekten in der Antwort zu erweitern.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-361">A comma separated list of child objects to expand in the response.</span></span> <span data-ttu-id="0b2f4-362">Möglichen Eigenschaften: ServiceTierAdvisors TransparentDataEncryption.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-362">Possible properties: serviceTierAdvisors, transparentDataEncryption.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="0b2f4-363">Ein OData-Filterausdruck, der eine Teilmenge der Datenbanken zurückzugebenden beschreibt.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-363">An OData filter expression that describes a subset of databases to return.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-364">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-364">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-365">Gibt eine Liste der Datenbanken auf einem Server zurück</span><span class="sxs-lookup"><span data-stu-id="0b2f4-365">Returns a list of databases in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitions">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt; ListMetricDefinitions (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt; ListMetricDefinitions(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListMetricDefinitions(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricDefinitions (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String) As IEnumerable(Of MetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitions : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListMetricDefinitions (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-366">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-366">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-367">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-367">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-368">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-368">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-369">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-369">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-370">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-370">The name of the database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-371">Gibt Datenbank metrikdefinitionen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-371">Returns database metric definitions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;&gt; ListMetricDefinitionsAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;&gt; ListMetricDefinitionsAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListMetricDefinitionsAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitionsAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListMetricDefinitionsAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;ListMetricDefinitionsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-372">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-372">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-373">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-373">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-374">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-374">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-375">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-375">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-376">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-376">The name of the database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-377">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-377">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-378">Gibt Datenbank metrikdefinitionen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-378">Returns database metric definitions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt; ListMetrics (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.Metric&gt; ListMetrics(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListMetrics(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetrics (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String, filter As String) As IEnumerable(Of Metric)" />
      <MemberSignature Language="F#" Value="static member ListMetrics : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListMetrics (operations, resourceGroupName, serverName, databaseName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-379">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-379">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-380">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-380">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-381">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-381">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-382">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-382">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-383">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-383">The name of the database.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="0b2f4-384">Ein OData-Filterausdruck, der eine Teilmenge der zurückzugebenden Metriken beschreibt.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-384">An OData filter expression that describes a subset of metrics to return.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-385">Gibt Datenbank Metriken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-385">Returns database metrics.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string filter, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.Metric&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ListMetricsAsync (operations, resourceGroupName, serverName, databaseName, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;ListMetricsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-386">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-386">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-387">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-387">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-388">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-388">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-389">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-389">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-390">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-390">The name of the database.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="0b2f4-391">Ein OData-Filterausdruck, der eine Teilmenge der zurückzugebenden Metriken beschreibt.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-391">An OData filter expression that describes a subset of metrics to return.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-392">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-392">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-393">Gibt Datenbank Metriken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-393">Returns database metrics.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pause">
      <MemberSignature Language="C#" Value="public static void Pause (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Pause(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.Pause(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Pause (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String)" />
      <MemberSignature Language="F#" Value="static member Pause : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.Pause (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-394">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-394">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-395">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-395">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-396">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-396">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-397">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-397">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-398">Der Name des Datawarehouse anhalten.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-398">The name of the data warehouse to pause.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-399">Hält ein Datawarehouse.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-399">Pauses a data warehouse.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PauseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PauseAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PauseAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.PauseAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PauseAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.PauseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;PauseAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-400">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-400">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-401">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-401">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-402">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-402">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-403">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-403">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-404">Der Name des Datawarehouse anhalten.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-404">The name of the data warehouse to pause.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-405">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-405">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-406">Hält ein Datawarehouse.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-406">Pauses a data warehouse.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rename">
      <MemberSignature Language="C#" Value="public static void Rename (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Rename(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.Rename(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Rename (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As ResourceMoveDefinition)" />
      <MemberSignature Language="F#" Value="static member Rename : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition -&gt; unit" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.Rename (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-407">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-407">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-408">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-408">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-409">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-409">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-410">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-410">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-411">Der Name der Datenbank umbenannt.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-411">The name of the database to rename.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-412">Die Ressource verschieben Definition für diese Datenbank umbenennen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-412">The resource move definition for renaming this database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-413">Benennt eine Datenbank an.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-413">Renames a database.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RenameAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RenameAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.RenameAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RenameAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.RenameAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;RenameAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-414">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-414">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-415">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-415">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-416">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-416">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-417">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-417">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-418">Der Name der Datenbank umbenannt.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-418">The name of the database to rename.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-419">Die Ressource verschieben Definition für diese Datenbank umbenennen.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-419">The resource move definition for renaming this database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-420">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-420">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-421">Benennt eine Datenbank an.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-421">Renames a database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resume">
      <MemberSignature Language="C#" Value="public static void Resume (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Resume(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.Resume(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Resume (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String)" />
      <MemberSignature Language="F#" Value="static member Resume : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.Resume (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-422">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-422">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-423">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-423">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-424">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-424">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-425">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-425">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-426">Der Name des Datawarehouse fortgesetzt.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-426">The name of the data warehouse to resume.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-427">Wird ein Datawarehouse fortgesetzt.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-427">Resumes a data warehouse.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResumeAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResumeAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ResumeAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResumeAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.ResumeAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;ResumeAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-428">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-428">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-429">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-429">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-430">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-430">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-431">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-431">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-432">Der Name des Datawarehouse fortgesetzt.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-432">The name of the data warehouse to resume.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-433">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-433">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-434">Wird ein Datawarehouse fortgesetzt.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-434">Resumes a data warehouse.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Database Update (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.DatabaseUpdate parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Database Update(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.DatabaseUpdate parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.Update(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DatabaseUpdate)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As DatabaseUpdate) As Database" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.DatabaseUpdate -&gt; Microsoft.Azure.Management.Sql.Models.Database" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.Update (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Database</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-435">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-435">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-436">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-436">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-437">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-437">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-438">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-438">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-439">Der Name der Datenbank aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-439">The name of the database to be updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-440">Die erforderlichen Parameter für eine Datenbank aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-440">The required parameters for updating a database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-441">Aktualisiert eine vorhandene Datenbank</span><span class="sxs-lookup"><span data-stu-id="0b2f4-441">Updates an existing database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt; UpdateAsync (this Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.DatabaseUpdate parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt; UpdateAsync(class Microsoft.Azure.Management.Sql.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.DatabaseUpdate parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Sql.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DatabaseUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Sql.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.DatabaseUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;" Usage="Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions.UpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabasesOperationsExtensions/&lt;UpdateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0b2f4-442">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-442">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0b2f4-443">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-443">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0b2f4-444">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-444">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0b2f4-445">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-445">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0b2f4-446">Der Name der Datenbank aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-446">The name of the database to be updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0b2f4-447">Die erforderlichen Parameter für eine Datenbank aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-447">The required parameters for updating a database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0b2f4-448">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0b2f4-448">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0b2f4-449">Aktualisiert eine vorhandene Datenbank</span><span class="sxs-lookup"><span data-stu-id="0b2f4-449">Updates an existing database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>