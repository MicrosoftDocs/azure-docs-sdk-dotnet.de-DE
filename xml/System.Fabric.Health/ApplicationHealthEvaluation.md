<Type Name="ApplicationHealthEvaluation" FullName="System.Fabric.Health.ApplicationHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type ApplicationHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para><span data-ttu-id="b1b62-101">Stellt die integritätsauswertung für eine Anwendung, die mit Informationen zu den Daten und der Algorithmus zum Health Store integritätsevaluierung aktiviert werden soll.</span><span class="sxs-lookup"><span data-stu-id="b1b62-101">Represents health evaluation for an application, containing information about the data and the algorithm used by health store to evaluate health.</span></span> </para>
    </summary>
    <remarks><span data-ttu-id="b1b62-102">Die Auswertung wird nur zurückgegeben, wenn der aggregierte Integritätszustand entweder ist <see cref="F:System.Fabric.Health.HealthState.Error" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span><span class="sxs-lookup"><span data-stu-id="b1b62-102">The evaluation is returned only when the aggregated health state is either <see cref="F:System.Fabric.Health.HealthState.Error" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthEvaluation.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.ApplicationHealthEvaluation.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b1b62-103">Ruft den Namen der Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="b1b62-103">Gets the application name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b1b62-104">Die <see cref="T:System.Uri" /> , die den Namen der Anwendung darstellt.</span><span class="sxs-lookup"><span data-stu-id="b1b62-104">The <see cref="T:System.Uri" /> representing the application name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.ApplicationHealthEvaluation.UnhealthyEvaluations" />
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
          <para><span data-ttu-id="b1b62-105">Ruft die fehlerhaften auswertungen, die mit dem aktuellen Status der zusammengefassten Integrität der Anwendung geführt hat.</span><span class="sxs-lookup"><span data-stu-id="b1b62-105">Gets the unhealthy evaluations that led to the current aggregated health state of the application.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="b1b62-106">Die Liste der <see cref="T:System.Fabric.Health.HealthEvaluation" /> , die die fehlerhaften auswertungen, die dem aktuellen aggregierte Integritätsstatus geführt haben darstellt.</span><span class="sxs-lookup"><span data-stu-id="b1b62-106">The list of <see cref="T:System.Fabric.Health.HealthEvaluation" /> representing the unhealthy evaluations that led to current aggregated health state.</span></span></para>
        </value>
        <remarks><span data-ttu-id="b1b62-107">Die Typen von fehlerhaften auswertungen kann <see cref="T:System.Fabric.Health.DeployedApplicationsHealthEvaluation" />, <see cref="T:System.Fabric.Health.ServicesHealthEvaluation" /> oder <see cref="T:System.Fabric.Health.EventHealthEvaluation" />.</span><span class="sxs-lookup"><span data-stu-id="b1b62-107">The types of the unhealthy evaluations can be <see cref="T:System.Fabric.Health.DeployedApplicationsHealthEvaluation" />, <see cref="T:System.Fabric.Health.ServicesHealthEvaluation" /> or <see cref="T:System.Fabric.Health.EventHealthEvaluation" />.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>