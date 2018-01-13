<Type Name="DeployedStatefulServiceReplica" FullName="System.Fabric.Query.DeployedStatefulServiceReplica">
  <TypeSignature Language="C#" Value="public sealed class DeployedStatefulServiceReplica : System.Fabric.Query.DeployedServiceReplica" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedStatefulServiceReplica extends System.Fabric.Query.DeployedServiceReplica" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedStatefulServiceReplica" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedStatefulServiceReplica&#xA;Inherits DeployedServiceReplica" />
  <TypeSignature Language="F#" Value="type DeployedStatefulServiceReplica = class&#xA;    inherit DeployedServiceReplica" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.DeployedServiceReplica</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt eine bereitgestellte statusbehafteten dienstreplikats dar.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedStatefulServiceReplica ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedStatefulServiceReplica.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.DeployedStatefulServiceReplica" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReconfigurationInformation">
      <MemberSignature Language="C#" Value="public System.Fabric.ReconfigurationInformation ReconfigurationInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ReconfigurationInformation ReconfigurationInformation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplica.ReconfigurationInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReconfigurationInformation As ReconfigurationInformation" />
      <MemberSignature Language="F#" Value="member this.ReconfigurationInformation : System.Fabric.ReconfigurationInformation" Usage="System.Fabric.Query.DeployedStatefulServiceReplica.ReconfigurationInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft zusätzliche Informationen zu den aktuellen Neukonfiguration ab, wie die vorherige Konfigurationsrolle, Neukonfiguration Typ, Phase Neukonfiguration und die Neukonfiguration Datum-Zeit starten.</para>
          <value>Neukonfiguration Informationen.</value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaId">
      <MemberSignature Language="C#" Value="public long ReplicaId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplica.ReplicaId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaId : int64" Usage="System.Fabric.Query.DeployedStatefulServiceReplica.ReplicaId" />
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
          <para>Ruft die Replikat-ID ab.</para>
        </summary>
        <value>
          <para>Die Replikat-ID</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaRole">
      <MemberSignature Language="C#" Value="public System.Fabric.ReplicaRole ReplicaRole { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ReplicaRole ReplicaRole" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplica.ReplicaRole" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaRole As ReplicaRole" />
      <MemberSignature Language="F#" Value="member this.ReplicaRole : System.Fabric.ReplicaRole" Usage="System.Fabric.Query.DeployedStatefulServiceReplica.ReplicaRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die aktuellen replikatrolle ab.</para>
        </summary>
        <value>
          <para>Die replikatrolle.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>