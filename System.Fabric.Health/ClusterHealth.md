<Type Name="ClusterHealth" FullName="System.Fabric.Health.ClusterHealth">
  <TypeSignature Language="C#" Value="public sealed class ClusterHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ClusterHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type ClusterHealth = class&#xA;    inherit EntityHealth" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealth</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Die Integrität des Clusters dar, der vom <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />.
            Enthält den Integritätsstatus des Clusters aggregiert, die anwendungsintegritätszustände, die knotenintegritätszustände als auch integritätsereignisse, integritätsauswertung und Integrität Statistiken.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthState&gt; ApplicationHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ApplicationHealthState&gt; ApplicationHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealth.ApplicationHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationHealthStates As IList(Of ApplicationHealthState)" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthState&gt;" Usage="System.Fabric.Health.ClusterHealth.ApplicationHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Clusterknoten anwendungsintegritätszustände als gefunden wurde im Health Store.</para>
        </summary>
        <value>
          <para>Die Clusteranwendungen wie im Health Store.</para>
        </value>
        <remarks>To be added.</remarks>
        <para>Alle Anwendungen werden ausgewertet, um zu bestimmen, den Clusterzustand aggregiert.</para>
        <para>Nur Anwendungen, die berücksichtigen die <see cref="P:System.Fabric.Description.ClusterHealthQueryDescription.ApplicationsFilter" /> (falls angegeben) werden zurückgegeben. Wenn der Filter nicht angegeben ist, werden alle Anwendungen zurückgegeben.</para>
      </Docs>
    </Member>
    <Member MemberName="HealthStatistics">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStatistics HealthStatistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthStatistics HealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealth.HealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStatistics As HealthStatistics" />
      <MemberSignature Language="F#" Value="member this.HealthStatistics : System.Fabric.Health.HealthStatistics" Usage="System.Fabric.Health.ClusterHealth.HealthStatistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Statistiken der Cluster-Integrität, die enthalten Informationen darüber, wie viele Cluster Entitäten in werden <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.
            </summary>
        <value>Die Statistiken für den Cluster-Integrität.</value>
        <remarks>
          <para>
            Die Cluster Health Statistiken enthalten Informationen darüber, wie viele Cluster Entitäten in werden <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.
            Es kann null oder leer sein, wenn die Abfrage, die zurückgibt die <see cref="T:System.Fabric.Health.ClusterHealth" /> angegebenen <see cref="T:System.Fabric.Health.ClusterHealthStatisticsFilter" /> Health Statistiken ausschließen.
            Standardmäßig gibt die Integrität Abfrage Statistiken, die keine Statistiken über die systemanwendung enthalten: die Anzahl der Anwendungen, Dienste, Partitionen, die die Replikate bereitgestellten Anwendungen und bereitgestellten dienstpakete nur benutzerentitäten enthalten.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.NodeHealthState&gt; NodeHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.NodeHealthState&gt; NodeHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealth.NodeHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeHealthStates As IList(Of NodeHealthState)" />
      <MemberSignature Language="F#" Value="member this.NodeHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.NodeHealthState&gt;" Usage="System.Fabric.Health.ClusterHealth.NodeHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.NodeHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Clusterknoten knotenintegritätszustände als gefunden wurde im Health Store.</para>
        </summary>
        <value>
          <para>Die Clusterknoten im Health Store als gefunden.</para>
        </value>
        <remarks>To be added.</remarks>
        <para>Alle Knoten werden ausgewertet, um zu bestimmen, den Clusterzustand aggregiert.</para>
        <para>Nur Knoten, deren berücksichtigen die <see cref="P:System.Fabric.Description.ClusterHealthQueryDescription.NodesFilter" /> (falls angegeben) werden zurückgegeben. Wenn der Filter nicht angegeben ist, werden alle Knoten zurückgegeben.</para>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterHealth.ToString " />
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
            Ruft eine Zeichenfolgendarstellung der <see cref="T:System.Fabric.Health.ClusterHealth" />.
            </summary>
        <returns>Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Health.ClusterHealth" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>