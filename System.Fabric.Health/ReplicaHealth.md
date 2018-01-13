<Type Name="ReplicaHealth" FullName="System.Fabric.Health.ReplicaHealth">
  <TypeSignature Language="C#" Value="public abstract class ReplicaHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ReplicaHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ReplicaHealth" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ReplicaHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type ReplicaHealth = class&#xA;    inherit EntityHealth" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealth</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.StatefulServiceReplicaHealth))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.StatelessServiceInstanceHealth))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>Beschreibt die Integrität eines zustandsbehafteten dienstreplikats oder einer zustandslosen Dienstinstanz aus, wie vom <see cref="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Fabric.Description.ReplicaHealthQueryDescription)" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public long Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Id" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealth.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As Long" />
      <MemberSignature Language="F#" Value="member this.Id : int64" Usage="System.Fabric.Health.ReplicaHealth.Id" />
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
          <para>Ruft die statusbehafteten dienstreplikats oder die ID der statusfreien Dienstinstanz-ID</para>
        </summary>
        <value>
          <para>Die zustandsbehaftetes Replikat oder zustandslose Instanz-ID</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealth.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As ServiceKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.Query.ServiceKind" Usage="System.Fabric.Health.ReplicaHealth.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Art des Replikats, zustandslose oder zustandsbehaftete ab. Auf dieser Grundlage der replikatintegrität konvertiert werden kann, entweder <see cref="T:System.Fabric.Health.StatefulServiceReplicaHealth" /> oder <see cref="T:System.Fabric.Health.StatelessServiceInstanceHealth" />.</para>
        </summary>
        <value>
          <para>Art des Diensts, der angibt, ob das Replikat zustandsbehaftete oder zustandslos ist.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealth.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Health.ReplicaHealth.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Partitionsbezeichner ab.</para>
        </summary>
        <value>
          <para>Die Partitions-ID.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="replicaHealth.ToString " />
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
            Ruft eine Zeichenfolgendarstellung der <see cref="T:System.Fabric.Health.ReplicaHealth" />.
            </summary>
        <returns>Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Health.ReplicaHealth" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>