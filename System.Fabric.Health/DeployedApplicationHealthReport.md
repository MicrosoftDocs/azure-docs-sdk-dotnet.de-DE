<Type Name="DeployedApplicationHealthReport" FullName="System.Fabric.Health.DeployedApplicationHealthReport">
  <TypeSignature Language="C#" Value="public class DeployedApplicationHealthReport : System.Fabric.Health.HealthReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeployedApplicationHealthReport extends System.Fabric.Health.HealthReport" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationHealthReport" />
  <TypeSignature Language="VB.NET" Value="Public Class DeployedApplicationHealthReport&#xA;Inherits HealthReport" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthReport = class&#xA;    inherit HealthReport" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthReport</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="1d65f-101">Stellt einen Statusbericht für die bereitgestellte Anwendung Integritäts-Entität verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="1d65f-101">Represents a health report to be applied on the deployed application health entity.</span></span> </para>
    </summary>
    <remarks><span data-ttu-id="1d65f-102">Der Bericht kann gesendet werden, mit dem Health Store <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span><span class="sxs-lookup"><span data-stu-id="1d65f-102">The report can be sent to the health store using <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedApplicationHealthReport (Uri applicationName, string nodeName, System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string nodeName, class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthReport.#ctor(System.Uri,System.String,System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.DeployedApplicationHealthReport : Uri * string * System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.DeployedApplicationHealthReport" Usage="new System.Fabric.Health.DeployedApplicationHealthReport (applicationName, nodeName, healthInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="1d65f-103">Der Anwendungsname.</span><span class="sxs-lookup"><span data-stu-id="1d65f-103">The application name.</span></span> <span data-ttu-id="1d65f-104">Darf nicht NULL sein.</span><span class="sxs-lookup"><span data-stu-id="1d65f-104">Cannot be null.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="1d65f-105">Der Knotenname.</span><span class="sxs-lookup"><span data-stu-id="1d65f-105">The node name.</span></span> <span data-ttu-id="1d65f-106">Darf weder NULL noch leer sein.</span><span class="sxs-lookup"><span data-stu-id="1d65f-106">Cannot be null or empty.</span></span></para>
        </param>
        <param name="healthInformation">
          <para><span data-ttu-id="1d65f-107">Die <see cref="T:System.Fabric.Health.HealthInformation" /> der beschrieben wird, die Berichtsfelder wie SourceId, Eigenschaft, Integritätsstatus.</span><span class="sxs-lookup"><span data-stu-id="1d65f-107">The <see cref="T:System.Fabric.Health.HealthInformation" /> which describes the report fields, like sourceId, property, health state.</span></span> <span data-ttu-id="1d65f-108">Darf nicht NULL sein.</span><span class="sxs-lookup"><span data-stu-id="1d65f-108">Cannot be null.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1d65f-109">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.DeployedApplicationHealthReport" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1d65f-109">Initializes a new instance of the <see cref="T:System.Fabric.Health.DeployedApplicationHealthReport" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>
            <span data-ttu-id="1d65f-110"><paramref name="healthInformation" /> darf nicht NULL sein.</span><span class="sxs-lookup"><span data-stu-id="1d65f-110"><paramref name="healthInformation" /> cannot be null.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
            <span data-ttu-id="1d65f-111"><paramref name="nodeName" />darf nicht leer sein.</span><span class="sxs-lookup"><span data-stu-id="1d65f-111"><paramref name="nodeName" /> cannot be empty.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthReport.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.DeployedApplicationHealthReport.ApplicationName" />
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
          <para><span data-ttu-id="1d65f-112">Ruft den Namen der Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="1d65f-112">Gets the application name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="1d65f-113">Die <see cref="T:System.Uri" /> , die den Namen der Anwendung darstellt.</span><span class="sxs-lookup"><span data-stu-id="1d65f-113">The <see cref="T:System.Uri" /> representing the application name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthReport.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.DeployedApplicationHealthReport.NodeName" />
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
          <para><span data-ttu-id="1d65f-114">Ruft ab, dass der Name des Knotens, in dem die bereitgestellte Anwendung ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="1d65f-114">Gets the node name where the deployed application is running.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="1d65f-115">Die <see cref="T:System.String" /> , der Name des Knotens darstellt.</span><span class="sxs-lookup"><span data-stu-id="1d65f-115">The <see cref="T:System.String" /> representing the node name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>