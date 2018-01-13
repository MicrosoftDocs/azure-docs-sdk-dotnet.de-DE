<Type Name="Shard" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard">
  <TypeSignature Language="C#" Value="public sealed class Shard : IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Shard extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Shard&#xA;Implements IEquatable(Of Shard)" />
  <TypeSignature Language="F#" Value="type Shard = class&#xA;    interface IShardProvider&lt;ShardLocation&gt;&#xA;    interface IShardProvider&#xA;    interface ICloneable&lt;Shard&gt;&#xA;    interface IEquatable&lt;Shard&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="55a2e-101">Darstellung von einem einzelnen shard zusammengeführt.</span><span class="sxs-lookup"><span data-stu-id="55a2e-101">Representation of a single shard.</span></span> <span data-ttu-id="55a2e-102">Shards sind also im Grunde Locators für Datenquellen <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />s, die mit einer shardzuordnung registriert wurden.</span><span class="sxs-lookup"><span data-stu-id="55a2e-102">Shards are basically locators for data sources i.e. <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />s that have been registered with a shard map.</span></span> <span data-ttu-id="55a2e-103">Shards werden bei der Zuordnung als Ziele von Zuordnungen verwendet (siehe <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1" /> und <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1" />).</span><span class="sxs-lookup"><span data-stu-id="55a2e-103">Shards are used in mapping as targets of mappings (see <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1" /> and <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1" />).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Shard" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&#xA;override this.Clone : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" Usage="shard.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ICloneable`1.Clone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="55a2e-104">Klont die Instanz.</span><span class="sxs-lookup"><span data-stu-id="55a2e-104">Clones the instance.</span></span>
            </summary>
        <returns><span data-ttu-id="55a2e-105">Klon der Instanz.</span><span class="sxs-lookup"><span data-stu-id="55a2e-105">Clone of the instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.Equals(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Shard) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard -&gt; bool" Usage="shard.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="55a2e-106">Shard zu mit verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="55a2e-106">Shard to compare with.</span></span></param>
        <summary>
            <span data-ttu-id="55a2e-107">Führt einen Gleichheitsvergleich für die angegebenen Shard.</span><span class="sxs-lookup"><span data-stu-id="55a2e-107">Performs equality comparison with given Shard.</span></span>
            </summary>
        <returns><span data-ttu-id="55a2e-108">Andernfalls ist "true", wenn dieses Objekt gleich andere Objekt, "false".</span><span class="sxs-lookup"><span data-stu-id="55a2e-108">True if this object is equal to other object, false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="shard.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="55a2e-109">Das Objekt, das mit dem aktuellen Objekt verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="55a2e-109">The object to compare with the current object.</span></span></param>
        <summary>
            <span data-ttu-id="55a2e-110">Bestimmt, ob das angegebene Objekt mit dem aktuellen Objekt identisch ist.</span><span class="sxs-lookup"><span data-stu-id="55a2e-110">Determines whether the specified object is equal to the current object.</span></span>
            </summary>
        <returns><span data-ttu-id="55a2e-111">True, wenn das angegebene Objekt mit dem aktuellen Objekt identisch ist. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="55a2e-111">True if the specified object is equal to the current object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="shard.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="55a2e-112">Berechnet den Hashcode für diese Instanz an.</span><span class="sxs-lookup"><span data-stu-id="55a2e-112">Calculates the hash code for this instance.</span></span>
            </summary>
        <returns><span data-ttu-id="55a2e-113">Der Hashcode für das Objekt.</span><span class="sxs-lookup"><span data-stu-id="55a2e-113">Hash code for the object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As ShardLocation" />
      <MemberSignature Language="F#" Value="member this.Location : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55a2e-114">Ruft die Position des betreffenden Shards ab.</span><span class="sxs-lookup"><span data-stu-id="55a2e-114">Gets Location of the shard.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnection">
      <MemberSignature Language="C#" Value="public System.Data.SqlClient.SqlConnection OpenConnection (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.SqlClient.SqlConnection OpenConnection(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.OpenConnection(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnection (connectionString As String) As SqlConnection" />
      <MemberSignature Language="F#" Value="member this.OpenConnection : string -&gt; System.Data.SqlClient.SqlConnection" Usage="shard.OpenConnection connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.SqlClient.SqlConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">
            <span data-ttu-id="55a2e-115">Verbindungszeichenfolge mit Anmeldeinformationen, z. B. SQL Server-Anmeldeinformationen oder die integrierte Sicherheit von Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="55a2e-115">Connection string with credential information such as SQL Server credentials or Integrated Security settings.</span></span> <span data-ttu-id="55a2e-116">Der Hostname des Servers und den Datenbanknamen für den Shard werden von der Suchvorgang für Schlüssel abgerufen.</span><span class="sxs-lookup"><span data-stu-id="55a2e-116">The hostname of the server and the database name for the shard are obtained from the lookup operation for key.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a2e-117">Öffnet eine reguläre <see cref="T:System.Data.SqlClient.SqlConnection" /> zum angegebenen Shard mit <see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />.</span><span class="sxs-lookup"><span data-stu-id="55a2e-117">Opens a regular <see cref="T:System.Data.SqlClient.SqlConnection" /> to the specified shard, with <see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="55a2e-118">Beachten Sie, dass die <see cref="T:System.Data.SqlClient.SqlConnection" /> durch diesen Aufruf zurückgegebene Objekt ist nicht geschützt gegen vorübergehende Fehler.</span><span class="sxs-lookup"><span data-stu-id="55a2e-118">Note that the <see cref="T:System.Data.SqlClient.SqlConnection" /> object returned by this call is not protected against transient faults.</span></span> <span data-ttu-id="55a2e-119">Aufrufer sollten bewährte Methoden, um die Verbindung für vorübergehende Fehler in ihrem Anwendungscode, z. B. zu schützen, mithilfe der Funktionalität in der Enterprise-Bibliothek von Microsoft Patterns and Practices-Team behandeln vorübergehenden Fehlers folgen.</span><span class="sxs-lookup"><span data-stu-id="55a2e-119">Callers should follow best practices to protect the connection against transient faults in their application code, e.g., by using the transient fault handling functionality in the Enterprise Library from Microsoft Patterns and Practices team.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnection">
      <MemberSignature Language="C#" Value="public System.Data.SqlClient.SqlConnection OpenConnection (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.SqlClient.SqlConnection OpenConnection(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.OpenConnection(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnection (connectionString As String, options As ConnectionOptions) As SqlConnection" />
      <MemberSignature Language="F#" Value="member this.OpenConnection : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions -&gt; System.Data.SqlClient.SqlConnection" Usage="shard.OpenConnection (connectionString, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.SqlClient.SqlConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions" />
      </Parameters>
      <Docs>
        <param name="connectionString">
            <span data-ttu-id="55a2e-120">Verbindungszeichenfolge mit Anmeldeinformationen, z. B. SQL Server-Anmeldeinformationen oder die integrierte Sicherheit von Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="55a2e-120">Connection string with credential information such as SQL Server credentials or Integrated Security settings.</span></span> <span data-ttu-id="55a2e-121">Der Hostname des Servers und den Datenbanknamen für den Shard werden von der Suchvorgang für Schlüssel abgerufen.</span><span class="sxs-lookup"><span data-stu-id="55a2e-121">The hostname of the server and the database name for the shard are obtained from the lookup operation for key.</span></span>
            </param>
        <param name="options"><span data-ttu-id="55a2e-122">Optionen für Validierungsvorgänge auf geöffnete Verbindung ausführen.</span><span class="sxs-lookup"><span data-stu-id="55a2e-122">Options for validation operations to perform on opened connection.</span></span></param>
        <summary>
            <span data-ttu-id="55a2e-123">Öffnet eine reguläre <see cref="T:System.Data.SqlClient.SqlConnection" /> zum angegebenen Shard.</span><span class="sxs-lookup"><span data-stu-id="55a2e-123">Opens a regular <see cref="T:System.Data.SqlClient.SqlConnection" /> to the specified shard.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="55a2e-124">Beachten Sie, dass die <see cref="T:System.Data.SqlClient.SqlConnection" /> durch diesen Aufruf zurückgegebene Objekt ist nicht geschützt gegen vorübergehende Fehler.</span><span class="sxs-lookup"><span data-stu-id="55a2e-124">Note that the <see cref="T:System.Data.SqlClient.SqlConnection" /> object returned by this call is not protected against transient faults.</span></span> <span data-ttu-id="55a2e-125">Aufrufer sollten bewährte Methoden, um die Verbindung für vorübergehende Fehler in ihrem Anwendungscode, z. B. zu schützen, mithilfe der Funktionalität in der Enterprise-Bibliothek von Microsoft Patterns and Practices-Team behandeln vorübergehenden Fehlers folgen.</span><span class="sxs-lookup"><span data-stu-id="55a2e-125">Callers should follow best practices to protect the connection against transient faults in their application code, e.g., by using the transient fault handling functionality in the Enterprise Library from Microsoft Patterns and Practices team.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt; OpenConnectionAsync (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.SqlClient.SqlConnection&gt; OpenConnectionAsync(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.OpenConnectionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionAsync (connectionString As String) As Task(Of SqlConnection)" />
      <MemberSignature Language="F#" Value="member this.OpenConnectionAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;" Usage="shard.OpenConnectionAsync connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">
            <span data-ttu-id="55a2e-126">Verbindungszeichenfolge mit Anmeldeinformationen, z. B. SQL Server-Anmeldeinformationen oder die integrierte Sicherheit von Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="55a2e-126">Connection string with credential information such as SQL Server credentials or Integrated Security settings.</span></span> <span data-ttu-id="55a2e-127">Der Hostname des Servers und den Datenbanknamen für den Shard werden von der Suchvorgang für Schlüssel abgerufen.</span><span class="sxs-lookup"><span data-stu-id="55a2e-127">The hostname of the server and the database name for the shard are obtained from the lookup operation for key.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a2e-128">Asynchron öffnet eine reguläre <see cref="T:System.Data.SqlClient.SqlConnection" /> zum angegebenen Shard mit <see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />.</span><span class="sxs-lookup"><span data-stu-id="55a2e-128">Asynchronously opens a regular <see cref="T:System.Data.SqlClient.SqlConnection" /> to the specified shard, with <see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />.</span></span>
            </summary>
        <returns><span data-ttu-id="55a2e-129">Eine Aufgabe, die eine geöffnete SqlConnection kapseln</span><span class="sxs-lookup"><span data-stu-id="55a2e-129">A Task encapsulating an opened SqlConnection</span></span></returns>
        <remarks>
            <span data-ttu-id="55a2e-130">Beachten Sie, dass die <see cref="T:System.Data.SqlClient.SqlConnection" /> durch diesen Aufruf zurückgegebene Objekt ist nicht geschützt gegen vorübergehende Fehler.</span><span class="sxs-lookup"><span data-stu-id="55a2e-130">Note that the <see cref="T:System.Data.SqlClient.SqlConnection" /> object returned by this call is not protected against transient faults.</span></span> <span data-ttu-id="55a2e-131">Aufrufer sollten bewährte Methoden, um die Verbindung für vorübergehende Fehler in ihrem Anwendungscode, z. B. zu schützen, mithilfe der Funktionalität in der Enterprise-Bibliothek von Microsoft Patterns and Practices-Team behandeln vorübergehenden Fehlers folgen.</span><span class="sxs-lookup"><span data-stu-id="55a2e-131">Callers should follow best practices to protect the connection against transient faults in their application code, e.g., by using the transient fault handling functionality in the Enterprise Library from Microsoft Patterns and Practices team.</span></span>
            <span data-ttu-id="55a2e-132">Alle nicht-Usage-Fehler werden über die zurückgegebene Aufgabe weitergegeben.</span><span class="sxs-lookup"><span data-stu-id="55a2e-132">All non-usage errors will be propagated via the returned Task.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt; OpenConnectionAsync (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.SqlClient.SqlConnection&gt; OpenConnectionAsync(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.OpenConnectionAsync(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionAsync (connectionString As String, options As ConnectionOptions) As Task(Of SqlConnection)" />
      <MemberSignature Language="F#" Value="member this.OpenConnectionAsync : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions -&gt; System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;" Usage="shard.OpenConnectionAsync (connectionString, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions" />
      </Parameters>
      <Docs>
        <param name="connectionString">
            <span data-ttu-id="55a2e-133">Verbindungszeichenfolge mit Anmeldeinformationen, z. B. SQL Server-Anmeldeinformationen oder die integrierte Sicherheit von Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="55a2e-133">Connection string with credential information such as SQL Server credentials or Integrated Security settings.</span></span> <span data-ttu-id="55a2e-134">Der Hostname des Servers und den Datenbanknamen für den Shard werden von der Suchvorgang für Schlüssel abgerufen.</span><span class="sxs-lookup"><span data-stu-id="55a2e-134">The hostname of the server and the database name for the shard are obtained from the lookup operation for key.</span></span>
            </param>
        <param name="options"><span data-ttu-id="55a2e-135">Optionen für Validierungsvorgänge auf geöffnete Verbindung ausführen.</span><span class="sxs-lookup"><span data-stu-id="55a2e-135">Options for validation operations to perform on opened connection.</span></span></param>
        <summary>
            <span data-ttu-id="55a2e-136">Asynchron eine reguläre <see cref="T:System.Data.SqlClient.SqlConnection" /> zum angegebenen Shard.</span><span class="sxs-lookup"><span data-stu-id="55a2e-136">Asynchronously a regular <see cref="T:System.Data.SqlClient.SqlConnection" /> to the specified shard.</span></span>
            </summary>
        <returns><span data-ttu-id="55a2e-137">Eine Aufgabe, die eine geöffnete SqlConnection kapseln</span><span class="sxs-lookup"><span data-stu-id="55a2e-137">A Task encapsulating an opened SqlConnection</span></span></returns>
        <remarks>
            <span data-ttu-id="55a2e-138">Beachten Sie, dass die <see cref="T:System.Data.SqlClient.SqlConnection" /> durch diesen Aufruf zurückgegebene Objekt ist nicht geschützt gegen vorübergehende Fehler.</span><span class="sxs-lookup"><span data-stu-id="55a2e-138">Note that the <see cref="T:System.Data.SqlClient.SqlConnection" /> object returned by this call is not protected against transient faults.</span></span> <span data-ttu-id="55a2e-139">Aufrufer sollten bewährte Methoden, um die Verbindung für vorübergehende Fehler in ihrem Anwendungscode, z. B. zu schützen, mithilfe der Funktionalität in der Enterprise-Bibliothek von Microsoft Patterns and Practices-Team behandeln vorübergehenden Fehlers folgen.</span><span class="sxs-lookup"><span data-stu-id="55a2e-139">Callers should follow best practices to protect the connection against transient faults in their application code, e.g., by using the transient fault handling functionality in the Enterprise Library from Microsoft Patterns and Practices team.</span></span>
            <span data-ttu-id="55a2e-140">Alle nicht-Usage-Fehler werden über die zurückgegebene Aufgabe weitergegeben.</span><span class="sxs-lookup"><span data-stu-id="55a2e-140">All non-usage errors will be propagated via the returned Task.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="shard.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="55a2e-141">Konvertiert das Objekt in seine Zeichenfolgendarstellung.</span><span class="sxs-lookup"><span data-stu-id="55a2e-141">Converts the object to its string representation.</span></span>
            </summary>
        <returns><span data-ttu-id="55a2e-142">Entspricht der Zeichenfolgendarstellung des Objekts.</span><span class="sxs-lookup"><span data-stu-id="55a2e-142">String representation of the object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>