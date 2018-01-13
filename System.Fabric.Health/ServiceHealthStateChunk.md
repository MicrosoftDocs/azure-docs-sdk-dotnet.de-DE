<Type Name="ServiceHealthStateChunk" FullName="System.Fabric.Health.ServiceHealthStateChunk">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealthStateChunk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealthStateChunk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealthStateChunk" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealthStateChunk" />
  <TypeSignature Language="F#" Value="type ServiceHealthStateChunk = class" />
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
            Stellt ein Service Health Status Segment, das grundlegende Zustandsinformationen zum Dienst enthält.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateChunk.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.ServiceHealthStateChunk.HealthState" />
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
            Ruft ab, der aggregierte Integritätszustand des Diensts, berechnet anhand der alle gemeldeten integritätsereignisse, seinen untergeordneten Elementen und einer anwendungsintegritäts-Richtlinie.
            </summary>
        <value>Der aggregierte Integritätszustand des Diensts.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.PartitionHealthStateChunkList PartitionHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.PartitionHealthStateChunkList PartitionHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateChunk.PartitionHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionHealthStateChunks As PartitionHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.PartitionHealthStateChunks : System.Fabric.Health.PartitionHealthStateChunkList" Usage="System.Fabric.Health.ServiceHealthStateChunk.PartitionHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.PartitionHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der partitionsintegrität Service State-Segmente, die die Eingabefilter respektieren ab.
            </summary>
        <value>Die Liste der Partition Health Status Blöcke, die die Eingabefilter berücksichtigen.</value>
        <remarks>
          <para>Standardmäßig sind keine untergeordneten Elemente in den Ergebnissen enthalten. Benutzer können anfordern, einige untergeordnete Elemente basierend auf den gewünschten Zustand oder andere Informationen einschließen. Beispielsweise können Benutzer auf alle Partitionen enthalten ist, Status Integritätsfehler anfordern.
            Unabhängig von den Filterwert werden alle untergeordneten Elemente verwendet, um aggregiert den Dienststatus zu berechnen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateChunk.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Health.ServiceHealthStateChunk.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Dienstnamen, der den Dienst eindeutig identifiziert.
            </summary>
        <value>Der Name des Diensts.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateChunk.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceHealthStateChunk.ToString " />
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
            Erstellt eine zeichenfolgenbeschreibung des Segments Service Health Status an.
            </summary>
        <returns>Die zeichenfolgenbeschreibung des Segments Status Integrität.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>