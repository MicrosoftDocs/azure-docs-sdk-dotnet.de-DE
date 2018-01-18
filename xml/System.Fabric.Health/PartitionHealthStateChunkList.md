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
            <span data-ttu-id="9023c-101">Stellt eine Liste mit <see cref="T:System.Fabric.Health.PartitionHealthStateChunk" /> Elemente.</span><span class="sxs-lookup"><span data-stu-id="9023c-101">Represents a list that contains <see cref="T:System.Fabric.Health.PartitionHealthStateChunk" /> items.</span></span>
            </summary>
    <remarks><span data-ttu-id="9023c-102">Die Liste kann über integritätsabfragen Status-Blocks abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="9023c-102">The list can be obtained through health state chunk queries.</span></span> <span data-ttu-id="9023c-103">Abfragen können als Ergebnis Segmente aufweisen, die eine Nachricht eingefügt werden kann.</span><span class="sxs-lookup"><span data-stu-id="9023c-103">The queries may have as result more chunks that can fit a message.</span></span>
            <span data-ttu-id="9023c-104">In diesem Fall die Liste der Elemente, die die Nachricht wird zurückgegeben, sowie eine Anzahl, die zeigt, wie viele gesamtelemente sind verfügbar.</span><span class="sxs-lookup"><span data-stu-id="9023c-104">In this case, the list of items that fit the message is returned plus a count that shows how many total items are available.</span></span></remarks>
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
            <span data-ttu-id="9023c-105">Instanziiert eine leere <see cref="T:System.Fabric.Health.PartitionHealthStateChunkList" />.</span><span class="sxs-lookup"><span data-stu-id="9023c-105">Instantiates an empty <see cref="T:System.Fabric.Health.PartitionHealthStateChunkList" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>