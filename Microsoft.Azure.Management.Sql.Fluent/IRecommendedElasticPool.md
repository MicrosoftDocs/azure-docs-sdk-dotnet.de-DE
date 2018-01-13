<Type Name="IRecommendedElasticPool" FullName="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool">
  <TypeSignature Language="C#" Value="public interface IRecommendedElasticPool : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRecommendedElasticPool implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRecommendedElasticPool&#xA;Implements IHasId, IHasInner(Of RecommendedElasticPoolInner), IHasManager(Of ISqlManager), IHasName, IHasResourceGroup, IRefreshable(Of IRecommendedElasticPool)" />
  <TypeSignature Language="F#" Value="type IRecommendedElasticPool = interface&#xA;    interface IRefreshable&lt;IRecommendedElasticPool&gt;&#xA;    interface IHasInner&lt;RecommendedElasticPoolInner&gt;&#xA;    interface IHasResourceGroup&#xA;    interface IHasName&#xA;    interface IHasId&#xA;    interface IHasManager&lt;ISqlManager&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="1c1ce-101">Eine unveränderliche clientseitige Darstellung einer Azure SQL-ElasticPool empfohlen.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-101">An immutable client-side representation of an Azure SQL Recommended ElasticPool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DatabaseDtuMax">
      <MemberSignature Language="C#" Value="public double DatabaseDtuMax { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DatabaseDtuMax" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.DatabaseDtuMax" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseDtuMax As Double" />
      <MemberSignature Language="F#" Value="member this.DatabaseDtuMax : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.DatabaseDtuMax" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c1ce-102">Ruft die maximale DTU für die Datenbank an.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-102">Gets the maximum DTU for the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseDtuMin">
      <MemberSignature Language="C#" Value="public double DatabaseDtuMin { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DatabaseDtuMin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.DatabaseDtuMin" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseDtuMin As Double" />
      <MemberSignature Language="F#" Value="member this.DatabaseDtuMin : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.DatabaseDtuMin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c1ce-103">Ruft die minimale DTU für die Datenbank an.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-103">Gets the minimum DTU for the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseEdition">
      <MemberSignature Language="C#" Value="public string DatabaseEdition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseEdition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.DatabaseEdition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseEdition As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseEdition : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.DatabaseEdition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c1ce-104">Ruft die Edition des Azure SQL empfohlene elastische Pools ab.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-104">Gets the edition of the Azure SQL Recommended Elastic Pool.</span></span> <span data-ttu-id="1c1ce-105">Die ElasticPoolEditions-Enumeration enthält alle gültigen Editionen.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-105">The ElasticPoolEditions enumeration contains all the valid editions.</span></span>
            <span data-ttu-id="1c1ce-106">Folgende Werte sind möglich: "Basic", "Standard", "Premium".</span><span class="sxs-lookup"><span data-stu-id="1c1ce-106">Possible values include: 'Basic', 'Standard', 'Premium'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Databases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; Databases { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; Databases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.Databases" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Databases As IReadOnlyList(Of ISqlDatabase)" />
      <MemberSignature Language="F#" Value="member this.Databases : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.Databases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c1ce-107">Ruft die Liste der Azure SQL-Datenbanken in diesem Pool.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-107">Gets the list of Azure SQL Databases in this pool.</span></span> <span data-ttu-id="1c1ce-108">Erweiterte Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-108">Expanded property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dtu">
      <MemberSignature Language="C#" Value="public double Dtu { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Dtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.Dtu" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Dtu As Double" />
      <MemberSignature Language="F#" Value="member this.Dtu : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.Dtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c1ce-109">Ruft die DTU für SQL Azure empfohlen elastischen Pool.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-109">Gets the DTU for the SQL Azure Recommended Elastic Pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatabase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase GetDatabase (string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase GetDatabase(string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.GetDatabase(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDatabase (databaseName As String) As ISqlDatabase" />
      <MemberSignature Language="F#" Value="abstract member GetDatabase : string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase" Usage="iRecommendedElasticPool.GetDatabase databaseName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseName"><span data-ttu-id="1c1ce-110">Der Name der Datenbank abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-110">Name of the database to be fetched.</span></span></param>
        <summary>
            <span data-ttu-id="1c1ce-111">Abrufen einer bestimmten Datenbank in der Datenbank empfohlen.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-111">Get a specific database in the recommended database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1c1ce-112">Informationen für die Datenbank, in der empfohlenen elastischen Pool empfohlen.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-112">Information on the database recommended in recommended elastic pool.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ListDatabases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; ListDatabases ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; ListDatabases() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.ListDatabases" />
      <MemberSignature Language="VB.NET" Value="Public Function ListDatabases () As IReadOnlyList(Of ISqlDatabase)" />
      <MemberSignature Language="F#" Value="abstract member ListDatabases : unit -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;" Usage="iRecommendedElasticPool.ListDatabases " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1c1ce-113">Liste der Datenbanken mittels ausführenden Azure Aufruf abgerufen.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-113">Fetches list of databases by making call to Azure.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1c1ce-114">Liste der Datenbanken in der empfohlenen elastischen Pool.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-114">List of the databases in recommended elastic pool.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolMetric&gt; ListMetrics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolMetric&gt; ListMetrics() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.ListMetrics" />
      <MemberSignature Language="VB.NET" Value="Public Function ListMetrics () As IReadOnlyList(Of IRecommendedElasticPoolMetric)" />
      <MemberSignature Language="F#" Value="abstract member ListMetrics : unit -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolMetric&gt;" Usage="iRecommendedElasticPool.ListMetrics " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1c1ce-115">Liste der metrikinformationen mittels ausführenden Azure Aufruf abgerufen.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-115">Fetches list of metrics information by making call to Azure.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1c1ce-116">Liste der Datenbanken in der empfohlenen elastischen Pool.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-116">List of the databases in recommended elastic pool.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="MaxObservedDtu">
      <MemberSignature Language="C#" Value="public double MaxObservedDtu { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 MaxObservedDtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.MaxObservedDtu" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxObservedDtu As Double" />
      <MemberSignature Language="F#" Value="member this.MaxObservedDtu : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.MaxObservedDtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c1ce-117">Ruft die maximale beobachtete DTU ab.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-117">Gets maximum observed DTU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxObservedStorageMB">
      <MemberSignature Language="C#" Value="public double MaxObservedStorageMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 MaxObservedStorageMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.MaxObservedStorageMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxObservedStorageMB As Double" />
      <MemberSignature Language="F#" Value="member this.MaxObservedStorageMB : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.MaxObservedStorageMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c1ce-118">Ruft maximale beobachteten Speicher in Megabyte an.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-118">Gets maximum observed storage in megabytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObservationPeriodEnd">
      <MemberSignature Language="C#" Value="public DateTime ObservationPeriodEnd { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ObservationPeriodEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.ObservationPeriodEnd" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ObservationPeriodEnd As DateTime" />
      <MemberSignature Language="F#" Value="member this.ObservationPeriodEnd : DateTime" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.ObservationPeriodEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c1ce-119">Ruft die Beobachtung zeitraumstarts (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="1c1ce-119">Gets the observation period start (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObservationPeriodStart">
      <MemberSignature Language="C#" Value="public DateTime ObservationPeriodStart { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ObservationPeriodStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.ObservationPeriodStart" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ObservationPeriodStart As DateTime" />
      <MemberSignature Language="F#" Value="member this.ObservationPeriodStart : DateTime" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.ObservationPeriodStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c1ce-120">Ruft die Beobachtung zeitraumstarts (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="1c1ce-120">Gets the observation period start (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerName">
      <MemberSignature Language="C#" Value="public string SqlServerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.SqlServerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlServerName As String" />
      <MemberSignature Language="F#" Value="member this.SqlServerName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.SqlServerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c1ce-121">Ruft die Namen des SQL-Servers, zu dem diese Datenbank gehört.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-121">Gets name of the SQL Server to which this database belongs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageMB">
      <MemberSignature Language="C#" Value="public double StorageMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 StorageMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.StorageMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageMB As Double" />
      <MemberSignature Language="F#" Value="member this.StorageMB : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.StorageMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c1ce-122">Ruft die Speichergröße in Megabytes ab.</span><span class="sxs-lookup"><span data-stu-id="1c1ce-122">Gets storage size in megabytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>