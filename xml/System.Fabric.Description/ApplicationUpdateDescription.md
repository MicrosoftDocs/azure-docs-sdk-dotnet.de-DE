<Type Name="ApplicationUpdateDescription" FullName="System.Fabric.Description.ApplicationUpdateDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationUpdateDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationUpdateDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationUpdateDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationUpdateDescription" />
  <TypeSignature Language="F#" Value="type ApplicationUpdateDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7f5be-101">Beschreibt ein Update der Anwendungskapazität, die aktualisiert werden<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" /></span><span class="sxs-lookup"><span data-stu-id="7f5be-101">Describes an update of application capacity that will be updated using <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" /></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationUpdateDescription (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationUpdateDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationUpdateDescription : Uri -&gt; System.Fabric.Description.ApplicationUpdateDescription" Usage="new System.Fabric.Description.ApplicationUpdateDescription applicationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="7f5be-102">Der URI des Instanznamens Anwendung.</span><span class="sxs-lookup"><span data-stu-id="7f5be-102">URI of the application instance name.</span></span></param>
        <summary>
            <span data-ttu-id="7f5be-103">Erstellt eine neue Instanz von <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" />.</span><span class="sxs-lookup"><span data-stu-id="7f5be-103">Creates a new instance of <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationUpdateDescription (Uri applicationName, bool removeApplicationCapacity, long minimumNodes, long maximumNodes, System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt; metrics);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, bool removeApplicationCapacity, int64 minimumNodes, int64 maximumNodes, class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ApplicationMetricDescription&gt; metrics) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationUpdateDescription.#ctor(System.Uri,System.Boolean,System.Int64,System.Int64,System.Collections.Generic.IList{System.Fabric.Description.ApplicationMetricDescription})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, removeApplicationCapacity As Boolean, minimumNodes As Long, maximumNodes As Long, metrics As IList(Of ApplicationMetricDescription))" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationUpdateDescription : Uri * bool * int64 * int64 * System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt; -&gt; System.Fabric.Description.ApplicationUpdateDescription" Usage="new System.Fabric.Description.ApplicationUpdateDescription (applicationName, removeApplicationCapacity, minimumNodes, maximumNodes, metrics)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="removeApplicationCapacity" Type="System.Boolean" />
        <Parameter Name="minimumNodes" Type="System.Int64" />
        <Parameter Name="maximumNodes" Type="System.Int64" />
        <Parameter Name="metrics" Type="System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt;" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="7f5be-104">Der URI des Instanznamens Anwendung.</span><span class="sxs-lookup"><span data-stu-id="7f5be-104">URI of the application instance name.</span></span></param>
        <param name="removeApplicationCapacity">
            <span data-ttu-id="7f5be-105">Gibt an, ob die Anwendungskapazität entfernt werden soll (siehe <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.RemoveApplicationCapacity" />).</span><span class="sxs-lookup"><span data-stu-id="7f5be-105">Indicates if application capacity should be removed (see <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.RemoveApplicationCapacity" />).</span></span>
            </param>
        <param name="minimumNodes">
            <span data-ttu-id="7f5be-106">Minimale Anzahl von Knoten (siehe <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />).</span><span class="sxs-lookup"><span data-stu-id="7f5be-106">Minimum number of nodes (see <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />).</span></span>
            </param>
        <param name="maximumNodes">
            <span data-ttu-id="7f5be-107">Maximale Anzahl von Knoten (siehe <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />)</span><span class="sxs-lookup"><span data-stu-id="7f5be-107">Maximum number of nodes (see <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />)</span></span>
            </param>
        <param name="metrics">
            <span data-ttu-id="7f5be-108">Kapazitätsmetriken für die Anwendung (siehe <see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" />)</span><span class="sxs-lookup"><span data-stu-id="7f5be-108">Application capacity metrics (see <see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" />)</span></span>
            </param>
        <summary>
            <span data-ttu-id="7f5be-109">Erstellt eine neue Instanz der <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" /> mit Anwendungsparameter-Kapazität.</span><span class="sxs-lookup"><span data-stu-id="7f5be-109">Creates a new instance of <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" /> with application capacity parameters.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpdateDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri with get, set" Usage="System.Fabric.Description.ApplicationUpdateDescription.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7f5be-110">Ruft ab oder legt den URI-Namen der Anwendungsinstanz.</span><span class="sxs-lookup"><span data-stu-id="7f5be-110">Gets or sets the URI name of the application instance.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7f5be-111">Der Anwendungsname.</span><span class="sxs-lookup"><span data-stu-id="7f5be-111">The application name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaximumNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaximumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumNodes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaximumNodes : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f5be-112">Ruft ab oder legt die maximale Anzahl von Knoten, in denen diese Anwendung instanziiert werden.</span><span class="sxs-lookup"><span data-stu-id="7f5be-112">Gets or sets the maximum number of nodes where this application can be instantiated.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="7f5be-113">Anzahl der Knoten, die diese Anwendung zulässig ist, umfassen.</span><span class="sxs-lookup"><span data-stu-id="7f5be-113">Number of nodes this application is allowed to span.</span></span> <span data-ttu-id="7f5be-114">Der Standardwert lautet null.</span><span class="sxs-lookup"><span data-stu-id="7f5be-114">Default value is zero.</span></span>
            <span data-ttu-id="7f5be-115">Ist er 0 (null), kann die Anwendung auf eine beliebige Anzahl von Knoten im Cluster befinden.</span><span class="sxs-lookup"><span data-stu-id="7f5be-115">If it is zero, Application can be placed on any number of nodes in the cluster.</span></span>
            <span data-ttu-id="7f5be-116">Wenn dieser Parameter nicht angegeben wird, wenn eine Anwendung zu aktualisieren, bleibt die maximale Anzahl von Knoten unverändert.</span><span class="sxs-lookup"><span data-stu-id="7f5be-116">If this parameter is not specified when updating an application, then the maximum number of nodes remains unchanged.</span></span>
            </para>
          <para>
            <span data-ttu-id="7f5be-117">Wenn dieser Parameter kleiner als <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" /> ein <see cref="T:System.ArgumentException" /> ausgelöst, wenn <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" /> aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="7f5be-117">If this parameter is smaller than <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" /> an <see cref="T:System.ArgumentException" /> will be thrown when <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" /> is called.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt; Metrics;" />
      <MemberSignature Language="ILAsm" Value=".field public class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ApplicationMetricDescription&gt; Metrics" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public Metrics As IList(Of ApplicationMetricDescription) " />
      <MemberSignature Language="F#" Value="val mutable Metrics : System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt;" Usage="System.Fabric.Description.ApplicationUpdateDescription.Metrics" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f5be-118">Ruft ab oder legt die Liste der Metriken für die die Anwendungskapazität definiert ist.</span><span class="sxs-lookup"><span data-stu-id="7f5be-118">Gets or sets the list of metrics for which the application capacity is defined.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7f5be-119">Gibt die metrische Kapazität der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="7f5be-119">Specifies the metric Capacity of the Application.</span></span> <span data-ttu-id="7f5be-120">Kapazität wird angegeben, für jede Metrik mit <see cref="T:System.Fabric.Description.ApplicationMetricDescription" />.</span><span class="sxs-lookup"><span data-stu-id="7f5be-120">Capacity is specified for each metric using <see cref="T:System.Fabric.Description.ApplicationMetricDescription" />.</span></span>
            <span data-ttu-id="7f5be-121">Wenn dieser Parameter nicht festgelegt ist, klicken Sie dann bleiben kapazitätsmetriken Anwendung unverändert bei der Anwendung zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="7f5be-121">If this parameter is not set, then application capacity metrics will remain unchanged when updating application.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MinimumNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MinimumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumNodes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MinimumNodes : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f5be-122">Ruft ab oder legt die Mindestanzahl von Knoten fest.</span><span class="sxs-lookup"><span data-stu-id="7f5be-122">Gets or sets the minimum number of nodes.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="7f5be-123">Anzahl der Knoten, auf dem Service Fabric Kapazität im Cluster für diese Anwendung platziert werden reservieren.</span><span class="sxs-lookup"><span data-stu-id="7f5be-123">Number of nodes where Service Fabric will reserve Capacity in the cluster for this Application to be placed.</span></span>
            <span data-ttu-id="7f5be-124">Beachten Sie, dass dies nicht bedeutet, dass die Anwendung unbedingt Replikate für alle diese Knoten verfügen.</span><span class="sxs-lookup"><span data-stu-id="7f5be-124">Note that this does not mean that the Application is guaranteed to have replicas on all those nodes.</span></span>
            </para>
          <para>
            <span data-ttu-id="7f5be-125">Wenn dieser Parameter auf NULL gesetzt wird, wird keine Kapazität reserviert werden.</span><span class="sxs-lookup"><span data-stu-id="7f5be-125">If this parameter is set to zero, no capacity will be reserved.</span></span> <span data-ttu-id="7f5be-126">Wenn dieser Parameter nicht festgelegt ist, wenn die Anwendung zu aktualisieren, bleibt die minimale Anzahl von Knoten unverändert.</span><span class="sxs-lookup"><span data-stu-id="7f5be-126">If this parameter is not set when updating application then the minimum number of nodes remains unchanged.</span></span>
            </para>
          <para>
            <span data-ttu-id="7f5be-127">Wenn dieser Parameter ist größer als <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" /> und wenn beide Parameter angegeben werden und dann eine <see cref="T:System.ArgumentException" /> ausgelöst, wenn <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" /> aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="7f5be-127">If this parameters is greater than <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" /> and if both parameters are specified then an <see cref="T:System.ArgumentException" /> will be thrown when <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" /> is called.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveApplicationCapacity">
      <MemberSignature Language="C#" Value="public bool RemoveApplicationCapacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RemoveApplicationCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpdateDescription.RemoveApplicationCapacity" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoveApplicationCapacity As Boolean" />
      <MemberSignature Language="F#" Value="member this.RemoveApplicationCapacity : bool with get, set" Usage="System.Fabric.Description.ApplicationUpdateDescription.RemoveApplicationCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f5be-128">Ruft ab oder legt das Flag RemoveApplicationCapacity fest.</span><span class="sxs-lookup"><span data-stu-id="7f5be-128">Gets or sets the RemoveApplicationCapacity flag.</span></span>
            </summary>
        <value>
            <span data-ttu-id="7f5be-129">So löschen Sie alle Parameter, die im Zusammenhang mit der Anwendungskapazität für diese Anwendung verwendet.</span><span class="sxs-lookup"><span data-stu-id="7f5be-129">Used to clear all parameters related to Application Capacity for this application.</span></span>
            <span data-ttu-id="7f5be-130">Es ist nicht möglich, dieser Parameter zusammen mit anderen Parametern Anwendungskapazität angeben.</span><span class="sxs-lookup"><span data-stu-id="7f5be-130">It is not possible to specify this parameter together with other Application Capacity parameters.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>