<Type Name="ApplicationHealthStateChunk" FullName="System.Fabric.Health.ApplicationHealthStateChunk">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthStateChunk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthStateChunk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthStateChunk" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthStateChunk" />
  <TypeSignature Language="F#" Value="type ApplicationHealthStateChunk = class" />
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
            <span data-ttu-id="335e5-101">Stellt eine Anwendung Health Status Segment, das grundlegende Zustandsinformationen zur Anwendung enthält.</span><span class="sxs-lookup"><span data-stu-id="335e5-101">Represents an application health state chunk, which contains basic health information about the application.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateChunk.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.ApplicationHealthStateChunk.ApplicationName" />
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
            <span data-ttu-id="335e5-102">Ruft den Namen der Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="335e5-102">Gets the application name.</span></span>
            </summary>
        <value><span data-ttu-id="335e5-103">Der Anwendungsname.</span><span class="sxs-lookup"><span data-stu-id="335e5-103">The application name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateChunk.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.Health.ApplicationHealthStateChunk.ApplicationTypeName" />
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
            <span data-ttu-id="335e5-104">Ruft den Typnamen der Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="335e5-104">Gets the application type name.</span></span>
            </summary>
        <value><span data-ttu-id="335e5-105">Der Name des Anwendungstyps.</span><span class="sxs-lookup"><span data-stu-id="335e5-105">The application type name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedApplicationHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedApplicationHealthStateChunkList DeployedApplicationHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedApplicationHealthStateChunkList DeployedApplicationHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateChunk.DeployedApplicationHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedApplicationHealthStateChunks As DeployedApplicationHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.DeployedApplicationHealthStateChunks : System.Fabric.Health.DeployedApplicationHealthStateChunkList" Usage="System.Fabric.Health.ApplicationHealthStateChunk.DeployedApplicationHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedApplicationHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="335e5-106">Ruft die Liste der bereitgestellten Anwendung Health Status Blöcke, die die Eingabefilter berücksichtigen.</span><span class="sxs-lookup"><span data-stu-id="335e5-106">Gets the list of the deployed application health state chunks that respect the input filters.</span></span>
            </summary>
        <value><span data-ttu-id="335e5-107">Die Liste der bereitgestellten Anwendung Health Status Blöcke, die die Eingabefilter berücksichtigen.</span><span class="sxs-lookup"><span data-stu-id="335e5-107">The list of the deployed application health state chunks that respect the input filters.</span></span></value>
        <remarks>
          <para><span data-ttu-id="335e5-108">Standardmäßig sind keine untergeordneten Elemente in den Ergebnissen enthalten.</span><span class="sxs-lookup"><span data-stu-id="335e5-108">By default, no children are included in results.</span></span> <span data-ttu-id="335e5-109">Benutzer können anfordern, einige untergeordnete Elemente basierend auf den gewünschten Zustand oder andere Informationen einschließen.</span><span class="sxs-lookup"><span data-stu-id="335e5-109">Users can request to include some children based on desired health or other information.</span></span> <span data-ttu-id="335e5-110">Beispielsweise können Benutzer auf alle bereitgestellte Anwendungen enthalten ist, Status Integritätsfehler anfordern.</span><span class="sxs-lookup"><span data-stu-id="335e5-110">For example, users can request to include all deployed applications that have health state error.</span></span>
            <span data-ttu-id="335e5-111">Unabhängig von den Filterwert werden alle untergeordneten Elemente aggregiert Anwendungsintegrität berechnet verwendet.</span><span class="sxs-lookup"><span data-stu-id="335e5-111">Regardless of filter value, all children are used to compute application aggregated health.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateChunk.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.ApplicationHealthStateChunk.HealthState" />
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
            <span data-ttu-id="335e5-112">Ruft die Anwendung Integritätsstatus, berechnet aggregiert basierend auf alle gemeldeten integritätsereignisse, die untergeordneten Elemente und einer anwendungsintegritäts-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="335e5-112">Gets the application aggregated health state, computed based on all reported health events, the children and the application health policy.</span></span>
            </summary>
        <value><span data-ttu-id="335e5-113">Der Integritätsstatus der Anwendung aggregiert.</span><span class="sxs-lookup"><span data-stu-id="335e5-113">The application aggregated health state.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ServiceHealthStateChunkList ServiceHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ServiceHealthStateChunkList ServiceHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateChunk.ServiceHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceHealthStateChunks As ServiceHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.ServiceHealthStateChunks : System.Fabric.Health.ServiceHealthStateChunkList" Usage="System.Fabric.Health.ApplicationHealthStateChunk.ServiceHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ServiceHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="335e5-114">Ruft die Liste der dienstintegrität Zustand Segmente, die die Eingabefilter berücksichtigen.</span><span class="sxs-lookup"><span data-stu-id="335e5-114">Gets the list of the service health state chunks that respect the input filters.</span></span>
            </summary>
        <value><span data-ttu-id="335e5-115">Die Liste der Service Health Status Blöcke, die die Eingabefilter berücksichtigen.</span><span class="sxs-lookup"><span data-stu-id="335e5-115">The list of the service health state chunks that respect the input filters.</span></span></value>
        <remarks>
          <para><span data-ttu-id="335e5-116">Standardmäßig sind keine untergeordneten Elemente in den Ergebnissen enthalten.</span><span class="sxs-lookup"><span data-stu-id="335e5-116">By default, no children are included in results.</span></span> <span data-ttu-id="335e5-117">Benutzer können anfordern, einige untergeordnete Elemente basierend auf den gewünschten Zustand oder andere Informationen einschließen.</span><span class="sxs-lookup"><span data-stu-id="335e5-117">Users can request to include some children based on desired health or other information.</span></span> <span data-ttu-id="335e5-118">Beispielsweise können Benutzer auf alle Dienste enthalten ist, Status Integritätsfehler anfordern.</span><span class="sxs-lookup"><span data-stu-id="335e5-118">For example, users can request to include all services that have health state error.</span></span>
            <span data-ttu-id="335e5-119">Unabhängig von den Filterwert werden alle untergeordneten Elemente aggregiert Anwendungsintegrität berechnet verwendet.</span><span class="sxs-lookup"><span data-stu-id="335e5-119">Regardless of filter value, all children are used to compute application aggregated health.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateChunk.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthStateChunk.ToString " />
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
            <span data-ttu-id="335e5-120">Erstellt eine zeichenfolgenbeschreibung des Segments Status Integrität an.</span><span class="sxs-lookup"><span data-stu-id="335e5-120">Creates a string description of the health state chunk.</span></span>
            </summary>
        <returns><span data-ttu-id="335e5-121">Die zeichenfolgenbeschreibung des Segments Status Integrität.</span><span class="sxs-lookup"><span data-stu-id="335e5-121">String description of the health state chunk.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>