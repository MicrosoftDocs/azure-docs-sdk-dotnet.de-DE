<Type Name="NamedPartitionInformation" FullName="System.Fabric.NamedPartitionInformation">
  <TypeSignature Language="C#" Value="public sealed class NamedPartitionInformation : System.Fabric.ServicePartitionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamedPartitionInformation extends System.Fabric.ServicePartitionInformation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NamedPartitionInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamedPartitionInformation&#xA;Inherits ServicePartitionInformation" />
  <TypeSignature Language="F#" Value="type NamedPartitionInformation = class&#xA;    inherit ServicePartitionInformation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.ServicePartitionInformation</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1201:ElementsMustAppearInTheCorrectOrder", Justification="Preserve order of public members from V1.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="4c665-101">Beschreibt die Partitionsinformationen für den Namen als eine Zeichenfolge, die auf Partitionsschemas basiert.</span><span class="sxs-lookup"><span data-stu-id="4c665-101">Describes the partition information for the name as a string that is based on partition schemes.</span></span>
            <span data-ttu-id="4c665-102">Services Beachten Sie diese Art von <see cref="T:System.Fabric.ServicePartitionInformation" /> Erstellungszeit des Diensts mit der <see cref="T:System.Fabric.Description.NamedPartitionSchemeDescription" />.</span><span class="sxs-lookup"><span data-stu-id="4c665-102">Services observe this type of <see cref="T:System.Fabric.ServicePartitionInformation" /> when the service is created with the <see cref="T:System.Fabric.Description.NamedPartitionSchemeDescription" />.</span></span> <span data-ttu-id="4c665-103"><see cref="T:System.Fabric.NamedPartitionInformation" />leitet sich von der <see cref="T:System.Fabric.IServicePartition" /> Schnittstelle und dient der Dienste im Rahmen des der <see cref="T:System.Fabric.IStatefulServicePartition" /> oder <see cref="T:System.Fabric.IStatelessServicePartition" /> -Schnittstelle, die während der zustandsbehafteten übergeben wird <see cref="M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" /> oder die zustandslose <see cref="M:System.Fabric.IStatelessServiceInstance.OpenAsync(System.Fabric.IStatelessServicePartition,System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="4c665-103"><see cref="T:System.Fabric.NamedPartitionInformation" /> derives from the <see cref="T:System.Fabric.IServicePartition" /> interface and is provided to services as part of the <see cref="T:System.Fabric.IStatefulServicePartition" /> or <see cref="T:System.Fabric.IStatelessServicePartition" /> interface, which is passed in during the stateful <see cref="M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" /> or the stateless <see cref="M:System.Fabric.IStatelessServiceInstance.OpenAsync(System.Fabric.IStatelessServicePartition,System.Threading.CancellationToken)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPartitionInformation.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.NamedPartitionInformation.Name" />
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
          <para><span data-ttu-id="4c665-104">Gibt den Namen dieser Partition des Diensts an.</span><span class="sxs-lookup"><span data-stu-id="4c665-104">Indicates the name of this partition of the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4c665-105">Der Name dieser Partition des Diensts.</span><span class="sxs-lookup"><span data-stu-id="4c665-105">The name of this partition of the service.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>