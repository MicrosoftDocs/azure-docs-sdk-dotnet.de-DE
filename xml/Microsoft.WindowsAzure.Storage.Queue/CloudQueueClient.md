<Type Name="CloudQueueClient" FullName="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient">
  <TypeSignature Language="C#" Value="public class CloudQueueClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudQueueClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudQueueClient" />
  <TypeSignature Language="F#" Value="type CloudQueueClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="37a45-101">Bietet eine clientseitige logische Darstellung des Microsoft Azure-Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-101">Provides a client-side logical representation of the Microsoft Azure Queue service.</span></span> <span data-ttu-id="37a45-102">Dieser Client wird verwendet, um zu konfigurieren und Ausführen von Anforderungen für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-102">This client is used to configure and execute requests against the Queue service.</span></span>
            </summary>
    <remarks><span data-ttu-id="37a45-103">Der Dienstclient kapselt den Endpunkt oder die Endpunkte für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-103">The service client encapsulates the endpoint or endpoints for the Queue service.</span></span> <span data-ttu-id="37a45-104">Wenn der Dienstclient für den authentifizierten Zugriff verwendet wird, kapselt er auch die Anmeldeinformationen für den Zugriff auf das Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="37a45-104">If the service client will be used for authenticated access, it also encapsulates the credentials for accessing the storage account.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueueClient (Microsoft.WindowsAzure.Storage.StorageUri storageUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri storageUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient (storageUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="storageUri"><span data-ttu-id="37a45-105">Ein <see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.StorageUri" /> Objekt, das den Warteschlangendienst-Endpunkt, mit der Erstellung des Clients enthält.</span><span class="sxs-lookup"><span data-stu-id="37a45-105">A <see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.StorageUri" /> object containing the Queue service endpoint to use to create the client.</span></span></param>
        <param name="credentials"><span data-ttu-id="37a45-106">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-106">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-107">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" /> -Klasse unter Verwendung der angegebenen Warteschlange-Endpunkt und der Kontoanmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="37a45-107">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" /> class using the specified Queue service endpoint and account credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueueClient (Uri baseUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient (baseUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="baseUri"><span data-ttu-id="37a45-108">Die <see cref="T:System.Uri" /> , enthält den warteschlangendienstendpunkt zum Erstellen des Clients verwenden.</span><span class="sxs-lookup"><span data-stu-id="37a45-108">The <see cref="T:System.Uri" /> containing the Queue service endpoint to use to create the client.</span></span></param>
        <param name="credentials"><span data-ttu-id="37a45-109">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-109">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-110">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" /> -Klasse unter Verwendung der angegebenen Warteschlange-Endpunkt und der Kontoanmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="37a45-110">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" /> class using the specified Queue service endpoint and account credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationScheme">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.AuthenticationScheme AuthenticationScheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.AuthenticationScheme AuthenticationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.AuthenticationScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationScheme As AuthenticationScheme" />
      <MemberSignature Language="F#" Value="member this.AuthenticationScheme : Microsoft.WindowsAzure.Storage.AuthenticationScheme with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.AuthenticationScheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AuthenticationScheme</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37a45-111">Ruft ab oder legt das Authentifizierungsschema zum Signieren von HTTP-Anforderungen.</span><span class="sxs-lookup"><span data-stu-id="37a45-111">Gets or sets the authentication scheme to use to sign HTTP requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="37a45-112">Diese Eigenschaft wird nur festgelegt, wenn Shared Key oder Shared Key Lite-Anmeldeinformationen verwendet werden; Es gilt nicht für die Authentifizierung über eine SAS oder anonymer Zugriff.</span><span class="sxs-lookup"><span data-stu-id="37a45-112">This property is set only when Shared Key or Shared Key Lite credentials are used; it does not apply to authentication via a shared access signature or anonymous access.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37a45-113">Ruft den Basis-URI für den warteschlangendienstclient am primären Speicherort ab.</span><span class="sxs-lookup"><span data-stu-id="37a45-113">Gets the base URI for the Queue service client, at the primary location.</span></span>
            </summary>
        <value><span data-ttu-id="37a45-114">Ein <see cref="T:System.Uri" /> -Objekt für den warteschlangendienstclient am primären Standort.</span><span class="sxs-lookup"><span data-stu-id="37a45-114">A <see cref="T:System.Uri" /> object for the Queue service client, at the primary location.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceProperties (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginGetServiceProperties (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="37a45-115">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="37a45-115">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="37a45-116">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="37a45-116">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-117">Startet einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-117">Begins an asynchronous operation to get service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-118">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="37a45-118">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceProperties(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginGetServiceProperties (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="37a45-119">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-119">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-120">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-120">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="37a45-121">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="37a45-121">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="37a45-122">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="37a45-122">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-123">Startet einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-123">Begins an asynchronous operation to get service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-124">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="37a45-124">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceStats(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceStats (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceStats : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceStats : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginGetServiceStats (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="37a45-125">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="37a45-125">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="37a45-126">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="37a45-126">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-127">Startet einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für den sekundärer Warteschlangendienst-Endpunkt an.</span><span class="sxs-lookup"><span data-stu-id="37a45-127">Begins an asynchronous operation to get service stats for the secondary Queue service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-128">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="37a45-128">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceStats(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceStats : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceStats : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginGetServiceStats (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="37a45-129">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-129">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-130">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-130">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="37a45-131">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="37a45-131">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="37a45-132">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="37a45-132">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-133">Startet einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für den sekundärer Warteschlangendienst-Endpunkt an.</span><span class="sxs-lookup"><span data-stu-id="37a45-133">Begins an asynchronous operation to get service stats for the secondary Queue service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-134">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="37a45-134">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented (Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented(class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginListQueuesSegmented(Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListQueuesSegmented (currentToken As QueueContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListQueuesSegmented : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListQueuesSegmented : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginListQueuesSegmented (currentToken, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="37a45-135">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="37a45-135">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="callback"><span data-ttu-id="37a45-136">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="37a45-136">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="37a45-137">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="37a45-137">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-138">Startet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.</span><span class="sxs-lookup"><span data-stu-id="37a45-138">Begins an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-139">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="37a45-139">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented (string prefix, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented(string prefix, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginListQueuesSegmented(System.String,Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListQueuesSegmented (prefix As String, currentToken As QueueContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginListQueuesSegmented (prefix, currentToken, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="37a45-140">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</span><span class="sxs-lookup"><span data-stu-id="37a45-140">A string containing the queue name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="37a45-141">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="37a45-141">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="callback"><span data-ttu-id="37a45-142">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="37a45-142">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="37a45-143">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="37a45-143">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-144">Startet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.</span><span class="sxs-lookup"><span data-stu-id="37a45-144">Begins an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-145">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="37a45-145">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented (string prefix, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented(string prefix, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginListQueuesSegmented(System.String,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginListQueuesSegmented (prefix, queueListingDetails, maxResults, currentToken, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="queueListingDetails" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="37a45-146">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</span><span class="sxs-lookup"><span data-stu-id="37a45-146">A string containing the queue name prefix.</span></span></param>
        <param name="queueListingDetails"><span data-ttu-id="37a45-147">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> -Enumeration, die in die Auflistung einzuschließenden Elemente beschreibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-147">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="37a45-148">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von gleichzeitig pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-148">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="37a45-149">Wenn dieser Wert ist <c>null</c>, die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="37a45-149">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="37a45-150">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="37a45-150">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="37a45-151">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-151">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-152">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-152">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="37a45-153">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="37a45-153">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="37a45-154">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="37a45-154">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-155">Startet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.</span><span class="sxs-lookup"><span data-stu-id="37a45-155">Begins an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-156">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="37a45-156">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetServiceProperties (properties As ServiceProperties, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginSetServiceProperties (properties, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="37a45-157">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-157">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="37a45-158">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="37a45-158">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="37a45-159">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="37a45-159">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-160">Startet einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-160">Begins an asynchronous operation to set service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-161">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="37a45-161">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginSetServiceProperties (properties, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="37a45-162">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-162">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="37a45-163">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-163">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-164">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-164">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="37a45-165">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="37a45-165">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="37a45-166">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="37a45-166">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-167">Startet einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-167">Begins an asynchronous operation to set service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-168">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="37a45-168">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BufferManager">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.IBufferManager BufferManager { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.IBufferManager BufferManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BufferManager" />
      <MemberSignature Language="VB.NET" Value="Public Property BufferManager As IBufferManager" />
      <MemberSignature Language="F#" Value="member this.BufferManager : Microsoft.WindowsAzure.Storage.IBufferManager with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BufferManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.IBufferManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37a45-169">Ruft ab oder legt einen Puffer-Manager, die implementiert die <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> -Schnittstelle, einen zu verwendender Pufferpool mit Vorgängen für den warteschlangendienstclient angeben.</span><span class="sxs-lookup"><span data-stu-id="37a45-169">Gets or sets a buffer manager that implements the <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> interface, specifying a buffer pool for use with operations against the Queue service client.</span></span>
            </summary>
        <value><span data-ttu-id="37a45-170">Ein Objekt vom Typ <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" />.</span><span class="sxs-lookup"><span data-stu-id="37a45-170">An object of type <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As StorageCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Auth.StorageCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37a45-171">Ruft die Kontoanmeldeinformationen, die zum Erstellen der Warteschlangen-Dienstclient ab.</span><span class="sxs-lookup"><span data-stu-id="37a45-171">Gets the account credentials used to create the Queue service client.</span></span>
            </summary>
        <value><span data-ttu-id="37a45-172">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-172">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRequestOptions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions DefaultRequestOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions DefaultRequestOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.DefaultRequestOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultRequestOptions As QueueRequestOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultRequestOptions : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.DefaultRequestOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37a45-173">Ruft ab und legt den Standardwert Anforderungsoptionen für über den Warteschlangen-Dienstclient vorgenommene Anforderungen.</span><span class="sxs-lookup"><span data-stu-id="37a45-173">Gets and sets the default request options for requests made via the Queue service client.</span></span>
            </summary>
        <value><span data-ttu-id="37a45-174">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-174">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties EndGetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties EndGetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.EndGetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceProperties (asyncResult As IAsyncResult) As ServiceProperties" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceProperties : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&#xA;override this.EndGetServiceProperties : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="cloudQueueClient.EndGetServiceProperties asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="37a45-175">Das Ergebnis von einem vorherigen Aufruf für zurückgegeben <see cref="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />.</span><span class="sxs-lookup"><span data-stu-id="37a45-175">The result returned from a prior call to <see cref="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-176">Beendet einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-176">Ends an asynchronous operation to get service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-177">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-177">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats EndGetServiceStats (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats EndGetServiceStats(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.EndGetServiceStats(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceStats (asyncResult As IAsyncResult) As ServiceStats" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceStats : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&#xA;override this.EndGetServiceStats : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="cloudQueueClient.EndGetServiceStats asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="37a45-178">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="37a45-178">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-179">Beendet einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für den sekundärer Warteschlangendienst-Endpunkt an.</span><span class="sxs-lookup"><span data-stu-id="37a45-179">Ends an asynchronous operation to get service stats for the secondary Queue service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-180">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-180">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment EndListQueuesSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment EndListQueuesSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.EndListQueuesSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndListQueuesSegmented (asyncResult As IAsyncResult) As QueueResultSegment" />
      <MemberSignature Language="F#" Value="abstract member EndListQueuesSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&#xA;override this.EndListQueuesSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" Usage="cloudQueueClient.EndListQueuesSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="37a45-181">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="37a45-181">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-182">Beendet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.</span><span class="sxs-lookup"><span data-stu-id="37a45-182">Ends an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-183">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-183">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void EndSetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.EndSetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetServiceProperties (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetServiceProperties : IAsyncResult -&gt; unit&#xA;override this.EndSetServiceProperties : IAsyncResult -&gt; unit" Usage="cloudQueueClient.EndSetServiceProperties asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="37a45-184">Die <see cref="T:System.IAsyncResult" /> zurückgegeben, die von einem vorherigen Aufruf für <see cref="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" />.</span><span class="sxs-lookup"><span data-stu-id="37a45-184">The <see cref="T:System.IAsyncResult" /> returned from a prior call to <see cref="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" />.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-185">Beendet einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-185">Ends an asynchronous operation to set service properties for the Queue service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQueueReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.CloudQueue GetQueueReference (string queueName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.CloudQueue GetQueueReference(string queueName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetQueueReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetQueueReference (queueName As String) As CloudQueue" />
      <MemberSignature Language="F#" Value="abstract member GetQueueReference : string -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueue&#xA;override this.GetQueueReference : string -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueue" Usage="cloudQueueClient.GetQueueReference queueName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.CloudQueue</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queueName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="queueName"><span data-ttu-id="37a45-186">Eine Zeichenfolge, die mit dem Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="37a45-186">A string containing the name of the queue.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-187">Gibt einen Verweis auf ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> Objekt mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="37a45-187">Returns a reference to a <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> object with the specified name.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-188">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-188">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties GetServiceProperties (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties GetServiceProperties(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceProperties(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceProperties : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&#xA;override this.GetServiceProperties : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="cloudQueueClient.GetServiceProperties (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="37a45-189">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-189">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-190">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-190">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-191">Ruft die Diensteigenschaften für den Warteschlangendienst ab.</span><span class="sxs-lookup"><span data-stu-id="37a45-191">Gets service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-192">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> mit den Eigenschaften der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="37a45-192">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> containing the Queue service properties.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServicePropertiesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServicePropertiesAsync () As Task(Of ServiceProperties)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudQueueClient.GetServicePropertiesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="37a45-193">Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-193">Initiates an asynchronous operation to get service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-194">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-194">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServicePropertiesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudQueueClient.GetServicePropertiesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="37a45-195">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="37a45-195">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-196">Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-196">Initiates an asynchronous operation to get service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-197">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-197">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudQueueClient.GetServicePropertiesAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="37a45-198">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-198">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-199">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-199">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-200">Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-200">Initiates an asynchronous operation to get service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-201">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-201">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudQueueClient.GetServicePropertiesAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="37a45-202">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-202">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-203">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-203">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="37a45-204">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="37a45-204">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-205">Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-205">Initiates an asynchronous operation to get service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-206">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-206">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats GetServiceStats (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats GetServiceStats(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceStats(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStats : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&#xA;override this.GetServiceStats : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="cloudQueueClient.GetServiceStats (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="37a45-207">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-207">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-208">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-208">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-209">Ruft die dienststatistik für den sekundären Warteschlangendienst-Endpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="37a45-209">Gets service stats for the secondary Queue service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-210">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-210">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceStatsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServiceStatsAsync () As Task(Of ServiceStats)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudQueueClient.GetServiceStatsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="37a45-211">Initiiert einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für den sekundärer Warteschlangendienst-Endpunkt an.</span><span class="sxs-lookup"><span data-stu-id="37a45-211">Initiates an asynchronous operation to get service stats for the secondary Queue service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-212">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-212">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceStatsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudQueueClient.GetServiceStatsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="37a45-213">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="37a45-213">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-214">Initiiert einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für den sekundärer Warteschlangendienst-Endpunkt an.</span><span class="sxs-lookup"><span data-stu-id="37a45-214">Initiates an asynchronous operation to get service stats for the secondary Queue service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-215">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-215">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceStatsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudQueueClient.GetServiceStatsAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="37a45-216">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-216">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-217">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-217">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-218">Initiiert einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für den sekundärer Warteschlangendienst-Endpunkt an.</span><span class="sxs-lookup"><span data-stu-id="37a45-218">Initiates an asynchronous operation to get service stats for the secondary Queue service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-219">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-219">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceStatsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudQueueClient.GetServiceStatsAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="37a45-220">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-220">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-221">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-221">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="37a45-222">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="37a45-222">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-223">Initiiert einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für den sekundärer Warteschlangendienst-Endpunkt an.</span><span class="sxs-lookup"><span data-stu-id="37a45-223">Initiates an asynchronous operation to get service stats for the secondary Queue service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-224">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-224">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueues">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt; ListQueues (string prefix = null, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails = Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails.None, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt; ListQueues(string prefix, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueues(System.String,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListQueues : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt;&#xA;override this.ListQueues : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt;" Usage="cloudQueueClient.ListQueues (prefix, queueListingDetails, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="queueListingDetails" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="37a45-225">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</span><span class="sxs-lookup"><span data-stu-id="37a45-225">A string containing the queue name prefix.</span></span></param>
        <param name="queueListingDetails"><span data-ttu-id="37a45-226">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> -Enumerationswert ab, der gibt an, welche Details in die Auflistung eingeschlossen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="37a45-226">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> enumeration value that indicates which details to include in the listing.</span></span></param>
        <param name="options"><span data-ttu-id="37a45-227">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-227">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="37a45-228">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="37a45-228">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-229">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-229">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-230">Gibt eine aufzählbare Auflistung von Warteschlangen im Speicherkonto, deren Namen mit dem angegebenen Präfix beginnen und verzögert werden abgerufen.</span><span class="sxs-lookup"><span data-stu-id="37a45-230">Returns an enumerable collection of the queues in the storage account whose names begin with the specified prefix and that are retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-231">Eine aufzählbare Auflistung von Objekten des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> verzögert werden abgerufen.</span><span class="sxs-lookup"><span data-stu-id="37a45-231">An enumerable collection of objects of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> that are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented (Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented(class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmented(Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListQueuesSegmented (currentToken As QueueContinuationToken) As QueueResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmented : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&#xA;override this.ListQueuesSegmented : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" Usage="cloudQueueClient.ListQueuesSegmented currentToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="37a45-232">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="37a45-232">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> continuation token returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-233">Gibt ein ergebnissegment mit einer Sammlung von Warteschlangen zurück.</span><span class="sxs-lookup"><span data-stu-id="37a45-233">Returns a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-234">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-234">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented (string prefix, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented(string prefix, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmented(System.String,Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListQueuesSegmented (prefix As String, currentToken As QueueContinuationToken) As QueueResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&#xA;override this.ListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" Usage="cloudQueueClient.ListQueuesSegmented (prefix, currentToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="37a45-235">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</span><span class="sxs-lookup"><span data-stu-id="37a45-235">A string containing the queue name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="37a45-236">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="37a45-236">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> continuation token returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-237">Gibt ein ergebnissegment mit einer Sammlung von Warteschlangen zurück.</span><span class="sxs-lookup"><span data-stu-id="37a45-237">Returns a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-238">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-238">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented (string prefix, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented(string prefix, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmented(System.String,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&#xA;override this.ListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" Usage="cloudQueueClient.ListQueuesSegmented (prefix, queueListingDetails, maxResults, currentToken, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="queueListingDetails" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="37a45-239">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</span><span class="sxs-lookup"><span data-stu-id="37a45-239">A string containing the queue name prefix.</span></span></param>
        <param name="queueListingDetails"><span data-ttu-id="37a45-240">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> -Enumeration, die in die Auflistung einzuschließenden Elemente beschreibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-240">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="37a45-241">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von gleichzeitig pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-241">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="37a45-242">Wenn dieser Wert ist <c>null</c>, die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="37a45-242">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="37a45-243">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="37a45-243">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="37a45-244">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-244">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="37a45-245">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="37a45-245">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-246">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-246">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-247">Gibt ein ergebnissegment mit einer Sammlung von Warteschlangen zurück.</span><span class="sxs-lookup"><span data-stu-id="37a45-247">Returns a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-248">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-248">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListQueuesSegmentedAsync (currentToken As QueueContinuationToken) As Task(Of QueueResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync currentToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="37a45-249">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="37a45-249">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-250">Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.</span><span class="sxs-lookup"><span data-stu-id="37a45-250">Initiates an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-251">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-251">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync (currentToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="37a45-252">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="37a45-252">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="37a45-253">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="37a45-253">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-254">Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.</span><span class="sxs-lookup"><span data-stu-id="37a45-254">Initiates an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-255">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-255">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListQueuesSegmentedAsync (prefix As String, currentToken As QueueContinuationToken) As Task(Of QueueResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync (prefix, currentToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="37a45-256">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</span><span class="sxs-lookup"><span data-stu-id="37a45-256">A string containing the queue name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="37a45-257">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="37a45-257">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-258">Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.</span><span class="sxs-lookup"><span data-stu-id="37a45-258">Initiates an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-259">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-259">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync (prefix, currentToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="37a45-260">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</span><span class="sxs-lookup"><span data-stu-id="37a45-260">A string containing the queue name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="37a45-261">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="37a45-261">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="37a45-262">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="37a45-262">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-263">Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.</span><span class="sxs-lookup"><span data-stu-id="37a45-263">Initiates an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-264">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-264">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(string prefix, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync (prefix, queueListingDetails, maxResults, currentToken, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="queueListingDetails" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="37a45-265">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</span><span class="sxs-lookup"><span data-stu-id="37a45-265">A string containing the queue name prefix.</span></span></param>
        <param name="queueListingDetails"><span data-ttu-id="37a45-266">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> -Enumeration, die in die Auflistung einzuschließenden Elemente beschreibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-266">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="37a45-267">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von gleichzeitig pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-267">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="37a45-268">Wenn dieser Wert ist <c>null</c>, die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="37a45-268">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="37a45-269">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="37a45-269">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="37a45-270">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-270">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-271">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-271">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-272">Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.</span><span class="sxs-lookup"><span data-stu-id="37a45-272">Initiates an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-273">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-273">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(string prefix, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync (prefix, queueListingDetails, maxResults, currentToken, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="queueListingDetails" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="37a45-274">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</span><span class="sxs-lookup"><span data-stu-id="37a45-274">A string containing the queue name prefix.</span></span></param>
        <param name="queueListingDetails"><span data-ttu-id="37a45-275">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> -Enumeration, die in die Auflistung einzuschließenden Elemente beschreibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-275">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="37a45-276">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von gleichzeitig pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-276">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="37a45-277">Wenn dieser Wert null ist, ist die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="37a45-277">If this value is null, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="37a45-278">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="37a45-278">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="37a45-279">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-279">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-280">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-280">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="37a45-281">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="37a45-281">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-282">Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.</span><span class="sxs-lookup"><span data-stu-id="37a45-282">Initiates an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-283">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-283">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void SetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.SetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueueClient.SetServiceProperties (properties, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="37a45-284">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-284">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="37a45-285">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-285">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-286">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-286">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-287">Legt die Diensteigenschaften für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-287">Sets service properties for the Queue service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetServicePropertiesAsync (properties As ServiceProperties) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties -&gt; System.Threading.Tasks.Task" Usage="cloudQueueClient.SetServicePropertiesAsync properties" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="37a45-288">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-288">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-289">Initiiert einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-289">Initiates an asynchronous operation to set service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-290">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-290">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueueClient.SetServicePropertiesAsync (properties, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="37a45-291">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-291">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="37a45-292">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="37a45-292">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-293">Initiiert einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-293">Initiates an asynchronous operation to set service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-294">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-294">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueueClient.SetServicePropertiesAsync (properties, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="37a45-295">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-295">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="37a45-296">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-296">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-297">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-297">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-298">Initiiert einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-298">Initiates an asynchronous operation to set service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-299">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-299">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueueClient.SetServicePropertiesAsync (properties, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="37a45-300">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="37a45-300">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="37a45-301">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="37a45-301">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="37a45-302">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-302">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="37a45-303">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="37a45-303">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="37a45-304">Initiiert einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="37a45-304">Initiates an asynchronous operation to set service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="37a45-305">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37a45-305">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.StorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37a45-306">Ruft die warteschlangendienstendpunkte sowohl für die primären und sekundären Speicherorte ab.</span><span class="sxs-lookup"><span data-stu-id="37a45-306">Gets the Queue service endpoints for both the primary and secondary locations.</span></span>
            </summary>
        <value><span data-ttu-id="37a45-307">Ein Objekt des Typs <see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.StorageUri" /> mit Warteschlangen-URIs für die primären und sekundären Speicherorte.</span><span class="sxs-lookup"><span data-stu-id="37a45-307">An object of type <see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.StorageUri" /> containing Queue service URIs for both the primary and secondary locations.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>