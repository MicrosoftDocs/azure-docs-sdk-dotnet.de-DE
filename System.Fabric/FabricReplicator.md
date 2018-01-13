<Type Name="FabricReplicator" FullName="System.Fabric.FabricReplicator">
  <TypeSignature Language="C#" Value="public sealed class FabricReplicator : System.Fabric.IReplicator, System.Fabric.IReplicatorCatchupSpecificQuorum" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FabricReplicator extends System.Object implements class System.Fabric.IPrimaryReplicator, class System.Fabric.IReplicator, class System.Fabric.IReplicatorCatchupSpecificQuorum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricReplicator" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricReplicator&#xA;Implements IReplicator, IReplicatorCatchupSpecificQuorum" />
  <TypeSignature Language="F#" Value="type FabricReplicator = class&#xA;    interface IReplicator&#xA;    interface IPrimaryReplicator&#xA;    interface IReplicatorCatchupSpecificQuorum" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IReplicator</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Fabric.IReplicatorCatchupSpecificQuorum</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>Repliziert den Status für hohe Verfügbarkeit und Zuverlässigkeit. </para>
    </summary>
    <remarks>
      <para>Stellt die Standardimplementierung von der <see cref="T:System.Fabric.IStateReplicator" />, <see cref="T:System.Fabric.IReplicator" />, und <see cref="T:System.Fabric.IPrimaryReplicator" /> Schnittstellen, die Benutzerdienste werden, zusammen mit ihrer Implementierung von verwendet können der <see cref="T:System.Fabric.IStateProvider" /> Schnittstelle.</para>
      <para>Eine Instanz von der <see cref="T:System.Fabric.FabricReplicator" /> Klasse abgerufen wird, über die <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" /> Methode.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="InvalidAtomicGroupId">
      <MemberSignature Language="C#" Value="public const long InvalidAtomicGroupId = -1;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int64 InvalidAtomicGroupId = (-1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FabricReplicator.InvalidAtomicGroupId" />
      <MemberSignature Language="VB.NET" Value="Public Const InvalidAtomicGroupId As Long  = -1" />
      <MemberSignature Language="F#" Value="val mutable InvalidAtomicGroupId : int64" Usage="System.Fabric.FabricReplicator.InvalidAtomicGroupId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <MemberValue>-1</MemberValue>
      <Docs>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateReplicator">
      <MemberSignature Language="C#" Value="public System.Fabric.IStateReplicator StateReplicator { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.IStateReplicator StateReplicator" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricReplicator.StateReplicator" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateReplicator As IStateReplicator" />
      <MemberSignature Language="F#" Value="member this.StateReplicator : System.Fabric.IStateReplicator" Usage="System.Fabric.FabricReplicator.StateReplicator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IStateReplicator</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die <see cref="T:System.Fabric.IStateReplicator" /> die Replikation des Status verwendet werden können</para>
        </summary>
        <value>Ein Wert, der die <see cref="T:System.Fabric.IStateReplicator" /> die Replikation des Status verwendet werden können</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateReplicator2">
      <MemberSignature Language="C#" Value="public System.Fabric.IStateReplicator2 StateReplicator2 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.IStateReplicator2 StateReplicator2" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricReplicator.StateReplicator2" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateReplicator2 As IStateReplicator2" />
      <MemberSignature Language="F#" Value="member this.StateReplicator2 : System.Fabric.IStateReplicator2" Usage="System.Fabric.FabricReplicator.StateReplicator2" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IStateReplicator2</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die <see cref="T:System.Fabric.IStateReplicator2" /> die Replikation des Status verwendet werden können</para>
        </summary>
        <value>Ein Wert, der die <see cref="T:System.Fabric.IStateReplicator2" /> die Replikation des Status verwendet werden können</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IPrimaryReplicator.BuildReplicaAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IPrimaryReplicator.BuildReplicaAsync (System.Fabric.ReplicaInformation replicaInfo, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task System.Fabric.IPrimaryReplicator.BuildReplicaAsync(class System.Fabric.ReplicaInformation replicaInfo, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IPrimaryReplicator#BuildReplicaAsync(System.Fabric.ReplicaInformation,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IPrimaryReplicator.BuildReplicaAsync(System.Fabric.ReplicaInformation,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaInfo" Type="System.Fabric.ReplicaInformation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaInfo">
          <para>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IPrimaryReplicator.OnDataLossAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;bool&gt; IPrimaryReplicator.OnDataLossAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; System.Fabric.IPrimaryReplicator.OnDataLossAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IPrimaryReplicator#OnDataLossAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IPrimaryReplicator.OnDataLossAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IPrimaryReplicator.RemoveReplica">
      <MemberSignature Language="C#" Value="void IPrimaryReplicator.RemoveReplica (long replicaId);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Fabric.IPrimaryReplicator.RemoveReplica(int64 replicaId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IPrimaryReplicator#RemoveReplica(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Sub RemoveReplica (replicaId As Long) Implements IPrimaryReplicator.RemoveReplica" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IPrimaryReplicator.RemoveReplica(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="replicaId">
          <para>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</para>
        </param>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <remarks>
          <para>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IPrimaryReplicator.UpdateCatchUpReplicaSetConfiguration">
      <MemberSignature Language="C#" Value="void IPrimaryReplicator.UpdateCatchUpReplicaSetConfiguration (System.Fabric.ReplicaSetConfiguration currentConfiguration, System.Fabric.ReplicaSetConfiguration previousConfiguration);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Fabric.IPrimaryReplicator.UpdateCatchUpReplicaSetConfiguration(class System.Fabric.ReplicaSetConfiguration currentConfiguration, class System.Fabric.ReplicaSetConfiguration previousConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IPrimaryReplicator#UpdateCatchUpReplicaSetConfiguration(System.Fabric.ReplicaSetConfiguration,System.Fabric.ReplicaSetConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Sub UpdateCatchUpReplicaSetConfiguration (currentConfiguration As ReplicaSetConfiguration, previousConfiguration As ReplicaSetConfiguration) Implements IPrimaryReplicator.UpdateCatchUpReplicaSetConfiguration" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IPrimaryReplicator.UpdateCatchUpReplicaSetConfiguration(System.Fabric.ReplicaSetConfiguration,System.Fabric.ReplicaSetConfiguration)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentConfiguration" Type="System.Fabric.ReplicaSetConfiguration" />
        <Parameter Name="previousConfiguration" Type="System.Fabric.ReplicaSetConfiguration" />
      </Parameters>
      <Docs>
        <param name="currentConfiguration">
          <para>Nur zur internen Verwendung.</para>
        </param>
        <param name="previousConfiguration">
          <para>Nur zur internen Verwendung.</para>
        </param>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IPrimaryReplicator.UpdateCurrentReplicaSetConfiguration">
      <MemberSignature Language="C#" Value="void IPrimaryReplicator.UpdateCurrentReplicaSetConfiguration (System.Fabric.ReplicaSetConfiguration currentConfiguration);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Fabric.IPrimaryReplicator.UpdateCurrentReplicaSetConfiguration(class System.Fabric.ReplicaSetConfiguration currentConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IPrimaryReplicator#UpdateCurrentReplicaSetConfiguration(System.Fabric.ReplicaSetConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Sub UpdateCurrentReplicaSetConfiguration (currentConfiguration As ReplicaSetConfiguration) Implements IPrimaryReplicator.UpdateCurrentReplicaSetConfiguration" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IPrimaryReplicator.UpdateCurrentReplicaSetConfiguration(System.Fabric.ReplicaSetConfiguration)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentConfiguration" Type="System.Fabric.ReplicaSetConfiguration" />
      </Parameters>
      <Docs>
        <param name="currentConfiguration">
          <para>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</para>
        </param>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <remarks>
          <para>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IPrimaryReplicator.WaitForCatchUpQuorumAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IPrimaryReplicator.WaitForCatchUpQuorumAsync (System.Fabric.ReplicaSetQuorumMode quorumMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task System.Fabric.IPrimaryReplicator.WaitForCatchUpQuorumAsync(valuetype System.Fabric.ReplicaSetQuorumMode quorumMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IPrimaryReplicator#WaitForCatchUpQuorumAsync(System.Fabric.ReplicaSetQuorumMode,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IPrimaryReplicator.WaitForCatchUpQuorumAsync(System.Fabric.ReplicaSetQuorumMode,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="quorumMode" Type="System.Fabric.ReplicaSetQuorumMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="quorumMode">
          <para>Nur zur internen Verwendung.</para>
        </param>
        <param name="cancellationToken">
          <para>Das CancellationToken-Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <returns>
          <para>Nur zur internen Verwendung.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IReplicator.Abort">
      <MemberSignature Language="C#" Value="void IReplicator.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Fabric.IReplicator.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IReplicator#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements IReplicator.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IReplicator.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <remarks />
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IReplicator.ChangeRoleAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReplicator.ChangeRoleAsync (System.Fabric.Epoch epoch, System.Fabric.ReplicaRole role, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task System.Fabric.IReplicator.ChangeRoleAsync(valuetype System.Fabric.Epoch epoch, valuetype System.Fabric.ReplicaRole role, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IReplicator#ChangeRoleAsync(System.Fabric.Epoch,System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IReplicator.ChangeRoleAsync(System.Fabric.Epoch,System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="role" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</para>
        </param>
        <param name="role">
          <para>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IReplicator.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReplicator.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task System.Fabric.IReplicator.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IReplicator#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IReplicator.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IReplicator.GetCatchUpCapability">
      <MemberSignature Language="C#" Value="long IReplicator.GetCatchUpCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance int64 System.Fabric.IReplicator.GetCatchUpCapability() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IReplicator#GetCatchUpCapability" />
      <MemberSignature Language="VB.NET" Value="Function GetCatchUpCapability () As Long Implements IReplicator.GetCatchUpCapability" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IReplicator.GetCatchUpCapability</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <returns>
          <para>Nur zur internen Verwendung.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IReplicator.GetCurrentProgress">
      <MemberSignature Language="C#" Value="long IReplicator.GetCurrentProgress ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance int64 System.Fabric.IReplicator.GetCurrentProgress() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IReplicator#GetCurrentProgress" />
      <MemberSignature Language="VB.NET" Value="Function GetCurrentProgress () As Long Implements IReplicator.GetCurrentProgress" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IReplicator.GetCurrentProgress</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <returns>
          <para>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IReplicator.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;string&gt; IReplicator.OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; System.Fabric.IReplicator.OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IReplicator#OpenAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IReplicator.OpenAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IReplicator.UpdateEpochAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReplicator.UpdateEpochAsync (System.Fabric.Epoch epoch, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task System.Fabric.IReplicator.UpdateEpochAsync(valuetype System.Fabric.Epoch epoch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IReplicator#UpdateEpochAsync(System.Fabric.Epoch,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IReplicator.UpdateEpochAsync(System.Fabric.Epoch,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <returns>
          <para>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnknownSequenceNumber">
      <MemberSignature Language="C#" Value="public const long UnknownSequenceNumber = -1;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int64 UnknownSequenceNumber = (-1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FabricReplicator.UnknownSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Const UnknownSequenceNumber As Long  = -1" />
      <MemberSignature Language="F#" Value="val mutable UnknownSequenceNumber : int64" Usage="System.Fabric.FabricReplicator.UnknownSequenceNumber" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <MemberValue>-1</MemberValue>
      <Docs>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>