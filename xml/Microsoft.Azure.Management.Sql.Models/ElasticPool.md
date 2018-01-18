<Type Name="ElasticPool" FullName="Microsoft.Azure.Management.Sql.Models.ElasticPool">
  <TypeSignature Language="C#" Value="public class ElasticPool : Microsoft.Azure.Management.Sql.Models.TrackedResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ElasticPool extends Microsoft.Azure.Management.Sql.Models.TrackedResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ElasticPool" />
  <TypeSignature Language="VB.NET" Value="Public Class ElasticPool&#xA;Inherits TrackedResource" />
  <TypeSignature Language="F#" Value="type ElasticPool = class&#xA;    inherit TrackedResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.TrackedResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c2fa6-101">Stellt einen elastischen Datenbankpool dar.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-101">Represents a database elastic pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPool.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c2fa6-102">Initialisiert eine neue Instanz der ElasticPool-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-102">Initializes a new instance of the ElasticPool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPool (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;DateTime&gt; creationDate = null, string state = null, string edition = null, Nullable&lt;int&gt; dtu = null, Nullable&lt;int&gt; databaseDtuMax = null, Nullable&lt;int&gt; databaseDtuMin = null, Nullable&lt;int&gt; storageMB = null, Nullable&lt;bool&gt; zoneRedundant = null, string kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationDate, string state, string edition, valuetype System.Nullable`1&lt;int32&gt; dtu, valuetype System.Nullable`1&lt;int32&gt; databaseDtuMax, valuetype System.Nullable`1&lt;int32&gt; databaseDtuMin, valuetype System.Nullable`1&lt;int32&gt; storageMB, valuetype System.Nullable`1&lt;bool&gt; zoneRedundant, string kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPool.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional creationDate As Nullable(Of DateTime) = null, Optional state As String = null, Optional edition As String = null, Optional dtu As Nullable(Of Integer) = null, Optional databaseDtuMax As Nullable(Of Integer) = null, Optional databaseDtuMin As Nullable(Of Integer) = null, Optional storageMB As Nullable(Of Integer) = null, Optional zoneRedundant As Nullable(Of Boolean) = null, Optional kind As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ElasticPool : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPool" Usage="new Microsoft.Azure.Management.Sql.Models.ElasticPool (location, id, name, type, tags, creationDate, state, edition, dtu, databaseDtuMax, databaseDtuMin, storageMB, zoneRedundant, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="creationDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="edition" Type="System.String" />
        <Parameter Name="dtu" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="databaseDtuMax" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="databaseDtuMin" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="storageMB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="zoneRedundant" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="kind" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="c2fa6-103">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-103">Resource location.</span></span></param>
        <param name="id"><span data-ttu-id="c2fa6-104">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="c2fa6-104">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="c2fa6-105">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-105">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="c2fa6-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-106">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="c2fa6-107">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-107">Resource tags.</span></span></param>
        <param name="creationDate"><span data-ttu-id="c2fa6-108">Das Erstellungsdatum des elastischen Pools (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="c2fa6-108">The creation date of the elastic pool (ISO8601 format).</span></span></param>
        <param name="state"><span data-ttu-id="c2fa6-109">Der Status des elastischen Pools.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-109">The state of the elastic pool.</span></span> <span data-ttu-id="c2fa6-110">Folgende Werte sind möglich: "Erstellen", "bereit", "Deaktiviert"</span><span class="sxs-lookup"><span data-stu-id="c2fa6-110">Possible values include: 'Creating', 'Ready', 'Disabled'</span></span></param>
        <param name="edition"><span data-ttu-id="c2fa6-111">Die Edition des elastischen Pools.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-111">The edition of the elastic pool.</span></span> <span data-ttu-id="c2fa6-112">Folgende Werte sind möglich: "Basic", "Standard", "Premium"</span><span class="sxs-lookup"><span data-stu-id="c2fa6-112">Possible values include: 'Basic', 'Standard', 'Premium'</span></span></param>
        <param name="dtu"><span data-ttu-id="c2fa6-113">Die Gesamtgröße des freigegebenen DTU für des elastischen datenbankpools.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-113">The total shared DTU for the database elastic pool.</span></span></param>
        <param name="databaseDtuMax"><span data-ttu-id="c2fa6-114">Die maximale DTU, die eine beliebige Datenbank verbraucht werden kann.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-114">The maximum DTU any one database can consume.</span></span></param>
        <param name="databaseDtuMin"><span data-ttu-id="c2fa6-115">Die minimale DTU, die alle Datenbanken garantiert werden kann.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-115">The minimum DTU all databases are guaranteed.</span></span></param>
        <param name="storageMB"><span data-ttu-id="c2fa6-116">Ruft die Speicherobergrenze für den elastischen Pool der Datenbank in MB ab.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-116">Gets storage limit for the database elastic pool in MB.</span></span></param>
        <param name="zoneRedundant"><span data-ttu-id="c2fa6-117">Davon, ob diesen elastischen Datenbankpool zonenredundant, ist, d. die Replikate für diese Datenbank h. wird auf mehreren Verfügbarkeit Zonen verteilt werden.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-117">Whether or not this database elastic pool is zone redundant, which means the replicas of this database will be spread across multiple availability zones.</span></span></param>
        <param name="kind"><span data-ttu-id="c2fa6-118">Die Art des elastischen Pools.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-118">Kind of elastic pool.</span></span>  <span data-ttu-id="c2fa6-119">Dies ist die Metadaten für die Azure portalumgebung verwendet.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-119">This is metadata used for the Azure portal experience.</span></span></param>
        <summary>
            <span data-ttu-id="c2fa6-120">Initialisiert eine neue Instanz der ElasticPool-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-120">Initializes a new instance of the ElasticPool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPool.CreationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPool.CreationDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2fa6-121">Ruft das Erstellungsdatum des elastischen Pools (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="c2fa6-121">Gets the creation date of the elastic pool (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseDtuMax">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DatabaseDtuMax { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DatabaseDtuMax" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPool.DatabaseDtuMax" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseDtuMax As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DatabaseDtuMax : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPool.DatabaseDtuMax" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseDtuMax")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2fa6-122">Ruft ab oder legt die maximale DTU, die eine beliebige Datenbank nutzen kann.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-122">Gets or sets the maximum DTU any one database can consume.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseDtuMin">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DatabaseDtuMin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DatabaseDtuMin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPool.DatabaseDtuMin" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseDtuMin As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DatabaseDtuMin : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPool.DatabaseDtuMin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseDtuMin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2fa6-123">Ruft ab oder legt die minimale DTU, die alle Datenbanken garantiert werden kann.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-123">Gets or sets the minimum DTU all databases are guaranteed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dtu">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Dtu { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Dtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPool.Dtu" />
      <MemberSignature Language="VB.NET" Value="Public Property Dtu As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Dtu : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPool.Dtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dtu")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2fa6-124">Abrufen oder festlegen die gesamte freigegebene DTU für des elastischen datenbankpools.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-124">Gets or sets the total shared DTU for the database elastic pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Edition">
      <MemberSignature Language="C#" Value="public string Edition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Edition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPool.Edition" />
      <MemberSignature Language="VB.NET" Value="Public Property Edition As String" />
      <MemberSignature Language="F#" Value="member this.Edition : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPool.Edition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.edition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2fa6-125">Ruft ab oder legt die Edition des elastischen Pools.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-125">Gets or sets the edition of the elastic pool.</span></span> <span data-ttu-id="c2fa6-126">Folgende Werte sind möglich: "Basic", "Standard", "Premium"</span><span class="sxs-lookup"><span data-stu-id="c2fa6-126">Possible values include: 'Basic', 'Standard', 'Premium'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPool.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPool.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2fa6-127">Ruft die Art von elastischen Pool ab.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-127">Gets kind of elastic pool.</span></span>  <span data-ttu-id="c2fa6-128">Dies ist die Metadaten für die Azure portalumgebung verwendet.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-128">This is metadata used for the Azure portal experience.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPool.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPool.State" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2fa6-129">Ruft den Zustand des elastischen Pools.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-129">Gets the state of the elastic pool.</span></span> <span data-ttu-id="c2fa6-130">Folgende Werte sind möglich: "Erstellen", "bereit", "Deaktiviert"</span><span class="sxs-lookup"><span data-stu-id="c2fa6-130">Possible values include: 'Creating', 'Ready', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; StorageMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; StorageMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPool.StorageMB" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageMB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.StorageMB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPool.StorageMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageMB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2fa6-131">Ruft die Speicherobergrenze für den elastischen Pool der Datenbank in MB ab.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-131">Gets storage limit for the database elastic pool in MB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPool.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="elasticPool.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c2fa6-132">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-132">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c2fa6-133">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="c2fa6-133">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ZoneRedundant">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ZoneRedundant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ZoneRedundant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPool.ZoneRedundant" />
      <MemberSignature Language="VB.NET" Value="Public Property ZoneRedundant As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ZoneRedundant : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPool.ZoneRedundant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.zoneRedundant")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2fa6-134">Ruft ab, oder legt ihn fest, und zwar unabhängig davon, ob diesen elastischen Datenbankpool ist, dass mehrere Verfügbarkeit Zonen zonenredundant, d. die Replikate für diese Datenbank h. verteilt werden.</span><span class="sxs-lookup"><span data-stu-id="c2fa6-134">Gets or sets whether or not this database elastic pool is zone redundant, which means the replicas of this database will be spread across multiple availability zones.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>