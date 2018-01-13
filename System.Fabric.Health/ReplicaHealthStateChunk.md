<Type Name="ReplicaHealthStateChunk" FullName="System.Fabric.Health.ReplicaHealthStateChunk">
  <TypeSignature Language="C#" Value="public sealed class ReplicaHealthStateChunk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicaHealthStateChunk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ReplicaHealthStateChunk" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicaHealthStateChunk" />
  <TypeSignature Language="F#" Value="type ReplicaHealthStateChunk = class" />
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
            <span data-ttu-id="33e0f-101">Stellt ein Replikat Health Status Segment, das grundlegende Zustandsinformationen zur das Replikat enthält.</span><span class="sxs-lookup"><span data-stu-id="33e0f-101">Represents a replica health state chunk, which contains basic health information about the replica.</span></span>
            <span data-ttu-id="33e0f-102">Sie ist als untergeordnetes Element einer Partition aus.</span><span class="sxs-lookup"><span data-stu-id="33e0f-102">It is included as child of a partition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthStateChunk.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.ReplicaHealthStateChunk.HealthState" />
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
            <span data-ttu-id="33e0f-103">Ruft ab, der aggregierte Integritätszustand des Replikats an und berechnet auf Grundlage alle gemeldeten integritätsereignisse und einer anwendungsintegritäts-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="33e0f-103">Gets the aggregated health state of the replica, computed based on all reported health events and the application health policy.</span></span>
            </summary>
        <value><span data-ttu-id="33e0f-104">Der aggregierte Integritätszustand des Replikats.</span><span class="sxs-lookup"><span data-stu-id="33e0f-104">The aggregated health state of the replica.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaOrInstanceId">
      <MemberSignature Language="C#" Value="public long ReplicaOrInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaOrInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthStateChunk.ReplicaOrInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaOrInstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaOrInstanceId : int64" Usage="System.Fabric.Health.ReplicaHealthStateChunk.ReplicaOrInstanceId" />
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
            <span data-ttu-id="33e0f-105">Ruft die Replikat-Id oder die Instanz-Id, je nach Art des Diensts ab.</span><span class="sxs-lookup"><span data-stu-id="33e0f-105">Gets the replica id or the instance id, depending on the service kind.</span></span>
            </summary>
        <value><span data-ttu-id="33e0f-106">Die Replikat-Id oder die Instanz-Id, je nach Art des Diensts.</span><span class="sxs-lookup"><span data-stu-id="33e0f-106">The replica id or the instance id, depending on the service kind.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateChunk.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="replicaHealthStateChunk.ToString " />
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
            <span data-ttu-id="33e0f-107">Erstellt eine zeichenfolgenbeschreibung des Segments Replikat Health Status an.</span><span class="sxs-lookup"><span data-stu-id="33e0f-107">Creates a string description of the replica health state chunk.</span></span>
            </summary>
        <returns><span data-ttu-id="33e0f-108">Die zeichenfolgenbeschreibung des Segments Status Integrität.</span><span class="sxs-lookup"><span data-stu-id="33e0f-108">String description of the health state chunk.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>