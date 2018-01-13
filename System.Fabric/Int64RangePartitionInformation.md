<Type Name="Int64RangePartitionInformation" FullName="System.Fabric.Int64RangePartitionInformation">
  <TypeSignature Language="C#" Value="public sealed class Int64RangePartitionInformation : System.Fabric.ServicePartitionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Int64RangePartitionInformation extends System.Fabric.ServicePartitionInformation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Int64RangePartitionInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Int64RangePartitionInformation&#xA;Inherits ServicePartitionInformation" />
  <TypeSignature Language="F#" Value="type Int64RangePartitionInformation = class&#xA;    inherit ServicePartitionInformation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.ServicePartitionInformation</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Beschreibt die Partitionsinformationen für die Bereichs für ganze Zahlen, die auf Partitionsschemas basieren. Services Beachten Sie diese Art von <see cref="T:System.Fabric.ServicePartitionInformation" /> Erstellungszeit des Diensts mit der <see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" /> Klasse. <see cref="T:System.Fabric.Int64RangePartitionInformation" />leitet sich von <see cref="T:System.Fabric.IServicePartition" /> und dient der Dienste im Rahmen des der <see cref="T:System.Fabric.IStatefulServicePartition" /> oder <see cref="T:System.Fabric.IStatelessServicePartition" />, die im übergeben wird, über die statusbehaftete <see cref="M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" /> oder die zustandslose <see cref="M:System.Fabric.IStatelessServiceInstance.OpenAsync(System.Fabric.IStatelessServicePartition,System.Threading.CancellationToken)" /> Methoden.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HighKey">
      <MemberSignature Language="C#" Value="public long HighKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HighKey" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Int64RangePartitionInformation.HighKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HighKey As Long" />
      <MemberSignature Language="F#" Value="member this.HighKey : int64" Usage="System.Fabric.Int64RangePartitionInformation.HighKey" />
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
          <para>Gibt die maximale Schlüsselwert für diese Partition an.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Int64" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LowKey">
      <MemberSignature Language="C#" Value="public long LowKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LowKey" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Int64RangePartitionInformation.LowKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LowKey As Long" />
      <MemberSignature Language="F#" Value="member this.LowKey : int64" Usage="System.Fabric.Int64RangePartitionInformation.LowKey" />
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
          <para>Gibt den minimalen Schlüsselwert für diese Partition an.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Int64" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>