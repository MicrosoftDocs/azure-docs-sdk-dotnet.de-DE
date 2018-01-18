<Type Name="HealthInformation" FullName="System.Fabric.Health.HealthInformation">
  <TypeSignature Language="C#" Value="public sealed class HealthInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HealthInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HealthInformation" />
  <TypeSignature Language="F#" Value="type HealthInformation = class" />
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
      <para><span data-ttu-id="46883-101">Stellt die allgemeine Integrität Berichtsinformationen dar.</span><span class="sxs-lookup"><span data-stu-id="46883-101">Represents common health report information.</span></span>
            <span data-ttu-id="46883-102">Es ist in allen Integritätsberichte im Health Store gesendet und in allen integritätsereignisse integritätsabfragen zurückgegebenes enthalten.</span><span class="sxs-lookup"><span data-stu-id="46883-102">It is included in all health reports sent to the health store and in all health events returned by health queries.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HealthInformation (string sourceId, string property, System.Fabric.Health.HealthState healthState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sourceId, string property, valuetype System.Fabric.Health.HealthState healthState) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthInformation.#ctor(System.String,System.String,System.Fabric.Health.HealthState)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.HealthInformation : string * string * System.Fabric.Health.HealthState -&gt; System.Fabric.Health.HealthInformation" Usage="new System.Fabric.Health.HealthInformation (sourceId, property, healthState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceId" Type="System.String" />
        <Parameter Name="property" Type="System.String" />
        <Parameter Name="healthState" Type="System.Fabric.Health.HealthState" />
      </Parameters>
      <Docs>
        <param name="sourceId">
          <para><span data-ttu-id="46883-103">Die Quelle des Berichts.</span><span class="sxs-lookup"><span data-stu-id="46883-103">The source of the report.</span></span> <span data-ttu-id="46883-104">Er darf nicht <languageKeyword>null</languageKeyword> oder leer sein.</span><span class="sxs-lookup"><span data-stu-id="46883-104">It cannot be <languageKeyword>null</languageKeyword> or empty.</span></span>
            <span data-ttu-id="46883-105">Es kann nicht gestartet werden mit"System", also reserviertes Schlüsselwort für die reporting-Komponenten.</span><span class="sxs-lookup"><span data-stu-id="46883-105">It can't start with "System.", which is reserved keyword for system components reporting.</span></span></para>
        </param>
        <param name="property">
          <para><span data-ttu-id="46883-106">Die Eigenschaft des Berichts.</span><span class="sxs-lookup"><span data-stu-id="46883-106">The property of the report.</span></span> <span data-ttu-id="46883-107">Er darf nicht <languageKeyword>null</languageKeyword> oder leer sein.</span><span class="sxs-lookup"><span data-stu-id="46883-107">It cannot be <languageKeyword>null</languageKeyword> or empty.</span></span></para>
        </param>
        <param name="healthState">
          <para><span data-ttu-id="46883-108">Der Integritätsstatus des Berichts.</span><span class="sxs-lookup"><span data-stu-id="46883-108">The health state of the report.</span></span> <span data-ttu-id="46883-109">Muss angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="46883-109">Must be specified.</span></span>
            <span data-ttu-id="46883-110">Muss die <see cref="F:System.Fabric.Health.HealthState.Error" />, <see cref="F:System.Fabric.Health.HealthState.Warning" /> oder <see cref="F:System.Fabric.Health.HealthState.Ok" /> Werte.</span><span class="sxs-lookup"><span data-stu-id="46883-110">Must be one of the <see cref="F:System.Fabric.Health.HealthState.Error" />, <see cref="F:System.Fabric.Health.HealthState.Warning" /> or <see cref="F:System.Fabric.Health.HealthState.Ok" /> values.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46883-111">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.HealthInformation" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="46883-111">Initializes a new instance of the <see cref="T:System.Fabric.Health.HealthInformation" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>
            <span data-ttu-id="46883-112"><paramref name="property" />nicht mit <languageKeyword>null</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="46883-112"><paramref name="property" /> cannot be <languageKeyword>null</languageKeyword>.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="46883-113">Angegebene <paramref name="healthState" /> wird nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="46883-113">Specified <paramref name="healthState" /> is not supported.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="AutoSequenceNumber">
      <MemberSignature Language="C#" Value="public const long AutoSequenceNumber = 0;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int64 AutoSequenceNumber = (0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Health.HealthInformation.AutoSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Const AutoSequenceNumber As Long  = 0" />
      <MemberSignature Language="F#" Value="val mutable AutoSequenceNumber : int64" Usage="System.Fabric.Health.HealthInformation.AutoSequenceNumber" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="46883-114">Automatische log Sequence Number, eine gültige Sequenznummer vom Health Client ersetzt.</span><span class="sxs-lookup"><span data-stu-id="46883-114">Auto sequence number, replaced with a valid sequence number by the health client.</span></span>
            </summary>
        <remarks><span data-ttu-id="46883-115">Wenn ein Integritäts-Client einen Bericht mit Auto-Sequenznummer empfängt, wird die Sequenznummer automatisch mit ein gültige Sequenznummer ersetzt.</span><span class="sxs-lookup"><span data-stu-id="46883-115">When a health client receives a report with Auto sequence number, it replaces the auto sequence number with a valid sequence number.</span></span>
            <span data-ttu-id="46883-116">Die Sequenznummer ist garantiert im selben Prozess erhöhen.</span><span class="sxs-lookup"><span data-stu-id="46883-116">The sequence number is guaranteed to increase in the same process.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="System.Fabric.Health.HealthInformation.Description" />
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
          <para><span data-ttu-id="46883-117">Ruft ab oder legt die Beschreibung des Integritätsinformationen zu.</span><span class="sxs-lookup"><span data-stu-id="46883-117">Gets or sets the description of the health information.</span></span> <span data-ttu-id="46883-118">Es stellt freien Text zum Hinzufügen von Menschen lesbare Informationen über die überwachte Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="46883-118">It represents free text used to add human readable information about the monitored condition.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="46883-119">Ein <see cref="T:System.String" /> der beschrieben wird, die Zustandsinformationen in Menschen lesbaren Format.</span><span class="sxs-lookup"><span data-stu-id="46883-119">A <see cref="T:System.String" /> which describes the health information in human readable form.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="46883-120">Die maximale Länge der Beschreibung beträgt 4096 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="46883-120">The maximum string length for the description is 4096 characters.</span></span>
            <span data-ttu-id="46883-121">Wenn die bereitgestellte Zeichenfolge länger ist, wird er automatisch abgeschnitten.</span><span class="sxs-lookup"><span data-stu-id="46883-121">If the provided string is longer, it will be automatically truncated.</span></span>
            <span data-ttu-id="46883-122">Wenn abgeschnitten, enthalten die letzten Zeichen in der Beschreibung einen Marker "[abgeschnitten]", und die Größe der gesamten beträgt 4096 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="46883-122">When truncated, the last characters of the description contain a marker "[Truncated]", and total string size is 4096 characters.</span></span>
            <span data-ttu-id="46883-123">Das Vorhandensein des Markers gibt Benutzer an, dass Daten abgeschnitten ist aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="46883-123">The presence of the marker indicates to users that truncation occurred.</span></span>
            <span data-ttu-id="46883-124">Beachten Sie, dass wenn abgeschnitten, die Beschreibung enthält weniger als 4096 Zeichen aus der ursprünglichen Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="46883-124">Note that when truncated, the description has less than 4096 characters from the original string.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.HealthInformation.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="46883-125">Ruft den Integritätsstatus, der den Schweregrad der überwachten Bedingung für die Berichterstattung verwendet beschreibt.</span><span class="sxs-lookup"><span data-stu-id="46883-125">Gets the health state that describes the severity of the monitored condition used for reporting.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="46883-126">Der Integritätsstatus, der den Schweregrad der überwachten Bedingung für die Berichterstattung verwendet beschreibt.</span><span class="sxs-lookup"><span data-stu-id="46883-126">The health state that describes the severity of the monitored condition used for reporting.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="46883-127">Die zulässigen Zustände sind <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" /> und <see cref="F:System.Fabric.Health.HealthState.Error" />.</span><span class="sxs-lookup"><span data-stu-id="46883-127">The accepted health states are <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" /> and <see cref="F:System.Fabric.Health.HealthState.Error" />.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Property">
      <MemberSignature Language="C#" Value="public string Property { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Property" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.Property" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Property As String" />
      <MemberSignature Language="F#" Value="member this.Property : string" Usage="System.Fabric.Health.HealthInformation.Property" />
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
          <para><span data-ttu-id="46883-128">Ruft die Eigenschaft des integritätsberichts ab.</span><span class="sxs-lookup"><span data-stu-id="46883-128">Gets the property of the health report.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="46883-129">Die Eigenschaft der Integritätsbericht senden.</span><span class="sxs-lookup"><span data-stu-id="46883-129">The property of the health report.</span></span> <span data-ttu-id="46883-130">Zusammen mit den <see cref="P:System.Fabric.Health.HealthInformation.SourceId" />, eindeutig für die Zustandsinformationen.</span><span class="sxs-lookup"><span data-stu-id="46883-130">Together with the <see cref="P:System.Fabric.Health.HealthInformation.SourceId" />, it uniquely identifies the health information.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="46883-131">Die Eigenschaft ist ein <see cref="T:System.String" /> und keiner festen-Enumeration können die Reporter Flexibilität, um den Zustand zu kategorisieren, die den Bericht ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="46883-131">The property is a <see cref="T:System.String" /> and not a fixed enumeration to allow the reporter flexibility to categorize the state condition that triggers the report.</span></span>
            <span data-ttu-id="46883-132">Z. B. eine Reporter mit <see cref="P:System.Fabric.Health.HealthInformation.SourceId" /> "A" kann den Status der verfügbaren Datenträger auf einem Knoten überwachen, damit er "AvailableDisk"-Eigenschaft auf diesem Knoten melden kann.</span><span class="sxs-lookup"><span data-stu-id="46883-132">For example, a reporter with <see cref="P:System.Fabric.Health.HealthInformation.SourceId" /> "A" can monitor the state of the available disk on a node, so it can report "AvailableDisk" property on that node.</span></span>
            <span data-ttu-id="46883-133">Ein reporterfehler mit <see cref="P:System.Fabric.Health.HealthInformation.SourceId" /> "B" kann die Konnektivität Knoten überwachen, damit er eine Eigenschaft "Verbindungen" auf dem gleichen Knoten melden kann.</span><span class="sxs-lookup"><span data-stu-id="46883-133">A reporter with <see cref="P:System.Fabric.Health.HealthInformation.SourceId" /> "B" can monitor the node connectivity, so it can report a property "Connectivity" on the same node.</span></span>
            <span data-ttu-id="46883-134">Diese Berichte werden im Health Store als separate integritätsereignisse für den angegebenen Knoten behandelt.</span><span class="sxs-lookup"><span data-stu-id="46883-134">In the health store, these reports are treated as separate health events for the specified node.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveWhenExpired">
      <MemberSignature Language="C#" Value="public bool RemoveWhenExpired { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RemoveWhenExpired" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoveWhenExpired As Boolean" />
      <MemberSignature Language="F#" Value="member this.RemoveWhenExpired : bool with get, set" Usage="System.Fabric.Health.HealthInformation.RemoveWhenExpired" />
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
          <para><span data-ttu-id="46883-135">Ruft ab oder legt einen Wert, der angibt, ob der Bericht aus dem Health Store entfernt wird, wenn es abläuft.</span><span class="sxs-lookup"><span data-stu-id="46883-135">Gets or sets a value that indicates whether the report is removed from health store when it expires.</span></span> <span data-ttu-id="46883-136">Wenn auf festgelegt <languageKeyword>"false"</languageKeyword>, der Bericht so behandelt, als ein Fehler, wenn abgelaufen.</span><span class="sxs-lookup"><span data-stu-id="46883-136">If set to <languageKeyword>false</languageKeyword>, the report is treated as an error when expired.</span></span> <span data-ttu-id="46883-137"><languageKeyword>"false"</languageKeyword> standardmäßig.</span><span class="sxs-lookup"><span data-stu-id="46883-137"><languageKeyword>false</languageKeyword> by default.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="46883-138"><languageKeyword>"true"</languageKeyword> Wenn der Bericht aus dem Health Store entfernt werden sollen, wenn abgelaufen ist, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="46883-138"><languageKeyword>true</languageKeyword> if the report should be removed from health store when expired; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="46883-139">Wenn Clients in regelmäßigen Abständen senden möchten, legen sie <see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" /> <languageKeyword>"false"</languageKeyword> (Standard).</span><span class="sxs-lookup"><span data-stu-id="46883-139">When clients report periodically, they should set <see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" /><languageKeyword>false</languageKeyword> (default).</span></span>
            <span data-ttu-id="46883-140">Auf diese Weise ist die Reporter Probleme (z. b.</span><span class="sxs-lookup"><span data-stu-id="46883-140">This way, is the reporter has issues (eg.</span></span> <span data-ttu-id="46883-141">Deadlock) und kann nicht Berichten, die Entität wird auf Fehler ausgewertet, wenn Integritätsbericht senden abläuft, und dadurch wird die Entität als flag <see cref="F:System.Fabric.Health.HealthState.Error" />.</span><span class="sxs-lookup"><span data-stu-id="46883-141">deadlock) and can't report, the entity is evaluated at error when the health report expires, and this will flag the entity as <see cref="F:System.Fabric.Health.HealthState.Error" />.</span></span>
            <span data-ttu-id="46883-142">Periodische Integritätsdienst-Clients sollten Berichte mit höheren Häufigkeit als Gültigkeitsdauer für Verzögerungen aufgrund von Health Client Batchverarbeitung tragen gesendet wird, Transport Verzögerungen bei der Nachricht über den über das Netzwerk und die Integrität speichern, verarbeiten.</span><span class="sxs-lookup"><span data-stu-id="46883-142">Periodic health clients should send reports with higher frequency than time to live to account for delays due to health client batching, message transport delays over the wire and health store processing.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64 with get, set" Usage="System.Fabric.Health.HealthInformation.SequenceNumber" />
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
          <para><span data-ttu-id="46883-143">Ruft ab oder legt die Sequenznummer der Zustandsinformationen zum Überalterung Erkennung durch den Health Store zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="46883-143">Gets or sets the sequence number associated with the health information, used by the health store for staleness detection.</span></span>
            <span data-ttu-id="46883-144">Muss größer sein als <see cref="F:System.Fabric.Health.HealthInformation.UnknownSequenceNumber" />.</span><span class="sxs-lookup"><span data-stu-id="46883-144">Must be greater than <see cref="F:System.Fabric.Health.HealthInformation.UnknownSequenceNumber" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="46883-145">Die Bericht-Sequenznummer Integritätsinformationen zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="46883-145">The report sequence number associated with the health information.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="46883-146">Die Sequenznummer des Berichts durch Health Store verwendet werden, um veraltete Berichte zu erkennen.</span><span class="sxs-lookup"><span data-stu-id="46883-146">The report sequence number is used by health store to detect stale reports.</span></span>
            </para>
          <para><span data-ttu-id="46883-147">Die meisten der Zeiten muss Reporter Geben Sie die Sequenznummer.</span><span class="sxs-lookup"><span data-stu-id="46883-147">Most of the times, the reporter doesn't need to specify the sequence number.</span></span> <span data-ttu-id="46883-148">Der Standardwert <see cref="F:System.Fabric.Health.HealthInformation.AutoSequenceNumber" /> kann stattdessen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="46883-148">The default value <see cref="F:System.Fabric.Health.HealthInformation.AutoSequenceNumber" /> can be used instead.</span></span> <span data-ttu-id="46883-149">Ein Integritäts-Client einen Bericht mit Auto-Sequenznummer empfängt, wird eine gültige Sequenznummer, die sichergestellt ist, erhöhen Sie im selben Prozess generiert.</span><span class="sxs-lookup"><span data-stu-id="46883-149">When a health client receives a report with Auto sequence number, it generates a valid sequence number, which is guaranteed to increase in the same process.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceId">
      <MemberSignature Language="C#" Value="public string SourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.SourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceId As String" />
      <MemberSignature Language="F#" Value="member this.SourceId : string" Usage="System.Fabric.Health.HealthInformation.SourceId" />
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
          <para><span data-ttu-id="46883-150">Ruft den Quellnamen, der Watchdog/Systemkomponente identifiziert, die die Zustandsinformationen generiert.</span><span class="sxs-lookup"><span data-stu-id="46883-150">Gets the source name which identifies the watchdog/system component which generated the health information.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="46883-151">Die Quelle des Integritätsbericht senden, das die Watchdog/Systemkomponente bezeichnet, die den Bericht erstellt.</span><span class="sxs-lookup"><span data-stu-id="46883-151">The source of the health report, which identifies the watchdog/system component that creates the report.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToLive" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : TimeSpan with get, set" Usage="System.Fabric.Health.HealthInformation.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="46883-152">Ruft ab oder legt sie fest, wie lange der Integritätsbericht gültig ist.</span><span class="sxs-lookup"><span data-stu-id="46883-152">Gets or sets how long the health report is valid.</span></span> <span data-ttu-id="46883-153">Muss größer sein als TimeSpan.Zero sein.</span><span class="sxs-lookup"><span data-stu-id="46883-153">Must be larger than TimeSpan.Zero.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="46883-154">Ein <see cref="T:System.TimeSpan" /> , die Zeit für die Gültigkeitsdauer des integritätsberichts darstellt.</span><span class="sxs-lookup"><span data-stu-id="46883-154">A <see cref="T:System.TimeSpan" /> representing the time to live of the health report.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="46883-155">Wenn Clients in regelmäßigen Abständen senden möchten, sollten sie Berichte mit höheren Häufigkeit als Gültigkeitsdauer senden.</span><span class="sxs-lookup"><span data-stu-id="46883-155">When clients report periodically, they should send reports with higher frequency than time to live.</span></span>
            <span data-ttu-id="46883-156">Wenn Clients auf den Übergang melden, können sie die Zeit für die Gültigkeitsdauer auf Infinite festgelegt.</span><span class="sxs-lookup"><span data-stu-id="46883-156">If clients report on transition, they can set the time to live to infinite.</span></span></para>
          <para><span data-ttu-id="46883-157">Ablauf der Gültigkeitsdauer der integritätsereignis, das die Zustandsinformationen enthält wird entweder entfernt aus dem Health Store, wenn <see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" /> ist <languageKeyword>"true"</languageKeyword> oder auf Fehler, ausgewertet werden, wenn <see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" /> ist <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="46883-157">When time to live expires, the health event that contains the health information is either removed from health store, if <see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" /> is <languageKeyword>true</languageKeyword> or evaluated at error, if <see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" /> is <languageKeyword>false</languageKeyword>.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="46883-158">Der angegebene Wert war ungültig.</span><span class="sxs-lookup"><span data-stu-id="46883-158">The specified value was invalid.</span></span> <span data-ttu-id="46883-159">Geben Sie eine Dauer, die größer als 0 ist.</span><span class="sxs-lookup"><span data-stu-id="46883-159">Please provide a duration that is larger than 0.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthInformation.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="healthInformation.ToString " />
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
            <span data-ttu-id="46883-160">Erstellt eine zeichenfolgenbeschreibung der Integritätsinformationen zu.</span><span class="sxs-lookup"><span data-stu-id="46883-160">Creates a string description of the health information.</span></span>
            </summary>
        <returns><span data-ttu-id="46883-161">Zeichenfolgenbeschreibung des Integritätsinformationen zu.</span><span class="sxs-lookup"><span data-stu-id="46883-161">String description of the health information.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnknownSequenceNumber">
      <MemberSignature Language="C#" Value="public const long UnknownSequenceNumber = -1;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int64 UnknownSequenceNumber = (-1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Health.HealthInformation.UnknownSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Const UnknownSequenceNumber As Long  = -1" />
      <MemberSignature Language="F#" Value="val mutable UnknownSequenceNumber : int64" Usage="System.Fabric.Health.HealthInformation.UnknownSequenceNumber" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <MemberValue>-1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="46883-162">Unbekannte Sequenznummer, die mit einer ungültigen Sequenznummer ist, die durch den Health Store nicht akzeptiert wird.</span><span class="sxs-lookup"><span data-stu-id="46883-162">Unknown sequence number, which is an invalid sequence number that is not accepted by the health store.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>