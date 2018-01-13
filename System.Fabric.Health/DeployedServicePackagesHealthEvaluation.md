<Type Name="DeployedServicePackagesHealthEvaluation" FullName="System.Fabric.Health.DeployedServicePackagesHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackagesHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackagesHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackagesHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackagesHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type DeployedServicePackagesHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para><span data-ttu-id="2aa90-101">Stellt die integritätsauswertung für die bereitgestellten dienstpakete mit auswertungen der Clientintegrität für jede fehlerhaftes bereitgestelltes Dienstpaket, das aktuellen aggregierte Integritätsstatus ausgewirkt haben.</span><span class="sxs-lookup"><span data-stu-id="2aa90-101">Represents health evaluation for deployed service packages, containing health evaluations for each unhealthy deployed service package that impacted current aggregated health state.</span></span> <span data-ttu-id="2aa90-102">Zurückgegeben werden kann, bei der Bewertung der Integrität der bereitgestellten Anwendung und der aggregierte Integritätszustand ist entweder <see cref="F:System.Fabric.Health.HealthState.Error" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span><span class="sxs-lookup"><span data-stu-id="2aa90-102">Can be returned when evaluating deployed application health and the aggregated health state is either <see cref="F:System.Fabric.Health.HealthState.Error" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackagesHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.DeployedServicePackagesHealthEvaluation.TotalCount" />
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
          <para><span data-ttu-id="2aa90-103">Ruft die Gesamtanzahl der bereitgestellten Anwendung bereitgestellten dienstpakete im Health Store an.</span><span class="sxs-lookup"><span data-stu-id="2aa90-103">Gets the total number of deployed service packages of the deployed application in the health store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2aa90-104">Ein <see cref="T:System.Int64" /> dienstpakete der bereitgestellten Anwendung im Health Store bereitgestellt, die die Gesamtzahl der darstellt.</span><span class="sxs-lookup"><span data-stu-id="2aa90-104">An <see cref="T:System.Int64" /> representing the total count of deployed service packages of the deployed application in the health store.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackagesHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.DeployedServicePackagesHealthEvaluation.UnhealthyEvaluations" />
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
          <para><span data-ttu-id="2aa90-105">Ruft die Liste der fehlerhaften auswertungen, die zu der aggregierte Integritätszustand geführt hat.</span><span class="sxs-lookup"><span data-stu-id="2aa90-105">Gets the list of unhealthy evaluations that led to the aggregated health state.</span></span> <span data-ttu-id="2aa90-106">Schließt alle fehlerhaften <see cref="T:System.Fabric.Health.DeployedServicePackageHealthEvaluation" /> , die die zusammengefasste Integrität beeinträchtigt.</span><span class="sxs-lookup"><span data-stu-id="2aa90-106">Includes all the unhealthy <see cref="T:System.Fabric.Health.DeployedServicePackageHealthEvaluation" /> that impacted the aggregated health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2aa90-107">Die fehlerhaften auswertungen, die dem aktuellen aggregierte Integritätsstatus geführt hat.</span><span class="sxs-lookup"><span data-stu-id="2aa90-107">The unhealthy evaluations that led to current aggregated health state.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>