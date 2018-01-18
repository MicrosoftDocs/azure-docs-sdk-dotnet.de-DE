<Type Name="StatefulServiceReplicaHealthReport" FullName="System.Fabric.Health.StatefulServiceReplicaHealthReport">
  <TypeSignature Language="C#" Value="public class StatefulServiceReplicaHealthReport : System.Fabric.Health.HealthReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StatefulServiceReplicaHealthReport extends System.Fabric.Health.HealthReport" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.StatefulServiceReplicaHealthReport" />
  <TypeSignature Language="VB.NET" Value="Public Class StatefulServiceReplicaHealthReport&#xA;Inherits HealthReport" />
  <TypeSignature Language="F#" Value="type StatefulServiceReplicaHealthReport = class&#xA;    inherit HealthReport" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthReport</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="87a60-101">Stellt einen Statusbericht auf einem zustandsbehafteten Dienst Integrität replikatsentität angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="87a60-101">Represents a health report to be applied on a stateful service replica health entity.</span></span>
            <span data-ttu-id="87a60-102">Der Bericht wird gesendet, in Health Store mit <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span><span class="sxs-lookup"><span data-stu-id="87a60-102">The report is sent to health store with <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatefulServiceReplicaHealthReport (Guid partitionId, long replicaId, System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid partitionId, int64 replicaId, class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.StatefulServiceReplicaHealthReport.#ctor(System.Guid,System.Int64,System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.StatefulServiceReplicaHealthReport : Guid * int64 * System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.StatefulServiceReplicaHealthReport" Usage="new System.Fabric.Health.StatefulServiceReplicaHealthReport (partitionId, replicaId, healthInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="87a60-103">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="87a60-103">The partition ID.</span></span></para>
        </param>
        <param name="replicaId">
          <para><span data-ttu-id="87a60-104">Die Replikat-ID</span><span class="sxs-lookup"><span data-stu-id="87a60-104">The replica ID.</span></span></para>
        </param>
        <param name="healthInformation">
          <para><span data-ttu-id="87a60-105">Die <see cref="T:System.Fabric.Health.HealthInformation" /> der beschrieben wird, die Berichtsfelder wie SourceId, Eigenschaft, Integritätsstatus.</span><span class="sxs-lookup"><span data-stu-id="87a60-105">The <see cref="T:System.Fabric.Health.HealthInformation" /> which describes the report fields, like sourceId, property, health state.</span></span> <span data-ttu-id="87a60-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="87a60-106">Required.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="87a60-107">Initialisiert eine neue Instanz von <see cref="T:System.Fabric.Health.StatefulServiceReplicaHealthReport" />.</span><span class="sxs-lookup"><span data-stu-id="87a60-107">Initializes a new instance of <see cref="T:System.Fabric.Health.StatefulServiceReplicaHealthReport" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="87a60-108">Ein null-Wert wurde für einen erforderlichen Parameter übergeben.</span><span class="sxs-lookup"><span data-stu-id="87a60-108">A null value was passed in for a required parameter.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.StatefulServiceReplicaHealthReport.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Health.StatefulServiceReplicaHealthReport.PartitionId" />
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
          <para><span data-ttu-id="87a60-109">Ruft die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="87a60-109">Gets the partition ID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="87a60-110">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="87a60-110">The partition ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaId">
      <MemberSignature Language="C#" Value="public long ReplicaId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.StatefulServiceReplicaHealthReport.ReplicaId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaId : int64" Usage="System.Fabric.Health.StatefulServiceReplicaHealthReport.ReplicaId" />
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
          <para><span data-ttu-id="87a60-111">Ruft die Replikat-ID ab.</span><span class="sxs-lookup"><span data-stu-id="87a60-111">Gets the replica ID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="87a60-112">Die Replikat-ID</span><span class="sxs-lookup"><span data-stu-id="87a60-112">The replica ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>