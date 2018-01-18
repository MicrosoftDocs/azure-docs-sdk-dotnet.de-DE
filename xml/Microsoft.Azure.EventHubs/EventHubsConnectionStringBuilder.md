<Type Name="EventHubsConnectionStringBuilder" FullName="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder">
  <TypeSignature Language="C#" Value="public class EventHubsConnectionStringBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventHubsConnectionStringBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class EventHubsConnectionStringBuilder" />
  <TypeSignature Language="F#" Value="type EventHubsConnectionStringBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2585b-101">EventHubsConnectionStringBuilder kann verwendet werden, um eine Verbindungszeichenfolge erstellen. diese Kommunikation mit Event Hubs Entitäten herstellen können.</span><span class="sxs-lookup"><span data-stu-id="2585b-101">EventHubsConnectionStringBuilder can be used to construct a connection string which can establish communication with Event Hubs entities.</span></span>
            <span data-ttu-id="2585b-102">Sie können auch die grundlegende Validierung auf eine vorhandene Verbindungszeichenfolge verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="2585b-102">It can also be used to perform basic validation on an existing connection string.</span></span>
            <span data-ttu-id="2585b-103"><para />Eine Verbindungszeichenfolge ist im Grunde eine Zeichenfolge von Schlüssel-Wert-Paar senkrechter umfasste ";".</span><span class="sxs-lookup"><span data-stu-id="2585b-103"><para /> A connection string is basically a string consisted of key-value pair separated by ";".</span></span> <span data-ttu-id="2585b-104">Grundlegende Format ist "&lt;Schlüssel&gt;=&lt;Wert&gt;[;&lt; Schlüssel&gt;=&lt;Wert&gt;] ", in dem unterstützten Schlüsselname lautet wie folgt: <para /> Endpunkt - URL, die der Event Hubs-Namespace enthält <para /> EntityPath - den Pfad an den Event Hub Entität <para /> SharedAccessKeyName - der entsprechenden freigegebenen Zugriffsrichtlinie im Schlüsselnamen für den Namespace oder Entität.</span><span class="sxs-lookup"><span data-stu-id="2585b-104">Basic format is "&lt;key&gt;=&lt;value&gt;[;&lt;key&gt;=&lt;value&gt;]" where supported key name are as follow: <para /> Endpoint - the URL that contains the Event Hubs namespace <para /> EntityPath - the path to the Event Hub entity <para /> SharedAccessKeyName - the key name to the corresponding shared access policy rule for the namespace, or entity.</span></span>
            <span data-ttu-id="2585b-105"><para />SharedAccessKey - Schlüssel für die entsprechenden SAS-Richtlinienregel des Namespace oder der Entität.</span><span class="sxs-lookup"><span data-stu-id="2585b-105"><para /> SharedAccessKey - the key for the corresponding shared access policy rule of the namespace or entity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
    <example>
            <span data-ttu-id="2585b-106">Beispielcode:</span><span class="sxs-lookup"><span data-stu-id="2585b-106">Sample code:</span></span>
            <code>
            var connectionStringBuiler = new EventHubsConnectionStringBuilder(
                "amqps://EventHubsNamespaceName.servicebus.windows.net", 
                "EventHubsEntityName", // Event Hub Name 
                "SharedAccessSignatureKeyName", 
                "SharedAccessSignatureKey");
             string connectionString = connectionStringBuiler.ToString();
            </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsConnectionStringBuilder (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder : string -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="2585b-107">"ConnectionString" Ereignis-Hubs</span><span class="sxs-lookup"><span data-stu-id="2585b-107">Event Hubs ConnectionString</span></span></param>
        <summary>
            <span data-ttu-id="2585b-108">ConnectionString-Format: Endpunkt = Sb: / / Namespace_DNS_Name; EntityPath = EVENT_HUB_NAME; SharedAccessKeyName = SHARED_ACCESS_KEY_NAME; SharedAccessKey = SHARED_ACCESS_KEY</span><span class="sxs-lookup"><span data-stu-id="2585b-108">ConnectionString format: Endpoint=sb://namespace_DNS_Name;EntityPath=EVENT_HUB_NAME;SharedAccessKeyName=SHARED_ACCESS_KEY_NAME;SharedAccessKey=SHARED_ACCESS_KEY</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsConnectionStringBuilder (Uri endpointAddress, string entityPath, string sharedAccessKeyName, string sharedAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri endpointAddress, string entityPath, string sharedAccessKeyName, string sharedAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.#ctor(System.Uri,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpointAddress As Uri, entityPath As String, sharedAccessKeyName As String, sharedAccessKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder : Uri * string * string * string -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder (endpointAddress, entityPath, sharedAccessKeyName, sharedAccessKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessKeyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="2585b-109">Vollständig qualifizierten Domänennamen für Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="2585b-109">Fully qualified domain name for Event Hubs.</span></span> <span data-ttu-id="2585b-110">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="2585b-110">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="entityPath"><span data-ttu-id="2585b-111">Pfad der Entität oder Event Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="2585b-111">Entity path or Event Hub name.</span></span></param>
        <param name="sharedAccessKeyName"><span data-ttu-id="2585b-112">Freigegebene Zugriffsschlüssel-name</span><span class="sxs-lookup"><span data-stu-id="2585b-112">Shared Access Key name</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="2585b-113">SAS-Schlüssel</span><span class="sxs-lookup"><span data-stu-id="2585b-113">Shared Access Key</span></span></param>
        <summary>
            <span data-ttu-id="2585b-114">Erstellen Sie eine Verbindungszeichenfolge Ereignisformat<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></span><span class="sxs-lookup"><span data-stu-id="2585b-114">Build a connection string consumable by <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsConnectionStringBuilder (Uri endpointAddress, string entityPath, string sharedAccessSignature, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri endpointAddress, string entityPath, string sharedAccessSignature, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.#ctor(System.Uri,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpointAddress As Uri, entityPath As String, sharedAccessSignature As String, operationTimeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder : Uri * string * string * TimeSpan -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder (endpointAddress, entityPath, sharedAccessSignature, operationTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessSignature" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="2585b-115">Vollständig qualifizierten Domänennamen für Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="2585b-115">Fully qualified domain name for Event Hubs.</span></span> <span data-ttu-id="2585b-116">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="2585b-116">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="entityPath"><span data-ttu-id="2585b-117">Pfad der Entität oder Event Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="2585b-117">Entity path or Event Hub name.</span></span></param>
        <param name="sharedAccessSignature"><span data-ttu-id="2585b-118">Shared Access Signature (SAS)</span><span class="sxs-lookup"><span data-stu-id="2585b-118">Shared Access Signature</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="2585b-119">Timeout des Vorgangs für Event Hubs-Vorgänge</span><span class="sxs-lookup"><span data-stu-id="2585b-119">Operation timeout for Event Hubs operations</span></span></param>
        <summary>
            <span data-ttu-id="2585b-120">Erstellen Sie eine Verbindungszeichenfolge Ereignisformat<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></span><span class="sxs-lookup"><span data-stu-id="2585b-120">Build a connection string consumable by <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsConnectionStringBuilder (Uri endpointAddress, string entityPath, string sharedAccessKeyName, string sharedAccessKey, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri endpointAddress, string entityPath, string sharedAccessKeyName, string sharedAccessKey, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.#ctor(System.Uri,System.String,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpointAddress As Uri, entityPath As String, sharedAccessKeyName As String, sharedAccessKey As String, operationTimeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder : Uri * string * string * string * TimeSpan -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder (endpointAddress, entityPath, sharedAccessKeyName, sharedAccessKey, operationTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessKeyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="2585b-121">Vollständig qualifizierten Domänennamen für Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="2585b-121">Fully qualified domain name for Event Hubs.</span></span> <span data-ttu-id="2585b-122">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="2585b-122">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="entityPath"><span data-ttu-id="2585b-123">Pfad der Entität oder Event Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="2585b-123">Entity path or Event Hub name.</span></span></param>
        <param name="sharedAccessKeyName"><span data-ttu-id="2585b-124">Freigegebene Zugriffsschlüssel-name</span><span class="sxs-lookup"><span data-stu-id="2585b-124">Shared Access Key name</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="2585b-125">SAS-Schlüssel</span><span class="sxs-lookup"><span data-stu-id="2585b-125">Shared Access Key</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="2585b-126">Timeout des Vorgangs für Event Hubs-Vorgänge</span><span class="sxs-lookup"><span data-stu-id="2585b-126">Operation timeout for Event Hubs operations</span></span></param>
        <summary>
            <span data-ttu-id="2585b-127">Erstellen Sie eine Verbindungszeichenfolge Ereignisformat<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></span><span class="sxs-lookup"><span data-stu-id="2585b-127">Build a connection string consumable by <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As EventHubsConnectionStringBuilder" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="eventHubsConnectionStringBuilder.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2585b-128">Erstellt ein geklontes Objekt des aktuellen <see cref="T:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" />.</span><span class="sxs-lookup"><span data-stu-id="2585b-128">Creates a cloned object of the current <see cref="T:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" />.</span></span>
            </summary>
        <returns><span data-ttu-id="2585b-129">Ein neues<see cref="T:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" /></span><span class="sxs-lookup"><span data-stu-id="2585b-129">A new <see cref="T:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" /></span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public Uri Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.Endpoint : Uri with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2585b-130">Abrufen oder festlegen den Event Hubs-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="2585b-130">Gets or sets the Event Hubs endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.EntityPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2585b-131">Der Pfadwert Entität aus der Verbindungszeichenfolge abrufen</span><span class="sxs-lookup"><span data-stu-id="2585b-131">Get the entity path value from the connection string</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2585b-132">OperationTimeout ist in fehlerhaften Situationen auf, die den Aufrufer über die relevanten benachrichtigen angewendet.<see cref="T:Microsoft.Azure.EventHubs.EventHubsException" /></span><span class="sxs-lookup"><span data-stu-id="2585b-132">OperationTimeout is applied in erroneous situations to notify the caller about the relevant <see cref="T:Microsoft.Azure.EventHubs.EventHubsException" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasKey">
      <MemberSignature Language="C#" Value="public string SasKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SasKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SasKey As String" />
      <MemberSignature Language="F#" Value="member this.SasKey : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SasKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2585b-133">Den Schlüsselwert der SAS-Richtlinie aus der Verbindungszeichenfolge abrufen</span><span class="sxs-lookup"><span data-stu-id="2585b-133">Get the shared access policy key value from the connection string</span></span>
            </summary>
        <value><span data-ttu-id="2585b-134">Freigegebenen SAS-Schlüssel</span><span class="sxs-lookup"><span data-stu-id="2585b-134">Shared Access Signature key</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasKeyName">
      <MemberSignature Language="C#" Value="public string SasKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SasKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SasKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SasKeyName : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SasKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2585b-135">Die SAS-Richtliniennamen Besitzer aus der Verbindungszeichenfolge abrufen</span><span class="sxs-lookup"><span data-stu-id="2585b-135">Get the shared access policy owner name from the connection string</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessSignature">
      <MemberSignature Language="C#" Value="public string SharedAccessSignature { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessSignature" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SharedAccessSignature" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessSignature As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessSignature : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SharedAccessSignature" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2585b-136">Ermittelt oder definiert das SAS-Zugriffstoken.</span><span class="sxs-lookup"><span data-stu-id="2585b-136">Gets or sets the SAS access token.</span></span>
            </summary>
        <value><span data-ttu-id="2585b-137">Shared Access Signature (SAS)</span><span class="sxs-lookup"><span data-stu-id="2585b-137">Shared Access Signature</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="eventHubsConnectionStringBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2585b-138">Gibt eine interoperable Verbindungszeichenfolge, die zur Verbindung mit Event Hubs-Namespace verwendet werden können</span><span class="sxs-lookup"><span data-stu-id="2585b-138">Returns an interoperable connection string that can be used to connect to Event Hubs Namespace</span></span>
            </summary>
        <returns><span data-ttu-id="2585b-139">die Verbindungszeichenfolge</span><span class="sxs-lookup"><span data-stu-id="2585b-139">the connection string</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransportType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.TransportType TransportType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.EventHubs.TransportType TransportType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.TransportType" />
      <MemberSignature Language="VB.NET" Value="Public Property TransportType As TransportType" />
      <MemberSignature Language="F#" Value="member this.TransportType : Microsoft.Azure.EventHubs.TransportType with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.TransportType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.TransportType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2585b-140">Der Transporttyp für die Clientverbindung.</span><span class="sxs-lookup"><span data-stu-id="2585b-140">Transport type for the client connection.</span></span>
            <span data-ttu-id="2585b-141">Verfügbaren Optionen sind Amqp und AmqpWebSockets.</span><span class="sxs-lookup"><span data-stu-id="2585b-141">Avaiable options are Amqp and AmqpWebSockets.</span></span>
            <span data-ttu-id="2585b-142">Der Standardwert ist Amqp, wenn nicht angegeben.</span><span class="sxs-lookup"><span data-stu-id="2585b-142">Defaults to Amqp if not specified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>