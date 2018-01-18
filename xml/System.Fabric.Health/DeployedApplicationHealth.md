<Type Name="DeployedApplicationHealth" FullName="System.Fabric.Health.DeployedApplicationHealth">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealth = class&#xA;    inherit EntityHealth" />
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
      <para><span data-ttu-id="47ad9-101">Beschreibt die Integrität einer Anwendung auf einem Knoten bereitgestellt werden, da vom <see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Fabric.Description.DeployedApplicationHealthQueryDescription)" />.</span><span class="sxs-lookup"><span data-stu-id="47ad9-101">Describes the health of an application deployed on a node as returned by <see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Fabric.Description.DeployedApplicationHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealth.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.DeployedApplicationHealth.ApplicationName" />
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
          <para><span data-ttu-id="47ad9-102">Ruft den Anwendungsnamen, der die Anwendung eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="47ad9-102">Gets the application name, which uniquely identifies the application .</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="47ad9-103">Der Anwendungsname.</span><span class="sxs-lookup"><span data-stu-id="47ad9-103">The application name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedServicePackageHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthState&gt; DeployedServicePackageHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.DeployedServicePackageHealthState&gt; DeployedServicePackageHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealth.DeployedServicePackageHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedServicePackageHealthStates As IList(Of DeployedServicePackageHealthState)" />
      <MemberSignature Language="F#" Value="member this.DeployedServicePackageHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthState&gt;" Usage="System.Fabric.Health.DeployedApplicationHealth.DeployedServicePackageHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="47ad9-104">Ruft die bereitgestelltes Dienstpaket Integritätsstatus für die aktuelle bereitgestellte Anwendung, die im Health Store.</span><span class="sxs-lookup"><span data-stu-id="47ad9-104">Gets the deployed service package health states for the current deployed application as found in the health store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="47ad9-105">Die bereitgestellten dienstpakete der aktuellen bereitgestellten Anwendung als wurde im Health Store gefunden.</span><span class="sxs-lookup"><span data-stu-id="47ad9-105">The deployed service packages of the current deployed application as found in the health store.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="47ad9-106">Alle bereitgestellten dienstpakete werden ausgewertet, um zu bestimmen, die Integrität der bereitgestellten Anwendung aggregiert.</span><span class="sxs-lookup"><span data-stu-id="47ad9-106">All deployed service packages are evaluated to determine the deployed application aggregated health.</span></span></para>
        <para><span data-ttu-id="47ad9-107">Nur der Dienst bereitgestellt Pakete dieser Hinsicht mit der <see cref="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.DeployedServicePackagesFilter" /> (falls angegeben) werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="47ad9-107">Only deployed service packages that respect the <see cref="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.DeployedServicePackagesFilter" /> (if specified) are returned.</span></span> <span data-ttu-id="47ad9-108">Wenn der Filter nicht angegeben ist, werden alle bereitgestellten dienstpakete zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="47ad9-108">If the input filter is not specified, all deployed service packages are returned.</span></span></para>
      </Docs>
    </Member>
    <Member MemberName="HealthStatistics">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStatistics HealthStatistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthStatistics HealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealth.HealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStatistics As HealthStatistics" />
      <MemberSignature Language="F#" Value="member this.HealthStatistics : System.Fabric.Health.HealthStatistics" Usage="System.Fabric.Health.DeployedApplicationHealth.HealthStatistics" />
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
            <span data-ttu-id="47ad9-109">Ruft die bereitgestellte Anwendung Integrität Statistiken, die enthalten Informationen darüber, wie viele bereitgestellte dienstpakete in werden <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="47ad9-109">Gets the deployed application health statistics, which contain information about how many deployed service packages are in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            </summary>
        <value><span data-ttu-id="47ad9-110">Die bereitgestellte Anwendung Integritäts-Statistiken.</span><span class="sxs-lookup"><span data-stu-id="47ad9-110">The deployed application health statistics.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="47ad9-111">Die bereitgestellte Anwendung Integrität Statistiken enthalten Informationen darüber, wie viele bereitgestellte dienstpakete in werden <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="47ad9-111">The deployed application health statistics contain information about how many deployed service packages are in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            <span data-ttu-id="47ad9-112">Es kann null oder leer sein, wenn die Abfrage, die zurückgibt die <see cref="T:System.Fabric.Health.DeployedApplicationHealth" /> angegebenen <see cref="T:System.Fabric.Health.DeployedApplicationHealthStatisticsFilter" /> Health Statistiken ausschließen.</span><span class="sxs-lookup"><span data-stu-id="47ad9-112">It can be null or empty if the query that returns the <see cref="T:System.Fabric.Health.DeployedApplicationHealth" /> specified <see cref="T:System.Fabric.Health.DeployedApplicationHealthStatisticsFilter" /> to exclude health statistics.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealth.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.DeployedApplicationHealth.NodeName" />
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
          <para><span data-ttu-id="47ad9-113">Ruft den Knotennamen für den Knoten, in dem die Anwendung bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="47ad9-113">Gets the node name for the node where the application is deployed.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="47ad9-114">Der Knotenname für den Knoten, in dem die Anwendung bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="47ad9-114">The node name for the node where the application is deployed.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedApplicationHealth.ToString " />
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
            <span data-ttu-id="47ad9-115">Ruft eine Zeichenfolgendarstellung der <see cref="T:System.Fabric.Health.DeployedApplicationHealth" />.</span><span class="sxs-lookup"><span data-stu-id="47ad9-115">Gets a string representation of the <see cref="T:System.Fabric.Health.DeployedApplicationHealth" />.</span></span>
            </summary>
        <returns><span data-ttu-id="47ad9-116">Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Health.DeployedApplicationHealth" />.</span><span class="sxs-lookup"><span data-stu-id="47ad9-116">A string representation of the <see cref="T:System.Fabric.Health.DeployedApplicationHealth" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>