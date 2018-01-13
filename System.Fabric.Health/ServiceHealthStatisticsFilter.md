<Type Name="ServiceHealthStatisticsFilter" FullName="System.Fabric.Health.ServiceHealthStatisticsFilter">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealthStatisticsFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealthStatisticsFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealthStatisticsFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealthStatisticsFilter" />
  <TypeSignature Language="F#" Value="type ServiceHealthStatisticsFilter = class" />
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
    <remarks>Der Filter kann verwendet werden, <see cref="T:System.Fabric.Description.ServiceHealthQueryDescription" /> angeben, ob die Integrität Statistiken sollen, im Rahmen des zurückgegeben werden <see cref="T:System.Fabric.Health.ServiceHealth" />.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceHealthStatisticsFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStatisticsFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ServiceHealthStatisticsFilter" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeHealthStatistics">
      <MemberSignature Language="C#" Value="public bool ExcludeHealthStatistics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeHealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStatisticsFilter.ExcludeHealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeHealthStatistics As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeHealthStatistics : bool with get, set" Usage="System.Fabric.Health.ServiceHealthStatisticsFilter.ExcludeHealthStatistics" />
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
            Andernfalls wird das Abfrageergebnis umfasst die Dienst-Integrität-Statistiken, die enthält Informationen über wie viele Partitionen und Replikate befinden sich im <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.
            Standardmäßig <languageKeyword>"false"</languageKeyword>.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStatisticsFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceHealthStatisticsFilter.ToString " />
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