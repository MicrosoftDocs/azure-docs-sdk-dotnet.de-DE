<Type Name="RecoveryServicesClient" FullName="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient">
  <TypeSignature Language="C#" Value="public class RecoveryServicesClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient&gt;, IDisposable, Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecoveryServicesClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient&gt; implements class Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient" />
  <TypeSignature Language="VB.NET" Value="Public Class RecoveryServicesClient&#xA;Inherits ServiceClient(Of RecoveryServicesClient)&#xA;Implements IAzureClient, IDisposable, IRecoveryServicesClient" />
  <TypeSignature Language="F#" Value="type RecoveryServicesClient = class&#xA;    inherit ServiceClient&lt;RecoveryServicesClient&gt;&#xA;    interface IRecoveryServicesClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IAzureClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="6bc00-101">Zusammengesetzte Swagger für Recovery Services-Client</span><span class="sxs-lookup"><span data-stu-id="6bc00-101">Composite Swagger for Recovery Services Client</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RecoveryServicesClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient" Usage="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="handlers">
            <span data-ttu-id="6bc00-102">Optional.</span><span class="sxs-lookup"><span data-stu-id="6bc00-102">Optional.</span></span> <span data-ttu-id="6bc00-103">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="6bc00-103">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6bc00-104">Initialisiert eine neue Instanz der RecoveryServicesClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6bc00-104">Initializes a new instance of the RecoveryServicesClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecoveryServicesClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient" Usage="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="6bc00-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6bc00-105">Required.</span></span> <span data-ttu-id="6bc00-106">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6bc00-106">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="6bc00-107">Optional.</span><span class="sxs-lookup"><span data-stu-id="6bc00-107">Optional.</span></span> <span data-ttu-id="6bc00-108">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="6bc00-108">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6bc00-109">Initialisiert eine neue Instanz der RecoveryServicesClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6bc00-109">Initializes a new instance of the RecoveryServicesClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="6bc00-110">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="6bc00-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RecoveryServicesClient (System.Net.Http.HttpClient httpClient, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClient httpClient, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.#ctor(System.Net.Http.HttpClient,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient : System.Net.Http.HttpClient * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient" Usage="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient (httpClient, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="httpClient">To be added.</param>
        <param name="handlers">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RecoveryServicesClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient" Usage="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="rootHandler">
            <span data-ttu-id="6bc00-111">Optional.</span><span class="sxs-lookup"><span data-stu-id="6bc00-111">Optional.</span></span> <span data-ttu-id="6bc00-112">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="6bc00-112">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="6bc00-113">Optional.</span><span class="sxs-lookup"><span data-stu-id="6bc00-113">Optional.</span></span> <span data-ttu-id="6bc00-114">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="6bc00-114">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6bc00-115">Initialisiert eine neue Instanz der RecoveryServicesClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6bc00-115">Initializes a new instance of the RecoveryServicesClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RecoveryServicesClient (Uri baseUri, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.#ctor(System.Uri,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient : Uri * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient" Usage="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient (baseUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            <span data-ttu-id="6bc00-116">Optional.</span><span class="sxs-lookup"><span data-stu-id="6bc00-116">Optional.</span></span> <span data-ttu-id="6bc00-117">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="6bc00-117">The base URI of the service.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="6bc00-118">Optional.</span><span class="sxs-lookup"><span data-stu-id="6bc00-118">Optional.</span></span> <span data-ttu-id="6bc00-119">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="6bc00-119">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6bc00-120">Initialisiert eine neue Instanz der RecoveryServicesClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6bc00-120">Initializes a new instance of the RecoveryServicesClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="6bc00-121">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="6bc00-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecoveryServicesClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient" Usage="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="6bc00-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6bc00-122">Required.</span></span> <span data-ttu-id="6bc00-123">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6bc00-123">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="6bc00-124">Optional.</span><span class="sxs-lookup"><span data-stu-id="6bc00-124">Optional.</span></span> <span data-ttu-id="6bc00-125">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="6bc00-125">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="6bc00-126">Optional.</span><span class="sxs-lookup"><span data-stu-id="6bc00-126">Optional.</span></span> <span data-ttu-id="6bc00-127">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="6bc00-127">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6bc00-128">Initialisiert eine neue Instanz der RecoveryServicesClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6bc00-128">Initializes a new instance of the RecoveryServicesClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="6bc00-129">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="6bc00-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecoveryServicesClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient" Usage="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient (baseUri, credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            <span data-ttu-id="6bc00-130">Optional.</span><span class="sxs-lookup"><span data-stu-id="6bc00-130">Optional.</span></span> <span data-ttu-id="6bc00-131">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="6bc00-131">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="6bc00-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6bc00-132">Required.</span></span> <span data-ttu-id="6bc00-133">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6bc00-133">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="6bc00-134">Optional.</span><span class="sxs-lookup"><span data-stu-id="6bc00-134">Optional.</span></span> <span data-ttu-id="6bc00-135">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="6bc00-135">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6bc00-136">Initialisiert eine neue Instanz der RecoveryServicesClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6bc00-136">Initializes a new instance of the RecoveryServicesClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="6bc00-137">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="6bc00-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RecoveryServicesClient (Uri baseUri, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.#ctor(System.Uri,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient : Uri * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient" Usage="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient (baseUri, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            <span data-ttu-id="6bc00-138">Optional.</span><span class="sxs-lookup"><span data-stu-id="6bc00-138">Optional.</span></span> <span data-ttu-id="6bc00-139">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="6bc00-139">The base URI of the service.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="6bc00-140">Optional.</span><span class="sxs-lookup"><span data-stu-id="6bc00-140">Optional.</span></span> <span data-ttu-id="6bc00-141">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="6bc00-141">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="6bc00-142">Optional.</span><span class="sxs-lookup"><span data-stu-id="6bc00-142">Optional.</span></span> <span data-ttu-id="6bc00-143">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="6bc00-143">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6bc00-144">Initialisiert eine neue Instanz der RecoveryServicesClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6bc00-144">Initializes a new instance of the RecoveryServicesClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="6bc00-145">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="6bc00-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecoveryServicesClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient" Usage="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient (baseUri, credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            <span data-ttu-id="6bc00-146">Optional.</span><span class="sxs-lookup"><span data-stu-id="6bc00-146">Optional.</span></span> <span data-ttu-id="6bc00-147">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="6bc00-147">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="6bc00-148">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6bc00-148">Required.</span></span> <span data-ttu-id="6bc00-149">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6bc00-149">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="6bc00-150">Optional.</span><span class="sxs-lookup"><span data-stu-id="6bc00-150">Optional.</span></span> <span data-ttu-id="6bc00-151">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="6bc00-151">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="6bc00-152">Optional.</span><span class="sxs-lookup"><span data-stu-id="6bc00-152">Optional.</span></span> <span data-ttu-id="6bc00-153">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="6bc00-153">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6bc00-154">Initialisiert eine neue Instanz der RecoveryServicesClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6bc00-154">Initializes a new instance of the RecoveryServicesClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="6bc00-155">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="6bc00-155">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecoveryServicesClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClient httpClient, bool disableDispose, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClient httpClient, bool disableDispose, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClient,System.Boolean,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClient * bool * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient" Usage="new Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient (baseUri, credentials, httpClient, disableDispose, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
        <Parameter Name="disableDispose" Type="System.Boolean" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">To be added.</param>
        <param name="credentials">To be added.</param>
        <param name="httpClient">To be added.</param>
        <param name="disableDispose">To be added.</param>
        <param name="handlers">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-156">Ruft ab oder legt die bevorzugte Sprache für die Antwort.</span><span class="sxs-lookup"><span data-stu-id="6bc00-156">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupStorageConfigs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations BackupStorageConfigs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations BackupStorageConfigs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.BackupStorageConfigs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupStorageConfigs As IBackupStorageConfigsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupStorageConfigs : Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.BackupStorageConfigs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-157">Ruft die IBackupStorageConfigsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="6bc00-157">Gets the IBackupStorageConfigsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupVaultConfigs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations BackupVaultConfigs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations BackupVaultConfigs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.BackupVaultConfigs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupVaultConfigs As IBackupVaultConfigsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupVaultConfigs : Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.BackupVaultConfigs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-158">Ruft die IBackupVaultConfigsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="6bc00-158">Gets the IBackupVaultConfigsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-159">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="6bc00-159">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-160">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6bc00-160">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-161">Ermittelt oder Json-Deserialisierung Einstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="6bc00-161">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected override void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.Dispose : bool -&gt; unit" Usage="recoveryServicesClient.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-162">Bei Festlegung werden auf einen eindeutigen X-ms-Client-Request-Id-Wert "true" generiert und in jeder Anforderung enthalten.</span><span class="sxs-lookup"><span data-stu-id="6bc00-162">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="6bc00-163">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="6bc00-163">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-164">Ruft ab oder legt das wiederholungstimeout in Sekunden für zeitintensive Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="6bc00-164">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span>
            <span data-ttu-id="6bc00-165">Standardwert ist 30.</span><span class="sxs-lookup"><span data-stu-id="6bc00-165">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IOperations Operations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IOperations Operations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.Operations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operations As IOperations" />
      <MemberSignature Language="F#" Value="member this.Operations : Microsoft.Azure.Management.RecoveryServices.IOperations" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.Operations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-166">Ruft die IOperations ab.</span><span class="sxs-lookup"><span data-stu-id="6bc00-166">Gets the IOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredIdentities">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations RegisteredIdentities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations RegisteredIdentities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.RegisteredIdentities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegisteredIdentities As IRegisteredIdentitiesOperations" />
      <MemberSignature Language="F#" Value="member this.RegisteredIdentities : Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.RegisteredIdentities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-167">Ruft die IRegisteredIdentitiesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="6bc00-167">Gets the IRegisteredIdentitiesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationUsages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations ReplicationUsages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations ReplicationUsages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.ReplicationUsages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationUsages As IReplicationUsagesOperations" />
      <MemberSignature Language="F#" Value="member this.ReplicationUsages : Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.ReplicationUsages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-168">Ruft die IReplicationUsagesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="6bc00-168">Gets the IReplicationUsagesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-169">Ermittelt oder Json-Serialisierungseinstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="6bc00-169">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.SubscriptionId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-170">Die Abonnement-Id.</span><span class="sxs-lookup"><span data-stu-id="6bc00-170">The subscription Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Usages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IUsagesOperations Usages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IUsagesOperations Usages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.Usages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Usages As IUsagesOperations" />
      <MemberSignature Language="F#" Value="member this.Usages : Microsoft.Azure.Management.RecoveryServices.IUsagesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.Usages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IUsagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-171">Ruft die IUsagesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="6bc00-171">Gets the IUsagesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VaultCertificates">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations VaultCertificates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations VaultCertificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.VaultCertificates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VaultCertificates As IVaultCertificatesOperations" />
      <MemberSignature Language="F#" Value="member this.VaultCertificates : Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.VaultCertificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-172">Ruft die IVaultCertificatesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="6bc00-172">Gets the IVaultCertificatesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VaultExtendedInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations VaultExtendedInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations VaultExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.VaultExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VaultExtendedInfo As IVaultExtendedInfoOperations" />
      <MemberSignature Language="F#" Value="member this.VaultExtendedInfo : Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.VaultExtendedInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-173">Ruft die IVaultExtendedInfoOperations ab.</span><span class="sxs-lookup"><span data-stu-id="6bc00-173">Gets the IVaultExtendedInfoOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Vaults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IVaultsOperations Vaults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IVaultsOperations Vaults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.Vaults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Vaults As IVaultsOperations" />
      <MemberSignature Language="F#" Value="member this.Vaults : Microsoft.Azure.Management.RecoveryServices.IVaultsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.RecoveryServicesClient.Vaults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IVaultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bc00-174">Ruft die IVaultsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="6bc00-174">Gets the IVaultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>