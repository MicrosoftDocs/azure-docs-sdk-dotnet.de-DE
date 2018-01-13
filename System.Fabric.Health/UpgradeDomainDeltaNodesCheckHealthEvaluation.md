<Type Name="UpgradeDomainDeltaNodesCheckHealthEvaluation" FullName="System.Fabric.Health.UpgradeDomainDeltaNodesCheckHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class UpgradeDomainDeltaNodesCheckHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UpgradeDomainDeltaNodesCheckHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.UpgradeDomainDeltaNodesCheckHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UpgradeDomainDeltaNodesCheckHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type UpgradeDomainDeltaNodesCheckHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para>Stellt die integritätsauswertung für das Delta fehlerhafter Clusterknoten in einer upgradedomäne mit auswertungen der Clientintegrität für jeden fehlerhaften Knoten, die aktuellen aggregierte Integritätsstatus ausgewirkt haben.
            Zurückgegeben werden kann, während des Upgrades der Cluster beim Cluster aggregierte Integritätsstatus ist <see cref="F:System.Fabric.Health.HealthState.Error" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BaselineErrorCount">
      <MemberSignature Language="C#" Value="public long BaselineErrorCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 BaselineErrorCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainDeltaNodesCheckHealthEvaluation.BaselineErrorCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaselineErrorCount As Long" />
      <MemberSignature Language="F#" Value="member this.BaselineErrorCount : int64" Usage="System.Fabric.Health.UpgradeDomainDeltaNodesCheckHealthEvaluation.BaselineErrorCount" />
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
          <para>Ruft die Anzahl der Knoten in upgradedomäne mit der aggregierte Integritätszustand <see cref="F:System.Fabric.Health.HealthState.Error" /> am Anfang des Cluster-Upgrades in den Zustand zu speichern.</para>
        </summary>
        <value>
          <para>Die Anzahl der Knoten in upgradedomäne mit der aggregierte Integritätszustand <see cref="F:System.Fabric.Health.HealthState.Error" /> am Anfang des Cluster-Upgrades in den Zustand zu speichern.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaselineTotalCount">
      <MemberSignature Language="C#" Value="public long BaselineTotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 BaselineTotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainDeltaNodesCheckHealthEvaluation.BaselineTotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaselineTotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.BaselineTotalCount : int64" Usage="System.Fabric.Health.UpgradeDomainDeltaNodesCheckHealthEvaluation.BaselineTotalCount" />
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
          <para>Ruft die Gesamtanzahl der Knoten in upgradedomäne im Health Store am Anfang des Cluster-Upgrades.</para>
        </summary>
        <value>
          <para>T He-Gesamtanzahl der Knoten in upgradedomäne in den Zustand gespeichert am Anfang des Cluster-Upgrades.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUpgradeDomainDeltaUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentUpgradeDomainDeltaUnhealthyNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainDeltaNodesCheckHealthEvaluation.MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentUpgradeDomainDeltaUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUpgradeDomainDeltaUnhealthyNodes : byte" Usage="System.Fabric.Health.UpgradeDomainDeltaNodesCheckHealthEvaluation.MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
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
          <para>Ruft die maximal zulässige Prozentsatz der upgradedomäne Delta fehlerhafte Knoten aus der <see cref="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" />.</para>
        </summary>
        <value>
          <para>Die maximal zulässige Prozentsatz der upgradedomäne Delta fehlerhafte Knoten.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainDeltaNodesCheckHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.UpgradeDomainDeltaNodesCheckHealthEvaluation.TotalCount" />
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
          <para>Ruft die aktuelle Gesamtanzahl von Knoten in upgradedomäne im Health Store ab.</para>
        </summary>
        <value>
          <para>Die aktuelle Gesamtzahl der Knoten in upgradedomäne im Health Store.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainDeltaNodesCheckHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.UpgradeDomainDeltaNodesCheckHealthEvaluation.UnhealthyEvaluations" />
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
          <para>Die fehlerhaften auswertungen, die dem aktuellen aggregierte Integritätsstatus geführt hat.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainName">
      <MemberSignature Language="C#" Value="public string UpgradeDomainName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeDomainName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainDeltaNodesCheckHealthEvaluation.UpgradeDomainName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomainName As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainName : string" Usage="System.Fabric.Health.UpgradeDomainDeltaNodesCheckHealthEvaluation.UpgradeDomainName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Namen der upgradedomäne, auf dem Knoten Integrität derzeit ausgewertet wird.</para>
        </summary>
        <value>
          <para>Der Name der upgradedomäne.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>