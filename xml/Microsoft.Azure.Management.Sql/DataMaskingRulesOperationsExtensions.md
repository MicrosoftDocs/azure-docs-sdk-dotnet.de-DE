<Type Name="DataMaskingRulesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataMaskingRulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataMaskingRulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataMaskingRulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataMaskingRulesOperationsExtensions = class" />
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
            <span data-ttu-id="0f116-101">Erweiterungsmethoden für DataMaskingRulesOperations.</span><span class="sxs-lookup"><span data-stu-id="0f116-101">Extension methods for DataMaskingRulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.DataMaskingRule CreateOrUpdate (this Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations operations, string resourceGroupName, string serverName, string databaseName, string dataMaskingRuleName, Microsoft.Azure.Management.Sql.Models.DataMaskingRule parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.DataMaskingRule CreateOrUpdate(class Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations operations, string resourceGroupName, string serverName, string databaseName, string dataMaskingRuleName, class Microsoft.Azure.Management.Sql.Models.DataMaskingRule parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DataMaskingRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDataMaskingRulesOperations, resourceGroupName As String, serverName As String, databaseName As String, dataMaskingRuleName As String, parameters As DataMaskingRule) As DataMaskingRule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.DataMaskingRule -&gt; Microsoft.Azure.Management.Sql.Models.DataMaskingRule" Usage="Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, dataMaskingRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.DataMaskingRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="dataMaskingRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DataMaskingRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f116-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f116-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0f116-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0f116-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0f116-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0f116-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0f116-105">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0f116-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0f116-106">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0f116-106">The name of the database.</span></span>
            </param>
        <param name="dataMaskingRuleName">
            <span data-ttu-id="0f116-107">Der Name der datenmaskierungsregel.</span><span class="sxs-lookup"><span data-stu-id="0f116-107">The name of the data masking rule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0f116-108">Die erforderlichen Parameter zum Erstellen oder Aktualisieren einer datenmaskierungsregel.</span><span class="sxs-lookup"><span data-stu-id="0f116-108">The required parameters for creating or updating a data masking rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f116-109">Erstellt oder aktualisiert eine datenmaskierungsregel Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0f116-109">Creates or updates a database data masking rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations operations, string resourceGroupName, string serverName, string databaseName, string dataMaskingRuleName, Microsoft.Azure.Management.Sql.Models.DataMaskingRule parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations operations, string resourceGroupName, string serverName, string databaseName, string dataMaskingRuleName, class Microsoft.Azure.Management.Sql.Models.DataMaskingRule parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DataMaskingRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.DataMaskingRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;" Usage="Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, dataMaskingRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="dataMaskingRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DataMaskingRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f116-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f116-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0f116-111">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0f116-111">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0f116-112">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0f116-112">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0f116-113">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0f116-113">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0f116-114">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0f116-114">The name of the database.</span></span>
            </param>
        <param name="dataMaskingRuleName">
            <span data-ttu-id="0f116-115">Der Name der datenmaskierungsregel.</span><span class="sxs-lookup"><span data-stu-id="0f116-115">The name of the data masking rule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0f116-116">Die erforderlichen Parameter zum Erstellen oder Aktualisieren einer datenmaskierungsregel.</span><span class="sxs-lookup"><span data-stu-id="0f116-116">The required parameters for creating or updating a data masking rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0f116-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0f116-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f116-118">Erstellt oder aktualisiert eine datenmaskierungsregel Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0f116-118">Creates or updates a database data masking rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabase">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt; ListByDatabase (this Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt; ListByDatabase(class Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions.ListByDatabase(Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatabase (operations As IDataMaskingRulesOperations, resourceGroupName As String, serverName As String, databaseName As String) As IEnumerable(Of DataMaskingRule)" />
      <MemberSignature Language="F#" Value="static member ListByDatabase : Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;" Usage="Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions.ListByDatabase (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f116-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f116-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0f116-120">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0f116-120">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0f116-121">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0f116-121">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0f116-122">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0f116-122">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0f116-123">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0f116-123">The name of the database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f116-124">Ruft eine Liste von datenmaskierungsregeln Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="0f116-124">Gets a list of database data masking rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;&gt; ListByDatabaseAsync (this Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;&gt; ListByDatabaseAsync(class Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions.ListByDatabaseAsync(Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseAsync : Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions.ListByDatabaseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions/&lt;ListByDatabaseAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f116-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f116-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0f116-126">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0f116-126">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0f116-127">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0f116-127">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0f116-128">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0f116-128">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0f116-129">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0f116-129">The name of the database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0f116-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0f116-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f116-131">Ruft eine Liste von datenmaskierungsregeln Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="0f116-131">Gets a list of database data masking rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>