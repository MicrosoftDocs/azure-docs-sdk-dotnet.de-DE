<Type Name="SystemApplicationHealthEvaluation" FullName="System.Fabric.Health.SystemApplicationHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class SystemApplicationHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SystemApplicationHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.SystemApplicationHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SystemApplicationHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type SystemApplicationHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para><span data-ttu-id="f99d7-101">Stellt die integritätsauswertung für das Fabric: / System-Anwendung, die Informationen zu den Daten und den Algorithmus vom Health Store auf integritätsevaluierung aktiviert werden soll.</span><span class="sxs-lookup"><span data-stu-id="f99d7-101">Represents health evaluation for the fabric:/System application, containing information about the data and the algorithm used by health store to evaluate health.</span></span> <span data-ttu-id="f99d7-102">Die Auswertung wird nur zurückgegeben, wenn der aggregierte Integritätszustand des Clusters entweder ist <see cref="F:System.Fabric.Health.HealthState.Error" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span><span class="sxs-lookup"><span data-stu-id="f99d7-102">The evaluation is returned only when the aggregated health state of the cluster is either <see cref="F:System.Fabric.Health.HealthState.Error" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.SystemApplicationHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.SystemApplicationHealthEvaluation.UnhealthyEvaluations" />
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
          <para><span data-ttu-id="f99d7-103">Ruft die fehlerhaften auswertungen, die mit dem aktuellen Status der zusammengefassten Integrität der systemanwendung geführt hat.</span><span class="sxs-lookup"><span data-stu-id="f99d7-103">Gets the unhealthy evaluations that led to the current aggregated health state of the system application.</span></span> <span data-ttu-id="f99d7-104">Die Typen von fehlerhaften auswertungen kann <see cref="T:System.Fabric.Health.DeployedApplicationsHealthEvaluation" />, <see cref="T:System.Fabric.Health.ServicesHealthEvaluation" /> oder <see cref="T:System.Fabric.Health.EventHealthEvaluation" />.</span><span class="sxs-lookup"><span data-stu-id="f99d7-104">The types of the unhealthy evaluations can be <see cref="T:System.Fabric.Health.DeployedApplicationsHealthEvaluation" />, <see cref="T:System.Fabric.Health.ServicesHealthEvaluation" /> or <see cref="T:System.Fabric.Health.EventHealthEvaluation" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f99d7-105">Die fehlerhaften auswertungen, die dem aktuellen aggregierte Integritätsstatus geführt hat.</span><span class="sxs-lookup"><span data-stu-id="f99d7-105">The unhealthy evaluations that led to current aggregated health state.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>