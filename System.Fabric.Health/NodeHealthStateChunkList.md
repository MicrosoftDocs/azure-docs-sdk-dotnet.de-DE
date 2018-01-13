<Type Name="NodeHealthStateChunkList" FullName="System.Fabric.Health.NodeHealthStateChunkList">
  <TypeSignature Language="C#" Value="public sealed class NodeHealthStateChunkList : System.Fabric.Health.HealthStateChunkList&lt;System.Fabric.Health.NodeHealthStateChunk&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeHealthStateChunkList extends System.Fabric.Health.HealthStateChunkList`1&lt;class System.Fabric.Health.NodeHealthStateChunk&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.NodeHealthStateChunkList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeHealthStateChunkList&#xA;Inherits HealthStateChunkList(Of NodeHealthStateChunk)" />
  <TypeSignature Language="F#" Value="type NodeHealthStateChunkList = class&#xA;    inherit HealthStateChunkList&lt;NodeHealthStateChunk&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthStateChunkList&lt;System.Fabric.Health.NodeHealthStateChunk&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">System.Fabric.Health.NodeHealthStateChunk</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="140f1-101">Stellt eine Liste mit <see cref="T:System.Fabric.Health.NodeHealthStateChunk" /> Elemente.</span><span class="sxs-lookup"><span data-stu-id="140f1-101">Represents a list that contains <see cref="T:System.Fabric.Health.NodeHealthStateChunk" /> items.</span></span>
            </summary>
    <remarks><span data-ttu-id="140f1-102">Die Liste kann über integritätsabfragen Status-Blocks abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="140f1-102">The list can be obtained through health state chunk queries.</span></span> <span data-ttu-id="140f1-103">Abfragen können als Ergebnis Segmente aufweisen, die eine Nachricht eingefügt werden kann.</span><span class="sxs-lookup"><span data-stu-id="140f1-103">The queries may have as result more chunks that can fit a message.</span></span>
            <span data-ttu-id="140f1-104">In diesem Fall die Liste der Elemente, die die Nachricht wird zurückgegeben, sowie eine Anzahl, die zeigt, wie viele gesamtelemente sind verfügbar.</span><span class="sxs-lookup"><span data-stu-id="140f1-104">In this case, the list of items that fit the message is returned plus a count that shows how many total items are available.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeHealthStateChunkList ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.NodeHealthStateChunkList.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="140f1-105">Instanziiert eine leere <see cref="T:System.Fabric.Health.NodeHealthStateChunkList" />.</span><span class="sxs-lookup"><span data-stu-id="140f1-105">Instantiates an empty <see cref="T:System.Fabric.Health.NodeHealthStateChunkList" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>