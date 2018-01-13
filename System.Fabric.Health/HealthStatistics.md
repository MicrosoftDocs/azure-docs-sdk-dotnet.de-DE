<Type Name="HealthStatistics" FullName="System.Fabric.Health.HealthStatistics">
  <TypeSignature Language="C#" Value="public sealed class HealthStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HealthStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthStatistics" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HealthStatistics" />
  <TypeSignature Language="F#" Value="type HealthStatistics = class" />
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
      <para>
            Stellt die Integrität von Statistiken für eine Entität dar.
            Es ist als Teil des Health Abfrageergebnisse zurückgegeben, wenn die Abfrage Beschreibungen für die Statistiken umfassen konfiguriert sind.
            Die Statistiken umfassen Health Status Anzahlen für alle untergeordneten Elemente der aktuellen Entität.
            Beispielsweise enthalten die Integrität Statistiken für Cluster, Integrität Zustand Anzahl für Knoten, Anwendungen, Dienste, Partitionen, Replikate, bereitgestellten Anwendungen und Pakete bereitgestellten Dienst.
            Für Partition enthalten die Integrität Statistiken die Integrität-Anzahl für Replikate.
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthStateCountList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.EntityKindHealthStateCount&gt; HealthStateCountList { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.EntityKindHealthStateCount&gt; HealthStateCountList" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthStatistics.HealthStateCountList" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStateCountList As IList(Of EntityKindHealthStateCount)" />
      <MemberSignature Language="F#" Value="member this.HealthStateCountList : System.Collections.Generic.IList&lt;System.Fabric.Health.EntityKindHealthStateCount&gt;" Usage="System.Fabric.Health.HealthStatistics.HealthStateCountList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.EntityKindHealthStateCount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine Liste der <see cref="T:System.Fabric.Health.HealthStateCount" /> Informationen für andere Entitätsarten.
            </summary>
        <value>Eine Liste mit <see cref="T:System.Fabric.Health.HealthStateCount" /> Informationen für andere Entitätsarten.</value>
        <remarks>
          <para>
            Die Liste der nachverfolgt werden wie viele untergeordnete Elemente der abgefragten Entität in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStatistics.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="healthStatistics.ToString " />
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
            Gibt eine Zeichenfolgendarstellung der Integrität Zustand Anzahl zurück.
            </summary>
        <returns>Eine Zeichenfolgendarstellung der Anzahl der Integrität-Zustand.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>