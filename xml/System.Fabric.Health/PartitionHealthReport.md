<Type Name="PartitionHealthReport" FullName="System.Fabric.Health.PartitionHealthReport">
  <TypeSignature Language="C#" Value="public class PartitionHealthReport : System.Fabric.Health.HealthReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PartitionHealthReport extends System.Fabric.Health.HealthReport" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionHealthReport" />
  <TypeSignature Language="VB.NET" Value="Public Class PartitionHealthReport&#xA;Inherits HealthReport" />
  <TypeSignature Language="F#" Value="type PartitionHealthReport = class&#xA;    inherit HealthReport" />
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
      <para><span data-ttu-id="ecc6f-101">Stellt einen Statusbericht für die Entität eine Partition Integrität verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="ecc6f-101">Represents a health report to be applied on a partition health entity.</span></span> <span data-ttu-id="ecc6f-102">Der Bericht wird gesendet, in Health Store mit <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span><span class="sxs-lookup"><span data-stu-id="ecc6f-102">The report is sent to health store with <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionHealthReport (Guid partitionId, System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid partitionId, class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthReport.#ctor(System.Guid,System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.PartitionHealthReport : Guid * System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.PartitionHealthReport" Usage="new System.Fabric.Health.PartitionHealthReport (partitionId, healthInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="ecc6f-103">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="ecc6f-103">The partition ID.</span></span> <span data-ttu-id="ecc6f-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ecc6f-104">Required.</span></span></para>
        </param>
        <param name="healthInformation">
          <para><span data-ttu-id="ecc6f-105">Die <see cref="T:System.Fabric.Health.HealthInformation" /> der beschrieben wird, die Berichtsfelder wie SourceId, Eigenschaft, Integritätsstatus.</span><span class="sxs-lookup"><span data-stu-id="ecc6f-105">The <see cref="T:System.Fabric.Health.HealthInformation" /> which describes the report fields, like sourceId, property, health state.</span></span> <span data-ttu-id="ecc6f-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ecc6f-106">Required.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="ecc6f-107">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.PartitionHealthReport" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ecc6f-107">Initializes a new instance of the <see cref="T:System.Fabric.Health.PartitionHealthReport" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="ecc6f-108">Ein null-Wert wurde für einen erforderlichen Parameter übergeben.</span><span class="sxs-lookup"><span data-stu-id="ecc6f-108">A null value was passed in for a required parameter.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthReport.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Health.PartitionHealthReport.PartitionId" />
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
          <para><span data-ttu-id="ecc6f-109">Ruft die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="ecc6f-109">Gets the partition ID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ecc6f-110">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="ecc6f-110">The partition ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>