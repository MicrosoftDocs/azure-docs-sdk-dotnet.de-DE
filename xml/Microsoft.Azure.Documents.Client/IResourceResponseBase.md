<Type Name="IResourceResponseBase" FullName="Microsoft.Azure.Documents.Client.IResourceResponseBase">
  <TypeSignature Language="C#" Value="public interface IResourceResponseBase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IResourceResponseBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.IResourceResponseBase" />
  <TypeSignature Language="VB.NET" Value="Public Interface IResourceResponseBase" />
  <TypeSignature Language="F#" Value="type IResourceResponseBase = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6a984-101">Stellt dar, die bestimmte nicht-Ressourcendienst Antwortheader zurückgegeben, die für jede Anforderung in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="6a984-101">Represents the non-resource specific service response headers returned by any request in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="6a984-102">Schnittstelle zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-102">Interface exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="ActivityId">
      <MemberSignature Language="C#" Value="public string ActivityId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.ActivityId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityId As String" />
      <MemberSignature Language="F#" Value="member this.ActivityId : string" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.ActivityId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-103">Ruft die Aktivitäts-ID für die Anforderung ab.</span><span class="sxs-lookup"><span data-stu-id="6a984-103">Gets the activity ID for the request.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-104">Die Aktivitäts-ID für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="6a984-104">The activity ID for the request.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-105">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-105">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionQuota">
      <MemberSignature Language="C#" Value="public long CollectionQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionQuota As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-106">Ruft den maximalen Kontingent für sammlungsressourcen innerhalb eines Kontos ab.</span><span class="sxs-lookup"><span data-stu-id="6a984-106">Gets the maximum quota for collection resources within an account.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-107">Das Kontingent für das Konto.</span><span class="sxs-lookup"><span data-stu-id="6a984-107">The maximum quota for the account.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-108">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-108">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionSizeQuota">
      <MemberSignature Language="C#" Value="public long CollectionSizeQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionSizeQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionSizeQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionSizeQuota As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionSizeQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionSizeQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-109">Maximale Größe einer Auflistung in Kilobyte.</span><span class="sxs-lookup"><span data-stu-id="6a984-109">Maximum size of a collection in kilobytes.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-110">Kontingent in KB.</span><span class="sxs-lookup"><span data-stu-id="6a984-110">Quota in kilobytes.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-111">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-111">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionSizeUsage">
      <MemberSignature Language="C#" Value="public long CollectionSizeUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionSizeUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionSizeUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionSizeUsage As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionSizeUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionSizeUsage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-112">Aktuelle Größe der Auflistung in Kilobyte.</span><span class="sxs-lookup"><span data-stu-id="6a984-112">Current size of a collection in kilobytes.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="6a984-113">Größe der aktuellen Auflistung in Kilobyte.</span><span class="sxs-lookup"><span data-stu-id="6a984-113">Current collection size in kilobytes.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-114">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-114">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionUsage">
      <MemberSignature Language="C#" Value="public long CollectionUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionUsage As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionUsage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-115">Die aktuelle Anzahl der sammlungsressourcen im Konto.</span><span class="sxs-lookup"><span data-stu-id="6a984-115">The current number of collection resources within the account.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-116">Die Anzahl der Sammlungen.</span><span class="sxs-lookup"><span data-stu-id="6a984-116">The number of collections.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-117">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-117">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLocation">
      <MemberSignature Language="C#" Value="public string ContentLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.ContentLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContentLocation As String" />
      <MemberSignature Language="F#" Value="member this.ContentLocation : string" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.ContentLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-118">Der Inhalt übergeordneten Speicherort, z. B. Dbs/Foo/colls/Leiste</span><span class="sxs-lookup"><span data-stu-id="6a984-118">The content parent location, for example, dbs/foo/colls/bar</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6a984-119">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-119">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentResourceQuotaUsage">
      <MemberSignature Language="C#" Value="public string CurrentResourceQuotaUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentResourceQuotaUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.CurrentResourceQuotaUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentResourceQuotaUsage As String" />
      <MemberSignature Language="F#" Value="member this.CurrentResourceQuotaUsage : string" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.CurrentResourceQuotaUsage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-120">Ruft die aktuelle Größe der diese Entität ab.</span><span class="sxs-lookup"><span data-stu-id="6a984-120">Gets the current size of this entity.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-121">Die aktuelle Größe für diese Entität.</span><span class="sxs-lookup"><span data-stu-id="6a984-121">The current size for this entity.</span></span> <span data-ttu-id="6a984-122">Gemessen in KB für Dokumentressourcen und für andere Ressourcen zählt.</span><span class="sxs-lookup"><span data-stu-id="6a984-122">Measured in kilobytes for document resources and in counts for other resources.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-123">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-123">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseQuota">
      <MemberSignature Language="C#" Value="public long DatabaseQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DatabaseQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.DatabaseQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseQuota As Long" />
      <MemberSignature Language="F#" Value="member this.DatabaseQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.DatabaseQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-124">Ruft den maximalen Kontingent für Database-Ressourcen im Konto ab.</span><span class="sxs-lookup"><span data-stu-id="6a984-124">Gets the maximum quota for database resources within the account.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="6a984-125">Das Kontingent für das Konto.</span><span class="sxs-lookup"><span data-stu-id="6a984-125">The maximum quota for the account.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-126">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-126">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseUsage">
      <MemberSignature Language="C#" Value="public long DatabaseUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DatabaseUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.DatabaseUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseUsage As Long" />
      <MemberSignature Language="F#" Value="member this.DatabaseUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.DatabaseUsage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-127">Die aktuelle Anzahl von Datenbankressourcen im Konto.</span><span class="sxs-lookup"><span data-stu-id="6a984-127">The current number of database resources within the account.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-128">Die Anzahl der Datenbanken.</span><span class="sxs-lookup"><span data-stu-id="6a984-128">The number of databases.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-129">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-129">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DocumentQuota">
      <MemberSignature Language="C#" Value="public long DocumentQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DocumentQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.DocumentQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DocumentQuota As Long" />
      <MemberSignature Language="F#" Value="member this.DocumentQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.DocumentQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-130">Maximale Größe einer Dokumente in einer Sammlung in Kilobyte.</span><span class="sxs-lookup"><span data-stu-id="6a984-130">Maximum size of a documents within a collection in kilobytes.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-131">Kontingent in KB.</span><span class="sxs-lookup"><span data-stu-id="6a984-131">Quota in kilobytes.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-132">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-132">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DocumentUsage">
      <MemberSignature Language="C#" Value="public long DocumentUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DocumentUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.DocumentUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DocumentUsage As Long" />
      <MemberSignature Language="F#" Value="member this.DocumentUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.DocumentUsage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-133">Aktuelle Größe von Dokumenten in einer Sammlung in Kilobyte.</span><span class="sxs-lookup"><span data-stu-id="6a984-133">Current size of documents within a collection in kilobytes.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="6a984-134">Aktuelle Dokumente Größe in KB.</span><span class="sxs-lookup"><span data-stu-id="6a984-134">Current documents size in kilobytes.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-135">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-135">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexTransformationProgress">
      <MemberSignature Language="C#" Value="public long IndexTransformationProgress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 IndexTransformationProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.IndexTransformationProgress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IndexTransformationProgress As Long" />
      <MemberSignature Language="F#" Value="member this.IndexTransformationProgress : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.IndexTransformationProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-136">Ruft den Status einer Index-Transformation ab, wenn eine ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="6a984-136">Gets the progress of an index transformation, if one is underway.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-137">Eine ganze Zahl zwischen 0 und 100, der Vollendungsgrad eines Transformationsprozess Index darstellt.</span><span class="sxs-lookup"><span data-stu-id="6a984-137">An integer from 0 to 100 representing percentage completion of the index transformation process.</span></span>
            <span data-ttu-id="6a984-138">Gibt-1 zurück, wenn die Index Transformation Header Status konnte nicht gefunden werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-138">Returns -1 if the index transformation progress header could not be found.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-139">Ein Index wird neu erstellt werden, wenn die IndexPolicy einer Auflistung aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="6a984-139">An index will be rebuilt when the IndexPolicy of a collection is updated.</span></span>
            <span data-ttu-id="6a984-140">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-140">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LazyIndexingProgress">
      <MemberSignature Language="C#" Value="public long LazyIndexingProgress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LazyIndexingProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.LazyIndexingProgress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LazyIndexingProgress As Long" />
      <MemberSignature Language="F#" Value="member this.LazyIndexingProgress : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.LazyIndexingProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-141">Ruft den Status der verzögerten Indizierung ab.</span><span class="sxs-lookup"><span data-stu-id="6a984-141">Gets the progress of lazy indexing.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-142">Eine ganze Zahl zwischen 0 und 100, die prozentuale Beendigung der verzögerten Indizierung darstellt.</span><span class="sxs-lookup"><span data-stu-id="6a984-142">An integer from 0 to 100 representing percentage completion of the lazy indexing process.</span></span>
            <span data-ttu-id="6a984-143">Gibt-1 zurück, wenn der verzögerten Indizierung Fortschritt-Header nicht gefunden werden kann.</span><span class="sxs-lookup"><span data-stu-id="6a984-143">Returns -1 if the lazy indexing progress header could not be found.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-144">Verzögerten Indizierung Status gilt nur für die Auflistung mit indizierungsmodus Lazy.</span><span class="sxs-lookup"><span data-stu-id="6a984-144">Lazy indexing progress only applies to the collection with indexing mode Lazy.</span></span>
            <span data-ttu-id="6a984-145">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-145">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResourceQuota">
      <MemberSignature Language="C#" Value="public string MaxResourceQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxResourceQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.MaxResourceQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResourceQuota As String" />
      <MemberSignature Language="F#" Value="member this.MaxResourceQuota : string" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.MaxResourceQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-146">Ruft die maximal zulässige Größe für diese Entität.</span><span class="sxs-lookup"><span data-stu-id="6a984-146">Gets the maximum size limit for this entity.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-147">Die maximal zulässige Größe für diese Entität.</span><span class="sxs-lookup"><span data-stu-id="6a984-147">The maximum size limit for this entity.</span></span> <span data-ttu-id="6a984-148">Gemessen in KB für Dokumentressourcen und für andere Ressourcen zählt.</span><span class="sxs-lookup"><span data-stu-id="6a984-148">Measured in kilobytes for document resources and in counts for other resources.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-149">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-149">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionQuota">
      <MemberSignature Language="C#" Value="public long PermissionQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PermissionQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.PermissionQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PermissionQuota As Long" />
      <MemberSignature Language="F#" Value="member this.PermissionQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.PermissionQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-150">Ruft den maximalen Kontingent für Berechtigung Ressourcen innerhalb eines Kontos ab.</span><span class="sxs-lookup"><span data-stu-id="6a984-150">Gets the maximum quota for permission resources within an account.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-151">Das Kontingent für das Konto.</span><span class="sxs-lookup"><span data-stu-id="6a984-151">The maximum quota for the account.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-152">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-152">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionUsage">
      <MemberSignature Language="C#" Value="public long PermissionUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PermissionUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.PermissionUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PermissionUsage As Long" />
      <MemberSignature Language="F#" Value="member this.PermissionUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.PermissionUsage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-153">Die aktuelle Anzahl der Berechtigung Ressourcen im Konto.</span><span class="sxs-lookup"><span data-stu-id="6a984-153">The current number of permission resources within the account.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="6a984-154">Die Anzahl der Berechtigungen.</span><span class="sxs-lookup"><span data-stu-id="6a984-154">The number of permissions.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-155">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-155">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestCharge">
      <MemberSignature Language="C#" Value="public double RequestCharge { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 RequestCharge" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.RequestCharge" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestCharge As Double" />
      <MemberSignature Language="F#" Value="member this.RequestCharge : double" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.RequestCharge" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-156">Ruft die Gebühr für die Anforderung für diese Anforderung ab.</span><span class="sxs-lookup"><span data-stu-id="6a984-156">Gets the request charge for this request.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-157">Die Gebühr für die Anforderung, gemessen in Reqest Einheiten.</span><span class="sxs-lookup"><span data-stu-id="6a984-157">The request charge measured in reqest units.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-158">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-158">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Specialized.NameValueCollection ResponseHeaders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Specialized.NameValueCollection ResponseHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.ResponseHeaders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseHeaders As NameValueCollection" />
      <MemberSignature Language="F#" Value="member this.ResponseHeaders : System.Collections.Specialized.NameValueCollection" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.ResponseHeaders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Specialized.NameValueCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-159">Ruft die Antwortheader ab.</span><span class="sxs-lookup"><span data-stu-id="6a984-159">Gets the response headers.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-160">Die Antwortheader.</span><span class="sxs-lookup"><span data-stu-id="6a984-160">The response headers.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-161">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-161">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseStream">
      <MemberSignature Language="C#" Value="public System.IO.Stream ResponseStream { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.IO.Stream ResponseStream" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.ResponseStream" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseStream As Stream" />
      <MemberSignature Language="F#" Value="member this.ResponseStream : System.IO.Stream" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.ResponseStream" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-162">Ruft den zugrunde liegenden Stream der Antwort ab.</span><span class="sxs-lookup"><span data-stu-id="6a984-162">Gets the underlying stream of the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6a984-163">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-163">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.SessionToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-164">Ruft die Sitzung für die Verwendung in Sitzung Konsistenz Lesevorgänge ab.</span><span class="sxs-lookup"><span data-stu-id="6a984-164">Gets the session token for use in sesssion consistency reads.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-165">Das Sitzungstoken für die Verwendung in sitzungskonsistenz.</span><span class="sxs-lookup"><span data-stu-id="6a984-165">The session token for use in session consistency.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-166">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-166">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public System.Net.HttpStatusCode StatusCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.HttpStatusCode StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusCode As HttpStatusCode" />
      <MemberSignature Language="F#" Value="member this.StatusCode : System.Net.HttpStatusCode" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpStatusCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-167">Ruft den HTTP-Statuscode der Antwort zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="6a984-167">Gets the HTTP status code associated with the response.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-168">Der HTTP-Statuscode der Antwort zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="6a984-168">The HTTP status code associated with the response.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-169">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-169">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProceduresQuota">
      <MemberSignature Language="C#" Value="public long StoredProceduresQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StoredProceduresQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.StoredProceduresQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredProceduresQuota As Long" />
      <MemberSignature Language="F#" Value="member this.StoredProceduresQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.StoredProceduresQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-170">Ruft den maximalen Kontingent von gespeicherten Prozeduren für eine Auflistung ab.</span><span class="sxs-lookup"><span data-stu-id="6a984-170">Gets the maximum quota of stored procedures for a collection.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-171">Das maximale Kontingent.</span><span class="sxs-lookup"><span data-stu-id="6a984-171">The maximum quota.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-172">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-172">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProceduresUsage">
      <MemberSignature Language="C#" Value="public long StoredProceduresUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StoredProceduresUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.StoredProceduresUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredProceduresUsage As Long" />
      <MemberSignature Language="F#" Value="member this.StoredProceduresUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.StoredProceduresUsage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-173">Die aktuelle Anzahl von gespeicherten Prozeduren für eine Sammlung.</span><span class="sxs-lookup"><span data-stu-id="6a984-173">The current number of stored procedures for a collection.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-174">Aktuelle Anzahl der gespeicherten Prozeduren.</span><span class="sxs-lookup"><span data-stu-id="6a984-174">Current number of stored procedures.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-175">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-175">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggersQuota">
      <MemberSignature Language="C#" Value="public long TriggersQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TriggersQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.TriggersQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggersQuota As Long" />
      <MemberSignature Language="F#" Value="member this.TriggersQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.TriggersQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-176">Ruft den maximalen Kontingent von Triggern für eine Auflistung ab.</span><span class="sxs-lookup"><span data-stu-id="6a984-176">Gets the maximum quota of triggers for a collection.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="6a984-177">Das maximale Kontingent.</span><span class="sxs-lookup"><span data-stu-id="6a984-177">The maximum quota.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-178">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-178">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggersUsage">
      <MemberSignature Language="C#" Value="public long TriggersUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TriggersUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.TriggersUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggersUsage As Long" />
      <MemberSignature Language="F#" Value="member this.TriggersUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.TriggersUsage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-179">Die aktuelle Anzahl von Triggern für eine Sammlung.</span><span class="sxs-lookup"><span data-stu-id="6a984-179">The current number of triggers for a collection.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-180">Aktuelle Anzahl von Triggern.</span><span class="sxs-lookup"><span data-stu-id="6a984-180">Current number of triggers.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-181">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-181">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserDefinedFunctionsQuota">
      <MemberSignature Language="C#" Value="public long UserDefinedFunctionsQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserDefinedFunctionsQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.UserDefinedFunctionsQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserDefinedFunctionsQuota As Long" />
      <MemberSignature Language="F#" Value="member this.UserDefinedFunctionsQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.UserDefinedFunctionsQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-182">Ruft die maximale Kontingent für benutzerdefinierte Funktionen für eine Auflistung ab.</span><span class="sxs-lookup"><span data-stu-id="6a984-182">Gets the maximum quota of user defined functions for a collection.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="6a984-183">Maximale Kontingent.</span><span class="sxs-lookup"><span data-stu-id="6a984-183">Maximum quota.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-184">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-184">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserDefinedFunctionsUsage">
      <MemberSignature Language="C#" Value="public long UserDefinedFunctionsUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserDefinedFunctionsUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.UserDefinedFunctionsUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserDefinedFunctionsUsage As Long" />
      <MemberSignature Language="F#" Value="member this.UserDefinedFunctionsUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.UserDefinedFunctionsUsage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-185">Die aktuelle Anzahl der Benutzer definiert Funktionen für eine Sammlung an.</span><span class="sxs-lookup"><span data-stu-id="6a984-185">The current number of user defined functions for a collection.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-186">Aktuelle Anzahl der Benutzer definierten Funktionen.</span><span class="sxs-lookup"><span data-stu-id="6a984-186">Current number of user defined functions.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-187">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-187">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserQuota">
      <MemberSignature Language="C#" Value="public long UserQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.UserQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserQuota As Long" />
      <MemberSignature Language="F#" Value="member this.UserQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.UserQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-188">Ruft den maximalen Kontingent für Benutzerressourcen innerhalb eines Kontos ab.</span><span class="sxs-lookup"><span data-stu-id="6a984-188">Gets the maximum quota for user resources within an account.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-189">Das Kontingent für das Konto.</span><span class="sxs-lookup"><span data-stu-id="6a984-189">The maximum quota for the account.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-190">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-190">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserUsage">
      <MemberSignature Language="C#" Value="public long UserUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.UserUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserUsage As Long" />
      <MemberSignature Language="F#" Value="member this.UserUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.UserUsage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a984-191">Die aktuelle Anzahl von Benutzerressourcen im Konto.</span><span class="sxs-lookup"><span data-stu-id="6a984-191">The current number of user resources within the account.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a984-192">Die Anzahl der Benutzer.</span><span class="sxs-lookup"><span data-stu-id="6a984-192">The number of users.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6a984-193">Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="6a984-193">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>