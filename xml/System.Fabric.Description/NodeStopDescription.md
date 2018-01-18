<Type Name="NodeStopDescription" FullName="System.Fabric.Description.NodeStopDescription">
  <TypeSignature Language="C#" Value="public sealed class NodeStopDescription : System.Fabric.Description.NodeTransitionDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeStopDescription extends System.Fabric.Description.NodeTransitionDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.NodeStopDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeStopDescription&#xA;Inherits NodeTransitionDescription" />
  <TypeSignature Language="F#" Value="type NodeStopDescription = class&#xA;    inherit NodeTransitionDescription" />
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
            <span data-ttu-id="c869e-101">Beschreibt Informationen dazu, wie ein Knoten sollten mit StartNodeTransitionAsync() beendet.</span><span class="sxs-lookup"><span data-stu-id="c869e-101">Describes information about how a node should be stopped using StartNodeTransitionAsync().</span></span>  
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeStopDescription (Guid operationId, string nodeName, System.Numerics.BigInteger nodeInstanceId, int stopDurationInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid operationId, string nodeName, valuetype System.Numerics.BigInteger nodeInstanceId, int32 stopDurationInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.NodeStopDescription.#ctor(System.Guid,System.String,System.Numerics.BigInteger,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (operationId As Guid, nodeName As String, nodeInstanceId As BigInteger, stopDurationInSeconds As Integer)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.NodeStopDescription : Guid * string * System.Numerics.BigInteger * int -&gt; System.Fabric.Description.NodeStopDescription" Usage="new System.Fabric.Description.NodeStopDescription (operationId, nodeName, nodeInstanceId, stopDurationInSeconds)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstanceId" Type="System.Numerics.BigInteger" />
        <Parameter Name="stopDurationInSeconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c869e-102">Eine Guid, um diesen Vorgang zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="c869e-102">A Guid to identify this operation.</span></span>  <span data-ttu-id="c869e-103">Dies sollte eindeutig sein und sollte nicht mit anderen Vorgängen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c869e-103">This should be unique, and should not be used with other operations.</span></span></param>
        <param name="nodeName"><span data-ttu-id="c869e-104">Der Name des Knotens zum Starten oder beenden.</span><span class="sxs-lookup"><span data-stu-id="c869e-104">The name of the node to start or stop.</span></span>  <span data-ttu-id="c869e-105">Der Name kann über GetNodeListAsync() ermittelt werden.</span><span class="sxs-lookup"><span data-stu-id="c869e-105">The name can be determined through GetNodeListAsync().</span></span></param>
        <param name="nodeInstanceId"><span data-ttu-id="c869e-106">Die Knoten-Id des Zielknotens.</span><span class="sxs-lookup"><span data-stu-id="c869e-106">The node instance id of the target node.</span></span>  <span data-ttu-id="c869e-107">Dies kann durch GetNodeListAsync() ermittelt werden.</span><span class="sxs-lookup"><span data-stu-id="c869e-107">This can be determined through GetNodeListAsync().</span></span></param>
        <param name="stopDurationInSeconds"><span data-ttu-id="c869e-108">Die Dauer den Knoten erhalten bleiben beendet.</span><span class="sxs-lookup"><span data-stu-id="c869e-108">The duration to keep the node stopped.</span></span>  <span data-ttu-id="c869e-109">Nach Ablauf dieser Zeit wird der Knoten automatisch wieder da sind.</span><span class="sxs-lookup"><span data-stu-id="c869e-109">After this time expires, the node will automatically come back up.</span></span>  <span data-ttu-id="c869e-110">Die Einheiten wird in Sekunden angegeben.</span><span class="sxs-lookup"><span data-stu-id="c869e-110">The units is in seconds.</span></span>  <span data-ttu-id="c869e-111">Der Mindestwert beträgt 600, der Höchstwert beträgt 14400.</span><span class="sxs-lookup"><span data-stu-id="c869e-111">The minimum value is 600, the maximum is 14400.</span></span></param>
        <summary>
            <span data-ttu-id="c869e-112">Erstellt eine NodeTransitionDescription, die Informationen zu einem Knoten beenden beschreibt.</span><span class="sxs-lookup"><span data-stu-id="c869e-112">Constructs a NodeTransitionDescription, which describes information about a node to stop.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopDurationInSeconds">
      <MemberSignature Language="C#" Value="public int StopDurationInSeconds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StopDurationInSeconds" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.NodeStopDescription.StopDurationInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StopDurationInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.StopDurationInSeconds : int" Usage="System.Fabric.Description.NodeStopDescription.StopDurationInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c869e-113">Die Dauer den Knoten erhalten bleiben beendet.</span><span class="sxs-lookup"><span data-stu-id="c869e-113">The duration to keep the node stopped.</span></span>  <span data-ttu-id="c869e-114">Nach Ablauf dieser Zeit wird der Knoten automatisch wieder da sind.</span><span class="sxs-lookup"><span data-stu-id="c869e-114">After this time expires, the node will automatically come back up.</span></span>  <span data-ttu-id="c869e-115">Die Einheiten wird in Sekunden angegeben.</span><span class="sxs-lookup"><span data-stu-id="c869e-115">The units is in seconds.</span></span>  <span data-ttu-id="c869e-116">Der Mindestwert beträgt 600, der Höchstwert beträgt 14400.</span><span class="sxs-lookup"><span data-stu-id="c869e-116">The minimum value is 600, the maximum is 14400.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.NodeStopDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeStopDescription.ToString " />
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
            <span data-ttu-id="c869e-117">Gibt eine Zeichenfolgendarstellung des Objekts an.</span><span class="sxs-lookup"><span data-stu-id="c869e-117">Prints a string representation of the object.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>