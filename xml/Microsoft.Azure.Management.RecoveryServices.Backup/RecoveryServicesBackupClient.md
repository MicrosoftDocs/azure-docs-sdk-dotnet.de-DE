<Type Name="RecoveryServicesBackupClient" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient">
  <TypeSignature Language="C#" Value="public class RecoveryServicesBackupClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient&gt;, IDisposable, Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecoveryServicesBackupClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient&gt; implements class Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient" />
  <TypeSignature Language="VB.NET" Value="Public Class RecoveryServicesBackupClient&#xA;Inherits ServiceClient(Of RecoveryServicesBackupClient)&#xA;Implements IAzureClient, IDisposable, IRecoveryServicesBackupClient" />
  <TypeSignature Language="F#" Value="type RecoveryServicesBackupClient = class&#xA;    inherit ServiceClient&lt;RecoveryServicesBackupClient&gt;&#xA;    interface IRecoveryServicesBackupClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient</InterfaceName>
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
            <span data-ttu-id="8bd7d-101">Öffnen Sie die API 2.0-Spezifikationen für Azure RecoveryServices-Sicherungsdienst</span><span class="sxs-lookup"><span data-stu-id="8bd7d-101">Open API 2.0 Specs for Azure RecoveryServices Backup service</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RecoveryServicesBackupClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="8bd7d-102">Optional.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-102">Optional.</span></span> <span data-ttu-id="8bd7d-103">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-103">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8bd7d-104">Initialisiert eine neue Instanz der RecoveryServicesBackupClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-104">Initializes a new instance of the RecoveryServicesBackupClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecoveryServicesBackupClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="8bd7d-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-105">Required.</span></span> <span data-ttu-id="8bd7d-106">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-106">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="8bd7d-107">Optional.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-107">Optional.</span></span> <span data-ttu-id="8bd7d-108">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-108">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8bd7d-109">Initialisiert eine neue Instanz der RecoveryServicesBackupClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-109">Initializes a new instance of the RecoveryServicesBackupClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="8bd7d-110">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RecoveryServicesBackupClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="8bd7d-111">Optional.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-111">Optional.</span></span> <span data-ttu-id="8bd7d-112">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-112">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="8bd7d-113">Optional.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-113">Optional.</span></span> <span data-ttu-id="8bd7d-114">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-114">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8bd7d-115">Initialisiert eine neue Instanz der RecoveryServicesBackupClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-115">Initializes a new instance of the RecoveryServicesBackupClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RecoveryServicesBackupClient (Uri baseUri, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.#ctor(System.Uri,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient : Uri * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient (baseUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="8bd7d-116">Optional.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-116">Optional.</span></span> <span data-ttu-id="8bd7d-117">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-117">The base URI of the service.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="8bd7d-118">Optional.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-118">Optional.</span></span> <span data-ttu-id="8bd7d-119">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-119">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8bd7d-120">Initialisiert eine neue Instanz der RecoveryServicesBackupClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-120">Initializes a new instance of the RecoveryServicesBackupClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="8bd7d-121">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecoveryServicesBackupClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="8bd7d-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-122">Required.</span></span> <span data-ttu-id="8bd7d-123">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-123">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="8bd7d-124">Optional.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-124">Optional.</span></span> <span data-ttu-id="8bd7d-125">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-125">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="8bd7d-126">Optional.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-126">Optional.</span></span> <span data-ttu-id="8bd7d-127">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-127">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8bd7d-128">Initialisiert eine neue Instanz der RecoveryServicesBackupClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-128">Initializes a new instance of the RecoveryServicesBackupClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="8bd7d-129">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecoveryServicesBackupClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient (baseUri, credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="8bd7d-130">Optional.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-130">Optional.</span></span> <span data-ttu-id="8bd7d-131">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-131">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="8bd7d-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-132">Required.</span></span> <span data-ttu-id="8bd7d-133">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-133">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="8bd7d-134">Optional.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-134">Optional.</span></span> <span data-ttu-id="8bd7d-135">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-135">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8bd7d-136">Initialisiert eine neue Instanz der RecoveryServicesBackupClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-136">Initializes a new instance of the RecoveryServicesBackupClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="8bd7d-137">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RecoveryServicesBackupClient (Uri baseUri, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.#ctor(System.Uri,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient : Uri * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient (baseUri, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="8bd7d-138">Optional.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-138">Optional.</span></span> <span data-ttu-id="8bd7d-139">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-139">The base URI of the service.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="8bd7d-140">Optional.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-140">Optional.</span></span> <span data-ttu-id="8bd7d-141">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-141">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="8bd7d-142">Optional.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-142">Optional.</span></span> <span data-ttu-id="8bd7d-143">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-143">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8bd7d-144">Initialisiert eine neue Instanz der RecoveryServicesBackupClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-144">Initializes a new instance of the RecoveryServicesBackupClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="8bd7d-145">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecoveryServicesBackupClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient (baseUri, credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="8bd7d-146">Optional.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-146">Optional.</span></span> <span data-ttu-id="8bd7d-147">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-147">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="8bd7d-148">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-148">Required.</span></span> <span data-ttu-id="8bd7d-149">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-149">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="8bd7d-150">Optional.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-150">Optional.</span></span> <span data-ttu-id="8bd7d-151">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-151">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="8bd7d-152">Optional.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-152">Optional.</span></span> <span data-ttu-id="8bd7d-153">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-153">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8bd7d-154">Initialisiert eine neue Instanz der RecoveryServicesBackupClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-154">Initializes a new instance of the RecoveryServicesBackupClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="8bd7d-155">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-155">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-156">Ruft ab oder legt die bevorzugte Sprache für die Antwort.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-156">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupEngines">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations BackupEngines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations BackupEngines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupEngines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupEngines As IBackupEnginesOperations" />
      <MemberSignature Language="F#" Value="member this.BackupEngines : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupEngines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-157">Ruft die IBackupEnginesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-157">Gets the IBackupEnginesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupJobs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations BackupJobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations BackupJobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupJobs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupJobs As IBackupJobsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupJobs : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupJobs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-158">Ruft die IBackupJobsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-158">Gets the IBackupJobsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupOperationResults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations BackupOperationResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations BackupOperationResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupOperationResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupOperationResults As IBackupOperationResultsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupOperationResults : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupOperationResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-159">Ruft die IBackupOperationResultsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-159">Gets the IBackupOperationResultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupOperationStatuses">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations BackupOperationStatuses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations BackupOperationStatuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupOperationStatuses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupOperationStatuses As IBackupOperationStatusesOperations" />
      <MemberSignature Language="F#" Value="member this.BackupOperationStatuses : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupOperationStatuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-160">Ruft die IBackupOperationStatusesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-160">Gets the IBackupOperationStatusesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations BackupPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations BackupPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupPolicies As IBackupPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.BackupPolicies : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-161">Ruft die IBackupPoliciesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-161">Gets the IBackupPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupProtectableItems">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations BackupProtectableItems { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations BackupProtectableItems" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupProtectableItems" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupProtectableItems As IBackupProtectableItemsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupProtectableItems : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupProtectableItems" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-162">Ruft die IBackupProtectableItemsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-162">Gets the IBackupProtectableItemsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupProtectedItems">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectedItemsOperations BackupProtectedItems { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectedItemsOperations BackupProtectedItems" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupProtectedItems" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupProtectedItems As IBackupProtectedItemsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupProtectedItems : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectedItemsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupProtectedItems" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectedItemsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-163">Ruft die IBackupProtectedItemsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-163">Gets the IBackupProtectedItemsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupProtectionContainers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations BackupProtectionContainers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations BackupProtectionContainers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupProtectionContainers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupProtectionContainers As IBackupProtectionContainersOperations" />
      <MemberSignature Language="F#" Value="member this.BackupProtectionContainers : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupProtectionContainers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-164">Ruft die IBackupProtectionContainersOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-164">Gets the IBackupProtectionContainersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupResourceStorageConfigs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations BackupResourceStorageConfigs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations BackupResourceStorageConfigs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupResourceStorageConfigs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupResourceStorageConfigs As IBackupResourceStorageConfigsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupResourceStorageConfigs : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupResourceStorageConfigs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-165">Ruft die IBackupResourceStorageConfigsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-165">Gets the IBackupResourceStorageConfigsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupResourceVaultConfigs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations BackupResourceVaultConfigs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations BackupResourceVaultConfigs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupResourceVaultConfigs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupResourceVaultConfigs As IBackupResourceVaultConfigsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupResourceVaultConfigs : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupResourceVaultConfigs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-166">Ruft die IBackupResourceVaultConfigsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-166">Gets the IBackupResourceVaultConfigsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Backups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations Backups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations Backups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.Backups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Backups As IBackupsOperations" />
      <MemberSignature Language="F#" Value="member this.Backups : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.Backups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-167">Ruft die IBackupsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-167">Gets the IBackupsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupUsageSummaries">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations BackupUsageSummaries { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations BackupUsageSummaries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupUsageSummaries" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupUsageSummaries As IBackupUsageSummariesOperations" />
      <MemberSignature Language="F#" Value="member this.BackupUsageSummaries : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BackupUsageSummaries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-168">Ruft die IBackupUsageSummariesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-168">Gets the IBackupUsageSummariesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-169">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-169">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-170">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-170">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-171">Ermittelt oder Json-Deserialisierung Einstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-171">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportJobsOperationResults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations ExportJobsOperationResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations ExportJobsOperationResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ExportJobsOperationResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExportJobsOperationResults As IExportJobsOperationResultsOperations" />
      <MemberSignature Language="F#" Value="member this.ExportJobsOperationResults : Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ExportJobsOperationResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-172">Ruft die IExportJobsOperationResultsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-172">Gets the IExportJobsOperationResultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-173">Bei Festlegung werden auf einen eindeutigen X-ms-Client-Request-Id-Wert "true" generiert und in jeder Anforderung enthalten.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-173">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="8bd7d-174">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-174">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ItemLevelRecoveryConnections">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations ItemLevelRecoveryConnections { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations ItemLevelRecoveryConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ItemLevelRecoveryConnections" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ItemLevelRecoveryConnections As IItemLevelRecoveryConnectionsOperations" />
      <MemberSignature Language="F#" Value="member this.ItemLevelRecoveryConnections : Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ItemLevelRecoveryConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-175">Ruft die IItemLevelRecoveryConnectionsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-175">Gets the IItemLevelRecoveryConnectionsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobCancellations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations JobCancellations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations JobCancellations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.JobCancellations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobCancellations As IJobCancellationsOperations" />
      <MemberSignature Language="F#" Value="member this.JobCancellations : Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.JobCancellations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-176">Ruft die IJobCancellationsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-176">Gets the IJobCancellationsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations JobDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations JobDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.JobDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobDetails As IJobDetailsOperations" />
      <MemberSignature Language="F#" Value="member this.JobDetails : Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.JobDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-177">Ruft die IJobDetailsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-177">Gets the IJobDetailsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobOperationResults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations JobOperationResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations JobOperationResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.JobOperationResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobOperationResults As IJobOperationResultsOperations" />
      <MemberSignature Language="F#" Value="member this.JobOperationResults : Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.JobOperationResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-178">Ruft die IJobOperationResultsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-178">Gets the IJobOperationResultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Jobs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations Jobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations Jobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.Jobs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Jobs As IJobsOperations" />
      <MemberSignature Language="F#" Value="member this.Jobs : Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.Jobs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-179">Ruft die IJobsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-179">Gets the IJobsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-180">Ruft ab oder legt das wiederholungstimeout in Sekunden für zeitintensive Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-180">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span>
            <span data-ttu-id="8bd7d-181">Standardwert ist 30.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-181">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IOperations Operations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IOperations Operations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.Operations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operations As IOperations" />
      <MemberSignature Language="F#" Value="member this.Operations : Microsoft.Azure.Management.RecoveryServices.Backup.IOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.Operations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-182">Ruft die IOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-182">Gets the IOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItemOperationResults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations ProtectedItemOperationResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations ProtectedItemOperationResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectedItemOperationResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectedItemOperationResults As IProtectedItemOperationResultsOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectedItemOperationResults : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectedItemOperationResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-183">Ruft die IProtectedItemOperationResultsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-183">Gets the IProtectedItemOperationResultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItemOperationStatuses">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations ProtectedItemOperationStatuses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations ProtectedItemOperationStatuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectedItemOperationStatuses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectedItemOperationStatuses As IProtectedItemOperationStatusesOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectedItemOperationStatuses : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectedItemOperationStatuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-184">Ruft die IProtectedItemOperationStatusesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-184">Gets the IProtectedItemOperationStatusesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItems">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations ProtectedItems { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations ProtectedItems" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectedItems" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectedItems As IProtectedItemsOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectedItems : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectedItems" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-185">Ruft die IProtectedItemsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-185">Gets the IProtectedItemsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionContainerOperationResults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations ProtectionContainerOperationResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations ProtectionContainerOperationResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectionContainerOperationResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectionContainerOperationResults As IProtectionContainerOperationResultsOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectionContainerOperationResults : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectionContainerOperationResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-186">Ruft die IProtectionContainerOperationResultsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-186">Gets the IProtectionContainerOperationResultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionContainerRefreshOperationResults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations ProtectionContainerRefreshOperationResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations ProtectionContainerRefreshOperationResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectionContainerRefreshOperationResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectionContainerRefreshOperationResults As IProtectionContainerRefreshOperationResultsOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectionContainerRefreshOperationResults : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectionContainerRefreshOperationResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-187">Ruft die IProtectionContainerRefreshOperationResultsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-187">Gets the IProtectionContainerRefreshOperationResultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionContainers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations ProtectionContainers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations ProtectionContainers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectionContainers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectionContainers As IProtectionContainersOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectionContainers : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectionContainers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-188">Ruft die IProtectionContainersOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-188">Gets the IProtectionContainersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations ProtectionPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations ProtectionPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectionPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectionPolicies As IProtectionPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectionPolicies : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectionPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-189">Ruft die IProtectionPoliciesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-189">Gets the IProtectionPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionPolicyOperationResults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationResultsOperations ProtectionPolicyOperationResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationResultsOperations ProtectionPolicyOperationResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectionPolicyOperationResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectionPolicyOperationResults As IProtectionPolicyOperationResultsOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectionPolicyOperationResults : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationResultsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectionPolicyOperationResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationResultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-190">Ruft die IProtectionPolicyOperationResultsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-190">Gets the IProtectionPolicyOperationResultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionPolicyOperationStatuses">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations ProtectionPolicyOperationStatuses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations ProtectionPolicyOperationStatuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectionPolicyOperationStatuses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectionPolicyOperationStatuses As IProtectionPolicyOperationStatusesOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectionPolicyOperationStatuses : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.ProtectionPolicyOperationStatuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-191">Ruft die IProtectionPolicyOperationStatusesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-191">Gets the IProtectionPolicyOperationStatusesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPoints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations RecoveryPoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations RecoveryPoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.RecoveryPoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecoveryPoints As IRecoveryPointsOperations" />
      <MemberSignature Language="F#" Value="member this.RecoveryPoints : Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.RecoveryPoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-192">Ruft die IRecoveryPointsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-192">Gets the IRecoveryPointsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restores">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations Restores { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations Restores" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.Restores" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Restores As IRestoresOperations" />
      <MemberSignature Language="F#" Value="member this.Restores : Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.Restores" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-193">Ruft die IRestoresOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-193">Gets the IRestoresOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityPINs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations SecurityPINs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations SecurityPINs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.SecurityPINs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecurityPINs As ISecurityPINsOperations" />
      <MemberSignature Language="F#" Value="member this.SecurityPINs : Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.SecurityPINs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-194">Ruft die ISecurityPINsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-194">Gets the ISecurityPINsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-195">Ermittelt oder Json-Serialisierungseinstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-195">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryServicesBackupClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.SubscriptionId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bd7d-196">Die Abonnement-Id.</span><span class="sxs-lookup"><span data-stu-id="8bd7d-196">The subscription Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>