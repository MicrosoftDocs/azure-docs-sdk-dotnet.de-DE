<Type Name="DeployedServicePackageHealthReport" FullName="System.Fabric.Health.DeployedServicePackageHealthReport">
  <TypeSignature Language="C#" Value="public class DeployedServicePackageHealthReport : System.Fabric.Health.HealthReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeployedServicePackageHealthReport extends System.Fabric.Health.HealthReport" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackageHealthReport" />
  <TypeSignature Language="VB.NET" Value="Public Class DeployedServicePackageHealthReport&#xA;Inherits HealthReport" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthReport = class&#xA;    inherit HealthReport" />
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
      <para><span data-ttu-id="08fcd-101">Stellt einen Statusbericht auf die bereitgestellten Dienst Paket Integrität Entität angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="08fcd-101">Represents a health report to be applied on the deployed service package health entity.</span></span> </para>
    </summary>
    <remarks><span data-ttu-id="08fcd-102">Der Bericht kann gesendet werden, mit dem Health Store <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span><span class="sxs-lookup"><span data-stu-id="08fcd-102">The report can be sent to the health store using <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthReport (Uri applicationName, string serviceManifestName, string nodeName, System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string serviceManifestName, string nodeName, class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthReport.#ctor(System.Uri,System.String,System.String,System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.DeployedServicePackageHealthReport : Uri * string * string * System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.DeployedServicePackageHealthReport" Usage="new System.Fabric.Health.DeployedServicePackageHealthReport (applicationName, serviceManifestName, nodeName, healthInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="08fcd-103">Der Anwendungsname.</span><span class="sxs-lookup"><span data-stu-id="08fcd-103">The application name.</span></span> <span data-ttu-id="08fcd-104">Darf weder NULL noch leer sein.</span><span class="sxs-lookup"><span data-stu-id="08fcd-104">Cannot be null or empty.</span></span></para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="08fcd-105">Dienstmanifestname.</span><span class="sxs-lookup"><span data-stu-id="08fcd-105">Service manifest name.</span></span> <span data-ttu-id="08fcd-106">Darf weder NULL noch leer sein.</span><span class="sxs-lookup"><span data-stu-id="08fcd-106">Cannot be null or empty.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="08fcd-107">Der Knotenname.</span><span class="sxs-lookup"><span data-stu-id="08fcd-107">The node name.</span></span> <span data-ttu-id="08fcd-108">Darf weder NULL noch leer sein.</span><span class="sxs-lookup"><span data-stu-id="08fcd-108">Cannot be null or empty.</span></span></para>
        </param>
        <param name="healthInformation">
          <para><span data-ttu-id="08fcd-109">Die <see cref="T:System.Fabric.Health.HealthInformation" /> der beschrieben wird, die Berichtsfelder wie SourceId, Eigenschaft, Integritätsstatus.</span><span class="sxs-lookup"><span data-stu-id="08fcd-109">The <see cref="T:System.Fabric.Health.HealthInformation" /> which describes the report fields, like sourceId, property, health state.</span></span> <span data-ttu-id="08fcd-110">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="08fcd-110">Required.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="08fcd-111">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.DeployedServicePackageHealthReport" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="08fcd-111">Initializes a new instance of the <see cref="T:System.Fabric.Health.DeployedServicePackageHealthReport" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="08fcd-112">Dienstmanifestname darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="08fcd-112">Service manifest name cannot be null.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="08fcd-113">Dienstmanifestname ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="08fcd-113">Service manifest name is invalid.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthReport (Uri applicationName, string serviceManifestName, string servicePackageActivationId, string nodeName, System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string serviceManifestName, string servicePackageActivationId, string nodeName, class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthReport.#ctor(System.Uri,System.String,System.String,System.String,System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.DeployedServicePackageHealthReport : Uri * string * string * string * System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.DeployedServicePackageHealthReport" Usage="new System.Fabric.Health.DeployedServicePackageHealthReport (applicationName, serviceManifestName, servicePackageActivationId, nodeName, healthInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="08fcd-114">Der Anwendungsname.</span><span class="sxs-lookup"><span data-stu-id="08fcd-114">The application name.</span></span> <span data-ttu-id="08fcd-115">Darf weder NULL noch leer sein.</span><span class="sxs-lookup"><span data-stu-id="08fcd-115">Cannot be null or empty.</span></span></para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="08fcd-116">Dienstmanifestname.</span><span class="sxs-lookup"><span data-stu-id="08fcd-116">Service manifest name.</span></span> <span data-ttu-id="08fcd-117">Darf weder NULL noch leer sein.</span><span class="sxs-lookup"><span data-stu-id="08fcd-117">Cannot be null or empty.</span></span></para>
        </param>
        <param name="servicePackageActivationId">
          <para>
            <span data-ttu-id="08fcd-118">Die <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> des bereitgestellten Dienstpakets.</span><span class="sxs-lookup"><span data-stu-id="08fcd-118">The <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package.</span></span> <span data-ttu-id="08fcd-119">Dies kann abgerufen werden, mithilfe von <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> Abfrage.</span><span class="sxs-lookup"><span data-stu-id="08fcd-119">This can be obtained by using <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> query.</span></span> 
            </para>
          <para>
            <span data-ttu-id="08fcd-120">Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung des Diensts wurde <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wurde, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="08fcd-120">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service was <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it was not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="08fcd-121">Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span><span class="sxs-lookup"><span data-stu-id="08fcd-121">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="08fcd-122">Der Knotenname.</span><span class="sxs-lookup"><span data-stu-id="08fcd-122">The node name.</span></span> <span data-ttu-id="08fcd-123">Darf weder NULL noch leer sein.</span><span class="sxs-lookup"><span data-stu-id="08fcd-123">Cannot be null or empty.</span></span></para>
        </param>
        <param name="healthInformation">
          <para><span data-ttu-id="08fcd-124">Die <see cref="T:System.Fabric.Health.HealthInformation" /> der beschrieben wird, die Berichtsfelder wie SourceId, Eigenschaft, Integritätsstatus.</span><span class="sxs-lookup"><span data-stu-id="08fcd-124">The <see cref="T:System.Fabric.Health.HealthInformation" /> which describes the report fields, like sourceId, property, health state.</span></span> <span data-ttu-id="08fcd-125">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="08fcd-125">Required.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="08fcd-126">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.DeployedServicePackageHealthReport" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="08fcd-126">Initializes a new instance of the <see cref="T:System.Fabric.Health.DeployedServicePackageHealthReport" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="08fcd-127">Dienstmanifestname darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="08fcd-127">Service manifest name cannot be null.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="08fcd-128">Dienstmanifestname ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="08fcd-128">Service manifest name is invalid.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthReport.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.DeployedServicePackageHealthReport.ApplicationName" />
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
          <para><span data-ttu-id="08fcd-129">Ruft den Namen der Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="08fcd-129">Gets the application name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="08fcd-130">Die <see cref="T:System.Uri" /> , die den Namen der Anwendung darstellt.</span><span class="sxs-lookup"><span data-stu-id="08fcd-130">The <see cref="T:System.Uri" /> representing the application name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthReport.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.DeployedServicePackageHealthReport.NodeName" />
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
          <para><span data-ttu-id="08fcd-131">Ruft den Namen des Knotens, in dem das Paket bereitgestellten Dienst ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="08fcd-131">Gets the name of the node where the deployed service package is running.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="08fcd-132">Ein <see cref="T:System.String" /> , der Name des Knotens darstellt.</span><span class="sxs-lookup"><span data-stu-id="08fcd-132">A <see cref="T:System.String" /> representing the node name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthReport.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Health.DeployedServicePackageHealthReport.ServiceManifestName" />
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
          <para><span data-ttu-id="08fcd-133">Ruft den Namen des Dienst-Manifests ab.</span><span class="sxs-lookup"><span data-stu-id="08fcd-133">Gets the service manifest name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="08fcd-134">Ein <see cref="T:System.String" /> , der dienstmanifestname darstellt.</span><span class="sxs-lookup"><span data-stu-id="08fcd-134">A <see cref="T:System.String" /> representing the service manifest name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthReport.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Health.DeployedServicePackageHealthReport.ServicePackageActivationId" />
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
            <span data-ttu-id="08fcd-135">Ruft die ActivationId des Dienstpakets ab.</span><span class="sxs-lookup"><span data-stu-id="08fcd-135">Gets the ActivationId of service package.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="08fcd-136">Die <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> des bereitgestellten Dienstpakets.</span><span class="sxs-lookup"><span data-stu-id="08fcd-136">The <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package.</span></span> <span data-ttu-id="08fcd-137">Dies kann abgerufen werden, mithilfe von <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> Abfrage.</span><span class="sxs-lookup"><span data-stu-id="08fcd-137">This can be obtained by using <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> query.</span></span> 
            </para>
          <para>
            <span data-ttu-id="08fcd-138">Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung des Diensts wurde <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wurde, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="08fcd-138">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service was <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it was not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="08fcd-139">Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span><span class="sxs-lookup"><span data-stu-id="08fcd-139">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>