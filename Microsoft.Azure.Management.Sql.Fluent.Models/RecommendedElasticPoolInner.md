<Type Name="RecommendedElasticPoolInner" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner">
  <TypeSignature Language="C#" Value="public class RecommendedElasticPoolInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecommendedElasticPoolInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner" />
  <TypeSignature Language="VB.NET" Value="Public Class RecommendedElasticPoolInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type RecommendedElasticPoolInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="b7bb5-101">Stellt eine Azure SQL-elastischen Pool empfohlen.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-101">Represents an Azure SQL Recommended Elastic Pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendedElasticPoolInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b7bb5-102">Initialisiert eine neue Instanz der RecommendedElasticPoolInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-102">Initializes a new instance of the RecommendedElasticPoolInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendedElasticPoolInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string databaseEdition = null, Nullable&lt;double&gt; dtu = null, Nullable&lt;double&gt; databaseDtuMin = null, Nullable&lt;double&gt; databaseDtuMax = null, Nullable&lt;double&gt; storageMB = null, Nullable&lt;DateTime&gt; observationPeriodStart = null, Nullable&lt;DateTime&gt; observationPeriodEnd = null, Nullable&lt;double&gt; maxObservedDtu = null, Nullable&lt;double&gt; maxObservedStorageMB = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; databases = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt; metrics = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string databaseEdition, valuetype System.Nullable`1&lt;float64&gt; dtu, valuetype System.Nullable`1&lt;float64&gt; databaseDtuMin, valuetype System.Nullable`1&lt;float64&gt; databaseDtuMax, valuetype System.Nullable`1&lt;float64&gt; storageMB, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; observationPeriodStart, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; observationPeriodEnd, valuetype System.Nullable`1&lt;float64&gt; maxObservedDtu, valuetype System.Nullable`1&lt;float64&gt; maxObservedStorageMB, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; databases, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt; metrics) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Double},System.Nullable{System.Double},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional databaseEdition As String = null, Optional dtu As Nullable(Of Double) = null, Optional databaseDtuMin As Nullable(Of Double) = null, Optional databaseDtuMax As Nullable(Of Double) = null, Optional storageMB As Nullable(Of Double) = null, Optional observationPeriodStart As Nullable(Of DateTime) = null, Optional observationPeriodEnd As Nullable(Of DateTime) = null, Optional maxObservedDtu As Nullable(Of Double) = null, Optional maxObservedStorageMB As Nullable(Of Double) = null, Optional databases As IList(Of DatabaseInner) = null, Optional metrics As IList(Of RecommendedElasticPoolMetric) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner (location, id, name, type, tags, databaseEdition, dtu, databaseDtuMin, databaseDtuMax, storageMB, observationPeriodStart, observationPeriodEnd, maxObservedDtu, maxObservedStorageMB, databases, metrics)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="databaseEdition" Type="System.String" />
        <Parameter Name="dtu" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="databaseDtuMin" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="databaseDtuMax" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="storageMB" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="observationPeriodStart" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="observationPeriodEnd" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="maxObservedDtu" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="maxObservedStorageMB" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="databases" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;" />
        <Parameter Name="metrics" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="databaseEdition"><span data-ttu-id="b7bb5-103">Die Edition des Azure SQL empfohlene elastische Pools.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-103">The edition of the Azure SQL Recommended Elastic Pool.</span></span> <span data-ttu-id="b7bb5-104">Die ElasticPoolEditions-Enumeration enthält alle gültigen Editionen.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-104">The ElasticPoolEditions enumeration contains all the valid editions.</span></span> <span data-ttu-id="b7bb5-105">Folgende Werte sind möglich: "Basic", "Standard", "Premium"</span><span class="sxs-lookup"><span data-stu-id="b7bb5-105">Possible values include: 'Basic', 'Standard', 'Premium'</span></span></param>
        <param name="dtu"><span data-ttu-id="b7bb5-106">Die DTU für SQL Azure empfohlen elastischen Pool.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-106">The DTU for the SQL Azure Recommended Elastic Pool.</span></span></param>
        <param name="databaseDtuMin"><span data-ttu-id="b7bb5-107">Die minimale DTU für die Datenbank.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-107">The minimum DTU for the database.</span></span></param>
        <param name="databaseDtuMax"><span data-ttu-id="b7bb5-108">Die maximale DTU für die Datenbank.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-108">The maximum DTU for the database.</span></span></param>
        <param name="storageMB"><span data-ttu-id="b7bb5-109">Ruft die Speichergröße in Megabytes ab.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-109">Gets storage size in megabytes.</span></span></param>
        <param name="observationPeriodStart"><span data-ttu-id="b7bb5-110">Beobachtung beginnt (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="b7bb5-110">The observation period start (ISO8601 format).</span></span></param>
        <param name="observationPeriodEnd"><span data-ttu-id="b7bb5-111">Beobachtung beginnt (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="b7bb5-111">The observation period start (ISO8601 format).</span></span></param>
        <param name="maxObservedDtu"><span data-ttu-id="b7bb5-112">Ruft die maximale beobachtete DTU ab.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-112">Gets maximum observed DTU.</span></span></param>
        <param name="maxObservedStorageMB"><span data-ttu-id="b7bb5-113">Ruft maximale beobachteten Speicher in Megabyte an.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-113">Gets maximum observed storage in megabytes.</span></span></param>
        <param name="databases"><span data-ttu-id="b7bb5-114">Die Liste der Azure SQL-Datenbanken in diesem Pool.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-114">The list of Azure SQL Databases in this pool.</span></span> <span data-ttu-id="b7bb5-115">Erweiterte Eigenschaft</span><span class="sxs-lookup"><span data-stu-id="b7bb5-115">Expanded property</span></span></param>
        <param name="metrics"><span data-ttu-id="b7bb5-116">Die Liste der Azure SQL-Datenbanken auf dem Server untergebracht.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-116">The list of Azure SQL Databases housed in the server.</span></span> <span data-ttu-id="b7bb5-117">Erweiterte Eigenschaft</span><span class="sxs-lookup"><span data-stu-id="b7bb5-117">Expanded property</span></span></param>
        <summary>
            <span data-ttu-id="b7bb5-118">Initialisiert eine neue Instanz der RecommendedElasticPoolInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-118">Initializes a new instance of the RecommendedElasticPoolInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseDtuMax">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; DatabaseDtuMax { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; DatabaseDtuMax" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.DatabaseDtuMax" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseDtuMax As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.DatabaseDtuMax : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.DatabaseDtuMax" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseDtuMax")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7bb5-119">Ruft ab oder legt die maximale DTU für die Datenbank.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-119">Gets or sets the maximum DTU for the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseDtuMin">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; DatabaseDtuMin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; DatabaseDtuMin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.DatabaseDtuMin" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseDtuMin As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.DatabaseDtuMin : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.DatabaseDtuMin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseDtuMin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7bb5-120">Ruft ab oder legt die minimale DTU für die Datenbank.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-120">Gets or sets the minimum DTU for the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseEdition">
      <MemberSignature Language="C#" Value="public string DatabaseEdition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseEdition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.DatabaseEdition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseEdition As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseEdition : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.DatabaseEdition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseEdition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7bb5-121">Ruft die Edition des Azure SQL empfohlene elastische Pools ab.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-121">Gets the edition of the Azure SQL Recommended Elastic Pool.</span></span> <span data-ttu-id="b7bb5-122">Die ElasticPoolEditions-Enumeration enthält alle gültigen Editionen.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-122">The ElasticPoolEditions enumeration contains all the valid editions.</span></span>
            <span data-ttu-id="b7bb5-123">Folgende Werte sind möglich: "Basic", "Standard", "Premium"</span><span class="sxs-lookup"><span data-stu-id="b7bb5-123">Possible values include: 'Basic', 'Standard', 'Premium'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Databases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; Databases { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; Databases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.Databases" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Databases As IList(Of DatabaseInner)" />
      <MemberSignature Language="F#" Value="member this.Databases : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.Databases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7bb5-124">Ruft die Liste der Azure SQL-Datenbanken in diesem Pool.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-124">Gets the list of Azure SQL Databases in this pool.</span></span> <span data-ttu-id="b7bb5-125">Erweiterte Eigenschaft</span><span class="sxs-lookup"><span data-stu-id="b7bb5-125">Expanded property</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dtu">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Dtu { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Dtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.Dtu" />
      <MemberSignature Language="VB.NET" Value="Public Property Dtu As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Dtu : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.Dtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dtu")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7bb5-126">Ermittelt oder definiert die DTU für die SQL Azure empfohlen elastischen Pool.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-126">Gets or sets the DTU for the SQL Azure Recommended Elastic Pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxObservedDtu">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MaxObservedDtu { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MaxObservedDtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.MaxObservedDtu" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxObservedDtu As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MaxObservedDtu : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.MaxObservedDtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxObservedDtu")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7bb5-127">Ruft die maximale beobachtete DTU ab.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-127">Gets maximum observed DTU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxObservedStorageMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MaxObservedStorageMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MaxObservedStorageMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.MaxObservedStorageMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxObservedStorageMB As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MaxObservedStorageMB : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.MaxObservedStorageMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxObservedStorageMB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7bb5-128">Ruft maximale beobachteten Speicher in Megabyte an.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-128">Gets maximum observed storage in megabytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt; Metrics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt; Metrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metrics As IList(Of RecommendedElasticPoolMetric)" />
      <MemberSignature Language="F#" Value="member this.Metrics : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.Metrics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metrics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7bb5-129">Ruft die Liste der Azure SQL-Datenbanken auf dem Server untergebracht ab.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-129">Gets the list of Azure SQL Databases housed in the server.</span></span> <span data-ttu-id="b7bb5-130">Erweiterte Eigenschaft</span><span class="sxs-lookup"><span data-stu-id="b7bb5-130">Expanded property</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObservationPeriodEnd">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ObservationPeriodEnd { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ObservationPeriodEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.ObservationPeriodEnd" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ObservationPeriodEnd As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ObservationPeriodEnd : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.ObservationPeriodEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.observationPeriodEnd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7bb5-131">Ruft die Beobachtung zeitraumstarts (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="b7bb5-131">Gets the observation period start (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObservationPeriodStart">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ObservationPeriodStart { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ObservationPeriodStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.ObservationPeriodStart" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ObservationPeriodStart As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ObservationPeriodStart : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.ObservationPeriodStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.observationPeriodStart")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7bb5-132">Ruft die Beobachtung zeitraumstarts (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="b7bb5-132">Gets the observation period start (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; StorageMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; StorageMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.StorageMB" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageMB As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.StorageMB : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner.StorageMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageMB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7bb5-133">Ruft die Speichergröße in Megabytes ab.</span><span class="sxs-lookup"><span data-stu-id="b7bb5-133">Gets storage size in megabytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>