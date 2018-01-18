<Type Name="DeployedApplicationHealthStateChunk" FullName="System.Fabric.Health.DeployedApplicationHealthStateChunk">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealthStateChunk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealthStateChunk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationHealthStateChunk" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealthStateChunk" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthStateChunk = class" />
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
            <span data-ttu-id="5e58a-101">Stellt eine bereitgestellte Anwendung Health Status Block, die grundlegende Zustandsinformationen zur der bereitgestellten Anwendung enthält.</span><span class="sxs-lookup"><span data-stu-id="5e58a-101">Represents a deployed application health state chunk, which contains basic health information about the deployed application.</span></span>
            <span data-ttu-id="5e58a-102">Sie ist als untergeordnetes Element von einer Anwendung aus.</span><span class="sxs-lookup"><span data-stu-id="5e58a-102">It is included as child of an application.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeployedServicePackageHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedServicePackageHealthStateChunkList DeployedServicePackageHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedServicePackageHealthStateChunkList DeployedServicePackageHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateChunk.DeployedServicePackageHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedServicePackageHealthStateChunks As DeployedServicePackageHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.DeployedServicePackageHealthStateChunks : System.Fabric.Health.DeployedServicePackageHealthStateChunkList" Usage="System.Fabric.Health.DeployedApplicationHealthStateChunk.DeployedServicePackageHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedServicePackageHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5e58a-103">Ruft die Liste der bereitgestellten Dienst Paket Integrität Zustand Blöcke untergeordneten Elemente, die die Eingabefilter berücksichtigen.</span><span class="sxs-lookup"><span data-stu-id="5e58a-103">Gets the list of the deployed service package health state chunks children that respect the input filters.</span></span>
            </summary>
        <value><span data-ttu-id="5e58a-104">Die Liste der bereitgestellten Dienst Paket Replikat-Integritätsstatus Blöcken untergeordnete Elemente, die die Eingabefilter berücksichtigen.</span><span class="sxs-lookup"><span data-stu-id="5e58a-104">The list of the deployed service package  replica health state chunks children that respect the input filters.</span></span></value>
        <remarks>
          <para><span data-ttu-id="5e58a-105">Standardmäßig sind keine untergeordneten Elemente in den Ergebnissen enthalten.</span><span class="sxs-lookup"><span data-stu-id="5e58a-105">By default, no children are included in results.</span></span> <span data-ttu-id="5e58a-106">Benutzer können anfordern, einige untergeordnete Elemente basierend auf den gewünschten Zustand oder andere Informationen einschließen.</span><span class="sxs-lookup"><span data-stu-id="5e58a-106">Users can request to include some children based on desired health or other information.</span></span> <span data-ttu-id="5e58a-107">Beispielsweise können Benutzer auf alle bereitgestellten dienstpakete enthalten ist, Status Integritätsfehler anfordern.</span><span class="sxs-lookup"><span data-stu-id="5e58a-107">For example, users can request to include all deployed service packages that have health state error.</span></span>
            <span data-ttu-id="5e58a-108">Unabhängig von den Filterwert werden alle untergeordneten Elemente aggregiert Entitätsintegrität berechnet verwendet.</span><span class="sxs-lookup"><span data-stu-id="5e58a-108">Regardless of filter value, all children are used to compute the entity aggregated health.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateChunk.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.DeployedApplicationHealthStateChunk.HealthState" />
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
            <span data-ttu-id="5e58a-109">Ruft ab, der aggregierte Integritätszustand der bereitgestellten Anwendung berechnet anhand alle gemeldeten integritätsereignisse, die untergeordneten Elemente und einer anwendungsintegritäts-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="5e58a-109">Gets the aggregated health state of the deployed application, computed based on all reported health events, the children and the application health policy.</span></span>
            </summary>
        <value><span data-ttu-id="5e58a-110">Der aggregierte Integritätszustand der bereitgestellten Anwendung.</span><span class="sxs-lookup"><span data-stu-id="5e58a-110">The aggregated health state of the deployed application.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateChunk.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.DeployedApplicationHealthStateChunk.NodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5e58a-111">Ruft den Knotennamen ab.</span><span class="sxs-lookup"><span data-stu-id="5e58a-111">Gets the node name.</span></span>
            </summary>
        <value><span data-ttu-id="5e58a-112">Der Knotenname.</span><span class="sxs-lookup"><span data-stu-id="5e58a-112">The node name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthStateChunk.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedApplicationHealthStateChunk.ToString " />
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
            <span data-ttu-id="5e58a-113">Erstellt eine zeichenfolgenbeschreibung des Segments Status Integrität an.</span><span class="sxs-lookup"><span data-stu-id="5e58a-113">Creates a string description of the health state chunk.</span></span>
            </summary>
        <returns><span data-ttu-id="5e58a-114">Die zeichenfolgenbeschreibung des Segments Status Integrität.</span><span class="sxs-lookup"><span data-stu-id="5e58a-114">String description of the health state chunk.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>