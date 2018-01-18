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
            <span data-ttu-id="e1339-101">Stellt ein Service Health Status Segment, das grundlegende Zustandsinformationen zum Dienst enthält.</span><span class="sxs-lookup"><span data-stu-id="e1339-101">Represents a service health state chunk, which contains basic health information about the service.</span></span>
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
            <span data-ttu-id="e1339-102">Ruft ab, der aggregierte Integritätszustand des Diensts, berechnet anhand der alle gemeldeten integritätsereignisse, seinen untergeordneten Elementen und einer anwendungsintegritäts-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="e1339-102">Gets the aggregated health state of the service, computed based on all reported health events, its children and the application health policy.</span></span>
            </summary>
        <value><span data-ttu-id="e1339-103">Der aggregierte Integritätszustand des Diensts.</span><span class="sxs-lookup"><span data-stu-id="e1339-103">The aggregated health state of the service.</span></span></value>
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
            <span data-ttu-id="e1339-104">Ruft die Liste der partitionsintegrität Service State-Segmente, die die Eingabefilter respektieren ab.</span><span class="sxs-lookup"><span data-stu-id="e1339-104">Gets the list of the service partition health state chunks that respect the input filters.</span></span>
            </summary>
        <value><span data-ttu-id="e1339-105">Die Liste der Partition Health Status Blöcke, die die Eingabefilter berücksichtigen.</span><span class="sxs-lookup"><span data-stu-id="e1339-105">The list of the partition health state chunks that respect the input filters.</span></span></value>
        <remarks>
          <para><span data-ttu-id="e1339-106">Standardmäßig sind keine untergeordneten Elemente in den Ergebnissen enthalten.</span><span class="sxs-lookup"><span data-stu-id="e1339-106">By default, no children are included in results.</span></span> <span data-ttu-id="e1339-107">Benutzer können anfordern, einige untergeordnete Elemente basierend auf den gewünschten Zustand oder andere Informationen einschließen.</span><span class="sxs-lookup"><span data-stu-id="e1339-107">Users can request to include some children based on desired health or other information.</span></span> <span data-ttu-id="e1339-108">Beispielsweise können Benutzer auf alle Partitionen enthalten ist, Status Integritätsfehler anfordern.</span><span class="sxs-lookup"><span data-stu-id="e1339-108">For example, users can request to include all partitions that have health state error.</span></span>
            <span data-ttu-id="e1339-109">Unabhängig von den Filterwert werden alle untergeordneten Elemente verwendet, um aggregiert den Dienststatus zu berechnen.</span><span class="sxs-lookup"><span data-stu-id="e1339-109">Regardless of filter value, all children are used to compute service aggregated health.</span></span></para>
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
            <span data-ttu-id="e1339-110">Ruft den Dienstnamen, der den Dienst eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="e1339-110">Gets the service name, which uniquely identifies the service.</span></span>
            </summary>
        <value><span data-ttu-id="e1339-111">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="e1339-111">The service name.</span></span></value>
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
            <span data-ttu-id="e1339-112">Erstellt eine zeichenfolgenbeschreibung des Segments Service Health Status an.</span><span class="sxs-lookup"><span data-stu-id="e1339-112">Creates a string description of the service health state chunk.</span></span>
            </summary>
        <returns><span data-ttu-id="e1339-113">Die zeichenfolgenbeschreibung des Segments Status Integrität.</span><span class="sxs-lookup"><span data-stu-id="e1339-113">String description of the health state chunk.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>