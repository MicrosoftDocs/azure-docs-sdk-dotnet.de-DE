<Type Name="DataFactoryManagementClient" FullName="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient">
  <TypeSignature Language="C#" Value="public class DataFactoryManagementClient : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt;, IDisposable, Microsoft.Azure.Management.DataFactories.IDataFactoryManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi DataFactoryManagementClient extends Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt; implements class Microsoft.Azure.Management.DataFactories.IDataFactoryManagementClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class DataFactoryManagementClient&#xA;Inherits ServiceClient(Of DataFactoryManagementClient)&#xA;Implements IDataFactoryManagementClient, IDisposable" />
  <TypeSignature Language="F#" Value="type DataFactoryManagementClient = class&#xA;    inherit ServiceClient&lt;DataFactoryManagementClient&gt;&#xA;    interface IDataFactoryManagementClient&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.DataFactories.IDataFactoryManagementClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="6e52f-101">Client für die Interaktion mit dem Azure Data Factory-Dienst.</span><span class="sxs-lookup"><span data-stu-id="6e52f-101">Client for interacting with the Azure Data Factory service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryManagementClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6e52f-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" /> class.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As SubscriptionCloudCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient : Microsoft.Azure.SubscriptionCloudCredentials -&gt; Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient credentials" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="6e52f-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6e52f-103">Required.</span></span> <span data-ttu-id="6e52f-104">Wenn Sie einen Windows Azure-Abonnement erstellen, wird er eindeutig durch eine Abonnement-ID identifiziert.</span><span class="sxs-lookup"><span data-stu-id="6e52f-104">When you create a Windows Azure subscription, it is uniquely identified by a subscription ID.</span></span> <span data-ttu-id="6e52f-105">Die Abonnement-ID ist Teil der URI für jeden Aufruf, die Sie an die Dienstverwaltungs-API vornehmen.</span><span class="sxs-lookup"><span data-stu-id="6e52f-105">The subscription ID forms part of the URI for every call that you make to the Service Management API.</span></span> <span data-ttu-id="6e52f-106">Der Windows Azure-Dienst ManagementAPI verwenden gegenseitige Authentifizierung von verwaltungszertifikaten über SSL, um sicherzustellen, dass eine Anforderung an den Dienst sicher ist.</span><span class="sxs-lookup"><span data-stu-id="6e52f-106">The Windows Azure Service ManagementAPI use mutual authentication of management certificates over SSL to ensure that a request made to the service is secure.</span></span> <span data-ttu-id="6e52f-107">Keine anonyme Anforderungen sind zulässig.</span><span class="sxs-lookup"><span data-stu-id="6e52f-107">No anonymous requests are allowed.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6e52f-108">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6e52f-108">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" /> class.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryManagementClient (System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.#ctor(System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient : System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient httpClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="httpClient">
            <span data-ttu-id="6e52f-109">Der HTTP-client</span><span class="sxs-lookup"><span data-stu-id="6e52f-109">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="6e52f-110">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6e52f-110">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" /> class.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient (credentials, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="6e52f-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6e52f-111">Required.</span></span> <span data-ttu-id="6e52f-112">Wenn Sie einen Windows Azure-Abonnement erstellen, wird er eindeutig durch eine Abonnement-ID identifiziert.</span><span class="sxs-lookup"><span data-stu-id="6e52f-112">When you create a Windows Azure subscription, it is uniquely identified by a subscription ID.</span></span> <span data-ttu-id="6e52f-113">Die Abonnement-ID ist Teil der URI für jeden Aufruf, die Sie an die Dienstverwaltungs-API vornehmen.</span><span class="sxs-lookup"><span data-stu-id="6e52f-113">The subscription ID forms part of the URI for every call that you make to the Service Management API.</span></span> <span data-ttu-id="6e52f-114">Der Windows Azure-Dienst ManagementAPI verwenden gegenseitige Authentifizierung von verwaltungszertifikaten über SSL, um sicherzustellen, dass eine Anforderung an den Dienst sicher ist.</span><span class="sxs-lookup"><span data-stu-id="6e52f-114">The Windows Azure Service ManagementAPI use mutual authentication of management certificates over SSL to ensure that a request made to the service is secure.</span></span> <span data-ttu-id="6e52f-115">Keine anonyme Anforderungen sind zulässig.</span><span class="sxs-lookup"><span data-stu-id="6e52f-115">No anonymous requests are allowed.</span></span>
            </param>
        <param name="httpClient">
            <span data-ttu-id="6e52f-116">Der HTTP-client</span><span class="sxs-lookup"><span data-stu-id="6e52f-116">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="6e52f-117">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6e52f-117">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As SubscriptionCloudCredentials, baseUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * Uri -&gt; Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient (credentials, baseUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="baseUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="6e52f-118">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6e52f-118">Required.</span></span> <span data-ttu-id="6e52f-119">Wenn Sie einen Windows Azure-Abonnement erstellen, wird er eindeutig durch eine Abonnement-ID identifiziert.</span><span class="sxs-lookup"><span data-stu-id="6e52f-119">When you create a Windows Azure subscription, it is uniquely identified by a subscription ID.</span></span> <span data-ttu-id="6e52f-120">Die Abonnement-ID ist Teil der URI für jeden Aufruf, die Sie an die Dienstverwaltungs-API vornehmen.</span><span class="sxs-lookup"><span data-stu-id="6e52f-120">The subscription ID forms part of the URI for every call that you make to the Service Management API.</span></span> <span data-ttu-id="6e52f-121">Der Windows Azure-Dienst ManagementAPI verwenden gegenseitige Authentifizierung von verwaltungszertifikaten über SSL, um sicherzustellen, dass eine Anforderung an den Dienst sicher ist.</span><span class="sxs-lookup"><span data-stu-id="6e52f-121">The Windows Azure Service ManagementAPI use mutual authentication of management certificates over SSL to ensure that a request made to the service is secure.</span></span> <span data-ttu-id="6e52f-122">Keine anonyme Anforderungen sind zulässig.</span><span class="sxs-lookup"><span data-stu-id="6e52f-122">No anonymous requests are allowed.</span></span>
            </param>
        <param name="baseUri">
            <span data-ttu-id="6e52f-123">Der URI, der als Basis für alle Service Management-Anforderungen verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="6e52f-123">The URI used as the base for all Service Management requests.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6e52f-124">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6e52f-124">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" /> class.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Uri,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * Uri * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" Usage="new Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient (credentials, baseUri, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="6e52f-125">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6e52f-125">Required.</span></span> <span data-ttu-id="6e52f-126">Wenn Sie einen Windows Azure-Abonnement erstellen, wird er eindeutig durch eine Abonnement-ID identifiziert.</span><span class="sxs-lookup"><span data-stu-id="6e52f-126">When you create a Windows Azure subscription, it is uniquely identified by a subscription ID.</span></span> <span data-ttu-id="6e52f-127">Die Abonnement-ID ist Teil der URI für jeden Aufruf, die Sie an die Dienstverwaltungs-API vornehmen.</span><span class="sxs-lookup"><span data-stu-id="6e52f-127">The subscription ID forms part of the URI for every call that you make to the Service Management API.</span></span> <span data-ttu-id="6e52f-128">Der Windows Azure-Dienst ManagementAPI verwenden gegenseitige Authentifizierung von verwaltungszertifikaten über SSL, um sicherzustellen, dass eine Anforderung an den Dienst sicher ist.</span><span class="sxs-lookup"><span data-stu-id="6e52f-128">The Windows Azure Service ManagementAPI use mutual authentication of management certificates over SSL to ensure that a request made to the service is secure.</span></span> <span data-ttu-id="6e52f-129">Keine anonyme Anforderungen sind zulässig.</span><span class="sxs-lookup"><span data-stu-id="6e52f-129">No anonymous requests are allowed.</span></span>
            </param>
        <param name="baseUri">
            <span data-ttu-id="6e52f-130">Optional.</span><span class="sxs-lookup"><span data-stu-id="6e52f-130">Optional.</span></span> <span data-ttu-id="6e52f-131">Der URI, der als Basis für alle Service Management-Anforderungen verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="6e52f-131">The URI used as the base for all Service Management requests.</span></span>
            </param>
        <param name="httpClient">
            <span data-ttu-id="6e52f-132">Der HTTP-client</span><span class="sxs-lookup"><span data-stu-id="6e52f-132">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="6e52f-133">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6e52f-133">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityTypes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.IActivityTypeOperations ActivityTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations ActivityTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.ActivityTypes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityTypes As IActivityTypeOperations" />
      <MemberSignature Language="F#" Value="member this.ActivityTypes : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.ActivityTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.IActivityTypeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-134">Vorgänge zum Verwalten von Data Factory "activitytypes".</span><span class="sxs-lookup"><span data-stu-id="6e52f-134">Operations for managing data factory ActivityTypes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityWindows">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.IActivityWindowOperations ActivityWindows { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations ActivityWindows" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.ActivityWindows" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityWindows As IActivityWindowOperations" />
      <MemberSignature Language="F#" Value="member this.ActivityWindows : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.ActivityWindows" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.IActivityWindowOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-135">Vorgänge zum Verwalten von Windows der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="6e52f-135">Operations for managing activity windows.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.IDataFactoryManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-136">Der URI, der als Basis für alle Service Management-Anforderungen verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="6e52f-136">The URI used as the base for all Service Management requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="protected override void Clone (Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt; client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Clone(class Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt; client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.Clone(Hyak.Common.ServiceClient{Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Clone (client As ServiceClient(Of DataFactoryManagementClient))" />
      <MemberSignature Language="F#" Value="override this.Clone : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt; -&gt; unit" Usage="dataFactoryManagementClient.Clone client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt;" />
      </Parameters>
      <Docs>
        <param name="client">
            <span data-ttu-id="6e52f-137">Instanz des DataFactoryManagementClient zum Klonen in</span><span class="sxs-lookup"><span data-stu-id="6e52f-137">Instance of DataFactoryManagementClient to clone to</span></span>
            </param>
        <summary>
            <span data-ttu-id="6e52f-138">Klont Eigenschaften aus der aktuellen Instanz in eine andere DataFactoryManagementClient-Instanz an.</span><span class="sxs-lookup"><span data-stu-id="6e52f-138">Clones properties from current instance to another DataFactoryManagementClient instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeTypes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.IComputeTypeOperations ComputeTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.IComputeTypeOperations ComputeTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.ComputeTypes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputeTypes As IComputeTypeOperations" />
      <MemberSignature Language="F#" Value="member this.ComputeTypes : Microsoft.Azure.Management.DataFactories.IComputeTypeOperations" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.ComputeTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.IComputeTypeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-139">Vorgänge zum Verwalten von Data Factory ComputeTypes.</span><span class="sxs-lookup"><span data-stu-id="6e52f-139">Operations for managing data factory ComputeTypes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SubscriptionCloudCredentials Credentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SubscriptionCloudCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public Property Credentials As SubscriptionCloudCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.SubscriptionCloudCredentials with get, set" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataFactories.IDataFactoryManagementClient.Credentials</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SubscriptionCloudCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-140">Wenn Sie einen Windows Azure-Abonnement erstellen, wird er eindeutig durch eine Abonnement-ID identifiziert.</span><span class="sxs-lookup"><span data-stu-id="6e52f-140">When you create a Windows Azure subscription, it is uniquely identified by a subscription ID.</span></span> <span data-ttu-id="6e52f-141">Die Abonnement-ID ist Teil der URI für jeden Aufruf, die Sie an die Dienstverwaltungs-API vornehmen.</span><span class="sxs-lookup"><span data-stu-id="6e52f-141">The subscription ID forms part of the URI for every call that you make to the Service Management API.</span></span> <span data-ttu-id="6e52f-142">Der Windows Azure-Dienst ManagementAPI verwenden gegenseitige Authentifizierung von verwaltungszertifikaten über SSL, um sicherzustellen, dass eine Anforderung an den Dienst sicher ist.</span><span class="sxs-lookup"><span data-stu-id="6e52f-142">The Windows Azure Service ManagementAPI use mutual authentication of management certificates over SSL to ensure that a request made to the service is secure.</span></span> <span data-ttu-id="6e52f-143">Keine anonyme Anforderungen sind zulässig.</span><span class="sxs-lookup"><span data-stu-id="6e52f-143">No anonymous requests are allowed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataFactories">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.IDataFactoryOperations DataFactories { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.IDataFactoryOperations DataFactories" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.DataFactories" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataFactories As IDataFactoryOperations" />
      <MemberSignature Language="F#" Value="member this.DataFactories : Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.DataFactories" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.IDataFactoryOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-144">Vorgänge zum Verwalten von Data Factorys.</span><span class="sxs-lookup"><span data-stu-id="6e52f-144">Operations for managing data factories.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Datasets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.IDatasetOperations Datasets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.IDatasetOperations Datasets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.Datasets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Datasets As IDatasetOperations" />
      <MemberSignature Language="F#" Value="member this.Datasets : Microsoft.Azure.Management.DataFactories.IDatasetOperations" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.Datasets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.IDatasetOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-145">Vorgänge zum Verwalten von Datasets.</span><span class="sxs-lookup"><span data-stu-id="6e52f-145">Operations for managing Datasets.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSliceRuns">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.IDataSliceRunOperations DataSliceRuns { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.IDataSliceRunOperations DataSliceRuns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.DataSliceRuns" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataSliceRuns As IDataSliceRunOperations" />
      <MemberSignature Language="F#" Value="member this.DataSliceRuns : Microsoft.Azure.Management.DataFactories.IDataSliceRunOperations" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.DataSliceRuns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.IDataSliceRunOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-146">Vorgänge zum Verwalten von Daten Slice ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="6e52f-146">Operations for managing data slice runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSlices">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.IDataSliceOperations DataSlices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.IDataSliceOperations DataSlices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.DataSlices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataSlices As IDataSliceOperations" />
      <MemberSignature Language="F#" Value="member this.DataSlices : Microsoft.Azure.Management.DataFactories.IDataSliceOperations" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.DataSlices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.IDataSliceOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-147">Vorgänge zum Verwalten von Datenslices.</span><span class="sxs-lookup"><span data-stu-id="6e52f-147">Operations for managing data slices.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Gateways">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.IGatewayOperations Gateways { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.IGatewayOperations Gateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.Gateways" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Gateways As IGatewayOperations" />
      <MemberSignature Language="F#" Value="member this.Gateways : Microsoft.Azure.Management.DataFactories.IGatewayOperations" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.Gateways" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.IGatewayOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-148">Vorgänge zum Verwalten von Data Factory-Gateways.</span><span class="sxs-lookup"><span data-stu-id="6e52f-148">Operations for managing data factory gateways.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Hubs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.IHubOperations Hubs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.IHubOperations Hubs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.Hubs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Hubs As IHubOperations" />
      <MemberSignature Language="F#" Value="member this.Hubs : Microsoft.Azure.Management.DataFactories.IHubOperations" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.Hubs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.IHubOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-149">Vorgänge zum Verwalten von Hubs.</span><span class="sxs-lookup"><span data-stu-id="6e52f-149">Operations for managing hubs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServices">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations LinkedServices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations LinkedServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.LinkedServices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LinkedServices As ILinkedServiceOperations" />
      <MemberSignature Language="F#" Value="member this.LinkedServices : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.LinkedServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-150">Vorgänge zum Verwalten von Data Factory LinkedServices.</span><span class="sxs-lookup"><span data-stu-id="6e52f-150">Operations for managing data factory linkedServices.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationInitialTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationInitialTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationInitialTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.LongRunningOperationInitialTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationInitialTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationInitialTimeout : int with get, set" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.LongRunningOperationInitialTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-151">Ruft ab oder legt das ursprüngliche Timeout für zeitintensive Vorgänge (in Sekunden) fest.</span><span class="sxs-lookup"><span data-stu-id="6e52f-151">Gets or sets the initial timeout for Long Running Operations (in seconds).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : int with get, set" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-152">Ruft ab oder legt das wiederholungstimeout für zeitintensive Vorgänge (in Sekunden) fest.</span><span class="sxs-lookup"><span data-stu-id="6e52f-152">Gets or sets the retry timeout for Long Running Operations (in seconds).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OAuth">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.IOAuthOperations OAuth { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.IOAuthOperations OAuth" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.OAuth" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OAuth As IOAuthOperations" />
      <MemberSignature Language="F#" Value="member this.OAuth : Microsoft.Azure.Management.DataFactories.IOAuthOperations" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.OAuth" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.IOAuthOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-153">Vorgänge für die OAuth-Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="6e52f-153">Operations for OAuth authorization.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pipelines">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.IPipelineOperations Pipelines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.IPipelineOperations Pipelines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.Pipelines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Pipelines As IPipelineOperations" />
      <MemberSignature Language="F#" Value="member this.Pipelines : Microsoft.Azure.Management.DataFactories.IPipelineOperations" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.Pipelines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.IPipelineOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e52f-154">Vorgänge zum Verwalten von Pipelines.</span><span class="sxs-lookup"><span data-stu-id="6e52f-154">Operations for managing pipelines.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterType&lt;T&gt;">
      <MemberSignature Language="C#" Value="public void RegisterType&lt;T&gt; (bool force = false) where T : Microsoft.Azure.Management.DataFactories.Models.TypeProperties;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterType&lt;(class Microsoft.Azure.Management.DataFactories.Models.TypeProperties) T&gt;(bool force) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.RegisterType``1(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterType(Of T As TypeProperties) (Optional force As Boolean = false)" />
      <MemberSignature Language="F#" Value="member this.RegisterType : bool -&gt; unit (requires 'T :&gt; Microsoft.Azure.Management.DataFactories.Models.TypeProperties)" Usage="dataFactoryManagementClient.RegisterType force" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.TypeProperties</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="force" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="force">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeIsRegistered&lt;T&gt;">
      <MemberSignature Language="C#" Value="public bool TypeIsRegistered&lt;T&gt; () where T : Microsoft.Azure.Management.DataFactories.Registration.Models.IRegisteredType;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TypeIsRegistered&lt;(class Microsoft.Azure.Management.DataFactories.Registration.Models.IRegisteredType) T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.TypeIsRegistered``1" />
      <MemberSignature Language="VB.NET" Value="Public Function TypeIsRegistered(Of T As IRegisteredType) () As Boolean" />
      <MemberSignature Language="F#" Value="member this.TypeIsRegistered : unit -&gt; bool (requires 'T :&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.IRegisteredType)" Usage="dataFactoryManagementClient.TypeIsRegistered " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.Azure.Management.DataFactories.Registration.Models.IRegisteredType</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithHandler">
      <MemberSignature Language="C#" Value="protected override Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient WithHandler (Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt; newClient, System.Net.Http.DelegatingHandler handler);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient WithHandler(class Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt; newClient, class System.Net.Http.DelegatingHandler handler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient.WithHandler(Hyak.Common.ServiceClient{Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient},System.Net.Http.DelegatingHandler)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function WithHandler (newClient As ServiceClient(Of DataFactoryManagementClient), handler As DelegatingHandler) As DataFactoryManagementClient" />
      <MemberSignature Language="F#" Value="override this.WithHandler : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt; * System.Net.Http.DelegatingHandler -&gt; Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" Usage="dataFactoryManagementClient.WithHandler (newClient, handler)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newClient" Type="Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt;" />
        <Parameter Name="handler" Type="System.Net.Http.DelegatingHandler" />
      </Parameters>
      <Docs>
        <param name="newClient">To be added.</param>
        <param name="handler">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>