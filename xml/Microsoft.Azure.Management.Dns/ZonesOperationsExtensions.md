<Type Name="ZonesOperationsExtensions" FullName="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ZonesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ZonesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ZonesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ZonesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1520b-101">Erweiterungsmethoden für ZonesOperations.</span><span class="sxs-lookup"><span data-stu-id="1520b-101">Extension methods for ZonesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IZonesOperations, resourceGroupName As String, zoneName As String, Optional ifMatch As String = null)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.BeginDelete (operations, resourceGroupName, zoneName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1520b-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1520b-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1520b-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1520b-103">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="1520b-104">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="1520b-104">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="1520b-105">Das Etag der DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="1520b-105">The etag of the DNS zone.</span></span> <span data-ttu-id="1520b-106">Lassen Sie diesen Wert, um immer die aktuellen Zone löschen.</span><span class="sxs-lookup"><span data-stu-id="1520b-106">Omit this value to always delete the current zone.</span></span> <span data-ttu-id="1520b-107">Geben Sie den letzten gesehen Etag-Wert, um zu verhindern, dass versehentliches Löschen von gleichzeitigen Änderungen.</span><span class="sxs-lookup"><span data-stu-id="1520b-107">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1520b-108">Löscht eine DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="1520b-108">Deletes a DNS zone.</span></span> <span data-ttu-id="1520b-109">Warnung: Alle DNS-Einträge in der Zone werden ebenfalls gelöscht.</span><span class="sxs-lookup"><span data-stu-id="1520b-109">WARNING: All DNS records in the zone will also be deleted.</span></span> <span data-ttu-id="1520b-110">Dieser Vorgang kann nicht rückgängig gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="1520b-110">This operation cannot be undone.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, zoneName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1520b-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1520b-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1520b-112">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1520b-112">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="1520b-113">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="1520b-113">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="1520b-114">Das Etag der DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="1520b-114">The etag of the DNS zone.</span></span> <span data-ttu-id="1520b-115">Lassen Sie diesen Wert, um immer die aktuellen Zone löschen.</span><span class="sxs-lookup"><span data-stu-id="1520b-115">Omit this value to always delete the current zone.</span></span> <span data-ttu-id="1520b-116">Geben Sie den letzten gesehen Etag-Wert, um zu verhindern, dass versehentliches Löschen von gleichzeitigen Änderungen.</span><span class="sxs-lookup"><span data-stu-id="1520b-116">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1520b-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1520b-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1520b-118">Löscht eine DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="1520b-118">Deletes a DNS zone.</span></span> <span data-ttu-id="1520b-119">Warnung: Alle DNS-Einträge in der Zone werden ebenfalls gelöscht.</span><span class="sxs-lookup"><span data-stu-id="1520b-119">WARNING: All DNS records in the zone will also be deleted.</span></span> <span data-ttu-id="1520b-120">Dieser Vorgang kann nicht rückgängig gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="1520b-120">This operation cannot be undone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Dns.Models.Zone CreateOrUpdate (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Models.Zone parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Dns.Models.Zone CreateOrUpdate(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, class Microsoft.Azure.Management.Dns.Models.Zone parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Models.Zone,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IZonesOperations, resourceGroupName As String, zoneName As String, parameters As Zone, Optional ifMatch As String = null, Optional ifNoneMatch As String = null) As Zone" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * Microsoft.Azure.Management.Dns.Models.Zone * string * string -&gt; Microsoft.Azure.Management.Dns.Models.Zone" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, zoneName, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Models.Zone</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.Zone" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1520b-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1520b-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1520b-122">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1520b-122">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="1520b-123">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="1520b-123">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1520b-124">Parameter für die CreateOrUpdate zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="1520b-124">Parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="1520b-125">Das Etag der DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="1520b-125">The etag of the DNS zone.</span></span> <span data-ttu-id="1520b-126">Lassen Sie diesen Wert, um die aktuelle Zone immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="1520b-126">Omit this value to always overwrite the current zone.</span></span> <span data-ttu-id="1520b-127">Geben Sie die letzten gesehen Etag-Wert, um versehentlich Overwritting keine gleichzeitigen geändert werden können.</span><span class="sxs-lookup"><span data-stu-id="1520b-127">Specify the last-seen etag value to prevent accidentally overwritting any concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="1520b-128">Legen Sie auf "\*" um eine neue DNS-Zone erstellt werden, sondern um zu verhindern, Aktualisieren einer vorhandenen Zone zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="1520b-128">Set to '\*' to allow a new DNS zone to be created, but to prevent updating an existing zone.</span></span> <span data-ttu-id="1520b-129">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="1520b-129">Other values will be ignored.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1520b-130">Erstellt oder aktualisiert eine DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="1520b-130">Creates or updates a DNS zone.</span></span> <span data-ttu-id="1520b-131">DNS-Einträge in der Zone werden nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="1520b-131">Does not modify DNS records within the zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Models.Zone parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, class Microsoft.Azure.Management.Dns.Models.Zone parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Models.Zone,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * Microsoft.Azure.Management.Dns.Models.Zone * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, zoneName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.Zone" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1520b-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1520b-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1520b-133">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1520b-133">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="1520b-134">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="1520b-134">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1520b-135">Parameter für die CreateOrUpdate zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="1520b-135">Parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="1520b-136">Das Etag der DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="1520b-136">The etag of the DNS zone.</span></span> <span data-ttu-id="1520b-137">Lassen Sie diesen Wert, um die aktuelle Zone immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="1520b-137">Omit this value to always overwrite the current zone.</span></span> <span data-ttu-id="1520b-138">Geben Sie die letzten gesehen Etag-Wert, um versehentlich Overwritting keine gleichzeitigen geändert werden können.</span><span class="sxs-lookup"><span data-stu-id="1520b-138">Specify the last-seen etag value to prevent accidentally overwritting any concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="1520b-139">Legen Sie auf "\*" um eine neue DNS-Zone erstellt werden, sondern um zu verhindern, Aktualisieren einer vorhandenen Zone zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="1520b-139">Set to '\*' to allow a new DNS zone to be created, but to prevent updating an existing zone.</span></span> <span data-ttu-id="1520b-140">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="1520b-140">Other values will be ignored.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1520b-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1520b-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1520b-142">Erstellt oder aktualisiert eine DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="1520b-142">Creates or updates a DNS zone.</span></span> <span data-ttu-id="1520b-143">DNS-Einträge in der Zone werden nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="1520b-143">Does not modify DNS records within the zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.Delete(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IZonesOperations, resourceGroupName As String, zoneName As String, Optional ifMatch As String = null)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.Delete (operations, resourceGroupName, zoneName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1520b-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1520b-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1520b-145">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1520b-145">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="1520b-146">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="1520b-146">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="1520b-147">Das Etag der DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="1520b-147">The etag of the DNS zone.</span></span> <span data-ttu-id="1520b-148">Lassen Sie diesen Wert, um immer die aktuellen Zone löschen.</span><span class="sxs-lookup"><span data-stu-id="1520b-148">Omit this value to always delete the current zone.</span></span> <span data-ttu-id="1520b-149">Geben Sie den letzten gesehen Etag-Wert, um zu verhindern, dass versehentliches Löschen von gleichzeitigen Änderungen.</span><span class="sxs-lookup"><span data-stu-id="1520b-149">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1520b-150">Löscht eine DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="1520b-150">Deletes a DNS zone.</span></span> <span data-ttu-id="1520b-151">Warnung: Alle DNS-Einträge in der Zone werden ebenfalls gelöscht.</span><span class="sxs-lookup"><span data-stu-id="1520b-151">WARNING: All DNS records in the zone will also be deleted.</span></span> <span data-ttu-id="1520b-152">Dieser Vorgang kann nicht rückgängig gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="1520b-152">This operation cannot be undone.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.DeleteAsync (operations, resourceGroupName, zoneName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1520b-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1520b-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1520b-154">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1520b-154">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="1520b-155">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="1520b-155">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="1520b-156">Das Etag der DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="1520b-156">The etag of the DNS zone.</span></span> <span data-ttu-id="1520b-157">Lassen Sie diesen Wert, um immer die aktuellen Zone löschen.</span><span class="sxs-lookup"><span data-stu-id="1520b-157">Omit this value to always delete the current zone.</span></span> <span data-ttu-id="1520b-158">Geben Sie den letzten gesehen Etag-Wert, um zu verhindern, dass versehentliches Löschen von gleichzeitigen Änderungen.</span><span class="sxs-lookup"><span data-stu-id="1520b-158">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1520b-159">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1520b-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1520b-160">Löscht eine DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="1520b-160">Deletes a DNS zone.</span></span> <span data-ttu-id="1520b-161">Warnung: Alle DNS-Einträge in der Zone werden ebenfalls gelöscht.</span><span class="sxs-lookup"><span data-stu-id="1520b-161">WARNING: All DNS records in the zone will also be deleted.</span></span> <span data-ttu-id="1520b-162">Dieser Vorgang kann nicht rückgängig gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="1520b-162">This operation cannot be undone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Dns.Models.Zone Get (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Dns.Models.Zone Get(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.Get(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IZonesOperations, resourceGroupName As String, zoneName As String) As Zone" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Dns.IZonesOperations * string * string -&gt; Microsoft.Azure.Management.Dns.Models.Zone" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.Get (operations, resourceGroupName, zoneName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Models.Zone</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1520b-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1520b-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1520b-164">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1520b-164">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="1520b-165">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="1520b-165">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <summary>
            <span data-ttu-id="1520b-166">Ruft eine DNS-Zone ab.</span><span class="sxs-lookup"><span data-stu-id="1520b-166">Gets a DNS zone.</span></span> <span data-ttu-id="1520b-167">Ruft ab den Zoneneigenschaften, aber nicht der Datensatzgruppen in der Zone.</span><span class="sxs-lookup"><span data-stu-id="1520b-167">Retrieves the zone properties, but not the record sets within the zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; GetAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; GetAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.GetAsync (operations, resourceGroupName, zoneName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1520b-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1520b-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1520b-169">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1520b-169">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="1520b-170">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="1520b-170">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1520b-171">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1520b-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1520b-172">Ruft eine DNS-Zone ab.</span><span class="sxs-lookup"><span data-stu-id="1520b-172">Gets a DNS zone.</span></span> <span data-ttu-id="1520b-173">Ruft ab den Zoneneigenschaften, aber nicht der Datensatzgruppen in der Zone.</span><span class="sxs-lookup"><span data-stu-id="1520b-173">Retrieves the zone properties, but not the record sets within the zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; List (this Microsoft.Azure.Management.Dns.IZonesOperations operations, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; List(class Microsoft.Azure.Management.Dns.IZonesOperations operations, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.List(Microsoft.Azure.Management.Dns.IZonesOperations,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IZonesOperations, Optional top As Nullable(Of Integer) = null) As IPage(Of Zone)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Dns.IZonesOperations * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.List (operations, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1520b-174">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1520b-174">The operations group for this extension method.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="1520b-175">Die maximale Anzahl von DNS-Zonen, die zurückgegeben werden soll.</span><span class="sxs-lookup"><span data-stu-id="1520b-175">The maximum number of DNS zones to return.</span></span> <span data-ttu-id="1520b-176">Wenn nicht angegeben, gibt bis zu 100 Zonen zurück.</span><span class="sxs-lookup"><span data-stu-id="1520b-176">If not specified, returns up to 100 zones.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1520b-177">Listet die DNS-Zonen in allen Ressourcengruppen in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="1520b-177">Lists the DNS zones in all resource groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Dns.IZonesOperations * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListAsync (operations, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1520b-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1520b-178">The operations group for this extension method.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="1520b-179">Die maximale Anzahl von DNS-Zonen, die zurückgegeben werden soll.</span><span class="sxs-lookup"><span data-stu-id="1520b-179">The maximum number of DNS zones to return.</span></span> <span data-ttu-id="1520b-180">Wenn nicht angegeben, gibt bis zu 100 Zonen zurück.</span><span class="sxs-lookup"><span data-stu-id="1520b-180">If not specified, returns up to 100 zones.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1520b-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1520b-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1520b-182">Listet die DNS-Zonen in allen Ressourcengruppen in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="1520b-182">Lists the DNS zones in all resource groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; ListByResourceGroup (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; ListByResourceGroup(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IZonesOperations, resourceGroupName As String, Optional top As Nullable(Of Integer) = null) As IPage(Of Zone)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Dns.IZonesOperations * string * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1520b-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1520b-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1520b-184">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1520b-184">The name of the resource group.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="1520b-185">Die maximale Anzahl der zurückzugebenden Datensätze.</span><span class="sxs-lookup"><span data-stu-id="1520b-185">The maximum number of record sets to return.</span></span> <span data-ttu-id="1520b-186">Wenn nicht angegeben, gibt bis zu 100 Datensatzgruppen zurück.</span><span class="sxs-lookup"><span data-stu-id="1520b-186">If not specified, returns up to 100 record sets.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1520b-187">Listet die DNS-Zonen innerhalb einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1520b-187">Lists the DNS zones within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1520b-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1520b-188">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1520b-189">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1520b-189">The name of the resource group.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="1520b-190">Die maximale Anzahl der zurückzugebenden Datensätze.</span><span class="sxs-lookup"><span data-stu-id="1520b-190">The maximum number of record sets to return.</span></span> <span data-ttu-id="1520b-191">Wenn nicht angegeben, gibt bis zu 100 Datensatzgruppen zurück.</span><span class="sxs-lookup"><span data-stu-id="1520b-191">If not specified, returns up to 100 record sets.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1520b-192">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1520b-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1520b-193">Listet die DNS-Zonen innerhalb einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1520b-193">Lists the DNS zones within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Dns.IZonesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IZonesOperations, nextPageLink As String) As IPage(Of Zone)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Dns.IZonesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1520b-194">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1520b-194">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1520b-195">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1520b-195">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1520b-196">Listet die DNS-Zonen innerhalb einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1520b-196">Lists the DNS zones within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1520b-197">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1520b-197">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1520b-198">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1520b-198">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1520b-199">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1520b-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1520b-200">Listet die DNS-Zonen innerhalb einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1520b-200">Lists the DNS zones within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; ListNext (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; ListNext(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListNext(Microsoft.Azure.Management.Dns.IZonesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IZonesOperations, nextPageLink As String) As IPage(Of Zone)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Dns.IZonesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1520b-201">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1520b-201">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1520b-202">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1520b-202">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1520b-203">Listet die DNS-Zonen in allen Ressourcengruppen in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="1520b-203">Lists the DNS zones in all resource groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1520b-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1520b-204">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1520b-205">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1520b-205">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1520b-206">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1520b-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1520b-207">Listet die DNS-Zonen in allen Ressourcengruppen in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="1520b-207">Lists the DNS zones in all resource groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>