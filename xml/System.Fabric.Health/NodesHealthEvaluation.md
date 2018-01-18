<Type Name="NodesHealthEvaluation" FullName="System.Fabric.Health.NodesHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class NodesHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodesHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.NodesHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodesHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type NodesHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para><span data-ttu-id="6e1e2-101">Stellt die integritätsevaluierung für Knoten, die mit auswertungen der Clientintegrität für jeden fehlerhaften Knoten, die aktuellen aggregierte Integritätsstatus ausgewirkt haben.</span><span class="sxs-lookup"><span data-stu-id="6e1e2-101">Represents health evaluation for nodes, containing health evaluations for each unhealthy node that impacted current aggregated health state.</span></span> <span data-ttu-id="6e1e2-102">Zurückgegeben werden kann, bei der Auswertung des gesamtclusterzustands und der aggregierte Integritätszustand ist entweder <see cref="F:System.Fabric.Health.HealthState.Error" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span><span class="sxs-lookup"><span data-stu-id="6e1e2-102">Can be returned when evaluating cluster health and the aggregated health state is either <see cref="F:System.Fabric.Health.HealthState.Error" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MaxPercentUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodesHealthEvaluation.MaxPercentUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyNodes : byte" Usage="System.Fabric.Health.NodesHealthEvaluation.MaxPercentUnhealthyNodes" />
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
          <para><span data-ttu-id="6e1e2-103">Ruft die maximal zulässige Prozentsatz fehlerhafter Knoten aus der <see cref="T:System.Fabric.Health.ClusterHealthPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="6e1e2-103">Gets the maximum allowed percentage of unhealthy nodes from the <see cref="T:System.Fabric.Health.ClusterHealthPolicy" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6e1e2-104">Die maximal zulässige Prozentsatz fehlerhafter Knoten.</span><span class="sxs-lookup"><span data-stu-id="6e1e2-104">The maximum allowed percentage of unhealthy nodes.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodesHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.NodesHealthEvaluation.TotalCount" />
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
          <para><span data-ttu-id="6e1e2-105">Ruft die Gesamtanzahl der Knoten im Health Store an.</span><span class="sxs-lookup"><span data-stu-id="6e1e2-105">Gets the total number of nodes in the health store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6e1e2-106">Die Gesamtanzahl der Knoten im Health Store.</span><span class="sxs-lookup"><span data-stu-id="6e1e2-106">The total number of nodes in the health store.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodesHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.NodesHealthEvaluation.UnhealthyEvaluations" />
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
          <para><span data-ttu-id="6e1e2-107">Ruft die Liste der fehlerhaften auswertungen, die zu der aggregierte Integritätszustand geführt hat.</span><span class="sxs-lookup"><span data-stu-id="6e1e2-107">Gets the list of unhealthy evaluations that led to the aggregated health state.</span></span> <span data-ttu-id="6e1e2-108">Schließt alle fehlerhaften <see cref="T:System.Fabric.Health.NodeHealthEvaluation" /> , die die zusammengefasste Integrität beeinträchtigt.</span><span class="sxs-lookup"><span data-stu-id="6e1e2-108">Includes all the unhealthy <see cref="T:System.Fabric.Health.NodeHealthEvaluation" /> that impacted the aggregated health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6e1e2-109">Die fehlerhaften auswertungen, die dem aktuellen aggregierte Integritätsstatus geführt hat.</span><span class="sxs-lookup"><span data-stu-id="6e1e2-109">The unhealthy evaluations that led to current aggregated health state.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>