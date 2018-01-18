<Type Name="RestartDeployedCodePackageResult" FullName="System.Fabric.Result.RestartDeployedCodePackageResult">
  <TypeSignature Language="C#" Value="public class RestartDeployedCodePackageResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit RestartDeployedCodePackageResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.RestartDeployedCodePackageResult" />
  <TypeSignature Language="VB.NET" Value="Public Class RestartDeployedCodePackageResult" />
  <TypeSignature Language="F#" Value="type RestartDeployedCodePackageResult = class" />
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
            <span data-ttu-id="6cb21-101">Gibt zurück, Neustart Code Ergebnis Paketobjekts bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="6cb21-101">Returns Restart deployed code package result object.</span></span> 
            </summary>
    <remarks>
            <span data-ttu-id="6cb21-102">Diese Klasse gibt die "nodename", Parameter "ApplicationName", ServiceManifestName, CodePackageName, CodePackageInstanceId und SelectedReplica-Informationen für das der bereitgestellten Code Paketaktion aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="6cb21-102">This class returns nodeName, applicationName, serviceManifestName, codePackageName, codePackageInstanceId and SelectedReplica information for which the deployed code package action was called.</span></span> <span data-ttu-id="6cb21-103">ReplicaSelector werden keine für den Fall, dass Anwendung Selecetd mit Nodename, Anwendungsname, Dienstmanifest, codepaketname und Code Paket Instanz-Id ist.</span><span class="sxs-lookup"><span data-stu-id="6cb21-103">ReplicaSelector will be none in case application is selecetd using nodename, application name, service manifest, code package name, and code package instance id.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.ApplicationName" />
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
            <span data-ttu-id="6cb21-104">Ruft die Namen der Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="6cb21-104">Gets Application name.</span></span>
            </summary>
        <value><span data-ttu-id="6cb21-105">Der Anwendungsname.</span><span class="sxs-lookup"><span data-stu-id="6cb21-105">The application name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageInstanceId">
      <MemberSignature Language="C#" Value="public long CodePackageInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CodePackageInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.CodePackageInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageInstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.CodePackageInstanceId : int64" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.CodePackageInstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6cb21-106">Ruft die Code-Paket-Instanz-Id ab.</span><span class="sxs-lookup"><span data-stu-id="6cb21-106">Gets code package instance id.</span></span>
            </summary>
        <value><span data-ttu-id="6cb21-107">Die Code-Paket-Id, als einen Long-Wert.</span><span class="sxs-lookup"><span data-stu-id="6cb21-107">The code package instance id, as a long.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageName">
      <MemberSignature Language="C#" Value="public string CodePackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.CodePackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageName As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageName : string" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.CodePackageName" />
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
            <span data-ttu-id="6cb21-108">Ruft die codepaketname ab.</span><span class="sxs-lookup"><span data-stu-id="6cb21-108">Gets code package name.</span></span>
            </summary>
        <value><span data-ttu-id="6cb21-109">Der Paketname für den Code.</span><span class="sxs-lookup"><span data-stu-id="6cb21-109">The code package name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.NodeName" />
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
            <span data-ttu-id="6cb21-110">Ruft Name des Knotens ab.</span><span class="sxs-lookup"><span data-stu-id="6cb21-110">Gets node name.</span></span>
            </summary>
        <value><span data-ttu-id="6cb21-111">Der Knotenname.</span><span class="sxs-lookup"><span data-stu-id="6cb21-111">The node name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectedReplica">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedReplica SelectedReplica { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedReplica SelectedReplica" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.SelectedReplica" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedReplica As SelectedReplica" />
      <MemberSignature Language="F#" Value="member this.SelectedReplica : System.Fabric.SelectedReplica" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.SelectedReplica" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SelectedReplica</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6cb21-112">Ruft den ausgewählten Replikat.</span><span class="sxs-lookup"><span data-stu-id="6cb21-112">Gets selected replica.</span></span>
            </summary>
        <value><span data-ttu-id="6cb21-113">Das SelectedReplica-Objekt.</span><span class="sxs-lookup"><span data-stu-id="6cb21-113">The SelectedReplica object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.ServiceManifestName" />
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
            <span data-ttu-id="6cb21-114">Ruft die dienstmanifestname ab.</span><span class="sxs-lookup"><span data-stu-id="6cb21-114">Gets service manifest name.</span></span>
            </summary>
        <value><span data-ttu-id="6cb21-115">Der dienstmanifestname.</span><span class="sxs-lookup"><span data-stu-id="6cb21-115">The service manifest name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.ServicePackageActivationId" />
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
            <span data-ttu-id="6cb21-116">Ruft die ActivationId des Dienstpakets ab.</span><span class="sxs-lookup"><span data-stu-id="6cb21-116">Gets the ActivationId of service package.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="6cb21-117">Eine Zeichenfolge von bereitgestelltes Dienstpaket ActivationId darstellt.</span><span class="sxs-lookup"><span data-stu-id="6cb21-117">A string representing ActivationId of deployed service package.</span></span> <span data-ttu-id="6cb21-118">Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung der Dienst ist <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn nicht angegeben ist, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Result.RestartDeployedCodePackageResult.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="6cb21-118">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service is <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it is not specfied, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Result.RestartDeployedCodePackageResult.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="6cb21-119">Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span><span class="sxs-lookup"><span data-stu-id="6cb21-119">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.RestartDeployedCodePackageResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="restartDeployedCodePackageResult.ToString " />
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
            <span data-ttu-id="6cb21-120">Formatiert die Daten in RestartDeployedCodePackageResult als Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="6cb21-120">Formats the data inside RestartDeployedCodePackageResult as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="6cb21-121">Die formatierte Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="6cb21-121">The formatted string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>