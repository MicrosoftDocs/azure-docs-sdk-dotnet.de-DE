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
      <para>Stellt eine zustandsbehaftete Dienstpartition dar.</para>
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
          <para>Ruft die Dauer der letzten Quorum verloren gehen.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.TimeSpan" />zurück.</para>
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
          <para>Ruft die Mindestgröße des Replikatsatzes Satz zulässige Größe für die Partition Fortschritte zu halten.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Int64" />zurück.</para>
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
            Ruft ab Beginn des Zeitraums der Partition, sieht das Replikat
            </para>
        </summary>
        <value>
          <para>Beginn des Zeitraums der partition</para>
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
          <para>Ruft die das Zielreplikat festgelegten Größe.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Int64" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>