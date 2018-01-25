<Type Name="ClusterHealthPolicy" FullName="System.Fabric.Health.ClusterHealthPolicy">
  <TypeSignature Language="C#" Value="public class ClusterHealthPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterHealthPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ClusterHealthPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterHealthPolicy" />
  <TypeSignature Language="F#" Value="type ClusterHealthPolicy = class" />
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
      <para><span data-ttu-id="ac56e-101">Definiert eine Integritätsrichtlinie, die zur Bewertung der Integritäts des Clusters oder eines Clusterknotens.</span><span class="sxs-lookup"><span data-stu-id="ac56e-101">Defines a health policy used to evaluate the health of the cluster or of a cluster node.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="ac56e-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ClusterHealthPolicy" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ac56e-102">Initializes a new instance of the <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> class.</span></span></para>
        </summary>
        <remarks><span data-ttu-id="ac56e-103">Standardmäßig werden keine Fehler oder Warnungen toleriert werden.</span><span class="sxs-lookup"><span data-stu-id="ac56e-103">By default, no errors or warnings are tolerated.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationTypeHealthPolicyMap ApplicationTypeHealthPolicyMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationTypeHealthPolicyMap ApplicationTypeHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthPolicy.ApplicationTypeHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeHealthPolicyMap As ApplicationTypeHealthPolicyMap" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeHealthPolicyMap : System.Fabric.Health.ApplicationTypeHealthPolicyMap" Usage="System.Fabric.Health.ClusterHealthPolicy.ApplicationTypeHealthPolicyMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationTypeHealthPolicyMap</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="ac56e-104">Ruft die Zuordnung mit MaxPercentUnhealthyApplications pro Anwendung Typnamen ab.</span><span class="sxs-lookup"><span data-stu-id="ac56e-104">Gets the map with MaxPercentUnhealthyApplications per application type name.</span></span> 
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="ac56e-105">Anwendung Integrität Richtlinie Typzuordnung mit MaxPercentUnhealthyApplications pro Name des Anwendungstyps.</span><span class="sxs-lookup"><span data-stu-id="ac56e-105">The application type health policy map with MaxPercentUnhealthyApplications per application type name.</span></span></para>
        </value>
        <remarks>
          <span data-ttu-id="ac56e-106"><para>Anwendung Integrität Richtlinie Typzuordnung kann während integritätsevaluierung Cluster verwendet werden, um spezielle Anwendungstypen zu beschreiben. Standardmäßig werden alle Anwendungen in einem Pool versetzt und mit ausgewertet <see cref="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />. Wenn eine oder mehrere Anwendungstypen speziell sind und müssen Sitzungsschlüsseln auf eine andere Weise behandelt außerhalb des globalen Pools und anhand der Prozentsätze mit ihrer Anwendung Typnamen in der Zuordnung verknüpfte ausgewertet. Beispielsweise enthält ein Cluster Tausende von Anwendungen mit unterschiedlichen Typen und wenige Steueranwendungsinstanzen eines besonderen Anwendungstyps. Die Steueranwendungen dürfen niemals einen Fehlerstatus aufweisen. Daher können Benutzer angeben, globale MaxPercentUnhealthyApplications 20 % tolerieren einige, aber für die Anwendung vom Typ "ControlApplicationType" die MaxPercentUnhealthyApplications auf 0 festgelegt. Wenn einige der zahlreichen Anwendungen fehlerhaft sind, aber unter dem globalen Prozentsatz für fehlerhafte Anwendungen liegen, wird der Cluster mit einer Warnung ausgewertet. Der Integritätszustand „Warnung“ wirkt sich nicht auf ein Clusterupgrade oder auf andere Überwachungen aus, die durch den Integritätszustand „Fehler“ ausgelöst werden. Aber auch nur ein einziges Steuerelement Anwendung Fehler stellen Cluster Integritätsfehler, welche Rollback kann oder zu verhindern, dass eine clusterupgrade würde. </para>&gt;<para>Für die Anwendungstypen, die in der Zuordnung definiert wird, werden alle Anwendungsinstanzen aus den globalen Pool Anwendungen übernommen. Sie werden anhand des speziellen MaxPercentUnhealthyApplications-Werts aus der Zuordnung basierend auf der Gesamtanzahl von Anwendungen des Anwendungstyps ausgewertet. Alle übrigen Anwendungen verbleiben in den globalen Pool und mit MaxPercentUnhealthyApplications ausgewertet werden. </para> <para>Um Einträge für die bestimmte Anwendungstypen im clustermanifest zu definieren, FabricSettings fügen Sie Einträge für den Parameter mit dem Namen gebildet, indem das Präfix "ApplicationTypeMaxPercentUnhealthyApplications-" gefolgt von Name des Anwendungstyps. </para> <para>Wenn keine Richtlinie für einen Anwendungstyp angegeben wird, ist die Standardeinstellung MaxPercentUnhealthyApplications zur Auswertung verwendet.</para> <para>Die Anwendung Typ integritätsauswertung erfolgt nur, wenn der Cluster mit EnableApplicationTypeHealthEvaluation konfiguriert ist <languageKeyword>"true"</languageKeyword>. Die Einstellung ist standardmäßig deaktiviert.</para></span><span class="sxs-lookup"><span data-stu-id="ac56e-106"><para>The application type health policy map can be used during cluster health evaluation to describe special application types. By default, all applications are put into a pool and evaluated with <see cref="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />. If one or more application types are special and should be treated in a different way, they can be taken out of the global pool and evaluated against the percentages associated with their application type name in the map. For example, in a cluster there are thousands of applications of different types, and a few control application instances of a special application type. The control applications should never be in error. So users can specify global MaxPercentUnhealthyApplications to 20% to tolerate some failures, but for the application type "ControlApplicationType" set the MaxPercentUnhealthyApplications to 0. This way, if some of the many applications are unhealthy, but below the global unhealthy percentage, the cluster would be evaluated to Warning. A warning health state does not impact cluster upgrade or other monitoring triggered by Error health state. But even one control application in error would make cluster health error, which can rollback or prevent a cluster upgrade. </para>&gt; <para>For the application types defined in the map, all application instances are taken out of the global pool of applications. They are evaluated based on the total number of applications of the application type, using the specific MaxPercentUnhealthyApplications from the map. All the rest of the applications remain in the global pool and are evaluated with MaxPercentUnhealthyApplications.</para><para>To define entries for the specific application types in the cluster manifest, inside FabricSettings add entries for parameters with name formed by prefix "ApplicationTypeMaxPercentUnhealthyApplications-" followed by application type name.</para><para>If no policy is specified for an application type, the default MaxPercentUnhealthyApplications is used for evaluation.</para><para>The application type health evaluation is done only when the cluster is configured with EnableApplicationTypeHealthEvaluation <languageKeyword>true</languageKeyword>. The setting is disabled by default. </para></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsiderWarningAsError">
      <MemberSignature Language="C#" Value="public bool ConsiderWarningAsError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ConsiderWarningAsError" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthPolicy.ConsiderWarningAsError" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsiderWarningAsError As Boolean" />
      <MemberSignature Language="F#" Value="member this.ConsiderWarningAsError : bool with get, set" Usage="System.Fabric.Health.ClusterHealthPolicy.ConsiderWarningAsError" />
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
          <para><span data-ttu-id="ac56e-107">Ruft ab oder legt einen <see cref="T:System.Boolean" /> , der bestimmt, ob Berichte mit Status "Warnung" mit den gleichen Schweregrad als Fehler behandelt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="ac56e-107">Gets or sets a <see cref="T:System.Boolean" /> that determines whether reports with warning state should be treated with the same severity as errors.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="ac56e-108"><languageKeyword>"true"</languageKeyword> Wenn Berichte mit Status "Warnung" als Fehler behandelt werden sollen <languageKeyword>"false"</languageKeyword> Wenn Warnungen nicht als Fehler behandelt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="ac56e-108"><languageKeyword>true</languageKeyword> if reports with warning state should be treated as errors; <languageKeyword>false</languageKeyword> if warnings should not be treated as errors.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyApplications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyApplications : byte with get, set" Usage="System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ac56e-109">Ruft ab oder legt die maximal zulässigen Prozentsatz fehlerhafter Anwendungen.</span><span class="sxs-lookup"><span data-stu-id="ac56e-109">Gets or sets the maximum allowed percentage of unhealthy applications.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ac56e-110">Die maximal zulässige Prozentsatz fehlerhafter Anwendungen.</span><span class="sxs-lookup"><span data-stu-id="ac56e-110">The maximum allowed percentage of unhealthy applications.</span></span> <span data-ttu-id="ac56e-111">Zulässige Werte sind ganzzahlige Werte von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="ac56e-111">Allowed values are integer values from zero to 100.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="ac56e-112">Der Prozentsatz entspricht dem maximalen tolerierten Prozentsatz an Anwendungen, die fehlerhaft sein können, bevor der Cluster als fehlerhaft behandelt wird.</span><span class="sxs-lookup"><span data-stu-id="ac56e-112">The percentage represents the maximum tolerated percentage of applications that can be unhealthy before the cluster is considered in error.</span></span> <span data-ttu-id="ac56e-113">Wird der Prozentsatz eingehalten, gibt es aber mindestens eine fehlerhafte Anwendung, wird die Integrität als „Warning“ ausgewertet.</span><span class="sxs-lookup"><span data-stu-id="ac56e-113">If the percentage is respected but there is at least one unhealthy application, the health is evaluated as Warning.</span></span>
            <span data-ttu-id="ac56e-114">Dies wird durch Dividieren der Anzahl der fehlerhaften Anwendungen über die Gesamtzahl der Anwendungen, die im Cluster ist, mit Ausnahme von Anwendungstypen, die in enthalten sind alle Anwendungen bereitgestellt berechnet die <see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />.</span><span class="sxs-lookup"><span data-stu-id="ac56e-114">This is calculated by dividing the number of unhealthy applications over the total number of applications deployed in the cluster, excluding all applications of application types that are included in the <see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />.</span></span>
            <span data-ttu-id="ac56e-115">Die Berechnung wird aufgerundet, um einen Fehler bei einer kleinen Anzahl von Anwendungen zu tolerieren.</span><span class="sxs-lookup"><span data-stu-id="ac56e-115">The computation rounds up to tolerate one failure on small numbers of applications.</span></span> <span data-ttu-id="ac56e-116">Standardprozentsatz : null.</span><span class="sxs-lookup"><span data-stu-id="ac56e-116">Default percentage: zero.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="ac56e-117">Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="ac56e-117">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyNodes : byte with get, set" Usage="System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ac56e-118">Ruft ab oder legt die maximal zulässigen Prozentsatz fehlerhafter Knoten.</span><span class="sxs-lookup"><span data-stu-id="ac56e-118">Gets or sets the maximum allowed percentage of unhealthy nodes.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ac56e-119">Die maximal zulässige Prozentsatz fehlerhafter Knoten.</span><span class="sxs-lookup"><span data-stu-id="ac56e-119">The maximum allowed percentage of unhealthy nodes.</span></span> <span data-ttu-id="ac56e-120">Zulässige Werte sind ganzzahlige Werte von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="ac56e-120">Allowed values are integer values from zero to 100.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="ac56e-121">Der Prozentsatz entspricht dem maximalen tolerierten Prozentsatz an Knoten, die fehlerhaft sein können, bevor der Cluster als fehlerhaft behandelt wird.</span><span class="sxs-lookup"><span data-stu-id="ac56e-121">The percentage represents the maximum tolerated percentage of nodes that can be unhealthy before the cluster is considered in error.</span></span> <span data-ttu-id="ac56e-122">Wird der Prozentsatz eingehalten, gibt es aber mindestens einen fehlerhaften Knoten, wird die Integrität als „Warning“ ausgewertet.</span><span class="sxs-lookup"><span data-stu-id="ac56e-122">If the percentage is respected but there is at least one unhealthy node, the health is evaluated as Warning.</span></span>
            <span data-ttu-id="ac56e-123">Dies wird durch Dividieren der Anzahl der fehlerhaften Knoten über die Gesamtanzahl der Knoten im Cluster berechnet.</span><span class="sxs-lookup"><span data-stu-id="ac56e-123">This is calculated by dividing the number of unhealthy nodes over the total number of nodes in the cluster.</span></span>
            <span data-ttu-id="ac56e-124">Die Berechnung wird aufgerundet, um einen Fehler auf einer kleinen Anzahl von Knoten zu tolerieren.</span><span class="sxs-lookup"><span data-stu-id="ac56e-124">The computation rounds up to tolerate one failure on small numbers of nodes.</span></span> <span data-ttu-id="ac56e-125">Standardprozentsatz : null.</span><span class="sxs-lookup"><span data-stu-id="ac56e-125">Default percentage: zero.</span></span>
            </para>
          <para><span data-ttu-id="ac56e-126">Beim Konfigurieren dieses Prozentsatzes muss berücksichtigt werden, dass in großen Clustern immer einige Knoten inaktiv oder aufgrund von Wartungsarbeiten nicht verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="ac56e-126">In large clusters, some nodes will always be down or out for repairs, so this percentage should be configured to tolerate that.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="ac56e-127">Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="ac56e-127">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthPolicy.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterHealthPolicy.ToString " />
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
            <span data-ttu-id="ac56e-128">Ruft eine Zeichenfolgendarstellung der clusterintegritätsrichtlinie ab.</span><span class="sxs-lookup"><span data-stu-id="ac56e-128">Gets a string representation of the cluster health policy.</span></span>
            </summary>
        <returns><span data-ttu-id="ac56e-129">Eine Zeichenfolgendarstellung der clusterintegritätsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="ac56e-129">A string representation of the cluster health policy.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>