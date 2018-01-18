<Type Name="PagedApplicationTypeQueryDescription" FullName="System.Fabric.Description.PagedApplicationTypeQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class PagedApplicationTypeQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PagedApplicationTypeQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PagedApplicationTypeQueryDescription" />
  <TypeSignature Language="F#" Value="type PagedApplicationTypeQueryDescription = class" />
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
      <para><span data-ttu-id="01ed1-101">Beschreibt einen Satz von Filtern, die beim Ausführen der Abfrage verwendeten <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.</span><span class="sxs-lookup"><span data-stu-id="01ed1-101">Describes a set of filters used when running the query <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="01ed1-102">Die Standardwerte für diese abfragebeschreibung stellen Sie sicher, dass die Ergebnisse werden auf der ersten Seite zurückgegeben und keine Filter anwenden.</span><span class="sxs-lookup"><span data-stu-id="01ed1-102">The default values of this query description ensure that results are returned from the first page and apply no filters.</span></span>
            <span data-ttu-id="01ed1-103">Diese abfragebeschreibung kann durch Festlegen einzelner Eigenschaften angepasst werden.</span><span class="sxs-lookup"><span data-stu-id="01ed1-103">This query description can be customized by setting individual properties.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PagedApplicationTypeQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.PagedApplicationTypeQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="01ed1-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="01ed1-104">Initializes a new instance of the <see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeDefinitionKindFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationTypeDefinitionKindFilter ApplicationTypeDefinitionKindFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ApplicationTypeDefinitionKindFilter ApplicationTypeDefinitionKindFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeDefinitionKindFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeDefinitionKindFilter As ApplicationTypeDefinitionKindFilter" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeDefinitionKindFilter : System.Fabric.Description.ApplicationTypeDefinitionKindFilter with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeDefinitionKindFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationTypeDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="01ed1-105">Abrufen oder Festlegen der definitionsart verwendet, um die Anwendungstypen zu filtern, die zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="01ed1-105">Gets or sets the definition kind used to filter the application types that will be returned.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="01ed1-106">Die definitionsart verwendet, um die Anwendungstypen zu filtern.</span><span class="sxs-lookup"><span data-stu-id="01ed1-106">The definition kind used to filter the application types.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="01ed1-107">Wenn ApplicationTypeDefinitionKindFilter nicht angegeben ist, würde das Ergebnis nicht durch definitionsart gefiltert werden.</span><span class="sxs-lookup"><span data-stu-id="01ed1-107">If ApplicationTypeDefinitionKindFilter is not specified, the result would not be filtered by definition kind.</span></span></para>
          <para><span data-ttu-id="01ed1-108">ApplicationTypeNameFilter und ApplicationTypeDefinitionKindFilter können nicht zusammen angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="01ed1-108">ApplicationTypeNameFilter and ApplicationTypeDefinitionKindFilter can not be specified together.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeNameFilter">
      <MemberSignature Language="C#" Value="public string ApplicationTypeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeNameFilter : string with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeNameFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="01ed1-109">Ruft ab, oder legt ihn fest zum Abrufen der Details für den Anwendungstyp.</span><span class="sxs-lookup"><span data-stu-id="01ed1-109">Gets or sets the application type to get details for.</span></span></para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="01ed1-110">Der Standardwert ist Null, was die Anwendungstypen übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="01ed1-110">Defaults to null, which matches all the application types.</span></span>
            </para>
          <para>
            <span data-ttu-id="01ed1-111">Dieser Parameter entspricht, für die Groß-/Kleinschreibung beachtet genaue anwendungstypnamen im Manifest Anwendung alle bereitgestellten oder Bereitstellung Anwendungstypen definiert.</span><span class="sxs-lookup"><span data-stu-id="01ed1-111">This parameter matches against the case sensitive exact application type names defined in the application manifest of all provisioned or provisioning application types.</span></span> <span data-ttu-id="01ed1-112">Beispielsweise entspricht dem Wert "Test" nicht "TestApp", da sie nur eine teilweise Übereinstimmung ist.</span><span class="sxs-lookup"><span data-stu-id="01ed1-112">For example, the value "Test" does not match "TestApp" because it is only a partial match.</span></span>
            <span data-ttu-id="01ed1-113">Dieser Wert dürfen nicht für die Version des Anwendungstyps und alle Versionen der gleichen Anwendung Typnamen entspricht.</span><span class="sxs-lookup"><span data-stu-id="01ed1-113">This value should not contain the version of the application type, and matches all versions of the same application type name.</span></span>
            <span data-ttu-id="01ed1-114">Legen Sie diesen Wert, um anzufordern, dass die Anwendungstypen nicht der Fall ist.</span><span class="sxs-lookup"><span data-stu-id="01ed1-114">To request all the application types do not set this value.</span></span>
            </para>
          <para>
            <span data-ttu-id="01ed1-115">ApplicationTypeNameFilter und ApplicationTypeDefinitionKindFilter können nicht zusammen angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="01ed1-115">ApplicationTypeNameFilter and ApplicationTypeDefinitionKindFilter can not be specified together.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeVersionFilter">
      <MemberSignature Language="C#" Value="public string ApplicationTypeVersionFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeVersionFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeVersionFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeVersionFilter As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeVersionFilter : string with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeVersionFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="01ed1-116">Ruft ab oder legt die Version der Anwendung zum Abrufen der Details für.</span><span class="sxs-lookup"><span data-stu-id="01ed1-116">Gets or sets the application type version to get details for.</span></span>
            </para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="01ed1-117">Der Standardwert ist Null, das alle für die Anwendung übereinstimmt, geben Sie Versionen von einer bestimmten Anwendung Type-Name.</span><span class="sxs-lookup"><span data-stu-id="01ed1-117">Defaults to null, which matches all the application type versions of a given application type name.</span></span> <span data-ttu-id="01ed1-118">Dieser Filter sollte bereitgestellt werden, nur, wenn eine Anwendung Typ Namensfilter auch bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="01ed1-118">This filter should be provided only if an application type name filter is also provided.</span></span>
            </para>
          <para>
            <span data-ttu-id="01ed1-119">Dieser Parameter entspricht, für die Groß-/Kleinschreibung beachtet genaue anwendungstypversion im Manifest Anwendung alle bereitgestellten oder Bereitstellung Anwendungstypen definiert.</span><span class="sxs-lookup"><span data-stu-id="01ed1-119">This parameter matches against the case sensitive exact application type version defined in the application manifest of all provisioned or provisioning application types.</span></span>
            <span data-ttu-id="01ed1-120">Beispielsweise entspricht Version "v1" nicht Version "1.0", da sie nur eine teilweise Übereinstimmung ist.</span><span class="sxs-lookup"><span data-stu-id="01ed1-120">For example, version "v1" does not match version "v1.0" because it is only a partial match.</span></span>
            <span data-ttu-id="01ed1-121">Um alle anwendungstypversionen des Namens einer Anwendung anfordern, legen Sie diesen Wert nicht.</span><span class="sxs-lookup"><span data-stu-id="01ed1-121">To request all the application type versions of an application type name, do not set this value.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="01ed1-122">Ermittelt oder definiert das Fortsetzungstoken, das zum Abrufen der nächsten Seite verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="01ed1-122">Gets or sets the continuation token which can be used to retrieve the next page.</span></span></para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="01ed1-123">Wird standardmäßig auf Null, was die Seite eine Abfrageergebnisse zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="01ed1-123">Defaults to null, which returns page one of query results.</span></span>
            </para>
          <para>
            <span data-ttu-id="01ed1-124">Wenn zu viele Ergebnisse den Filter berücksichtigt, können sie eine Nachricht nicht ausreicht.</span><span class="sxs-lookup"><span data-stu-id="01ed1-124">If too many results respect the filter, they may not fit into one message.</span></span>
            <span data-ttu-id="01ed1-125">Paging wird verwendet, um dies zu berücksichtigen und teilen Sie die Auflistung der <see cref="T:System.Fabric.Query.ApplicationType" />s in getrennte Seiten.</span><span class="sxs-lookup"><span data-stu-id="01ed1-125">Paging is used to account for this by splitting the collection of <see cref="T:System.Fabric.Query.ApplicationType" />s into separate pages.</span></span>
            <span data-ttu-id="01ed1-126">Das Fortsetzungstoken wird verwendet, um wissen, an die vorherige Seite unterbrochen Durchführung der "significance" nur für die Abfrage selbst.</span><span class="sxs-lookup"><span data-stu-id="01ed1-126">The continuation token is used to know where the previous page left off, carrying significance only to the query itself.</span></span>
            <span data-ttu-id="01ed1-127">Dieser Wert Ausführung dieser Abfrage generiert werden soll, und übergeben werden kann, in der nächsten abfrageanforderung, um auf den nachfolgenden Seiten zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="01ed1-127">This value should be generated from running this query, and can be passed into the next query request in order to get subsequent pages.</span></span>
            <span data-ttu-id="01ed1-128">Ein fortsetzungstokenwert ungleich Null wird als Teil des Resultsets zurückgegeben werden, nur, wenn eine nachfolgende Seite vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="01ed1-128">A non-null continuation token value is returned as part of the result only if there is a subsequent page.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeApplicationParameters">
      <MemberSignature Language="C#" Value="public bool ExcludeApplicationParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeApplicationParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ExcludeApplicationParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeApplicationParameters As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeApplicationParameters : bool with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ExcludeApplicationParameters" />
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
          <para><span data-ttu-id="01ed1-129">Ruft ab oder legt fest, ob das Abfrageergebnis Anwendungsparameter ausgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="01ed1-129">Gets or sets whether to exclude application parameters from the query result.</span></span></para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="01ed1-130">Der Standardwert ist "false".</span><span class="sxs-lookup"><span data-stu-id="01ed1-130">Defaults to false.</span></span>
            </para>
          <para>
            <span data-ttu-id="01ed1-131">Eine Einstellung auf "true" bewirkt, dass die <see cref="P:System.Fabric.Query.ApplicationType.DefaultParameters" /> leer.</span><span class="sxs-lookup"><span data-stu-id="01ed1-131">Setting this to true leaves the <see cref="P:System.Fabric.Query.ApplicationType.DefaultParameters" /> blank.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public long MaxResults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxResults" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxResults As Long" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int64 with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="01ed1-132">Ruft ab oder legt die maximale Anzahl von <see cref="T:System.Fabric.Query.ApplicationType" />s, die pro Seite zurückgegeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="01ed1-132">Gets or sets the max number of <see cref="T:System.Fabric.Query.ApplicationType" />s that can be returned per page.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="01ed1-133">Der Standardwert ist der maximale Wert vom Typ long.</span><span class="sxs-lookup"><span data-stu-id="01ed1-133">Defaults to the max value of type long.</span></span>
            </para>
          <para><span data-ttu-id="01ed1-134">Dadurch wird nur die obere Grenze für die Anzahl von Anwendungstypen zurückgegeben wird, nicht auf ein Minimum definiert.</span><span class="sxs-lookup"><span data-stu-id="01ed1-134">This defines only the upper bound for the number of application types returned, not a minimum.</span></span>
            <span data-ttu-id="01ed1-135">Beispielsweise, wenn die Seite höchstens 1000 zurückgegeben passt Elemente nach der maximalen Größe des Nachrichtenempfangs in der Konfiguration definiert und der Wert von "maxresults" auf 2000 festgelegt ist, und klicken Sie dann nur 1000 Ergebnisse zurückgegeben werden, auch wenn 2000 Anwendungstypen Beschreibung der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="01ed1-135">For example, if the page fits at most 1000 returned items according to max message size restrictions defined in the configuration, and the MaxResults value is set to 2000, then only 1000 results are returned, even if 2000 application types match the query description.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.PagedApplicationTypeQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="pagedApplicationTypeQueryDescription.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="01ed1-136">Überschreibt ToString()-Methode, um alle Inhalte der Beschreibung der Abfrage zu drucken.</span><span class="sxs-lookup"><span data-stu-id="01ed1-136">Overrides ToString() method to print all content of the query description.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="01ed1-137">Gibt eine Zeichenfolge, enthält alle Eigenschaften der Beschreibung der Abfrage zurück.</span><span class="sxs-lookup"><span data-stu-id="01ed1-137">Returns a string containing all the properties of the query description.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>