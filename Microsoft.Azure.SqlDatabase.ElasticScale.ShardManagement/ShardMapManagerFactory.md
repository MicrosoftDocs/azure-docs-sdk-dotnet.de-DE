<Type Name="ShardMapManagerFactory" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory">
  <TypeSignature Language="C#" Value="public static class ShardMapManagerFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ShardMapManagerFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class ShardMapManagerFactory" />
  <TypeSignature Language="F#" Value="type ShardMapManagerFactory = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3722e-101">Factory für <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" />s erleichtert die Erstellung und Verwaltung von Shard Zuordnung Manager persistenten Status.</span><span class="sxs-lookup"><span data-stu-id="3722e-101">Factory for <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" />s facilitates the creation and management of shard map manager persistent state.</span></span> <span data-ttu-id="3722e-102">Verwenden Sie diese Klasse als Eintrag zeigen Sie auf die Bibliothek-Objekthierarchie.</span><span class="sxs-lookup"><span data-stu-id="3722e-102">Use this class as the entry point to the library's object hierarchy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreatePerformanceCategoryAndCounters">
      <MemberSignature Language="C#" Value="public static void CreatePerformanceCategoryAndCounters ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void CreatePerformanceCategoryAndCounters() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreatePerformanceCategoryAndCounters" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub CreatePerformanceCategoryAndCounters ()" />
      <MemberSignature Language="F#" Value="static member CreatePerformanceCategoryAndCounters : unit -&gt; unit" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreatePerformanceCategoryAndCounters " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3722e-103">Erstellen von Shard Management Leistungsindikatorkategorie und Leistungsindikatoren</span><span class="sxs-lookup"><span data-stu-id="3722e-103">Create shard management performance counter category and counters</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSqlShardMapManager">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager CreateSqlShardMapManager (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager CreateSqlShardMapManager(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreateSqlShardMapManager(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSqlShardMapManager (connectionString As String) As ShardMapManager" />
      <MemberSignature Language="F#" Value="static member CreateSqlShardMapManager : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreateSqlShardMapManager connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="3722e-104">Die Verbindungsparameter für die Erstellung von Shard-Schema-Manager-Datenbank verwendet.</span><span class="sxs-lookup"><span data-stu-id="3722e-104">Connection parameters used for creating shard map manager database.</span></span></param>
        <summary>
            <span data-ttu-id="3722e-105">Erstellt eine <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> und entsprechende Speicher Strukturen in der angegebenen SQL Server-Datenbank mit <see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode.KeepExisting" /> und <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior.DefaultRetryBehavior" />.</span><span class="sxs-lookup"><span data-stu-id="3722e-105">Creates a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> and its corresponding storage structures in the specified SQL Server database, with <see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode.KeepExisting" /> and <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior.DefaultRetryBehavior" />.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3722e-106">Ein Shard Map-Objekt-Manager zum Ausführen von Management verwendet und Lesevorgänge für shardzuordnungen, Shards und Shard-Zuordnungen.</span><span class="sxs-lookup"><span data-stu-id="3722e-106">A shard map manager object used for performing management and read operations for shard maps, shards and shard mappings.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSqlShardMapManager">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager CreateSqlShardMapManager (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior retryBehavior);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager CreateSqlShardMapManager(string connectionString, class Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior retryBehavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreateSqlShardMapManager(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior)" />
      <MemberSignature Language="F#" Value="static member CreateSqlShardMapManager : string * Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreateSqlShardMapManager (connectionString, retryBehavior)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="retryBehavior" Type="Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="3722e-107">Die Verbindungsparameter für die Erstellung von Shard-Schema-Manager-Datenbank verwendet.</span><span class="sxs-lookup"><span data-stu-id="3722e-107">Connection parameters used for creating shard map manager database.</span></span></param>
        <param name="retryBehavior"><span data-ttu-id="3722e-108">Verhalten für die vorübergehende Ausnahmen, die in den Speicher zu erkennen.</span><span class="sxs-lookup"><span data-stu-id="3722e-108">Behavior for detecting transient exceptions in the store.</span></span></param>
        <summary>
            <span data-ttu-id="3722e-109">Erstellt eine <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> und entsprechende Speicher Strukturen in der angegebenen SQL Server-Datenbank mit <see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode.KeepExisting" />.</span><span class="sxs-lookup"><span data-stu-id="3722e-109">Creates a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> and its corresponding storage structures in the specified SQL Server database, with <see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode.KeepExisting" />.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3722e-110">Ein Shard Map-Objekt-Manager zum Ausführen von Management verwendet und Lesevorgänge für shardzuordnungen, Shards und Shard-Zuordnungen.</span><span class="sxs-lookup"><span data-stu-id="3722e-110">A shard map manager object used for performing management and read operations for shard maps, shards and shard mappings.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSqlShardMapManager">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager CreateSqlShardMapManager (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode createMode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager CreateSqlShardMapManager(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode createMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreateSqlShardMapManager(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSqlShardMapManager (connectionString As String, createMode As ShardMapManagerCreateMode) As ShardMapManager" />
      <MemberSignature Language="F#" Value="static member CreateSqlShardMapManager : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreateSqlShardMapManager (connectionString, createMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="createMode" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="3722e-111">Die Verbindungsparameter für die Erstellung von Shard-Schema-Manager-Datenbank verwendet.</span><span class="sxs-lookup"><span data-stu-id="3722e-111">Connection parameters used for creating shard map manager database.</span></span></param>
        <param name="createMode"><span data-ttu-id="3722e-112">Beschreibt die Option zum Erstellen von Shard-Schema-Manager-Datenbank vom Benutzer ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="3722e-112">Describes the option selected by the user for creating shard map manager database.</span></span></param>
        <summary>
            <span data-ttu-id="3722e-113">Erstellt eine <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> und entsprechende Speicher Strukturen in der angegebenen SQL Server-Datenbank mit <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior.DefaultRetryBehavior" />.</span><span class="sxs-lookup"><span data-stu-id="3722e-113">Creates a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> and its corresponding storage structures in the specified SQL Server database, with <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior.DefaultRetryBehavior" />.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3722e-114">Ein Shard Map-Objekt-Manager zum Ausführen von Management verwendet und Lesevorgänge für shardzuordnungen, Shards und Shard-Zuordnungen.</span><span class="sxs-lookup"><span data-stu-id="3722e-114">A shard map manager object used for performing management and read operations for shard maps, shards and shard mappings.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSqlShardMapManager">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager CreateSqlShardMapManager (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode createMode, Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior retryBehavior);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager CreateSqlShardMapManager(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode createMode, class Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior retryBehavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreateSqlShardMapManager(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode,Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior)" />
      <MemberSignature Language="F#" Value="static member CreateSqlShardMapManager : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode * Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreateSqlShardMapManager (connectionString, createMode, retryBehavior)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="2")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Reliability", "CA2000:Dispose objects before losing scope")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="createMode" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode" />
        <Parameter Name="retryBehavior" Type="Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="3722e-115">Die Verbindungsparameter für die Erstellung von Shard-Schema-Manager-Datenbank verwendet.</span><span class="sxs-lookup"><span data-stu-id="3722e-115">Connection parameters used for creating shard map manager database.</span></span></param>
        <param name="createMode"><span data-ttu-id="3722e-116">Beschreibt die Option zum Erstellen von Shard-Schema-Manager-Datenbank vom Benutzer ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="3722e-116">Describes the option selected by the user for creating shard map manager database.</span></span></param>
        <param name="retryBehavior"><span data-ttu-id="3722e-117">Verhalten für die vorübergehende Ausnahmen, die in den Speicher zu erkennen.</span><span class="sxs-lookup"><span data-stu-id="3722e-117">Behavior for detecting transient exceptions in the store.</span></span></param>
        <summary>
            <span data-ttu-id="3722e-118">Erstellt eine <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> und entsprechende Speicher Strukturen, in der angegebenen SQL Server-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="3722e-118">Creates a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> and its corresponding storage structures in the specified SQL Server database.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3722e-119">Ein Shard Map-Objekt-Manager zum Ausführen von Management verwendet und Lesevorgänge für shardzuordnungen, Shards und Shard-Zuordnungen.</span><span class="sxs-lookup"><span data-stu-id="3722e-119">A shard map manager object used for performing management and read operations for shard maps, shards and shard mappings.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSqlShardMapManager">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager GetSqlShardMapManager (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy loadPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager GetSqlShardMapManager(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy loadPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.GetSqlShardMapManager(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetSqlShardMapManager (connectionString As String, loadPolicy As ShardMapManagerLoadPolicy) As ShardMapManager" />
      <MemberSignature Language="F#" Value="static member GetSqlShardMapManager : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.GetSqlShardMapManager (connectionString, loadPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="loadPolicy" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="3722e-120">Verwendet zum Ausführen von Vorgängen für Shard Verbindungsparameter zuordnen Manager-Datenbanken.</span><span class="sxs-lookup"><span data-stu-id="3722e-120">Connection parameters used for performing operations against shard map manager database(s).</span></span></param>
        <param name="loadPolicy"><span data-ttu-id="3722e-121">Richtlinie für die Initialisierung.</span><span class="sxs-lookup"><span data-stu-id="3722e-121">Initialization policy.</span></span></param>
        <summary>
            <span data-ttu-id="3722e-122">Ruft <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> von beibehalten Status in einer SQL Server-Datenbank mit <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior.DefaultRetryBehavior" />.</span><span class="sxs-lookup"><span data-stu-id="3722e-122">Gets <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> from persisted state in a SQL Server database, with <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior.DefaultRetryBehavior" />.</span></span> 
            </summary>
        <returns>
            <span data-ttu-id="3722e-123">Ein Shard Map-Objekt-Manager zum Ausführen von Management verwendet und Lesevorgänge für shardzuordnungen, Shards und Shard-Zuordnungen.</span><span class="sxs-lookup"><span data-stu-id="3722e-123">A shard map manager object used for performing management and read operations for shard maps, shards and shard mappings.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSqlShardMapManager">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager GetSqlShardMapManager (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy loadPolicy, Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior retryBehavior);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager GetSqlShardMapManager(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy loadPolicy, class Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior retryBehavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.GetSqlShardMapManager(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy,Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior)" />
      <MemberSignature Language="F#" Value="static member GetSqlShardMapManager : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy * Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.GetSqlShardMapManager (connectionString, loadPolicy, retryBehavior)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="loadPolicy" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy" />
        <Parameter Name="retryBehavior" Type="Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="3722e-124">Verwendet zum Ausführen von Vorgängen für Shard Verbindungsparameter zuordnen Manager-Datenbanken.</span><span class="sxs-lookup"><span data-stu-id="3722e-124">Connection parameters used for performing operations against shard map manager database(s).</span></span></param>
        <param name="loadPolicy"><span data-ttu-id="3722e-125">Richtlinie für die Initialisierung.</span><span class="sxs-lookup"><span data-stu-id="3722e-125">Initialization policy.</span></span></param>
        <param name="retryBehavior"><span data-ttu-id="3722e-126">Verhalten für die vorübergehende Ausnahmen, die in den Speicher zu erkennen.</span><span class="sxs-lookup"><span data-stu-id="3722e-126">Behavior for detecting transient exceptions in the store.</span></span></param>
        <summary>
            <span data-ttu-id="3722e-127">Ruft <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> von beibehaltenen Zustand in einer SQL Server-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="3722e-127">Gets <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> from persisted state in a SQL Server database.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3722e-128">Ein Shard Map-Objekt-Manager zum Ausführen von Management verwendet und Lesevorgänge für shardzuordnungen, Shards und Shard-Zuordnungen.</span><span class="sxs-lookup"><span data-stu-id="3722e-128">A shard map manager object used for performing management and read operations for shard maps, shards and shard mappings.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetSqlShardMapManager">
      <MemberSignature Language="C#" Value="public static bool TryGetSqlShardMapManager (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy loadPolicy, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager shardMapManager);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryGetSqlShardMapManager(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy loadPolicy, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager&amp; shardMapManager) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.TryGetSqlShardMapManager(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryGetSqlShardMapManager (connectionString As String, loadPolicy As ShardMapManagerLoadPolicy, ByRef shardMapManager As ShardMapManager) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryGetSqlShardMapManager : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy *  -&gt; bool" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.TryGetSqlShardMapManager (connectionString, loadPolicy, shardMapManager)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="2#")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="loadPolicy" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy" />
        <Parameter Name="shardMapManager" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="3722e-129">Verwendet zum Ausführen von Vorgängen für Shard Verbindungsparameter zuordnen Manager-Datenbanken.</span><span class="sxs-lookup"><span data-stu-id="3722e-129">Connection parameters used for performing operations against shard map manager database(s).</span></span></param>
        <param name="loadPolicy"><span data-ttu-id="3722e-130">Richtlinie für die Initialisierung.</span><span class="sxs-lookup"><span data-stu-id="3722e-130">Initialization policy.</span></span></param>
        <param name="shardMapManager"><span data-ttu-id="3722e-131">Shard Map-Manager-Objekt zum Ausführen von Management verwendet und Lesevorgänge für shardzuordnungen, Shards und Shard-Zuordnungen oder <c>null</c> für den Fall, dass shardzuordnungs-Manager nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="3722e-131">Shard map manager object used for performing management and read operations for shard maps, shards and shard mappings or <c>null</c> in case shard map manager does not exist.</span></span></param>
        <summary>
            <span data-ttu-id="3722e-132">Ruft <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> von beibehaltenen Zustand in einer SQL Server-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="3722e-132">Gets <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> from persisted state in a SQL Server database.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="3722e-133"><c>"true"</c> Wenn einem Shard Map-Manager-Objekt erstellt wurde, <c>"false"</c> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="3722e-133"><c>true</c> if a shard map manager object was created, <c>false</c> otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetSqlShardMapManager">
      <MemberSignature Language="C#" Value="public static bool TryGetSqlShardMapManager (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy loadPolicy, Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior retryBehavior, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager shardMapManager);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryGetSqlShardMapManager(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy loadPolicy, class Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior retryBehavior, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager&amp; shardMapManager) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.TryGetSqlShardMapManager(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy,Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager@)" />
      <MemberSignature Language="F#" Value="static member TryGetSqlShardMapManager : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy * Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior *  -&gt; bool" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.TryGetSqlShardMapManager (connectionString, loadPolicy, retryBehavior, shardMapManager)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="2")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="2#")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="loadPolicy" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy" />
        <Parameter Name="retryBehavior" Type="Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior" />
        <Parameter Name="shardMapManager" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="3722e-134">Verwendet zum Ausführen von Vorgängen für Shard Verbindungsparameter zuordnen Manager-Datenbanken.</span><span class="sxs-lookup"><span data-stu-id="3722e-134">Connection parameters used for performing operations against shard map manager database(s).</span></span></param>
        <param name="loadPolicy"><span data-ttu-id="3722e-135">Richtlinie für die Initialisierung.</span><span class="sxs-lookup"><span data-stu-id="3722e-135">Initialization policy.</span></span></param>
        <param name="retryBehavior"><span data-ttu-id="3722e-136">Verhalten für die vorübergehende Ausnahmen, die in den Speicher zu erkennen.</span><span class="sxs-lookup"><span data-stu-id="3722e-136">Behavior for detecting transient exceptions in the store.</span></span></param>
        <param name="shardMapManager"><span data-ttu-id="3722e-137">Shard Map-Manager-Objekt zum Ausführen von Management verwendet und Lesevorgänge für shardzuordnungen, Shards und Shard-Zuordnungen oder <c>null</c> für den Fall, dass shardzuordnungs-Manager nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="3722e-137">Shard map manager object used for performing management and read operations for shard maps, shards and shard mappings or <c>null</c> in case shard map manager does not exist.</span></span></param>
        <summary>
            <span data-ttu-id="3722e-138">Ruft <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> von beibehaltenen Zustand in einer SQL Server-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="3722e-138">Gets <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> from persisted state in a SQL Server database.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="3722e-139"><c>"true"</c> Wenn einem Shard Map-Manager-Objekt erstellt wurde, <c>"false"</c> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="3722e-139"><c>true</c> if a shard map manager object was created, <c>false</c> otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>