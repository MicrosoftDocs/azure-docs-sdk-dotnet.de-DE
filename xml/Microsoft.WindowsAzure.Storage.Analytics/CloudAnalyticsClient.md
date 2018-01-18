<Type Name="CloudAnalyticsClient" FullName="Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient">
  <TypeSignature Language="C#" Value="public sealed class CloudAnalyticsClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CloudAnalyticsClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CloudAnalyticsClient" />
  <TypeSignature Language="F#" Value="type CloudAnalyticsClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="40674-101">Bietet eine clientseitige logische Darstellung für Microsoft Azure-Speicheranalyse an.</span><span class="sxs-lookup"><span data-stu-id="40674-101">Provides a client-side logical representation for Microsoft Azure Storage Analytics.</span></span> <span data-ttu-id="40674-102">Dieser Client wird verwendet, zu konfigurieren und Anforderungen für die Speicheranalyse auszuführen.</span><span class="sxs-lookup"><span data-stu-id="40674-102">This client is used to configure and execute requests against storage analytics.</span></span>
            </summary>
    <remarks><span data-ttu-id="40674-103">Der Dienstclient Analytics kapselt die Endpunkte für die BLOB- und -Dienste.</span><span class="sxs-lookup"><span data-stu-id="40674-103">The analytics service client encapsulates the endpoints for the Blob and Table services.</span></span> <span data-ttu-id="40674-104">Sie kapselt auch Anmeldeinformationen für den Zugriff auf das Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="40674-104">It also encapsulates credentials for accessing the storage account.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudAnalyticsClient (Microsoft.WindowsAzure.Storage.StorageUri blobStorageUri, Microsoft.WindowsAzure.Storage.StorageUri tableStorageUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri blobStorageUri, class Microsoft.WindowsAzure.Storage.StorageUri tableStorageUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobStorageUri As StorageUri, tableStorageUri As StorageUri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient" Usage="new Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient (blobStorageUri, tableStorageUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobStorageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="tableStorageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="blobStorageUri"><span data-ttu-id="40674-105">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Objekt, das den Blob-Dienstendpunkt, mit der Erstellung des Clients enthält.</span><span class="sxs-lookup"><span data-stu-id="40674-105">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> object containing the Blob service endpoint to use to create the client.</span></span></param>
        <param name="tableStorageUri"><span data-ttu-id="40674-106">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Objekt, das den tabellendienstendpunkt verwenden Sie zum Erstellen des Clients enthält.</span><span class="sxs-lookup"><span data-stu-id="40674-106">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> object containing the Table service endpoint to use to create the client.</span></span></param>
        <param name="credentials"><span data-ttu-id="40674-107">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="40674-107">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="40674-108">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient" /> -Klasse unter Verwendung der angegebenen BLOB- und Dienstendpunkte und Kontoanmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="40674-108">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient" /> class using the specified Blob and Table service endpoints and account credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCapacityQuery">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity&gt; CreateCapacityQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity&gt; CreateCapacityQuery() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.CreateCapacityQuery" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCapacityQuery () As TableQuery(Of CapacityEntity)" />
      <MemberSignature Language="F#" Value="member this.CreateCapacityQuery : unit -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity&gt;" Usage="cloudAnalyticsClient.CreateCapacityQuery " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="40674-109">Erstellt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> -Objekt für die Blob-Dienst Kapazität Tabelle Abfragen.</span><span class="sxs-lookup"><span data-stu-id="40674-109">Creates a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> object for querying the Blob service capacity table.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-110">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="40674-110">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> object.</span></span></returns>
        <remarks><span data-ttu-id="40674-111">Diese Methode gilt nur für Blob-Dienst zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="40674-111">This method is applicable only to Blob service.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateHourMetricsQuery">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt; CreateHourMetricsQuery (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt; CreateHourMetricsQuery(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.CreateHourMetricsQuery(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateHourMetricsQuery (service As StorageService, location As StorageLocation) As TableQuery(Of MetricsEntity)" />
      <MemberSignature Language="F#" Value="member this.CreateHourMetricsQuery : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt;" Usage="cloudAnalyticsClient.CreateHourMetricsQuery (service, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="40674-112">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-112">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="location"><span data-ttu-id="40674-113">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-113">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="40674-114">Erstellt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> Objekt für die Abfrage eine stündliche Metriken-Protokolltabelle.</span><span class="sxs-lookup"><span data-stu-id="40674-114">Creates a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> object for querying an hourly metrics log table.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-115">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="40674-115">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMinuteMetricsQuery">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt; CreateMinuteMetricsQuery (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt; CreateMinuteMetricsQuery(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.CreateMinuteMetricsQuery(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMinuteMetricsQuery (service As StorageService, location As StorageLocation) As TableQuery(Of MetricsEntity)" />
      <MemberSignature Language="F#" Value="member this.CreateMinuteMetricsQuery : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt;" Usage="cloudAnalyticsClient.CreateMinuteMetricsQuery (service, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="40674-116">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-116">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="location"><span data-ttu-id="40674-117">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-117">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="40674-118">Erstellt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> Objekt für die Abfrage von einer Minute Metriken-Protokolltabelle.</span><span class="sxs-lookup"><span data-stu-id="40674-118">Creates a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> object for querying a minute metrics log table.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-119">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="40674-119">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCapacityTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetCapacityTable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetCapacityTable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetCapacityTable" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCapacityTable () As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetCapacityTable : unit -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetCapacityTable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="40674-120">Ruft die metriktabelle Kapazität für den Blob-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="40674-120">Gets the capacity metrics table for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-121">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="40674-121">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHourMetricsTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetHourMetricsTable (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetHourMetricsTable(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetHourMetricsTable(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetHourMetricsTable (service As StorageService) As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetHourMetricsTable : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetHourMetricsTable service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="40674-122">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-122">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="40674-123">Ruft die stündlichen metrikentabelle für den angegebenen Speicherdienst ab.</span><span class="sxs-lookup"><span data-stu-id="40674-123">Gets the hourly metrics table for the specified storage service.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-124">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="40674-124">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHourMetricsTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetHourMetricsTable (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetHourMetricsTable(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetHourMetricsTable(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetHourMetricsTable (service As StorageService, location As StorageLocation) As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetHourMetricsTable : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetHourMetricsTable (service, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="40674-125">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-125">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="location"><span data-ttu-id="40674-126">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-126">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="40674-127">Ruft die stündlichen metrikentabelle für den angegebenen Speicherdienst ab.</span><span class="sxs-lookup"><span data-stu-id="40674-127">Gets the hourly metrics table for the specified storage service.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-128">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="40674-128">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLogDirectory">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory GetLogDirectory (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory GetLogDirectory(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetLogDirectory(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLogDirectory (service As StorageService) As CloudBlobDirectory" />
      <MemberSignature Language="F#" Value="member this.GetLogDirectory : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" Usage="cloudAnalyticsClient.GetLogDirectory service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="40674-129">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-129">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="40674-130">Ruft eine <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> Objekt, das die Protokolle für den angegebenen Speicherdienst enthält.</span><span class="sxs-lookup"><span data-stu-id="40674-130">Gets a <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> object containing the logs for the specified storage service.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-131">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="40674-131">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMinuteMetricsTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetMinuteMetricsTable (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetMinuteMetricsTable(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetMinuteMetricsTable(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMinuteMetricsTable (service As StorageService) As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetMinuteMetricsTable : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetMinuteMetricsTable service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="40674-132">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-132">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="40674-133">Ruft die Tabelle minütlichen Metriken für den angegebenen Speicherdienst ab.</span><span class="sxs-lookup"><span data-stu-id="40674-133">Gets the minute metrics table for the specified storage service.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-134">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="40674-134">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMinuteMetricsTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetMinuteMetricsTable (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetMinuteMetricsTable(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetMinuteMetricsTable(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMinuteMetricsTable (service As StorageService, location As StorageLocation) As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetMinuteMetricsTable : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetMinuteMetricsTable (service, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="40674-135">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-135">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="location"><span data-ttu-id="40674-136">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-136">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="40674-137">Ruft die Tabelle minütlichen Metriken für den angegebenen Speicherdienst ab.</span><span class="sxs-lookup"><span data-stu-id="40674-137">Gets the minute metrics table for the specified storage service.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-138">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="40674-138">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogRecords(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLogRecords (service As StorageService) As IEnumerable(Of LogRecord)" />
      <MemberSignature Language="F#" Value="member this.ListLogRecords : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="cloudAnalyticsClient.ListLogRecords service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="40674-139">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-139">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="40674-140">Gibt eine aufzählbare Auflistung von Protokolldatensätzen Analytics, verzögert abgerufen.</span><span class="sxs-lookup"><span data-stu-id="40674-140">Returns an enumerable collection of Analytics log records, retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-141">Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> und verzögert abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="40674-141">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogRecords(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListLogRecords : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="cloudAnalyticsClient.ListLogRecords (service, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="40674-142">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-142">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="options"><span data-ttu-id="40674-143">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="40674-143">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="40674-144">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="40674-144">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="40674-145">Gibt eine aufzählbare Auflistung von Protokolldatensätzen Analytics, verzögert abgerufen.</span><span class="sxs-lookup"><span data-stu-id="40674-145">Returns an enumerable collection of Analytics log records, retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-146">Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> und verzögert abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="40674-146">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, DateTimeOffset startTime, Nullable&lt;DateTimeOffset&gt; endTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype System.DateTimeOffset startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogRecords(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,System.DateTimeOffset,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLogRecords (service As StorageService, startTime As DateTimeOffset, endTime As Nullable(Of DateTimeOffset)) As IEnumerable(Of LogRecord)" />
      <MemberSignature Language="F#" Value="member this.ListLogRecords : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * DateTimeOffset * Nullable&lt;DateTimeOffset&gt; -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="cloudAnalyticsClient.ListLogRecords (service, startTime, endTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="40674-147">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-147">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="startTime"><span data-ttu-id="40674-148">Ein <see cref="T:System.DateTimeOffset" /> Objekt, das den Beginn des Zeitraums für die Protokolle abgerufen werden sollen darstellt.</span><span class="sxs-lookup"><span data-stu-id="40674-148">A <see cref="T:System.DateTimeOffset" /> object representing the start of the time range for which logs should be retrieved.</span></span></param>
        <param name="endTime"><span data-ttu-id="40674-149">Ein <see cref="T:System.DateTimeOffset" /> Objekt, das das Ende des Zeitraums für die Protokolle abgerufen werden sollen darstellt.</span><span class="sxs-lookup"><span data-stu-id="40674-149">A <see cref="T:System.DateTimeOffset" /> object representing the end of the time range for which logs should be retrieved.</span></span></param>
        <summary>
            <span data-ttu-id="40674-150">Gibt eine aufzählbare Auflistung von Protokolldatensätzen Analytics, verzögert abgerufen.</span><span class="sxs-lookup"><span data-stu-id="40674-150">Returns an enumerable collection of Analytics log records, retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-151">Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> und verzögert abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="40674-151">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, DateTimeOffset startTime, Nullable&lt;DateTimeOffset&gt; endTime, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype System.DateTimeOffset startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogRecords(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,System.DateTimeOffset,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListLogRecords : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * DateTimeOffset * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="cloudAnalyticsClient.ListLogRecords (service, startTime, endTime, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="40674-152">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-152">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="startTime"><span data-ttu-id="40674-153">Ein <see cref="T:System.DateTimeOffset" /> Objekt, das den Beginn des Zeitraums für die Protokolle abgerufen werden sollen darstellt.</span><span class="sxs-lookup"><span data-stu-id="40674-153">A <see cref="T:System.DateTimeOffset" /> object representing the start of the time range for which logs should be retrieved.</span></span></param>
        <param name="endTime"><span data-ttu-id="40674-154">Ein <see cref="T:System.DateTimeOffset" /> Objekt, das das Ende des Zeitraums für die Protokolle abgerufen werden sollen darstellt.</span><span class="sxs-lookup"><span data-stu-id="40674-154">A <see cref="T:System.DateTimeOffset" /> object representing the end of the time range for which logs should be retrieved.</span></span></param>
        <param name="options"><span data-ttu-id="40674-155">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="40674-155">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="40674-156">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="40674-156">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="40674-157">Gibt eine aufzählbare Auflistung von Protokolldatensätzen Analytics, verzögert abgerufen.</span><span class="sxs-lookup"><span data-stu-id="40674-157">Returns an enumerable collection of Analytics log records, retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-158">Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> und verzögert abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="40674-158">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogs(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLogs (service As StorageService) As IEnumerable(Of ICloudBlob)" />
      <MemberSignature Language="F#" Value="member this.ListLogs : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudAnalyticsClient.ListLogs service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="40674-159">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-159">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="40674-160">Gibt eine aufzählbare Auflistung der Protokoll-Blobs, Analytics Protokolldatensätze zurück.</span><span class="sxs-lookup"><span data-stu-id="40674-160">Returns an enumerable collection of log blobs containing Analytics log records.</span></span> <span data-ttu-id="40674-161">Blobs sind verzögert abgerufen.</span><span class="sxs-lookup"><span data-stu-id="40674-161">The blobs are retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-162">Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> und verzögert abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="40674-162">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, DateTimeOffset startTime, Nullable&lt;DateTimeOffset&gt; endTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype System.DateTimeOffset startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogs(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,System.DateTimeOffset,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLogs (service As StorageService, startTime As DateTimeOffset, endTime As Nullable(Of DateTimeOffset)) As IEnumerable(Of ICloudBlob)" />
      <MemberSignature Language="F#" Value="member this.ListLogs : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * DateTimeOffset * Nullable&lt;DateTimeOffset&gt; -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudAnalyticsClient.ListLogs (service, startTime, endTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="40674-163">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-163">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="startTime"><span data-ttu-id="40674-164">Ein <see cref="T:System.DateTimeOffset" /> Objekt stellt die Startzeit für die Protokolle abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="40674-164">A <see cref="T:System.DateTimeOffset" /> object representing the start time for which logs should be retrieved.</span></span></param>
        <param name="endTime"><span data-ttu-id="40674-165">Ein <see cref="T:System.DateTimeOffset" /> Objekt stellt die Endzeit für die Protokolle abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="40674-165">A <see cref="T:System.DateTimeOffset" /> object representing the end time for which logs should be retrieved.</span></span></param>
        <summary>
            <span data-ttu-id="40674-166">Gibt eine aufzählbare Auflistung der Protokoll-Blobs, Analytics Protokolldatensätze zurück.</span><span class="sxs-lookup"><span data-stu-id="40674-166">Returns an enumerable collection of log blobs containing Analytics log records.</span></span> <span data-ttu-id="40674-167">Blobs sind verzögert abgerufen.</span><span class="sxs-lookup"><span data-stu-id="40674-167">The blobs are retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-168">Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> und verzögert abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="40674-168">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations operations, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations operations, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogs(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListLogs : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudAnalyticsClient.ListLogs (service, operations, details, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" />
        <Parameter Name="details" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="40674-169">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-169">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="operations"><span data-ttu-id="40674-170">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" /> -Enumerationswert, der die Vorgangstypen Protokollierung für das Filtern der Protokoll-Blobs angibt.</span><span class="sxs-lookup"><span data-stu-id="40674-170">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" /> enumeration value that indicates the types of logging operations on which to filter the log blobs.</span></span></param>
        <param name="details"><span data-ttu-id="40674-171">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> -Enumerationswert ab, der angibt, ob Blob-Metadaten zurückgegeben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="40674-171">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration value that indicates whether or not blob metadata should be returned.</span></span> <span data-ttu-id="40674-172">Nur <c>keine</c> und <c>Metadaten</c> Werte sind gültig.</span><span class="sxs-lookup"><span data-stu-id="40674-172">Only <c>None</c> and <c>Metadata</c> are valid values.</span></span> </param>
        <param name="options"><span data-ttu-id="40674-173">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="40674-173">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="40674-174">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="40674-174">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="40674-175">Gibt eine aufzählbare Auflistung der Protokoll-Blobs, Analytics Protokolldatensätze zurück.</span><span class="sxs-lookup"><span data-stu-id="40674-175">Returns an enumerable collection of log blobs containing Analytics log records.</span></span> <span data-ttu-id="40674-176">Blobs sind verzögert abgerufen.</span><span class="sxs-lookup"><span data-stu-id="40674-176">The blobs are retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-177">Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> und verzögert abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="40674-177">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> and are retrieved lazily.</span></span></returns>
        <remarks><span data-ttu-id="40674-178">Beachten Sie, Angeben eines Vorgangs für die Protokollierung für den Typ der <paramref name="operations" /> Parameter beliebige Analytics Protokoll-BLOBs, die den Vorgang angegebenen Protokollierung enthält zurück, selbst wenn Protokoll Blob auch andere Arten von Vorgängen für die Protokollierung enthält.</span><span class="sxs-lookup"><span data-stu-id="40674-178">Note that specifying a logging operation type for the <paramref name="operations" /> parameter will return any Analytics log blob that contains the specified logging operation, even if that log blob also includes other types of logging operations.</span></span> <span data-ttu-id="40674-179">Beachten Sie, die derzeit die einzigen unterstützten Werte für die <paramref name="details" /> Parameter sind <c>keine</c> und <c>Metadaten</c>.</span><span class="sxs-lookup"><span data-stu-id="40674-179">Also note that the only currently supported values for the <paramref name="details" /> parameter are <c>None</c> and <c>Metadata</c>.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, DateTimeOffset startTime, Nullable&lt;DateTimeOffset&gt; endTime, Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations operations, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype System.DateTimeOffset startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime, valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations operations, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogs(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,System.DateTimeOffset,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListLogs : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * DateTimeOffset * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudAnalyticsClient.ListLogs (service, startTime, endTime, operations, details, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" />
        <Parameter Name="details" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="40674-180">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="40674-180">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="startTime"><span data-ttu-id="40674-181">Ein <see cref="T:System.DateTimeOffset" /> Objekt, das den Beginn des Zeitraums für die Protokolle abgerufen werden sollen darstellt.</span><span class="sxs-lookup"><span data-stu-id="40674-181">A <see cref="T:System.DateTimeOffset" /> object representing the start of the time range for which logs should be retrieved.</span></span></param>
        <param name="endTime"><span data-ttu-id="40674-182">Ein <see cref="T:System.DateTimeOffset" /> Objekt, das das Ende des Zeitraums für die Protokolle abgerufen werden sollen darstellt.</span><span class="sxs-lookup"><span data-stu-id="40674-182">A <see cref="T:System.DateTimeOffset" /> object representing the end of the time range for which logs should be retrieved.</span></span></param>
        <param name="operations"><span data-ttu-id="40674-183">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" /> -Enumerationswert, der die Vorgangstypen Protokollierung für das Filtern der Protokoll-Blobs angibt.</span><span class="sxs-lookup"><span data-stu-id="40674-183">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" /> enumeration value that indicates the types of logging operations on which to filter the log blobs.</span></span></param>
        <param name="details"><span data-ttu-id="40674-184">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> -Enumerationswert ab, der angibt, ob Blob-Metadaten zurückgegeben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="40674-184">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration value that indicates whether or not blob metadata should be returned.</span></span> <span data-ttu-id="40674-185">Nur <c>keine</c> und <c>Metadaten</c> Werte sind gültig.</span><span class="sxs-lookup"><span data-stu-id="40674-185">Only <c>None</c> and <c>Metadata</c> are valid values.</span></span> </param>
        <param name="options"><span data-ttu-id="40674-186">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="40674-186">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="40674-187">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="40674-187">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="40674-188">Gibt eine aufzählbare Auflistung der Protokoll-Blobs, Analytics Protokolldatensätze zurück.</span><span class="sxs-lookup"><span data-stu-id="40674-188">Returns an enumerable collection of log blobs containing Analytics log records.</span></span> <span data-ttu-id="40674-189">Blobs sind verzögert abgerufen.</span><span class="sxs-lookup"><span data-stu-id="40674-189">The blobs are retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-190">Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> und verzögert abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="40674-190">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> and are retrieved lazily.</span></span></returns>
        <remarks><span data-ttu-id="40674-191">Beachten Sie, Angeben eines Vorgangs für die Protokollierung für den Typ der <paramref name="operations" /> Parameter beliebige Analytics Protokoll-BLOBs, die den Vorgang angegebenen Protokollierung enthält zurück, selbst wenn Protokoll Blob auch andere Arten von Vorgängen für die Protokollierung enthält.</span><span class="sxs-lookup"><span data-stu-id="40674-191">Note that specifying a logging operation type for the <paramref name="operations" /> parameter will return any Analytics log blob that contains the specified logging operation, even if that log blob also includes other types of logging operations.</span></span> <span data-ttu-id="40674-192">Beachten Sie, die derzeit die einzigen unterstützten Werte für die <paramref name="details" /> Parameter sind <c>keine</c> und <c>Metadaten</c>.</span><span class="sxs-lookup"><span data-stu-id="40674-192">Also note that the only currently supported values for the <paramref name="details" /> parameter are <c>None</c> and <c>Metadata</c>.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseLogBlob">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogBlob (Microsoft.WindowsAzure.Storage.Blob.ICloudBlob logBlob);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogBlob(class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob logBlob) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogBlob(Microsoft.WindowsAzure.Storage.Blob.ICloudBlob)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ParseLogBlob (logBlob As ICloudBlob) As IEnumerable(Of LogRecord)" />
      <MemberSignature Language="F#" Value="static member ParseLogBlob : Microsoft.WindowsAzure.Storage.Blob.ICloudBlob -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogBlob logBlob" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logBlob" Type="Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />
      </Parameters>
      <Docs>
        <param name="logBlob"><span data-ttu-id="40674-193">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> Objekt, aus dem Protokolldatensätze zu analysieren.</span><span class="sxs-lookup"><span data-stu-id="40674-193">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> object from which to parse log records.</span></span></param>
        <summary>
            <span data-ttu-id="40674-194">Gibt eine aufzählbare Auflistung von Protokolldatensätzen Analytics, verzögert abgerufen.</span><span class="sxs-lookup"><span data-stu-id="40674-194">Returns an enumerable collection of Analytics log records, retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-195">Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> und verzögert abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="40674-195">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseLogBlobs">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogBlobs (System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; logBlobs);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogBlobs(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; logBlobs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogBlobs(System.Collections.Generic.IEnumerable{Microsoft.WindowsAzure.Storage.Blob.ICloudBlob})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ParseLogBlobs (logBlobs As IEnumerable(Of ICloudBlob)) As IEnumerable(Of LogRecord)" />
      <MemberSignature Language="F#" Value="static member ParseLogBlobs : seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogBlobs logBlobs" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logBlobs" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" />
      </Parameters>
      <Docs>
        <param name="logBlobs"><span data-ttu-id="40674-196">Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> Objekte, die Protokolldatensätze zu analysieren.</span><span class="sxs-lookup"><span data-stu-id="40674-196">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> objects from which to parse log records.</span></span></param>
        <summary>
            <span data-ttu-id="40674-197">Gibt eine aufzählbare Auflistung von Protokolldatensätzen Analytics, verzögert abgerufen.</span><span class="sxs-lookup"><span data-stu-id="40674-197">Returns an enumerable collection of Analytics log records, retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-198">Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> und verzögert abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="40674-198">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseLogStream">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogStream (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogStream(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogStream(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="static member ParseLogStream : System.IO.Stream -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogStream stream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream"><span data-ttu-id="40674-199">Die <see cref="T:System.IO.Stream" /> Objekt, aus dem Protokolldatensätze zu analysieren.</span><span class="sxs-lookup"><span data-stu-id="40674-199">The <see cref="T:System.IO.Stream" /> object from which to parse log records.</span></span></param>
        <summary>
            <span data-ttu-id="40674-200">Gibt eine aufzählbare Auflistung von Protokolldatensätzen Analytics, verzögert abgerufen.</span><span class="sxs-lookup"><span data-stu-id="40674-200">Returns an enumerable collection of Analytics log records, retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="40674-201">Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> und verzögert abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="40674-201">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>