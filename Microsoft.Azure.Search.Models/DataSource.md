<Type Name="DataSource" FullName="Microsoft.Azure.Search.Models.DataSource">
  <TypeSignature Language="C#" Value="public class DataSource : Microsoft.Azure.Search.Models.IResourceWithETag" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataSource extends System.Object implements class Microsoft.Azure.Search.Models.IResourceWithETag" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class DataSource&#xA;Implements IResourceWithETag" />
  <TypeSignature Language="F#" Value="type DataSource = class&#xA;    interface IResourceWithETag" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Search.Models.IResourceWithETag</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="09964-101">Stellt eine Datenquellendefinition in Azure Search dar, mit dem ein Indexer konfiguriert werden kann.</span><span class="sxs-lookup"><span data-stu-id="09964-101">Represents a datasource definition in Azure Search, which can be used to configure an indexer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="09964-102">Initialisiert eine neue Instanz der DataSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="09964-102">Initializes a new instance of the DataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSource (string name, Microsoft.Azure.Search.Models.DataSourceType type, Microsoft.Azure.Search.Models.DataSourceCredentials credentials, Microsoft.Azure.Search.Models.DataContainer container, string description = null, Microsoft.Azure.Search.Models.DataChangeDetectionPolicy dataChangeDetectionPolicy = null, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy dataDeletionDetectionPolicy = null, string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Search.Models.DataSourceType type, class Microsoft.Azure.Search.Models.DataSourceCredentials credentials, class Microsoft.Azure.Search.Models.DataContainer container, string description, class Microsoft.Azure.Search.Models.DataChangeDetectionPolicy dataChangeDetectionPolicy, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy dataDeletionDetectionPolicy, string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.#ctor(System.String,Microsoft.Azure.Search.Models.DataSourceType,Microsoft.Azure.Search.Models.DataSourceCredentials,Microsoft.Azure.Search.Models.DataContainer,System.String,Microsoft.Azure.Search.Models.DataChangeDetectionPolicy,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.DataSource : string * Microsoft.Azure.Search.Models.DataSourceType * Microsoft.Azure.Search.Models.DataSourceCredentials * Microsoft.Azure.Search.Models.DataContainer * string * Microsoft.Azure.Search.Models.DataChangeDetectionPolicy * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="new Microsoft.Azure.Search.Models.DataSource (name, type, credentials, container, description, dataChangeDetectionPolicy, dataDeletionDetectionPolicy, eTag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Search.Models.DataSourceType" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Search.Models.DataSourceCredentials" />
        <Parameter Name="container" Type="Microsoft.Azure.Search.Models.DataContainer" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dataChangeDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataChangeDetectionPolicy" />
        <Parameter Name="dataDeletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="09964-103">Der Name der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-103">The name of the datasource.</span></span></param>
        <param name="type"><span data-ttu-id="09964-104">Der Typ der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-104">The type of the datasource.</span></span></param>
        <param name="credentials"><span data-ttu-id="09964-105">Anmeldeinformationen für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-105">Credentials for the datasource.</span></span></param>
        <param name="container"><span data-ttu-id="09964-106">Der Datencontainer für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-106">The data container for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="09964-107">Die Beschreibung der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-107">The description of the datasource.</span></span></param>
        <param name="dataChangeDetectionPolicy"><span data-ttu-id="09964-108">Die Datenänderung Erkennungsrichtlinie für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-108">The data change detection policy for the datasource.</span></span></param>
        <param name="dataDeletionDetectionPolicy"><span data-ttu-id="09964-109">Die Erkennungsrichtlinie für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-109">The data deletion detection policy for the datasource.</span></span></param>
        <param name="eTag"><span data-ttu-id="09964-110">Das ETag der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-110">The ETag of the DataSource.</span></span></param>
        <summary>
            <span data-ttu-id="09964-111">Initialisiert eine neue Instanz der DataSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="09964-111">Initializes a new instance of the DataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureBlobStorage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureBlobStorage (string name, string storageConnectionString, string containerName, string pathPrefix = null, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureBlobStorage(string name, string storageConnectionString, string containerName, string pathPrefix, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureBlobStorage(System.String,System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureBlobStorage (name As String, storageConnectionString As String, containerName As String, Optional pathPrefix As String = null, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureBlobStorage : string * string * string * string * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureBlobStorage (name, storageConnectionString, containerName, pathPrefix, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="pathPrefix" Type="System.String" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="09964-112">Der Name der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-112">The name of the datasource.</span></span></param>
        <param name="storageConnectionString"><span data-ttu-id="09964-113">Die Verbindungszeichenfolge für das Azure-Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="09964-113">The connection string for the Azure Storage account.</span></span> <span data-ttu-id="09964-114">Er muss folgendem Format entsprechen: "DefaultEndpointsProtocol = Https; AccountName = [Ihr Speicherkonto]; AccountKey = [Ihr kontoschlüssel]; " Beachten Sie, dass HTTPS erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="09964-114">It must follow this format: "DefaultEndpointsProtocol=https;AccountName=[your storage account];AccountKey=[your account key];" Note that HTTPS is required.</span></span></param>
        <param name="containerName"><span data-ttu-id="09964-115">Der Name des Containers aus dem Blobs gelesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="09964-115">The name of the container from which to read blobs.</span></span></param>
        <param name="pathPrefix"><span data-ttu-id="09964-116">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-116">Optional.</span></span> <span data-ttu-id="09964-117">Wenn angegeben, umfasst die Datenquelle nur Blobs mit Namen mit diesem Präfix beginnen.</span><span class="sxs-lookup"><span data-stu-id="09964-117">If specified, the datasource will include only blobs with names starting with this prefix.</span></span> <span data-ttu-id="09964-118">Dies ist hilfreich, wenn Blobs z. B. in "virtuelle Ordner" organisiert sind.</span><span class="sxs-lookup"><span data-stu-id="09964-118">This is useful when blobs are organized into "virtual folders", for example.</span></span></param>
        <param name="deletionDetectionPolicy"><span data-ttu-id="09964-119">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-119">Optional.</span></span> <span data-ttu-id="09964-120">Die Erkennungsrichtlinie für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-120">The data deletion detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="09964-121">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-121">Optional.</span></span> <span data-ttu-id="09964-122">Beschreibung der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-122">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="09964-123">Erstellt eine neue Datenquelle für die Verbindung mit einem Azure-Blob-Container.</span><span class="sxs-lookup"><span data-stu-id="09964-123">Creates a new DataSource to connect to an Azure Blob container.</span></span>
            </summary>
        <returns><span data-ttu-id="09964-124">Eine neue Datenquelleninstanz.</span><span class="sxs-lookup"><span data-stu-id="09964-124">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureSql">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureSql (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.DataChangeDetectionPolicy changeDetectionPolicy, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureSql(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.DataChangeDetectionPolicy changeDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureSql(System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataChangeDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureSql (name As String, sqlConnectionString As String, tableOrViewName As String, changeDetectionPolicy As DataChangeDetectionPolicy, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureSql : string * string * string * Microsoft.Azure.Search.Models.DataChangeDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureSql (name, sqlConnectionString, tableOrViewName, changeDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="changeDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataChangeDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="09964-125">Der Name der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-125">The name of the datasource.</span></span></param>
        <param name="sqlConnectionString"><span data-ttu-id="09964-126">Die Verbindungszeichenfolge für die Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="09964-126">The connection string for the Azure SQL database.</span></span></param>
        <param name="tableOrViewName"><span data-ttu-id="09964-127">Der Name der Tabelle oder Sicht aus dem Zeilen gelesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="09964-127">The name of the table or view from which to read rows.</span></span></param>
        <param name="changeDetectionPolicy"><span data-ttu-id="09964-128">Die Erkennungsrichtlinie für für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-128">The change detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="09964-129">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-129">Optional.</span></span> <span data-ttu-id="09964-130">Beschreibung der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-130">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="09964-131">Erstellt eine neue Datenquelle mit änderungserkennung aktiviert die Verbindung mit einer Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="09964-131">Creates a new DataSource to connect to an Azure SQL database with change detection enabled.</span></span>
            </summary>
        <returns><span data-ttu-id="09964-132">Eine neue Datenquelleninstanz.</span><span class="sxs-lookup"><span data-stu-id="09964-132">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureSql">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureSql (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureSql(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureSql(System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureSql (name As String, sqlConnectionString As String, tableOrViewName As String, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureSql : string * string * string * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureSql (name, sqlConnectionString, tableOrViewName, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="09964-133">Der Name der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-133">The name of the datasource.</span></span></param>
        <param name="sqlConnectionString"><span data-ttu-id="09964-134">Die Verbindungszeichenfolge für die Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="09964-134">The connection string for the Azure SQL database.</span></span></param>
        <param name="tableOrViewName"><span data-ttu-id="09964-135">Der Name der Tabelle oder Sicht aus dem Zeilen gelesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="09964-135">The name of the table or view from which to read rows.</span></span></param>
        <param name="deletionDetectionPolicy"><span data-ttu-id="09964-136">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-136">Optional.</span></span> <span data-ttu-id="09964-137">Die Erkennungsrichtlinie für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-137">The data deletion detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="09964-138">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-138">Optional.</span></span> <span data-ttu-id="09964-139">Beschreibung der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-139">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="09964-140">Erstellt eine neue Datenquelle für die Verbindung mit einer Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="09964-140">Creates a new DataSource to connect to an Azure SQL database.</span></span>
            </summary>
        <returns><span data-ttu-id="09964-141">Eine neue Datenquelleninstanz.</span><span class="sxs-lookup"><span data-stu-id="09964-141">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureSql">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureSql (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy changeDetectionPolicy, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureSql(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy changeDetectionPolicy, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureSql(System.String,System.String,System.String,Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureSql (name As String, sqlConnectionString As String, tableOrViewName As String, changeDetectionPolicy As HighWaterMarkChangeDetectionPolicy, deletionDetectionPolicy As DataDeletionDetectionPolicy, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureSql : string * string * string * Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureSql (name, sqlConnectionString, tableOrViewName, changeDetectionPolicy, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="changeDetectionPolicy" Type="Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="09964-142">Der Name der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-142">The name of the datasource.</span></span></param>
        <param name="sqlConnectionString"><span data-ttu-id="09964-143">Die Verbindungszeichenfolge für die Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="09964-143">The connection string for the Azure SQL database.</span></span></param>
        <param name="tableOrViewName"><span data-ttu-id="09964-144">Der Name der Tabelle oder Sicht aus dem Zeilen gelesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="09964-144">The name of the table or view from which to read rows.</span></span></param>
        <param name="changeDetectionPolicy"><span data-ttu-id="09964-145">Die Erkennungsrichtlinie für für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-145">The change detection policy for the datasource.</span></span> <span data-ttu-id="09964-146">Beachten Sie, nur das Kontingent Erkennung zu ändern ist für SQL Azure zulässig, wenn löschen Erkennung aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="09964-146">Note that only high watermark change detection is allowed for Azure SQL when deletion detection is enabled.</span></span></param>
        <param name="deletionDetectionPolicy"><span data-ttu-id="09964-147">Die Erkennungsrichtlinie für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-147">The data deletion detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="09964-148">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-148">Optional.</span></span> <span data-ttu-id="09964-149">Beschreibung der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-149">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="09964-150">Erstellt eine neue Datenquelle für die Verbindung mit einer Azure SQL-Datenbank mit änderungserkennung und Erkennung des Löschvorgänge aktiviert.</span><span class="sxs-lookup"><span data-stu-id="09964-150">Creates a new DataSource to connect to an Azure SQL database with change detection and deletion detection enabled.</span></span>
            </summary>
        <returns><span data-ttu-id="09964-151">Eine neue Datenquelleninstanz.</span><span class="sxs-lookup"><span data-stu-id="09964-151">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableStorage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureTableStorage (string name, string storageConnectionString, string tableName, string query = null, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureTableStorage(string name, string storageConnectionString, string tableName, string query, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureTableStorage(System.String,System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureTableStorage (name As String, storageConnectionString As String, tableName As String, Optional query As String = null, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureTableStorage : string * string * string * string * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureTableStorage (name, storageConnectionString, tableName, query, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="09964-152">Der Name der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-152">The name of the datasource.</span></span></param>
        <param name="storageConnectionString"><span data-ttu-id="09964-153">Die Verbindungszeichenfolge für das Azure-Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="09964-153">The connection string for the Azure Storage account.</span></span> <span data-ttu-id="09964-154">Er muss folgendem Format entsprechen: "DefaultEndpointsProtocol = Https; AccountName = [Ihr Speicherkonto]; AccountKey = [Ihr kontoschlüssel]; " Beachten Sie, dass HTTPS erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="09964-154">It must follow this format: "DefaultEndpointsProtocol=https;AccountName=[your storage account];AccountKey=[your account key];" Note that HTTPS is required.</span></span></param>
        <param name="tableName"><span data-ttu-id="09964-155">Der Name der Tabelle, aus der gelesenen Zeilen.</span><span class="sxs-lookup"><span data-stu-id="09964-155">The name of the table from which to read rows.</span></span></param>
        <param name="query"><span data-ttu-id="09964-156">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-156">Optional.</span></span> <span data-ttu-id="09964-157">Eine Abfrage, die beim Lesen von Zeilen in der Tabelle angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="09964-157">A query that is applied to the table when reading rows.</span></span></param>
        <param name="deletionDetectionPolicy"><span data-ttu-id="09964-158">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-158">Optional.</span></span> <span data-ttu-id="09964-159">Die Erkennungsrichtlinie für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-159">The data deletion detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="09964-160">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-160">Optional.</span></span> <span data-ttu-id="09964-161">Beschreibung der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-161">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="09964-162">Erstellt eine neue Datenquelle für die Verbindung mit einer Azure-Tabelle.</span><span class="sxs-lookup"><span data-stu-id="09964-162">Creates a new DataSource to connect to an Azure Table.</span></span>
            </summary>
        <returns><span data-ttu-id="09964-163">Eine neue Datenquelleninstanz.</span><span class="sxs-lookup"><span data-stu-id="09964-163">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataContainer Container { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataContainer Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Container" />
      <MemberSignature Language="VB.NET" Value="Public Property Container As DataContainer" />
      <MemberSignature Language="F#" Value="member this.Container : Microsoft.Azure.Search.Models.DataContainer with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="container")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataContainer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09964-164">Ruft ab oder legt den Datencontainer für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-164">Gets or sets the data container for the datasource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataSourceCredentials Credentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataSourceCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public Property Credentials As DataSourceCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.Search.Models.DataSourceCredentials with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="credentials")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSourceCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09964-165">Ruft ab oder legt die Anmeldeinformationen für die Datenquelle fest.</span><span class="sxs-lookup"><span data-stu-id="09964-165">Gets or sets credentials for the datasource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataChangeDetectionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataChangeDetectionPolicy DataChangeDetectionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataChangeDetectionPolicy DataChangeDetectionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.DataChangeDetectionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property DataChangeDetectionPolicy As DataChangeDetectionPolicy" />
      <MemberSignature Language="F#" Value="member this.DataChangeDetectionPolicy : Microsoft.Azure.Search.Models.DataChangeDetectionPolicy with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.DataChangeDetectionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataChangeDetectionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataChangeDetectionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09964-166">Ruft ab oder legt die Erkennungsrichtlinie für für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-166">Gets or sets the data change detection policy for the datasource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDeletionDetectionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy DataDeletionDetectionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy DataDeletionDetectionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.DataDeletionDetectionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDeletionDetectionPolicy As DataDeletionDetectionPolicy" />
      <MemberSignature Language="F#" Value="member this.DataDeletionDetectionPolicy : Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.DataDeletionDetectionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataDeletionDetectionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09964-167">Ruft ab oder legt die Erkennungsrichtlinie für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-167">Gets or sets the data deletion detection policy for the datasource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09964-168">Ruft ab oder legt die Beschreibung der Datenquelle fest.</span><span class="sxs-lookup"><span data-stu-id="09964-168">Gets or sets the description of the datasource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DocumentDb">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource DocumentDb (string name, string documentDbConnectionString, string collectionName, string query = null, bool useChangeDetection = true, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource DocumentDb(string name, string documentDbConnectionString, string collectionName, string query, bool useChangeDetection, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.DocumentDb(System.String,System.String,System.String,System.String,System.Boolean,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DocumentDb (name As String, documentDbConnectionString As String, collectionName As String, Optional query As String = null, Optional useChangeDetection As Boolean = true, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member DocumentDb : string * string * string * string * bool * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.DocumentDb (name, documentDbConnectionString, collectionName, query, useChangeDetection, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="documentDbConnectionString" Type="System.String" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="useChangeDetection" Type="System.Boolean" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="09964-169">Der Name der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-169">The name of the datasource.</span></span></param>
        <param name="documentDbConnectionString"><span data-ttu-id="09964-170">Die Verbindungszeichenfolge für die DocumentDb-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="09964-170">The connection string for the DocumentDb database.</span></span> <span data-ttu-id="09964-171">Er muss folgendem Format entsprechen: "AccountName | AccountEndpoint = [Ihr Kontoname oder der Endpunkt]; AccountKey = [Ihr kontoschlüssel]; Database = [Ihre Datenbankname] "</span><span class="sxs-lookup"><span data-stu-id="09964-171">It must follow this format: "AccountName|AccountEndpoint=[your account name or endpoint];AccountKey=[your account key];Database=[your database name]"</span></span></param>
        <param name="collectionName"><span data-ttu-id="09964-172">Der Name der Auflistung, um Dokumente zu lesen.</span><span class="sxs-lookup"><span data-stu-id="09964-172">The name of the collection from which to read documents.</span></span></param>
        <param name="query"><span data-ttu-id="09964-173">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-173">Optional.</span></span> <span data-ttu-id="09964-174">Eine Abfrage, die auf die Auflistung angewendet wird, wenn Dokumente gelesen.</span><span class="sxs-lookup"><span data-stu-id="09964-174">A query that is applied to the collection when reading documents.</span></span></param>
        <param name="useChangeDetection"><span data-ttu-id="09964-175">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-175">Optional.</span></span> <span data-ttu-id="09964-176">Gibt an, ob änderungserkennung verwendet beim indizieren.</span><span class="sxs-lookup"><span data-stu-id="09964-176">Indicates whether to use change detection when indexing.</span></span> <span data-ttu-id="09964-177">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="09964-177">Default is true.</span></span></param>
        <param name="deletionDetectionPolicy"><span data-ttu-id="09964-178">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-178">Optional.</span></span> <span data-ttu-id="09964-179">Die Erkennungsrichtlinie für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-179">The data deletion detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="09964-180">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-180">Optional.</span></span> <span data-ttu-id="09964-181">Beschreibung der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-181">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="09964-182">Erstellt eine neue Datenquelle für die Verbindung mit DocumentDb-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="09964-182">Creates a new DataSource to connect to a DocumentDb database.</span></span>
            </summary>
        <returns><span data-ttu-id="09964-183">Eine neue Datenquelleninstanz.</span><span class="sxs-lookup"><span data-stu-id="09964-183">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="@odata.etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09964-184">Ruft ab oder legt das ETag der Datenquelle fest.</span><span class="sxs-lookup"><span data-stu-id="09964-184">Gets or sets the ETag of the DataSource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09964-185">Ruft ab oder legt den Namen der Datenquelle fest.</span><span class="sxs-lookup"><span data-stu-id="09964-185">Gets or sets the name of the datasource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerOnAzureVM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.DataChangeDetectionPolicy changeDetectionPolicy, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.DataChangeDetectionPolicy changeDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM(System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataChangeDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlServerOnAzureVM (name As String, sqlConnectionString As String, tableOrViewName As String, changeDetectionPolicy As DataChangeDetectionPolicy, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member SqlServerOnAzureVM : string * string * string * Microsoft.Azure.Search.Models.DataChangeDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM (name, sqlConnectionString, tableOrViewName, changeDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="changeDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataChangeDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="09964-186">Der Name der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-186">The name of the datasource.</span></span></param>
        <param name="sqlConnectionString"><span data-ttu-id="09964-187">Die Verbindungszeichenfolge für die SQL Server-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="09964-187">The connection string for the SQL Server database.</span></span></param>
        <param name="tableOrViewName"><span data-ttu-id="09964-188">Der Name der Tabelle oder Sicht aus dem Zeilen gelesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="09964-188">The name of the table or view from which to read rows.</span></span></param>
        <param name="changeDetectionPolicy"><span data-ttu-id="09964-189">Die Erkennungsrichtlinie für für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-189">The change detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="09964-190">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-190">Optional.</span></span> <span data-ttu-id="09964-191">Beschreibung der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-191">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="09964-192">Erstellt eine neue Datenquelle mit änderungserkennung aktiviert die Verbindung mit einer VM-gehostete SQL Server-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="09964-192">Creates a new DataSource to connect to a VM-hosted SQL Server database with change detection enabled.</span></span>
            </summary>
        <returns><span data-ttu-id="09964-193">Eine neue Datenquelleninstanz.</span><span class="sxs-lookup"><span data-stu-id="09964-193">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerOnAzureVM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM(System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlServerOnAzureVM (name As String, sqlConnectionString As String, tableOrViewName As String, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member SqlServerOnAzureVM : string * string * string * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM (name, sqlConnectionString, tableOrViewName, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="09964-194">Der Name der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-194">The name of the datasource.</span></span></param>
        <param name="sqlConnectionString"><span data-ttu-id="09964-195">Die Verbindungszeichenfolge für die SQL Server-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="09964-195">The connection string for the SQL Server database.</span></span></param>
        <param name="tableOrViewName"><span data-ttu-id="09964-196">Der Name der Tabelle oder Sicht aus dem Zeilen gelesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="09964-196">The name of the table or view from which to read rows.</span></span></param>
        <param name="deletionDetectionPolicy"><span data-ttu-id="09964-197">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-197">Optional.</span></span> <span data-ttu-id="09964-198">Die Erkennungsrichtlinie für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-198">The data deletion detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="09964-199">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-199">Optional.</span></span> <span data-ttu-id="09964-200">Beschreibung der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-200">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="09964-201">Erstellt eine neue Datenquelle für die Verbindung mit einer VM-gehostete SQL Server-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="09964-201">Creates a new DataSource to connect to a VM-hosted SQL Server database.</span></span>
            </summary>
        <returns><span data-ttu-id="09964-202">Eine neue Datenquelleninstanz.</span><span class="sxs-lookup"><span data-stu-id="09964-202">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerOnAzureVM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy changeDetectionPolicy, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy changeDetectionPolicy, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM(System.String,System.String,System.String,Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlServerOnAzureVM (name As String, sqlConnectionString As String, tableOrViewName As String, changeDetectionPolicy As HighWaterMarkChangeDetectionPolicy, deletionDetectionPolicy As DataDeletionDetectionPolicy, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member SqlServerOnAzureVM : string * string * string * Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM (name, sqlConnectionString, tableOrViewName, changeDetectionPolicy, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="changeDetectionPolicy" Type="Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="09964-203">Der Name der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-203">The name of the datasource.</span></span></param>
        <param name="sqlConnectionString"><span data-ttu-id="09964-204">Die Verbindungszeichenfolge für die SQL Server-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="09964-204">The connection string for the SQL Server database.</span></span></param>
        <param name="tableOrViewName"><span data-ttu-id="09964-205">Der Name der Tabelle oder Sicht aus dem Zeilen gelesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="09964-205">The name of the table or view from which to read rows.</span></span></param>
        <param name="changeDetectionPolicy"><span data-ttu-id="09964-206">Die Erkennungsrichtlinie für für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-206">The change detection policy for the datasource.</span></span> <span data-ttu-id="09964-207">Beachten Sie, nur das Kontingent Erkennung zu ändern ist für SQL Server zulässig, wenn löschen Erkennung aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="09964-207">Note that only high watermark change detection is allowed for SQL Server when deletion detection is enabled.</span></span></param>
        <param name="deletionDetectionPolicy"><span data-ttu-id="09964-208">Die Erkennungsrichtlinie für die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-208">The data deletion detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="09964-209">Optional.</span><span class="sxs-lookup"><span data-stu-id="09964-209">Optional.</span></span> <span data-ttu-id="09964-210">Beschreibung der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="09964-210">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="09964-211">Erstellt eine neue Datenquelle für die Verbindung zu einer VM-gehostete SQL Server-Datenbank mit änderungserkennung und Löschung konflikterkennung zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="09964-211">Creates a new DataSource to connect to a VM-hosted SQL Server database with change detection and deletion detection enabled.</span></span>
            </summary>
        <returns><span data-ttu-id="09964-212">Eine neue Datenquelleninstanz.</span><span class="sxs-lookup"><span data-stu-id="09964-212">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataSourceType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataSourceType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As DataSourceType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Search.Models.DataSourceType with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSourceType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09964-213">Ruft ab oder legt den Typ der Datenquelle fest.</span><span class="sxs-lookup"><span data-stu-id="09964-213">Gets or sets the type of the datasource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataSource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="09964-214">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="09964-214">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="09964-215">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="09964-215">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>