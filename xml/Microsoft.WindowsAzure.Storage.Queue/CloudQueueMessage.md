<Type Name="CloudQueueMessage" FullName="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage">
  <TypeSignature Language="C#" Value="public sealed class CloudQueueMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CloudQueueMessage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CloudQueueMessage" />
  <TypeSignature Language="F#" Value="type CloudQueueMessage = class" />
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
            <span data-ttu-id="3350f-101">Stellt eine Nachricht im Microsoft Azure-Warteschlangendienst dar.</span><span class="sxs-lookup"><span data-stu-id="3350f-101">Represents a message in the Microsoft Azure Queue service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueueMessage (byte[] content);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (content As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage : byte[] -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage content" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="content" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="content"><span data-ttu-id="3350f-102">Der Inhalt der Nachricht als Bytearray.</span><span class="sxs-lookup"><span data-stu-id="3350f-102">The content of the message as a byte array.</span></span></param>
        <summary>
            <span data-ttu-id="3350f-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> Klasse mit dem angegebenen Bytearray.</span><span class="sxs-lookup"><span data-stu-id="3350f-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> class with the given byte array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueueMessage (string content);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (content As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage : string -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage content" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="content"><span data-ttu-id="3350f-104">Der Inhalt der Nachricht als Zeichenfolge bestehend aus Text.</span><span class="sxs-lookup"><span data-stu-id="3350f-104">The content of the message as a string of text.</span></span></param>
        <summary>
            <span data-ttu-id="3350f-105">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> -Klasse mit der angegebenen Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="3350f-105">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> class with the given string.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueueMessage (string messageId, string popReceipt);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string messageId, string popReceipt) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (messageId As String, popReceipt As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage : string * string -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage (messageId, popReceipt)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="messageId"><span data-ttu-id="3350f-106">Eine Zeichenfolge, die Nachrichten-ID angibt</span><span class="sxs-lookup"><span data-stu-id="3350f-106">A string specifying the message ID.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="3350f-107">Eine Zeichenfolge, die das abrufbestätigungs-Token enthält.</span><span class="sxs-lookup"><span data-stu-id="3350f-107">A string containing the pop receipt token.</span></span></param>
        <summary>
            <span data-ttu-id="3350f-108">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> Klasse mit der vorgegebenen Nachrichten-ID und der abrufbestätigung.</span><span class="sxs-lookup"><span data-stu-id="3350f-108">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> class with the given message ID and pop receipt.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AsBytes">
      <MemberSignature Language="C#" Value="public byte[] AsBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] AsBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.AsBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AsBytes As Byte()" />
      <MemberSignature Language="F#" Value="member this.AsBytes : byte[]" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.AsBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3350f-109">Ruft den Inhalt der Nachricht als Bytearray ab.</span><span class="sxs-lookup"><span data-stu-id="3350f-109">Gets the content of the message as a byte array.</span></span>
            </summary>
        <value><span data-ttu-id="3350f-110">Der Inhalt der Nachricht als Bytearray.</span><span class="sxs-lookup"><span data-stu-id="3350f-110">The content of the message as a byte array.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AsString">
      <MemberSignature Language="C#" Value="public string AsString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AsString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.AsString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AsString As String" />
      <MemberSignature Language="F#" Value="member this.AsString : string" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.AsString" />
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
            <span data-ttu-id="3350f-111">Ruft den Inhalt der Nachricht als Zeichenfolge ab.</span><span class="sxs-lookup"><span data-stu-id="3350f-111">Gets the content of the message, as a string.</span></span>
            </summary>
        <value><span data-ttu-id="3350f-112">Eine Zeichenfolge, die den Nachrichteninhalt enthält.</span><span class="sxs-lookup"><span data-stu-id="3350f-112">A string containing the message content.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DequeueCount">
      <MemberSignature Language="C#" Value="public int DequeueCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DequeueCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.DequeueCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DequeueCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DequeueCount : int" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.DequeueCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3350f-113">Ruft die Anzahl der Häufigkeit, mit die diese Nachricht aus der Warteschlange entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="3350f-113">Gets the number of times this message has been dequeued.</span></span>
            </summary>
        <value><span data-ttu-id="3350f-114">Gibt an, wie oft diese Nachricht aus der Warteschlange entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="3350f-114">The number of times this message has been dequeued.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3350f-115">Ruft die Zeit ab, der die Nachricht abläuft.</span><span class="sxs-lookup"><span data-stu-id="3350f-115">Gets the time that the message expires.</span></span>
            </summary>
        <value><span data-ttu-id="3350f-116">Ein <see cref="T:System.DateTimeOffset" /> , der angibt, der Zeit, die die Nachricht abläuft.</span><span class="sxs-lookup"><span data-stu-id="3350f-116">A <see cref="T:System.DateTimeOffset" /> indicating the time that the message expires.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.Id" />
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
            <span data-ttu-id="3350f-117">Ruft die Nachrichten-ID.</span><span class="sxs-lookup"><span data-stu-id="3350f-117">Gets the message ID.</span></span>
            </summary>
        <value><span data-ttu-id="3350f-118">Eine Zeichenfolge, enthält die Nachrichten-ID.</span><span class="sxs-lookup"><span data-stu-id="3350f-118">A string containing the message ID.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; InsertionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; InsertionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.InsertionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InsertionTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.InsertionTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.InsertionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3350f-119">Ruft die Zeit ab, der die Nachricht zur Warteschlange hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="3350f-119">Gets the time that the message was added to the queue.</span></span>
            </summary>
        <value><span data-ttu-id="3350f-120">Ein <see cref="T:System.DateTimeOffset" /> , der angibt, der Zeit, die die Nachricht der Warteschlange hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="3350f-120">A <see cref="T:System.DateTimeOffset" /> indicating the time that the message was added to the queue.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public static long MaxMessageSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3350f-121">Ruft die maximale Nachrichtengröße in Bytes ab.</span><span class="sxs-lookup"><span data-stu-id="3350f-121">Gets the maximum message size in bytes.</span></span>
            </summary>
        <value><span data-ttu-id="3350f-122">Die maximale Nachrichtengröße in Byte.</span><span class="sxs-lookup"><span data-stu-id="3350f-122">The maximum message size in bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxNumberOfMessagesToPeek">
      <MemberSignature Language="C#" Value="public static int MaxNumberOfMessagesToPeek { get; }" />
      <MemberSignature Language="ILAsm" Value=".property int32 MaxNumberOfMessagesToPeek" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxNumberOfMessagesToPeek" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MaxNumberOfMessagesToPeek As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxNumberOfMessagesToPeek : int" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxNumberOfMessagesToPeek" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3350f-123">Ruft die maximale Anzahl von Nachrichten, die zu einem bestimmten Zeitpunkt eingesehen werden können.</span><span class="sxs-lookup"><span data-stu-id="3350f-123">Gets the maximum number of messages that can be peeked at a time.</span></span>
            </summary>
        <value><span data-ttu-id="3350f-124">Die maximale Anzahl der Nachrichten, die zu einem bestimmten Zeitpunkt eingesehen werden können.</span><span class="sxs-lookup"><span data-stu-id="3350f-124">The maximum number of messages that can be peeked at a time.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTimeToLive">
      <MemberSignature Language="C#" Value="public static TimeSpan MaxTimeToLive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property valuetype System.TimeSpan MaxTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MaxTimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxTimeToLive : TimeSpan" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3350f-125">Ruft die maximale Zeitspanne, die eine Nachricht in der Warteschlange beibehalten wird.</span><span class="sxs-lookup"><span data-stu-id="3350f-125">Gets the maximum amount of time a message is kept in the queue.</span></span>
            </summary>
        <value><span data-ttu-id="3350f-126">Ein <see cref="T:System.TimeSpan" /> angeben die maximale Zeitspanne, die eine Nachricht in der Warteschlange beibehalten wird.</span><span class="sxs-lookup"><span data-stu-id="3350f-126">A <see cref="T:System.TimeSpan" /> specifying the maximum amount of time a message is kept in the queue.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextVisibleTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; NextVisibleTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; NextVisibleTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.NextVisibleTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextVisibleTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.NextVisibleTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.NextVisibleTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3350f-127">Ruft die Zeit ab, der die Nachricht als Nächstes angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="3350f-127">Gets the time that the message will next be visible.</span></span>
            </summary>
        <value><span data-ttu-id="3350f-128">Ein <see cref="T:System.DateTimeOffset" /> , der angibt, der Zeit, die die Nachricht als Nächstes angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="3350f-128">A <see cref="T:System.DateTimeOffset" /> indicating the time that the message will next be visible.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PopReceipt">
      <MemberSignature Language="C#" Value="public string PopReceipt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PopReceipt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.PopReceipt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PopReceipt As String" />
      <MemberSignature Language="F#" Value="member this.PopReceipt : string" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.PopReceipt" />
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
            <span data-ttu-id="3350f-129">Ruft die abrufbestätigung der Nachricht ab.</span><span class="sxs-lookup"><span data-stu-id="3350f-129">Gets the message's pop receipt.</span></span>
            </summary>
        <value><span data-ttu-id="3350f-130">Eine Zeichenfolge, die den abrufbestätigungswert enthält.</span><span class="sxs-lookup"><span data-stu-id="3350f-130">A string containing the pop receipt value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMessageContent">
      <MemberSignature Language="C#" Value="public void SetMessageContent (byte[] content);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetMessageContent(unsigned int8[] content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.SetMessageContent(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetMessageContent (content As Byte())" />
      <MemberSignature Language="F#" Value="member this.SetMessageContent : byte[] -&gt; unit" Usage="cloudQueueMessage.SetMessageContent content" />
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
        <Parameter Name="content" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="content"><span data-ttu-id="3350f-131">Der Inhalt der Nachricht als Bytearray.</span><span class="sxs-lookup"><span data-stu-id="3350f-131">The content of the message as a byte array.</span></span></param>
        <summary>
            <span data-ttu-id="3350f-132">Legt den Inhalt dieser Nachricht fest.</span><span class="sxs-lookup"><span data-stu-id="3350f-132">Sets the content of this message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMessageContent">
      <MemberSignature Language="C#" Value="public void SetMessageContent (string content);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetMessageContent(string content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.SetMessageContent(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetMessageContent (content As String)" />
      <MemberSignature Language="F#" Value="member this.SetMessageContent : string -&gt; unit" Usage="cloudQueueMessage.SetMessageContent content" />
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
        <Parameter Name="content" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="content"><span data-ttu-id="3350f-133">Eine Zeichenfolge, die den Inhalt der neuen Nachricht enthält.</span><span class="sxs-lookup"><span data-stu-id="3350f-133">A string containing the new message content.</span></span></param>
        <summary>
            <span data-ttu-id="3350f-134">Legt den Inhalt dieser Nachricht fest.</span><span class="sxs-lookup"><span data-stu-id="3350f-134">Sets the content of this message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>