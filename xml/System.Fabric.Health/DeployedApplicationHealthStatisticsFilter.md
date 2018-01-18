<Type Name="DeployedApplicationHealthStatisticsFilter" FullName="System.Fabric.Health.DeployedApplicationHealthStatisticsFilter">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealthStatisticsFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealthStatisticsFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationHealthStatisticsFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealthStatisticsFilter" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthStatisticsFilter = class" />
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
      <para><span data-ttu-id="40c6c-101">Stellt den Filter für <see cref="T:System.Fabric.Health.HealthStatistics" />.</span><span class="sxs-lookup"><span data-stu-id="40c6c-101">Represents the filter for <see cref="T:System.Fabric.Health.HealthStatistics" />.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="40c6c-102">Der Filter kann verwendet werden, <see cref="T:System.Fabric.Description.DeployedApplicationHealthQueryDescription" /> angeben, ob die Integrität Statistiken sollen, im Rahmen des zurückgegeben werden <see cref="T:System.Fabric.Health.DeployedApplicationHealth" />.</span><span class="sxs-lookup"><span data-stu-id="40c6c-102">The filter can be used in <see cref="T:System.Fabric.Description.DeployedApplicationHealthQueryDescription" /> to specify whether the health statistics should be returned as part of <see cref="T:System.Fabric.Health.DeployedApplicationHealth" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedApplicationHealthStatisticsFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthStatisticsFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="40c6c-103">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.DeployedApplicationHealthStatisticsFilter" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="40c6c-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.DeployedApplicationHealthStatisticsFilter" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeHealthStatistics">
      <MemberSignature Language="C#" Value="public bool ExcludeHealthStatistics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeHealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStatisticsFilter.ExcludeHealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeHealthStatistics As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeHealthStatistics : bool with get, set" Usage="System.Fabric.Health.DeployedApplicationHealthStatisticsFilter.ExcludeHealthStatistics" />
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
            <span data-ttu-id="40c6c-104">Ruft ab oder legt ein Flag fest, der angibt, ob die Integrität Statistiken im Abfrageergebnis aufgenommen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="40c6c-104">Gets or sets a flag that indicates whether the health statistics should be included in query result.</span></span>
            </summary>
        <value><span data-ttu-id="40c6c-105">Ein Flag, der angibt, ob die Integrität Statistiken im Abfrageergebnis aufgenommen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="40c6c-105">A flag that indicates whether the health statistics should be included in query result.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="40c6c-106">Wenn ExcludeHealthStatistics, um festgelegt ist <languageKeyword>"true"</languageKeyword>, die Integrität Statistiken werden nicht als Teil des Abfrageergebnisses zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="40c6c-106">If ExcludeHealthStatistics is set to <languageKeyword>true</languageKeyword>, the health statistics are not returned as part of the query result.</span></span>
            <span data-ttu-id="40c6c-107">Andernfalls enthält das Ergebnis der Abfrage die bereitgestellte Anwendung Integrität Statistiken, die enthält Informationen dazu, wie viele bereitgestellte dienstpakete in sind <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="40c6c-107">Otherwise, the query result includes the deployed application health statistics, which contains information about how many deployed service packages are in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            <span data-ttu-id="40c6c-108">Standardmäßig <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="40c6c-108">Defaults to <languageKeyword>false</languageKeyword>.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthStatisticsFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedApplicationHealthStatisticsFilter.ToString " />
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
            <span data-ttu-id="40c6c-109">Gibt eine Zeichenfolgendarstellung des Filters zurück.</span><span class="sxs-lookup"><span data-stu-id="40c6c-109">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="40c6c-110">Eine Zeichenfolgendarstellung des Filters.</span><span class="sxs-lookup"><span data-stu-id="40c6c-110">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>