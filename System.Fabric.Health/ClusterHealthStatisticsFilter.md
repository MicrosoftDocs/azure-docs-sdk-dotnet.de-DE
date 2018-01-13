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
      <para>Stellt den Filter für <see cref="T:System.Fabric.Health.HealthStatistics" />.</para>
    </summary>
    <remarks>Der Filter kann verwendet werden, <see cref="T:System.Fabric.Description.ClusterHealthQueryDescription" /> angeben, ob die Integrität Statistiken sollen, im Rahmen des zurückgegeben werden <see cref="T:System.Fabric.Health.ClusterHealth" />.</remarks>
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
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ClusterHealthStatisticsFilter" />-Klasse.</para>
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
            Ruft ab oder legt ein Flag fest, der angibt, ob die Integrität Statistiken im Abfrageergebnis aufgenommen werden sollen.
            </summary>
        <value>Ein Flag, der angibt, ob die Integrität Statistiken im Abfrageergebnis aufgenommen werden sollen.</value>
        <remarks>
          <para>
            Wenn ExcludeHealthStatistics, um festgelegt ist <languageKeyword>"true"</languageKeyword>, die Integrität Statistiken werden nicht als Teil des Abfrageergebnisses zurückgegeben.
            Andernfalls enthält das Ergebnis der Abfrage die Cluster Health Statistiken.
            Die Statistik zeigt die Anzahl der Entitäten im Cluster pro Entitätstyp, mit der Anzahl der für <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.
            Standardmäßig <languageKeyword>"false"</languageKeyword>.
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
            Ruft ab oder legt ein Flag, das angibt, ob die Integrität Statistiken für das Fabric Angaben: / System-Anwendung.
            </summary>
        <value>Ein Flag, das angibt, ob die Integrität Statistiken für das Fabric Angaben: / System-Anwendung.</value>
        <remarks>
          <para>
            Wenn IncludeSystemApplicationHealthStatistics, um festgelegt ist <languageKeyword>"true"</languageKeyword>, die Integrität Statistiken umfassen, die Entitäten, die für das Fabric gehören: / System-Anwendung.
            Andernfalls enthält das Abfrageergebnis nur Integritätsstatistiken für Benutzeranwendungen.
            Standardmäßig <languageKeyword>"false"</languageKeyword>.
            </para>
          <para>IncludeSystemApplicationHealthStatistics anwenden zu können, muss ExcludeHealthStatistics auf festgelegt werden <languageKeyword>"false"</languageKeyword> (Standardwert).</para>
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
            Gibt eine Zeichenfolgendarstellung des Filters zurück.
            </summary>
        <returns>Eine Zeichenfolgendarstellung des Filters.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>