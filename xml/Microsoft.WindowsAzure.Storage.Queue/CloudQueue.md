<Type Name="CloudQueue" FullName="Microsoft.WindowsAzure.Storage.Queue.CloudQueue">
  <TypeSignature Language="C#" Value="public class CloudQueue" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudQueue extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudQueue" />
  <TypeSignature Language="F#" Value="type CloudQueue = class" />
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
            <span data-ttu-id="15c63-101">Diese Klasse stellt eine Warteschlange im Microsoft Azure-Warteschlangendienst dar.</span><span class="sxs-lookup"><span data-stu-id="15c63-101">This class represents a queue in the Microsoft Azure Queue service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueue (Uri queueAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri queueAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (queueAddress As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueue : Uri -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueue" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueue queueAddress" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="queueAddress" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="queueAddress"><span data-ttu-id="15c63-102">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-102">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="15c63-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueue (Microsoft.WindowsAzure.Storage.StorageUri queueAddress, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri queueAddress, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (queueAddress As StorageUri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueue : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueue" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueue (queueAddress, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="queueAddress" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="queueAddress"><span data-ttu-id="15c63-104">Ein <see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.StorageUri" /> , den absoluten URI zur Warteschlange am primären und sekundären Speicherorte enthält.</span><span class="sxs-lookup"><span data-stu-id="15c63-104">A <see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.StorageUri" /> containing the absolute URI to the queue at both the primary and secondary locations.</span></span></param>
        <param name="credentials"><span data-ttu-id="15c63-105">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-105">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="15c63-106">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> class.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-107">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-107">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueue (Uri queueAddress, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri queueAddress, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (queueAddress As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueue : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueue" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueue (queueAddress, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="queueAddress" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="queueAddress"><span data-ttu-id="15c63-108">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-108">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="credentials"><span data-ttu-id="15c63-109">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-109">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-110">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="15c63-110">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMessage">
      <MemberSignature Language="C#" Value="public virtual void AddMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, Nullable&lt;TimeSpan&gt; timeToLive = null, Nullable&lt;TimeSpan&gt; initialVisibilityDelay = null, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AddMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeToLive, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; initialVisibilityDelay, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.AddMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AddMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.AddMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.AddMessage (message, timeToLive, initialVisibilityDelay, options, operationContext)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="timeToLive" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="initialVisibilityDelay" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-111">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-111">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="timeToLive"><span data-ttu-id="15c63-112">Ein <see cref="T:System.TimeSpan" /> angeben die maximal zulässige Ausführungszeit für die Nachricht in der Warteschlange bleiben kann oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="15c63-112">A <see cref="T:System.TimeSpan" /> specifying the maximum time to allow the message to be in the queue, or <c>null</c>.</span></span></param>
        <param name="initialVisibilityDelay"><span data-ttu-id="15c63-113">Ein <see cref="T:System.TimeSpan" /> angeben das Zeitintervall aus jetzt, die Nachricht nicht sichtbar sein soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-113">A <see cref="T:System.TimeSpan" /> specifying the interval of time from now during which the message will be invisible.</span></span>
            <span data-ttu-id="15c63-114">Wenn <c>null</c> und dann die Nachricht sofort sichtbar.</span><span class="sxs-lookup"><span data-stu-id="15c63-114">If <c>null</c> then the message will be visible immediately.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-115">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-115">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-116">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-116">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-117">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-117">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-118">Fügt eine Nachricht an die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-118">Adds a message to the queue.</span></span>
            </summary>
        <remarks><span data-ttu-id="15c63-119">Die <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> übergebene Nachricht wird mit der abrufbestätigung, Nachrichten-ID und die Einfügung/Ablaufzeit aufgefüllt.</span><span class="sxs-lookup"><span data-stu-id="15c63-119">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> message passed in will be populated with the pop receipt, message ID, and the insertion/expiration time.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AddMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.AddMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function AddMessageAsync (message As CloudQueueMessage) As Task" />
      <MemberSignature Language="F#" Value="abstract member AddMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage -&gt; System.Threading.Tasks.Task&#xA;override this.AddMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.AddMessageAsync message" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-120">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-120">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-121">Initiiert einen asynchronen Vorgang zum Hinzufügen einer Nachricht an die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-121">Initiates an asynchronous operation to add a message to the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-122">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-122">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15c63-123">Die <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> übergebene Nachricht wird mit der abrufbestätigung, Nachrichten-ID und die Einfügung/Ablaufzeit aufgefüllt.</span><span class="sxs-lookup"><span data-stu-id="15c63-123">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> message passed in will be populated with the pop receipt, message ID, and the insertion/expiration time.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AddMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.AddMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AddMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.AddMessageAsync (message, cancellationToken)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-124">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-124">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-125">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-125">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-126">Initiiert einen asynchronen Vorgang zum Hinzufügen einer Nachricht an die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-126">Initiates an asynchronous operation to add a message to the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-127">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-127">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15c63-128">Die <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> übergebene Nachricht wird mit der abrufbestätigung, Nachrichten-ID und die Einfügung/Ablaufzeit aufgefüllt.</span><span class="sxs-lookup"><span data-stu-id="15c63-128">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> message passed in will be populated with the pop receipt, message ID, and the insertion/expiration time.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AddMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, Nullable&lt;TimeSpan&gt; timeToLive, Nullable&lt;TimeSpan&gt; initialVisibilityDelay, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeToLive, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; initialVisibilityDelay, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.AddMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AddMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.AddMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.AddMessageAsync (message, timeToLive, initialVisibilityDelay, options, operationContext)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="timeToLive" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="initialVisibilityDelay" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-129">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-129">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="timeToLive"><span data-ttu-id="15c63-130">Ein <see cref="T:System.TimeSpan" /> angeben die maximal zulässige Ausführungszeit für die Nachricht in der Warteschlange bleiben kann oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="15c63-130">A <see cref="T:System.TimeSpan" /> specifying the maximum time to allow the message to be in the queue, or <c>null</c>.</span></span></param>
        <param name="initialVisibilityDelay"><span data-ttu-id="15c63-131">Ein <see cref="T:System.TimeSpan" /> angeben das Zeitintervall aus jetzt, die Nachricht nicht sichtbar sein soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-131">A <see cref="T:System.TimeSpan" /> specifying the interval of time from now during which the message will be invisible.</span></span>
            <span data-ttu-id="15c63-132">Wenn <c>null</c> und dann die Nachricht sofort sichtbar.</span><span class="sxs-lookup"><span data-stu-id="15c63-132">If <c>null</c> then the message will be visible immediately.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-133">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-133">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-134">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-134">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-135">Initiiert einen asynchronen Vorgang zum Hinzufügen einer Nachricht an die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-135">Initiates an asynchronous operation to add a message to the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-136">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-136">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15c63-137">Die <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> übergebene Nachricht wird mit der abrufbestätigung, Nachrichten-ID und die Einfügung/Ablaufzeit aufgefüllt.</span><span class="sxs-lookup"><span data-stu-id="15c63-137">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> message passed in will be populated with the pop receipt, message ID, and the insertion/expiration time.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AddMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, Nullable&lt;TimeSpan&gt; timeToLive, Nullable&lt;TimeSpan&gt; initialVisibilityDelay, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeToLive, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; initialVisibilityDelay, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.AddMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AddMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.AddMessageAsync (message, timeToLive, initialVisibilityDelay, options, operationContext, cancellationToken)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="timeToLive" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="initialVisibilityDelay" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-138">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-138">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="timeToLive"><span data-ttu-id="15c63-139">Ein <see cref="T:System.TimeSpan" /> angeben die maximal zulässige Ausführungszeit für die Nachricht in der Warteschlange bleiben kann oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="15c63-139">A <see cref="T:System.TimeSpan" /> specifying the maximum time to allow the message to be in the queue, or <c>null</c>.</span></span></param>
        <param name="initialVisibilityDelay"><span data-ttu-id="15c63-140">Ein <see cref="T:System.TimeSpan" /> angeben das Zeitintervall aus jetzt, die Nachricht nicht sichtbar sein soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-140">A <see cref="T:System.TimeSpan" /> specifying the interval of time from now during which the message will be invisible.</span></span>
            <span data-ttu-id="15c63-141">Wenn <c>null</c> und dann die Nachricht sofort sichtbar.</span><span class="sxs-lookup"><span data-stu-id="15c63-141">If <c>null</c> then the message will be visible immediately.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-142">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-142">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-143">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-143">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-144">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-144">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-145">Initiiert einen asynchronen Vorgang zum Hinzufügen einer Nachricht an die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-145">Initiates an asynchronous operation to add a message to the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-146">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-146">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15c63-147">Die <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> übergebene Nachricht wird mit der abrufbestätigung, Nachrichten-ID und die Einfügung/Ablaufzeit aufgefüllt.</span><span class="sxs-lookup"><span data-stu-id="15c63-147">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> message passed in will be populated with the pop receipt, message ID, and the insertion/expiration time.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ApproximateMessageCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ApproximateMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ApproximateMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ApproximateMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApproximateMessageCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ApproximateMessageCount : Nullable&lt;int&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ApproximateMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="15c63-148">Ruft die ungefähre Nachrichtenanzahl für die Warteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="15c63-148">Gets the approximate message count for the queue.</span></span>
            </summary>
        <value><span data-ttu-id="15c63-149">Die ungefähre Nachrichtenanzahl.</span><span class="sxs-lookup"><span data-stu-id="15c63-149">The approximate message count.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAddMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAddMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAddMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginAddMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginAddMessage (message As CloudQueueMessage, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginAddMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAddMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginAddMessage (message, callback, state)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-150">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-150">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-151">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-151">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-152">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-152">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-153">Startet einen asynchronen Vorgang zum Hinzufügen einer Nachricht an die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-153">Begins an asynchronous operation to add a message to the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-154">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-154">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAddMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAddMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, Nullable&lt;TimeSpan&gt; timeToLive, Nullable&lt;TimeSpan&gt; initialVisibilityDelay, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAddMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeToLive, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; initialVisibilityDelay, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginAddMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginAddMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAddMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginAddMessage (message, timeToLive, initialVisibilityDelay, options, operationContext, callback, state)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="timeToLive" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="initialVisibilityDelay" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-155">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-155">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="timeToLive"><span data-ttu-id="15c63-156">Ein <see cref="T:System.TimeSpan" /> angeben die maximal zulässige Ausführungszeit für die Nachricht in der Warteschlange bleiben kann oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="15c63-156">A <see cref="T:System.TimeSpan" /> specifying the maximum time to allow the message to be in the queue, or <c>null</c>.</span></span></param>
        <param name="initialVisibilityDelay"><span data-ttu-id="15c63-157">Ein <see cref="T:System.TimeSpan" /> angeben das Zeitintervall aus jetzt, die Nachricht nicht sichtbar sein soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-157">A <see cref="T:System.TimeSpan" /> specifying the interval of time from now during which the message will be invisible.</span></span>
            <span data-ttu-id="15c63-158">Wenn <c>null</c> und dann die Nachricht sofort sichtbar.</span><span class="sxs-lookup"><span data-stu-id="15c63-158">If <c>null</c> then the message will be visible immediately.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-159">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-159">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-160">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-160">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-161">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-161">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-162">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-162">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-163">Startet einen asynchronen Vorgang zum Hinzufügen einer Nachricht an die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-163">Begins an asynchronous operation to add a message to the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-164">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-164">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginClear">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginClear (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginClear(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginClear(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginClear (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginClear : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginClear : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginClear (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15c63-165">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-165">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-166">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-166">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-167">Startet einen asynchronen Vorgang, um alle Nachrichten aus der Warteschlange zu löschen.</span><span class="sxs-lookup"><span data-stu-id="15c63-167">Begins an asynchronous operation to clear all messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-168">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-168">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginClear">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginClear (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginClear(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginClear(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginClear : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginClear : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginClear (options, operationContext, callback, state)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-169">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-169">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-170">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-170">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-171">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-171">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-172">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-172">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-173">Startet einen asynchronen Vorgang, um alle Nachrichten aus der Warteschlange zu löschen.</span><span class="sxs-lookup"><span data-stu-id="15c63-173">Begins an asynchronous operation to clear all messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-174">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-174">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginCreate(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreate (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginCreate (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15c63-175">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-175">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-176">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-176">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-177">Startet einen asynchronen Vorgang zum Erstellen einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-177">Begins an asynchronous operation to create a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-178">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-178">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginCreate(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginCreate (options, operationContext, callback, state)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-179">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-179">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-180">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-180">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-181">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-181">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-182">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-182">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-183">Startet einen asynchronen Vorgang zum Erstellen einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-183">Begins an asynchronous operation to create a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-184">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-184">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginCreateIfNotExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreateIfNotExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginCreateIfNotExists (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15c63-185">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-185">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-186">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-186">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-187">Startet einen asynchronen Vorgang zum Erstellen der Warteschlange, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-187">Begins an asynchronous operation to create the queue if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-188">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-188">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15c63-189">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="15c63-189">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginCreateIfNotExists(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginCreateIfNotExists (options, operationContext, callback, state)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-190">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-190">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-191">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-191">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-192">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-192">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-193">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-193">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-194">Startet einen asynchronen Vorgang zum Erstellen der Warteschlange, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-194">Begins an asynchronous operation to create the queue if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-195">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-195">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15c63-196">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="15c63-196">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginDelete(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDelete (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginDelete (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15c63-197">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-197">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-198">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-198">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-199">Startet einen asynchronen Vorgang zum Löschen einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-199">Begins an asynchronous operation to delete a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-200">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-200">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginDelete(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginDelete (options, operationContext, callback, state)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-201">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-201">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-202">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-202">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-203">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-203">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-204">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-204">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-205">Startet einen asynchronen Vorgang zum Löschen einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-205">Begins an asynchronous operation to delete a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-206">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-206">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginDeleteIfExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDeleteIfExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginDeleteIfExists (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15c63-207">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-207">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-208">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-208">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-209">Startet einen asynchronen Vorgang zum Löschen der Warteschlange, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-209">Begins an asynchronous operation to delete the queue if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-210">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-210">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginDeleteIfExists(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginDeleteIfExists (options, operationContext, callback, state)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-211">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-211">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-212">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-212">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-213">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-213">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-214">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-214">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-215">Startet einen asynchronen Vorgang zum Löschen der Warteschlange, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-215">Begins an asynchronous operation to delete the queue if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-216">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-216">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginDeleteMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDeleteMessage (message As CloudQueueMessage, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginDeleteMessage (message, callback, state)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-217">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-217">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-218">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-218">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-219">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-219">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-220">Startet einen asynchronen Vorgang zum Löschen einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="15c63-220">Begins an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-221">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-221">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteMessage (string messageId, string popReceipt, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteMessage(string messageId, string popReceipt, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginDeleteMessage(System.String,System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDeleteMessage (messageId As String, popReceipt As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteMessage : string * string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteMessage : string * string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginDeleteMessage (messageId, popReceipt, callback, state)" />
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
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="messageId"><span data-ttu-id="15c63-222">Eine Zeichenfolge, die Nachrichten-ID angibt</span><span class="sxs-lookup"><span data-stu-id="15c63-222">A string specifying the message ID.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="15c63-223">Eine Zeichenfolge, die den abrufbestätigungswert angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-223">A string specifying the pop receipt value.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-224">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-224">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-225">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-225">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-226">Startet einen asynchronen Vorgang zum Löschen einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="15c63-226">Begins an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-227">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-227">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginDeleteMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginDeleteMessage (message, options, operationContext, callback, state)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-228">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-228">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-229">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-229">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-230">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-230">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-231">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-231">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-232">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-232">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-233">Startet einen asynchronen Vorgang zum Löschen einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="15c63-233">Begins an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-234">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-234">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteMessage (string messageId, string popReceipt, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteMessage(string messageId, string popReceipt, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginDeleteMessage(System.String,System.String,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteMessage : string * string * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteMessage : string * string * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginDeleteMessage (messageId, popReceipt, options, operationContext, callback, state)" />
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
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="messageId"><span data-ttu-id="15c63-235">Eine Zeichenfolge, die Nachrichten-ID angibt</span><span class="sxs-lookup"><span data-stu-id="15c63-235">A string specifying the message ID.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="15c63-236">Eine Zeichenfolge, die den abrufbestätigungswert angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-236">A string specifying the pop receipt value.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-237">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-237">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-238">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-238">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-239">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-239">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-240">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-240">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-241">Startet einen asynchronen Vorgang zum Löschen einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="15c63-241">Begins an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-242">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-242">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginExists (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15c63-243">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-243">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-244">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-244">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-245">Startet einen asynchronen Vorgang, um das Vorhandensein der Warteschlange zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="15c63-245">Begins an asynchronous operation to check the existence of the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-246">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-246">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginExists(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginExists (options, operationContext, callback, state)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-247">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-247">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-248">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-248">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-249">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-249">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-250">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-250">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-251">Startet einen asynchronen Vorgang, um das Vorhandensein der Warteschlange zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="15c63-251">Begins an asynchronous operation to check the existence of the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-252">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-252">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginFetchAttributes(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginFetchAttributes (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginFetchAttributes : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginFetchAttributes : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginFetchAttributes (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15c63-253">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-253">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-254">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-254">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-255">Startet einen asynchronen Vorgang zum Abrufen von Attributen für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-255">Begins an asynchronous operation to fetch the queue's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-256">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-256">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginFetchAttributes : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginFetchAttributes : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginFetchAttributes (options, operationContext, callback, state)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-257">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-257">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-258">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-258">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-259">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-259">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-260">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-260">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-261">Startet einen asynchronen Vorgang zum Abrufen von Attributen für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-261">Begins an asynchronous operation to fetch the queue's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-262">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-262">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetMessage (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetMessage(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginGetMessage(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetMessage (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetMessage : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetMessage : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginGetMessage (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15c63-263">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-263">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-264">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-264">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-265">Startet einen asynchronen Vorgang zum Abrufen einer einzelnen Nachricht aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-265">Begins an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-266">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-266">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetMessage (Nullable&lt;TimeSpan&gt; visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetMessage(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginGetMessage(System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetMessage : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetMessage : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginGetMessage (visibilityTimeout, options, operationContext, callback, state)" />
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
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="visibilityTimeout"><span data-ttu-id="15c63-267">Ein <see cref="T:System.TimeSpan" /> das Timeoutintervall für die Sichtbarkeit angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-267">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-268">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-268">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-269">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-269">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-270">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-270">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-271">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-271">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-272">Startet einen asynchronen Vorgang, um eine einzelne Nachricht aus der Warteschlange abzurufen, und gibt an, wie lange die Nachricht reserviert werden soll, bevor es sichtbar und daher für die Löschung verfügbar wird.</span><span class="sxs-lookup"><span data-stu-id="15c63-272">Begins an asynchronous operation to get a single message from the queue, and specifies how long the message should be reserved before it becomes visible, and therefore available for deletion.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-273">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-273">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetMessages">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetMessages (int messageCount, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetMessages(int32 messageCount, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginGetMessages(System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetMessages (messageCount As Integer, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetMessages : int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetMessages : int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginGetMessages (messageCount, callback, state)" />
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
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="15c63-274">Die Anzahl der abzurufenden Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="15c63-274">The number of messages to retrieve.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-275">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-275">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-276">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-276">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-277">Startet einen asynchronen Vorgang zum Abrufen von Nachrichten aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-277">Begins an asynchronous operation to get messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-278">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-278">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetMessages">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetMessages (int messageCount, Nullable&lt;TimeSpan&gt; visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetMessages(int32 messageCount, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginGetMessages(System.Int32,System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetMessages : int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetMessages : int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginGetMessages (messageCount, visibilityTimeout, options, operationContext, callback, state)" />
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
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="15c63-279">Die Anzahl der abzurufenden Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="15c63-279">The number of messages to retrieve.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="15c63-280">Ein <see cref="T:System.TimeSpan" /> das Timeoutintervall für die Sichtbarkeit angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-280">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-281">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-281">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-282">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-282">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-283">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-283">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-284">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-284">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-285">Startet einen asynchronen Vorgang zum Abrufen der angegebenen Anzahl von Nachrichten aus der Warteschlange, die unter Verwendung des angegebenen Anforderungsoptionen und Vorgangskontext.</span><span class="sxs-lookup"><span data-stu-id="15c63-285">Begins an asynchronous operation to get the specified number of messages from the queue using the specified request options and operation context.</span></span> <span data-ttu-id="15c63-286">Dieser Vorgang kennzeichnet die abgerufenen Nachrichten als nicht sichtbar, in der Warteschlange für das Standardtimeout für die Sichtbarkeit.</span><span class="sxs-lookup"><span data-stu-id="15c63-286">This operation marks the retrieved messages as invisible in the queue for the default visibility timeout period.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-287">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-287">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginGetPermissions(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetPermissions (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPermissions : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPermissions : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginGetPermissions (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15c63-288">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-288">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-289">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-289">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-290">Startet einen asynchronen Vorgang zum Abrufen der berechtigungseinstellungen für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-290">Begins an asynchronous operation to get the permissions settings for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-291">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-291">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginGetPermissions(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPermissions : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPermissions : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginGetPermissions (options, operationContext, callback, state)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-292">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-292">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-293">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-293">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-294">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-294">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-295">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-295">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-296">Startet einen asynchronen Vorgang zum Abrufen der berechtigungseinstellungen für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-296">Begins an asynchronous operation to get the permissions settings for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-297">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-297">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPeekMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPeekMessage (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPeekMessage(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginPeekMessage(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginPeekMessage (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginPeekMessage : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginPeekMessage : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginPeekMessage (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15c63-298">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-298">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-299">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-299">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-300">Startet einen asynchronen Vorgang zum Abrufen einer einzelnen Nachricht aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-300">Begins an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-301">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-301">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPeekMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPeekMessage (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPeekMessage(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginPeekMessage(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginPeekMessage : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginPeekMessage : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginPeekMessage (options, operationContext, callback, state)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-302">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-302">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-303">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-303">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-304">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-304">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-305">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-305">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-306">Startet einen asynchronen Vorgang zum Einsehen einer einzelnen Nachricht aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-306">Begins an asynchronous operation to peek a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-307">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-307">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPeekMessages">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPeekMessages (int messageCount, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPeekMessages(int32 messageCount, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginPeekMessages(System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginPeekMessages (messageCount As Integer, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginPeekMessages : int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginPeekMessages : int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginPeekMessages (messageCount, callback, state)" />
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
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="15c63-308">Die Anzahl der Nachrichten einsehen.</span><span class="sxs-lookup"><span data-stu-id="15c63-308">The number of messages to peek.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-309">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-309">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-310">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-310">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-311">Startet einen asynchronen Vorgang zum Einsehen von Nachrichten aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-311">Begins an asynchronous operation to peek messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-312">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-312">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPeekMessages">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPeekMessages (int messageCount, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPeekMessages(int32 messageCount, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginPeekMessages(System.Int32,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginPeekMessages : int * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginPeekMessages : int * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginPeekMessages (messageCount, options, operationContext, callback, state)" />
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
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="15c63-313">Die Anzahl der Nachrichten einsehen.</span><span class="sxs-lookup"><span data-stu-id="15c63-313">The number of messages to peek.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-314">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-314">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-315">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-315">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-316">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-316">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-317">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-317">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-318">Startet einen asynchronen Vorgang zum Einsehen von Nachrichten aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-318">Begins an asynchronous operation to peek messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-319">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-319">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetMetadata">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginSetMetadata(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetMetadata (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetMetadata : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetMetadata : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginSetMetadata (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15c63-320">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-320">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-321">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-321">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-322">Startet einen asynchronen Vorgang zum Festlegen von benutzerdefinierten Metadaten für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-322">Begins an asynchronous operation to set user-defined metadata on the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-323">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-323">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetMetadata">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginSetMetadata(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetMetadata : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetMetadata : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginSetMetadata (options, operationContext, callback, state)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-324">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-324">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-325">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-325">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-326">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-326">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-327">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-327">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-328">Startet einen asynchronen Vorgang zum Festlegen von benutzerdefinierten Metadaten für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-328">Begins an asynchronous operation to set user-defined metadata on the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-329">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-329">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions (Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions(class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginSetPermissions(Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetPermissions (permissions As QueuePermissions, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPermissions : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPermissions : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginSetPermissions (permissions, callback, state)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="15c63-330">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-330">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-331">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-331">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-332">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-332">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-333">Startet einen asynchronen Vorgang zum Festlegen von Berechtigungen für die Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-333">Begins an asynchronous operation to set permissions for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-334">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-334">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions (Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions(class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginSetPermissions(Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPermissions : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPermissions : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginSetPermissions (permissions, options, operationContext, callback, state)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="15c63-335">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-335">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-336">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-336">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-337">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-337">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-338">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-338">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-339">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-339">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-340">Startet einen asynchronen Vorgang zum Festlegen von Berechtigungen für die Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-340">Begins an asynchronous operation to set permissions for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-341">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-341">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUpdateMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, TimeSpan visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUpdateMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.TimeSpan visibilityTimeout, valuetype Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginUpdateMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.TimeSpan,Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUpdateMessage (message As CloudQueueMessage, visibilityTimeout As TimeSpan, updateFields As MessageUpdateFields, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUpdateMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginUpdateMessage (message, visibilityTimeout, updateFields, callback, state)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="visibilityTimeout" Type="System.TimeSpan" />
        <Parameter Name="updateFields" Type="Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-342">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-342">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="15c63-343">Ein <see cref="T:System.TimeSpan" /> das Timeoutintervall für die Sichtbarkeit angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-343">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="updateFields"><span data-ttu-id="15c63-344">Eine Reihe von <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> Werte, die angeben, welche Teile der Nachricht sind, aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-344">A set of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> values that specify which parts of the message are to be updated.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-345">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-345">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-346">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-346">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-347">Startet einen asynchronen Vorgang, um das sichtbarkeitstimeout und optional den Inhalt einer Nachricht zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="15c63-347">Begins an asynchronous operation to update the visibility timeout and optionally the content of a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-348">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-348">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUpdateMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, TimeSpan visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUpdateMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.TimeSpan visibilityTimeout, valuetype Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginUpdateMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.TimeSpan,Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUpdateMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginUpdateMessage (message, visibilityTimeout, updateFields, options, operationContext, callback, state)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="visibilityTimeout" Type="System.TimeSpan" />
        <Parameter Name="updateFields" Type="Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-349">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-349">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="15c63-350">Ein <see cref="T:System.TimeSpan" /> das Timeoutintervall für die Sichtbarkeit angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-350">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="updateFields"><span data-ttu-id="15c63-351">Eine Reihe von <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> Werte, die angeben, welche Teile der Nachricht sind, aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-351">A set of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> values that specify which parts of the message are to be updated.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-352">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-352">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-353">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-353">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15c63-354">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-354">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15c63-355">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-355">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-356">Startet einen asynchronen Vorgang, um das sichtbarkeitstimeout und optional den Inhalt einer Nachricht zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="15c63-356">Begins an asynchronous operation to update the visibility timeout and optionally the content of a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-357">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-357">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public virtual void Clear (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Clear(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Clear : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Clear : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.Clear (options, operationContext)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-358">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-358">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-359">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-359">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-360">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-360">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-361">Löscht alle Nachrichten aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-361">Clears all messages from the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ClearAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ClearAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ClearAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member ClearAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.ClearAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.ClearAsync " />
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15c63-362">Initiiert einen asynchronen Vorgang, um alle Nachrichten aus der Warteschlange zu löschen.</span><span class="sxs-lookup"><span data-stu-id="15c63-362">Initiates an asynchronous operation to clear all messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-363">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-363">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ClearAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ClearAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ClearAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.ClearAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.ClearAsync cancellationToken" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15c63-364">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-364">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-365">Initiiert einen asynchronen Vorgang, um alle Nachrichten aus der Warteschlange zu löschen.</span><span class="sxs-lookup"><span data-stu-id="15c63-365">Initiates an asynchronous operation to clear all messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-366">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-366">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ClearAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ClearAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ClearAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.ClearAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.ClearAsync (options, operationContext)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-367">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-367">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-368">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-368">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-369">Initiiert einen asynchronen Vorgang, um alle Nachrichten aus der Warteschlange zu löschen.</span><span class="sxs-lookup"><span data-stu-id="15c63-369">Initiates an asynchronous operation to clear all messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-370">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-370">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ClearAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ClearAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ClearAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.ClearAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.ClearAsync (options, operationContext, cancellationToken)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-371">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-371">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-372">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-372">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-373">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-373">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-374">Initiiert einen asynchronen Vorgang, um alle Nachrichten aus der Warteschlange zu löschen.</span><span class="sxs-lookup"><span data-stu-id="15c63-374">Initiates an asynchronous operation to clear all messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-375">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-375">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public virtual void Create (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Create(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Create(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Create : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Create : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.Create (options, operationContext)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-376">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-376">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-377">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-377">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-378">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-378">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-379">Erstellt die Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-379">Creates the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.CreateAsync " />
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15c63-380">Initiiert einen asynchronen Vorgang zum Erstellen einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-380">Initiates an asynchronous operation to create a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-381">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-381">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.CreateAsync cancellationToken" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15c63-382">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-382">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-383">Initiiert einen asynchronen Vorgang zum Erstellen einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-383">Initiates an asynchronous operation to create a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-384">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-384">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.CreateAsync (options, operationContext)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-385">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-385">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-386">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-386">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-387">Initiiert einen asynchronen Vorgang zum Erstellen einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-387">Initiates an asynchronous operation to create a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-388">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-388">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.CreateAsync (options, operationContext, cancellationToken)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-389">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-389">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-390">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-390">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-391">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-391">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-392">Initiiert einen asynchronen Vorgang zum Erstellen einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-392">Initiates an asynchronous operation to create a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-393">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-393">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool CreateIfNotExists (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CreateIfNotExists(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateIfNotExists(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.CreateIfNotExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudQueue.CreateIfNotExists (options, operationContext)" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-394">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-394">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-395">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-395">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-396">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-396">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-397">Erstellt die Warteschlange an, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-397">Creates the queue if it does not already exist.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="15c63-398"><c>"true"</c> Wenn die Warteschlange noch nicht vorhanden war und erstellt; andernfalls wurde <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="15c63-398"><c>true</c> if the queue did not already exist and was created; otherwise <c>false</c>.</span></span></returns>
        <remarks><span data-ttu-id="15c63-399">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="15c63-399">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateIfNotExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateIfNotExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.CreateIfNotExistsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15c63-400">Initiiert einen asynchronen Vorgang zum Erstellen der Warteschlange, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-400">Initiates an asynchronous operation to create the queue if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-401">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-401">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15c63-402">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="15c63-402">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateIfNotExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.CreateIfNotExistsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15c63-403">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-403">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-404">Initiiert einen asynchronen Vorgang zum Erstellen der Warteschlange, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-404">Initiates an asynchronous operation to create the queue if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-405">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-405">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15c63-406">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="15c63-406">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateIfNotExistsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.CreateIfNotExistsAsync (options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-407">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-407">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-408">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-408">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-409">Initiiert einen asynchronen Vorgang zum Erstellen der Warteschlange, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-409">Initiates an asynchronous operation to create the queue if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-410">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-410">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15c63-411">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="15c63-411">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateIfNotExistsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.CreateIfNotExistsAsync (options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-412">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-412">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-413">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-413">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-414">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-414">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-415">Initiiert einen asynchronen Vorgang zum Erstellen der Warteschlange, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-415">Initiates an asynchronous operation to create the queue if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-416">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-416">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15c63-417">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="15c63-417">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public virtual void Delete (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Delete(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Delete : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Delete : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.Delete (options, operationContext)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-418">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-418">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-419">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-419">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-420">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-420">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-421">Löscht die Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-421">Deletes the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteAsync " />
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15c63-422">Initiiert einen asynchronen Vorgang zum Löschen einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-422">Initiates an asynchronous operation to delete a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-423">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-423">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteAsync cancellationToken" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15c63-424">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-424">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-425">Initiiert einen asynchronen Vorgang zum Löschen einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-425">Initiates an asynchronous operation to delete a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-426">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-426">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteAsync (options, operationContext)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-427">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-427">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-428">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-428">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-429">Initiiert einen asynchronen Vorgang zum Löschen einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-429">Initiates an asynchronous operation to delete a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-430">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-430">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteAsync (options, operationContext, cancellationToken)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-431">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-431">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-432">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-432">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-433">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-433">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-434">Initiiert einen asynchronen Vorgang zum Löschen einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-434">Initiates an asynchronous operation to delete a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-435">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-435">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool DeleteIfExists (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool DeleteIfExists(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteIfExists(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.DeleteIfExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudQueue.DeleteIfExists (options, operationContext)" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-436">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-436">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-437">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-437">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-438">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-438">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-439">Löscht die Warteschlange an, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-439">Deletes the queue if it already exists.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="15c63-440"><c>"true"</c> Wenn die Warteschlange noch nicht vorhanden war und erstellt; andernfalls wurde <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="15c63-440"><c>true</c> if the queue did not already exist and was created; otherwise <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteIfExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteIfExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.DeleteIfExistsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15c63-441">Initiiert einen asynchronen Vorgang zum Löschen der Warteschlange, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-441">Initiates an asynchronous operation to delete the queue if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-442">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-442">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteIfExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.DeleteIfExistsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15c63-443">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-443">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-444">Initiiert einen asynchronen Vorgang zum Löschen der Warteschlange, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-444">Initiates an asynchronous operation to delete the queue if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-445">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-445">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteIfExistsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.DeleteIfExistsAsync (options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-446">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-446">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-447">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-447">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-448">Initiiert einen asynchronen Vorgang zum Löschen der Warteschlange, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-448">Initiates an asynchronous operation to delete the queue if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-449">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-449">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteIfExistsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.DeleteIfExistsAsync (options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-450">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-450">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-451">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-451">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-452">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-452">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-453">Initiiert einen asynchronen Vorgang zum Löschen der Warteschlange, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-453">Initiates an asynchronous operation to delete the queue if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-454">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-454">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessage">
      <MemberSignature Language="C#" Value="public virtual void DeleteMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.DeleteMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.DeleteMessage (message, options, operationContext)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-455">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-455">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-456">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-456">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-457">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-457">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-458">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-458">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-459">Löscht eine Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="15c63-459">Deletes a message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessage">
      <MemberSignature Language="C#" Value="public virtual void DeleteMessage (string messageId, string popReceipt, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteMessage(string messageId, string popReceipt, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessage(System.String,System.String,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessage : string * string * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.DeleteMessage : string * string * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.DeleteMessage (messageId, popReceipt, options, operationContext)" />
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
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="messageId"><span data-ttu-id="15c63-460">Eine Zeichenfolge, die Nachrichten-ID angibt</span><span class="sxs-lookup"><span data-stu-id="15c63-460">A string specifying the message ID.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="15c63-461">Eine Zeichenfolge, die den abrufbestätigungswert angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-461">A string specifying the pop receipt value.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-462">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-462">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-463">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-463">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-464">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-464">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-465">Löscht die angegebene Nachricht aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-465">Deletes the specified message from the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteMessageAsync (message As CloudQueueMessage) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteMessageAsync message" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-466">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-466">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-467">Initiiert einen asynchronen Vorgang zum Löschen einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="15c63-467">Initiates an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-468">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-468">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteMessageAsync (message, cancellationToken)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-469">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-469">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-470">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-470">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-471">Initiiert einen asynchronen Vorgang zum Löschen einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="15c63-471">Initiates an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-472">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-472">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteMessageAsync (string messageId, string popReceipt);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteMessageAsync(string messageId, string popReceipt) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessageAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteMessageAsync (messageId As String, popReceipt As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessageAsync : string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteMessageAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteMessageAsync (messageId, popReceipt)" />
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
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="messageId"><span data-ttu-id="15c63-473">Eine Zeichenfolge, die Nachrichten-ID angibt</span><span class="sxs-lookup"><span data-stu-id="15c63-473">A string specifying the message ID.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="15c63-474">Eine Zeichenfolge, die den abrufbestätigungswert angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-474">A string specifying the pop receipt value.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-475">Initiiert einen asynchronen Vorgang zum Löschen einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="15c63-475">Initiates an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-476">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-476">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteMessageAsync (message, options, operationContext)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-477">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-477">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-478">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-478">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-479">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-479">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-480">Initiiert einen asynchronen Vorgang zum Löschen einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="15c63-480">Initiates an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-481">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-481">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteMessageAsync (string messageId, string popReceipt, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteMessageAsync(string messageId, string popReceipt, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessageAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessageAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteMessageAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteMessageAsync (messageId, popReceipt, cancellationToken)" />
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
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="messageId"><span data-ttu-id="15c63-482">Eine Zeichenfolge, die Nachrichten-ID angibt</span><span class="sxs-lookup"><span data-stu-id="15c63-482">A string specifying the message ID.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="15c63-483">Eine Zeichenfolge, die den abrufbestätigungswert angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-483">A string specifying the pop receipt value.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-484">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-484">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-485">Initiiert einen asynchronen Vorgang zum Löschen einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="15c63-485">Initiates an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-486">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-486">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteMessageAsync (message, options, operationContext, cancellationToken)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-487">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-487">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-488">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-488">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-489">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-489">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-490">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-490">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-491">Initiiert einen asynchronen Vorgang zum Löschen einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="15c63-491">Initiates an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-492">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-492">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteMessageAsync (string messageId, string popReceipt, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteMessageAsync(string messageId, string popReceipt, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessageAsync(System.String,System.String,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessageAsync : string * string * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteMessageAsync : string * string * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteMessageAsync (messageId, popReceipt, options, operationContext)" />
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
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="messageId"><span data-ttu-id="15c63-493">Eine Zeichenfolge, die Nachrichten-ID angibt</span><span class="sxs-lookup"><span data-stu-id="15c63-493">A string specifying the message ID.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="15c63-494">Eine Zeichenfolge, die den abrufbestätigungswert angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-494">A string specifying the pop receipt value.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-495">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-495">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-496">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-496">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-497">Initiiert einen asynchronen Vorgang zum Löschen einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="15c63-497">Initiates an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-498">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-498">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteMessageAsync (string messageId, string popReceipt, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteMessageAsync(string messageId, string popReceipt, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessageAsync(System.String,System.String,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessageAsync : string * string * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteMessageAsync : string * string * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteMessageAsync (messageId, popReceipt, options, operationContext, cancellationToken)" />
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
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="messageId"><span data-ttu-id="15c63-499">Eine Zeichenfolge, die Nachrichten-ID angibt</span><span class="sxs-lookup"><span data-stu-id="15c63-499">A string specifying the message ID.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="15c63-500">Eine Zeichenfolge, die den abrufbestätigungswert angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-500">A string specifying the pop receipt value.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-501">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-501">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-502">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-502">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-503">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-503">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-504">Initiiert einen asynchronen Vorgang zum Löschen einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="15c63-504">Initiates an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-505">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-505">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncodeMessage">
      <MemberSignature Language="C#" Value="public bool EncodeMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EncodeMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EncodeMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property EncodeMessage As Boolean" />
      <MemberSignature Language="F#" Value="member this.EncodeMessage : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EncodeMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="15c63-506">Ruft ab oder legt einen Wert, der angibt, ob beim Hinzufügen oder Abrufen von Nachrichten base64-Codierung angewendet.</span><span class="sxs-lookup"><span data-stu-id="15c63-506">Gets or sets a value indicating whether to apply base64 encoding when adding or retrieving messages.</span></span>
            </summary>
        <value>
          <span data-ttu-id="15c63-507"><c>"true"</c> auf Nachrichten zu codieren; andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="15c63-507"><c>true</c> to encode messages; otherwise, <c>false</c>.</span></span> <span data-ttu-id="15c63-508">Der Standardwert lautet <c>true</c>.</span><span class="sxs-lookup"><span data-stu-id="15c63-508">The default value is <c>true</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndAddMessage">
      <MemberSignature Language="C#" Value="public virtual void EndAddMessage (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndAddMessage(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndAddMessage(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndAddMessage (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndAddMessage : IAsyncResult -&gt; unit&#xA;override this.EndAddMessage : IAsyncResult -&gt; unit" Usage="cloudQueue.EndAddMessage asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="15c63-509">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-509">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-510">Beendet einen asynchronen Vorgang zum Hinzufügen einer Nachricht an die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-510">Ends an asynchronous operation to add a message to the queue.</span></span>
            </summary>
        <remarks><span data-ttu-id="15c63-511">Die <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> übergebene Nachricht wird mit der abrufbestätigung, Nachrichten-ID und die Einfügung/Ablaufzeit aufgefüllt.</span><span class="sxs-lookup"><span data-stu-id="15c63-511">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> message passed in will be populated with the pop receipt, message ID, and the insertion/expiration time.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EndClear">
      <MemberSignature Language="C#" Value="public virtual void EndClear (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndClear(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndClear(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndClear (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndClear : IAsyncResult -&gt; unit&#xA;override this.EndClear : IAsyncResult -&gt; unit" Usage="cloudQueue.EndClear asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="15c63-512">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-512">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-513">Beendet einen asynchronen Vorgang, um alle Nachrichten aus der Warteschlange zu löschen.</span><span class="sxs-lookup"><span data-stu-id="15c63-513">Ends an asynchronous operation to clear all messages from the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreate">
      <MemberSignature Language="C#" Value="public virtual void EndCreate (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndCreate(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndCreate(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndCreate (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndCreate : IAsyncResult -&gt; unit&#xA;override this.EndCreate : IAsyncResult -&gt; unit" Usage="cloudQueue.EndCreate asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="15c63-514">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-514">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-515">Beendet einen asynchronen Vorgang zum Erstellen einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-515">Ends an asynchronous operation to create a queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool EndCreateIfNotExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndCreateIfNotExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndCreateIfNotExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndCreateIfNotExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndCreateIfNotExists : IAsyncResult -&gt; bool&#xA;override this.EndCreateIfNotExists : IAsyncResult -&gt; bool" Usage="cloudQueue.EndCreateIfNotExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="15c63-516">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-516">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-517">Gibt das Ergebnis eines asynchronen Vorgangs an die Warteschlange zu erstellen, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-517">Returns the result of an asynchronous operation to create the queue if it does not already exist.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="15c63-518"><c>"true"</c> Wenn die Warteschlange noch nicht vorhanden war und erstellt; andernfalls wurde, <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="15c63-518"><c>true</c> if the queue did not already exist and was created; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDelete">
      <MemberSignature Language="C#" Value="public virtual void EndDelete (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndDelete(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndDelete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndDelete (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndDelete : IAsyncResult -&gt; unit&#xA;override this.EndDelete : IAsyncResult -&gt; unit" Usage="cloudQueue.EndDelete asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="15c63-519">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-519">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-520">Beendet einen asynchronen Vorgang zum Löschen einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-520">Ends an asynchronous operation to delete a queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool EndDeleteIfExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndDeleteIfExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndDeleteIfExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDeleteIfExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndDeleteIfExists : IAsyncResult -&gt; bool&#xA;override this.EndDeleteIfExists : IAsyncResult -&gt; bool" Usage="cloudQueue.EndDeleteIfExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="15c63-521">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-521">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-522">Gibt das Ergebnis eines asynchronen Vorgangs zum Löschen der Warteschlange, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-522">Returns the result of an asynchronous operation to delete the queue if it already exists.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="15c63-523"><c>"true"</c> Wenn die Warteschlange noch nicht vorhanden war und erstellt; andernfalls wurde, <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="15c63-523"><c>true</c> if the queue did not already exist and was created; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteMessage">
      <MemberSignature Language="C#" Value="public virtual void EndDeleteMessage (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndDeleteMessage(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndDeleteMessage(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndDeleteMessage (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndDeleteMessage : IAsyncResult -&gt; unit&#xA;override this.EndDeleteMessage : IAsyncResult -&gt; unit" Usage="cloudQueue.EndDeleteMessage asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="15c63-524">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-524">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-525">Beendet einen asynchronen Vorgang zum Löschen einer Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="15c63-525">Ends an asynchronous operation to delete a message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExists">
      <MemberSignature Language="C#" Value="public virtual bool EndExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndExists : IAsyncResult -&gt; bool&#xA;override this.EndExists : IAsyncResult -&gt; bool" Usage="cloudQueue.EndExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="15c63-526">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-526">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-527">Gibt das asynchrone Ergebnis der Anforderung überprüft das Vorhandensein der Warteschlange zurück.</span><span class="sxs-lookup"><span data-stu-id="15c63-527">Returns the asynchronous result of the request to check the existence of the queue.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="15c63-528"><c>"true"</c> , wenn die Warteschlange vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-528"><c>true</c> if the queue exists.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual void EndFetchAttributes (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndFetchAttributes(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndFetchAttributes(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndFetchAttributes (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndFetchAttributes : IAsyncResult -&gt; unit&#xA;override this.EndFetchAttributes : IAsyncResult -&gt; unit" Usage="cloudQueue.EndFetchAttributes asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="15c63-529">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-529">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-530">Beendet einen asynchronen Vorgang zum Abrufen von Attributen für eine Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-530">Ends an asynchronous operation to fetch a queue's attributes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage EndGetMessage (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage EndGetMessage(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndGetMessage(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetMessage (asyncResult As IAsyncResult) As CloudQueueMessage" />
      <MemberSignature Language="F#" Value="abstract member EndGetMessage : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&#xA;override this.EndGetMessage : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="cloudQueue.EndGetMessage asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="15c63-531">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-531">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-532">Beendet einen asynchronen Vorgang zum Abrufen einer einzelnen Nachricht aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-532">Ends an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-533">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-533">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetMessages">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; EndGetMessages (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; EndGetMessages(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndGetMessages(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetMessages (asyncResult As IAsyncResult) As IEnumerable(Of CloudQueueMessage)" />
      <MemberSignature Language="F#" Value="abstract member EndGetMessages : IAsyncResult -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.EndGetMessages : IAsyncResult -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.EndGetMessages asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="15c63-534">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-534">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-535">Beendet einen asynchronen Vorgang zum Abrufen von Nachrichten aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-535">Ends an asynchronous operation to get messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-536">Eine aufzählbare Auflistung von Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="15c63-536">An enumerable collection of messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions EndGetPermissions (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions EndGetPermissions(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndGetPermissions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetPermissions (asyncResult As IAsyncResult) As QueuePermissions" />
      <MemberSignature Language="F#" Value="abstract member EndGetPermissions : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&#xA;override this.EndGetPermissions : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" Usage="cloudQueue.EndGetPermissions asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="15c63-537">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-537">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-538">Das asynchrone Ergebnis der Anforderung zum Abrufen der berechtigungseinstellungen für die Warteschlange zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-538">Returns the asynchronous result of the request to get the permissions settings for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-539">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-539">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndPeekMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage EndPeekMessage (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage EndPeekMessage(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndPeekMessage(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndPeekMessage (asyncResult As IAsyncResult) As CloudQueueMessage" />
      <MemberSignature Language="F#" Value="abstract member EndPeekMessage : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&#xA;override this.EndPeekMessage : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="cloudQueue.EndPeekMessage asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="15c63-540">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-540">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-541">Beendet einen asynchronen Vorgang zum Einsehen einer einzelnen Nachricht aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-541">Ends an asynchronous operation to peek a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-542">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-542">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndPeekMessages">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; EndPeekMessages (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; EndPeekMessages(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndPeekMessages(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndPeekMessages (asyncResult As IAsyncResult) As IEnumerable(Of CloudQueueMessage)" />
      <MemberSignature Language="F#" Value="abstract member EndPeekMessages : IAsyncResult -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.EndPeekMessages : IAsyncResult -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.EndPeekMessages asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="15c63-543">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-543">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-544">Beendet einen asynchronen Vorgang zum Einsehen von Nachrichten aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-544">Ends an asynchronous operation to peek messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-545">Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="15c63-545">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> objects.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetMetadata">
      <MemberSignature Language="C#" Value="public virtual void EndSetMetadata (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetMetadata(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndSetMetadata(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetMetadata (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetMetadata : IAsyncResult -&gt; unit&#xA;override this.EndSetMetadata : IAsyncResult -&gt; unit" Usage="cloudQueue.EndSetMetadata asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="15c63-546">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-546">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-547">Beendet einen asynchronen Vorgang zum Festlegen von benutzerdefinierten Metadaten für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-547">Ends an asynchronous operation to set user-defined metadata on the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetPermissions">
      <MemberSignature Language="C#" Value="public virtual void EndSetPermissions (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetPermissions(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndSetPermissions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetPermissions (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetPermissions : IAsyncResult -&gt; unit&#xA;override this.EndSetPermissions : IAsyncResult -&gt; unit" Usage="cloudQueue.EndSetPermissions asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="15c63-548">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-548">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-549">Gibt das Ergebnis eines asynchronen Vorgangs zum Festlegen von Berechtigungen für die Warteschlange zurück.</span><span class="sxs-lookup"><span data-stu-id="15c63-549">Returns the result of an asynchronous operation to set permissions for the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUpdateMessage">
      <MemberSignature Language="C#" Value="public virtual void EndUpdateMessage (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUpdateMessage(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndUpdateMessage(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUpdateMessage (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUpdateMessage : IAsyncResult -&gt; unit&#xA;override this.EndUpdateMessage : IAsyncResult -&gt; unit" Usage="cloudQueue.EndUpdateMessage asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="15c63-550">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="15c63-550">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-551">Beendet einen asynchronen Vorgang zum Hinzufügen einer Nachricht an die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-551">Ends an asynchronous operation to add a message to the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public virtual bool Exists (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Exists(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Exists(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Exists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.Exists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudQueue.Exists (options, operationContext)" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-552">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-552">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-553">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-553">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-554">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-554">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-555">Überprüft, ob die Warteschlange vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-555">Checks existence of the queue.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="15c63-556"><c>"true"</c> , wenn die Warteschlange vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15c63-556"><c>true</c> if the queue exists.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.ExistsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15c63-557">Initiiert einen asynchronen Vorgang, um das Vorhandensein der Warteschlange zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="15c63-557">Initiates an asynchronous operation to check the existence of the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-558">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-558">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.ExistsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15c63-559">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-559">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-560">Initiiert einen asynchronen Vorgang, um das Vorhandensein der Warteschlange zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="15c63-560">Initiates an asynchronous operation to check the existence of the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-561">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-561">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ExistsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.ExistsAsync (options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-562">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-562">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-563">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-563">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-564">Initiiert einen asynchronen Vorgang, um das Vorhandensein der Warteschlange zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="15c63-564">Initiates an asynchronous operation to check the existence of the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-565">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-565">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ExistsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.ExistsAsync (options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-566">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-566">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-567">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-567">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-568">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-568">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-569">Initiiert einen asynchronen Vorgang, um das Vorhandensein der Warteschlange zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="15c63-569">Initiates an asynchronous operation to check the existence of the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-570">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-570">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributes">
      <MemberSignature Language="C#" Value="public virtual void FetchAttributes (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void FetchAttributes(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.FetchAttributes(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributes : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.FetchAttributes : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.FetchAttributes (options, operationContext)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-571">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-571">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-572">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-572">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-573">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-573">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-574">Ruft die Attribute der Warteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="15c63-574">Fetches the queue's attributes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.FetchAttributesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function FetchAttributesAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.FetchAttributesAsync " />
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15c63-575">Initiiert einen asynchronen Vorgang zum Abrufen von Attributen für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-575">Initiates an asynchronous operation to fetch the queue's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-576">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-576">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.FetchAttributesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.FetchAttributesAsync cancellationToken" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15c63-577">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-577">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-578">Initiiert einen asynchronen Vorgang zum Abrufen von Attributen für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-578">Initiates an asynchronous operation to fetch the queue's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-579">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-579">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.FetchAttributesAsync (options, operationContext)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-580">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-580">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-581">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-581">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-582">Initiiert einen asynchronen Vorgang zum Abrufen von Attributen für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-582">Initiates an asynchronous operation to fetch the queue's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-583">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-583">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.FetchAttributesAsync (options, operationContext, cancellationToken)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-584">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-584">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-585">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-585">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-586">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-586">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-587">Initiiert einen asynchronen Vorgang zum Abrufen von Attributen für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-587">Initiates an asynchronous operation to fetch the queue's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-588">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-588">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage GetMessage (Nullable&lt;TimeSpan&gt; visibilityTimeout = null, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage GetMessage(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessage(System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetMessage : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&#xA;override this.GetMessage : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="cloudQueue.GetMessage (visibilityTimeout, options, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="visibilityTimeout"><span data-ttu-id="15c63-589">Ein <see cref="T:System.TimeSpan" /> das Timeoutintervall für die Sichtbarkeit angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-589">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-590">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-590">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-591">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-591">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-592">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-592">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-593">Ruft eine Meldung aus der Warteschlange, die mit den Standardoptionen für die Anforderung ab.</span><span class="sxs-lookup"><span data-stu-id="15c63-593">Gets a message from the queue using the default request options.</span></span> <span data-ttu-id="15c63-594">Dieser Vorgang wird die abgerufene Nachricht als nicht sichtbar, in der Warteschlange für das Standardtimeout für die Sichtbarkeit gekennzeichnet.</span><span class="sxs-lookup"><span data-stu-id="15c63-594">This operation marks the retrieved message as invisible in the queue for the default visibility timeout period.</span></span> 
            </summary>
        <returns><span data-ttu-id="15c63-595">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-595">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessageAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessageAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessageAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetMessageAsync () As Task(Of CloudQueueMessage)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.GetMessageAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.GetMessageAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15c63-596">Initiiert einen asynchronen Vorgang zum Abrufen einer einzelnen Nachricht aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-596">Initiates an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-597">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-597">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessageAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessageAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessageAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.GetMessageAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.GetMessageAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15c63-598">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-598">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-599">Initiiert einen asynchronen Vorgang zum Abrufen einer einzelnen Nachricht aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-599">Initiates an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-600">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-600">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessageAsync (Nullable&lt;TimeSpan&gt; visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessageAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessageAsync(System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageAsync : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.GetMessageAsync : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.GetMessageAsync (visibilityTimeout, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="visibilityTimeout"><span data-ttu-id="15c63-601">Ein <see cref="T:System.TimeSpan" /> das Timeoutintervall für die Sichtbarkeit angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-601">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-602">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-602">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-603">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-603">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-604">Initiiert einen asynchronen Vorgang, um eine einzelne Nachricht aus der Warteschlange abzurufen, und gibt an, wie lange die Nachricht reserviert werden soll, bevor es sichtbar und daher für die Löschung verfügbar wird.</span><span class="sxs-lookup"><span data-stu-id="15c63-604">Initiates an asynchronous operation to get a single message from the queue, and specifies how long the message should be reserved before it becomes visible, and therefore available for deletion.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-605">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-605">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessageAsync (Nullable&lt;TimeSpan&gt; visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessageAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessageAsync(System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageAsync : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.GetMessageAsync : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.GetMessageAsync (visibilityTimeout, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="visibilityTimeout"><span data-ttu-id="15c63-606">Ein <see cref="T:System.TimeSpan" /> das Timeoutintervall für die Sichtbarkeit angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-606">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-607">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-607">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-608">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-608">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-609">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-609">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-610">Initiiert einen asynchronen Vorgang, um eine einzelne Nachricht aus der Warteschlange abzurufen, und gibt an, wie lange die Nachricht reserviert werden soll, bevor es sichtbar und daher für die Löschung verfügbar wird.</span><span class="sxs-lookup"><span data-stu-id="15c63-610">Initiates an asynchronous operation to get a single message from the queue, and specifies how long the message should be reserved before it becomes visible, and therefore available for deletion.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-611">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-611">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessages">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessages (int messageCount, Nullable&lt;TimeSpan&gt; visibilityTimeout = null, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessages(int32 messageCount, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessages(System.Int32,System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetMessages : int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.GetMessages : int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.GetMessages (messageCount, visibilityTimeout, options, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="15c63-612">Die Anzahl der abzurufenden Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="15c63-612">The number of messages to retrieve.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="15c63-613">Ein <see cref="T:System.TimeSpan" /> das Timeoutintervall für die Sichtbarkeit angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-613">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-614">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-614">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-615">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-615">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-616">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-616">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-617">Ruft die angegebene Anzahl von Nachrichten aus der Warteschlange, die mit den angegebenen Optionen und des vorgangskontexts ab.</span><span class="sxs-lookup"><span data-stu-id="15c63-617">Gets the specified number of messages from the queue using the specified request options and operation context.</span></span> <span data-ttu-id="15c63-618">Dieser Vorgang kennzeichnet die abgerufenen Nachrichten als nicht sichtbar, in der Warteschlange für das Standardtimeout für die Sichtbarkeit.</span><span class="sxs-lookup"><span data-stu-id="15c63-618">This operation marks the retrieved messages as invisible in the queue for the default visibility timeout period.</span></span> 
            </summary>
        <returns><span data-ttu-id="15c63-619">Eine aufzählbare Auflistung von Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="15c63-619">An enumerable collection of messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; GetMessagesAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; GetMessagesAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessagesAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetMessagesAsync (messageCount As Integer) As Task(Of IEnumerable(Of CloudQueueMessage))" />
      <MemberSignature Language="F#" Value="abstract member GetMessagesAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;&#xA;override this.GetMessagesAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;" Usage="cloudQueue.GetMessagesAsync messageCount" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="15c63-620">Die Anzahl der abzurufenden Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="15c63-620">The number of messages to retrieve.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-621">Initiiert einen asynchronen Vorgang zum Abrufen von Nachrichten aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-621">Initiates an asynchronous operation to get messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-622">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt, das eine aufzählbare Auflistung von Typ <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-622">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; GetMessagesAsync (int messageCount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; GetMessagesAsync(int32 messageCount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessagesAsync(System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetMessagesAsync : int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;&#xA;override this.GetMessagesAsync : int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;" Usage="cloudQueue.GetMessagesAsync (messageCount, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="15c63-623">Die Anzahl der abzurufenden Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="15c63-623">The number of messages to retrieve.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-624">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-624">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-625">Initiiert einen asynchronen Vorgang zum Abrufen von Nachrichten aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-625">Initiates an asynchronous operation to get messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-626">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt, das eine aufzählbare Auflistung von Typ <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-626">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; GetMessagesAsync (int messageCount, Nullable&lt;TimeSpan&gt; visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; GetMessagesAsync(int32 messageCount, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessagesAsync(System.Int32,System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetMessagesAsync : int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;&#xA;override this.GetMessagesAsync : int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;" Usage="cloudQueue.GetMessagesAsync (messageCount, visibilityTimeout, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="15c63-627">Die Anzahl der abzurufenden Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="15c63-627">The number of messages to retrieve.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="15c63-628">Ein <see cref="T:System.TimeSpan" /> das Timeoutintervall für die Sichtbarkeit angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-628">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-629">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-629">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-630">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-630">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-631">Initiiert einen asynchronen Vorgang zum Abrufen der angegebenen Anzahl von Nachrichten aus der Warteschlange, die unter Verwendung des angegebenen Anforderungsoptionen und Vorgangskontext.</span><span class="sxs-lookup"><span data-stu-id="15c63-631">Initiates an asynchronous operation to get the specified number of messages from the queue using the specified request options and operation context.</span></span> <span data-ttu-id="15c63-632">Dieser Vorgang kennzeichnet die abgerufenen Nachrichten als nicht sichtbar, in der Warteschlange für das Standardtimeout für die Sichtbarkeit.</span><span class="sxs-lookup"><span data-stu-id="15c63-632">This operation marks the retrieved messages as invisible in the queue for the default visibility timeout period.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-633">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt, das eine aufzählbare Auflistung von Typ <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-633">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; GetMessagesAsync (int messageCount, Nullable&lt;TimeSpan&gt; visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; GetMessagesAsync(int32 messageCount, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessagesAsync(System.Int32,System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetMessagesAsync : int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;&#xA;override this.GetMessagesAsync : int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;" Usage="cloudQueue.GetMessagesAsync (messageCount, visibilityTimeout, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="15c63-634">Die Anzahl der abzurufenden Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="15c63-634">The number of messages to retrieve.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="15c63-635">Ein <see cref="T:System.TimeSpan" /> das Timeoutintervall für die Sichtbarkeit angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-635">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-636">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-636">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-637">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-637">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-638">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-638">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-639">Initiiert einen asynchronen Vorgang zum Abrufen der angegebenen Anzahl von Nachrichten aus der Warteschlange, die unter Verwendung des angegebenen Anforderungsoptionen und Vorgangskontext.</span><span class="sxs-lookup"><span data-stu-id="15c63-639">Initiates an asynchronous operation to get the specified number of messages from the queue using the specified request options and operation context.</span></span> <span data-ttu-id="15c63-640">Dieser Vorgang kennzeichnet die abgerufenen Nachrichten als nicht sichtbar, in der Warteschlange für das Standardtimeout für die Sichtbarkeit.</span><span class="sxs-lookup"><span data-stu-id="15c63-640">This operation marks the retrieved messages as invisible in the queue for the default visibility timeout period.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-641">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt, das eine aufzählbare Auflistung von Typ <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-641">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions GetPermissions (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions GetPermissions(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetPermissions(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissions : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&#xA;override this.GetPermissions : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" Usage="cloudQueue.GetPermissions (options, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-642">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-642">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-643">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-643">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-644">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-644">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-645">Ruft die berechtigungseinstellungen für die Warteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="15c63-645">Gets the permissions settings for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-646">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-646">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt; GetPermissionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt; GetPermissionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetPermissionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPermissionsAsync () As Task(Of QueuePermissions)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;&#xA;override this.GetPermissionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;" Usage="cloudQueue.GetPermissionsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15c63-647">Initiiert einen asynchronen Vorgang zum Abrufen der berechtigungseinstellungen für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-647">Initiates an asynchronous operation to get the permissions settings for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-648">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-648">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt; GetPermissionsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt; GetPermissionsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetPermissionsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;&#xA;override this.GetPermissionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;" Usage="cloudQueue.GetPermissionsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15c63-649">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-649">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-650">Initiiert einen asynchronen Vorgang zum Abrufen der berechtigungseinstellungen für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-650">Initiates an asynchronous operation to get the permissions settings for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-651">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-651">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt; GetPermissionsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt; GetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetPermissionsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;&#xA;override this.GetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;" Usage="cloudQueue.GetPermissionsAsync (options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-652">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-652">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-653">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-653">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-654">Initiiert einen asynchronen Vorgang zum Abrufen der berechtigungseinstellungen für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-654">Initiates an asynchronous operation to get the permissions settings for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-655">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-655">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt; GetPermissionsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt; GetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetPermissionsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;&#xA;override this.GetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;" Usage="cloudQueue.GetPermissionsAsync (options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-656">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-656">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-657">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-657">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-658">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-658">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-659">Initiiert einen asynchronen Vorgang zum Abrufen der berechtigungseinstellungen für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-659">Initiates an asynchronous operation to get the permissions settings for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-660">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-660">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy policy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy policy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessQueuePolicy) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy -&gt; string" Usage="cloudQueue.GetSharedAccessSignature policy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="15c63-661">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-661">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-662">Gibt eine SAS für die Warteschlange zurück.</span><span class="sxs-lookup"><span data-stu-id="15c63-662">Returns a shared access signature for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-663">Eine SAS als URI-Abfragezeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="15c63-663">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="15c63-664">Die zurückgegebene Abfragezeichenfolge enthält das vorangestellte Fragezeichen.</span><span class="sxs-lookup"><span data-stu-id="15c63-664">The query string returned includes the leading question mark.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy policy, string accessPolicyIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy policy, string accessPolicyIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessQueuePolicy, accessPolicyIdentifier As String) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy * string -&gt; string" Usage="cloudQueue.GetSharedAccessSignature (policy, accessPolicyIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" />
        <Parameter Name="accessPolicyIdentifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="15c63-665">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-665">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <param name="accessPolicyIdentifier"><span data-ttu-id="15c63-666">Eine Zeichenfolge, die eine gespeicherte Zugriffsrichtlinie identifiziert.</span><span class="sxs-lookup"><span data-stu-id="15c63-666">A string identifying a stored access policy.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-667">Gibt eine SAS für die Warteschlange zurück.</span><span class="sxs-lookup"><span data-stu-id="15c63-667">Returns a shared access signature for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-668">Eine SAS als URI-Abfragezeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="15c63-668">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="15c63-669">Die zurückgegebene Abfragezeichenfolge enthält das vorangestellte Fragezeichen.</span><span class="sxs-lookup"><span data-stu-id="15c63-669">The query string returned includes the leading question mark.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy policy, string accessPolicyIdentifier, Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; protocols, Microsoft.WindowsAzure.Storage.IPAddressOrRange ipAddressOrRange);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy policy, string accessPolicyIdentifier, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; protocols, class Microsoft.WindowsAzure.Storage.IPAddressOrRange ipAddressOrRange) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy,System.String,System.Nullable{Microsoft.WindowsAzure.Storage.SharedAccessProtocol},Microsoft.WindowsAzure.Storage.IPAddressOrRange)" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy * string * Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; * Microsoft.WindowsAzure.Storage.IPAddressOrRange -&gt; string" Usage="cloudQueue.GetSharedAccessSignature (policy, accessPolicyIdentifier, protocols, ipAddressOrRange)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" />
        <Parameter Name="accessPolicyIdentifier" Type="System.String" />
        <Parameter Name="protocols" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt;" />
        <Parameter Name="ipAddressOrRange" Type="Microsoft.WindowsAzure.Storage.IPAddressOrRange" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="15c63-670">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-670">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <param name="accessPolicyIdentifier"><span data-ttu-id="15c63-671">Eine Zeichenfolge, die eine gespeicherte Zugriffsrichtlinie identifiziert.</span><span class="sxs-lookup"><span data-stu-id="15c63-671">A string identifying a stored access policy.</span></span></param>
        <param name="protocols"><span data-ttu-id="15c63-672">Die zulässige Protokolle (nur Https oder http und Https).</span><span class="sxs-lookup"><span data-stu-id="15c63-672">The allowed protocols (https only, or http and https).</span></span> <span data-ttu-id="15c63-673">NULL, wenn Sie nicht Protokoll beschränken möchten.</span><span class="sxs-lookup"><span data-stu-id="15c63-673">Null if you don't want to restrict protocol.</span></span></param>
        <param name="ipAddressOrRange"><span data-ttu-id="15c63-674">Die zulässigen IP-Adresse oder IP-Adressbereich.</span><span class="sxs-lookup"><span data-stu-id="15c63-674">The allowed IP address or IP address range.</span></span> <span data-ttu-id="15c63-675">NULL, wenn Sie einschränken möchten, nicht basierend auf IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="15c63-675">Null if you don't want to restrict based on IP address.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-676">Gibt eine SAS für die Warteschlange zurück.</span><span class="sxs-lookup"><span data-stu-id="15c63-676">Returns a shared access signature for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-677">Eine SAS als URI-Abfragezeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="15c63-677">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="15c63-678">Die zurückgegebene Abfragezeichenfolge enthält das vorangestellte Fragezeichen.</span><span class="sxs-lookup"><span data-stu-id="15c63-678">The query string returned includes the leading question mark.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Metadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metadata As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="15c63-679">Ruft die Metadaten der Warteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="15c63-679">Gets the queue's metadata.</span></span>
            </summary>
        <value><span data-ttu-id="15c63-680">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt, das die Metadaten der Warteschlange enthält.</span><span class="sxs-lookup"><span data-stu-id="15c63-680">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object containing the queue's metadata.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="15c63-681">Ruft den Namen der Warteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="15c63-681">Gets the name of the queue.</span></span>
            </summary>
        <value><span data-ttu-id="15c63-682">Eine Zeichenfolge, die mit dem Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15c63-682">A string containing the name of the queue.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage PeekMessage (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage PeekMessage(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessage(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessage : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&#xA;override this.PeekMessage : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="cloudQueue.PeekMessage (options, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-683">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-683">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-684">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-684">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-685">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-685">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-686">Sieht eine einzelne Nachricht aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-686">Peeks a single message from the queue.</span></span> <span data-ttu-id="15c63-687">Eine Peek-Anforderung Ruft eine Nachricht aus der Warteschlange, ohne die Sichtbarkeit ändern zu müssen.</span><span class="sxs-lookup"><span data-stu-id="15c63-687">A peek request retrieves a message from the queue without changing its visibility.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-688">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-688">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessageAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessageAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessageAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function PeekMessageAsync () As Task(Of CloudQueueMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessageAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.PeekMessageAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.PeekMessageAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15c63-689">Initiiert einen asynchronen Vorgang zum Abrufen einer einzelnen Nachricht aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-689">Initiates an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-690">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-690">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessageAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessageAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessageAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessageAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.PeekMessageAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.PeekMessageAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15c63-691">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-691">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-692">Initiiert einen asynchronen Vorgang zum Abrufen einer einzelnen Nachricht aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-692">Initiates an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-693">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-693">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessageAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessageAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessageAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.PeekMessageAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.PeekMessageAsync (options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-694">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-694">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-695">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-695">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-696">Initiiert einen asynchronen Vorgang zum Abrufen einer einzelnen Nachricht aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-696">Initiates an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-697">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-697">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessageAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessageAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessageAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.PeekMessageAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.PeekMessageAsync (options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-698">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-698">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-699">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-699">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-700">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-700">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-701">Initiiert einen asynchronen Vorgang zum Abrufen einer einzelnen Nachricht aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-701">Initiates an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-702">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-702">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessages">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessages (int messageCount, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessages(int32 messageCount, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessages(System.Int32,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessages : int * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.PeekMessages : int * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.PeekMessages (messageCount, options, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="15c63-703">Die Anzahl der Nachrichten einsehen.</span><span class="sxs-lookup"><span data-stu-id="15c63-703">The number of messages to peek.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-704">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-704">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-705">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-705">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-706">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-706">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-707">Sieht eine Nachricht aus der Warteschlange, die mithilfe des angegebenen Anforderungskontexts Optionen und den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="15c63-707">Peeks a message from the queue, using the specified request options and operation context.</span></span> <span data-ttu-id="15c63-708">Eine Peek-Anforderung Ruft eine Nachricht aus der Warteschlange, ohne die Sichtbarkeit ändern zu müssen.</span><span class="sxs-lookup"><span data-stu-id="15c63-708">A peek request retrieves a message from the queue without changing its visibility.</span></span> 
            </summary>
        <returns><span data-ttu-id="15c63-709">Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="15c63-709">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> objects.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; PeekMessagesAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; PeekMessagesAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessagesAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function PeekMessagesAsync (messageCount As Integer) As Task(Of IEnumerable(Of CloudQueueMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekMessagesAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;&#xA;override this.PeekMessagesAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;" Usage="cloudQueue.PeekMessagesAsync messageCount" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="15c63-710">Die Anzahl der Nachrichten einsehen.</span><span class="sxs-lookup"><span data-stu-id="15c63-710">The number of messages to peek.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-711">Initiiert einen asynchronen Vorgang zum Einsehen von Nachrichten aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-711">Initiates an asynchronous operation to peek messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-712">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt, das eine aufzählbare Auflistung von Typ <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-712">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; PeekMessagesAsync (int messageCount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; PeekMessagesAsync(int32 messageCount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessagesAsync(System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessagesAsync : int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;&#xA;override this.PeekMessagesAsync : int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;" Usage="cloudQueue.PeekMessagesAsync (messageCount, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="15c63-713">Die Anzahl der Nachrichten einsehen.</span><span class="sxs-lookup"><span data-stu-id="15c63-713">The number of messages to peek.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-714">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-714">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-715">Initiiert einen asynchronen Vorgang zum Einsehen von Nachrichten aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-715">Initiates an asynchronous operation to peek messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-716">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt, das eine aufzählbare Auflistung von Typ <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-716">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; PeekMessagesAsync (int messageCount, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; PeekMessagesAsync(int32 messageCount, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessagesAsync(System.Int32,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessagesAsync : int * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;&#xA;override this.PeekMessagesAsync : int * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;" Usage="cloudQueue.PeekMessagesAsync (messageCount, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="15c63-717">Die Anzahl der Nachrichten einsehen.</span><span class="sxs-lookup"><span data-stu-id="15c63-717">The number of messages to peek.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-718">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-718">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-719">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-719">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-720">Initiiert einen asynchronen Vorgang zum Einsehen von Nachrichten aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-720">Initiates an asynchronous operation to peek messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-721">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt, das eine aufzählbare Auflistung von Typ <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-721">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; PeekMessagesAsync (int messageCount, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; PeekMessagesAsync(int32 messageCount, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessagesAsync(System.Int32,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessagesAsync : int * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;&#xA;override this.PeekMessagesAsync : int * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;" Usage="cloudQueue.PeekMessagesAsync (messageCount, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="15c63-722">Die Anzahl der Nachrichten einsehen.</span><span class="sxs-lookup"><span data-stu-id="15c63-722">The number of messages to peek.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-723">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-723">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-724">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-724">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-725">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-725">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-726">Initiiert einen asynchronen Vorgang zum Einsehen von Nachrichten aus der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-726">Initiates an asynchronous operation to peek messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-727">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt, das eine aufzählbare Auflistung von Typ <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-727">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient ServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient ServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceClient As CloudQueueClient" />
      <MemberSignature Language="F#" Value="member this.ServiceClient : Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ServiceClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="15c63-728">Ruft die <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" /> Objekt, das den Warteschlangendienst darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-728">Gets the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" /> object that represents the Queue service.</span></span>
            </summary>
        <value><span data-ttu-id="15c63-729">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-729">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public virtual void SetMetadata (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetMetadata(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetMetadata(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadata : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetMetadata : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.SetMetadata (options, operationContext)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-730">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-730">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-731">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-731">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-732">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-732">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-733">Legt die Warteschlange benutzerdefinierte Metadaten.</span><span class="sxs-lookup"><span data-stu-id="15c63-733">Sets the queue's user-defined metadata.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetMetadataAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetMetadataAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.SetMetadataAsync " />
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15c63-734">Initiiert einen asynchronen Vorgang zum Festlegen von benutzerdefinierten Metadaten für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-734">Initiates an asynchronous operation to set user-defined metadata on the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-735">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-735">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetMetadataAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.SetMetadataAsync cancellationToken" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15c63-736">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-736">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-737">Initiiert einen asynchronen Vorgang zum Festlegen von benutzerdefinierten Metadaten für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-737">Initiates an asynchronous operation to set user-defined metadata on the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-738">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-738">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetMetadataAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.SetMetadataAsync (options, operationContext)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-739">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-739">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-740">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-740">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-741">Initiiert einen asynchronen Vorgang zum Festlegen von benutzerdefinierten Metadaten für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-741">Initiates an asynchronous operation to set user-defined metadata on the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-742">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-742">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetMetadataAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.SetMetadataAsync (options, operationContext, cancellationToken)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="15c63-743">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-743">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-744">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-744">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-745">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-745">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-746">Initiiert einen asynchronen Vorgang zum Festlegen von benutzerdefinierten Metadaten für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-746">Initiates an asynchronous operation to set user-defined metadata on the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-747">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-747">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissions">
      <MemberSignature Language="C#" Value="public virtual void SetPermissions (Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetPermissions(class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetPermissions(Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissions : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetPermissions : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.SetPermissions (permissions, options, operationContext)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="15c63-748">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-748">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-749">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-749">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-750">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-750">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-751">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-751">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-752">Legt Berechtigungen für die Warteschlange fest.</span><span class="sxs-lookup"><span data-stu-id="15c63-752">Sets permissions for the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetPermissionsAsync (permissions As QueuePermissions) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.SetPermissionsAsync permissions" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="15c63-753">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-753">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-754">Initiiert einen asynchronen Vorgang zum Festlegen von Berechtigungen für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-754">Initiates an asynchronous operation to set permissions for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-755">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-755">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.SetPermissionsAsync (permissions, cancellationToken)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="15c63-756">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-756">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-757">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-757">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-758">Initiiert einen asynchronen Vorgang zum Festlegen von Berechtigungen für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-758">Initiates an asynchronous operation to set permissions for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-759">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-759">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.SetPermissionsAsync (permissions, options, operationContext)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="15c63-760">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-760">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-761">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-761">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-762">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-762">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-763">Initiiert einen asynchronen Vorgang zum Festlegen von Berechtigungen für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-763">Initiates an asynchronous operation to set permissions for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-764">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-764">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.SetPermissionsAsync (permissions, options, operationContext, cancellationToken)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="15c63-765">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-765">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-766">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-766">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-767">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-767">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-768">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-768">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-769">Initiiert einen asynchronen Vorgang zum Festlegen von Berechtigungen für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="15c63-769">Initiates an asynchronous operation to set permissions for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-770">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-770">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueue.StorageUri" />
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
            <span data-ttu-id="15c63-771">Ruft den Warteschlangen-URIs für die primären und sekundären Speicherorte ab.</span><span class="sxs-lookup"><span data-stu-id="15c63-771">Gets the queue URIs for both the primary and secondary locations.</span></span>
            </summary>
        <value><span data-ttu-id="15c63-772">Ein Objekt des Typs <see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.StorageUri" /> , die dem Warteschlangen URIs für die primären und sekundären Speicherorte enthält.</span><span class="sxs-lookup"><span data-stu-id="15c63-772">An object of type <see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.StorageUri" /> containing the queue's URIs for both the primary and secondary locations.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessage">
      <MemberSignature Language="C#" Value="public virtual void UpdateMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, TimeSpan visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UpdateMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.TimeSpan visibilityTimeout, valuetype Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.UpdateMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.TimeSpan,Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UpdateMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UpdateMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.UpdateMessage (message, visibilityTimeout, updateFields, options, operationContext)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="visibilityTimeout" Type="System.TimeSpan" />
        <Parameter Name="updateFields" Type="Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-773">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-773">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="15c63-774">Ein <see cref="T:System.TimeSpan" /> das Timeoutintervall für die Sichtbarkeit angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-774">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="updateFields"><span data-ttu-id="15c63-775">Der Flags <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> Werte, die angibt, welche Teile der Nachricht aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-775">Flags of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> values that specifies which parts of the message are to be updated.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-776">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-776">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="15c63-777">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="15c63-777">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-778">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-778">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-779">Aktualisiert das sichtbarkeitstimeout und optional den Inhalt einer Nachricht.</span><span class="sxs-lookup"><span data-stu-id="15c63-779">Updates the visibility timeout and optionally the content of a message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UpdateMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, TimeSpan visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.TimeSpan visibilityTimeout, valuetype Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.UpdateMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.TimeSpan,Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UpdateMessageAsync (message As CloudQueueMessage, visibilityTimeout As TimeSpan, updateFields As MessageUpdateFields) As Task" />
      <MemberSignature Language="F#" Value="abstract member UpdateMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields -&gt; System.Threading.Tasks.Task&#xA;override this.UpdateMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.UpdateMessageAsync (message, visibilityTimeout, updateFields)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="visibilityTimeout" Type="System.TimeSpan" />
        <Parameter Name="updateFields" Type="Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-780">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-780">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="15c63-781">Ein <see cref="T:System.TimeSpan" /> das Timeoutintervall für die Sichtbarkeit angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-781">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="updateFields"><span data-ttu-id="15c63-782">Eine Reihe von <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> Werte, die angeben, welche Teile der Nachricht sind, aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-782">A set of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> values that specify which parts of the message are to be updated.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-783">Initiiert einen asynchronen Vorgang, um das sichtbarkeitstimeout und optional den Inhalt einer Nachricht zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="15c63-783">Initiates an asynchronous operation to update the visibility timeout and optionally the content of a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-784">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-784">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UpdateMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, TimeSpan visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.TimeSpan visibilityTimeout, valuetype Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.UpdateMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.TimeSpan,Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UpdateMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.UpdateMessageAsync (message, visibilityTimeout, updateFields, cancellationToken)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="visibilityTimeout" Type="System.TimeSpan" />
        <Parameter Name="updateFields" Type="Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-785">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-785">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="15c63-786">Ein <see cref="T:System.TimeSpan" /> das Timeoutintervall für die Sichtbarkeit angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-786">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="updateFields"><span data-ttu-id="15c63-787">Eine Reihe von <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> Werte, die angeben, welche Teile der Nachricht sind, aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-787">A set of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> values that specify which parts of the message are to be updated.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-788">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-788">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-789">Initiiert einen asynchronen Vorgang, um das sichtbarkeitstimeout und optional den Inhalt einer Nachricht zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="15c63-789">Initiates an asynchronous operation to update the visibility timeout and optionally the content of a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-790">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-790">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UpdateMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, TimeSpan visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.TimeSpan visibilityTimeout, valuetype Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.UpdateMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.TimeSpan,Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UpdateMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UpdateMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.UpdateMessageAsync (message, visibilityTimeout, updateFields, options, operationContext)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="visibilityTimeout" Type="System.TimeSpan" />
        <Parameter Name="updateFields" Type="Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-791">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-791">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="15c63-792">Ein <see cref="T:System.TimeSpan" /> das Timeoutintervall für die Sichtbarkeit angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-792">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="updateFields"><span data-ttu-id="15c63-793">Eine Reihe von <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> Werte, die angeben, welche Teile der Nachricht sind, aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-793">A set of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> values that specify which parts of the message are to be updated.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-794">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-794">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-795">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-795">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-796">Initiiert einen asynchronen Vorgang, um das sichtbarkeitstimeout und optional den Inhalt einer Nachricht zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="15c63-796">Initiates an asynchronous operation to update the visibility timeout and optionally the content of a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-797">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-797">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UpdateMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, TimeSpan visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.TimeSpan visibilityTimeout, valuetype Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.UpdateMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.TimeSpan,Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UpdateMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.UpdateMessageAsync (message, visibilityTimeout, updateFields, options, operationContext, cancellationToken)" />
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
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="visibilityTimeout" Type="System.TimeSpan" />
        <Parameter Name="updateFields" Type="Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="15c63-798">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="15c63-798">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="15c63-799">Ein <see cref="T:System.TimeSpan" /> das Timeoutintervall für die Sichtbarkeit angeben.</span><span class="sxs-lookup"><span data-stu-id="15c63-799">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="updateFields"><span data-ttu-id="15c63-800">Eine Reihe von <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> Werte, die angeben, welche Teile der Nachricht sind, aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="15c63-800">A set of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> values that specify which parts of the message are to be updated.</span></span></param>
        <param name="options"><span data-ttu-id="15c63-801">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-801">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15c63-802">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-802">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15c63-803">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="15c63-803">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15c63-804">Initiiert einen asynchronen Vorgang, um das sichtbarkeitstimeout und optional den Inhalt einer Nachricht zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="15c63-804">Initiates an asynchronous operation to update the visibility timeout and optionally the content of a message.</span></span>
            </summary>
        <returns><span data-ttu-id="15c63-805">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="15c63-805">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Uri" />
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
            <span data-ttu-id="15c63-806">Ruft den Warteschlangen-URI für den primären Speicherort ab.</span><span class="sxs-lookup"><span data-stu-id="15c63-806">Gets the queue URI for the primary location.</span></span>
            </summary>
        <value><span data-ttu-id="15c63-807">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange am primären Speicherort angibt.</span><span class="sxs-lookup"><span data-stu-id="15c63-807">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue at the primary location.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>