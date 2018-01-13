<Type Name="ReplicasHealthEvaluation" FullName="System.Fabric.Health.ReplicasHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class ReplicasHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicasHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ReplicasHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicasHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type ReplicasHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthEvaluation</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt die integritätsauswertung für Replikate, die mit auswertungen der Clientintegrität für jedes "fehlerhaft" Replikat, die aktuellen aggregierte Integritätsstatus ausgewirkt haben.
            Zurückgegeben werden kann, wenn die Auswertung von partitionsintegrität und der aggregierte Integritätszustand entweder ist <see cref="F:System.Fabric.Health.HealthState.Error" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MaxPercentUnhealthyReplicasPerPartition">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyReplicasPerPartition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyReplicasPerPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicasHealthEvaluation.MaxPercentUnhealthyReplicasPerPartition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentUnhealthyReplicasPerPartition As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyReplicasPerPartition : byte" Usage="System.Fabric.Health.ReplicasHealthEvaluation.MaxPercentUnhealthyReplicasPerPartition" />
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
          <para>Ruft die maximal zulässige Prozentsatz fehlerhafter Replikate pro Partition aus der <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />.</para>
        </summary>
        <value>
          <para>Die maximal zulässige Prozentsatz fehlerhafter Replikate pro Partition.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicasHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.ReplicasHealthEvaluation.TotalCount" />
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
          <para>Ruft die Gesamtanzahl der Replikate in der Partition aus dem Health Store.</para>
        </summary>
        <value>
          <para>Die Gesamtanzahl der Replikate in der Partition.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicasHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.ReplicasHealthEvaluation.UnhealthyEvaluations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Liste der fehlerhaften auswertungen, die zu der aggregierte Integritätszustand geführt hat.
            Schließt alle fehlerhaften <see cref="T:System.Fabric.Health.ReplicaHealthEvaluation" /> , die die zusammengefasste Integrität beeinträchtigt.</para>
        </summary>
        <value>
          <para>Die fehlerhaften auswertungen, die dem aktuellen aggregierte Integritätsstatus geführt hat.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>