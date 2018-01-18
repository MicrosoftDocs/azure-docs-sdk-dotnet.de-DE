<Type Name="IRedisCachePremium" FullName="Microsoft.Azure.Management.Redis.Fluent.IRedisCachePremium">
  <TypeSignature Language="C#" Value="public interface IRedisCachePremium : Microsoft.Azure.Management.Redis.Fluent.IRedisCache, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisManager,Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRedisCachePremium implements class Microsoft.Azure.Management.Redis.Fluent.IRedisCache, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Redis.Fluent.IRedisManager, class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Redis.Fluent.IRedisManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.IRedisCachePremium" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRedisCachePremium&#xA;Implements IGroupableResource(Of IRedisManager, RedisResourceInner), IHasInner(Of RedisResourceInner), IHasManager(Of IRedisManager), IRedisCache, IRefreshable(Of IRedisCache), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IRedisCachePremium = interface&#xA;    interface IRedisCache&#xA;    interface IGroupableResource&lt;IRedisManager, RedisResourceInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IRedisManager&gt;&#xA;    interface IHasInner&lt;RedisResourceInner&gt;&#xA;    interface IRefreshable&lt;IRedisCache&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Redis.Fluent.IRedisCache</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisManager,Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="2a1bf-101">Eine unveränderliche clientseitige Darstellung von einem Azure-Redis-Cache mit der Premium-SKU.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-101">An immutable client-side representation of an Azure Redis cache with Premium SKU.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeletePatchSchedule">
      <MemberSignature Language="C#" Value="public void DeletePatchSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeletePatchSchedule() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisCachePremium.DeletePatchSchedule" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeletePatchSchedule ()" />
      <MemberSignature Language="F#" Value="abstract member DeletePatchSchedule : unit -&gt; unit" Usage="iRedisCachePremium.DeletePatchSchedule " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2a1bf-102">Löscht das Patchen Zeitplan für Redis-Cache.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-102">Deletes the patching schedule for Redis Cache.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportData">
      <MemberSignature Language="C#" Value="public void ExportData (string containerSASUrl, string prefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ExportData(string containerSASUrl, string prefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisCachePremium.ExportData(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ExportData (containerSASUrl As String, prefix As String)" />
      <MemberSignature Language="F#" Value="abstract member ExportData : string * string -&gt; unit" Usage="iRedisCachePremium.ExportData (containerSASUrl, prefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="containerSASUrl" Type="System.String" />
        <Parameter Name="prefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="containerSASUrl"><span data-ttu-id="2a1bf-103">Der Containername zu exportieren.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-103">Container name to export to.</span></span></param>
        <param name="prefix"><span data-ttu-id="2a1bf-104">Präfix für exportierte Dateien verwenden.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-104">Prefix to use for exported files.</span></span></param>
        <summary>
            <span data-ttu-id="2a1bf-105">Exportieren von Daten aus der Redis-Cache.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-105">Export data from Redis Cache.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportData">
      <MemberSignature Language="C#" Value="public void ExportData (string containerSASUrl, string prefix, string fileFormat);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ExportData(string containerSASUrl, string prefix, string fileFormat) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisCachePremium.ExportData(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ExportData (containerSASUrl As String, prefix As String, fileFormat As String)" />
      <MemberSignature Language="F#" Value="abstract member ExportData : string * string * string -&gt; unit" Usage="iRedisCachePremium.ExportData (containerSASUrl, prefix, fileFormat)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="containerSASUrl" Type="System.String" />
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="fileFormat" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="containerSASUrl"><span data-ttu-id="2a1bf-106">Der Containername zu exportieren.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-106">Container name to export to.</span></span></param>
        <param name="prefix"><span data-ttu-id="2a1bf-107">Präfix für exportierte Dateien verwenden.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-107">Prefix to use for exported files.</span></span></param>
        <param name="fileFormat"><span data-ttu-id="2a1bf-108">Gibt das Dateiformat an.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-108">Specifies file format.</span></span></param>
        <summary>
            <span data-ttu-id="2a1bf-109">Exportieren von Daten aus der Redis-Cache.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-109">Export data from Redis Cache.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceReboot">
      <MemberSignature Language="C#" Value="public void ForceReboot (string rebootType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ForceReboot(string rebootType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisCachePremium.ForceReboot(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ForceReboot (rebootType As String)" />
      <MemberSignature Language="F#" Value="abstract member ForceReboot : string -&gt; unit" Usage="iRedisCachePremium.ForceReboot rebootType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rebootType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="rebootType">
            <span data-ttu-id="2a1bf-110">Gibt an, der Redis-Knoten neu starten.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-110">Specifies which Redis node(s) to reboot.</span></span> <span data-ttu-id="2a1bf-111">Je nach dieser Wert ist Datenverlust möglich.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-111">Depending on this value data loss is possible.</span></span> <span data-ttu-id="2a1bf-112">Folgende Werte sind möglich: "PrimaryNode", "SecondaryNode", "AllNodes".</span><span class="sxs-lookup"><span data-stu-id="2a1bf-112">Possible values include: 'PrimaryNode', 'SecondaryNode', 'AllNodes'.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2a1bf-113">Neustart angegeben Redis-Knoten.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-113">Reboot specified Redis node(s).</span></span> <span data-ttu-id="2a1bf-114">Dieser Vorgang erfordert, über die Schreibberechtigung für die Cache-Ressource.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-114">This operation requires write permission to the cache resource.</span></span> <span data-ttu-id="2a1bf-115">Datenverlust möglich.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-115">There can be potential data loss.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceReboot">
      <MemberSignature Language="C#" Value="public void ForceReboot (string rebootType, int shardId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ForceReboot(string rebootType, int32 shardId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisCachePremium.ForceReboot(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ForceReboot (rebootType As String, shardId As Integer)" />
      <MemberSignature Language="F#" Value="abstract member ForceReboot : string * int -&gt; unit" Usage="iRedisCachePremium.ForceReboot (rebootType, shardId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rebootType" Type="System.String" />
        <Parameter Name="shardId" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="rebootType">
            <span data-ttu-id="2a1bf-116">Gibt an, der Redis-Knoten neu starten.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-116">Specifies which Redis node(s) to reboot.</span></span> <span data-ttu-id="2a1bf-117">Je nach dieser Wert ist Datenverlust möglich.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-117">Depending on this value data loss is possible.</span></span> <span data-ttu-id="2a1bf-118">Folgende Werte sind möglich: "PrimaryNode", "SecondaryNode", "AllNodes".</span><span class="sxs-lookup"><span data-stu-id="2a1bf-118">Possible values include: 'PrimaryNode', 'SecondaryNode', 'AllNodes'.</span></span>
            </param>
        <param name="shardId"><span data-ttu-id="2a1bf-119">Bei einem Cluster Cache gibt diese Shard-Id, die neu gestartet werden soll.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-119">In case of cluster cache, this specifies shard id which should be rebooted.</span></span></param>
        <summary>
            <span data-ttu-id="2a1bf-120">Neustart angegeben Redis-Knoten.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-120">Reboot specified Redis node(s).</span></span> <span data-ttu-id="2a1bf-121">Dieser Vorgang erfordert, über die Schreibberechtigung für die Cache-Ressource.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-121">This operation requires write permission to the cache resource.</span></span> <span data-ttu-id="2a1bf-122">Datenverlust möglich.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-122">There can be potential data loss.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportData">
      <MemberSignature Language="C#" Value="public void ImportData (System.Collections.Generic.IList&lt;string&gt; files);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ImportData(class System.Collections.Generic.IList`1&lt;string&gt; files) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisCachePremium.ImportData(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ImportData (files As IList(Of String))" />
      <MemberSignature Language="F#" Value="abstract member ImportData : System.Collections.Generic.IList&lt;string&gt; -&gt; unit" Usage="iRedisCachePremium.ImportData files" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="files" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="files"><span data-ttu-id="2a1bf-123">zu importierende Dateien.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-123">Files to import.</span></span></param>
        <summary>
            <span data-ttu-id="2a1bf-124">Importieren Sie Daten in Redis-Cache.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-124">Import data into Redis Cache.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportData">
      <MemberSignature Language="C#" Value="public void ImportData (System.Collections.Generic.IList&lt;string&gt; files, string fileFormat);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ImportData(class System.Collections.Generic.IList`1&lt;string&gt; files, string fileFormat) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisCachePremium.ImportData(System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ImportData (files As IList(Of String), fileFormat As String)" />
      <MemberSignature Language="F#" Value="abstract member ImportData : System.Collections.Generic.IList&lt;string&gt; * string -&gt; unit" Usage="iRedisCachePremium.ImportData (files, fileFormat)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="files" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="fileFormat" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="files"><span data-ttu-id="2a1bf-125">zu importierende Dateien.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-125">Files to import.</span></span></param>
        <param name="fileFormat"><span data-ttu-id="2a1bf-126">Gibt das Dateiformat an.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-126">Specifies file format.</span></span></param>
        <summary>
            <span data-ttu-id="2a1bf-127">Importieren Sie Daten in Redis-Cache.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-127">Import data into Redis Cache.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPatchSchedules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry&gt; ListPatchSchedules ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry&gt; ListPatchSchedules() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisCachePremium.ListPatchSchedules" />
      <MemberSignature Language="VB.NET" Value="Public Function ListPatchSchedules () As IReadOnlyList(Of ScheduleEntry)" />
      <MemberSignature Language="F#" Value="abstract member ListPatchSchedules : unit -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry&gt;" Usage="iRedisCachePremium.ListPatchSchedules " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2a1bf-128">Ruft den Patchen Zeitplan für Redis-Cache ab.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-128">Gets the patching schedule for Redis Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2a1bf-129">Liste der Patch-Zeitpläne für die aktuelle Redis-Cache.</span><span class="sxs-lookup"><span data-stu-id="2a1bf-129">List of patch schedules for current Redis Cache.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>