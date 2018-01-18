<Type Name="RecordSetsOperationsExtensions" FullName="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecordSetsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecordSetsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecordSetsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecordSetsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="14c83-101">Erweiterungsmethoden für RecordSetsOperations.</span><span class="sxs-lookup"><span data-stu-id="14c83-101">Extension methods for RecordSetsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="14c83-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="14c83-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="14c83-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="14c83-103">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="14c83-104">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="14c83-104">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="14c83-105">Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.</span><span class="sxs-lookup"><span data-stu-id="14c83-105">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="14c83-106">Der Typ des DNS-Eintrags in diesen Datensatz.</span><span class="sxs-lookup"><span data-stu-id="14c83-106">The type of DNS record in this record set.</span></span> <span data-ttu-id="14c83-107">Zeichnen Sie Sätze von Typ SOA aktualisiert, aber nicht erstellt werden kann (sie werden erstellt, wenn die DNS-Zone erstellt wird).</span><span class="sxs-lookup"><span data-stu-id="14c83-107">Record sets of type SOA can be updated but not created (they are created when the DNS zone is created).</span></span>
            <span data-ttu-id="14c83-108">Folgende Werte sind möglich: "A", "AAAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"</span><span class="sxs-lookup"><span data-stu-id="14c83-108">Possible values include: 'A', 'AAAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="14c83-109">Parameter für die CreateOrUpdate zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="14c83-109">Parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="14c83-110">Das Etag des Datensatzes festgelegt.</span><span class="sxs-lookup"><span data-stu-id="14c83-110">The etag of the record set.</span></span> <span data-ttu-id="14c83-111">Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="14c83-111">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="14c83-112">Geben Sie die letzten gesehen Etag-Wert, um versehentlich Overwritting keine gleichzeitigen geändert werden können.</span><span class="sxs-lookup"><span data-stu-id="14c83-112">Specify the last-seen etag value to prevent accidentally overwritting any concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="14c83-113">Legen Sie auf "\*" damit wird einen neuen Datensatz erstellt werden festgelegt, aber um zu verhindern, aktualisieren eine vorhandene Satz aufzeichnen.</span><span class="sxs-lookup"><span data-stu-id="14c83-113">Set to '\*' to allow a new record set to be created, but to prevent updating an existing record set.</span></span> <span data-ttu-id="14c83-114">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="14c83-114">Other values will be ignored.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="14c83-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="14c83-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="14c83-116">Erstellt oder aktualisiert einen Datensatz in einer DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="14c83-116">Creates or updates a record set within a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.DeleteAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="14c83-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="14c83-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="14c83-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="14c83-118">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="14c83-119">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="14c83-119">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="14c83-120">Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.</span><span class="sxs-lookup"><span data-stu-id="14c83-120">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="14c83-121">Der Typ des DNS-Eintrags in diesen Datensatz.</span><span class="sxs-lookup"><span data-stu-id="14c83-121">The type of DNS record in this record set.</span></span> <span data-ttu-id="14c83-122">Zeichnen Sie Sätze von Typ SOA kann nicht gelöscht werden (werden gelöscht, sobald die DNS-Zone gelöscht wird).</span><span class="sxs-lookup"><span data-stu-id="14c83-122">Record sets of type SOA cannot be deleted (they are deleted when the DNS zone is deleted).</span></span> <span data-ttu-id="14c83-123">Folgende Werte sind möglich: "A", "AAAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"</span><span class="sxs-lookup"><span data-stu-id="14c83-123">Possible values include: 'A', 'AAAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="14c83-124">Das Etag des Datensatzes festgelegt.</span><span class="sxs-lookup"><span data-stu-id="14c83-124">The etag of the record set.</span></span> <span data-ttu-id="14c83-125">Lassen Sie diesen Wert, um stets aktuelle Ressourceneintragssatz löschen.</span><span class="sxs-lookup"><span data-stu-id="14c83-125">Omit this value to always delete the current record set.</span></span> <span data-ttu-id="14c83-126">Geben Sie den letzten gesehen Etag-Wert, um zu verhindern, dass versehentliches Löschen von gleichzeitigen Änderungen.</span><span class="sxs-lookup"><span data-stu-id="14c83-126">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="14c83-127">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="14c83-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="14c83-128">Löscht einen Datensatz aus einer DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="14c83-128">Deletes a record set from a DNS zone.</span></span> <span data-ttu-id="14c83-129">Dieser Vorgang kann nicht rückgängig gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="14c83-129">This operation cannot be undone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; GetAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; GetAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.GetAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="14c83-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="14c83-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="14c83-131">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="14c83-131">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="14c83-132">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="14c83-132">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="14c83-133">Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.</span><span class="sxs-lookup"><span data-stu-id="14c83-133">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="14c83-134">Der Typ des DNS-Eintrags in diesen Datensatz.</span><span class="sxs-lookup"><span data-stu-id="14c83-134">The type of DNS record in this record set.</span></span> <span data-ttu-id="14c83-135">Folgende Werte sind möglich: "A", "AAAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"</span><span class="sxs-lookup"><span data-stu-id="14c83-135">Possible values include: 'A', 'AAAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="14c83-136">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="14c83-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="14c83-137">Ruft einen Ressourceneintragssatz ab.</span><span class="sxs-lookup"><span data-stu-id="14c83-137">Gets a record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByDnsZoneAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByDnsZoneAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByDnsZoneAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZoneAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByDnsZoneAsync (operations, resourceGroupName, zoneName, top, recordsetnamesuffix, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;ListByDnsZoneAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="zoneName">To be added.</param>
        <param name="top">To be added.</param>
        <param name="recordsetnamesuffix">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByDnsZoneNextAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByDnsZoneNextAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByDnsZoneNextAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZoneNextAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByDnsZoneNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;ListByDnsZoneNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="14c83-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="14c83-138">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="14c83-139">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="14c83-139">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="14c83-140">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="14c83-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="14c83-141">Listet alle Datensatzgruppen in einer DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="14c83-141">Lists all record sets in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByTypeAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByTypeAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByTypeAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTypeAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByTypeAsync (operations, resourceGroupName, zoneName, recordType, top, recordsetnamesuffix, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;ListByTypeAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="zoneName">To be added.</param>
        <param name="recordType">To be added.</param>
        <param name="top">To be added.</param>
        <param name="recordsetnamesuffix">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByTypeNextAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByTypeNextAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByTypeNextAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTypeNextAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByTypeNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;ListByTypeNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="14c83-142">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="14c83-142">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="14c83-143">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="14c83-143">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="14c83-144">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="14c83-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="14c83-145">Listet die Datensatzgruppen eines angegebenen Typs in einer DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="14c83-145">Lists the record sets of a specified type in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; UpdateAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; UpdateAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.UpdateAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;UpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="14c83-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="14c83-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="14c83-147">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="14c83-147">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="14c83-148">Der Name der DNS-Zone (ohne einen abschließenden Punkt).</span><span class="sxs-lookup"><span data-stu-id="14c83-148">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="14c83-149">Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.</span><span class="sxs-lookup"><span data-stu-id="14c83-149">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="14c83-150">Der Typ des DNS-Eintrags in diesen Datensatz.</span><span class="sxs-lookup"><span data-stu-id="14c83-150">The type of DNS record in this record set.</span></span> <span data-ttu-id="14c83-151">Folgende Werte sind möglich: "A", "AAAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"</span><span class="sxs-lookup"><span data-stu-id="14c83-151">Possible values include: 'A', 'AAAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="14c83-152">Parameter, die auf den Updatevorgang angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="14c83-152">Parameters supplied to the Update operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="14c83-153">Das Etag des Datensatzes festgelegt.</span><span class="sxs-lookup"><span data-stu-id="14c83-153">The etag of the record set.</span></span> <span data-ttu-id="14c83-154">Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="14c83-154">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="14c83-155">Geben Sie die letzten gesehen Etag-Wert, um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="14c83-155">Specify the last-seen etag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="14c83-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="14c83-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="14c83-157">Aktualisiert einen Datensatz in einer DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="14c83-157">Updates a record set within a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>