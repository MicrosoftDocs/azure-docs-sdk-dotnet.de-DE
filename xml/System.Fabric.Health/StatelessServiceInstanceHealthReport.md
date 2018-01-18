<Type Name="StatelessServiceInstanceHealthReport" FullName="System.Fabric.Health.StatelessServiceInstanceHealthReport">
  <TypeSignature Language="C#" Value="public class StatelessServiceInstanceHealthReport : System.Fabric.Health.HealthReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StatelessServiceInstanceHealthReport extends System.Fabric.Health.HealthReport" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.StatelessServiceInstanceHealthReport" />
  <TypeSignature Language="VB.NET" Value="Public Class StatelessServiceInstanceHealthReport&#xA;Inherits HealthReport" />
  <TypeSignature Language="F#" Value="type StatelessServiceInstanceHealthReport = class&#xA;    inherit HealthReport" />
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
      <para><span data-ttu-id="459ce-101">Stellt einen Statusbericht auf einem zustandslosen Diensts Integrität Entität angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="459ce-101">Represents a health report to be applied on a stateless service health entity.</span></span>
            <span data-ttu-id="459ce-102">Der Bericht wird gesendet, in Health Store mit <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span><span class="sxs-lookup"><span data-stu-id="459ce-102">The report is sent to health store with <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatelessServiceInstanceHealthReport (Guid partitionId, long instanceId, System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid partitionId, int64 instanceId, class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.StatelessServiceInstanceHealthReport.#ctor(System.Guid,System.Int64,System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.StatelessServiceInstanceHealthReport : Guid * int64 * System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.StatelessServiceInstanceHealthReport" Usage="new System.Fabric.Health.StatelessServiceInstanceHealthReport (partitionId, instanceId, healthInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="instanceId" Type="System.Int64" />
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="459ce-103">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="459ce-103">The partition ID.</span></span></para>
        </param>
        <param name="instanceId">
          <para><span data-ttu-id="459ce-104">Die Instanz-ID.</span><span class="sxs-lookup"><span data-stu-id="459ce-104">The instance ID.</span></span></para>
        </param>
        <param name="healthInformation">
          <para><span data-ttu-id="459ce-105">Die <see cref="T:System.Fabric.Health.HealthInformation" /> der beschrieben wird, die Berichtsfelder wie SourceId, Eigenschaft, Integritätsstatus.</span><span class="sxs-lookup"><span data-stu-id="459ce-105">The <see cref="T:System.Fabric.Health.HealthInformation" /> which describes the report fields, like sourceId, property, health state.</span></span> <span data-ttu-id="459ce-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="459ce-106">Required.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="459ce-107">Initialisiert eine neue Instanz von <see cref="T:System.Fabric.Health.StatelessServiceInstanceHealthReport" />.</span><span class="sxs-lookup"><span data-stu-id="459ce-107">Initializes a new instance of <see cref="T:System.Fabric.Health.StatelessServiceInstanceHealthReport" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="459ce-108">Ein null-Wert wurde für einen erforderlichen Parameter übergeben.</span><span class="sxs-lookup"><span data-stu-id="459ce-108">A null value was passed in for a required parameter.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="InstanceId">
      <MemberSignature Language="C#" Value="public long InstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 InstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.StatelessServiceInstanceHealthReport.InstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.InstanceId : int64" Usage="System.Fabric.Health.StatelessServiceInstanceHealthReport.InstanceId" />
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
          <para><span data-ttu-id="459ce-109">Ruft die Instanz-ID ab.</span><span class="sxs-lookup"><span data-stu-id="459ce-109">Gets the instance ID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="459ce-110">Die Instanz-ID.</span><span class="sxs-lookup"><span data-stu-id="459ce-110">The instance ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.StatelessServiceInstanceHealthReport.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Health.StatelessServiceInstanceHealthReport.PartitionId" />
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
          <para><span data-ttu-id="459ce-111">Ruft die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="459ce-111">Gets the partition ID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="459ce-112">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="459ce-112">The partition ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>