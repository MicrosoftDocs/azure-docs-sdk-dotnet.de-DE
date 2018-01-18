<Type Name="PatchSchedulesOperationsExtensions" FullName="Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PatchSchedulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PatchSchedulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PatchSchedulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PatchSchedulesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="846a8-101">Erweiterungsmethoden für PatchSchedulesOperations.</span><span class="sxs-lookup"><span data-stu-id="846a8-101">Extension methods for PatchSchedulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule CreateOrUpdate (this Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule CreateOrUpdate(class Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Redis.IPatchSchedulesOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IPatchSchedulesOperations, resourceGroupName As String, name As String, parameters As RedisPatchSchedule) As RedisPatchSchedule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Redis.IPatchSchedulesOperations * string * string * Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule -&gt; Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule" Usage="Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="846a8-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="846a8-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="846a8-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="846a8-103">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="846a8-104">Der Name des Redis-Caches.</span><span class="sxs-lookup"><span data-stu-id="846a8-104">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="846a8-105">Parameter zum Festlegen des Patchen Zeitplans für Redis-Cache.</span><span class="sxs-lookup"><span data-stu-id="846a8-105">Parameters to set the patching schedule for Redis cache.</span></span>
            </param>
        <summary>
            <span data-ttu-id="846a8-106">Erstellen Sie oder Ersetzen Sie den Patchen Zeitplan für Redis-Cache (Premium SKU erfordert).</span><span class="sxs-lookup"><span data-stu-id="846a8-106">Create or replace the patching schedule for Redis cache (requires Premium SKU).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Redis.IPatchSchedulesOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Redis.IPatchSchedulesOperations * string * string * Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt;" Usage="Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="846a8-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="846a8-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="846a8-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="846a8-108">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="846a8-109">Der Name des Redis-Caches.</span><span class="sxs-lookup"><span data-stu-id="846a8-109">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="846a8-110">Parameter zum Festlegen des Patchen Zeitplans für Redis-Cache.</span><span class="sxs-lookup"><span data-stu-id="846a8-110">Parameters to set the patching schedule for Redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="846a8-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="846a8-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="846a8-112">Erstellen Sie oder Ersetzen Sie den Patchen Zeitplan für Redis-Cache (Premium SKU erfordert).</span><span class="sxs-lookup"><span data-stu-id="846a8-112">Create or replace the patching schedule for Redis cache (requires Premium SKU).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.Delete(Microsoft.Azure.Management.Redis.IPatchSchedulesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IPatchSchedulesOperations, resourceGroupName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Redis.IPatchSchedulesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.Delete (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="846a8-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="846a8-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="846a8-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="846a8-114">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="846a8-115">Der Name des Redis-Caches.</span><span class="sxs-lookup"><span data-stu-id="846a8-115">The name of the redis cache.</span></span>
            </param>
        <summary>
            <span data-ttu-id="846a8-116">Löscht das Patchen Zeitplan für einen Redis Cache (Premium SKU erfordert).</span><span class="sxs-lookup"><span data-stu-id="846a8-116">Deletes the patching schedule of a redis cache (requires Premium SKU).</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Redis.IPatchSchedulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Redis.IPatchSchedulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="846a8-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="846a8-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="846a8-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="846a8-118">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="846a8-119">Der Name des Redis-Caches.</span><span class="sxs-lookup"><span data-stu-id="846a8-119">The name of the redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="846a8-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="846a8-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="846a8-121">Löscht das Patchen Zeitplan für einen Redis Cache (Premium SKU erfordert).</span><span class="sxs-lookup"><span data-stu-id="846a8-121">Deletes the patching schedule of a redis cache (requires Premium SKU).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule Get (this Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule Get(class Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.Get(Microsoft.Azure.Management.Redis.IPatchSchedulesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPatchSchedulesOperations, resourceGroupName As String, name As String) As RedisPatchSchedule" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Redis.IPatchSchedulesOperations * string * string -&gt; Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule" Usage="Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.Get (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="846a8-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="846a8-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="846a8-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="846a8-123">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="846a8-124">Der Name des Redis-Caches.</span><span class="sxs-lookup"><span data-stu-id="846a8-124">The name of the redis cache.</span></span>
            </param>
        <summary>
            <span data-ttu-id="846a8-125">Ruft das Patchen Zeitplan für einen Redis Cache (Premium SKU erfordert).</span><span class="sxs-lookup"><span data-stu-id="846a8-125">Gets the patching schedule of a redis cache (requires Premium SKU).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt; GetAsync (this Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt; GetAsync(class Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Redis.IPatchSchedulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Redis.IPatchSchedulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt;" Usage="Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="846a8-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="846a8-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="846a8-127">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="846a8-127">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="846a8-128">Der Name des Redis-Caches.</span><span class="sxs-lookup"><span data-stu-id="846a8-128">The name of the redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="846a8-129">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="846a8-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="846a8-130">Ruft das Patchen Zeitplan für einen Redis Cache (Premium SKU erfordert).</span><span class="sxs-lookup"><span data-stu-id="846a8-130">Gets the patching schedule of a redis cache (requires Premium SKU).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>