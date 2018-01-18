<Type Name="RecordSetsOperationsExtensions" FullName="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecordSetsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecordSetsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecordSetsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecordSetsOperationsExtensions = class" />
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
            <span data-ttu-id="42a68-101">Erweiterungsmethoden für RecordSetsOperations.</span><span class="sxs-lookup"><span data-stu-id="42a68-101">Extension methods for RecordSetsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Dns.Models.RecordSet CreateOrUpdate (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Dns.Models.RecordSet CreateOrUpdate(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,Microsoft.Azure.Management.Dns.Models.RecordSet,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Microsoft.Azure.Management.Dns.Models.RecordSet * string * string -&gt; Microsoft.Azure.Management.Dns.Models.RecordSet" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Models.RecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.RecordSet" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="42a68-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="42a68-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="42a68-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="42a68-103">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="42a68-104">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="42a68-104">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="42a68-105">Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.</span><span class="sxs-lookup"><span data-stu-id="42a68-105">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="42a68-106">Der Typ des DNS-Eintrags in diesen Datensatz.</span><span class="sxs-lookup"><span data-stu-id="42a68-106">The type of DNS record in this record set.</span></span> <span data-ttu-id="42a68-107">Zeichnen Sie Sätze von Typ SOA aktualisiert, aber nicht erstellt werden kann (sie werden erstellt, wenn die DNS-Zone erstellt wird).</span><span class="sxs-lookup"><span data-stu-id="42a68-107">Record sets of type SOA can be updated but not created (they are created when the DNS zone is created).</span></span>
            <span data-ttu-id="42a68-108">Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"</span><span class="sxs-lookup"><span data-stu-id="42a68-108">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="42a68-109">Parameter für die CreateOrUpdate zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="42a68-109">Parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="42a68-110">Das Etag des Datensatzes festgelegt.</span><span class="sxs-lookup"><span data-stu-id="42a68-110">The etag of the record set.</span></span> <span data-ttu-id="42a68-111">Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="42a68-111">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="42a68-112">Geben Sie die letzten gesehen Etag-Wert, um versehentlich Overwritting keine gleichzeitigen geändert werden können.</span><span class="sxs-lookup"><span data-stu-id="42a68-112">Specify the last-seen etag value to prevent accidentally overwritting any concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="42a68-113">Legen Sie auf "\*" damit wird einen neuen Datensatz erstellt werden festgelegt, aber um zu verhindern, aktualisieren eine vorhandene Satz aufzeichnen.</span><span class="sxs-lookup"><span data-stu-id="42a68-113">Set to '\*' to allow a new record set to be created, but to prevent updating an existing record set.</span></span> <span data-ttu-id="42a68-114">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="42a68-114">Other values will be ignored.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42a68-115">Erstellt oder aktualisiert einen Datensatz in einer DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="42a68-115">Creates or updates a record set within a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,Microsoft.Azure.Management.Dns.Models.RecordSet,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Microsoft.Azure.Management.Dns.Models.RecordSet * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.RecordSet" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="42a68-116">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="42a68-116">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="42a68-117">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="42a68-117">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="42a68-118">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="42a68-118">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="42a68-119">Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.</span><span class="sxs-lookup"><span data-stu-id="42a68-119">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="42a68-120">Der Typ des DNS-Eintrags in diesen Datensatz.</span><span class="sxs-lookup"><span data-stu-id="42a68-120">The type of DNS record in this record set.</span></span> <span data-ttu-id="42a68-121">Zeichnen Sie Sätze von Typ SOA aktualisiert, aber nicht erstellt werden kann (sie werden erstellt, wenn die DNS-Zone erstellt wird).</span><span class="sxs-lookup"><span data-stu-id="42a68-121">Record sets of type SOA can be updated but not created (they are created when the DNS zone is created).</span></span>
            <span data-ttu-id="42a68-122">Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"</span><span class="sxs-lookup"><span data-stu-id="42a68-122">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="42a68-123">Parameter für die CreateOrUpdate zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="42a68-123">Parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="42a68-124">Das Etag des Datensatzes festgelegt.</span><span class="sxs-lookup"><span data-stu-id="42a68-124">The etag of the record set.</span></span> <span data-ttu-id="42a68-125">Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="42a68-125">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="42a68-126">Geben Sie die letzten gesehen Etag-Wert, um versehentlich Overwritting keine gleichzeitigen geändert werden können.</span><span class="sxs-lookup"><span data-stu-id="42a68-126">Specify the last-seen etag value to prevent accidentally overwritting any concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="42a68-127">Legen Sie auf "\*" damit wird einen neuen Datensatz erstellt werden festgelegt, aber um zu verhindern, aktualisieren eine vorhandene Satz aufzeichnen.</span><span class="sxs-lookup"><span data-stu-id="42a68-127">Set to '\*' to allow a new record set to be created, but to prevent updating an existing record set.</span></span> <span data-ttu-id="42a68-128">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="42a68-128">Other values will be ignored.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42a68-129">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42a68-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42a68-130">Erstellt oder aktualisiert einen Datensatz in einer DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="42a68-130">Creates or updates a record set within a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Delete(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * string -&gt; unit" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Delete (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="42a68-131">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="42a68-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="42a68-132">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="42a68-132">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="42a68-133">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="42a68-133">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="42a68-134">Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.</span><span class="sxs-lookup"><span data-stu-id="42a68-134">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="42a68-135">Der Typ des DNS-Eintrags in diesen Datensatz.</span><span class="sxs-lookup"><span data-stu-id="42a68-135">The type of DNS record in this record set.</span></span> <span data-ttu-id="42a68-136">Zeichnen Sie Sätze von Typ SOA kann nicht gelöscht werden (werden gelöscht, sobald die DNS-Zone gelöscht wird).</span><span class="sxs-lookup"><span data-stu-id="42a68-136">Record sets of type SOA cannot be deleted (they are deleted when the DNS zone is deleted).</span></span> <span data-ttu-id="42a68-137">Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"</span><span class="sxs-lookup"><span data-stu-id="42a68-137">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="42a68-138">Das Etag des Datensatzes festgelegt.</span><span class="sxs-lookup"><span data-stu-id="42a68-138">The etag of the record set.</span></span> <span data-ttu-id="42a68-139">Lassen Sie diesen Wert, um stets aktuelle Ressourceneintragssatz löschen.</span><span class="sxs-lookup"><span data-stu-id="42a68-139">Omit this value to always delete the current record set.</span></span> <span data-ttu-id="42a68-140">Geben Sie den letzten gesehen Etag-Wert, um zu verhindern, dass versehentliches Löschen von gleichzeitigen Änderungen.</span><span class="sxs-lookup"><span data-stu-id="42a68-140">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42a68-141">Löscht einen Datensatz aus einer DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="42a68-141">Deletes a record set from a DNS zone.</span></span> <span data-ttu-id="42a68-142">Dieser Vorgang kann nicht rückgängig gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="42a68-142">This operation cannot be undone.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.DeleteAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="42a68-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="42a68-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="42a68-144">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="42a68-144">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="42a68-145">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="42a68-145">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="42a68-146">Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.</span><span class="sxs-lookup"><span data-stu-id="42a68-146">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="42a68-147">Der Typ des DNS-Eintrags in diesen Datensatz.</span><span class="sxs-lookup"><span data-stu-id="42a68-147">The type of DNS record in this record set.</span></span> <span data-ttu-id="42a68-148">Zeichnen Sie Sätze von Typ SOA kann nicht gelöscht werden (werden gelöscht, sobald die DNS-Zone gelöscht wird).</span><span class="sxs-lookup"><span data-stu-id="42a68-148">Record sets of type SOA cannot be deleted (they are deleted when the DNS zone is deleted).</span></span> <span data-ttu-id="42a68-149">Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"</span><span class="sxs-lookup"><span data-stu-id="42a68-149">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="42a68-150">Das Etag des Datensatzes festgelegt.</span><span class="sxs-lookup"><span data-stu-id="42a68-150">The etag of the record set.</span></span> <span data-ttu-id="42a68-151">Lassen Sie diesen Wert, um stets aktuelle Ressourceneintragssatz löschen.</span><span class="sxs-lookup"><span data-stu-id="42a68-151">Omit this value to always delete the current record set.</span></span> <span data-ttu-id="42a68-152">Geben Sie den letzten gesehen Etag-Wert, um zu verhindern, dass versehentliches Löschen von gleichzeitigen Änderungen.</span><span class="sxs-lookup"><span data-stu-id="42a68-152">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42a68-153">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42a68-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42a68-154">Löscht einen Datensatz aus einer DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="42a68-154">Deletes a record set from a DNS zone.</span></span> <span data-ttu-id="42a68-155">Dieser Vorgang kann nicht rückgängig gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="42a68-155">This operation cannot be undone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Dns.Models.RecordSet Get (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Dns.Models.RecordSet Get(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Get(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType -&gt; Microsoft.Azure.Management.Dns.Models.RecordSet" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Get (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Models.RecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="42a68-156">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="42a68-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="42a68-157">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="42a68-157">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="42a68-158">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="42a68-158">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="42a68-159">Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.</span><span class="sxs-lookup"><span data-stu-id="42a68-159">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="42a68-160">Der Typ des DNS-Eintrags in diesen Datensatz.</span><span class="sxs-lookup"><span data-stu-id="42a68-160">The type of DNS record in this record set.</span></span> <span data-ttu-id="42a68-161">Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"</span><span class="sxs-lookup"><span data-stu-id="42a68-161">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <summary>
            <span data-ttu-id="42a68-162">Ruft einen Ressourceneintragssatz ab.</span><span class="sxs-lookup"><span data-stu-id="42a68-162">Gets a record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; GetAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; GetAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.GetAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="42a68-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="42a68-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="42a68-164">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="42a68-164">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="42a68-165">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="42a68-165">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="42a68-166">Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.</span><span class="sxs-lookup"><span data-stu-id="42a68-166">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="42a68-167">Der Typ des DNS-Eintrags in diesen Datensatz.</span><span class="sxs-lookup"><span data-stu-id="42a68-167">The type of DNS record in this record set.</span></span> <span data-ttu-id="42a68-168">Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"</span><span class="sxs-lookup"><span data-stu-id="42a68-168">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42a68-169">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42a68-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42a68-170">Ruft einen Ressourceneintragssatz ab.</span><span class="sxs-lookup"><span data-stu-id="42a68-170">Gets a record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZone">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByDnsZone (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByDnsZone(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZone(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDnsZone (operations As IRecordSetsOperations, resourceGroupName As String, zoneName As String, Optional top As Nullable(Of Integer) = null, Optional recordsetnamesuffix As String = null) As IPage(Of RecordSet)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZone : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * Nullable&lt;int&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZone (operations, resourceGroupName, zoneName, top, recordsetnamesuffix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="42a68-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="42a68-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="42a68-172">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="42a68-172">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="42a68-173">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="42a68-173">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="42a68-174">Die maximale Anzahl der zurückzugebenden Datensätze.</span><span class="sxs-lookup"><span data-stu-id="42a68-174">The maximum number of record sets to return.</span></span> <span data-ttu-id="42a68-175">Wenn nicht angegeben, gibt bis zu 100 Datensatzgruppen zurück.</span><span class="sxs-lookup"><span data-stu-id="42a68-175">If not specified, returns up to 100 record sets.</span></span>
            </param>
        <param name="recordsetnamesuffix">
            <span data-ttu-id="42a68-176">Die suffixbezeichnung des Namen der Datensatzgruppe, die verwendet werden, um den Datensatz Filtern festlegen Enumerationen.</span><span class="sxs-lookup"><span data-stu-id="42a68-176">The suffix label of the record set name that has to be used to filter the record set enumerations.</span></span> <span data-ttu-id="42a68-177">Wenn dieser Parameter angegeben wird, gibt die Enumeration nur Datensätze zurück, die mit enden. &lt;RecordSetNameSuffix&gt;</span><span class="sxs-lookup"><span data-stu-id="42a68-177">If this parameter is specified, Enumeration will return only records that end with .&lt;recordSetNameSuffix&gt;</span></span>
            </param>
        <summary>
            <span data-ttu-id="42a68-178">Listet alle Datensatzgruppen in einer DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="42a68-178">Lists all record sets in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByDnsZoneAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByDnsZoneAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZoneAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneAsync (operations, resourceGroupName, zoneName, top, recordsetnamesuffix, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;ListByDnsZoneAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="42a68-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="42a68-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="42a68-180">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="42a68-180">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="42a68-181">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="42a68-181">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="42a68-182">Die maximale Anzahl der zurückzugebenden Datensätze.</span><span class="sxs-lookup"><span data-stu-id="42a68-182">The maximum number of record sets to return.</span></span> <span data-ttu-id="42a68-183">Wenn nicht angegeben, gibt bis zu 100 Datensatzgruppen zurück.</span><span class="sxs-lookup"><span data-stu-id="42a68-183">If not specified, returns up to 100 record sets.</span></span>
            </param>
        <param name="recordsetnamesuffix">
            <span data-ttu-id="42a68-184">Die suffixbezeichnung des Namen der Datensatzgruppe, die verwendet werden, um den Datensatz Filtern festlegen Enumerationen.</span><span class="sxs-lookup"><span data-stu-id="42a68-184">The suffix label of the record set name that has to be used to filter the record set enumerations.</span></span> <span data-ttu-id="42a68-185">Wenn dieser Parameter angegeben wird, gibt die Enumeration nur Datensätze zurück, die mit enden. &lt;RecordSetNameSuffix&gt;</span><span class="sxs-lookup"><span data-stu-id="42a68-185">If this parameter is specified, Enumeration will return only records that end with .&lt;recordSetNameSuffix&gt;</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42a68-186">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42a68-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42a68-187">Listet alle Datensatzgruppen in einer DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="42a68-187">Lists all record sets in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByDnsZoneNext (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByDnsZoneNext(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneNext(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDnsZoneNext (operations As IRecordSetsOperations, nextPageLink As String) As IPage(Of RecordSet)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZoneNext : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="42a68-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="42a68-188">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="42a68-189">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="42a68-189">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42a68-190">Listet alle Datensatzgruppen in einer DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="42a68-190">Lists all record sets in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByDnsZoneNextAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByDnsZoneNextAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneNextAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZoneNextAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;ListByDnsZoneNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="42a68-191">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="42a68-191">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="42a68-192">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="42a68-192">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42a68-193">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42a68-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42a68-194">Listet alle Datensatzgruppen in einer DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="42a68-194">Lists all record sets in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByType">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByType (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByType(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByType(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="F#" Value="static member ListByType : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Nullable&lt;int&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByType (operations, resourceGroupName, zoneName, recordType, top, recordsetnamesuffix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="42a68-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="42a68-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="42a68-196">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="42a68-196">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="42a68-197">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="42a68-197">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="42a68-198">Der Typ der Datensatzgruppen aufgelistet werden.</span><span class="sxs-lookup"><span data-stu-id="42a68-198">The type of record sets to enumerate.</span></span> <span data-ttu-id="42a68-199">Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"</span><span class="sxs-lookup"><span data-stu-id="42a68-199">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="42a68-200">Die maximale Anzahl der zurückzugebenden Datensätze.</span><span class="sxs-lookup"><span data-stu-id="42a68-200">The maximum number of record sets to return.</span></span> <span data-ttu-id="42a68-201">Wenn nicht angegeben, gibt bis zu 100 Datensatzgruppen zurück.</span><span class="sxs-lookup"><span data-stu-id="42a68-201">If not specified, returns up to 100 record sets.</span></span>
            </param>
        <param name="recordsetnamesuffix">
            <span data-ttu-id="42a68-202">Die suffixbezeichnung des Namen der Datensatzgruppe, die verwendet werden, um den Datensatz Filtern festlegen Enumerationen.</span><span class="sxs-lookup"><span data-stu-id="42a68-202">The suffix label of the record set name that has to be used to filter the record set enumerations.</span></span> <span data-ttu-id="42a68-203">Wenn dieser Parameter angegeben wird, gibt die Enumeration nur Datensätze zurück, die mit enden. &lt;RecordSetNameSuffix&gt;</span><span class="sxs-lookup"><span data-stu-id="42a68-203">If this parameter is specified, Enumeration will return only records that end with .&lt;recordSetNameSuffix&gt;</span></span>
            </param>
        <summary>
            <span data-ttu-id="42a68-204">Listet die Datensatzgruppen eines angegebenen Typs in einer DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="42a68-204">Lists the record sets of a specified type in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByTypeAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByTypeAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTypeAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeAsync (operations, resourceGroupName, zoneName, recordType, top, recordsetnamesuffix, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;ListByTypeAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="42a68-205">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="42a68-205">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="42a68-206">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="42a68-206">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="42a68-207">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="42a68-207">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="42a68-208">Der Typ der Datensatzgruppen aufgelistet werden.</span><span class="sxs-lookup"><span data-stu-id="42a68-208">The type of record sets to enumerate.</span></span> <span data-ttu-id="42a68-209">Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"</span><span class="sxs-lookup"><span data-stu-id="42a68-209">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="42a68-210">Die maximale Anzahl der zurückzugebenden Datensätze.</span><span class="sxs-lookup"><span data-stu-id="42a68-210">The maximum number of record sets to return.</span></span> <span data-ttu-id="42a68-211">Wenn nicht angegeben, gibt bis zu 100 Datensatzgruppen zurück.</span><span class="sxs-lookup"><span data-stu-id="42a68-211">If not specified, returns up to 100 record sets.</span></span>
            </param>
        <param name="recordsetnamesuffix">
            <span data-ttu-id="42a68-212">Die suffixbezeichnung des Namen der Datensatzgruppe, die verwendet werden, um den Datensatz Filtern festlegen Enumerationen.</span><span class="sxs-lookup"><span data-stu-id="42a68-212">The suffix label of the record set name that has to be used to filter the record set enumerations.</span></span> <span data-ttu-id="42a68-213">Wenn dieser Parameter angegeben wird, gibt die Enumeration nur Datensätze zurück, die mit enden. &lt;RecordSetNameSuffix&gt;</span><span class="sxs-lookup"><span data-stu-id="42a68-213">If this parameter is specified, Enumeration will return only records that end with .&lt;recordSetNameSuffix&gt;</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42a68-214">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42a68-214">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42a68-215">Listet die Datensatzgruppen eines angegebenen Typs in einer DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="42a68-215">Lists the record sets of a specified type in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByTypeNext (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByTypeNext(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeNext(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByTypeNext (operations As IRecordSetsOperations, nextPageLink As String) As IPage(Of RecordSet)" />
      <MemberSignature Language="F#" Value="static member ListByTypeNext : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="42a68-216">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="42a68-216">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="42a68-217">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="42a68-217">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42a68-218">Listet die Datensatzgruppen eines angegebenen Typs in einer DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="42a68-218">Lists the record sets of a specified type in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByTypeNextAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByTypeNextAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeNextAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTypeNextAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;ListByTypeNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="42a68-219">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="42a68-219">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="42a68-220">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="42a68-220">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42a68-221">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42a68-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42a68-222">Listet die Datensatzgruppen eines angegebenen Typs in einer DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="42a68-222">Lists the record sets of a specified type in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Dns.Models.RecordSet Update (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Dns.Models.RecordSet Update(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Update(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,Microsoft.Azure.Management.Dns.Models.RecordSet,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Microsoft.Azure.Management.Dns.Models.RecordSet * string -&gt; Microsoft.Azure.Management.Dns.Models.RecordSet" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Update (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Models.RecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.RecordSet" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="42a68-223">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="42a68-223">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="42a68-224">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="42a68-224">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="42a68-225">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="42a68-225">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="42a68-226">Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.</span><span class="sxs-lookup"><span data-stu-id="42a68-226">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="42a68-227">Der Typ des DNS-Eintrags in diesen Datensatz.</span><span class="sxs-lookup"><span data-stu-id="42a68-227">The type of DNS record in this record set.</span></span> <span data-ttu-id="42a68-228">Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"</span><span class="sxs-lookup"><span data-stu-id="42a68-228">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="42a68-229">Parameter, die auf den Updatevorgang angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="42a68-229">Parameters supplied to the Update operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="42a68-230">Das Etag des Datensatzes festgelegt.</span><span class="sxs-lookup"><span data-stu-id="42a68-230">The etag of the record set.</span></span> <span data-ttu-id="42a68-231">Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="42a68-231">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="42a68-232">Geben Sie die letzten gesehen Etag-Wert, um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="42a68-232">Specify the last-seen etag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42a68-233">Aktualisiert einen Datensatz in einer DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="42a68-233">Updates a record set within a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; UpdateAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; UpdateAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,Microsoft.Azure.Management.Dns.Models.RecordSet,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Microsoft.Azure.Management.Dns.Models.RecordSet * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.UpdateAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;UpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.RecordSet" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="42a68-234">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="42a68-234">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="42a68-235">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="42a68-235">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="42a68-236">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="42a68-236">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="42a68-237">Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.</span><span class="sxs-lookup"><span data-stu-id="42a68-237">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="42a68-238">Der Typ des DNS-Eintrags in diesen Datensatz.</span><span class="sxs-lookup"><span data-stu-id="42a68-238">The type of DNS record in this record set.</span></span> <span data-ttu-id="42a68-239">Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"</span><span class="sxs-lookup"><span data-stu-id="42a68-239">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="42a68-240">Parameter, die auf den Updatevorgang angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="42a68-240">Parameters supplied to the Update operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="42a68-241">Das Etag des Datensatzes festgelegt.</span><span class="sxs-lookup"><span data-stu-id="42a68-241">The etag of the record set.</span></span> <span data-ttu-id="42a68-242">Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="42a68-242">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="42a68-243">Geben Sie die letzten gesehen Etag-Wert, um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="42a68-243">Specify the last-seen etag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42a68-244">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42a68-244">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42a68-245">Aktualisiert einen Datensatz in einer DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="42a68-245">Updates a record set within a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>