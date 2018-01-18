<Type Name="NodeHealthQueryDescription" FullName="System.Fabric.Description.NodeHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class NodeHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.NodeHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type NodeHealthQueryDescription = class" />
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
      <para><span data-ttu-id="e2211-101">Beschreibt abfrageeingabe zum Abrufen von <see cref="T:System.Fabric.Health.NodeHealth" />.</span><span class="sxs-lookup"><span data-stu-id="e2211-101">Describes query input for getting <see cref="T:System.Fabric.Health.NodeHealth" />.</span></span> <span data-ttu-id="e2211-102">Wird von <see cref="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.Fabric.Description.NodeHealthQueryDescription)" /> verwendet.</span><span class="sxs-lookup"><span data-stu-id="e2211-102">Used by <see cref="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.Fabric.Description.NodeHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeHealthQueryDescription (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.NodeHealthQueryDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nodeName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.NodeHealthQueryDescription : string -&gt; System.Fabric.Description.NodeHealthQueryDescription" Usage="new System.Fabric.Description.NodeHealthQueryDescription nodeName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="e2211-103">Der Knotenname.</span><span class="sxs-lookup"><span data-stu-id="e2211-103">The node name.</span></span> <span data-ttu-id="e2211-104">Darf weder NULL noch leer sein.</span><span class="sxs-lookup"><span data-stu-id="e2211-104">Cannot be null or empty.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2211-105">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.NodeHealthQueryDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e2211-105">Initializes a new instance of the <see cref="T:System.Fabric.Description.NodeHealthQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="e2211-106">Ein erforderlicher Parameter darf nicht null oder leer sein.</span><span class="sxs-lookup"><span data-stu-id="e2211-106">A required parameter can't be null or empty.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.NodeHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.NodeHealthQueryDescription.EventsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthEventsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e2211-107">Ruft ab oder legt Sie den Filter für die Auflistung von <see cref="T:System.Fabric.Health.HealthEvent" /> auf dem Knoten gemeldet.</span><span class="sxs-lookup"><span data-stu-id="e2211-107">Gets or sets the filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the node.</span></span> <span data-ttu-id="e2211-108">Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="e2211-108">Only events that match the filter will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e2211-109">Der Filter für das integritätsereignis.</span><span class="sxs-lookup"><span data-stu-id="e2211-109">The filter for the health event.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="e2211-110">Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="e2211-110">Only events that match the filter will be returned.</span></span> <span data-ttu-id="e2211-111">Alle Ereignisse werden der Zustand des Knotens aggregiert auszuwertende verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="e2211-111">All events will be used to evaluate the node aggregated health state.</span></span>
            <span data-ttu-id="e2211-112">Wenn der Filter nicht angegeben wird, werden alle Ereignisse zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="e2211-112">If the filter is not specified, all events are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.NodeHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ClusterHealthPolicy with get, set" Usage="System.Fabric.Description.NodeHealthQueryDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e2211-113">Ruft ab oder legt die <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> verwendet, um den Zustand des Knotens auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="e2211-113">Gets or sets the <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> used to evaluate the node health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e2211-114">Die <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> verwendet, um den Zustand des Knotens auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="e2211-114">The <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> used to evaluate the node health.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="e2211-115">Wenn nicht angegeben ist, handelt es sich bei den Integritäts-Speicher verwendet die clusterintegritätsrichtlinie aus dem Manifest (wenn vorhanden) oder den Standardwert, strikte Integritätsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="e2211-115">If not specified, the health store uses the cluster health policy from the manifest (if exists) or the default, strict health policy.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.NodeHealthQueryDescription.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Description.NodeHealthQueryDescription.NodeName" />
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
          <para><span data-ttu-id="e2211-116">Ruft den Knotennamen ab.</span><span class="sxs-lookup"><span data-stu-id="e2211-116">Gets the node name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e2211-117">Der Knotenname.</span><span class="sxs-lookup"><span data-stu-id="e2211-117">The node name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.NodeHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeHealthQueryDescription.ToString " />
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
            <span data-ttu-id="e2211-118">Ruft eine Zeichenfolgendarstellung der Integrität abfragebeschreibung ab.</span><span class="sxs-lookup"><span data-stu-id="e2211-118">Gets a string representation of the health query description.</span></span>
            </summary>
        <returns><span data-ttu-id="e2211-119">Eine Zeichenfolgendarstellung der abfragebeschreibung Integrität.</span><span class="sxs-lookup"><span data-stu-id="e2211-119">A string representation of the health query description.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>