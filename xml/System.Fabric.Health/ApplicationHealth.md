<Type Name="ApplicationHealth" FullName="System.Fabric.Health.ApplicationHealth">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type ApplicationHealth = class&#xA;    inherit EntityHealth" />
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
      <para><span data-ttu-id="3a4e1-101">Die Integrität einer Anwendung beschrieben, wie vom <see cref="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription)" />.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-101">Describes the health of an application as returned by <see cref="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealth.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.ApplicationHealth.ApplicationName" />
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
          <para><span data-ttu-id="3a4e1-102">Ruft den Anwendungsnamen, der die Anwendung eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-102">Gets the application name, which uniquely identifies the application .</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="3a4e1-103">Der Anwendungsname.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-103">The application name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedApplicationHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthState&gt; DeployedApplicationHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.DeployedApplicationHealthState&gt; DeployedApplicationHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealth.DeployedApplicationHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedApplicationHealthStates As IList(Of DeployedApplicationHealthState)" />
      <MemberSignature Language="F#" Value="member this.DeployedApplicationHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthState&gt;" Usage="System.Fabric.Health.ApplicationHealth.DeployedApplicationHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3a4e1-104">Ruft den Integritätsstatus der bereitgestellten Anwendung für die aktuelle Anwendung, die im Health Store.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-104">Gets the deployed application health states for the current application as found in the health store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3a4e1-105">bereitgestellten Anwendungen für die aktuelle Anwendung im Health Store gefunden.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-105">deployed applications for the current application as found in the health store.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="3a4e1-106">Alle bereitgestellte Anwendungen werden ausgewertet, um zu bestimmen, die Anwendungsintegrität aggregiert.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-106">All deployed applications are evaluated to determine the application aggregated health.</span></span></para>
        <para><span data-ttu-id="3a4e1-107">Nur Anwendungen bereitgestellt, die berücksichtigen die <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.DeployedApplicationsFilter" /> (falls angegeben) werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-107">Only deployed applications that respect the <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.DeployedApplicationsFilter" /> (if specified) are returned.</span></span> <span data-ttu-id="3a4e1-108">Wenn der Filter nicht angegeben ist, werden alle bereitgestellte Anwendungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-108">If the input filter is not specified, all deployed applications are returned.</span></span></para>
      </Docs>
    </Member>
    <Member MemberName="HealthStatistics">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStatistics HealthStatistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthStatistics HealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealth.HealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStatistics As HealthStatistics" />
      <MemberSignature Language="F#" Value="member this.HealthStatistics : System.Fabric.Health.HealthStatistics" Usage="System.Fabric.Health.ApplicationHealth.HealthStatistics" />
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
            <span data-ttu-id="3a4e1-109">Ruft die Anwendung Integrität Statistiken, die enthalten Informationen darüber, wie viele Entitäten der Anwendung in werden <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-109">Gets the application health statistics, which contain information about how many entities of the application are in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            </summary>
        <value><span data-ttu-id="3a4e1-110">Die Integrität Anwendungsstatistiken.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-110">The application health statistics.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="3a4e1-111">Die Integrität Anwendungsstatistiken enthalten Informationen über wie viele Dienste, Partitionen, Replikate, bereitgestellten Anwendungen und Pakete bereitgestellten Dienst sind in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-111">The application health statistics contain information about how many services, partitions, replicas, deployed applications, and deployed service packages are in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            <span data-ttu-id="3a4e1-112">Es kann null oder leer sein, wenn die Abfrage, die zurückgibt die <see cref="T:System.Fabric.Health.ApplicationHealth" /> angegebenen <see cref="T:System.Fabric.Health.ApplicationHealthStatisticsFilter" /> Health Statistiken ausschließen.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-112">It can be null or empty if the query that returns the <see cref="T:System.Fabric.Health.ApplicationHealth" /> specified <see cref="T:System.Fabric.Health.ApplicationHealthStatisticsFilter" /> to exclude health statistics.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthState&gt; ServiceHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ServiceHealthState&gt; ServiceHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealth.ServiceHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceHealthStates As IList(Of ServiceHealthState)" />
      <MemberSignature Language="F#" Value="member this.ServiceHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthState&gt;" Usage="System.Fabric.Health.ApplicationHealth.ServiceHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3a4e1-113">Ruft die dienstintegritätszustände für die aktuelle Anwendung, die im Health Store.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-113">Gets the service health states for the current application as found in the health store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3a4e1-114">Die Dienste von der aktuellen Anwendung als gefunden wurde im Health Store.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-114">The services of the current application as found in the health store.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="3a4e1-115">Alle Dienste werden ausgewertet, um zu bestimmen, die Anwendungsintegrität aggregiert.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-115">All services are evaluated to determine the application aggregated health.</span></span></para>
        <para><span data-ttu-id="3a4e1-116">Dienste nur dieser Hinsicht mit der <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ServicesFilter" /> (falls angegeben) werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-116">Only services that respect the <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ServicesFilter" /> (if specified) are returned.</span></span> <span data-ttu-id="3a4e1-117">Wenn der Filter nicht angegeben ist, werden alle Dienste zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-117">If the input filter is not specified, all services are returned.</span></span></para>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealth.ToString " />
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
            <span data-ttu-id="3a4e1-118">Ruft eine Zeichenfolgendarstellung der <see cref="T:System.Fabric.Health.ApplicationHealth" />.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-118">Gets a string representation of the <see cref="T:System.Fabric.Health.ApplicationHealth" />.</span></span>
            </summary>
        <returns><span data-ttu-id="3a4e1-119">Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Health.ApplicationHealth" />.</span><span class="sxs-lookup"><span data-stu-id="3a4e1-119">A string representation of the <see cref="T:System.Fabric.Health.ApplicationHealth" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>