<Type Name="NodeHealthStateChunk" FullName="System.Fabric.Health.NodeHealthStateChunk">
  <TypeSignature Language="C#" Value="public sealed class NodeHealthStateChunk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeHealthStateChunk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.NodeHealthStateChunk" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeHealthStateChunk" />
  <TypeSignature Language="F#" Value="type NodeHealthStateChunk = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2ff94-101">Stellt ein Knoten Integrität Zustand Segment, das grundlegende Zustandsinformationen zur des Knotens enthält.</span><span class="sxs-lookup"><span data-stu-id="2ff94-101">Represents a node health state chunk, which contains basic health information about the node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodeHealthStateChunk.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.NodeHealthStateChunk.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ff94-102">Ruft die aggregierte Integritätsstatus des Knotens, berechnet basierend auf alle gemeldeten integritätsereignisse und die clusterintegritätsrichtlinie ab.</span><span class="sxs-lookup"><span data-stu-id="2ff94-102">Gets the aggregated health state of the node, computed based on all reported health events and the cluster health policy.</span></span>
            </summary>
        <value><span data-ttu-id="2ff94-103">Der aggregierte Integritätszustand des Knotens.</span><span class="sxs-lookup"><span data-stu-id="2ff94-103">The aggregated health state of the node.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodeHealthStateChunk.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.NodeHealthStateChunk.NodeName" />
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
            <span data-ttu-id="2ff94-104">Ruft den Knotennamen ab.</span><span class="sxs-lookup"><span data-stu-id="2ff94-104">Gets the node name.</span></span>
            </summary>
        <value><span data-ttu-id="2ff94-105">Der Knotenname.</span><span class="sxs-lookup"><span data-stu-id="2ff94-105">The node name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.NodeHealthStateChunk.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeHealthStateChunk.ToString " />
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
            <span data-ttu-id="2ff94-106">Erstellt eine zeichenfolgenbeschreibung des Segments Knoten Health Status an.</span><span class="sxs-lookup"><span data-stu-id="2ff94-106">Creates a string description of the node health state chunk.</span></span>
            </summary>
        <returns><span data-ttu-id="2ff94-107">Zeichenfolgenbeschreibung des der <see cref="T:System.Fabric.Health.NodeHealthStateChunk" />.</span><span class="sxs-lookup"><span data-stu-id="2ff94-107">String description of the <see cref="T:System.Fabric.Health.NodeHealthStateChunk" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>