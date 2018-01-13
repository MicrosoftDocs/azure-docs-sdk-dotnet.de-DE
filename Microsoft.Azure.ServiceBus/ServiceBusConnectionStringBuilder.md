<Type Name="ServiceBusConnectionStringBuilder" FullName="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder">
  <TypeSignature Language="C#" Value="public class ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceBusConnectionStringBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="F#" Value="type ServiceBusConnectionStringBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5e124-101">Zum Generieren von Service Bus-Verbindungszeichenfolgen verwendet.</span><span class="sxs-lookup"><span data-stu-id="5e124-101">Used to generate Service Bus connection strings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5e124-102">Instanziiert eine neue<see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /></span><span class="sxs-lookup"><span data-stu-id="5e124-102">Instantiates a new <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder : string -&gt; Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" Usage="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="5e124-103">Verbindungszeichenfolge für den Namespace oder die Entität.</span><span class="sxs-lookup"><span data-stu-id="5e124-103">Connection string for namespace or the entity.</span></span></param>
        <summary>
            <span data-ttu-id="5e124-104">Instanziiert eine neue <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />.</span><span class="sxs-lookup"><span data-stu-id="5e124-104">Instantiates a new <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder (string endpoint, string entityPath, string sharedAccessSignature);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string entityPath, string sharedAccessSignature) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpoint As String, entityPath As String, sharedAccessSignature As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder : string * string * string -&gt; Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" Usage="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder (endpoint, entityPath, sharedAccessSignature)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessSignature" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="5e124-105">Vollqualifizierte Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="5e124-105">Fully qualified endpoint.</span></span></param>
        <param name="entityPath">To be added.</param>
        <param name="sharedAccessSignature">To be added.</param>
        <summary>
            <span data-ttu-id="5e124-106">Instanziiert eine neue <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />.</span><span class="sxs-lookup"><span data-stu-id="5e124-106">Instantiates a new <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <example>
          <code>
            <span data-ttu-id="5e124-107">ConnectionStringBuilder Var = neue ServiceBusConnectionStringBuilder ("contoso.servicebus.windows.net", "MyQueue", "{... SAS-Token...} ");</span><span class="sxs-lookup"><span data-stu-id="5e124-107">var connectionStringBuilder = new ServiceBusConnectionStringBuilder( "contoso.servicebus.windows.net", "myQueue", "{ ... SAS token ... }" );</span></span>
                </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder (string endpoint, string entityPath, string sharedAccessSignature, Microsoft.Azure.ServiceBus.TransportType transportType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string entityPath, string sharedAccessSignature, valuetype Microsoft.Azure.ServiceBus.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.#ctor(System.String,System.String,System.String,Microsoft.Azure.ServiceBus.TransportType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder : string * string * string * Microsoft.Azure.ServiceBus.TransportType -&gt; Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" Usage="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder (endpoint, entityPath, sharedAccessSignature, transportType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessSignature" Type="System.String" />
        <Parameter Name="transportType" Type="Microsoft.Azure.ServiceBus.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="5e124-108">Vollqualifizierte Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="5e124-108">Fully qualified endpoint.</span></span></param>
        <param name="entityPath">To be added.</param>
        <param name="sharedAccessSignature">To be added.</param>
        <param name="transportType">To be added.</param>
        <summary>
            <span data-ttu-id="5e124-109">Instanziiert eine neue <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />.</span><span class="sxs-lookup"><span data-stu-id="5e124-109">Instantiates a new <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <example>
          <code>
            <span data-ttu-id="5e124-110">ConnectionStringBuilder Var = neue ServiceBusConnectionStringBuilder ("contoso.servicebus.windows.net", "MyQueue", "{... SAS-Token...} ", TransportType.Amqp);</span><span class="sxs-lookup"><span data-stu-id="5e124-110">var connectionStringBuilder = new ServiceBusConnectionStringBuilder( "contoso.servicebus.windows.net", "myQueue", "{ ... SAS token ... }", TransportType.Amqp );</span></span>
                </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder (string endpoint, string entityPath, string sharedAccessKeyName, string sharedAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string entityPath, string sharedAccessKeyName, string sharedAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpoint As String, entityPath As String, sharedAccessKeyName As String, sharedAccessKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder : string * string * string * string -&gt; Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" Usage="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder (endpoint, entityPath, sharedAccessKeyName, sharedAccessKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessKeyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="5e124-111">Vollqualifizierte Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="5e124-111">Fully qualified endpoint.</span></span></param>
        <param name="entityPath"><span data-ttu-id="5e124-112">Der Pfad zu der Entität.</span><span class="sxs-lookup"><span data-stu-id="5e124-112">Path to the entity.</span></span></param>
        <param name="sharedAccessKeyName"><span data-ttu-id="5e124-113">Name der gemeinsamen Zugriff Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="5e124-113">Shared access key name.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="5e124-114">SAS-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="5e124-114">Shared access key.</span></span></param>
        <summary>
            <span data-ttu-id="5e124-115">Instanziiert eine neue <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />.</span><span class="sxs-lookup"><span data-stu-id="5e124-115">Instantiates a new <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <example>
          <code>
            <span data-ttu-id="5e124-116">ConnectionStringBuilder Var = neue ServiceBusConnectionStringBuilder ("contoso.servicebus.windows.net", "MyQueue", "RootManageSharedAccessKey", "&amp;Lt; SharedAccessKey&amp;Gt;);</span><span class="sxs-lookup"><span data-stu-id="5e124-116">var connectionStringBuilder = new ServiceBusConnectionStringBuilder( "contoso.servicebus.windows.net", "myQueue", "RootManageSharedAccessKey", "&amp;lt;sharedAccessKey&amp;gt; );</span></span>
                </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder (string endpoint, string entityPath, string sharedAccessKeyName, string sharedAccessKey, Microsoft.Azure.ServiceBus.TransportType transportType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string entityPath, string sharedAccessKeyName, string sharedAccessKey, valuetype Microsoft.Azure.ServiceBus.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.ServiceBus.TransportType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder : string * string * string * string * Microsoft.Azure.ServiceBus.TransportType -&gt; Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" Usage="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder (endpoint, entityPath, sharedAccessKeyName, sharedAccessKey, transportType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessKeyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="transportType" Type="Microsoft.Azure.ServiceBus.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="5e124-117">Vollqualifizierte Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="5e124-117">Fully qualified endpoint.</span></span></param>
        <param name="entityPath">To be added.</param>
        <param name="sharedAccessKeyName">To be added.</param>
        <param name="sharedAccessKey">To be added.</param>
        <param name="transportType">To be added.</param>
        <summary>
            <span data-ttu-id="5e124-118">Instanziiert eine neue <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />.</span><span class="sxs-lookup"><span data-stu-id="5e124-118">Instantiates a new <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <example>
          <code>
            <span data-ttu-id="5e124-119">ConnectionStringBuilder Var = neue ServiceBusConnectionStringBuilder ("contoso.servicebus.windows.net", "MyQueue", "RootManageSharedAccessKey", "&amp;Lt; SharedAccessKey&amp;Gt; TransportType.Amqp);</span><span class="sxs-lookup"><span data-stu-id="5e124-119">var connectionStringBuilder = new ServiceBusConnectionStringBuilder( "contoso.servicebus.windows.net", "myQueue", "RootManageSharedAccessKey", "&amp;lt;sharedAccessKey&amp;gt;, TransportType.Amqp );</span></span>
                </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string with get, set" Usage="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5e124-120">Vollständig qualifizierten Domänennamen des Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="5e124-120">Fully qualified domain name of the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <example>
          <code><span data-ttu-id="5e124-121">Diese. Endpunkt = contoso.servicebus.windows.net</span><span class="sxs-lookup"><span data-stu-id="5e124-121">this.Endpoint = contoso.servicebus.windows.net</span></span></code>
        </example>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5e124-122">Löst aus, wenn der Endpunkt nicht vollqualifizierte Endpunkt ist.</span><span class="sxs-lookup"><span data-stu-id="5e124-122">Throws when endpoint is not fully qualified endpoint.</span></span></exception>
        <exception cref="T:System.UriFormatException"><span data-ttu-id="5e124-123">Löst aus, wenn der Hostname kann nicht analysiert werden</span><span class="sxs-lookup"><span data-stu-id="5e124-123">Throws when the hostname cannot be parsed</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string with get, set" Usage="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5e124-124">Der Pfadwert Entität aus der Verbindungszeichenfolge abrufen</span><span class="sxs-lookup"><span data-stu-id="5e124-124">Get the entity path value from the connection string</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEntityConnectionString">
      <MemberSignature Language="C#" Value="public string GetEntityConnectionString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetEntityConnectionString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.GetEntityConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEntityConnectionString () As String" />
      <MemberSignature Language="F#" Value="member this.GetEntityConnectionString : unit -&gt; string" Usage="serviceBusConnectionStringBuilder.GetEntityConnectionString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5e124-125">Gibt eine interoperable Verbindungszeichenfolge, die zur Verbindung mit der angegebenen Service Bus-Entität verwendet werden können</span><span class="sxs-lookup"><span data-stu-id="5e124-125">Returns an interoperable connection string that can be used to connect to the given ServiceBus Entity</span></span>
            </summary>
        <returns><span data-ttu-id="5e124-126">Entitätsverbindungszeichenfolge</span><span class="sxs-lookup"><span data-stu-id="5e124-126">Entity connection string</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNamespaceConnectionString">
      <MemberSignature Language="C#" Value="public string GetNamespaceConnectionString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetNamespaceConnectionString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.GetNamespaceConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNamespaceConnectionString () As String" />
      <MemberSignature Language="F#" Value="member this.GetNamespaceConnectionString : unit -&gt; string" Usage="serviceBusConnectionStringBuilder.GetNamespaceConnectionString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5e124-127">Gibt eine interoperable Verbindungszeichenfolge, die zum Herstellen von Verbindungen ServiceBus Namespace verwendet werden kann</span><span class="sxs-lookup"><span data-stu-id="5e124-127">Returns an interoperable connection string that can be used to connect to ServiceBus Namespace</span></span>
            </summary>
        <returns><span data-ttu-id="5e124-128">Namespace-Verbindungszeichenfolge</span><span class="sxs-lookup"><span data-stu-id="5e124-128">Namespace connection string</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasKey">
      <MemberSignature Language="C#" Value="public string SasKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.SasKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SasKey As String" />
      <MemberSignature Language="F#" Value="member this.SasKey : string with get, set" Usage="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.SasKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5e124-129">Den Schlüsselwert der SAS-Richtlinie aus der Verbindungszeichenfolge abrufen</span><span class="sxs-lookup"><span data-stu-id="5e124-129">Get the shared access policy key value from the connection string</span></span>
            </summary>
        <value><span data-ttu-id="5e124-130">Freigegebenen SAS-Schlüssel</span><span class="sxs-lookup"><span data-stu-id="5e124-130">Shared Access Signature key</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasKeyName">
      <MemberSignature Language="C#" Value="public string SasKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.SasKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SasKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SasKeyName : string with get, set" Usage="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.SasKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5e124-131">Die SAS-Richtliniennamen Besitzer aus der Verbindungszeichenfolge abrufen</span><span class="sxs-lookup"><span data-stu-id="5e124-131">Get the shared access policy owner name from the connection string</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasToken">
      <MemberSignature Language="C#" Value="public string SasToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.SasToken" />
      <MemberSignature Language="VB.NET" Value="Public Property SasToken As String" />
      <MemberSignature Language="F#" Value="member this.SasToken : string with get, set" Usage="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.SasToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5e124-132">Die SAS-token von Abrufen der Verbindungszeichenfolge</span><span class="sxs-lookup"><span data-stu-id="5e124-132">Get the shared access signature token from the connection string</span></span>
            </summary>
        <value><span data-ttu-id="5e124-133">Freigegebene Access Signature-token</span><span class="sxs-lookup"><span data-stu-id="5e124-133">Shared Access Signature token</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceBusConnectionStringBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5e124-134">Gibt eine interoperable Verbindungszeichenfolge, die zum Herstellen von Verbindungen ServiceBus Namespace verwendet werden kann</span><span class="sxs-lookup"><span data-stu-id="5e124-134">Returns an interoperable connection string that can be used to connect to ServiceBus Namespace</span></span>
            </summary>
        <returns><span data-ttu-id="5e124-135">die Verbindungszeichenfolge</span><span class="sxs-lookup"><span data-stu-id="5e124-135">The connection string</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransportType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.TransportType TransportType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.ServiceBus.TransportType TransportType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.TransportType" />
      <MemberSignature Language="VB.NET" Value="Public Property TransportType As TransportType" />
      <MemberSignature Language="F#" Value="member this.TransportType : Microsoft.Azure.ServiceBus.TransportType with get, set" Usage="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.TransportType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.TransportType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5e124-136">Rufen Sie den Transporttyp aus der Verbindungszeichenfolge</span><span class="sxs-lookup"><span data-stu-id="5e124-136">Get the transport type from the connection string</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>