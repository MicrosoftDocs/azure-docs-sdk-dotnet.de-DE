<Type Name="ServicePartitionInformation" FullName="System.Fabric.ServicePartitionInformation">
  <TypeSignature Language="C#" Value="public abstract class ServicePartitionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServicePartitionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServicePartitionInformation" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServicePartitionInformation" />
  <TypeSignature Language="F#" Value="type ServicePartitionInformation = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.SingletonPartitionInformation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Int64RangePartitionInformation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.NamedPartitionInformation))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="630aa-101">Stellt die Basisklasse zum Beschreiben von Partitionen dar.</span><span class="sxs-lookup"><span data-stu-id="630aa-101">Represents the base class for describing partitions.</span></span></para>
    </summary>
    <remarks>
      <para>
        <span data-ttu-id="630aa-102"><see cref="T:System.Fabric.Int64RangePartitionInformation" />, <see cref="T:System.Fabric.NamedPartitionInformation" />, und <see cref="T:System.Fabric.SingletonPartitionInformation" /> alle von diesem Typ abgeleitet sind.</span><span class="sxs-lookup"><span data-stu-id="630aa-102"><see cref="T:System.Fabric.Int64RangePartitionInformation" />, <see cref="T:System.Fabric.NamedPartitionInformation" />, and <see cref="T:System.Fabric.SingletonPartitionInformation" /> all derive from this type.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public Guid Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid Id" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServicePartitionInformation.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As Guid" />
      <MemberSignature Language="F#" Value="member this.Id : Guid" Usage="System.Fabric.ServicePartitionInformation.Id" />
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
          <para><span data-ttu-id="630aa-103">Gibt die Partitions-ID für diese Partition als GUID an.</span><span class="sxs-lookup"><span data-stu-id="630aa-103">Specifies the partition ID for this partition as a GUID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="630aa-104">Gibt <see cref="T:System.Guid" />zurück.</span><span class="sxs-lookup"><span data-stu-id="630aa-104">Returns <see cref="T:System.Guid" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.ServicePartitionKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ServicePartitionKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServicePartitionInformation.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As ServicePartitionKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.ServicePartitionKind" Usage="System.Fabric.ServicePartitionInformation.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="630aa-105">Beschreibt den Typ der Partition an.</span><span class="sxs-lookup"><span data-stu-id="630aa-105">Describes the type of partition.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="630aa-106">Gibt <see cref="T:System.Fabric.ServicePartitionKind" />zurück.</span><span class="sxs-lookup"><span data-stu-id="630aa-106">Returns <see cref="T:System.Fabric.ServicePartitionKind" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>