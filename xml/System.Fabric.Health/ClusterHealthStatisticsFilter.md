<Type Name="ClusterHealthStatisticsFilter" FullName="System.Fabric.Health.ClusterHealthStatisticsFilter">
  <TypeSignature Language="C#" Value="public sealed class ClusterHealthStatisticsFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterHealthStatisticsFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ClusterHealthStatisticsFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterHealthStatisticsFilter" />
  <TypeSignature Language="F#" Value="type ClusterHealthStatisticsFilter = class" />
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
      <para><span data-ttu-id="759f0-101">Stellt den Filter für <see cref="T:System.Fabric.Health.HealthStatistics" />.</span><span class="sxs-lookup"><span data-stu-id="759f0-101">Represents the filter for <see cref="T:System.Fabric.Health.HealthStatistics" />.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="759f0-102">Der Filter kann verwendet werden, <see cref="T:System.Fabric.Description.ClusterHealthQueryDescription" /> angeben, ob die Integrität Statistiken sollen, im Rahmen des zurückgegeben werden <see cref="T:System.Fabric.Health.ClusterHealth" />.</span><span class="sxs-lookup"><span data-stu-id="759f0-102">The filter can be used in <see cref="T:System.Fabric.Description.ClusterHealthQueryDescription" /> to specify whether the health statistics should be returned as part of <see cref="T:System.Fabric.Health.ClusterHealth" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthStatisticsFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthStatisticsFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="759f0-103">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ClusterHealthStatisticsFilter" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="759f0-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.ClusterHealthStatisticsFilter" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeHealthStatistics">
      <MemberSignature Language="C#" Value="public bool ExcludeHealthStatistics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeHealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthStatisticsFilter.ExcludeHealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeHealthStatistics As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeHealthStatistics : bool with get, set" Usage="System.Fabric.Health.ClusterHealthStatisticsFilter.ExcludeHealthStatistics" />
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
            <span data-ttu-id="759f0-104">Ruft ab oder legt ein Flag fest, der angibt, ob die Integrität Statistiken im Abfrageergebnis aufgenommen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="759f0-104">Gets or sets a flag that indicates whether the health statistics should be included in query result.</span></span>
            </summary>
        <value><span data-ttu-id="759f0-105">Ein Flag, der angibt, ob die Integrität Statistiken im Abfrageergebnis aufgenommen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="759f0-105">A flag that indicates whether the health statistics should be included in query result.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="759f0-106">Wenn ExcludeHealthStatistics, um festgelegt ist <languageKeyword>"true"</languageKeyword>, die Integrität Statistiken werden nicht als Teil des Abfrageergebnisses zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="759f0-106">If ExcludeHealthStatistics is set to <languageKeyword>true</languageKeyword>, the health statistics are not returned as part of the query result.</span></span>
            <span data-ttu-id="759f0-107">Andernfalls enthält das Ergebnis der Abfrage die Cluster Health Statistiken.</span><span class="sxs-lookup"><span data-stu-id="759f0-107">Otherwise, the query result includes the cluster health statistics.</span></span>
            <span data-ttu-id="759f0-108">Die Statistik zeigt die Anzahl der Entitäten im Cluster pro Entitätstyp, mit der Anzahl der für <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="759f0-108">The statistics shows the number of entities in the cluster per entity type, with count for <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            <span data-ttu-id="759f0-109">Standardmäßig <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="759f0-109">Defaults to <languageKeyword>false</languageKeyword>.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeSystemApplicationHealthStatistics">
      <MemberSignature Language="C#" Value="public bool IncludeSystemApplicationHealthStatistics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncludeSystemApplicationHealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthStatisticsFilter.IncludeSystemApplicationHealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludeSystemApplicationHealthStatistics As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncludeSystemApplicationHealthStatistics : bool with get, set" Usage="System.Fabric.Health.ClusterHealthStatisticsFilter.IncludeSystemApplicationHealthStatistics" />
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
            <span data-ttu-id="759f0-110">Ruft ab oder legt ein Flag, das angibt, ob die Integrität Statistiken für das Fabric Angaben: / System-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="759f0-110">Gets or sets a flag that indicates whether the health statistics should include information for the fabric:/System application.</span></span>
            </summary>
        <value><span data-ttu-id="759f0-111">Ein Flag, das angibt, ob die Integrität Statistiken für das Fabric Angaben: / System-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="759f0-111">A flag that indicates whether the health statistics should include information for the fabric:/System application.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="759f0-112">Wenn IncludeSystemApplicationHealthStatistics, um festgelegt ist <languageKeyword>"true"</languageKeyword>, die Integrität Statistiken umfassen, die Entitäten, die für das Fabric gehören: / System-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="759f0-112">If IncludeSystemApplicationHealthStatistics is set to <languageKeyword>true</languageKeyword>, the health statistics include the entities that belong to the fabric:/System application.</span></span>
            <span data-ttu-id="759f0-113">Andernfalls enthält das Abfrageergebnis nur Integritätsstatistiken für Benutzeranwendungen.</span><span class="sxs-lookup"><span data-stu-id="759f0-113">Otherwise, the query result includes health statistics only for user applications.</span></span>
            <span data-ttu-id="759f0-114">Standardmäßig <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="759f0-114">Defaults to <languageKeyword>false</languageKeyword>.</span></span>
            </para>
          <para><span data-ttu-id="759f0-115">IncludeSystemApplicationHealthStatistics anwenden zu können, muss ExcludeHealthStatistics auf festgelegt werden <languageKeyword>"false"</languageKeyword> (Standardwert).</span><span class="sxs-lookup"><span data-stu-id="759f0-115">In order to apply IncludeSystemApplicationHealthStatistics, ExcludeHealthStatistics must be set to <languageKeyword>false</languageKeyword> (default value).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthStatisticsFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterHealthStatisticsFilter.ToString " />
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
            <span data-ttu-id="759f0-116">Gibt eine Zeichenfolgendarstellung des Filters zurück.</span><span class="sxs-lookup"><span data-stu-id="759f0-116">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="759f0-117">Eine Zeichenfolgendarstellung des Filters.</span><span class="sxs-lookup"><span data-stu-id="759f0-117">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>