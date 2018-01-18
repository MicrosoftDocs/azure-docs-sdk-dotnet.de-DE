<Type Name="ServiceHealth" FullName="System.Fabric.Health.ServiceHealth">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type ServiceHealth = class&#xA;    inherit EntityHealth" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealth</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="27789-101">Die Integrität eines Diensts beschreibt, wie vom <see cref="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Fabric.Description.ServiceHealthQueryDescription)" />.</span><span class="sxs-lookup"><span data-stu-id="27789-101">Describes the health of a service as returned by <see cref="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Fabric.Description.ServiceHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthStatistics">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStatistics HealthStatistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthStatistics HealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealth.HealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStatistics As HealthStatistics" />
      <MemberSignature Language="F#" Value="member this.HealthStatistics : System.Fabric.Health.HealthStatistics" Usage="System.Fabric.Health.ServiceHealth.HealthStatistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27789-102">Ruft die Service Health Statistiken, die enthalten Informationen darüber, wie viele Partitionen und Replikaten in werden <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="27789-102">Gets the service health statistics, which contain information about how many partitions and replicas are in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            </summary>
        <value><span data-ttu-id="27789-103">Die Statistiken für den Dienst-Integrität.</span><span class="sxs-lookup"><span data-stu-id="27789-103">The service health statistics.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="27789-104">Das Service Health Statistiken enthalten Informationen über wie viele Partitionen und Replikate befinden sich im <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="27789-104">The service health statistics contain information about how many partitions and replicas are in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            <span data-ttu-id="27789-105">Es kann null oder leer sein, wenn die Abfrage, die zurückgibt die <see cref="T:System.Fabric.Health.ServiceHealth" /> angegebenen <see cref="T:System.Fabric.Health.ServiceHealthStatisticsFilter" /> Health Statistiken ausschließen.</span><span class="sxs-lookup"><span data-stu-id="27789-105">It can be null or empty if the query that returns the <see cref="T:System.Fabric.Health.ServiceHealth" /> specified <see cref="T:System.Fabric.Health.ServiceHealthStatisticsFilter" /> to exclude health statistics.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthState&gt; PartitionHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.PartitionHealthState&gt; PartitionHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealth.PartitionHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionHealthStates As IList(Of PartitionHealthState)" />
      <MemberSignature Language="F#" Value="member this.PartitionHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthState&gt;" Usage="System.Fabric.Health.ServiceHealth.PartitionHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="27789-106">Ruft den Integritätsstatus Partition für den aktuellen Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="27789-106">Gets partition health states for the current service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="27789-107">Die Partition Integritätsstatus für den aktuellen Dienst.</span><span class="sxs-lookup"><span data-stu-id="27789-107">The partition health states for the current service.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="27789-108">Nur Partitionen dieser Hinsicht mit der <see cref="P:System.Fabric.Description.ServiceHealthQueryDescription.PartitionsFilter" /> (falls angegeben) werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="27789-108">Only partitions that respect the <see cref="P:System.Fabric.Description.ServiceHealthQueryDescription.PartitionsFilter" /> (if specified) are returned.</span></span> <span data-ttu-id="27789-109">Wenn der Filter nicht angegeben ist, werden alle Partitionen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="27789-109">If the input filter is not specified, all partitions are returned.</span></span></para>
          <para><span data-ttu-id="27789-110">Alle Partitionen werden ausgewertet, um die aggregierten Integrität zu ermitteln.</span><span class="sxs-lookup"><span data-stu-id="27789-110">All partitions are evaluated to determine the service aggregated health.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealth.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Health.ServiceHealth.ServiceName" />
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
          <para><span data-ttu-id="27789-111">Ruft den Dienstnamen, der die Service Health Entität eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="27789-111">Gets the service name which uniquely identifies the service health entity.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="27789-112">Der Dienstname der Entität Health Service eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="27789-112">The service name which uniquely identifies the service health entity.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceHealth.ToString " />
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
            <span data-ttu-id="27789-113">Ruft eine Zeichenfolgendarstellung der <see cref="T:System.Fabric.Health.ServiceHealth" />.</span><span class="sxs-lookup"><span data-stu-id="27789-113">Gets a string representation of the <see cref="T:System.Fabric.Health.ServiceHealth" />.</span></span>
            </summary>
        <returns><span data-ttu-id="27789-114">Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Health.ServiceHealth" />.</span><span class="sxs-lookup"><span data-stu-id="27789-114">A string representation of the <see cref="T:System.Fabric.Health.ServiceHealth" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>