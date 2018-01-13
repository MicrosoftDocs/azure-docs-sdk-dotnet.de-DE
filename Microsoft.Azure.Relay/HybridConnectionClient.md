<Type Name="HybridConnectionClient" FullName="Microsoft.Azure.Relay.HybridConnectionClient">
  <TypeSignature Language="C#" Value="public class HybridConnectionClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HybridConnectionClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.HybridConnectionClient" />
  <TypeSignature Language="VB.NET" Value="Public Class HybridConnectionClient" />
  <TypeSignature Language="F#" Value="type HybridConnectionClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f7968-101">Stellt einen Client für das neue Sendeseite HybridConnections initiieren.</span><span class="sxs-lookup"><span data-stu-id="f7968-101">Provides a client for initiating new send-side HybridConnections.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionClient (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionClient : string -&gt; Microsoft.Azure.Relay.HybridConnectionClient" Usage="new Microsoft.Azure.Relay.HybridConnectionClient connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="f7968-102">Die zu verwendende Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="f7968-102">The connection string to use.</span></span>  <span data-ttu-id="f7968-103">Diese Verbindungszeichenfolge muss die EntityPath-Eigenschaft enthalten.</span><span class="sxs-lookup"><span data-stu-id="f7968-103">This connection string must include the EntityPath property.</span></span></param>
        <summary><span data-ttu-id="f7968-104">Erstellt eine neue Instanz der <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" /> unter Verwendung der angegebenen Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="f7968-104">Creates a new instance of <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" /> using the specified connection string.</span></span></summary>
        <returns><span data-ttu-id="f7968-105">Das neu erstellte <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" /> Instanz.</span><span class="sxs-lookup"><span data-stu-id="f7968-105">The newly created <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" /> instance.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="f7968-106">Wird ausgelöst, wenn das Format der <paramref name="connectionString" /> Parameter ist falsch.</span><span class="sxs-lookup"><span data-stu-id="f7968-106">Thrown when the format of the <paramref name="connectionString" /> parameter is incorrect.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionClient (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionClient : Uri -&gt; Microsoft.Azure.Relay.HybridConnectionClient" Usage="new Microsoft.Azure.Relay.HybridConnectionClient address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="f7968-107">Die Adresse, an der HybridConnections überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f7968-107">The address on which to listen for HybridConnections.</span></span>  <span data-ttu-id="f7968-108">Diese Adresse muss im Format "sb://contoso.servicebus.windows.net/yourhybridconnection".</span><span class="sxs-lookup"><span data-stu-id="f7968-108">This address should be of the format "sb://contoso.servicebus.windows.net/yourhybridconnection".</span></span></param>
        <summary>
            <span data-ttu-id="f7968-109">Erstellen Sie eine neue Instanz der HybridConnectionClient zum Initiieren von HybridConnections, in denen keine Clientauthentifizierung erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="f7968-109">Create a new HybridConnectionClient instance for initiating HybridConnections where no client authentication is required.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionClient (string connectionString, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String, path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionClient : string * string -&gt; Microsoft.Azure.Relay.HybridConnectionClient" Usage="new Microsoft.Azure.Relay.HybridConnectionClient (connectionString, path)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="f7968-110">Die verwendete Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="f7968-110">The connection string used.</span></span> <span data-ttu-id="f7968-111">Diese Verbindungszeichenfolge muss die EntityPath-Eigenschaft nicht enthalten.</span><span class="sxs-lookup"><span data-stu-id="f7968-111">This connection string must not include the EntityPath property.</span></span></param>
        <param name="path"><span data-ttu-id="f7968-112">Der Pfad zu der HybridConnection.</span><span class="sxs-lookup"><span data-stu-id="f7968-112">The path to the HybridConnection.</span></span></param>
        <summary><span data-ttu-id="f7968-113">Erstellt eine neue Instanz der <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" /> eine Verbindungszeichenfolge sowie der angegebenen HybridConection Pfad.</span><span class="sxs-lookup"><span data-stu-id="f7968-113">Creates a new instance of <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" /> from a connection string and the specified HybridConection path.</span></span> <span data-ttu-id="f7968-114">Verwenden Sie diese Überladung nur, wenn die Verbindungszeichenfolge nicht verwendet die <see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.EntityPath" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f7968-114">Use this overload only when the connection string does not use the <see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.EntityPath" /> property.</span></span></summary>
        <returns><span data-ttu-id="f7968-115">Der erstellte <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" />.</span><span class="sxs-lookup"><span data-stu-id="f7968-115">The created <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="f7968-116">Wird ausgelöst, wenn das Format der <paramref name="connectionString" /> Parameter ist falsch.</span><span class="sxs-lookup"><span data-stu-id="f7968-116">Thrown when the format of the <paramref name="connectionString" /> parameter is incorrect.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionClient (Uri address, Microsoft.Azure.Relay.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.Azure.Relay.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.#ctor(System.Uri,Microsoft.Azure.Relay.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionClient : Uri * Microsoft.Azure.Relay.TokenProvider -&gt; Microsoft.Azure.Relay.HybridConnectionClient" Usage="new Microsoft.Azure.Relay.HybridConnectionClient (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.Relay.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="f7968-117">Die Adresse, an der HybridConnections überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f7968-117">The address on which to listen for HybridConnections.</span></span>  <span data-ttu-id="f7968-118">Diese Adresse muss im Format "sb://contoso.servicebus.windows.net/yourhybridconnection".</span><span class="sxs-lookup"><span data-stu-id="f7968-118">This address should be of the format "sb://contoso.servicebus.windows.net/yourhybridconnection".</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="f7968-119">Zum Herstellen einer Verbindung mit Service Bus die TokenProvider dar.</span><span class="sxs-lookup"><span data-stu-id="f7968-119">The TokenProvider for connecting to ServiceBus.</span></span></param>
        <summary>
            <span data-ttu-id="f7968-120">Erstellen Sie eine neue Instanz der HybridConnectionClient zum Initiieren von HybridConnections mit Clientauthentifizierung.</span><span class="sxs-lookup"><span data-stu-id="f7968-120">Create a new HybridConnectionClient instance for initiating HybridConnections with client authentication.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionClient.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.Azure.Relay.HybridConnectionClient.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7968-121">Ruft die Adresse dieser HybridConnection Herstellen einer Verbindung über ab.</span><span class="sxs-lookup"><span data-stu-id="f7968-121">Gets the address of this HybridConnection to connect through.</span></span> <span data-ttu-id="f7968-122">Die Adresse, an der HybridConnections überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f7968-122">The address on which to listen for HybridConnections.</span></span>
            <span data-ttu-id="f7968-123">Diese Adresse muss im Format "sb://contoso.servicebus.windows.net/yourhybridconnection".</span><span class="sxs-lookup"><span data-stu-id="f7968-123">This address should be of the format "sb://contoso.servicebus.windows.net/yourhybridconnection".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConnectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt; CreateConnectionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionStream&gt; CreateConnectionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.CreateConnectionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConnectionAsync () As Task(Of HybridConnectionStream)" />
      <MemberSignature Language="F#" Value="member this.CreateConnectionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt;" Usage="hybridConnectionClient.CreateConnectionAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionClient/&lt;CreateConnectionAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7968-124">Stellt eine neue Sendeseite HybridConnection her und gibt den Stream zurück.</span><span class="sxs-lookup"><span data-stu-id="f7968-124">Establishes a new send-side HybridConnection and returns the Stream.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.GetRuntimeInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRuntimeInformationAsync () As Task(Of HybridConnectionRuntimeInformation)" />
      <MemberSignature Language="F#" Value="member this.GetRuntimeInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;" Usage="hybridConnectionClient.GetRuntimeInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionClient/&lt;GetRuntimeInformationAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7968-125">Ruft die <see cref="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" /> für diese HybridConnection-Entität mithilfe der Standard-Timeoutwert.</span><span class="sxs-lookup"><span data-stu-id="f7968-125">Gets the <see cref="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" /> for this HybridConnection entity using the default timeout.</span></span>
            <span data-ttu-id="f7968-126">Es sei denn, in der Verbindungszeichenfolge angegeben ist der Standardwert 1 Minute.</span><span class="sxs-lookup"><span data-stu-id="f7968-126">Unless specified in the connection string the default is 1 minute.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.GetRuntimeInformationAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRuntimeInformationAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;" Usage="hybridConnectionClient.GetRuntimeInformationAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f7968-127">Ein Abbruchtoken, das überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f7968-127">A cancellation token to observe.</span></span></param>
        <summary>
            <span data-ttu-id="f7968-128">Ruft die <see cref="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" /> für diese mithilfe der bereitgestellten CancellationToken HybridConnection-Entität.</span><span class="sxs-lookup"><span data-stu-id="f7968-128">Gets the <see cref="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" /> for this HybridConnection entity using the provided CancellationToken.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionClient.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.Relay.HybridConnectionClient.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7968-129">Abrufen oder Festlegen des Timeouts für eine HybridConnection Verbindungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="f7968-129">Gets or sets the timeout used when connecting a HybridConnection.</span></span>  <span data-ttu-id="f7968-130">Standardwert ist 70 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="f7968-130">Default value is 70 seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Proxy">
      <MemberSignature Language="C#" Value="public System.Net.IWebProxy Proxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Net.IWebProxy Proxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionClient.Proxy" />
      <MemberSignature Language="VB.NET" Value="Public Property Proxy As IWebProxy" />
      <MemberSignature Language="F#" Value="member this.Proxy : System.Net.IWebProxy with get, set" Usage="Microsoft.Azure.Relay.HybridConnectionClient.Proxy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.IWebProxy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7968-131">Ruft ab, oder legt ihn fest Proxyinformationen für die Verbindung mit Service Bus.</span><span class="sxs-lookup"><span data-stu-id="f7968-131">Gets or sets proxy information for connecting to ServiceBus.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Relay.TokenProvider TokenProvider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Relay.TokenProvider TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionClient.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenProvider As TokenProvider" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.Azure.Relay.TokenProvider" Usage="Microsoft.Azure.Relay.HybridConnectionClient.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Relay.TokenProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7968-132">Ruft die TokenProvider zum Authentifizieren von HybridConnections ab.</span><span class="sxs-lookup"><span data-stu-id="f7968-132">Gets the TokenProvider for authenticating HybridConnections.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>