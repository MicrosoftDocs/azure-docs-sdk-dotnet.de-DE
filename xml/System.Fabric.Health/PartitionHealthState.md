<Type Name="PartitionHealthState" FullName="System.Fabric.Health.PartitionHealthState">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealthState : System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealthState extends System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionHealthState" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealthState&#xA;Inherits EntityHealthState" />
  <TypeSignature Language="F#" Value="type PartitionHealthState = class&#xA;    inherit EntityHealthState" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealthState</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="d4051-101">Stellt den Zustand einer Partition, die die Partitions-ID und der aggregierte Integritätszustand enthält.</span><span class="sxs-lookup"><span data-stu-id="d4051-101">Represents the health state of a partition, which contains the partition identifier and its aggregated health state.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthState.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Health.PartitionHealthState.PartitionId" />
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
          <para><span data-ttu-id="d4051-102">Ruft die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="d4051-102">Gets the partition ID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="d4051-103">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="d4051-103">The partition ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthState.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionHealthState.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d4051-104">Erstellt eine zeichenfolgenbeschreibung des Integritätsstatus Partition an.</span><span class="sxs-lookup"><span data-stu-id="d4051-104">Creates a string description of the partition health state.</span></span>
            </summary>
        <returns><span data-ttu-id="d4051-105">Zeichenfolgenbeschreibung des der <see cref="T:System.Fabric.Health.PartitionHealthState" />.</span><span class="sxs-lookup"><span data-stu-id="d4051-105">String description of the <see cref="T:System.Fabric.Health.PartitionHealthState" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>