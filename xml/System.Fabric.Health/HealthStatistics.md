<Type Name="HealthStatistics" FullName="System.Fabric.Health.HealthStatistics">
  <TypeSignature Language="C#" Value="public sealed class HealthStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HealthStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthStatistics" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HealthStatistics" />
  <TypeSignature Language="F#" Value="type HealthStatistics = class" />
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
      <para>
            <span data-ttu-id="7d79e-101">Stellt die Integrität von Statistiken für eine Entität dar.</span><span class="sxs-lookup"><span data-stu-id="7d79e-101">Represents health statistics for an entity.</span></span>
            <span data-ttu-id="7d79e-102">Es ist als Teil des Health Abfrageergebnisse zurückgegeben, wenn die Abfrage Beschreibungen für die Statistiken umfassen konfiguriert sind.</span><span class="sxs-lookup"><span data-stu-id="7d79e-102">It is returned as part of health queries results when the query descriptions are configured to include statistics.</span></span>
            <span data-ttu-id="7d79e-103">Die Statistiken umfassen Health Status Anzahlen für alle untergeordneten Elemente der aktuellen Entität.</span><span class="sxs-lookup"><span data-stu-id="7d79e-103">The statistics include health state counts for all children types of the current entity.</span></span>
            <span data-ttu-id="7d79e-104">Beispielsweise enthalten die Integrität Statistiken für Cluster, Integrität Zustand Anzahl für Knoten, Anwendungen, Dienste, Partitionen, Replikate, bereitgestellten Anwendungen und Pakete bereitgestellten Dienst.</span><span class="sxs-lookup"><span data-stu-id="7d79e-104">For example, for cluster, the health statistics include health state counts for nodes, applications, services, partitions, replicas, deployed applications and deployed service packages.</span></span>
            <span data-ttu-id="7d79e-105">Für Partition enthalten die Integrität Statistiken die Integrität-Anzahl für Replikate.</span><span class="sxs-lookup"><span data-stu-id="7d79e-105">For partition, the health statistics include health counts for replicas.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthStateCountList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.EntityKindHealthStateCount&gt; HealthStateCountList { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.EntityKindHealthStateCount&gt; HealthStateCountList" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthStatistics.HealthStateCountList" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStateCountList As IList(Of EntityKindHealthStateCount)" />
      <MemberSignature Language="F#" Value="member this.HealthStateCountList : System.Collections.Generic.IList&lt;System.Fabric.Health.EntityKindHealthStateCount&gt;" Usage="System.Fabric.Health.HealthStatistics.HealthStateCountList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.EntityKindHealthStateCount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d79e-106">Ruft eine Liste der <see cref="T:System.Fabric.Health.HealthStateCount" /> Informationen für andere Entitätsarten.</span><span class="sxs-lookup"><span data-stu-id="7d79e-106">Gets a list of <see cref="T:System.Fabric.Health.HealthStateCount" /> information for different entity kinds.</span></span>
            </summary>
        <value><span data-ttu-id="7d79e-107">Eine Liste mit <see cref="T:System.Fabric.Health.HealthStateCount" /> Informationen für andere Entitätsarten.</span><span class="sxs-lookup"><span data-stu-id="7d79e-107">A list with <see cref="T:System.Fabric.Health.HealthStateCount" /> information for different entity kinds.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="7d79e-108">Die Liste der nachverfolgt werden wie viele untergeordnete Elemente der abgefragten Entität in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="7d79e-108">The list keeps track of how many children of the queried entity are in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStatistics.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="healthStatistics.ToString " />
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
            <span data-ttu-id="7d79e-109">Gibt eine Zeichenfolgendarstellung der Integrität Zustand Anzahl zurück.</span><span class="sxs-lookup"><span data-stu-id="7d79e-109">Returns a string representation of the health state count.</span></span>
            </summary>
        <returns><span data-ttu-id="7d79e-110">Eine Zeichenfolgendarstellung der Anzahl der Integrität-Zustand.</span><span class="sxs-lookup"><span data-stu-id="7d79e-110">A string representation of the health state count.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>