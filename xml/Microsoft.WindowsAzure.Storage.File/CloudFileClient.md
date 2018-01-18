<Type Name="CloudFileClient" FullName="Microsoft.WindowsAzure.Storage.File.CloudFileClient">
  <TypeSignature Language="C#" Value="public class CloudFileClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudFileClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.CloudFileClient" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudFileClient" />
  <TypeSignature Language="F#" Value="type CloudFileClient = class" />
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
            <span data-ttu-id="f5707-101">Bietet eine clientseitige logische Darstellung des Microsoft Azure-dateidiensts an.</span><span class="sxs-lookup"><span data-stu-id="f5707-101">Provides a client-side logical representation of the Microsoft Azure File service.</span></span> <span data-ttu-id="f5707-102">Dieser Client wird verwendet, zu konfigurieren und Anforderungen für den Dienst auszuführen.</span><span class="sxs-lookup"><span data-stu-id="f5707-102">This client is used to configure and execute requests against the File service.</span></span>
            </summary>
    <remarks><span data-ttu-id="f5707-103">Der Dienstclient kapselt den Basis-URI für den Dateidienst an.</span><span class="sxs-lookup"><span data-stu-id="f5707-103">The service client encapsulates the base URI for the File service.</span></span> <span data-ttu-id="f5707-104">Wenn der Dienstclient für den authentifizierten Zugriff verwendet wird, kapselt er auch die Anmeldeinformationen für den Zugriff auf das Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="f5707-104">If the service client will be used for authenticated access, it also encapsulates the credentials for accessing the storage account.</span></span></remarks>
    <remarks><span data-ttu-id="f5707-105">Der Dienstclient kapselt den Basis-URI für den Dateidienst an.</span><span class="sxs-lookup"><span data-stu-id="f5707-105">The service client encapsulates the base URI for the File service.</span></span> <span data-ttu-id="f5707-106">Wenn der Dienstclient für den authentifizierten Zugriff verwendet wird, kapselt er auch die Anmeldeinformationen für den Zugriff auf das Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="f5707-106">If the service client will be used for authenticated access, it also encapsulates the credentials for accessing the storage account.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudFileClient (Microsoft.WindowsAzure.Storage.StorageUri storageUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri storageUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.CloudFileClient : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileClient" Usage="new Microsoft.WindowsAzure.Storage.File.CloudFileClient (storageUri, credentials)" />
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
        <param name="storageUri"><span data-ttu-id="f5707-107">Die Dateidienst-Endpunkt zu verwenden, um den Client zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="f5707-107">The File service endpoint to use to create the client.</span></span></param>
        <param name="credentials"><span data-ttu-id="f5707-108">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f5707-108">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-109">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileClient" /> -Klasse unter Verwendung der angegebenen Datei-Endpunkt und der Kontoanmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="f5707-109">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileClient" /> class using the specified File service endpoint and account credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudFileClient (Uri baseUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.CloudFileClient : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileClient" Usage="new Microsoft.WindowsAzure.Storage.File.CloudFileClient (baseUri, credentials)" />
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
        <param name="baseUri"><span data-ttu-id="f5707-110">Die Dateidienst-Endpunkt zu verwenden, um den Client zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="f5707-110">The File service endpoint to use to create the client.</span></span></param>
        <param name="credentials"><span data-ttu-id="f5707-111">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f5707-111">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-112">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileClient" /> -Klasse unter Verwendung der angegebenen Datei-Endpunkt und der Kontoanmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="f5707-112">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileClient" /> class using the specified File service endpoint and account credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationScheme">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.AuthenticationScheme AuthenticationScheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.AuthenticationScheme AuthenticationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileClient.AuthenticationScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationScheme As AuthenticationScheme" />
      <MemberSignature Language="F#" Value="member this.AuthenticationScheme : Microsoft.WindowsAzure.Storage.AuthenticationScheme with get, set" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileClient.AuthenticationScheme" />
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
            <span data-ttu-id="f5707-113">Ruft ab oder legt das Authentifizierungsschema zum Signieren von HTTP-Anforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5707-113">Gets or sets the authentication scheme to use to sign HTTP requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileClient.BaseUri" />
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
            <span data-ttu-id="f5707-114">Ruft den Basis-URI für den File-Dienstclient ab.</span><span class="sxs-lookup"><span data-stu-id="f5707-114">Gets the base URI for the File service client.</span></span>
            </summary>
        <value><span data-ttu-id="f5707-115">Die Basis-URI verwendet, um den File-Dienstclient erstellen.</span><span class="sxs-lookup"><span data-stu-id="f5707-115">The base URI used to construct the File service client.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceProperties (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileClient.BeginGetServiceProperties (callback, state)" />
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
        <param name="callback"><span data-ttu-id="f5707-116">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f5707-116">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f5707-117">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f5707-117">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-118">Startet einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Dateidienst an.</span><span class="sxs-lookup"><span data-stu-id="f5707-118">Begins an asynchronous operation to get service properties for the File service.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-119">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f5707-119">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties (Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BeginGetServiceProperties(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileClient.BeginGetServiceProperties (requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="f5707-120">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-120">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f5707-121">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-121">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f5707-122">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f5707-122">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f5707-123">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f5707-123">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-124">Startet einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Dateidienst an.</span><span class="sxs-lookup"><span data-stu-id="f5707-124">Begins an asynchronous operation to get service properties for the File service.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-125">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f5707-125">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListSharesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListSharesSegmented (Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListSharesSegmented(class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BeginListSharesSegmented(Microsoft.WindowsAzure.Storage.File.FileContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListSharesSegmented (currentToken As FileContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListSharesSegmented : Microsoft.WindowsAzure.Storage.File.FileContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListSharesSegmented : Microsoft.WindowsAzure.Storage.File.FileContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileClient.BeginListSharesSegmented (currentToken, callback, state)" />
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
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="f5707-126">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="f5707-126">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f5707-127">Der Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f5707-127">The callback delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f5707-128">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f5707-128">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-129">Beginnt eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, das eine Auflistung von Freigaben enthält.</span><span class="sxs-lookup"><span data-stu-id="f5707-129">Begins an asynchronous request to return a result segment containing a collection of shares.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-130">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f5707-130">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListSharesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListSharesSegmented (string prefix, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListSharesSegmented(string prefix, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BeginListSharesSegmented(System.String,Microsoft.WindowsAzure.Storage.File.FileContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListSharesSegmented (prefix As String, currentToken As FileContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListSharesSegmented : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListSharesSegmented : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileClient.BeginListSharesSegmented (prefix, currentToken, callback, state)" />
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="f5707-131">Das Präfix des Freigabenamens.</span><span class="sxs-lookup"><span data-stu-id="f5707-131">The share name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="f5707-132">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="f5707-132">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f5707-133">Der Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f5707-133">The callback delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f5707-134">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f5707-134">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-135">Beginnt eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, das eine Auflistung von Freigaben enthält.</span><span class="sxs-lookup"><span data-stu-id="f5707-135">Begins an asynchronous request to return a result segment containing a collection of shares.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-136">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f5707-136">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListSharesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListSharesSegmented (string prefix, Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListSharesSegmented(string prefix, valuetype Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BeginListSharesSegmented(System.String,Microsoft.WindowsAzure.Storage.File.ShareListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileContinuationToken,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginListSharesSegmented : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListSharesSegmented : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileClient.BeginListSharesSegmented (prefix, detailsIncluded, maxResults, currentToken, options, operationContext, callback, state)" />
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.File.ShareListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="f5707-137">Das Präfix des Freigabenamens.</span><span class="sxs-lookup"><span data-stu-id="f5707-137">The share name prefix.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="f5707-138">Ein Wert, der angibt, ob die freigabemetadaten mit der Auflistung zurück.</span><span class="sxs-lookup"><span data-stu-id="f5707-138">A value that indicates whether to return share metadata with the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="f5707-139">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von im ergebnissegment pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-139">A non-negative integer value that indicates the maximum number of results to be returned in the result segment, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="f5707-140">Wenn dieser Wert null ist, ist die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="f5707-140">If this value is null, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="f5707-141">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="f5707-141">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="f5707-142">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-142">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f5707-143">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-143">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f5707-144">Der Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f5707-144">The callback delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f5707-145">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f5707-145">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-146">Beginnt eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, enthält eine Auflistung von Freigaben, deren Namen mit dem angegebenen Präfix beginnen.</span><span class="sxs-lookup"><span data-stu-id="f5707-146">Begins an asynchronous request to return a result segment containing a collection of shares whose names begin with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-147">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f5707-147">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetServiceProperties (properties As FileServiceProperties, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileClient.BeginSetServiceProperties (properties, callback, state)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="f5707-148">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f5707-148">A <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="f5707-149">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f5707-149">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f5707-150">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f5707-150">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-151">Startet einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Dateidienst an.</span><span class="sxs-lookup"><span data-stu-id="f5707-151">Begins an asynchronous operation to set service properties for the File service.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-152">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f5707-152">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileClient.BeginSetServiceProperties (properties, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="f5707-153">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f5707-153">A <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="f5707-154">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-154">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f5707-155">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-155">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f5707-156">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f5707-156">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f5707-157">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f5707-157">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-158">Startet einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Dateidienst an.</span><span class="sxs-lookup"><span data-stu-id="f5707-158">Begins an asynchronous operation to set service properties for the File service.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-159">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f5707-159">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BufferManager">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.IBufferManager BufferManager { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.IBufferManager BufferManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BufferManager" />
      <MemberSignature Language="VB.NET" Value="Public Property BufferManager As IBufferManager" />
      <MemberSignature Language="F#" Value="member this.BufferManager : Microsoft.WindowsAzure.Storage.IBufferManager with get, set" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileClient.BufferManager" />
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
            <span data-ttu-id="f5707-160">Ruft ab oder legt einen Puffer-Manager, die implementiert die <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> -Schnittstelle, einen zu verwendender Pufferpool mit Vorgängen für den File-Dienstclient angeben.</span><span class="sxs-lookup"><span data-stu-id="f5707-160">Gets or sets a buffer manager that implements the <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> interface, specifying a buffer pool for use with operations against the File service client.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As StorageCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileClient.Credentials" />
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
            <span data-ttu-id="f5707-161">Ruft die Kontoanmeldeinformationen verwendet, um den File-Dienstclient erstellen.</span><span class="sxs-lookup"><span data-stu-id="f5707-161">Gets the account credentials used to create the File service client.</span></span>
            </summary>
        <value><span data-ttu-id="f5707-162">Die Kontoanmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="f5707-162">The account credentials.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRequestOptions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.FileRequestOptions DefaultRequestOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.FileRequestOptions DefaultRequestOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileClient.DefaultRequestOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultRequestOptions As FileRequestOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultRequestOptions : Microsoft.WindowsAzure.Storage.File.FileRequestOptions with get, set" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileClient.DefaultRequestOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileRequestOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5707-163">Ruft ab oder legt den Standardwert Anforderungsoptionen für über den File-Dienstclient vorgenommene Anforderungen.</span><span class="sxs-lookup"><span data-stu-id="f5707-163">Gets or sets the default request options for requests made via the File service client.</span></span>
            </summary>
        <value><span data-ttu-id="f5707-164">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f5707-164">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties EndGetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties EndGetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.EndGetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceProperties (asyncResult As IAsyncResult) As FileServiceProperties" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceProperties : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&#xA;override this.EndGetServiceProperties : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" Usage="cloudFileClient.EndGetServiceProperties asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f5707-165">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f5707-165">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-166">Beendet einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Dateidienst an.</span><span class="sxs-lookup"><span data-stu-id="f5707-166">Ends an asynchronous operation to get service properties for the File service.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-167">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f5707-167">A <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndListSharesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.ShareResultSegment EndListSharesSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.ShareResultSegment EndListSharesSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.EndListSharesSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndListSharesSegmented (asyncResult As IAsyncResult) As ShareResultSegment" />
      <MemberSignature Language="F#" Value="abstract member EndListSharesSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.File.ShareResultSegment&#xA;override this.EndListSharesSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.File.ShareResultSegment" Usage="cloudFileClient.EndListSharesSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.ShareResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f5707-168">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f5707-168">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-169">Beendet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Freigaben enthält.</span><span class="sxs-lookup"><span data-stu-id="f5707-169">Ends an asynchronous operation to return a result segment containing a collection of shares.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-170">Ein ergebnissegment von Freigaben.</span><span class="sxs-lookup"><span data-stu-id="f5707-170">A result segment of shares.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void EndSetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.EndSetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetServiceProperties (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetServiceProperties : IAsyncResult -&gt; unit&#xA;override this.EndSetServiceProperties : IAsyncResult -&gt; unit" Usage="cloudFileClient.EndSetServiceProperties asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="f5707-171">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f5707-171">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-172">Beendet einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Blob-Dienst an.</span><span class="sxs-lookup"><span data-stu-id="f5707-172">Ends an asynchronous operation to set service properties for the Blob service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties GetServiceProperties (Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties GetServiceProperties(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.GetServiceProperties(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceProperties : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&#xA;override this.GetServiceProperties : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" Usage="cloudFileClient.GetServiceProperties (requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="f5707-173">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-173">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f5707-174">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-174">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-175">Ruft die Diensteigenschaften für den Dateidienst ab.</span><span class="sxs-lookup"><span data-stu-id="f5707-175">Gets service properties for the File service.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-176">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f5707-176">A <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt; GetServicePropertiesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt; GetServicePropertiesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.GetServicePropertiesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServicePropertiesAsync () As Task(Of FileServiceProperties)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;" Usage="cloudFileClient.GetServicePropertiesAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f5707-177">Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Dateidienst an.</span><span class="sxs-lookup"><span data-stu-id="f5707-177">Initiates an asynchronous operation to get service properties for the File service.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-178">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-178">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt; GetServicePropertiesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt; GetServicePropertiesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.GetServicePropertiesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;" Usage="cloudFileClient.GetServicePropertiesAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f5707-179">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f5707-179">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-180">Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Dateidienst an.</span><span class="sxs-lookup"><span data-stu-id="f5707-180">Initiates an asynchronous operation to get service properties for the File service.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-181">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-181">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt; GetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.GetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;" Usage="cloudFileClient.GetServicePropertiesAsync (requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="f5707-182">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-182">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f5707-183">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-183">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-184">Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Dateidienst an.</span><span class="sxs-lookup"><span data-stu-id="f5707-184">Initiates an asynchronous operation to get service properties for the File service.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-185">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-185">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt; GetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.GetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;" Usage="cloudFileClient.GetServicePropertiesAsync (requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="f5707-186">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-186">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f5707-187">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-187">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5707-188">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f5707-188">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-189">Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Dateidienst an.</span><span class="sxs-lookup"><span data-stu-id="f5707-189">Initiates an asynchronous operation to get service properties for the File service.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-190">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-190">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShareReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.CloudFileShare GetShareReference (string shareName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.CloudFileShare GetShareReference(string shareName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.GetShareReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetShareReference (shareName As String) As CloudFileShare" />
      <MemberSignature Language="F#" Value="abstract member GetShareReference : string -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileShare&#xA;override this.GetShareReference : string -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileShare" Usage="cloudFileClient.GetShareReference shareName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.CloudFileShare</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shareName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shareName"><span data-ttu-id="f5707-191">Eine Zeichenfolge, die mit dem Namen der Freigabe.</span><span class="sxs-lookup"><span data-stu-id="f5707-191">A string containing the name of the share.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-192">Gibt einen Verweis auf ein <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" /> Objekt mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="f5707-192">Returns a reference to a <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" /> object with the specified name.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-193">Ein Verweis auf eine Freigabe.</span><span class="sxs-lookup"><span data-stu-id="f5707-193">A reference to a share.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShareReference">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.CloudFileShare GetShareReference (string shareName, Nullable&lt;DateTimeOffset&gt; snapshotTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.File.CloudFileShare GetShareReference(string shareName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.GetShareReference(System.String,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShareReference (shareName As String, snapshotTime As Nullable(Of DateTimeOffset)) As CloudFileShare" />
      <MemberSignature Language="F#" Value="member this.GetShareReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileShare" Usage="cloudFileClient.GetShareReference (shareName, snapshotTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.CloudFileShare</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shareName" Type="System.String" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="shareName"><span data-ttu-id="f5707-194">Eine Zeichenfolge, die mit dem Namen der Freigabe.</span><span class="sxs-lookup"><span data-stu-id="f5707-194">A string containing the name of the share.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="f5707-195">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel angeben, wenn die Freigabe eine Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="f5707-195">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the share is a snapshot.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-196">Gibt einen Verweis auf ein <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" /> Objekt mit dem angegebenen Namen und eine momentaufnahmezeit.</span><span class="sxs-lookup"><span data-stu-id="f5707-196">Returns a reference to a <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" /> object with the specified name and snapshot time.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-197">Ein Verweis auf eine Freigabe.</span><span class="sxs-lookup"><span data-stu-id="f5707-197">A reference to a share.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListShares">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt; ListShares (string prefix = null, Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded = Microsoft.WindowsAzure.Storage.File.ShareListingDetails.None, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt; ListShares(string prefix, valuetype Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListShares(System.String,Microsoft.WindowsAzure.Storage.File.ShareListingDetails,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListShares : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt;&#xA;override this.ListShares : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt;" Usage="cloudFileClient.ListShares (prefix, detailsIncluded, options, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.File.ShareListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="f5707-198">Das Präfix des Freigabenamens.</span><span class="sxs-lookup"><span data-stu-id="f5707-198">The share name prefix.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="f5707-199">Ein Wert, der angibt, ob die freigabemetadaten mit der Auflistung zurück.</span><span class="sxs-lookup"><span data-stu-id="f5707-199">A value that indicates whether to return share metadata with the listing.</span></span></param>
        <param name="options"><span data-ttu-id="f5707-200">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-200">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f5707-201">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-201">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-202">Gibt eine aufzählbare Auflistung von Freigaben, die verzögert abgerufen werden, deren Namen mit dem angegebenen Präfix beginnen.</span><span class="sxs-lookup"><span data-stu-id="f5707-202">Returns an enumerable collection of shares, which are retrieved lazily, whose names begin with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-203">Eine aufzählbare Auflistung von Freigaben, die verzögert abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f5707-203">An enumerable collection of shares that are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.ShareResultSegment ListSharesSegmented (Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.ShareResultSegment ListSharesSegmented(class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmented(Microsoft.WindowsAzure.Storage.File.FileContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListSharesSegmented (currentToken As FileContinuationToken) As ShareResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmented : Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; Microsoft.WindowsAzure.Storage.File.ShareResultSegment&#xA;override this.ListSharesSegmented : Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; Microsoft.WindowsAzure.Storage.File.ShareResultSegment" Usage="cloudFileClient.ListSharesSegmented currentToken" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.File.ShareResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="f5707-204">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileContinuationToken" /> Token von einem vorherigen Auflistungsvorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="f5707-204">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileContinuationToken" /> token returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-205">Gibt ein ergebnissegment mit einer Auflistung von Freigaben zurück.</span><span class="sxs-lookup"><span data-stu-id="f5707-205">Returns a result segment containing a collection of shares.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-206">Ein ergebnissegment von Freigaben.</span><span class="sxs-lookup"><span data-stu-id="f5707-206">A result segment of shares.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.ShareResultSegment ListSharesSegmented (string prefix, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.ShareResultSegment ListSharesSegmented(string prefix, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmented(System.String,Microsoft.WindowsAzure.Storage.File.FileContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListSharesSegmented (prefix As String, currentToken As FileContinuationToken) As ShareResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmented : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; Microsoft.WindowsAzure.Storage.File.ShareResultSegment&#xA;override this.ListSharesSegmented : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; Microsoft.WindowsAzure.Storage.File.ShareResultSegment" Usage="cloudFileClient.ListSharesSegmented (prefix, currentToken)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.File.ShareResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="f5707-207">Das Präfix des Freigabenamens.</span><span class="sxs-lookup"><span data-stu-id="f5707-207">The share name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="f5707-208">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="f5707-208">A continuation token returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-209">Gibt ein ergebnissegment mit einer Auflistung von Freigaben zurück.</span><span class="sxs-lookup"><span data-stu-id="f5707-209">Returns a result segment containing a collection of shares.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-210">Ein ergebnissegment von Freigaben.</span><span class="sxs-lookup"><span data-stu-id="f5707-210">A result segment of shares.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.ShareResultSegment ListSharesSegmented (string prefix, Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.ShareResultSegment ListSharesSegmented(string prefix, valuetype Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmented(System.String,Microsoft.WindowsAzure.Storage.File.ShareListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileContinuationToken,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmented : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.File.ShareResultSegment&#xA;override this.ListSharesSegmented : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.File.ShareResultSegment" Usage="cloudFileClient.ListSharesSegmented (prefix, detailsIncluded, maxResults, currentToken, options, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.File.ShareResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.File.ShareListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="f5707-211">Das Präfix des Freigabenamens.</span><span class="sxs-lookup"><span data-stu-id="f5707-211">The share name prefix.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="f5707-212">Ein Wert, der angibt, ob die freigabemetadaten mit der Auflistung zurück.</span><span class="sxs-lookup"><span data-stu-id="f5707-212">A value that indicates whether to return share metadata with the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="f5707-213">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von im ergebnissegment pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-213">A non-negative integer value that indicates the maximum number of results to be returned in the result segment, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="f5707-214">Wenn dieser Wert null ist, ist die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="f5707-214">If this value is null, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="f5707-215">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="f5707-215">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="f5707-216">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-216">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f5707-217">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-217">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-218">Gibt ein ergebnissegment mit einer Auflistung von Freigaben, deren Namen mit dem angegebenen Präfix beginnen.</span><span class="sxs-lookup"><span data-stu-id="f5707-218">Returns a result segment containing a collection of shares whose names begin with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-219">Ein ergebnissegment von Freigaben.</span><span class="sxs-lookup"><span data-stu-id="f5707-219">A result segment of shares.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync (Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync(class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmentedAsync(Microsoft.WindowsAzure.Storage.File.FileContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListSharesSegmentedAsync (currentToken As FileContinuationToken) As Task(Of ShareResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmentedAsync : Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;&#xA;override this.ListSharesSegmentedAsync : Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;" Usage="cloudFileClient.ListSharesSegmentedAsync currentToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="f5707-220">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileContinuationToken" /> Token von einem vorherigen Auflistungsvorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="f5707-220">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileContinuationToken" /> token returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-221">Gibt eine Aufgabe, die eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, enthält eine Auflistung von Freigaben ausführt.</span><span class="sxs-lookup"><span data-stu-id="f5707-221">Returns a task that performs an asynchronous request to return a result segment containing a collection of shares.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-222">Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-222">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the current operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync (Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync(class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmentedAsync(Microsoft.WindowsAzure.Storage.File.FileContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmentedAsync : Microsoft.WindowsAzure.Storage.File.FileContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;&#xA;override this.ListSharesSegmentedAsync : Microsoft.WindowsAzure.Storage.File.FileContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;" Usage="cloudFileClient.ListSharesSegmentedAsync (currentToken, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="f5707-223">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileContinuationToken" /> Token von einem vorherigen Auflistungsvorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="f5707-223">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileContinuationToken" /> token returned by a previous listing operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5707-224">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f5707-224">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-225">Gibt eine Aufgabe, die eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, enthält eine Auflistung von Freigaben ausführt.</span><span class="sxs-lookup"><span data-stu-id="f5707-225">Returns a task that performs an asynchronous request to return a result segment containing a collection of shares.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-226">Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-226">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the current operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.File.FileContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListSharesSegmentedAsync (prefix As String, currentToken As FileContinuationToken) As Task(Of ShareResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;&#xA;override this.ListSharesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;" Usage="cloudFileClient.ListSharesSegmentedAsync (prefix, currentToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="f5707-227">Das Präfix des Freigabenamens.</span><span class="sxs-lookup"><span data-stu-id="f5707-227">The share name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="f5707-228">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="f5707-228">A continuation token returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-229">Gibt eine Aufgabe, die führt eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, enthält eine Auflistung von Freigaben, deren Namen mit dem angegebenen Präfix beginnen.</span><span class="sxs-lookup"><span data-stu-id="f5707-229">Returns a task that performs an asynchronous request to return a result segment containing a collection of shares whose names begin with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-230">Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-230">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the current operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.File.FileContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;&#xA;override this.ListSharesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;" Usage="cloudFileClient.ListSharesSegmentedAsync (prefix, currentToken, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="f5707-231">Das Präfix des Freigabenamens.</span><span class="sxs-lookup"><span data-stu-id="f5707-231">The share name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="f5707-232">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="f5707-232">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5707-233">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f5707-233">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-234">Gibt eine Aufgabe, die führt eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, enthält eine Auflistung von Freigaben, deren Namen mit dem angegebenen Präfix beginnen.</span><span class="sxs-lookup"><span data-stu-id="f5707-234">Returns a task that performs an asynchronous request to return a result segment containing a collection of shares whose names begin with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-235">Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-235">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the current operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync(string prefix, valuetype Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.File.ShareListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileContinuationToken,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;&#xA;override this.ListSharesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;" Usage="cloudFileClient.ListSharesSegmentedAsync (prefix, detailsIncluded, maxResults, currentToken, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.File.ShareListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="f5707-236">Das Präfix des Freigabenamens.</span><span class="sxs-lookup"><span data-stu-id="f5707-236">The share name prefix.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="f5707-237">Ein Wert, der angibt, ob die freigabemetadaten mit der Auflistung zurück.</span><span class="sxs-lookup"><span data-stu-id="f5707-237">A value that indicates whether to return share metadata with the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="f5707-238">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von im ergebnissegment pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-238">A non-negative integer value that indicates the maximum number of results to be returned in the result segment, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="f5707-239">Wenn dieser Wert null ist, ist die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="f5707-239">If this value is null, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="f5707-240">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="f5707-240">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="f5707-241">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-241">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f5707-242">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-242">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-243">Gibt eine Aufgabe, die führt eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, enthält eine Auflistung von Freigaben, deren Namen mit dem angegebenen Präfix beginnen.</span><span class="sxs-lookup"><span data-stu-id="f5707-243">Returns a task that performs an asynchronous request to return a result segment containing a collection of shares whose names begin with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-244">Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-244">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the current operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync(string prefix, valuetype Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.File.ShareListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileContinuationToken,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;&#xA;override this.ListSharesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;" Usage="cloudFileClient.ListSharesSegmentedAsync (prefix, detailsIncluded, maxResults, currentToken, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.File.ShareListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="f5707-245">Das Präfix des Freigabenamens.</span><span class="sxs-lookup"><span data-stu-id="f5707-245">The share name prefix.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="f5707-246">Ein Wert, der angibt, ob die freigabemetadaten mit der Auflistung zurück.</span><span class="sxs-lookup"><span data-stu-id="f5707-246">A value that indicates whether to return share metadata with the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="f5707-247">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von im ergebnissegment pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-247">A non-negative integer value that indicates the maximum number of results to be returned in the result segment, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="f5707-248">Wenn dieser Wert null ist, ist die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="f5707-248">If this value is null, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="f5707-249">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="f5707-249">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="f5707-250">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-250">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f5707-251">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-251">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5707-252">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f5707-252">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-253">Gibt eine Aufgabe, die führt eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, enthält eine Auflistung von Freigaben, deren Namen mit dem angegebenen Präfix beginnen.</span><span class="sxs-lookup"><span data-stu-id="f5707-253">Returns a task that performs an asynchronous request to return a result segment containing a collection of shares whose names begin with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-254">Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-254">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the current operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void SetServiceProperties (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetServiceProperties(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.SetServiceProperties(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServiceProperties : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetServiceProperties : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudFileClient.SetServiceProperties (properties, requestOptions, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="f5707-255">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f5707-255">A <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="f5707-256">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-256">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f5707-257">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-257">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-258">Legt die Diensteigenschaften für den Dateidienst.</span><span class="sxs-lookup"><span data-stu-id="f5707-258">Sets service properties for the File service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetServicePropertiesAsync (properties As FileServiceProperties) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties -&gt; System.Threading.Tasks.Task" Usage="cloudFileClient.SetServicePropertiesAsync properties" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="f5707-259">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f5707-259">A <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-260">Initiiert einen asynchronen Vorgang, durch die Diensteigenschaften für den Blob-Dienst festgelegt.</span><span class="sxs-lookup"><span data-stu-id="f5707-260">Initiates an asynchronous operation that sets service properties for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-261">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-261">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileClient.SetServicePropertiesAsync (properties, cancellationToken)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="f5707-262">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f5707-262">A <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5707-263">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f5707-263">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-264">Initiiert einen asynchronen Vorgang, durch die Diensteigenschaften für den Blob-Dienst festgelegt.</span><span class="sxs-lookup"><span data-stu-id="f5707-264">Initiates an asynchronous operation that sets service properties for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-265">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-265">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudFileClient.SetServicePropertiesAsync (properties, requestOptions, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="f5707-266">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f5707-266">A <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="f5707-267">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-267">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f5707-268">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-268">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-269">Initiiert einen asynchronen Vorgang, der Diensteigenschaften für den Dateidienst festlegt.</span><span class="sxs-lookup"><span data-stu-id="f5707-269">Initiates an asynchronous operation that sets service properties for the File service.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-270">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-270">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileClient.SetServicePropertiesAsync (properties, requestOptions, operationContext, cancellationToken)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="f5707-271">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f5707-271">A <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="f5707-272">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f5707-272">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f5707-273">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-273">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f5707-274">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f5707-274">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f5707-275">Initiiert einen asynchronen Vorgang, der Diensteigenschaften für den Dateidienst festlegt.</span><span class="sxs-lookup"><span data-stu-id="f5707-275">Initiates an asynchronous operation that sets service properties for the File service.</span></span>
            </summary>
        <returns><span data-ttu-id="f5707-276">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f5707-276">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileClient.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileClient.StorageUri" />
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
            <span data-ttu-id="f5707-277">Ruft die Liste der URIs für alle Speicherorte ab.</span><span class="sxs-lookup"><span data-stu-id="f5707-277">Gets the list of URIs for all locations.</span></span>
            </summary>
        <value><span data-ttu-id="f5707-278">Die Liste der URIs für alle Speicherorte.</span><span class="sxs-lookup"><span data-stu-id="f5707-278">The list of URIs for all locations.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>