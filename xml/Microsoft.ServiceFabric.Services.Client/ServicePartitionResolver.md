<Type Name="ServicePartitionResolver" FullName="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver">
  <TypeSignature Language="C#" Value="public class ServicePartitionResolver : Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServicePartitionResolver extends System.Object implements class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" />
  <TypeSignature Language="VB.NET" Value="Public Class ServicePartitionResolver&#xA;Implements IServicePartitionResolver" />
  <TypeSignature Language="F#" Value="type ServicePartitionResolver = class&#xA;    interface IServicePartitionResolver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="7dd3c-101">Implementiert die Partition Konfliktlöser Dienstklasse, die verwendet die <see cref="T:System.Fabric.FabricClient">FabricClients </see> <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" /> Methode für die Dienst-Auflösung und einen Back-off/Wiederholungsmechanismus bei Fehlern von dieser Methode implementiert.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-101">Implements the Service partition resolver class that uses the <see cref="T:System.Fabric.FabricClient">FabricClient's </see><see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" /> method for service resolution and implements a back-off/retry mechanism on errors from that method.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate createFabricClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate createFabricClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createFabricClient As CreateFabricClientDelegate)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver createFabricClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createFabricClient" Type="Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate" />
      </Parameters>
      <Docs>
        <param name="createFabricClient"><span data-ttu-id="7dd3c-102">Delegat, der Fabric-Client zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-102">Delegate to create fabric client.</span></span></param>
        <summary>
            <span data-ttu-id="7dd3c-103">Instanziiert eine ServicePartitionResolver, die den angegebenen Delegaten instanziieren FabricClient aufrufen.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-103">Instantiates a ServicePartitionResolver, invoking the given delegate to instantiate FabricClient.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (params string[] connectionEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string[] connectionEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray connectionEndpoints As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : string[] -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver connectionEndpoints" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="connectionEndpoints"><span data-ttu-id="7dd3c-104">Array von-Endpunkte des Clusters.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-104">Array of management endpoints of the cluster.</span></span></param>
        <summary>
            <span data-ttu-id="7dd3c-105">Instanziiert eine ServicePartitionResolver, der angegebenen ConnectionEndpoints verwendet, um eine neue Instanz der dem FabricClient zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-105">Instantiates a ServicePartitionResolver, uses the given connectionEndpoints to create a new instance of the FabricClient.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate createFabricClient, Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate recreateFabricClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate createFabricClient, class Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate recreateFabricClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate,Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createFabricClient As CreateFabricClientDelegate, recreateFabricClient As CreateFabricClientDelegate)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate * Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver (createFabricClient, recreateFabricClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createFabricClient" Type="Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate" />
        <Parameter Name="recreateFabricClient" Type="Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate" />
      </Parameters>
      <Docs>
        <param name="createFabricClient"><span data-ttu-id="7dd3c-106">Delegieren Sie zum Erstellen des Fabric-Clients.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-106">Delegate to create the fabric client.</span></span></param>
        <param name="recreateFabricClient"><span data-ttu-id="7dd3c-107">Zu den Fabric-Client erneut zu erstellenden Delegaten.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-107">Delegate to re-create the fabric client.</span></span></param>
        <summary>
          <para>
            <span data-ttu-id="7dd3c-108">Instanziiert eine ServicePartionResolver, das Aufrufen der erste Delegat zum Abrufen der <see cref="T:System.Fabric.FabricClient">FabricClient.</see>.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-108">Instantiates a ServicePartionResolver, invoking the first delegate to get the <see cref="T:System.Fabric.FabricClient">FabricClient.</see>.</span></span>
            <span data-ttu-id="7dd3c-109">Während der Auflösung von Partition wird Wenn FabricClient Objekt verworfen ruft und der zweite Delegat bereitgestellt wird, sie den zweiten Delegaten der FabricClient erneut abgerufen.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-109">During partition resolution if FabricClient object gets disposed and second delegate is provided, it uses the second delegate to get the FabricClient again.</span></span> <span data-ttu-id="7dd3c-110">Der zweite Delegat bietet eine Möglichkeit, geben Sie eine alternative Möglichkeit zum Abrufen oder FabricClient erstellen, wenn mit dem ersten Delegaten FabricClient erstellt werden freigegeben.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-110">The second delegate provides a way to specify an alternate way to get or create FabricClient if FabricClient created with first delegate get disposed.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (System.Fabric.FabricClientSettings settings, params string[] connectionEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClientSettings settings, string[] connectionEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(System.Fabric.FabricClientSettings,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (settings As FabricClientSettings, ParamArray connectionEndpoints As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : System.Fabric.FabricClientSettings * string[] -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver (settings, connectionEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
        <Parameter Name="connectionEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="settings"><span data-ttu-id="7dd3c-111">Fabric-Client-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-111">Fabric client Settings.</span></span></param>
        <param name="connectionEndpoints"><span data-ttu-id="7dd3c-112">Array von-Endpunkte des Clusters.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-112">Array of management endpoints of the cluster.</span></span></param>
        <summary>
            <span data-ttu-id="7dd3c-113">Instanziiert eine ServicePartitionResolver, verwendet den angegebenen FabricClient-Einstellungen und die ConnectionEndpoints um eine neue Instanz der FabricClient zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-113">Instantiates a ServicePartitionResolver, uses the given FabricClient Settings and the connectionEndpoints to create a new instance of FabricClient.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (System.Fabric.SecurityCredentials credential, params string[] connectionEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, string[] connectionEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(System.Fabric.SecurityCredentials,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, ParamArray connectionEndpoints As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : System.Fabric.SecurityCredentials * string[] -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver (credential, connectionEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="connectionEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential"><span data-ttu-id="7dd3c-114">Die Sicherheitsanmeldeinformationen für die Fabric-Client.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-114">Security credentials for the fabric client.</span></span></param>
        <param name="connectionEndpoints"><span data-ttu-id="7dd3c-115">Array von-Endpunkte des Clusters.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-115">Array of management endpoints of the cluster.</span></span></param>
        <summary>
            <span data-ttu-id="7dd3c-116">Instanziiert eine ServicePartitionResolver, verwendet die angegebenen Anmeldeinformationen und die ConnectionEndpoints, um eine neue Instanz der FabricClient zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-116">Instantiates a ServicePartitionResolver, uses the given security credentials and the connectionEndpoints to create a new instance of FabricClient.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (System.Fabric.SecurityCredentials credential, System.Fabric.FabricClientSettings settings, params string[] connectionEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, class System.Fabric.FabricClientSettings settings, string[] connectionEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(System.Fabric.SecurityCredentials,System.Fabric.FabricClientSettings,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, settings As FabricClientSettings, ParamArray connectionEndpoints As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : System.Fabric.SecurityCredentials * System.Fabric.FabricClientSettings * string[] -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver (credential, settings, connectionEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
        <Parameter Name="connectionEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential"><span data-ttu-id="7dd3c-117">Die Sicherheitsanmeldeinformationen für die Fabric-Client.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-117">Security credentials for the fabric client.</span></span></param>
        <param name="settings"><span data-ttu-id="7dd3c-118">Fabric-Client-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-118">Fabric client Settings.</span></span></param>
        <param name="connectionEndpoints"><span data-ttu-id="7dd3c-119">Array von-Endpunkte des Clusters.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-119">Array of management endpoints of the cluster.</span></span></param>
        <summary>
            <span data-ttu-id="7dd3c-120">Instanziiert eine ServicePartitionResolver, verwendet die angegebenen Anmeldeinformationen, FabricClient Einstellungen und die ConnectionEndpoints um eine neue Instanz der FabricClient zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-120">Instantiates a ServicePartitionResolver, uses the given security credentials, FabricClient Settings and the connectionEndpoints to create a new instance of FabricClient.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMaxRetryBackoffInterval">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan DefaultMaxRetryBackoffInterval;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan DefaultMaxRetryBackoffInterval" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultMaxRetryBackoffInterval" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultMaxRetryBackoffInterval As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultMaxRetryBackoffInterval : TimeSpan" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultMaxRetryBackoffInterval" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7dd3c-121">Die maximale Backoff-Standardzeit von ServicePartitionResolvers ResolveAsync-Methode verwendet wird, und wiederholen Sie dann, wenn er aufgerufen wird, ohne explizite Angabe der MaxRetryBackoffInterval-Argument.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-121">The default maximum back-off time used by ServicePartitionResolver's ResolveAsync method before retrying, when it is invoked without explicitly specifying the maxRetryBackoffInterval argument.</span></span> <span data-ttu-id="7dd3c-122">Der Standardwert ist 5 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-122">The default value is 5 seconds.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultResolveTimeout">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan DefaultResolveTimeout;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan DefaultResolveTimeout" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultResolveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultResolveTimeout As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultResolveTimeout : TimeSpan" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultResolveTimeout" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7dd3c-123">Die Standardeinstellung zu beheben, Timeouts pro versuchen Sie es von der ResolveAsync-Methode des verwendeten <see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" /> beim ohne explizite Angabe der ResolveTimeoutPerTry Argument aufrufen.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-123">The default resolve timeout per try used by the ResolveAsync method of <see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" /> when it is invoked without explicitly specifying the resolveTimeoutPerTry argument.</span></span> <span data-ttu-id="7dd3c-124">Der Standardwert ist 30 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-124">The default value is 30 seconds.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDefault">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver GetDefault ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver GetDefault() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetDefault () As ServicePartitionResolver" />
      <MemberSignature Language="F#" Value="static member GetDefault : unit -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7dd3c-125">Ruft die standardmäßigen ServicePartitionResolver ab.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-125">Gets the default ServicePartitionResolver.</span></span>
            <span data-ttu-id="7dd3c-126"><remarks><para>Die Standard-Partition Konfliktlöser Dienstinstanz verwendet die lokale <see href="https://docs.microsoft.com/en-us/dotnet/api/system.fabric.fabricclient#System_Fabric_FabricClient__ctor">Fabric-Client</see>. Wenn Sie die ServicePartitionResolver verwenden, zum Auflösen der Dienste, die auf einem remote-Cluster ausgeführt werden, ist die empfohlene Vorgehensweise erstellen eine ServicePartitionResolver über die entsprechenden Endpunkte oder FabricClient und aktualisieren Sie die Standardeinstellung ServicePartitionResolver.</para></remarks></span><span class="sxs-lookup"><span data-stu-id="7dd3c-126"><remarks><para> The default service partition resolver instance uses the local <see href="https://docs.microsoft.com/en-us/dotnet/api/system.fabric.fabricclient#System_Fabric_FabricClient__ctor">fabric client</see>. If you are using the ServicePartitionResolver to resolve services that are running on a remote cluster, the recommended practice is to create a ServicePartitionResolver using the appropriate endpoints or FabricClient and then update the default ServicePartitionResolver. </para></remarks></span></span></summary>
        <returns><span data-ttu-id="7dd3c-127">Standardwert<see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" /></span><span class="sxs-lookup"><span data-stu-id="7dd3c-127">Default <see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" /></span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (System.Fabric.ResolvedServicePartition previousRsp, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.ResolveAsync(System.Fabric.ResolvedServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveAsync : System.Fabric.ResolvedServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="servicePartitionResolver.ResolveAsync (previousRsp, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp"><span data-ttu-id="7dd3c-128">Die aufgelösten Dienstpartition, die der Client über den früheren Aufruf der Methode ResolveAsync() erhalten haben.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-128">The resolved service partition that the client got from the earlier invocation of the ResolveAsync() method.</span></span></param>
        <param name="cancellationToken">
          <para>
            <span data-ttu-id="7dd3c-129">Das CancellationToken, das diesen Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-129">The CancellationToken that this operation is observing.</span></span> <span data-ttu-id="7dd3c-130">Es wird verwendet, um dem Vorgang zu benachrichtigen, dass es abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-130">It is used to notify the operation that it should be canceled.</span></span>
            </para>
        </param>
        <summary>
            <span data-ttu-id="7dd3c-131">Löst eine Partition des angegebenen Diensts durch den Aufruf des FabricClient <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />Methode mit Back-off/Wiederholen auf Fehler mit möglichem Wiederholungsversuch.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-131">Resolves a partition of the specified service by invoking FabricClient's <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />method with back-off/retry on retry-able errors.</span></span> <span data-ttu-id="7dd3c-132">Dies geschieht in der aufgelösten Dienstpartition, die über einen früheren Aufruf der Methode ResolveAsync() erhalten haben, wurde.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-132">This takes in the resolved service partition that was got via an earlier invocation of the ResolveAsync() method.</span></span> <span data-ttu-id="7dd3c-133">Diese methodenüberladung ist in Fällen verwendet, in dem der Client weiß, dass die aufgelösten Dienstpartition, die nicht mehr gültig ist.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-133">This method overload is used in cases where the client knows that the resolved service partition that it has is no longer valid.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7dd3c-134">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-134">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="7dd3c-135">Das Ergebnis von der Aufgabe ist die <see cref="T:System.Fabric.ResolvedServicePartition" /> -Objekt, das die Informationen über die aufgelösten Dienstpartition einschließlich Dienstendpunkte enthält.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-135">The result from the task is the <see cref="T:System.Fabric.ResolvedServicePartition" /> object, that contains the information about the resolved service partition including the service endpoints.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="7dd3c-136">Diese Methode, die bei allen vorübergehende Ausnahmen, die wiederholt werden.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-136">This method retries on all transient exceptions.</span></span> <span data-ttu-id="7dd3c-137">Für Fälle, in denen Sie die maximale Ausführungszeit auf einen dieser Methode beschränken möchten, erstellen Sie eine <see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">, maximale Ausführungszeit zugeordnete Abbruchtoken</see> und dieses Abbruchtoken an diese Methode übergeben.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-137">For cases where you want to limit the max execution time of this method, you should create a <see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">cancellation token associated with that max execution time</see> and pass that cancellation token to this method.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricServiceNotFoundException">
          <para>
            <span data-ttu-id="7dd3c-138">Diese Methode kann eine FabricServiceNotFoundExcepion auslösen, wenn der Dienst, zuvor gelöst wurde, nicht mehr im Cluster vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-138">This method can throw a FabricServiceNotFoundExcepion if the service which was resolved previously is no longer present in the cluster.</span></span>
            </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.ResolveAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="servicePartitionResolver.ResolveAsync (serviceUri, partitionKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceUri"><span data-ttu-id="7dd3c-139">Der Name der Dienstinstanz zu beheben.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-139">Name of the service instance to resolve.</span></span></param>
        <param name="partitionKey">
          <para>
            <span data-ttu-id="7dd3c-140"><see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">Schlüssel</see> , bestimmt die Zielpartition der Dienstinstanz.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-140"><see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">Key</see> that determines the target partition of the service instance.</span></span> <span data-ttu-id="7dd3c-141">Die <see cref="T:System.Fabric.ServicePartitionKind">Partitionsschema</see> angegeben im Schlüssel sollten Übereinstimmung das Partitionierungsschema verwendet, um die Instanz zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-141">The <see cref="T:System.Fabric.ServicePartitionKind">partitioning scheme</see> specified in the key should match the partitioning scheme used to create the service instance.</span></span>
            </para>
        </param>
        <param name="cancellationToken">
          <para>
            <span data-ttu-id="7dd3c-142">Das CancellationToken, das diesen Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-142">The CancellationToken that this operation is observing.</span></span> <span data-ttu-id="7dd3c-143">Es wird verwendet, um dem Vorgang zu benachrichtigen, dass es abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-143">It is used to notify the operation that it should be canceled.</span></span>
            </para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7dd3c-144">Löst eine Partition des angegebenen Diensts durch den Aufruf des FabricClient <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />Methode.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-144">Resolves a partition of the specified service by invoking FabricClient's <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />method.</span></span> <span data-ttu-id="7dd3c-145">Dies wird verwendet, die Standardeinstellungen für <see cref="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultResolveTimeout">Timeout</see> und <see cref="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultMaxRetryBackoffInterval">Backoff-Wiederholung</see> Intervallen.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-145">This uses the default settings for <see cref="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultResolveTimeout">timeout</see> and <see cref="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultMaxRetryBackoffInterval">back-off retry</see> intervals.</span></span>
            </para>
        </summary>
        <returns>
            <span data-ttu-id="7dd3c-146">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-146">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="7dd3c-147">Das Ergebnis von der Aufgabe ist die <see cref="T:System.Fabric.ResolvedServicePartition" /> -Objekt, das die Informationen über die aufgelösten Dienstpartition einschließlich Dienstendpunkte enthält.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-147">The result from the task is the <see cref="T:System.Fabric.ResolvedServicePartition" /> object, that contains the information about the resolved service partition including the service endpoints.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="7dd3c-148">Diese Methode, die bei allen vorübergehende Ausnahmen, die wiederholt werden.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-148">This method retries on all transient exceptions.</span></span> <span data-ttu-id="7dd3c-149">Für Fälle, in denen Sie die maximale Ausführungszeit auf einen dieser Methode beschränken möchten, erstellen Sie eine <see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">, maximale Ausführungszeit zugeordnete Abbruchtoken</see> und dieses Abbruchtoken an diese Methode übergeben.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-149">For cases where you want to limit the max execution time of this method, you should create a <see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">cancellation token associated with that max execution time</see> and pass that cancellation token to this method.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricServiceNotFoundException">
          <para>
            <span data-ttu-id="7dd3c-150">Diese Methode kann eine FabricServiceNotFoundExcepion auslösen, wenn keine Service-Instanz im angegebenen ServiceUri übereinstimmende Cluster vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-150">This method can throw a FabricServiceNotFoundExcepion if there is no service instance in the cluster matching the specified serviceUri.</span></span>
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="7dd3c-151">Diese Methode kann eine FabricException auslösen, wenn in der ServicePartitionKey angegebene Schema nicht mit das Schema verwendet, um die Dienstinstanz erstellen übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-151">This method can throw a FabricException if the scheme specified in the ServicePartitionKey doesn't match the scheme used to create the service instance.</span></span>
            <span data-ttu-id="7dd3c-152">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/">Fehlern und Ausnahmen</see> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-152">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/">Errors and Exceptions</see> for handling common FabricClient failures.</span></span>
            </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (System.Fabric.ResolvedServicePartition previousRsp, TimeSpan resolveTimeoutPerTry, TimeSpan maxRetryBackoffInterval, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype System.TimeSpan resolveTimeoutPerTry, valuetype System.TimeSpan maxRetryBackoffInterval, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.ResolveAsync(System.Fabric.ResolvedServicePartition,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResolveAsync : System.Fabric.ResolvedServicePartition * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;&#xA;override this.ResolveAsync : System.Fabric.ResolvedServicePartition * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="servicePartitionResolver.ResolveAsync (previousRsp, resolveTimeoutPerTry, maxRetryBackoffInterval, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver.ResolveAsync(System.Fabric.ResolvedServicePartition,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="resolveTimeoutPerTry" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffInterval" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp"><span data-ttu-id="7dd3c-153">Die aufgelösten Dienstpartition, die der Client über den früheren Aufruf der Methode ResolveAsync() erhalten haben.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-153">The resolved service partition that the client got from the earlier invocation of the ResolveAsync() method.</span></span></param>
        <param name="resolveTimeoutPerTry"><span data-ttu-id="7dd3c-154">Das Timeout überschritten wird, um FabricClient des <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />Methode</span><span class="sxs-lookup"><span data-stu-id="7dd3c-154">The timeout passed to FabricClient's <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />method</span></span> </param>
        <param name="maxRetryBackoffInterval">
          <para>
            <span data-ttu-id="7dd3c-155">Das maximale Intervall, und wiederholen Sie dann beim Backoff FabricClients <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />Methode, die durch eine Ausnahme mit möglichem Wiederholungsversuch fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-155">The max interval to back-off before retrying when FabricClient's <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />method fails with a retry-able exception.</span></span> <span data-ttu-id="7dd3c-156">Die tatsächlichen Backoff-Intervall ist einem zufälligen Zeitintervall kleiner oder gleich der angegebenen MaxRetryBackoffInterval also.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-156">The actual back off interval is a random time interval which is less than or equal to the specified maxRetryBackoffInterval.</span></span>
            </para>
        </param>
        <param name="cancellationToken">
          <para>
            <span data-ttu-id="7dd3c-157">Das CancellationToken, das diesen Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-157">The CancellationToken that this operation is observing.</span></span> <span data-ttu-id="7dd3c-158">Es wird verwendet, um dem Vorgang zu benachrichtigen, dass es abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-158">It is used to notify the operation that it should be canceled.</span></span>
            </para>
        </param>
        <summary>
            <span data-ttu-id="7dd3c-159">Löst eine Partition des angegebenen Diensts durch den Aufruf des FabricClient <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />Methode mit Back-off/Wiederholen auf Fehler mit möglichem Wiederholungsversuch.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-159">Resolves a partition of the specified service by invoking FabricClient's <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />method with back-off/retry on retry-able errors.</span></span> <span data-ttu-id="7dd3c-160">Dies geschieht in der aufgelösten Dienstpartition, die über einen früheren Aufruf der Methode ResolveAsync() erhalten haben, wurde.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-160">This takes in the resolved service partition that was got via an earlier invocation of the ResolveAsync() method.</span></span> <span data-ttu-id="7dd3c-161">Diese methodenüberladung ist in Fällen verwendet, in dem der Client weiß, dass die aufgelösten Dienstpartition, die nicht mehr gültig ist.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-161">This method overload is used in cases where the client knows that the resolved service partition that it has is no longer valid.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7dd3c-162">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-162">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="7dd3c-163">Das Ergebnis von der Aufgabe ist die <see cref="T:System.Fabric.ResolvedServicePartition" /> -Objekt, das die Informationen über die aufgelösten Dienstpartition einschließlich Dienstendpunkte enthält.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-163">The result from the task is the <see cref="T:System.Fabric.ResolvedServicePartition" /> object, that contains the information about the resolved service partition including the service endpoints.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="7dd3c-164">Diese Methode, die bei allen vorübergehende Ausnahmen, die wiederholt werden.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-164">This method retries on all transient exceptions.</span></span> <span data-ttu-id="7dd3c-165">Für Fälle, in denen Sie die maximale Ausführungszeit auf einen dieser Methode beschränken möchten, erstellen Sie eine <see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">, maximale Ausführungszeit zugeordnete Abbruchtoken</see> und dieses Abbruchtoken an diese Methode übergeben.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-165">For cases where you want to limit the max execution time of this method, you should create a <see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">cancellation token associated with that max execution time</see> and pass that cancellation token to this method.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricServiceNotFoundException">
          <para>
            <span data-ttu-id="7dd3c-166">Diese Methode kann eine FabricServiceNotFoundExcepion auslösen, wenn der Dienst, zuvor gelöst wurde, nicht mehr im Cluster vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-166">This method can throw a FabricServiceNotFoundExcepion if the service which was resolved previously is no longer present in the cluster.</span></span>
            </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, TimeSpan resolveTimeoutPerTry, TimeSpan maxRetryBackoffInterval, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype System.TimeSpan resolveTimeoutPerTry, valuetype System.TimeSpan maxRetryBackoffInterval, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.ResolveAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResolveAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;&#xA;override this.ResolveAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="servicePartitionResolver.ResolveAsync (serviceUri, partitionKey, resolveTimeoutPerTry, maxRetryBackoffInterval, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver.ResolveAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="resolveTimeoutPerTry" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffInterval" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceUri"><span data-ttu-id="7dd3c-167">Der Name der Dienstinstanz zu beheben.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-167">Name of the service instance to resolve.</span></span></param>
        <param name="partitionKey">
          <para>
            <span data-ttu-id="7dd3c-168"><see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">Schlüssel</see> , bestimmt die Zielpartition der Dienstinstanz.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-168"><see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">Key</see> that determines the target partition of the service instance.</span></span> <span data-ttu-id="7dd3c-169">Die <see cref="T:System.Fabric.ServicePartitionKind">Partitionsschema</see> angegeben im Schlüssel sollten Übereinstimmung das Partitionierungsschema verwendet, um die Instanz zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-169">The <see cref="T:System.Fabric.ServicePartitionKind">partitioning scheme</see> specified in the key should match the partitioning scheme used to create the service instance.</span></span>
            </para>
        </param>
        <param name="resolveTimeoutPerTry"><span data-ttu-id="7dd3c-170">Das Timeout überschritten wird, um FabricClient des <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />Methode.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-170">The timeout passed to FabricClient's <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />method.</span></span></param>
        <param name="maxRetryBackoffInterval">
          <para>
            <span data-ttu-id="7dd3c-171">Das maximale Intervall, und wiederholen Sie dann beim Backoff FabricClients <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />Methode, die durch eine Ausnahme mit möglichem Wiederholungsversuch fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-171">The max interval to back-off before retrying when FabricClient's <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />method fails with a retry-able exception.</span></span> <span data-ttu-id="7dd3c-172">Die tatsächlichen Backoff-Intervall ist einem zufälligen Zeitintervall kleiner oder gleich der angegebenen MaxRetryBackoffInterval also.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-172">The actual back off interval is a random time interval which is less than or equal to the specified maxRetryBackoffInterval.</span></span>
            </para>
        </param>
        <param name="cancellationToken">
          <para>
            <span data-ttu-id="7dd3c-173">Das CancellationToken, das diesen Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-173">The CancellationToken that this operation is observing.</span></span> <span data-ttu-id="7dd3c-174">Es wird verwendet, um dem Vorgang zu benachrichtigen, dass es abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-174">It is used to notify the operation that it should be canceled.</span></span>
            </para>
        </param>
        <summary>
            <span data-ttu-id="7dd3c-175">Löst eine Partition des angegebenen Diensts durch den Aufruf des FabricClient <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" /> Methode mit dem angegebenen Timeout und den Back-off/Wiederholen auf Fehler mit möglichem Wiederholungsversuch.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-175">Resolves a partition of the specified service by invoking FabricClient's <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" /> method with the given timeout and back-off/retry on retry-able errors.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7dd3c-176">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-176">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="7dd3c-177">Das Ergebnis von der Aufgabe ist die <see cref="T:System.Fabric.ResolvedServicePartition" /> -Objekt, das die Informationen über die aufgelösten Dienstpartition einschließlich Dienstendpunkte enthält.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-177">The result from the task is the <see cref="T:System.Fabric.ResolvedServicePartition" /> object, that contains the information about the resolved service partition including the service endpoints.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="7dd3c-178">Diese Methode, die bei allen vorübergehende Ausnahmen, die wiederholt werden.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-178">This method retries on all transient exceptions.</span></span> <span data-ttu-id="7dd3c-179">Für Fälle, in denen Sie die maximale Ausführungszeit auf einen dieser Methode beschränken möchten, erstellen Sie eine <see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">, maximale Ausführungszeit zugeordnete Abbruchtoken</see> und dieses Abbruchtoken an diese Methode übergeben.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-179">For cases where you want to limit the max execution time of this method, you should create a <see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">cancellation token associated with that max execution time</see> and pass that cancellation token to this method.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricServiceNotFoundException">
          <para>
            <span data-ttu-id="7dd3c-180">Diese Methode kann eine FabricServiceNotFoundExcepion auslösen, wenn keine Service-Instanz im angegebenen ServiceUri übereinstimmende Cluster vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-180">This method can throw a FabricServiceNotFoundExcepion if there is no service instance in the cluster matching the specified serviceUri.</span></span>
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="7dd3c-181">Dies kann eine FabricException auslösen, wenn es sich bei in der ServicePartitionKey angegebene Schema nicht mit das Schema verwendet, um die Dienstinstanz erstellen übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-181">This can throw a FabricException if the scheme specified in the ServicePartitionKey doesn't match the scheme used to create the service instance.</span></span>
            <span data-ttu-id="7dd3c-182">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/">Fehlern und Ausnahmen</see> für Weitere Informationen.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-182">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/">Errors and Exceptions</see> for more information.</span></span>
            </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="SetDefault">
      <MemberSignature Language="C#" Value="public static void SetDefault (Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver defaultServiceResolver);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetDefault(class Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver defaultServiceResolver) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.SetDefault(Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub SetDefault (defaultServiceResolver As ServicePartitionResolver)" />
      <MemberSignature Language="F#" Value="static member SetDefault : Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver -&gt; unit" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.SetDefault defaultServiceResolver" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="defaultServiceResolver" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" />
      </Parameters>
      <Docs>
        <param name="defaultServiceResolver"><span data-ttu-id="7dd3c-183">Der neue Standardwert</span><span class="sxs-lookup"><span data-stu-id="7dd3c-183">The new default value</span></span></param>
        <summary>
            <span data-ttu-id="7dd3c-184">Die Standardeinstellung ServicePartitionResolver wird aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="7dd3c-184">Updates the default ServicePartitionResolver.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>