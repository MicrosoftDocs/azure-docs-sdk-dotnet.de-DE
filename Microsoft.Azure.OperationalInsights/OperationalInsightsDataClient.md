<Type Name="OperationalInsightsDataClient" FullName="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient">
  <TypeSignature Language="C#" Value="public class OperationalInsightsDataClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient&gt;, IDisposable, Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationalInsightsDataClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient&gt; implements class Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationalInsightsDataClient&#xA;Inherits ServiceClient(Of OperationalInsightsDataClient)&#xA;Implements IDisposable, IOperationalInsightsDataClient" />
  <TypeSignature Language="F#" Value="type OperationalInsightsDataClient = class&#xA;    inherit ServiceClient&lt;OperationalInsightsDataClient&gt;&#xA;    interface IOperationalInsightsDataClient&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>0.9.0.1</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="3fd5d-101">Operational Insights-Data-Client</span><span class="sxs-lookup"><span data-stu-id="3fd5d-101">Operational Insights Data Client</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationalInsightsDataClient (Microsoft.Rest.ServiceClientCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(Microsoft.Rest.ServiceClientCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : Microsoft.Rest.ServiceClientCredentials -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient credentials" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="3fd5d-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-102">Required.</span></span> <span data-ttu-id="3fd5d-103">Abonnementanmeldeinformationen, clientabonnement eindeutig identifiziert werden.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-103">Subscription credentials which uniquely identify client subscription.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3fd5d-104">Initialisiert eine neue Instanz der OperationalInsightsDataClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-104">Initializes a new instance of the OperationalInsightsDataClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="3fd5d-105">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-105">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected OperationalInsightsDataClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            <span data-ttu-id="3fd5d-106">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-106">Optional.</span></span> <span data-ttu-id="3fd5d-107">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-107">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3fd5d-108">Initialisiert eine neue Instanz der OperationalInsightsDataClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-108">Initializes a new instance of the OperationalInsightsDataClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationalInsightsDataClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            <span data-ttu-id="3fd5d-109">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-109">Required.</span></span> <span data-ttu-id="3fd5d-110">Abonnementanmeldeinformationen, clientabonnement eindeutig identifiziert werden.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-110">Subscription credentials which uniquely identify client subscription.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="3fd5d-111">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-111">Optional.</span></span> <span data-ttu-id="3fd5d-112">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-112">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3fd5d-113">Initialisiert eine neue Instanz der OperationalInsightsDataClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-113">Initializes a new instance of the OperationalInsightsDataClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="3fd5d-114">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-114">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected OperationalInsightsDataClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            <span data-ttu-id="3fd5d-115">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-115">Optional.</span></span> <span data-ttu-id="3fd5d-116">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-116">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="3fd5d-117">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-117">Optional.</span></span> <span data-ttu-id="3fd5d-118">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-118">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3fd5d-119">Initialisiert eine neue Instanz der OperationalInsightsDataClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-119">Initializes a new instance of the OperationalInsightsDataClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected OperationalInsightsDataClient (Uri baseUri, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(System.Uri,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : Uri * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient (baseUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            <span data-ttu-id="3fd5d-120">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-120">Optional.</span></span> <span data-ttu-id="3fd5d-121">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-121">The base URI of the service.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="3fd5d-122">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-122">Optional.</span></span> <span data-ttu-id="3fd5d-123">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-123">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3fd5d-124">Initialisiert eine neue Instanz der OperationalInsightsDataClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-124">Initializes a new instance of the OperationalInsightsDataClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="3fd5d-125">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-125">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationalInsightsDataClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            <span data-ttu-id="3fd5d-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-126">Required.</span></span> <span data-ttu-id="3fd5d-127">Abonnementanmeldeinformationen, clientabonnement eindeutig identifiziert werden.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-127">Subscription credentials which uniquely identify client subscription.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="3fd5d-128">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-128">Optional.</span></span> <span data-ttu-id="3fd5d-129">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-129">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="3fd5d-130">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-130">Optional.</span></span> <span data-ttu-id="3fd5d-131">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-131">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3fd5d-132">Initialisiert eine neue Instanz der OperationalInsightsDataClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-132">Initializes a new instance of the OperationalInsightsDataClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="3fd5d-133">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationalInsightsDataClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient (baseUri, credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            <span data-ttu-id="3fd5d-134">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-134">Optional.</span></span> <span data-ttu-id="3fd5d-135">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-135">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="3fd5d-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-136">Required.</span></span> <span data-ttu-id="3fd5d-137">Abonnementanmeldeinformationen, clientabonnement eindeutig identifiziert werden.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-137">Subscription credentials which uniquely identify client subscription.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="3fd5d-138">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-138">Optional.</span></span> <span data-ttu-id="3fd5d-139">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-139">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3fd5d-140">Initialisiert eine neue Instanz der OperationalInsightsDataClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-140">Initializes a new instance of the OperationalInsightsDataClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="3fd5d-141">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-141">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected OperationalInsightsDataClient (Uri baseUri, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(System.Uri,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : Uri * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient (baseUri, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            <span data-ttu-id="3fd5d-142">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-142">Optional.</span></span> <span data-ttu-id="3fd5d-143">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-143">The base URI of the service.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="3fd5d-144">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-144">Optional.</span></span> <span data-ttu-id="3fd5d-145">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-145">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="3fd5d-146">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-146">Optional.</span></span> <span data-ttu-id="3fd5d-147">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-147">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3fd5d-148">Initialisiert eine neue Instanz der OperationalInsightsDataClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-148">Initializes a new instance of the OperationalInsightsDataClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="3fd5d-149">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationalInsightsDataClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient (baseUri, credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            <span data-ttu-id="3fd5d-150">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-150">Optional.</span></span> <span data-ttu-id="3fd5d-151">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-151">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="3fd5d-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-152">Required.</span></span> <span data-ttu-id="3fd5d-153">Abonnementanmeldeinformationen, clientabonnement eindeutig identifiziert werden.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-153">Subscription credentials which uniquely identify client subscription.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="3fd5d-154">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-154">Optional.</span></span> <span data-ttu-id="3fd5d-155">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-155">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="3fd5d-156">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-156">Optional.</span></span> <span data-ttu-id="3fd5d-157">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-157">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3fd5d-158">Initialisiert eine neue Instanz der OperationalInsightsDataClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-158">Initializes a new instance of the OperationalInsightsDataClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="3fd5d-159">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-159">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AdditionalWorkspaces">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AdditionalWorkspaces { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AdditionalWorkspaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.AdditionalWorkspaces" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalWorkspaces As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AdditionalWorkspaces : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.AdditionalWorkspaces" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.AdditionalWorkspaces</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fd5d-160">Zusätzliche Arbeitsbereiche, die in Abfragen mit Cross verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-160">Additional workspaces referenced in cross-resource queries.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fd5d-161">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-161">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fd5d-162">Abonnementanmeldeinformationen, clientabonnement eindeutig identifiziert werden.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-162">Subscription credentials which uniquely identify client subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fd5d-163">Ermittelt oder Json-Deserialisierung Einstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-163">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameHeader">
      <MemberSignature Language="C#" Value="public string NameHeader { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NameHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.NameHeader" />
      <MemberSignature Language="VB.NET" Value="Public Property NameHeader As String" />
      <MemberSignature Language="F#" Value="member this.NameHeader : string with get, set" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.NameHeader" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.NameHeader</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fd5d-164">Eindeutiger Name für die aufrufende Anwendung.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-164">Unique name for the calling application.</span></span> <span data-ttu-id="3fd5d-165">Dies dient lediglich zum Telemetrie und Debuggen.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-165">This is only used for telemetry and debugging.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Preferences">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.OperationalInsights.Models.ApiPreferences Preferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.OperationalInsights.Models.ApiPreferences Preferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.Preferences" />
      <MemberSignature Language="VB.NET" Value="Public Property Preferences As ApiPreferences" />
      <MemberSignature Language="F#" Value="member this.Preferences : Microsoft.Azure.OperationalInsights.Models.ApiPreferences with get, set" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.Preferences" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.Preferences</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.OperationalInsights.Models.ApiPreferences</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fd5d-166">Fragen Sie die Voreinstellungen.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-166">Query preferences.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.Azure.OperationalInsights.Models.QueryResults&gt;&gt; QueryWithHttpMessagesAsync (string query, Nullable&lt;TimeSpan&gt; timespan = null, System.Collections.Generic.IList&lt;string&gt; workspaces = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.Azure.OperationalInsights.Models.QueryResults&gt;&gt; QueryWithHttpMessagesAsync(string query, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timespan, class System.Collections.Generic.IList`1&lt;string&gt; workspaces, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.QueryWithHttpMessagesAsync(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member QueryWithHttpMessagesAsync : string * Nullable&lt;TimeSpan&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.Azure.OperationalInsights.Models.QueryResults&gt;&gt;&#xA;override this.QueryWithHttpMessagesAsync : string * Nullable&lt;TimeSpan&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.Azure.OperationalInsights.Models.QueryResults&gt;&gt;" Usage="operationalInsightsDataClient.QueryWithHttpMessagesAsync (query, timespan, workspaces, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.QueryWithHttpMessagesAsync(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient/&lt;QueryWithHttpMessagesAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.Azure.OperationalInsights.Models.QueryResults&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="timespan" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="workspaces" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query">
            <span data-ttu-id="3fd5d-167">Die auszuführende Abfrage.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-167">The query to execute.</span></span>
            </param>
        <param name="timespan">
            <span data-ttu-id="3fd5d-168">Optional.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-168">Optional.</span></span> <span data-ttu-id="3fd5d-169">Die Zeitspanne für die zum Abfragen von Daten.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-169">The timespan over which to query data.</span></span> <span data-ttu-id="3fd5d-170">Dies ist ein Wert für den Zeitraum ISO8601.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-170">This is an ISO8601 time period value.</span></span>  <span data-ttu-id="3fd5d-171">Diese Zeitspanne wird zusätzlich zu anderen angewendet, die im Abfrageausdruck angegeben sind.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-171">This timespan is applied in addition to any that are specified in the query expression.</span></span>
            </param>
        <param name="workspaces">
            <span data-ttu-id="3fd5d-172">Eine Liste der Arbeitsbereiche, die in der Abfrage enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-172">A list of workspaces that are included in the query.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="3fd5d-173">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-173">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3fd5d-174">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3fd5d-175">Führen Sie eine Analyseabfrage</span><span class="sxs-lookup"><span data-stu-id="3fd5d-175">Execute an Analytics query</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3fd5d-176">Führt eine Analyseabfrage für Daten.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-176">Executes an Analytics query for data.</span></span>
            <span data-ttu-id="3fd5d-177">[Hier](/documentation/2-Using-the-API/Query) ist ein Beispiel für eine Analyseabfrage mit POST.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-177">[Here](/documentation/2-Using-the-API/Query) is an example for using POST with an Analytics query.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.OperationalInsights.Models.ErrorResponseException">
            <span data-ttu-id="3fd5d-178">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-178">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="3fd5d-179">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-179">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3fd5d-180">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-180">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="3fd5d-181">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-181">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="3fd5d-182">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-182">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public string RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As String" />
      <MemberSignature Language="F#" Value="member this.RequestId : string with get, set" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.RequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.RequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fd5d-183">Eine eindeutige ID pro Anforderung.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-183">A unique ID per request.</span></span> <span data-ttu-id="3fd5d-184">Dies wird werden pro Anforderung generiert, wenn kein Wert angegeben.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-184">This will be generated per request if not specified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fd5d-185">Ermittelt oder Json-Serialisierungseinstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-185">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkspaceId">
      <MemberSignature Language="C#" Value="public string WorkspaceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkspaceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.WorkspaceId" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkspaceId As String" />
      <MemberSignature Language="F#" Value="member this.WorkspaceId : string with get, set" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.WorkspaceId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.WorkspaceId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fd5d-186">Die ID des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-186">ID of the workspace.</span></span> <span data-ttu-id="3fd5d-187">Dies ist die Arbeitsbereichs-ID aus dem Blatt "Eigenschaften" im Azure-Portal.</span><span class="sxs-lookup"><span data-stu-id="3fd5d-187">This is Workspace ID from the Properties blade in the Azure portal.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>