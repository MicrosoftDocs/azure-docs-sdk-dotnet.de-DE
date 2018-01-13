<Type Name="RetryExponential" FullName="Microsoft.ServiceBus.RetryExponential">
  <TypeSignature Language="C#" Value="public sealed class RetryExponential : Microsoft.ServiceBus.RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RetryExponential extends Microsoft.ServiceBus.RetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.RetryExponential" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RetryExponential&#xA;Inherits RetryPolicy" />
  <TypeSignature Language="F#" Value="type RetryExponential = class&#xA;    inherit RetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.RetryPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="256ac-101">Stellt eine Implementierung eine wiederholungsrichtlinie dar.</span><span class="sxs-lookup"><span data-stu-id="256ac-101">Represents an implementation of a retry policy.</span></span> <span data-ttu-id="256ac-102">Für jedes Mal der messaging-Vorgang muss wiederholt werden, steigt die Verzögerung zwischen den Wiederholungsversuchen Weise versetzten, exponentiell.</span><span class="sxs-lookup"><span data-stu-id="256ac-102">For each time the messaging operation must be retried, the delay between retries grows in a staggered, exponential manner.</span></span></summary>
    <remarks><span data-ttu-id="256ac-103">Die wiederholungsrichtlinie für die folgenden Aspekte berücksichtigt: <list type="bullet"> <item>berücksichtigen Sie die Richtlinie immer die <seealso cref="P:Microsoft.ServiceBus.Messaging.ClientEntity.OperationTimeout" /> damit, wiederholen Sie den Vorgang beendet wird, wenn es sich bei der nächsten Wiederholungsintervall wird das die Vorgang Zeit überschreitet.</item> <item>die Richtlinie wird nur wiederholen, wenn <seealso cref="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" /> ist "true".</item> <item>verzögern, sollten die Richtlinie mithilfe einer zusätzlichen 10 Sekunden ist das der Ausnahme weiter eine<seealso cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException" /></item></list></span><span class="sxs-lookup"><span data-stu-id="256ac-103">The retry policy will honor the following aspect: <list type="bullet"><item>the policy always honor the <seealso cref="P:Microsoft.ServiceBus.Messaging.ClientEntity.OperationTimeout" /> so that retry will terminate if the next retry interval will exceed the operation time.</item><item>the policy only retry when <seealso cref="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" /> is true.</item><item>the policy should delay further by an additional 10 seconds if exception is a <seealso cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException" /></item></list></span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryExponential (TimeSpan minBackoff, TimeSpan maxBackoff, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan minBackoff, valuetype System.TimeSpan maxBackoff, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryExponential.#ctor(System.TimeSpan,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (minBackoff As TimeSpan, maxBackoff As TimeSpan, maxRetryCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.RetryExponential : TimeSpan * TimeSpan * int -&gt; Microsoft.ServiceBus.RetryExponential" Usage="new Microsoft.ServiceBus.RetryExponential (minBackoff, maxBackoff, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minBackoff"><span data-ttu-id="256ac-104">Die minimale zurückgestellt Wert gewartet werden soll.</span><span class="sxs-lookup"><span data-stu-id="256ac-104">The minimum back off value to wait.</span></span> <span data-ttu-id="256ac-105">Dieser Wert darf nicht größer als oder gleich sein <see cref="P:Microsoft.ServiceBus.RetryExponential.MaximumBackoff" />, andernfalls Vorgänge möglicherweise nicht wiederholt.</span><span class="sxs-lookup"><span data-stu-id="256ac-105">This value must not be greater than or equal to <see cref="P:Microsoft.ServiceBus.RetryExponential.MaximumBackoff" />, otherwise operations might not be able to retry.</span></span></param>
        <param name="maxBackoff"><span data-ttu-id="256ac-106">Die maximale zurückgestellt Wert zu warten.</span><span class="sxs-lookup"><span data-stu-id="256ac-106">The maximum back off value to wait.</span></span> <span data-ttu-id="256ac-107">Dieser Wert muss größer als oder gleich der <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> Wert andernfalls Vorgänge möglicherweise nicht wiederholt.</span><span class="sxs-lookup"><span data-stu-id="256ac-107">This value must not be greater than or equal to the <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> value, otherwise operations might not be able to retry.</span></span></param>
        <param name="maxRetryCount"><span data-ttu-id="256ac-108">Die Höchstzahl der Versuche, die die Wiederholung Richtlinieninstanz das Wiederholungsintervall für die Zeit berechnet.</span><span class="sxs-lookup"><span data-stu-id="256ac-108">The maximum number of times the retry policy instance calculates the retry time interval.</span></span> <span data-ttu-id="256ac-109">Wenn die Anzahl der Versuche, diesen Wert überschreitet, beendet die Wiederholung, auch wenn einige verbleibende Zeit für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="256ac-109">If the number of retries exceeds this value, the retry terminates, even if there is some remaining operation time.</span></span></param>
        <summary><span data-ttu-id="256ac-110">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.RetryExponential" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="256ac-110">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.RetryExponential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryExponential (TimeSpan minBackoff, TimeSpan maxBackoff, TimeSpan deltaBackoff, TimeSpan terminationTimeBuffer, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan minBackoff, valuetype System.TimeSpan maxBackoff, valuetype System.TimeSpan deltaBackoff, valuetype System.TimeSpan terminationTimeBuffer, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryExponential.#ctor(System.TimeSpan,System.TimeSpan,System.TimeSpan,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (minBackoff As TimeSpan, maxBackoff As TimeSpan, deltaBackoff As TimeSpan, terminationTimeBuffer As TimeSpan, maxRetryCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.RetryExponential : TimeSpan * TimeSpan * TimeSpan * TimeSpan * int -&gt; Microsoft.ServiceBus.RetryExponential" Usage="new Microsoft.ServiceBus.RetryExponential (minBackoff, maxBackoff, deltaBackoff, terminationTimeBuffer, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This constructor is obsolete. Please use the other constructor instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="minBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxBackoff" Type="System.TimeSpan" />
        <Parameter Name="deltaBackoff" Type="System.TimeSpan" />
        <Parameter Name="terminationTimeBuffer" Type="System.TimeSpan" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minBackoff"><span data-ttu-id="256ac-111">Die minimale zurückgestellt Wert gewartet werden soll.</span><span class="sxs-lookup"><span data-stu-id="256ac-111">The minimum back off value to wait.</span></span> <span data-ttu-id="256ac-112">Dieser Wert darf nicht größer als oder gleich sein <see cref="P:Microsoft.ServiceBus.RetryExponential.MaximumBackoff" />, andernfalls Vorgänge möglicherweise nicht wiederholt.</span><span class="sxs-lookup"><span data-stu-id="256ac-112">This value must not be greater than or equal to <see cref="P:Microsoft.ServiceBus.RetryExponential.MaximumBackoff" />, otherwise operations might not be able to retry.</span></span></param>
        <param name="maxBackoff"><span data-ttu-id="256ac-113">Die maximale zurückgestellt Wert zu warten.</span><span class="sxs-lookup"><span data-stu-id="256ac-113">The maximum back off value to wait.</span></span> <span data-ttu-id="256ac-114">Dieser Wert muss größer als oder gleich der <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> Wert andernfalls Vorgänge möglicherweise nicht wiederholt.</span><span class="sxs-lookup"><span data-stu-id="256ac-114">This value must not be greater than or equal to the <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> value, otherwise operations might not be able to retry.</span></span></param>
        <param name="deltaBackoff"><span data-ttu-id="256ac-115">Das Backoff-Intervall, das die Wiederholung zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="256ac-115">The backoff interval associated with the retry.</span></span></param>
        <param name="terminationTimeBuffer"><span data-ttu-id="256ac-116">Der Beendigungszeitpuffer für die Wiederholung.</span><span class="sxs-lookup"><span data-stu-id="256ac-116">The termination time buffer associated with the retry.</span></span></param>
        <param name="maxRetryCount"><span data-ttu-id="256ac-117">Die Höchstzahl der Versuche, die die Wiederholung Richtlinieninstanz das Wiederholungsintervall für die Zeit berechnet.</span><span class="sxs-lookup"><span data-stu-id="256ac-117">The maximum number of times the retry policy instance calculates the retry time interval.</span></span> <span data-ttu-id="256ac-118">Wenn die Anzahl der Versuche, diesen Wert überschreitet, beendet die Wiederholung, auch wenn einige verbleibende Zeit für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="256ac-118">If the number of retries exceeds this value, the retry terminates, even if there is some remaining operation time.</span></span></param>
        <summary><span data-ttu-id="256ac-119">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.RetryExponential" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="256ac-119">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.RetryExponential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceBus.RetryPolicy Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceBus.RetryPolicy Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryExponential.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Clone () As RetryPolicy" />
      <MemberSignature Language="F#" Value="override this.Clone : unit -&gt; Microsoft.ServiceBus.RetryPolicy" Usage="retryExponential.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RetryPolicy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="256ac-120">Erstellt eine neue Kopie dieser Instanz.</span><span class="sxs-lookup"><span data-stu-id="256ac-120">Creates a new copy of this instance.</span></span></summary>
        <returns><span data-ttu-id="256ac-121">Die erstellte neue Kopie dieser Instanz.</span><span class="sxs-lookup"><span data-stu-id="256ac-121">The created new copy of this instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeltaBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan DeltaBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DeltaBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RetryExponential.DeltaBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeltaBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DeltaBackoff : TimeSpan" Usage="Microsoft.ServiceBus.RetryExponential.DeltaBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="256ac-122">Ermittelt oder definiert das Backoff-Intervall, das die Wiederholung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="256ac-122">Gets or sets the backoff interval associated with the retry.</span></span></summary>
        <value><span data-ttu-id="256ac-123">Das Backoff-Intervall, das die Wiederholung zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="256ac-123">The backoff interval associated with the retry.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRetryableException">
      <MemberSignature Language="C#" Value="protected override bool IsRetryableException (Exception lastException);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool IsRetryableException(class System.Exception lastException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryExponential.IsRetryableException(System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function IsRetryableException (lastException As Exception) As Boolean" />
      <MemberSignature Language="F#" Value="override this.IsRetryableException : Exception -&gt; bool" Usage="retryExponential.IsRetryableException lastException" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="lastException">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan MaximumBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaximumBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RetryExponential.MaximumBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaximumBackoff : TimeSpan" Usage="Microsoft.ServiceBus.RetryExponential.MaximumBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="256ac-124">Ruft ab oder legt die maximale Backoff-Intervall.</span><span class="sxs-lookup"><span data-stu-id="256ac-124">Gets or sets the maximum backoff interval.</span></span></summary>
        <value><span data-ttu-id="256ac-125">Das maximale backoffintervall.</span><span class="sxs-lookup"><span data-stu-id="256ac-125">The maximum backoff interval.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryCount">
      <MemberSignature Language="C#" Value="public int MaxRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RetryExponential.MaxRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryCount : int" Usage="Microsoft.ServiceBus.RetryExponential.MaxRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="256ac-126">Ruft ab oder legt die maximale Anzahl von zulässigen Wiederholungen.</span><span class="sxs-lookup"><span data-stu-id="256ac-126">Gets or sets the maximum number of allowed retries.</span></span></summary>
        <value><span data-ttu-id="256ac-127">Die maximale Anzahl von zulässigen Wiederholungen.</span><span class="sxs-lookup"><span data-stu-id="256ac-127">The maximum number of allowed retries.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimalBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan MinimalBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MinimalBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RetryExponential.MinimalBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinimalBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MinimalBackoff : TimeSpan" Usage="Microsoft.ServiceBus.RetryExponential.MinimalBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="256ac-128">Ruft ab oder legt das Intervall für minimale Wartezeit fest.</span><span class="sxs-lookup"><span data-stu-id="256ac-128">Gets or sets the minimum backoff interval.</span></span></summary>
        <value><span data-ttu-id="256ac-129">Das Intervall für minimale Wartezeit.</span><span class="sxs-lookup"><span data-stu-id="256ac-129">The minimum backoff interval.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnShouldRetry">
      <MemberSignature Language="C#" Value="protected override bool OnShouldRetry (TimeSpan remainingTime, int currentRetryCount, out TimeSpan retryInterval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnShouldRetry(valuetype System.TimeSpan remainingTime, int32 currentRetryCount, [out] valuetype System.TimeSpan&amp; retryInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryExponential.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnShouldRetry (remainingTime As TimeSpan, currentRetryCount As Integer, ByRef retryInterval As TimeSpan) As Boolean" />
      <MemberSignature Language="F#" Value="override this.OnShouldRetry : TimeSpan * int *  -&gt; bool" Usage="retryExponential.OnShouldRetry (remainingTime, currentRetryCount, retryInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="remainingTime" Type="System.TimeSpan" />
        <Parameter Name="currentRetryCount" Type="System.Int32" />
        <Parameter Name="retryInterval" Type="System.TimeSpan&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="remainingTime">To be added.</param>
        <param name="currentRetryCount">To be added.</param>
        <param name="retryInterval">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminationTimeBuffer">
      <MemberSignature Language="C#" Value="public TimeSpan TerminationTimeBuffer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TerminationTimeBuffer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RetryExponential.TerminationTimeBuffer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TerminationTimeBuffer As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TerminationTimeBuffer : TimeSpan" Usage="Microsoft.ServiceBus.RetryExponential.TerminationTimeBuffer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="256ac-130">Abrufen oder festlegen den Beendigung Zeitpuffer, die die Wiederholung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="256ac-130">Gets or sets the termination time buffer associated with the retry.</span></span></summary>
        <value><span data-ttu-id="256ac-131">Der Beendigungszeitpuffer für die Wiederholung.</span><span class="sxs-lookup"><span data-stu-id="256ac-131">The termination time buffer associated with the retry.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>