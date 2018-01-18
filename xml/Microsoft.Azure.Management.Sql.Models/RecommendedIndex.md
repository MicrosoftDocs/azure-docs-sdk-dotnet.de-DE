<Type Name="RecommendedIndex" FullName="Microsoft.Azure.Management.Sql.Models.RecommendedIndex">
  <TypeSignature Language="C#" Value="public class RecommendedIndex : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecommendedIndex extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.RecommendedIndex" />
  <TypeSignature Language="VB.NET" Value="Public Class RecommendedIndex&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type RecommendedIndex = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5400d-101">Stellt eine Datenbank mit dem Index empfohlen.</span><span class="sxs-lookup"><span data-stu-id="5400d-101">Represents a database recommended index.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendedIndex ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.RecommendedIndex.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5400d-102">Initialisiert eine neue Instanz der RecommendedIndex-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5400d-102">Initializes a new instance of the RecommendedIndex class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendedIndex (string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexAction&gt; action = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexState&gt; state = null, Nullable&lt;DateTime&gt; created = null, Nullable&lt;DateTime&gt; lastModified = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexType&gt; indexType = null, string schema = null, string table = null, System.Collections.Generic.IList&lt;string&gt; columns = null, System.Collections.Generic.IList&lt;string&gt; includedColumns = null, string indexScript = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.OperationImpact&gt; estimatedImpact = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.OperationImpact&gt; reportedImpact = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.RecommendedIndexAction&gt; action, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.RecommendedIndexState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; created, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.RecommendedIndexType&gt; indexType, string schema, string table, class System.Collections.Generic.IList`1&lt;string&gt; columns, class System.Collections.Generic.IList`1&lt;string&gt; includedColumns, string indexScript, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.OperationImpact&gt; estimatedImpact, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.OperationImpact&gt; reportedImpact) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.RecommendedIndex.#ctor(System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.RecommendedIndexAction},System.Nullable{Microsoft.Azure.Management.Sql.Models.RecommendedIndexState},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.Sql.Models.RecommendedIndexType},System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.OperationImpact},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.OperationImpact})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional action As Nullable(Of RecommendedIndexAction) = null, Optional state As Nullable(Of RecommendedIndexState) = null, Optional created As Nullable(Of DateTime) = null, Optional lastModified As Nullable(Of DateTime) = null, Optional indexType As Nullable(Of RecommendedIndexType) = null, Optional schema As String = null, Optional table As String = null, Optional columns As IList(Of String) = null, Optional includedColumns As IList(Of String) = null, Optional indexScript As String = null, Optional estimatedImpact As IList(Of OperationImpact) = null, Optional reportedImpact As IList(Of OperationImpact) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.RecommendedIndex : string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexAction&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexType&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.OperationImpact&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.OperationImpact&gt; -&gt; Microsoft.Azure.Management.Sql.Models.RecommendedIndex" Usage="new Microsoft.Azure.Management.Sql.Models.RecommendedIndex (id, name, type, action, state, created, lastModified, indexType, schema, table, columns, includedColumns, indexScript, estimatedImpact, reportedImpact)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="action" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexAction&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexState&gt;" />
        <Parameter Name="created" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="indexType" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexType&gt;" />
        <Parameter Name="schema" Type="System.String" />
        <Parameter Name="table" Type="System.String" />
        <Parameter Name="columns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="includedColumns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="indexScript" Type="System.String" />
        <Parameter Name="estimatedImpact" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.OperationImpact&gt;" />
        <Parameter Name="reportedImpact" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.OperationImpact&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="5400d-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="5400d-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="5400d-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="5400d-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="5400d-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="5400d-105">Resource type.</span></span></param>
        <param name="action"><span data-ttu-id="5400d-106">Die Aktion vorgeschlagene Index.</span><span class="sxs-lookup"><span data-stu-id="5400d-106">The proposed index action.</span></span> <span data-ttu-id="5400d-107">Sie können einen fehlenden Index zu erstellen, einen nicht verwendeten Index löschen oder Neuerstellen eines vorhandenes Indexes um die Leistung zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="5400d-107">You can create a missing index, drop an unused index, or rebuild an existing index to improve its performance.</span></span> <span data-ttu-id="5400d-108">Folgende Werte sind möglich: 'Erstellen', 'Drop', 'Rebuild'</span><span class="sxs-lookup"><span data-stu-id="5400d-108">Possible values include: 'Create', 'Drop', 'Rebuild'</span></span></param>
        <param name="state"><span data-ttu-id="5400d-109">Der aktuelle Status der Empfehlung.</span><span class="sxs-lookup"><span data-stu-id="5400d-109">The current recommendation state.</span></span> <span data-ttu-id="5400d-110">Folgende Werte sind möglich: "Aktiv", "Ausstehend", "Ausführen", "Überprüfen", "Ausstehende Revert", "Zurücksetzen", "Wiederhergestellten", "Ignoriert", "Abgelaufen", "Blockiert", "Success"</span><span class="sxs-lookup"><span data-stu-id="5400d-110">Possible values include: 'Active', 'Pending', 'Executing', 'Verifying', 'Pending Revert', 'Reverting', 'Reverted', 'Ignored', 'Expired', 'Blocked', 'Success'</span></span></param>
        <param name="created"><span data-ttu-id="5400d-111">Die UTC-Datetime anzeigt, wann diese Ressource erstellt wurde (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="5400d-111">The UTC datetime showing when this resource was created (ISO8601 format).</span></span></param>
        <param name="lastModified"><span data-ttu-id="5400d-112">Zuletzt geändert von, wenn diese Ressource wurde die UTC-Datetime (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="5400d-112">The UTC datetime of when was this resource last changed (ISO8601 format).</span></span></param>
        <param name="indexType"><span data-ttu-id="5400d-113">Der Typ des Index (GRUPPIERTER, nicht GRUPPIERT, COLUMNSTORE, CLUSTERED COLUMNSTORE).</span><span class="sxs-lookup"><span data-stu-id="5400d-113">The type of index (CLUSTERED, NONCLUSTERED, COLUMNSTORE, CLUSTERED COLUMNSTORE).</span></span> <span data-ttu-id="5400d-114">Folgende Werte sind möglich: "Gruppierten", "NONCLUSTERED", "COLUMNSTORE", "CLUSTERED COLUMNSTORE"</span><span class="sxs-lookup"><span data-stu-id="5400d-114">Possible values include: 'CLUSTERED', 'NONCLUSTERED', 'COLUMNSTORE', 'CLUSTERED COLUMNSTORE'</span></span></param>
        <param name="schema"><span data-ttu-id="5400d-115">Das Schema, in denen Tabelle zum Erstellen des Indexes über befindet</span><span class="sxs-lookup"><span data-stu-id="5400d-115">The schema where table to build index over resides</span></span></param>
        <param name="table"><span data-ttu-id="5400d-116">Die Tabelle auf dem Index zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="5400d-116">The table on which to build index.</span></span></param>
        <param name="columns"><span data-ttu-id="5400d-117">Spalten, die über den Index zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="5400d-117">Columns over which to build index</span></span></param>
        <param name="includedColumns"><span data-ttu-id="5400d-118">Die Liste der Spaltennamen in den Index einbezogen werden</span><span class="sxs-lookup"><span data-stu-id="5400d-118">The list of column names to be included in the index</span></span></param>
        <param name="indexScript"><span data-ttu-id="5400d-119">Vollständige Buildskript index</span><span class="sxs-lookup"><span data-stu-id="5400d-119">The full build index script</span></span></param>
        <param name="estimatedImpact"><span data-ttu-id="5400d-120">Die geschätzte Auswirkungen dafür empfohlene Index-Aktion.</span><span class="sxs-lookup"><span data-stu-id="5400d-120">The estimated impact of doing recommended index action.</span></span></param>
        <param name="reportedImpact"><span data-ttu-id="5400d-121">Die Werte angezeigt, nachdem Index-Aktion abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5400d-121">The values reported after index action is complete.</span></span></param>
        <summary>
            <span data-ttu-id="5400d-122">Initialisiert eine neue Instanz der RecommendedIndex-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5400d-122">Initializes a new instance of the RecommendedIndex class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexAction&gt; Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.RecommendedIndexAction&gt; Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedIndex.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As Nullable(Of RecommendedIndexAction)" />
      <MemberSignature Language="F#" Value="member this.Action : Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexAction&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedIndex.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.action")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5400d-123">Ruft die Aktion vorgeschlagene Index ab.</span><span class="sxs-lookup"><span data-stu-id="5400d-123">Gets the proposed index action.</span></span> <span data-ttu-id="5400d-124">Sie können einen fehlenden Index zu erstellen, einen nicht verwendeten Index löschen oder Neuerstellen eines vorhandenes Indexes um die Leistung zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="5400d-124">You can create a missing index, drop an unused index, or rebuild an existing index to improve its performance.</span></span> <span data-ttu-id="5400d-125">Folgende Werte sind möglich: 'Erstellen', 'Drop', 'Rebuild'</span><span class="sxs-lookup"><span data-stu-id="5400d-125">Possible values include: 'Create', 'Drop', 'Rebuild'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Columns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Columns { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Columns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedIndex.Columns" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Columns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Columns : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedIndex.Columns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.columns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5400d-126">Ruft die Spalten aus, für den Index ab</span><span class="sxs-lookup"><span data-stu-id="5400d-126">Gets columns over which to build index</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Created">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Created { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Created" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedIndex.Created" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Created As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Created : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedIndex.Created" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.created")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5400d-127">Ruft den UTC-DateTime-Wert anzeigen, wenn diese Ressource (ISO8601-Format) erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="5400d-127">Gets the UTC datetime showing when this resource was created (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EstimatedImpact">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.OperationImpact&gt; EstimatedImpact { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.OperationImpact&gt; EstimatedImpact" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedIndex.EstimatedImpact" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EstimatedImpact As IList(Of OperationImpact)" />
      <MemberSignature Language="F#" Value="member this.EstimatedImpact : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.OperationImpact&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedIndex.EstimatedImpact" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.estimatedImpact")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.OperationImpact&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5400d-128">Ruft die geschätzte Auswirkungen dafür empfohlene Aktion Index ab.</span><span class="sxs-lookup"><span data-stu-id="5400d-128">Gets the estimated impact of doing recommended index action.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludedColumns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; IncludedColumns { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; IncludedColumns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedIndex.IncludedColumns" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IncludedColumns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.IncludedColumns : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedIndex.IncludedColumns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.includedColumns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5400d-129">Ruft die Liste der Spaltennamen in den Index einbezogen werden</span><span class="sxs-lookup"><span data-stu-id="5400d-129">Gets the list of column names to be included in the index</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexScript">
      <MemberSignature Language="C#" Value="public string IndexScript { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IndexScript" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedIndex.IndexScript" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IndexScript As String" />
      <MemberSignature Language="F#" Value="member this.IndexScript : string" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedIndex.IndexScript" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.indexScript")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5400d-130">Ruft den vollständigen Index Buildskript</span><span class="sxs-lookup"><span data-stu-id="5400d-130">Gets the full build index script</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexType&gt; IndexType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.RecommendedIndexType&gt; IndexType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedIndex.IndexType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IndexType As Nullable(Of RecommendedIndexType)" />
      <MemberSignature Language="F#" Value="member this.IndexType : Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexType&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedIndex.IndexType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.indexType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5400d-131">Ruft den Typ des Index (GRUPPIERTER, nicht GRUPPIERT, columnstore-, CLUSTERED COLUMNSTORE) ab.</span><span class="sxs-lookup"><span data-stu-id="5400d-131">Gets the type of index (CLUSTERED, NONCLUSTERED, COLUMNSTORE, CLUSTERED COLUMNSTORE).</span></span> <span data-ttu-id="5400d-132">Folgende Werte sind möglich: "Gruppierten", "NONCLUSTERED", "COLUMNSTORE", "CLUSTERED COLUMNSTORE"</span><span class="sxs-lookup"><span data-stu-id="5400d-132">Possible values include: 'CLUSTERED', 'NONCLUSTERED', 'COLUMNSTORE', 'CLUSTERED COLUMNSTORE'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedIndex.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedIndex.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5400d-133">Ruft den UTC-Datetime bei dieser Ressource zuletzt geänderte (ISO8601-Format) befand.</span><span class="sxs-lookup"><span data-stu-id="5400d-133">Gets the UTC datetime of when was this resource last changed (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportedImpact">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.OperationImpact&gt; ReportedImpact { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.OperationImpact&gt; ReportedImpact" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedIndex.ReportedImpact" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReportedImpact As IList(Of OperationImpact)" />
      <MemberSignature Language="F#" Value="member this.ReportedImpact : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.OperationImpact&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedIndex.ReportedImpact" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.reportedImpact")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.OperationImpact&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5400d-134">Ruft die Werte angezeigt, nachdem der Index-Aktion abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5400d-134">Gets the values reported after index action is complete.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schema">
      <MemberSignature Language="C#" Value="public string Schema { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Schema" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedIndex.Schema" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Schema As String" />
      <MemberSignature Language="F#" Value="member this.Schema : string" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedIndex.Schema" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.schema")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5400d-135">Ruft das Schema, in denen Tabelle zum Erstellen des Indexes über befindet</span><span class="sxs-lookup"><span data-stu-id="5400d-135">Gets the schema where table to build index over resides</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.RecommendedIndexState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedIndex.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of RecommendedIndexState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexState&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedIndex.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndexState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5400d-136">Ruft den aktuellen Status der Empfehlung.</span><span class="sxs-lookup"><span data-stu-id="5400d-136">Gets the current recommendation state.</span></span> <span data-ttu-id="5400d-137">Folgende Werte sind möglich: "Aktiv", "Ausstehend", "Ausführen", "Überprüfen", "Ausstehende Revert", "Zurücksetzen", "Wiederhergestellten", "Ignoriert", "Abgelaufen", "Blockiert", "Success"</span><span class="sxs-lookup"><span data-stu-id="5400d-137">Possible values include: 'Active', 'Pending', 'Executing', 'Verifying', 'Pending Revert', 'Reverting', 'Reverted', 'Ignored', 'Expired', 'Blocked', 'Success'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Table">
      <MemberSignature Language="C#" Value="public string Table { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Table" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedIndex.Table" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Table As String" />
      <MemberSignature Language="F#" Value="member this.Table : string" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedIndex.Table" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.table")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5400d-138">Ruft die Tabelle auf den Index ab.</span><span class="sxs-lookup"><span data-stu-id="5400d-138">Gets the table on which to build index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>