<Type Name="ReplicaHealthStateChunkList" FullName="System.Fabric.Health.ReplicaHealthStateChunkList">
  <TypeSignature Language="C#" Value="public sealed class ReplicaHealthStateChunkList : System.Fabric.Health.HealthStateChunkList&lt;System.Fabric.Health.ReplicaHealthStateChunk&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicaHealthStateChunkList extends System.Fabric.Health.HealthStateChunkList`1&lt;class System.Fabric.Health.ReplicaHealthStateChunk&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ReplicaHealthStateChunkList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicaHealthStateChunkList&#xA;Inherits HealthStateChunkList(Of ReplicaHealthStateChunk)" />
  <TypeSignature Language="F#" Value="type ReplicaHealthStateChunkList = class&#xA;    inherit HealthStateChunkList&lt;ReplicaHealthStateChunk&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthStateChunkList&lt;System.Fabric.Health.ReplicaHealthStateChunk&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">System.Fabric.Health.ReplicaHealthStateChunk</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Liste mit <see cref="T:System.Fabric.Health.ReplicaHealthStateChunk" /> Elemente.
            </summary>
    <remarks>Die Liste kann über integritätsabfragen Status-Blocks abgerufen werden. Abfragen können als Ergebnis Segmente aufweisen, die eine Nachricht eingefügt werden kann.
            In diesem Fall die Liste der Elemente, die die Nachricht wird zurückgegeben, sowie eine Anzahl, die zeigt, wie viele gesamtelemente sind verfügbar.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicaHealthStateChunkList ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateChunkList.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Instanziiert eine leere <see cref="T:System.Fabric.Health.ReplicaHealthStateChunkList" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>