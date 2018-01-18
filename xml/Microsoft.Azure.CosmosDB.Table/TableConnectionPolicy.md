<Type Name="TableConnectionPolicy" FullName="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy">
  <TypeSignature Language="C#" Value="public sealed class TableConnectionPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TableConnectionPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableConnectionPolicy" />
  <TypeSignature Language="F#" Value="type TableConnectionPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="57ac2-101">Stellt die zugeordnete Verbindungsrichtlinie <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> zur Verbindung mit des Azure-CosmosDB-tabellendiensts.</span><span class="sxs-lookup"><span data-stu-id="57ac2-101">Represents the connection policy associated with <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> to connect to the Azure CosmosDB table service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableConnectionPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="57ac2-102">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" /> Klasse, um die Verbindung mit dem Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="57ac2-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" /> class to connect to the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableEndpointDiscovery">
      <MemberSignature Language="C#" Value="public bool EnableEndpointDiscovery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableEndpointDiscovery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableEndpointDiscovery As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableEndpointDiscovery : bool with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57ac2-103">Ruft ab oder legt das Flag zum Endpunkt-Ermittlung für geografisch repliziert Datenbankkonten im Azure-Cosmos-DB-Dienst zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="57ac2-103">Gets or sets the flag to enable endpoint discovery for geo-replicated database accounts in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="57ac2-104">Wenn der Wert dieser Eigenschaft "true ist", das SDK automatisch die aktuellen schreiben erkennt und Lese Regionen, um sicherzustellen, dass Anforderungen an die richtige Region basierend auf den Regionen, die im angegebenen gesendet werden die <see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.PreferredLocations" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="57ac2-104">When the value of this property is true, the SDK will automatically discover the current write and read regions to ensure requests are sent to the correct region based on the regions specified in the <see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.PreferredLocations" /> property.</span></span>
            <span data-ttu-id="57ac2-105"><value>Standardwert ist "true", der angibt, Endpunkt-Ermittlung aktiviert ist.</value></span><span class="sxs-lookup"><span data-stu-id="57ac2-105"><value>Default value is true indicating endpoint discovery is enabled.</value></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConnectionLimit">
      <MemberSignature Language="C#" Value="public int MaxConnectionLimit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConnectionLimit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxConnectionLimit" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConnectionLimit As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConnectionLimit : int with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxConnectionLimit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57ac2-106">Ruft ab oder legt die maximale Anzahl gleichzeitiger Verbindungen für den Ziel-Dienstendpunkt im Azure-Cosmos-DB-Dienst zulässig.</span><span class="sxs-lookup"><span data-stu-id="57ac2-106">Gets or sets the maximum number of concurrent connections allowed for the target service endpoint in the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="57ac2-107">Standardwert ist 50.</span><span class="sxs-lookup"><span data-stu-id="57ac2-107">Default value is 50.</span></span></value>
        <remarks>
            <span data-ttu-id="57ac2-108">Diese Einstellung gilt nur in der Gateway-Modus.</span><span class="sxs-lookup"><span data-stu-id="57ac2-108">This setting is only applicable in Gateway mode.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryAttemptsOnThrottledRequests">
      <MemberSignature Language="C#" Value="public int MaxRetryAttemptsOnThrottledRequests { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryAttemptsOnThrottledRequests" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxRetryAttemptsOnThrottledRequests" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryAttemptsOnThrottledRequests As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryAttemptsOnThrottledRequests : int with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxRetryAttemptsOnThrottledRequests" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57ac2-109">Ruft ab oder legt die maximale Anzahl der Wiederholungsversuche im Fall, in dem die Anforderung schlägt fehl, da der Dienst Azure-Cosmos-DB Begrenzung von aufrufraten, auf dem Client angewendet wurde.</span><span class="sxs-lookup"><span data-stu-id="57ac2-109">Gets or sets the maximum number of retries in the case where the request fails because the Azure Cosmos DB service has applied rate limiting on the client.</span></span>
            </summary>
        <value>
            <span data-ttu-id="57ac2-110">Der Standardwert ist 9.</span><span class="sxs-lookup"><span data-stu-id="57ac2-110">The default value is 9.</span></span> <span data-ttu-id="57ac2-111">Dies bedeutet, dass im Fall, in dem die Anforderung Rate begrenzt wird, ist, die gleiche Anforderung ausgegeben für maximal 10 Mal an den Server vor dem Fehler an die Anwendung zurückgegeben wird.</span><span class="sxs-lookup"><span data-stu-id="57ac2-111">This means in the case where the request is rate limited, the same request will be issued for a maximum of 10 times to the server before an error is returned to the application.</span></span> <span data-ttu-id="57ac2-112">Wenn der Wert dieser Eigenschaft auf 0 festgelegt ist, keine automatische Wiederholung auf Begrenzung von aufrufraten, die Clientanforderungen werden, und die Ausnahme muss auf Anwendungsebene behandelt.</span><span class="sxs-lookup"><span data-stu-id="57ac2-112">If the value of this property is set to 0, there will be no automatic retry on rate limiting requests from the client and the exception needs to handled at the application level.</span></span> 
            </value>
        <remarks>
          <para>
            <span data-ttu-id="57ac2-113">Wenn ein Client fordert schneller als die zulässige Rate sendet, wird vom Dienst HttpStatusCode 429 (zu viele Anforderung) auf den Grenzwert für den Client zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="57ac2-113">When a client is sending requests faster than the allowed rate, the service will return HttpStatusCode 429 (Too Many Request) to rate limit the client.</span></span> <span data-ttu-id="57ac2-114">Die aktuelle Implementierung im SDK wartet dann für den Zeitraum, den der Dienst weist warten, und wiederholen Sie dann die Zeit verstrichen ist.</span><span class="sxs-lookup"><span data-stu-id="57ac2-114">The current implementation in the SDK will then wait for the amount of time the service tells it to wait and retry after the time has elapsed.</span></span>  
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryWaitTimeInSeconds">
      <MemberSignature Language="C#" Value="public int MaxRetryWaitTimeInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryWaitTimeInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxRetryWaitTimeInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryWaitTimeInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryWaitTimeInSeconds : int with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxRetryWaitTimeInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57ac2-115">Ruft ab oder legt die maximale Wiederholungszeit in Sekunden für den Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="57ac2-115">Gets or sets the maximum retry time in seconds for the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="57ac2-116">Der Standardwert ist 30 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="57ac2-116">The default value is 30 seconds.</span></span> 
            </value>
        <remarks>
          <para>
            <span data-ttu-id="57ac2-117">Bei einem aufgrund einer Begrenzung von aufrufraten, Fehler Anforderungsfehler, sendet der Dienst wieder eine Antwort, die dar, die einen Wert, der angibt, dass der Client nicht erneut sollte vor Ablauf des Zeitraums enthält.</span><span class="sxs-lookup"><span data-stu-id="57ac2-117">When a request fails due to a rate limiting error, the service sends back a response that contains a value indicating the client should not retry before the time period has elapsed.</span></span> <span data-ttu-id="57ac2-118">Diese Eigenschaft kann die Anwendung auf eine maximalen Wartezeit festgelegt, für alle Wiederholungsversuchen.</span><span class="sxs-lookup"><span data-stu-id="57ac2-118">This property allows the application to set a maximum wait time for all retry attempts.</span></span>
            <span data-ttu-id="57ac2-119">Wenn die kumulierte Wartezeit diesen überschreitet Wert, der Client beendet, und wiederholen Sie dann und der Fehler an die Anwendung zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="57ac2-119">If the cumulative wait time exceeds the this value, the client will stop retrying and return the error to the application.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreferredLocations">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;string&gt; PreferredLocations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;string&gt; PreferredLocations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.PreferredLocations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreferredLocations As Collection(Of String)" />
      <MemberSignature Language="F#" Value="member this.PreferredLocations : System.Collections.ObjectModel.Collection&lt;string&gt;" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.PreferredLocations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57ac2-120">Ermittelt und definiert die bevorzugte Speicherorte (Regionen) für geografisch repliziert Datenbankkonten im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="57ac2-120">Gets and sets the preferred locations (regions) for geo-replicated database accounts in the Azure Cosmos DB service.</span></span> <span data-ttu-id="57ac2-121">Beispiel: "East US" als bevorzugten Speicherort.</span><span class="sxs-lookup"><span data-stu-id="57ac2-121">For example, "East US" as the preferred location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="57ac2-122">Wenn <see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" /> ist "true" und der Wert dieser Eigenschaft ist nicht leer, das SDK verwendet die Speicherorten in der Auflistung in der Reihenfolge angegebenen Operationen andernfalls ausführen, wenn der Wert dieser Eigenschaft nicht angegeben wird, das SDK verwendet den Write-Region wie die Bevorzugter Speicherort für alle Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="57ac2-122">When <see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" /> is true and the value of this property is non-empty, the SDK uses the locations in the collection in the order they are specified to perform operations, otherwise if the value of this property is not specified, the SDK uses the write region as the preferred location for all operations.</span></span>
            </para>
          <para>
            <span data-ttu-id="57ac2-123">Wenn <see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" /> festgelegt ist auf "false", wird der Wert dieser Eigenschaft ignoriert.</span><span class="sxs-lookup"><span data-stu-id="57ac2-123">If <see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" /> is set to false, the value of this property is ignored.</span></span> 
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDirectMode">
      <MemberSignature Language="C#" Value="public bool UseDirectMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDirectMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UseDirectMode" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDirectMode As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDirectMode : bool with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UseDirectMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57ac2-124">Direct-Modus verwenden beim Verbinden mit Azure-Cosmos-DB Service Flase verbindet sich über REST-API-Tabelle</span><span class="sxs-lookup"><span data-stu-id="57ac2-124">Use direct mode when connecting to Azure Cosmos DB service flase, will connect through table REST API</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAgentSuffix">
      <MemberSignature Language="C#" Value="public string UserAgentSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserAgentSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UserAgentSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAgentSuffix As String" />
      <MemberSignature Language="F#" Value="member this.UserAgentSuffix : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UserAgentSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57ac2-125">Suffix an Standardeinstellung User-Agent für den Azure-Cosmos-DB-Dienst hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="57ac2-125">A suffix to be added to the default user-agent for the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="57ac2-126">Durch Festlegen dieser Eigenschaft nach dem Senden einer Anforderung keine Auswirkung.</span><span class="sxs-lookup"><span data-stu-id="57ac2-126">Setting this property after sending any request won't have any effect.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UseTcpProtocol">
      <MemberSignature Language="C#" Value="public bool UseTcpProtocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseTcpProtocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UseTcpProtocol" />
      <MemberSignature Language="VB.NET" Value="Public Property UseTcpProtocol As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseTcpProtocol : bool with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UseTcpProtocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57ac2-127">Verwenden Sie die TCP-Verbindung-Protokoll beim Verbinden mit der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="57ac2-127">Use TCP connection protocol when connecting to the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="57ac2-128">Weitere Informationen finden Sie unter <see href="https://docs.microsoft.com/en-us/azure/documentdb/documentdb-performance-tips#use-tcp">Verbindungsrichtlinie: Verwenden Sie das TCP-Protokoll</see>.</span><span class="sxs-lookup"><span data-stu-id="57ac2-128">For more information, see <see href="https://docs.microsoft.com/en-us/azure/documentdb/documentdb-performance-tips#use-tcp">Connection policy: Use the TCP protocol</see>.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>