<Type Name="ApplicationTypeApplicationsHealthEvaluation" FullName="System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class ApplicationTypeApplicationsHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationTypeApplicationsHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationTypeApplicationsHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type ApplicationTypeApplicationsHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para>
            <span data-ttu-id="542fe-101">Stellt die integritätsevaluierung für Anwendungen eines Anwendungstyps dar.</span><span class="sxs-lookup"><span data-stu-id="542fe-101">Represents health evaluation for applications of an application type.</span></span>
            </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="542fe-102">Anwendungen vom Typ "Application" Auswertung zurückgegeben werden kann, Rückkehr Cluster integritätsauswertung "fehlerhaft" aggregierte Integritätsstatus, entweder <see cref="F:System.Fabric.Health.HealthState.Error" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span><span class="sxs-lookup"><span data-stu-id="542fe-102">The application type applications evaluation can be returned when cluster health evaluation returns unhealthy aggregated health state, either <see cref="F:System.Fabric.Health.HealthState.Error" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span>
            <span data-ttu-id="542fe-103">Es enthält die auswertungen der Clientintegrität für jede Anwendung "fehlerhaft" des Anwendungstyps enthalten, die aktuellen aggregierte Integritätsstatus ausgewirkt haben.</span><span class="sxs-lookup"><span data-stu-id="542fe-103">It contains health evaluations for each unhealthy application of the included application type that impacted current aggregated health state.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation.ApplicationTypeName" />
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
          <para>
            <span data-ttu-id="542fe-104">Ruft den Typnamen der Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="542fe-104">Gets the application type name.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="542fe-105">Der Name des Anwendungstyps.</span><span class="sxs-lookup"><span data-stu-id="542fe-105">The application type name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyApplications { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation.MaxPercentUnhealthyApplications" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentUnhealthyApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyApplications : byte" Usage="System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation.MaxPercentUnhealthyApplications" />
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
          <para>
            <span data-ttu-id="542fe-106">Ruft die maximal zulässige Prozentsatz fehlerhafter Anwendungen für den Anwendungstyp, angegeben als Eintrag in <see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />.</span><span class="sxs-lookup"><span data-stu-id="542fe-106">Gets the maximum allowed percentage of unhealthy applications for the application type, specified as an entry in <see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="542fe-107">Die maximal zulässige Prozentsatz fehlerhafter Anwendungen für den Anwendungstyp.</span><span class="sxs-lookup"><span data-stu-id="542fe-107">The maximum allowed percentage of unhealthy applications for the application type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation.TotalCount" />
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
          <para>
            <span data-ttu-id="542fe-108">Ruft die Gesamtzahl der Anwendungen des Anwendungstyps im Health Store gefunden.</span><span class="sxs-lookup"><span data-stu-id="542fe-108">Gets the total number of applications of the application type found in the health store.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="542fe-109">Die Gesamtanzahl von Anwendungen des Anwendungstyps.</span><span class="sxs-lookup"><span data-stu-id="542fe-109">The total number of applications of the application type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation.UnhealthyEvaluations" />
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
          <para>
            <span data-ttu-id="542fe-110">Ruft die Liste der fehlerhaften auswertungen, die zu der aggregierte Integritätszustand geführt hat.</span><span class="sxs-lookup"><span data-stu-id="542fe-110">Gets the list of unhealthy evaluations that led to the aggregated health state.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="542fe-111">Die Liste der fehlerhaften auswertungen für den angegebenen Anwendungstyp.</span><span class="sxs-lookup"><span data-stu-id="542fe-111">The list of unhealthy evaluations for the specified application type.</span></span></para>
        </value>
        <remarks> <span data-ttu-id="542fe-112">Schließt alle fehlerhaften <see cref="T:System.Fabric.Health.ApplicationHealthEvaluation" /> diesen Anwendungstyp, die die zusammengefasste Integrität ausgewirkt haben.</span><span class="sxs-lookup"><span data-stu-id="542fe-112">Includes all the unhealthy <see cref="T:System.Fabric.Health.ApplicationHealthEvaluation" /> of this application type that impacted the aggregated health.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>