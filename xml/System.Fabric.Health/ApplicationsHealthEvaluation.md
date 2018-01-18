<Type Name="ApplicationsHealthEvaluation" FullName="System.Fabric.Health.ApplicationsHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class ApplicationsHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationsHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationsHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationsHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type ApplicationsHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para><span data-ttu-id="24f6d-101">Stellt die integritätsevaluierung für Anwendungen, die mit auswertungen der Clientintegrität für jede fehlerhafte Anwendung, die aktuellen aggregierte Integritätsstatus ausgewirkt haben.</span><span class="sxs-lookup"><span data-stu-id="24f6d-101">Represents health evaluation for applications, containing health evaluations for each unhealthy application that impacted current aggregated health state.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="24f6d-102">Die Auswertung Anwendungen zurückgegeben werden kann, während integritätsevaluierung für Cluster, bei der aggregierte Integritätszustand des Clusters entweder <see cref="F:System.Fabric.Health.HealthState.Error" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span><span class="sxs-lookup"><span data-stu-id="24f6d-102">The applications evaluation can be returned during cluster health evaluation, when the aggregated health state of the cluster is either <see cref="F:System.Fabric.Health.HealthState.Error" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="MaxPercentUnhealthyApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyApplications { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationsHealthEvaluation.MaxPercentUnhealthyApplications" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentUnhealthyApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyApplications : byte" Usage="System.Fabric.Health.ApplicationsHealthEvaluation.MaxPercentUnhealthyApplications" />
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
          <para><span data-ttu-id="24f6d-103">Ruft die maximal zulässige Prozentsatz fehlerhafter Anwendungen aus dem <see cref="T:System.Fabric.Health.ClusterHealthPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="24f6d-103">Gets the maximum allowed percentage of unhealthy applications from the <see cref="T:System.Fabric.Health.ClusterHealthPolicy" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="24f6d-104">Die maximal zulässige Prozentsatz fehlerhafter Anwendungen.</span><span class="sxs-lookup"><span data-stu-id="24f6d-104">The maximum allowed percentage of unhealthy applications.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationsHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.ApplicationsHealthEvaluation.TotalCount" />
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
          <para><span data-ttu-id="24f6d-105">Ruft die Gesamtzahl der Anwendungen im Health Store an.</span><span class="sxs-lookup"><span data-stu-id="24f6d-105">Gets the total number of applications in the health store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="24f6d-106">Eine <see cref="T:System.Int64" /> , die die Gesamtzahl der Anwendungen im Health Store darstellt.</span><span class="sxs-lookup"><span data-stu-id="24f6d-106">An <see cref="T:System.Int64" /> representing the total count of applications in the health store.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationsHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.ApplicationsHealthEvaluation.UnhealthyEvaluations" />
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
          <para><span data-ttu-id="24f6d-107">Ruft die Liste der fehlerhaften auswertungen, die zu der aggregierte Integritätszustand geführt hat.</span><span class="sxs-lookup"><span data-stu-id="24f6d-107">Gets the list of unhealthy evaluations that led to the aggregated health state.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="24f6d-108">Eine Liste der <see cref="T:System.Fabric.Health.HealthEvaluation" /> , die die fehlerhaften auswertungen, die dem aktuellen aggregierte Integritätsstatus geführt haben darstellt.</span><span class="sxs-lookup"><span data-stu-id="24f6d-108">A list of <see cref="T:System.Fabric.Health.HealthEvaluation" /> representing the unhealthy evaluations that led to current aggregated health state.</span></span></para>
        </value>
        <remarks>
            <span data-ttu-id="24f6d-109">Schließt alle fehlerhaften <see cref="T:System.Fabric.Health.ApplicationHealthEvaluation" /> , die die zusammengefasste Integrität beeinträchtigt.</span><span class="sxs-lookup"><span data-stu-id="24f6d-109">Includes all the unhealthy <see cref="T:System.Fabric.Health.ApplicationHealthEvaluation" /> that impacted the aggregated health.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>