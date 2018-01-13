<Type Name="DeployedStatefulServiceReplicaDetail" FullName="System.Fabric.Query.DeployedStatefulServiceReplicaDetail">
  <TypeSignature Language="C#" Value="public sealed class DeployedStatefulServiceReplicaDetail : System.Fabric.Query.DeployedServiceReplicaDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedStatefulServiceReplicaDetail extends System.Fabric.Query.DeployedServiceReplicaDetail" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedStatefulServiceReplicaDetail" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedStatefulServiceReplicaDetail&#xA;Inherits DeployedServiceReplicaDetail" />
  <TypeSignature Language="F#" Value="type DeployedStatefulServiceReplicaDetail = class&#xA;    inherit DeployedServiceReplicaDetail" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.DeployedServiceReplicaDetail</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt die Informationen über ein zustandsbehaftetes Replikat in einem Codepaket ausgeführt wird.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedStatefulServiceReplicaDetail ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.DeployedStatefulServiceReplicaDetail" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentReplicatorOperation">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicatorOperationName CurrentReplicatorOperation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ReplicatorOperationName CurrentReplicatorOperation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.CurrentReplicatorOperation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentReplicatorOperation As ReplicatorOperationName" />
      <MemberSignature Language="F#" Value="member this.CurrentReplicatorOperation : System.Fabric.Query.ReplicatorOperationName" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.CurrentReplicatorOperation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die aktuellen-APIs auf Replikator ausgeführt wird.</para>
        </summary>
        <value>
          <para>Die aktuelle-APIs auf Replikator ausgeführt wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedServiceReplica">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.DeployedStatefulServiceReplica DeployedServiceReplica { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.DeployedStatefulServiceReplica DeployedServiceReplica" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.DeployedServiceReplica" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedServiceReplica As DeployedStatefulServiceReplica" />
      <MemberSignature Language="F#" Value="member this.DeployedServiceReplica : System.Fabric.Query.DeployedStatefulServiceReplica" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.DeployedServiceReplica" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.DeployedStatefulServiceReplica</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft zusätzliche Details zu den bereitgestellten dienstreplikats wie replikatrolle, Host-Prozess-ID, Informationen zur Neukonfiguration ab.</para>
          <value>Replikat-Details.</value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionAccessStatus ReadStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PartitionAccessStatus ReadStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReadStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadStatus As PartitionAccessStatus" />
      <MemberSignature Language="F#" Value="member this.ReadStatus : System.Fabric.PartitionAccessStatus" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReadStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den aktuellen Status für dieses Replikat zu lesen.</para>
        </summary>
        <value>
          <para>Aktuellen Status für dieses Replikat zu lesen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaId">
      <MemberSignature Language="C#" Value="public long ReplicaId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicaId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaId : int64" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicaId" />
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
          <para>Ruft die Replikat-ID für dieses Replikat.</para>
        </summary>
        <value>
          <para>Die Replikat-ID</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicaStatus ReplicaStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ReplicaStatus ReplicaStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicaStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaStatus As ReplicaStatus" />
      <MemberSignature Language="F#" Value="member this.ReplicaStatus : System.Fabric.Query.ReplicaStatus" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicaStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicaStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, des Status des aktuellen Replikats.
            </summary>
        <value>Der Status des Replikats.</value>
        <remarks>Derzeit nur Replikate des Typs <see cref="T:System.Fabric.KeyValueStoreReplica" /> Statusdetails Abfrage erzeugt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicatorStatus ReplicatorStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ReplicatorStatus ReplicatorStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicatorStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicatorStatus As ReplicatorStatus" />
      <MemberSignature Language="F#" Value="member this.ReplicatorStatus : System.Fabric.Query.ReplicatorStatus" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicatorStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Informationen zur Replikator ab, wenn das Replikat Replikator Fabric-Dienst verwendet wird</para>
        </summary>
        <value>
          <para>Der Replikator-Status.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionAccessStatus WriteStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PartitionAccessStatus WriteStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.WriteStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteStatus As PartitionAccessStatus" />
      <MemberSignature Language="F#" Value="member this.WriteStatus : System.Fabric.PartitionAccessStatus" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.WriteStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den aktuellen Schreibstatus des Replikats ab.</para>
        </summary>
        <value>
          <para>Der aktuellen Status des Replikats geschrieben werden.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>