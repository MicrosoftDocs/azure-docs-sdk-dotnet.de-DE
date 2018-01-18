<Type Name="StatefulServicePartition" FullName="System.Fabric.Query.StatefulServicePartition">
  <TypeSignature Language="C#" Value="public sealed class StatefulServicePartition : System.Fabric.Query.Partition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatefulServicePartition extends System.Fabric.Query.Partition" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.StatefulServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatefulServicePartition&#xA;Inherits Partition" />
  <TypeSignature Language="F#" Value="type StatefulServicePartition = class&#xA;    inherit Partition" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.Partition</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="a109d-101">Stellt eine zustandsbehaftete Dienstpartition dar.</span><span class="sxs-lookup"><span data-stu-id="a109d-101">Represents a stateful service partition.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="LastQuorumLossDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LastQuorumLossDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LastQuorumLossDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.StatefulServicePartition.LastQuorumLossDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastQuorumLossDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LastQuorumLossDuration : TimeSpan" Usage="System.Fabric.Query.StatefulServicePartition.LastQuorumLossDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a109d-102">Ruft die Dauer der letzten Quorum verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="a109d-102">Gets the last quorum loss duration.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="a109d-103">Gibt <see cref="T:System.TimeSpan" />zurück.</span><span class="sxs-lookup"><span data-stu-id="a109d-103">Returns <see cref="T:System.TimeSpan" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinReplicaSetSize">
      <MemberSignature Language="C#" Value="public long MinReplicaSetSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MinReplicaSetSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.StatefulServicePartition.MinReplicaSetSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinReplicaSetSize As Long" />
      <MemberSignature Language="F#" Value="member this.MinReplicaSetSize : int64" Usage="System.Fabric.Query.StatefulServicePartition.MinReplicaSetSize" />
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
          <para><span data-ttu-id="a109d-104">Ruft die Mindestgröße des Replikatsatzes Satz zulässige Größe für die Partition Fortschritte zu halten.</span><span class="sxs-lookup"><span data-stu-id="a109d-104">Gets the minimum replica set size allowed for the partition to keep making progress.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="a109d-105">Gibt <see cref="T:System.Int64" />zurück.</span><span class="sxs-lookup"><span data-stu-id="a109d-105">Returns <see cref="T:System.Int64" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryEpoch">
      <MemberSignature Language="C#" Value="public System.Fabric.Epoch PrimaryEpoch { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Epoch PrimaryEpoch" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.StatefulServicePartition.PrimaryEpoch" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryEpoch As Epoch" />
      <MemberSignature Language="F#" Value="member this.PrimaryEpoch : System.Fabric.Epoch" Usage="System.Fabric.Query.StatefulServicePartition.PrimaryEpoch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Epoch</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="a109d-106">Ruft ab Beginn des Zeitraums der Partition, sieht das Replikat</span><span class="sxs-lookup"><span data-stu-id="a109d-106">Gets the epoch of the partition as seen by the replica</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="a109d-107">Beginn des Zeitraums der partition</span><span class="sxs-lookup"><span data-stu-id="a109d-107">The epoch of the partition</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetReplicaSetSize">
      <MemberSignature Language="C#" Value="public long TargetReplicaSetSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TargetReplicaSetSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.StatefulServicePartition.TargetReplicaSetSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetReplicaSetSize As Long" />
      <MemberSignature Language="F#" Value="member this.TargetReplicaSetSize : int64" Usage="System.Fabric.Query.StatefulServicePartition.TargetReplicaSetSize" />
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
          <para><span data-ttu-id="a109d-108">Ruft die das Zielreplikat festgelegten Größe.</span><span class="sxs-lookup"><span data-stu-id="a109d-108">Gets the target replica set size.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="a109d-109">Gibt <see cref="T:System.Int64" />zurück.</span><span class="sxs-lookup"><span data-stu-id="a109d-109">Returns <see cref="T:System.Int64" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>