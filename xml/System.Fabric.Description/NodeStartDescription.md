<Type Name="NodeStartDescription" FullName="System.Fabric.Description.NodeStartDescription">
  <TypeSignature Language="C#" Value="public sealed class NodeStartDescription : System.Fabric.Description.NodeTransitionDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeStartDescription extends System.Fabric.Description.NodeTransitionDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.NodeStartDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeStartDescription&#xA;Inherits NodeTransitionDescription" />
  <TypeSignature Language="F#" Value="type NodeStartDescription = class&#xA;    inherit NodeTransitionDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.NodeTransitionDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="95eaf-101">Beschreibt Informationen dazu, wie ein Knoten sollten mit StartNodeTransitionAsync() gestartet.</span><span class="sxs-lookup"><span data-stu-id="95eaf-101">Describes information about how a node should be started using StartNodeTransitionAsync().</span></span>  
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeStartDescription (Guid operationId, string nodeName, System.Numerics.BigInteger nodeInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid operationId, string nodeName, valuetype System.Numerics.BigInteger nodeInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.NodeStartDescription.#ctor(System.Guid,System.String,System.Numerics.BigInteger)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (operationId As Guid, nodeName As String, nodeInstanceId As BigInteger)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.NodeStartDescription : Guid * string * System.Numerics.BigInteger -&gt; System.Fabric.Description.NodeStartDescription" Usage="new System.Fabric.Description.NodeStartDescription (operationId, nodeName, nodeInstanceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstanceId" Type="System.Numerics.BigInteger" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="95eaf-102">Eine Guid, um diesen Vorgang zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="95eaf-102">A Guid to identify this operation.</span></span>  <span data-ttu-id="95eaf-103">Dies sollte eindeutig sein und sollte nicht mit anderen Vorgängen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="95eaf-103">This should be unique, and should not be used with other operations.</span></span></param>
        <param name="nodeName"><span data-ttu-id="95eaf-104">Der Name des Knotens zum Starten oder beenden.</span><span class="sxs-lookup"><span data-stu-id="95eaf-104">The name of the node to start or stop.</span></span>  <span data-ttu-id="95eaf-105">Der Name kann über GetNodeListAsync() ermittelt werden.</span><span class="sxs-lookup"><span data-stu-id="95eaf-105">The name can be determined through GetNodeListAsync().</span></span></param>
        <param name="nodeInstanceId"><span data-ttu-id="95eaf-106">Die Knoten-Id des Zielknotens.</span><span class="sxs-lookup"><span data-stu-id="95eaf-106">The node instance id of the target node.</span></span>  <span data-ttu-id="95eaf-107">Dies kann durch GetNodeListAsync() ermittelt werden.</span><span class="sxs-lookup"><span data-stu-id="95eaf-107">This can be determined through GetNodeListAsync().</span></span></param>
        <summary>
            <span data-ttu-id="95eaf-108">Erstellen Sie eine Instanz des NodeStartDescription, die Informationen, wie ein Knoten sein soll beschreibt mit StartNodeTransitionAsync() gestartet.</span><span class="sxs-lookup"><span data-stu-id="95eaf-108">Create an instance of NodeStartDescription, which describes information about how a node should be started using StartNodeTransitionAsync().</span></span>  
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>