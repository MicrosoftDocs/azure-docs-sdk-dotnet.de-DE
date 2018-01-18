<Type Name="IUpdate" FullName="Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate">
  <TypeSignature Language="C#" Value="public interface IUpdate : Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithNonSslPort, Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithRedisConfiguration, Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithSku, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IUpdate implements class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithNonSslPort, class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithRedisConfiguration, class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithSku, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags`1&lt;class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable`1&lt;class Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IUpdate&#xA;Implements IAppliable(Of IRedisCache), IUpdateWithTags(Of IUpdate), IWithNonSslPort, IWithRedisConfiguration, IWithSku" />
  <TypeSignature Language="F#" Value="type IUpdate = interface&#xA;    interface IAppliable&lt;IRedisCache&gt;&#xA;    interface IIndexable&#xA;    interface IUpdateWithTags&lt;IUpdate&gt;&#xA;    interface IWithSku&#xA;    interface IWithNonSslPort&#xA;    interface IWithRedisConfiguration" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithNonSslPort</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithRedisConfiguration</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithSku</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="5aca2-101">Die Vorlage für einen Redis-Cache: Update-Vorgang mit den Einstellungen aus, die geändert werden können.</span><span class="sxs-lookup"><span data-stu-id="5aca2-101">The template for a Redis Cache update operation, containing all the settings that can be modified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPatchSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithPatchSchedule (Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry scheduleEntry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithPatchSchedule(class Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry scheduleEntry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate.WithPatchSchedule(Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry)" />
      <MemberSignature Language="F#" Value="abstract member WithPatchSchedule : Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iUpdate.WithPatchSchedule scheduleEntry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scheduleEntry" Type="Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry" />
      </Parameters>
      <Docs>
        <param name="scheduleEntry"><span data-ttu-id="5aca2-102">Patch für Zeitplaneintrag für Premium-Redis-Cache.</span><span class="sxs-lookup"><span data-stu-id="5aca2-102">Patch schedule entry for Premium Redis Cache.</span></span></param>
        <summary>
            <span data-ttu-id="5aca2-103">Patch für den Zeitplan für einen Cache der Premium-Cluster.</span><span class="sxs-lookup"><span data-stu-id="5aca2-103">Patch schedule on a Premium Cluster Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5aca2-104">die nächste Phase des Redis-Cache mit Premium SKU-Definition.</span><span class="sxs-lookup"><span data-stu-id="5aca2-104">The next stage of Redis Cache with Premium SKU definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPatchSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithPatchSchedule (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry&gt; scheduleEntry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithPatchSchedule(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry&gt; scheduleEntry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate.WithPatchSchedule(System.Collections.Generic.IList{Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPatchSchedule (scheduleEntry As IList(Of ScheduleEntry)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPatchSchedule : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry&gt; -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iUpdate.WithPatchSchedule scheduleEntry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scheduleEntry" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry&gt;" />
      </Parameters>
      <Docs>
        <param name="scheduleEntry"><span data-ttu-id="5aca2-105">Liste der Patch-Zeitplan-Einträge für Premium-Redis-Cache.</span><span class="sxs-lookup"><span data-stu-id="5aca2-105">List of patch schedule entries for Premium Redis Cache.</span></span></param>
        <summary>
            <span data-ttu-id="5aca2-106">Patch für den Zeitplan für einen Cache der Premium-Cluster.</span><span class="sxs-lookup"><span data-stu-id="5aca2-106">Patch schedule on a Premium Cluster Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5aca2-107">die nächste Phase des Redis-Cache mit Premium SKU-Definition.</span><span class="sxs-lookup"><span data-stu-id="5aca2-107">The next stage of Redis Cache with Premium SKU definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPatchSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithPatchSchedule (Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek dayOfWeek, int startHourUtc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithPatchSchedule(valuetype Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek dayOfWeek, int32 startHourUtc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate.WithPatchSchedule(Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek,System.Int32)" />
      <MemberSignature Language="F#" Value="abstract member WithPatchSchedule : Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek * int -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iUpdate.WithPatchSchedule (dayOfWeek, startHourUtc)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dayOfWeek" Type="Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek" />
        <Parameter Name="startHourUtc" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="dayOfWeek"><span data-ttu-id="5aca2-108">Tag der Woche Wenn Cache Patch angewendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="5aca2-108">Day of week when cache can be patched.</span></span></param>
        <param name="startHourUtc"><span data-ttu-id="5aca2-109">Starten Sie die Stunde nach der Cache Patchen starten kann.</span><span class="sxs-lookup"><span data-stu-id="5aca2-109">Start hour after which cache patching can start.</span></span></param>
        <summary>
            <span data-ttu-id="5aca2-110">Patch für den Zeitplan für einen Cache der Premium-Cluster.</span><span class="sxs-lookup"><span data-stu-id="5aca2-110">Patch schedule on a Premium Cluster Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5aca2-111">die nächste Phase des Redis-Cache mit Premium SKU-Definition.</span><span class="sxs-lookup"><span data-stu-id="5aca2-111">The next stage of Redis Cache with Premium SKU definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPatchSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithPatchSchedule (Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek dayOfWeek, int startHourUtc, TimeSpan maintenanceWindow);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithPatchSchedule(valuetype Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek dayOfWeek, int32 startHourUtc, valuetype System.TimeSpan maintenanceWindow) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate.WithPatchSchedule(Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek,System.Int32,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member WithPatchSchedule : Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek * int * TimeSpan -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iUpdate.WithPatchSchedule (dayOfWeek, startHourUtc, maintenanceWindow)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dayOfWeek" Type="Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek" />
        <Parameter Name="startHourUtc" Type="System.Int32" />
        <Parameter Name="maintenanceWindow" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="dayOfWeek"><span data-ttu-id="5aca2-112">Tag der Woche Wenn Cache Patch angewendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="5aca2-112">Day of week when cache can be patched.</span></span></param>
        <param name="startHourUtc"><span data-ttu-id="5aca2-113">Starten Sie die Stunde nach der Cache Patchen starten kann.</span><span class="sxs-lookup"><span data-stu-id="5aca2-113">Start hour after which cache patching can start.</span></span></param>
        <param name="maintenanceWindow"><span data-ttu-id="5aca2-114">ISO8601-Zeitspanne angeben, wie viel Zeit Cache Patchen ergreifen kann.</span><span class="sxs-lookup"><span data-stu-id="5aca2-114">ISO8601 timespan specifying how much time cache patching can take.</span></span></param>
        <summary>
            <span data-ttu-id="5aca2-115">Die Anzahl der Shards auf eine Premium-Cache-Cluster erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5aca2-115">The number of shards to be created on a Premium Cluster Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5aca2-116">die nächste Phase des Redis-Cache mit Premium SKU-Definition.</span><span class="sxs-lookup"><span data-stu-id="5aca2-116">The next stage of Redis Cache with Premium SKU definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithShardCount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithShardCount (int shardCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithShardCount(int32 shardCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate.WithShardCount(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithShardCount (shardCount As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithShardCount : int -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iUpdate.WithShardCount shardCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="shardCount"><span data-ttu-id="5aca2-117">der Wert für die Shard festlegen.</span><span class="sxs-lookup"><span data-stu-id="5aca2-117">The shard count value to set.</span></span></param>
        <summary>
            <span data-ttu-id="5aca2-118">Die Anzahl der Shards auf eine Premium-Cache-Cluster erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5aca2-118">The number of shards to be created on a Premium Cluster Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5aca2-119">die nächste Phase des Redis-Cache aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="5aca2-119">The next stage of Redis Cache update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStaticIP">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithStaticIP (string staticIP);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithStaticIP(string staticIP) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate.WithStaticIP(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStaticIP (staticIP As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithStaticIP : string -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iUpdate.WithStaticIP staticIP" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="staticIP" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="staticIP"><span data-ttu-id="5aca2-120">Der festzulegende StaticIP-Wert.</span><span class="sxs-lookup"><span data-stu-id="5aca2-120">The staticIP value to set.</span></span></param>
        <summary>
            <span data-ttu-id="5aca2-121">Legt die Redis-Cache: statische IP-Adresse fest.</span><span class="sxs-lookup"><span data-stu-id="5aca2-121">Sets Redis Cache static IP.</span></span> <span data-ttu-id="5aca2-122">Erforderlich, wenn Sie einen Redis Cache in einem vorhandenen virtuellen Azure-Netzwerk bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="5aca2-122">Required when deploying a Redis Cache inside an existing Azure Virtual Network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5aca2-123">die nächste Phase des Redis-Cache aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="5aca2-123">The next stage of Redis Cache update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithSubnet (Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId networkResource, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithSubnet(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId networkResource, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate.WithSubnet(Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnet (networkResource As IHasId, subnetName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithSubnet : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId * string -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iUpdate.WithSubnet (networkResource, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="networkResource" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="networkResource"><span data-ttu-id="5aca2-124">die Instanz des Netzwerk-Objekts.</span><span class="sxs-lookup"><span data-stu-id="5aca2-124">Instance of Network object.</span></span></param>
        <param name="subnetName"><span data-ttu-id="5aca2-125">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="5aca2-125">The name of the subnet.</span></span></param>
        <summary>
            <span data-ttu-id="5aca2-126">Weist das angegebene Subnetz für diese Instanz des Redis-Cache.</span><span class="sxs-lookup"><span data-stu-id="5aca2-126">Assigns the specified subnet to this instance of Redis Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5aca2-127">die nächste Phase des Redis-Cache aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="5aca2-127">The next stage of Redis Cache update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>