<Type Name="EventProcessorOptions" FullName="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions">
  <TypeSignature Language="C#" Value="public sealed class EventProcessorOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventProcessorOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventProcessorOptions" />
  <TypeSignature Language="F#" Value="type EventProcessorOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8f0fd-101">Definiert die Common Language Runtime-Optionen bei der Registrierung einer <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> Schnittstelle mit einer EventHubConsumerGroup.</span><span class="sxs-lookup"><span data-stu-id="8f0fd-101">Defines the runtime options when registering an <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> interface with an EventHubConsumerGroup.</span></span> <span data-ttu-id="8f0fd-102">Dies ist auch der Mechanismus zum Abfangen von Ausnahmen aus einer IEventProcessor-Instanz anhand einer <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="8f0fd-102">This is also the mechanism for catching exceptions from an IEventProcessor instance used by an <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" /> object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8f0fd-103">Erstellt ein neues <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="8f0fd-103">Creates a new <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions" /> object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultOptions">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.Processor.EventProcessorOptions DefaultOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.EventHubs.Processor.EventProcessorOptions DefaultOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.DefaultOptions" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DefaultOptions As EventProcessorOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultOptions : Microsoft.Azure.EventHubs.Processor.EventProcessorOptions" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.DefaultOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.Processor.EventProcessorOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f0fd-104">Gibt eine EventProcessorOptions-Instanz mit allen Optionen, die auf die Standardwerte festgelegt.</span><span class="sxs-lookup"><span data-stu-id="8f0fd-104">Returns an EventProcessorOptions instance with all options set to the default values.</span></span>
            <span data-ttu-id="8f0fd-105">Die Standardwerte sind: <para>MaxBatchSize: 10</para><para>ReceiveTimeOut: 1 Minute</para><para>PrefetchCount: 300</para><para>InitialOffsetProvider: verwendet den letzten Offset geprüften, oder StartOfStream</para><para>InvokeProcessorAfterReceiveTimeout: "false"</para></span><span class="sxs-lookup"><span data-stu-id="8f0fd-105">The default values are: <para>MaxBatchSize: 10</para><para>ReceiveTimeOut: 1 minute</para><para>PrefetchCount: 300</para><para>InitialOffsetProvider: uses the last offset checkpointed, or StartOfStream</para><para>InvokeProcessorAfterReceiveTimeout: false</para></span></span></summary>
        <value><span data-ttu-id="8f0fd-106">eine EventProcessorOptions-Instanz mit allen Optionen auf die Standardwerte festgelegt</span><span class="sxs-lookup"><span data-stu-id="8f0fd-106">an EventProcessorOptions instance with all options set to the default values</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableReceiverRuntimeMetric">
      <MemberSignature Language="C#" Value="public bool EnableReceiverRuntimeMetric { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableReceiverRuntimeMetric" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.EnableReceiverRuntimeMetric" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableReceiverRuntimeMetric As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableReceiverRuntimeMetric : bool with get, set" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.EnableReceiverRuntimeMetric" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> <span data-ttu-id="8f0fd-107">Ruft ab oder legt einen Wert, der angibt, ob der Empfänger die Common Language Runtime-Metrik aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="8f0fd-107">Gets or sets a value indicating whether the runtime metric of a receiver is enabled.</span></span> </summary>
        <value> <span data-ttu-id="8f0fd-108">"true", wenn ein Client zugreifen möchte <see cref="T:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation" /> mit <see cref="T:Microsoft.Azure.EventHubs.Processor.PartitionContext" />.</span><span class="sxs-lookup"><span data-stu-id="8f0fd-108">true if a client wants to access <see cref="T:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation" /> using <see cref="T:Microsoft.Azure.EventHubs.Processor.PartitionContext" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialOffsetProvider">
      <MemberSignature Language="C#" Value="public Func&lt;string,object&gt; InitialOffsetProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;string, object&gt; InitialOffsetProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.InitialOffsetProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialOffsetProvider As Func(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.InitialOffsetProvider : Func&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.InitialOffsetProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f0fd-109">Ruft ab oder legt die aktuelle Funktion verwendet, um den ersten offset, an dem mit dem Empfang von Ereignissen für eine Partition zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="8f0fd-109">Get or sets the current function used to determine the initial offset at which to start receiving events for a partition.</span></span>
            <span data-ttu-id="8f0fd-110"><para>Eine Rückgabe null gibt an, dass er die interne-Anbieter, der den letzten Wert des geprüften Offset (falls vorhanden) verwendet oder StartOfSTream (sofern nicht).</para></span><span class="sxs-lookup"><span data-stu-id="8f0fd-110"><para>A null return indicates that it is using the internal provider, which uses the last checkpointed offset value (if present) or StartOfSTream (if not).</para></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeProcessorAfterReceiveTimeout">
      <MemberSignature Language="C#" Value="public bool InvokeProcessorAfterReceiveTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool InvokeProcessorAfterReceiveTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.InvokeProcessorAfterReceiveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property InvokeProcessorAfterReceiveTimeout As Boolean" />
      <MemberSignature Language="F#" Value="member this.InvokeProcessorAfterReceiveTimeout : bool with get, set" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.InvokeProcessorAfterReceiveTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f0fd-111">Gibt zurück, ob die EventProcessorHost IEventProcessor.OnEvents(null) aufgerufen wird, wenn ein Empfangs-Timeout (true) oder nicht auftritt (false).</span><span class="sxs-lookup"><span data-stu-id="8f0fd-111">Returns whether the EventProcessorHost will call IEventProcessor.OnEvents(null) when a receive timeout occurs (true) or not (false).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBatchSize">
      <MemberSignature Language="C#" Value="public int MaxBatchSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBatchSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.MaxBatchSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBatchSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBatchSize : int with get, set" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.MaxBatchSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f0fd-112">Gibt die maximale Größe eines Ereignis-Batches, die mit IEventProcessor.ProcessEventsAsync aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="8f0fd-112">Returns the maximum size of an event batch that IEventProcessor.ProcessEventsAsync will be called with</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f0fd-113">Ruft ab oder legt die aktuelle Prefetch-Anzahl für den zugrunde liegenden Client.</span><span class="sxs-lookup"><span data-stu-id="8f0fd-113">Gets or sets the current prefetch count for the underlying client.</span></span>
            <span data-ttu-id="8f0fd-114">Der Standardwert ist 300.</span><span class="sxs-lookup"><span data-stu-id="8f0fd-114">The default is 300.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ReceiveTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ReceiveTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.ReceiveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ReceiveTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ReceiveTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.ReceiveTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f0fd-115">Ruft ab oder legt das Timeout Länge für Empfangsvorgänge.</span><span class="sxs-lookup"><span data-stu-id="8f0fd-115">Gets or sets the timeout length for receive operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetExceptionHandler">
      <MemberSignature Language="C#" Value="public void SetExceptionHandler (Action&lt;Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs&gt; exceptionHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetExceptionHandler(class System.Action`1&lt;class Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs&gt; exceptionHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.SetExceptionHandler(System.Action{Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs})" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetExceptionHandler (exceptionHandler As Action(Of ExceptionReceivedEventArgs))" />
      <MemberSignature Language="F#" Value="member this.SetExceptionHandler : Action&lt;Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs&gt; -&gt; unit" Usage="eventProcessorOptions.SetExceptionHandler exceptionHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exceptionHandler" Type="System.Action&lt;Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs&gt;" />
      </Parameters>
      <Docs>
        <param name="exceptionHandler"><span data-ttu-id="8f0fd-116">Handler, der aufgerufen wird, wenn eine Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="8f0fd-116">Handler which is called when an exception occurs.</span></span> <span data-ttu-id="8f0fd-117">Legen Sie auf die null-Behandlung beendet.</span><span class="sxs-lookup"><span data-stu-id="8f0fd-117">Set to null to stop handling.</span></span></param>
        <summary>
            <span data-ttu-id="8f0fd-118">Legt einen Ereignishandler, der Benachrichtigung über allgemeine Ausnahmen empfängt.</span><span class="sxs-lookup"><span data-stu-id="8f0fd-118">Sets a handler which receives notification of general exceptions.</span></span>
            <span data-ttu-id="8f0fd-119"><para>Ausnahmen, die auftreten, während der Verarbeitung von Ereignissen aus einer bestimmten Event Hub-Partition an der OnError-Methode von der Ereignisprozessor für diese Partition übermittelt werden. Dieser Handler wird aufgerufen, in Fällen, wenn kein Ereignisprozessor, der auslösende Aktivität zugeordneten vorhanden ist, oder der Ereignisprozessor konnte nicht erstellt werden.</para></span><span class="sxs-lookup"><span data-stu-id="8f0fd-119"><para>Exceptions which occur while processing events from a particular Event Hub partition are delivered to the onError method of the event processor for that partition. This handler is called on occasions when there is no event processor associated with the throwing activity, or the event processor could not be created.</para></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>