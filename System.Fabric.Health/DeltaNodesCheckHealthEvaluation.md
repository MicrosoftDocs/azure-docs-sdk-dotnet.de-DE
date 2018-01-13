<Type Name="DeltaNodesCheckHealthEvaluation" FullName="System.Fabric.Health.DeltaNodesCheckHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class DeltaNodesCheckHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeltaNodesCheckHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeltaNodesCheckHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeltaNodesCheckHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type DeltaNodesCheckHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para>Stellt die integritätsevaluierung für Deltaknoten, mit auswertungen der Clientintegrität für jeden fehlerhaften Knoten, die aktuellen aggregierte Integritätsstatus ausgewirkt haben. Während des Upgrades Cluster zurückgegeben werden kann, wird der aggregierte Integritätszustand des Clusters <see cref="F:System.Fabric.Health.HealthState.Error" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BaselineErrorCount">
      <MemberSignature Language="C#" Value="public long BaselineErrorCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 BaselineErrorCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeltaNodesCheckHealthEvaluation.BaselineErrorCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaselineErrorCount As Long" />
      <MemberSignature Language="F#" Value="member this.BaselineErrorCount : int64" Usage="System.Fabric.Health.DeltaNodesCheckHealthEvaluation.BaselineErrorCount" />
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
          <para>Ruft die Anzahl der Knoten mit der aggregierte Integritätszustand <see cref="F:System.Fabric.Health.HealthState.Error" /> am Anfang des Cluster-Upgrades in den Zustand zu speichern.</para>
        </summary>
        <value>
          <para>Die Anzahl von Knoten mit der aggregierte Integritätszustand <see cref="F:System.Fabric.Health.HealthState.Error" /> am Anfang des Cluster-Upgrades in den Zustand zu speichern.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaselineTotalCount">
      <MemberSignature Language="C#" Value="public long BaselineTotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 BaselineTotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeltaNodesCheckHealthEvaluation.BaselineTotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaselineTotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.BaselineTotalCount : int64" Usage="System.Fabric.Health.DeltaNodesCheckHealthEvaluation.BaselineTotalCount" />
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
          <para>Ruft die Gesamtanzahl der Knoten im Health Store am Anfang des Cluster-Upgrades.</para>
        </summary>
        <value>
          <para>Die Gesamtanzahl der Knoten im Health Store am Anfang des Cluster-Upgrades.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentDeltaUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentDeltaUnhealthyNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentDeltaUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeltaNodesCheckHealthEvaluation.MaxPercentDeltaUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentDeltaUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentDeltaUnhealthyNodes : byte" Usage="System.Fabric.Health.DeltaNodesCheckHealthEvaluation.MaxPercentDeltaUnhealthyNodes" />
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
          <para>Ruft die maximal zulässige Prozentsatz Delta fehlerhafte Knoten aus der <see cref="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" />.</para>
        </summary>
        <value>
          <para>Die maximal zulässige Prozentsatz Delta fehlerhafte Knoten.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeltaNodesCheckHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.DeltaNodesCheckHealthEvaluation.TotalCount" />
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
          <para>Ruft die Gesamtzahl der Knoten im Health Store an.</para>
        </summary>
        <value>
          <para>Die aktuelle Gesamtzahl der Knoten im Health Store.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeltaNodesCheckHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.DeltaNodesCheckHealthEvaluation.UnhealthyEvaluations" />
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
          <para>Ruft die Liste der fehlerhaften auswertungen, die zu der aggregierte Integritätszustand geführt hat. Schließt alle fehlerhaften <see cref="T:System.Fabric.Health.NodeHealthEvaluation" /> , die die zusammengefasste Integrität beeinträchtigt.</para>
        </summary>
        <value>
          <para>Gibt eine Liste von die fehlerhaften auswertungen, die dem aktuellen aggregierte Integritätsstatus geführt hat.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>