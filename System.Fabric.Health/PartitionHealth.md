<Type Name="PartitionHealth" FullName="System.Fabric.Health.PartitionHealth">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type PartitionHealth = class&#xA;    inherit EntityHealth" />
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
      <para>Integrität einer Partition wird beschrieben, wie vom <see cref="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Fabric.Description.PartitionHealthQueryDescription)" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthStatistics">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStatistics HealthStatistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthStatistics HealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealth.HealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStatistics As HealthStatistics" />
      <MemberSignature Language="F#" Value="member this.HealthStatistics : System.Fabric.Health.HealthStatistics" Usage="System.Fabric.Health.PartitionHealth.HealthStatistics" />
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
            Ruft die Health partitionsstatistiken, die enthalten Informationen darüber, wie viele Replikate in werden <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.
            </summary>
        <value>Die Integrität partitionsstatistik.</value>
        <remarks>
          <para>
            Der Health partitionsstatistik enthalten Informationen über wie viele Replikate befinden sich im <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.
            Es kann null oder leer sein, wenn die Abfrage, die zurückgibt die <see cref="T:System.Fabric.Health.PartitionHealth" /> angegebenen <see cref="T:System.Fabric.Health.PartitionHealthStatisticsFilter" /> Health Statistiken ausschließen.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealth.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Health.PartitionHealth.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Partitions-ID, die die Partition eindeutig identifiziert.</para>
        </summary>
        <value>
          <para>Die Partitions-ID.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthState&gt; ReplicaHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ReplicaHealthState&gt; ReplicaHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealth.ReplicaHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaHealthStates As IList(Of ReplicaHealthState)" />
      <MemberSignature Language="F#" Value="member this.ReplicaHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthState&gt;" Usage="System.Fabric.Health.PartitionHealth.ReplicaHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft das Replikat Integritätsstatus für die aktuelle Partition als gefunden wurde im Health Store.</para>
        </summary>
        <value>
          <para>Die Replikate der aktuellen Partition als gefunden wurde im Health Store.</para>
        </value>
        <remarks>To be added.</remarks>
        <para>Alle Replikate werden ausgewertet, um die aggregiert partitionsintegrität zu ermitteln.</para>
        <para>Nur Replikate, die berücksichtigen die <see cref="P:System.Fabric.Description.PartitionHealthQueryDescription.ReplicasFilter" /> (falls angegeben) werden zurückgegeben. Wenn der Filter nicht angegeben ist, werden alle Replikate zurückgegeben.</para>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionHealth.ToString " />
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
            Ruft eine Zeichenfolgendarstellung der <see cref="T:System.Fabric.Health.PartitionHealth" />.
            </summary>
        <returns>Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Health.PartitionHealth" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>