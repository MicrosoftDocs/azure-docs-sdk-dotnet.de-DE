<Type Name="DeployedServicePackageHealthStateChunkList" FullName="System.Fabric.Health.DeployedServicePackageHealthStateChunkList">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealthStateChunkList : System.Fabric.Health.HealthStateChunkList&lt;System.Fabric.Health.DeployedServicePackageHealthStateChunk&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealthStateChunkList extends System.Fabric.Health.HealthStateChunkList`1&lt;class System.Fabric.Health.DeployedServicePackageHealthStateChunk&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackageHealthStateChunkList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealthStateChunkList&#xA;Inherits HealthStateChunkList(Of DeployedServicePackageHealthStateChunk)" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthStateChunkList = class&#xA;    inherit HealthStateChunkList&lt;DeployedServicePackageHealthStateChunk&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthStateChunkList&lt;System.Fabric.Health.DeployedServicePackageHealthStateChunk&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">System.Fabric.Health.DeployedServicePackageHealthStateChunk</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7df25-101">Stellt eine Liste mit <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateChunk" /> Elemente.</span><span class="sxs-lookup"><span data-stu-id="7df25-101">Represents a list that contains <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateChunk" /> items.</span></span>
            </summary>
    <remarks><span data-ttu-id="7df25-102">Die Liste kann über integritätsabfragen Status-Blocks abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="7df25-102">The list can be obtained through health state chunk queries.</span></span> <span data-ttu-id="7df25-103">Abfragen können als Ergebnis Segmente aufweisen, die eine Nachricht eingefügt werden kann.</span><span class="sxs-lookup"><span data-stu-id="7df25-103">The queries may have as result more chunks that can fit a message.</span></span>
            <span data-ttu-id="7df25-104">In diesem Fall die Liste der Elemente, die die Nachricht wird zurückgegeben, sowie eine Anzahl, die zeigt, wie viele gesamtelemente sind verfügbar.</span><span class="sxs-lookup"><span data-stu-id="7df25-104">In this case, the list of items that fit the message is returned plus a count that shows how many total items are available.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthStateChunkList ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateChunkList.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7df25-105">Instanziiert eine leere <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateChunkList" />.</span><span class="sxs-lookup"><span data-stu-id="7df25-105">Instantiates an empty <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateChunkList" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>