<Type Name="DeployedStatelessServiceInstanceDetail" FullName="System.Fabric.Query.DeployedStatelessServiceInstanceDetail">
  <TypeSignature Language="C#" Value="public sealed class DeployedStatelessServiceInstanceDetail : System.Fabric.Query.DeployedServiceReplicaDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedStatelessServiceInstanceDetail extends System.Fabric.Query.DeployedServiceReplicaDetail" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedStatelessServiceInstanceDetail" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedStatelessServiceInstanceDetail&#xA;Inherits DeployedServiceReplicaDetail" />
  <TypeSignature Language="F#" Value="type DeployedStatelessServiceInstanceDetail = class&#xA;    inherit DeployedServiceReplicaDetail" />
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
      <para>Stellt die Informationen über eine zustandslose Instanz in einem Codepaket ausgeführt wird.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedStatelessServiceInstanceDetail ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedStatelessServiceInstanceDetail.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.DeployedStatelessServiceInstanceDetail" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedServiceReplicaInstance">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.DeployedStatelessServiceInstance DeployedServiceReplicaInstance { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.DeployedStatelessServiceInstance DeployedServiceReplicaInstance" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatelessServiceInstanceDetail.DeployedServiceReplicaInstance" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedServiceReplicaInstance As DeployedStatelessServiceInstance" />
      <MemberSignature Language="F#" Value="member this.DeployedServiceReplicaInstance : System.Fabric.Query.DeployedStatelessServiceInstance" Usage="System.Fabric.Query.DeployedStatelessServiceInstanceDetail.DeployedServiceReplicaInstance" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.DeployedStatelessServiceInstance</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft zusätzliche Details zu bereitgestellten Dienst-Instanz wie der Host-Prozess-Id, codepaketname ab.</para>
          <value>Replikat-Details.</value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceId">
      <MemberSignature Language="C#" Value="public long InstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 InstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatelessServiceInstanceDetail.InstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.InstanceId : int64" Usage="System.Fabric.Query.DeployedStatelessServiceInstanceDetail.InstanceId" />
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
          <para>Ruft ab oder legt die Instanz-ID dieser Instanz.</para>
        </summary>
        <value>
          <para>Der Bezeichner der dieser Instanz.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>