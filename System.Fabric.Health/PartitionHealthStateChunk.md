<Type Name="PartitionHealthStateChunk" FullName="System.Fabric.Health.PartitionHealthStateChunk">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealthStateChunk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealthStateChunk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionHealthStateChunk" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealthStateChunk" />
  <TypeSignature Language="F#" Value="type PartitionHealthStateChunk = class" />
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
            Stellt eine Partition Health Status Segment, das grundlegende Zustandsinformationen zur Partition enthält.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateChunk.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.PartitionHealthStateChunk.HealthState" />
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
            Ruft die Partition Integritätsstatus, berechnet aggregiert basierend auf alle gemeldeten integritätsereignisse, untergeordneten Elemente Replikat und einer anwendungsintegritäts-Richtlinie.
            </summary>
        <value>Der aggregierte Integritätszustand der Partition.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateChunk.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Health.PartitionHealthStateChunk.PartitionId" />
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
            Ruft die Partitions-Id ab.
            </summary>
        <value>Die Partitions-Id.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ReplicaHealthStateChunkList ReplicaHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ReplicaHealthStateChunkList ReplicaHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateChunk.ReplicaHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaHealthStateChunks As ReplicaHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.ReplicaHealthStateChunks : System.Fabric.Health.ReplicaHealthStateChunkList" Usage="System.Fabric.Health.PartitionHealthStateChunk.ReplicaHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ReplicaHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der Partition Replikat Health Status Segmente, die die Eingabefilter respektieren ab.
            </summary>
        <value>Die Liste der Integrität Partition-Replikat-Status-Segmente, die die Eingabefilter berücksichtigen.</value>
        <remarks>
          <para>Standardmäßig sind keine untergeordneten Elemente in den Ergebnissen enthalten. Benutzer können anfordern, einige untergeordnete Elemente basierend auf den gewünschten Zustand oder andere Informationen einschließen. Beispielsweise können Benutzer anfordern, um alle Replikate enthalten, die Integrität Statusfehler aufweisen.
            Unabhängig von den Filterwert werden alle untergeordneten Elemente aggregiert partitionsintegrität berechnet verwendet.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthStateChunk.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionHealthStateChunk.ToString " />
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
            Erstellt eine zeichenfolgenbeschreibung des Segments Status Integrität Partition an.
            </summary>
        <returns>Die zeichenfolgenbeschreibung des Segments Status Integrität.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>