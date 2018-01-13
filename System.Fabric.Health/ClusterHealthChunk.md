<Type Name="ClusterHealthChunk" FullName="System.Fabric.Health.ClusterHealthChunk">
  <TypeSignature Language="C#" Value="public sealed class ClusterHealthChunk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterHealthChunk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ClusterHealthChunk" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterHealthChunk" />
  <TypeSignature Language="F#" Value="type ClusterHealthChunk = class" />
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
            Stellt das Segment der Cluster-Status, das Zustandsinformationen zur Cluster enthält.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthStateChunkList ApplicationHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthStateChunkList ApplicationHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthChunk.ApplicationHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationHealthStateChunks As ApplicationHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthStateChunks : System.Fabric.Health.ApplicationHealthStateChunkList" Usage="System.Fabric.Health.ClusterHealthChunk.ApplicationHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der Anwendungsintegrität Status-Segmente, die die Eingabefilter respektieren ab.
            </summary>
        <value>Die Liste der Anwendung Health Status Blöcke, die die Eingabefilter berücksichtigen.</value>
        <remarks>
          <para>Standardmäßig sind keine untergeordneten Elemente in den Ergebnissen enthalten. Benutzer können anfordern, einige untergeordnete Elemente basierend auf den gewünschten Zustand oder andere Informationen einschließen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthChunk.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.ClusterHealthChunk.HealthState" />
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
            Ruft den Integritätsstatus des Clusters aggregiert.
            </summary>
        <value>Aggregierter Integritätszustand des Clusters.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.NodeHealthStateChunkList NodeHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.NodeHealthStateChunkList NodeHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthChunk.NodeHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeHealthStateChunks As NodeHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.NodeHealthStateChunks : System.Fabric.Health.NodeHealthStateChunkList" Usage="System.Fabric.Health.ClusterHealthChunk.NodeHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.NodeHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der Knoten Health-Status-Segmente, die die Eingabefilter respektieren ab.
            </summary>
        <value>Die Liste der Knoten Health Status Blöcke, die die Eingabefilter berücksichtigen.</value>
        <remarks>
          <para>Standardmäßig sind keine untergeordneten Elemente in den Ergebnissen enthalten. Benutzer können anfordern, einige untergeordnete Elemente basierend auf den gewünschten Zustand oder andere Informationen einschließen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthChunk.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterHealthChunk.ToString " />
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
            Erstellt eine zeichenfolgenbeschreibung des Cluster-Blocks.
            </summary>
        <returns>Die zeichenfolgenbeschreibung des Cluster-Blocks.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>