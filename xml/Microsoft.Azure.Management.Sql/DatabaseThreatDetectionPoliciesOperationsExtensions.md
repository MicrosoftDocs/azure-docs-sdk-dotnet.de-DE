<Type Name="DatabaseThreatDetectionPoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DatabaseThreatDetectionPoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DatabaseThreatDetectionPoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DatabaseThreatDetectionPoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DatabaseThreatDetectionPoliciesOperationsExtensions = class" />
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
            <span data-ttu-id="8cd5c-101">Erweiterungsmethoden für DatabaseThreatDetectionPoliciesOperations.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-101">Extension methods for DatabaseThreatDetectionPoliciesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy CreateOrUpdate (this Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy CreateOrUpdate(class Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDatabaseThreatDetectionPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As DatabaseSecurityAlertPolicy) As DatabaseSecurityAlertPolicy" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy -&gt; Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy" Usage="Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8cd5c-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8cd5c-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8cd5c-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="8cd5c-105">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="8cd5c-106">Der Name der Datenbank, für welche, die Datenbank die Bedrohungserkennung Richtlinie definiert ist.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-106">The name of the database for which database Threat Detection policy is defined.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8cd5c-107">Die Bedrohungserkennung-Richtlinie für die Datenbank.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-107">The database Threat Detection policy.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8cd5c-108">Erstellt oder aktualisiert die Richtlinie zur Erkennung von einer Datenbank darstellen.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-108">Creates or updates a database's threat detection policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8cd5c-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8cd5c-110">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8cd5c-111">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="8cd5c-112">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-112">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="8cd5c-113">Der Name der Datenbank, für welche, die Datenbank die Bedrohungserkennung Richtlinie definiert ist.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-113">The name of the database for which database Threat Detection policy is defined.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8cd5c-114">Die Bedrohungserkennung-Richtlinie für die Datenbank.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-114">The database Threat Detection policy.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8cd5c-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8cd5c-116">Erstellt oder aktualisiert die Richtlinie zur Erkennung von einer Datenbank darstellen.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-116">Creates or updates a database's threat detection policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy Get (this Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy Get(class Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDatabaseThreatDetectionPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String) As DatabaseSecurityAlertPolicy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy" Usage="Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8cd5c-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8cd5c-118">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8cd5c-119">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="8cd5c-120">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-120">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="8cd5c-121">Der Name der Datenbank, für welche, die Datenbank die Bedrohungserkennung Richtlinie definiert ist.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-121">The name of the database for which database Threat Detection policy is defined.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8cd5c-122">Ruft die Erkennungsrichtlinie für eine Datenbank darstellen.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-122">Gets a database's threat detection policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy&gt; GetAsync (this Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy&gt; GetAsync(class Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8cd5c-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8cd5c-124">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8cd5c-125">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="8cd5c-126">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-126">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="8cd5c-127">Der Name der Datenbank, für welche, die Datenbank die Bedrohungserkennung Richtlinie definiert ist.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-127">The name of the database for which database Threat Detection policy is defined.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8cd5c-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8cd5c-129">Ruft die Erkennungsrichtlinie für eine Datenbank darstellen.</span><span class="sxs-lookup"><span data-stu-id="8cd5c-129">Gets a database's threat detection policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>