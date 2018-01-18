<Type Name="ServiceQueryDescription" FullName="System.Fabric.Description.ServiceQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceQueryDescription" />
  <TypeSignature Language="F#" Value="type ServiceQueryDescription = class" />
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
      <para><span data-ttu-id="fc1f4-101">Stellt dar, die mehrere Filter, die angegeben werden können, um die Rückgabe zu verfeinern.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-101">Represents the multiple filters that can be specified to refine the return.</span></span>
            <span data-ttu-id="fc1f4-102">Wird von <see cref="M:System.Fabric.FabricClient.QueryClient.GetServicePagedListAsync(System.Fabric.Description.ServiceQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" /> verwendet.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-102">Used by <see cref="M:System.Fabric.FabricClient.QueryClient.GetServicePagedListAsync(System.Fabric.Description.ServiceQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceQueryDescription (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceQueryDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceQueryDescription : Uri -&gt; System.Fabric.Description.ServiceQueryDescription" Usage="new System.Fabric.Description.ServiceQueryDescription applicationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">To be added.</param>
        <summary>
          <para><span data-ttu-id="fc1f4-103">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ServiceQueryDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-103">Initializes a new instance of the <see cref="T:System.Fabric.Description.ServiceQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceQueryDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.ServiceQueryDescription.ApplicationName" />
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
          <para><span data-ttu-id="fc1f4-104">Ruft den URI-Namen der Anwendung, die Dienste, bei der Abfrage enthält.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-104">Gets the URI name of application that contains services to query for.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="fc1f4-105">Der Name der URI der Anwendung, die Dienste, bei der Abfrage enthält.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-105">The URI name of application that contains services to query for.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceQueryDescription.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="System.Fabric.Description.ServiceQueryDescription.ContinuationToken" />
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
          <para><span data-ttu-id="fc1f4-106">Ruft ab oder legt das Token, das zum Abrufen der nächsten Seite von Abfragen verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-106">Gets or sets the token that can be used by queries to get the next page.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="fc1f4-107">Das Token, das zum Abrufen der nächsten Seite von Abfragen verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-107">The token that can be used by queries to get the next page.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="fc1f4-108">ContinuationToken wird von einer vorherigen Abfrage empfangen.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-108">ContinuationToken is received by a previous query.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceNameFilter">
      <MemberSignature Language="C#" Value="public Uri ServiceNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceQueryDescription.ServiceNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceNameFilter As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceNameFilter : Uri with get, set" Usage="System.Fabric.Description.ServiceQueryDescription.ServiceNameFilter" />
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
          <para><span data-ttu-id="fc1f4-109">Ruft ab oder legt den URI-Namen des Diensts bei der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-109">Gets or sets the URI name of service to query for.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="fc1f4-110">Der Name der URI des Diensts zur Abfrage.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-110">The URI name of service to query for.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="fc1f4-111">ServiceNameFilter und ServiceTypeNameFilter können nicht zusammen angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-111">ServiceNameFilter and ServiceTypeNameFilter can not be specified together.</span></span></para>
          <para><span data-ttu-id="fc1f4-112">Wenn weder ServiceNameFilter noch ServiceTypeNameFilter angegeben wird, werden alle Dienste der angegebenen Anwendung zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-112">If neither ServiceNameFilter nor ServiceTypeNameFilter is specified, all services of the specified application are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeNameFilter">
      <MemberSignature Language="C#" Value="public string ServiceTypeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceQueryDescription.ServiceTypeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceTypeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeNameFilter : string with get, set" Usage="System.Fabric.Description.ServiceQueryDescription.ServiceTypeNameFilter" />
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
          <para><span data-ttu-id="fc1f4-113">Ruft ab oder legt den Dienstnamen-Typ verwendet, um die Dienste für Abfragen zu filtern.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-113">Gets or sets the service type name used to filter the services to query for.</span></span>
            <span data-ttu-id="fc1f4-114">Dienste, die dieses Diensttyps sind, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-114">Services that are of this service type will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="fc1f4-115">Der Diensttypname, der zum Filtern der Dienste verwendet wird, die abgefragt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-115">The service type name used to filter the services to query for.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="fc1f4-116">ServiceNameFilter und ServiceTypeNameFilter können nicht zusammen angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-116">ServiceNameFilter and ServiceTypeNameFilter can not be specified together.</span></span></para>
          <para><span data-ttu-id="fc1f4-117">Wenn weder ServiceNameFilter noch ServiceTypeNameFilter angegeben wird, werden alle Dienste der angegebenen Anwendung zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-117">If neither ServiceNameFilter nor ServiceTypeNameFilter is specified, all services of the specified application are returned.</span></span></para>
          <para><span data-ttu-id="fc1f4-118">Dieser Filter ist Groß-/Kleinschreibung beachtet.</span><span class="sxs-lookup"><span data-stu-id="fc1f4-118">This filter is case sensitive.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>