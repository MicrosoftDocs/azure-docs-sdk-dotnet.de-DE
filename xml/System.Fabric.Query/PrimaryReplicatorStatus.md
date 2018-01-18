<Type Name="PrimaryReplicatorStatus" FullName="System.Fabric.Query.PrimaryReplicatorStatus">
  <TypeSignature Language="C#" Value="public sealed class PrimaryReplicatorStatus : System.Fabric.Query.ReplicatorStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PrimaryReplicatorStatus extends System.Fabric.Query.ReplicatorStatus" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.PrimaryReplicatorStatus" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PrimaryReplicatorStatus&#xA;Inherits ReplicatorStatus" />
  <TypeSignature Language="F#" Value="type PrimaryReplicatorStatus = class&#xA;    inherit ReplicatorStatus" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.ReplicatorStatus</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="ae8d1-101">Stellt Statistiken zum Service Fabric Replikator, bereit, wenn es in funktioniert einer <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle.</span><span class="sxs-lookup"><span data-stu-id="ae8d1-101">Provides statistics about the Service Fabric Replicator, when it is functioning in a <see cref="F:System.Fabric.ReplicaRole.Primary" /> role.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PrimaryReplicatorStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.PrimaryReplicatorStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="ae8d1-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.PrimaryReplicatorStatus" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ae8d1-102">Initializes a new instance of the <see cref="T:System.Fabric.Query.PrimaryReplicatorStatus" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteReplicators">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.RemoteReplicatorStatus&gt; RemoteReplicators { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.RemoteReplicatorStatus&gt; RemoteReplicators" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.PrimaryReplicatorStatus.RemoteReplicators" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteReplicators As IList(Of RemoteReplicatorStatus)" />
      <MemberSignature Language="F#" Value="member this.RemoteReplicators : System.Collections.Generic.IList&lt;System.Fabric.Query.RemoteReplicatorStatus&gt;" Usage="System.Fabric.Query.PrimaryReplicatorStatus.RemoteReplicators" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.RemoteReplicatorStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ae8d1-103">Ruft den Status der die sekundären Replikate der primären bekannt ist.</span><span class="sxs-lookup"><span data-stu-id="ae8d1-103">Gets the status of all the secondary replicas that the primary is aware of.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ae8d1-104">Die Liste der remote-Replikatoren.</span><span class="sxs-lookup"><span data-stu-id="ae8d1-104">The list of remote replicators.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationQueueStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicatorQueueStatus ReplicationQueueStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ReplicatorQueueStatus ReplicationQueueStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.PrimaryReplicatorStatus.ReplicationQueueStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationQueueStatus As ReplicatorQueueStatus" />
      <MemberSignature Language="F#" Value="member this.ReplicationQueueStatus : System.Fabric.Query.ReplicatorQueueStatus" Usage="System.Fabric.Query.PrimaryReplicatorStatus.ReplicationQueueStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorQueueStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ae8d1-105">Ruft den Status der Replikationswarteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="ae8d1-105">Gets the status of the Replication queue.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ae8d1-106">Der Status der Replikationswarteschlange.</span><span class="sxs-lookup"><span data-stu-id="ae8d1-106">The status of the replication queue.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>