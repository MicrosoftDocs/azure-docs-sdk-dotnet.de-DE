<Type Name="PartitionHealthStateChunkList" FullName="System.Fabric.Health.PartitionHealthStateChunkList">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealthStateChunkList : System.Fabric.Health.HealthStateChunkList&lt;System.Fabric.Health.PartitionHealthStateChunk&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealthStateChunkList extends System.Fabric.Health.HealthStateChunkList`1&lt;class System.Fabric.Health.PartitionHealthStateChunk&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionHealthStateChunkList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealthStateChunkList&#xA;Inherits HealthStateChunkList(Of PartitionHealthStateChunk)" />
  <TypeSignature Language="F#" Value="type PartitionHealthStateChunkList = class&#xA;    inherit HealthStateChunkList&lt;PartitionHealthStateChunk&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthStateChunkList&lt;System.Fabric.Health.PartitionHealthStateChunk&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">System.Fabric.Health.PartitionHealthStateChunk</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Liste mit <see cref="T:System.Fabric.Health.PartitionHealthStateChunk" /> Elemente.
            </summary>
    <remarks>Die Liste kann über integritätsabfragen Status-Blocks abgerufen werden. Abfragen können als Ergebnis Segmente aufweisen, die eine Nachricht eingefügt werden kann.
            In diesem Fall die Liste der Elemente, die die Nachricht wird zurückgegeben, sowie eine Anzahl, die zeigt, wie viele gesamtelemente sind verfügbar.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionHealthStateChunkList ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthStateChunkList.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Instanziiert eine leere <see cref="T:System.Fabric.Health.PartitionHealthStateChunkList" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>