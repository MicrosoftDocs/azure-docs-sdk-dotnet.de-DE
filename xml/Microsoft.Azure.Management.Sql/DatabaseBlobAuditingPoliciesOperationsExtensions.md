<Type Name="DatabaseBlobAuditingPoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.DatabaseBlobAuditingPoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DatabaseBlobAuditingPoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DatabaseBlobAuditingPoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.DatabaseBlobAuditingPoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DatabaseBlobAuditingPoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DatabaseBlobAuditingPoliciesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="32cb2-101">Erweiterungsmethoden für DatabaseBlobAuditingPoliciesOperations.</span><span class="sxs-lookup"><span data-stu-id="32cb2-101">Extension methods for DatabaseBlobAuditingPoliciesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy CreateOrUpdate (this Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy CreateOrUpdate(class Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseBlobAuditingPoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDatabaseBlobAuditingPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As DatabaseBlobAuditingPolicy) As DatabaseBlobAuditingPolicy" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy -&gt; Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy" Usage="Microsoft.Azure.Management.Sql.DatabaseBlobAuditingPoliciesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32cb2-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32cb2-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="32cb2-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="32cb2-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="32cb2-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="32cb2-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="32cb2-105">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="32cb2-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="32cb2-106">Der Name der Datenbank, für die die Überwachungsrichtlinie Blob definiert wird.</span><span class="sxs-lookup"><span data-stu-id="32cb2-106">The name of the database for which the blob auditing policy will be defined.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="32cb2-107">Die Datenbank Überwachungsrichtlinie für das Blob.</span><span class="sxs-lookup"><span data-stu-id="32cb2-107">The database blob auditing policy.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32cb2-108">Erstellt oder aktualisiert eine Datenbank-Blob Überwachungsrichtlinien.</span><span class="sxs-lookup"><span data-stu-id="32cb2-108">Creates or updates a database's blob auditing policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseBlobAuditingPoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.DatabaseBlobAuditingPoliciesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabaseBlobAuditingPoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32cb2-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32cb2-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="32cb2-110">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="32cb2-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="32cb2-111">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="32cb2-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="32cb2-112">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="32cb2-112">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="32cb2-113">Der Name der Datenbank, für die die Überwachungsrichtlinie Blob definiert wird.</span><span class="sxs-lookup"><span data-stu-id="32cb2-113">The name of the database for which the blob auditing policy will be defined.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="32cb2-114">Die Datenbank Überwachungsrichtlinie für das Blob.</span><span class="sxs-lookup"><span data-stu-id="32cb2-114">The database blob auditing policy.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32cb2-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="32cb2-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32cb2-116">Erstellt oder aktualisiert eine Datenbank-Blob Überwachungsrichtlinien.</span><span class="sxs-lookup"><span data-stu-id="32cb2-116">Creates or updates a database's blob auditing policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy Get (this Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy Get(class Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseBlobAuditingPoliciesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDatabaseBlobAuditingPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String) As DatabaseBlobAuditingPolicy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy" Usage="Microsoft.Azure.Management.Sql.DatabaseBlobAuditingPoliciesOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32cb2-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32cb2-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="32cb2-118">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="32cb2-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="32cb2-119">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="32cb2-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="32cb2-120">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="32cb2-120">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="32cb2-121">Der Name der Datenbank für die Blob-Überwachungsrichtlinie definiert ist.</span><span class="sxs-lookup"><span data-stu-id="32cb2-121">The name of the database for which the blob audit policy is defined.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32cb2-122">Ruft die Richtlinie für die Überwachung einer Datenbank-Blob ab.</span><span class="sxs-lookup"><span data-stu-id="32cb2-122">Gets a database's blob auditing policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy&gt; GetAsync (this Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy&gt; GetAsync(class Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseBlobAuditingPoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.DatabaseBlobAuditingPoliciesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabaseBlobAuditingPoliciesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32cb2-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32cb2-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="32cb2-124">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="32cb2-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="32cb2-125">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="32cb2-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="32cb2-126">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="32cb2-126">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="32cb2-127">Der Name der Datenbank für die Blob-Überwachungsrichtlinie definiert ist.</span><span class="sxs-lookup"><span data-stu-id="32cb2-127">The name of the database for which the blob audit policy is defined.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32cb2-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="32cb2-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32cb2-129">Ruft die Richtlinie für die Überwachung einer Datenbank-Blob ab.</span><span class="sxs-lookup"><span data-stu-id="32cb2-129">Gets a database's blob auditing policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>