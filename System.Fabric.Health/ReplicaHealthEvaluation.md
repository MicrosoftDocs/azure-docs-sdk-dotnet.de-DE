<Type Name="ReplicaHealthEvaluation" FullName="System.Fabric.Health.ReplicaHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class ReplicaHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicaHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ReplicaHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicaHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type ReplicaHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para>Stellt die integritätsauswertung für ein Replikat mit den Informationen zu den Daten und der Algorithmus zum Health Store integritätsevaluierung aktiviert werden soll. Die Auswertung wird nur zurückgegeben, wenn der aggregierte Integritätszustand entweder ist <see cref="F:System.Fabric.Health.HealthState.Error" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthEvaluation.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Health.ReplicaHealthEvaluation.PartitionId" />
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
          <para>Ruft die Partitions-ID.</para>
        </summary>
        <value>
          <para>Die Partitions-ID.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaOrInstanceId">
      <MemberSignature Language="C#" Value="public long ReplicaOrInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaOrInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthEvaluation.ReplicaOrInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaOrInstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaOrInstanceId : int64" Usage="System.Fabric.Health.ReplicaHealthEvaluation.ReplicaOrInstanceId" />
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
          <para>Ruft ab, der einem zustandsbehafteten Dienst dienstreplikats oder die ID der statusfreien Dienstinstanz-ID</para>
        </summary>
        <value>
          <para>Das Replikat oder eine Instanz-ID an.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.ReplicaHealthEvaluation.UnhealthyEvaluations" />
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
          <para>Ruft die fehlerhaften auswertungen, die mit dem aktuellen Status der zusammengefassten Integrität des Replikats geführt hat. Die Typen von fehlerhaften auswertungen möglich <see cref="T:System.Fabric.Health.EventHealthEvaluation" />.</para>
        </summary>
        <value>
          <para>Die fehlerhaften auswertungen, die dem aktuellen aggregierte Integritätsstatus geführt hat.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>