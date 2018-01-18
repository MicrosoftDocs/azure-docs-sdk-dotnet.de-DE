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
            <span data-ttu-id="659df-101">Stellt das Segment der Cluster-Status, das Zustandsinformationen zur Cluster enthält.</span><span class="sxs-lookup"><span data-stu-id="659df-101">Represents the cluster state chunk, which includes health information about the cluster.</span></span>
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
            <span data-ttu-id="659df-102">Ruft die Liste der Anwendungsintegrität Status-Segmente, die die Eingabefilter respektieren ab.</span><span class="sxs-lookup"><span data-stu-id="659df-102">Gets the list of the application health state chunks that respect the input filters.</span></span>
            </summary>
        <value><span data-ttu-id="659df-103">Die Liste der Anwendung Health Status Blöcke, die die Eingabefilter berücksichtigen.</span><span class="sxs-lookup"><span data-stu-id="659df-103">The list of the application health state chunks that respect the input filters.</span></span></value>
        <remarks>
          <para><span data-ttu-id="659df-104">Standardmäßig sind keine untergeordneten Elemente in den Ergebnissen enthalten.</span><span class="sxs-lookup"><span data-stu-id="659df-104">By default, no children are included in results.</span></span> <span data-ttu-id="659df-105">Benutzer können anfordern, einige untergeordnete Elemente basierend auf den gewünschten Zustand oder andere Informationen einschließen.</span><span class="sxs-lookup"><span data-stu-id="659df-105">Users can request to include some children based on desired health or other information.</span></span></para>
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
            <span data-ttu-id="659df-106">Ruft den Integritätsstatus des Clusters aggregiert.</span><span class="sxs-lookup"><span data-stu-id="659df-106">Gets the cluster aggregated health state.</span></span>
            </summary>
        <value><span data-ttu-id="659df-107">Aggregierter Integritätszustand des Clusters.</span><span class="sxs-lookup"><span data-stu-id="659df-107">The cluster aggregated health state.</span></span></value>
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
            <span data-ttu-id="659df-108">Ruft die Liste der Knoten Health-Status-Segmente, die die Eingabefilter respektieren ab.</span><span class="sxs-lookup"><span data-stu-id="659df-108">Gets the list of the node health state chunks that respect the input filters.</span></span>
            </summary>
        <value><span data-ttu-id="659df-109">Die Liste der Knoten Health Status Blöcke, die die Eingabefilter berücksichtigen.</span><span class="sxs-lookup"><span data-stu-id="659df-109">The list of the node health state chunks that respect the input filters.</span></span></value>
        <remarks>
          <para><span data-ttu-id="659df-110">Standardmäßig sind keine untergeordneten Elemente in den Ergebnissen enthalten.</span><span class="sxs-lookup"><span data-stu-id="659df-110">By default, no children are included in results.</span></span> <span data-ttu-id="659df-111">Benutzer können anfordern, einige untergeordnete Elemente basierend auf den gewünschten Zustand oder andere Informationen einschließen.</span><span class="sxs-lookup"><span data-stu-id="659df-111">Users can request to include some children based on desired health or other information.</span></span></para>
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
            <span data-ttu-id="659df-112">Erstellt eine zeichenfolgenbeschreibung des Cluster-Blocks.</span><span class="sxs-lookup"><span data-stu-id="659df-112">Creates a string description of the cluster chunk.</span></span>
            </summary>
        <returns><span data-ttu-id="659df-113">Die zeichenfolgenbeschreibung des Cluster-Blocks.</span><span class="sxs-lookup"><span data-stu-id="659df-113">String description of the cluster chunk.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>