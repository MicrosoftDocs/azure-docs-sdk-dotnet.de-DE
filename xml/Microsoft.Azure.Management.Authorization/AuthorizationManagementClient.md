<Type Name="AuthorizationManagementClient" FullName="Microsoft.Azure.Management.Authorization.AuthorizationManagementClient">
  <TypeSignature Language="C#" Value="public class AuthorizationManagementClient : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.Authorization.AuthorizationManagementClient&gt;, IDisposable, Microsoft.Azure.Management.Authorization.IAuthorizationManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AuthorizationManagementClient extends Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.Authorization.AuthorizationManagementClient&gt; implements class Microsoft.Azure.Management.Authorization.IAuthorizationManagementClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class AuthorizationManagementClient&#xA;Inherits ServiceClient(Of AuthorizationManagementClient)&#xA;Implements IAuthorizationManagementClient, IDisposable" />
  <TypeSignature Language="F#" Value="type AuthorizationManagementClient = class&#xA;    inherit ServiceClient&lt;AuthorizationManagementClient&gt;&#xA;    interface IAuthorizationManagementClient&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.Authorization.AuthorizationManagementClient&gt;</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.Authorization.AuthorizationManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.Authorization.AuthorizationManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Authorization.IAuthorizationManagementClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationManagementClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="07b05-101">Initialisiert eine neue Instanz der AuthorizationManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="07b05-101">Initializes a new instance of the AuthorizationManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As SubscriptionCloudCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Authorization.AuthorizationManagementClient : Microsoft.Azure.SubscriptionCloudCredentials -&gt; Microsoft.Azure.Management.Authorization.AuthorizationManagementClient" Usage="new Microsoft.Azure.Management.Authorization.AuthorizationManagementClient credentials" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="07b05-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="07b05-102">Required.</span></span> <span data-ttu-id="07b05-103">Ruft die abonnementanmeldeinformationen ab Microsoft Azure-Abonnement eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="07b05-103">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="07b05-104">Die Abonnement-ID ist Teil der URI für jeden Dienstaufruf.</span><span class="sxs-lookup"><span data-stu-id="07b05-104">The subscription ID forms part of the URI for every service call.</span></span>
            </param>
        <summary>
            <span data-ttu-id="07b05-105">Initialisiert eine neue Instanz der AuthorizationManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="07b05-105">Initializes a new instance of the AuthorizationManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationManagementClient (System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.#ctor(System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Authorization.AuthorizationManagementClient : System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.Authorization.AuthorizationManagementClient" Usage="new Microsoft.Azure.Management.Authorization.AuthorizationManagementClient httpClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="httpClient">
            <span data-ttu-id="07b05-106">Der HTTP-client</span><span class="sxs-lookup"><span data-stu-id="07b05-106">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="07b05-107">Initialisiert eine neue Instanz der AuthorizationManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="07b05-107">Initializes a new instance of the AuthorizationManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Authorization.AuthorizationManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.Authorization.AuthorizationManagementClient" Usage="new Microsoft.Azure.Management.Authorization.AuthorizationManagementClient (credentials, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="07b05-108">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="07b05-108">Required.</span></span> <span data-ttu-id="07b05-109">Ruft die abonnementanmeldeinformationen ab Microsoft Azure-Abonnement eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="07b05-109">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="07b05-110">Die Abonnement-ID ist Teil der URI für jeden Dienstaufruf.</span><span class="sxs-lookup"><span data-stu-id="07b05-110">The subscription ID forms part of the URI for every service call.</span></span>
            </param>
        <param name="httpClient">
            <span data-ttu-id="07b05-111">Der HTTP-client</span><span class="sxs-lookup"><span data-stu-id="07b05-111">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="07b05-112">Initialisiert eine neue Instanz der AuthorizationManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="07b05-112">Initializes a new instance of the AuthorizationManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As SubscriptionCloudCredentials, baseUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Authorization.AuthorizationManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * Uri -&gt; Microsoft.Azure.Management.Authorization.AuthorizationManagementClient" Usage="new Microsoft.Azure.Management.Authorization.AuthorizationManagementClient (credentials, baseUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="baseUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="07b05-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="07b05-113">Required.</span></span> <span data-ttu-id="07b05-114">Ruft die abonnementanmeldeinformationen ab Microsoft Azure-Abonnement eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="07b05-114">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="07b05-115">Die Abonnement-ID ist Teil der URI für jeden Dienstaufruf.</span><span class="sxs-lookup"><span data-stu-id="07b05-115">The subscription ID forms part of the URI for every service call.</span></span>
            </param>
        <param name="baseUri">
            <span data-ttu-id="07b05-116">Optional.</span><span class="sxs-lookup"><span data-stu-id="07b05-116">Optional.</span></span> <span data-ttu-id="07b05-117">Ruft den URI, der als Basis für alle Cloud-Service-Requests verwendet.</span><span class="sxs-lookup"><span data-stu-id="07b05-117">Gets the URI used as the base for all cloud service requests.</span></span>
            </param>
        <summary>
            <span data-ttu-id="07b05-118">Initialisiert eine neue Instanz der AuthorizationManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="07b05-118">Initializes a new instance of the AuthorizationManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Uri,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Authorization.AuthorizationManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * Uri * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.Authorization.AuthorizationManagementClient" Usage="new Microsoft.Azure.Management.Authorization.AuthorizationManagementClient (credentials, baseUri, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="07b05-119">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="07b05-119">Required.</span></span> <span data-ttu-id="07b05-120">Ruft die abonnementanmeldeinformationen ab Microsoft Azure-Abonnement eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="07b05-120">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="07b05-121">Die Abonnement-ID ist Teil der URI für jeden Dienstaufruf.</span><span class="sxs-lookup"><span data-stu-id="07b05-121">The subscription ID forms part of the URI for every service call.</span></span>
            </param>
        <param name="baseUri">
            <span data-ttu-id="07b05-122">Optional.</span><span class="sxs-lookup"><span data-stu-id="07b05-122">Optional.</span></span> <span data-ttu-id="07b05-123">Ruft den URI, der als Basis für alle Cloud-Service-Requests verwendet.</span><span class="sxs-lookup"><span data-stu-id="07b05-123">Gets the URI used as the base for all cloud service requests.</span></span>
            </param>
        <param name="httpClient">
            <span data-ttu-id="07b05-124">Der HTTP-client</span><span class="sxs-lookup"><span data-stu-id="07b05-124">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="07b05-125">Initialisiert eine neue Instanz der AuthorizationManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="07b05-125">Initializes a new instance of the AuthorizationManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Authorization.IAuthorizationManagementClient.ApiVersion</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07b05-126">Ruft die API-Version ab.</span><span class="sxs-lookup"><span data-stu-id="07b05-126">Gets the API version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="APIVersion">
      <MemberSignature Language="C#" Value="public const string APIVersion;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string APIVersion" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.APIVersion" />
      <MemberSignature Language="VB.NET" Value="Public Const APIVersion As String " />
      <MemberSignature Language="F#" Value="val mutable APIVersion : string" Usage="Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.APIVersion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Authorization.IAuthorizationManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07b05-127">Ruft den URI, der als Basis für alle Cloud-Service-Requests verwendet.</span><span class="sxs-lookup"><span data-stu-id="07b05-127">Gets the URI used as the base for all cloud service requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClassicAdministrators">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Authorization.IClassicAdministratorOperations ClassicAdministrators { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Authorization.IClassicAdministratorOperations ClassicAdministrators" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.ClassicAdministrators" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property ClassicAdministrators As IClassicAdministratorOperations" />
      <MemberSignature Language="F#" Value="member this.ClassicAdministrators : Microsoft.Azure.Management.Authorization.IClassicAdministratorOperations" Usage="Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.ClassicAdministrators" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Authorization.IAuthorizationManagementClient.ClassicAdministrators</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.IClassicAdministratorOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07b05-128">Rufen Sie Details des klassischen Administrators (http://TBD für Weitere Informationen siehe)</span><span class="sxs-lookup"><span data-stu-id="07b05-128">Get classic administrator details  (see http://TBD for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="protected override void Clone (Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.Authorization.AuthorizationManagementClient&gt; client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Clone(class Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.Authorization.AuthorizationManagementClient&gt; client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.Clone(Hyak.Common.ServiceClient{Microsoft.Azure.Management.Authorization.AuthorizationManagementClient})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Clone (client As ServiceClient(Of AuthorizationManagementClient))" />
      <MemberSignature Language="F#" Value="override this.Clone : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.Authorization.AuthorizationManagementClient&gt; -&gt; unit" Usage="authorizationManagementClient.Clone client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.Authorization.AuthorizationManagementClient&gt;" />
      </Parameters>
      <Docs>
        <param name="client">
            <span data-ttu-id="07b05-129">Instanz des AuthorizationManagementClient zum Klonen in</span><span class="sxs-lookup"><span data-stu-id="07b05-129">Instance of AuthorizationManagementClient to clone to</span></span>
            </param>
        <summary>
            <span data-ttu-id="07b05-130">Klont Eigenschaften aus der aktuellen Instanz in eine andere AuthorizationManagementClient-Instanz</span><span class="sxs-lookup"><span data-stu-id="07b05-130">Clones properties from current instance to another AuthorizationManagementClient instance</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SubscriptionCloudCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SubscriptionCloudCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As SubscriptionCloudCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.SubscriptionCloudCredentials" Usage="Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Authorization.IAuthorizationManagementClient.Credentials</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SubscriptionCloudCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07b05-131">Ruft die abonnementanmeldeinformationen ab Microsoft Azure-Abonnement eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="07b05-131">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="07b05-132">Die Abonnement-ID ist Teil der URI für jeden Dienstaufruf.</span><span class="sxs-lookup"><span data-stu-id="07b05-132">The subscription ID forms part of the URI for every service call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationInitialTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationInitialTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationInitialTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.LongRunningOperationInitialTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationInitialTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationInitialTimeout : int with get, set" Usage="Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.LongRunningOperationInitialTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Authorization.IAuthorizationManagementClient.LongRunningOperationInitialTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07b05-133">Ruft ab oder legt das ursprüngliche Timeout für zeitintensive Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="07b05-133">Gets or sets the initial timeout for Long Running Operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : int with get, set" Usage="Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Authorization.IAuthorizationManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07b05-134">Ruft ab oder legt das wiederholungstimeout für zeitintensive Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="07b05-134">Gets or sets the retry timeout for Long Running Operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Authorization.IPermissionOperations Permissions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Authorization.IPermissionOperations Permissions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.Permissions" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Permissions As IPermissionOperations" />
      <MemberSignature Language="F#" Value="member this.Permissions : Microsoft.Azure.Management.Authorization.IPermissionOperations" Usage="Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.Permissions" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Authorization.IAuthorizationManagementClient.Permissions</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.IPermissionOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07b05-135">Rufen Sie oder Ressource Gruppenberechtigungen (http://TBD für Weitere Informationen siehe ab)</span><span class="sxs-lookup"><span data-stu-id="07b05-135">Get resource or resource group permissions  (see http://TBD for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RoleAssignments">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations RoleAssignments { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations RoleAssignments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.RoleAssignments" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property RoleAssignments As IRoleAssignmentOperations" />
      <MemberSignature Language="F#" Value="member this.RoleAssignments : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" Usage="Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.RoleAssignments" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Authorization.IAuthorizationManagementClient.RoleAssignments</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07b05-136">TBD (http://TBD für Weitere Informationen siehe)</span><span class="sxs-lookup"><span data-stu-id="07b05-136">TBD  (see http://TBD for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RoleDefinitions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations RoleDefinitions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations RoleDefinitions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.RoleDefinitions" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property RoleDefinitions As IRoleDefinitionOperations" />
      <MemberSignature Language="F#" Value="member this.RoleDefinitions : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" Usage="Microsoft.Azure.Management.Authorization.AuthorizationManagementClient.RoleDefinitions" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Authorization.IAuthorizationManagementClient.RoleDefinitions</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07b05-137">TBD (http://TBD für Weitere Informationen siehe)</span><span class="sxs-lookup"><span data-stu-id="07b05-137">TBD  (see http://TBD for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>