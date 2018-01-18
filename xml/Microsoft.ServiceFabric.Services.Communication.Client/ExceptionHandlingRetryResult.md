<Type Name="ExceptionHandlingRetryResult" FullName="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult">
  <TypeSignature Language="C#" Value="public sealed class ExceptionHandlingRetryResult : Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExceptionHandlingRetryResult extends Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExceptionHandlingRetryResult&#xA;Inherits ExceptionHandlingResult" />
  <TypeSignature Language="F#" Value="type ExceptionHandlingRetryResult = class&#xA;    inherit ExceptionHandlingResult" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f3514-101">Gibt an, die Ausnahmebehandlung Ergebnis, wenn die Anforderung vom Client zum Dienst wiederholt werden kann</span><span class="sxs-lookup"><span data-stu-id="f3514-101">Specifies the exception handling result when the request from client to service can be retried</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionHandlingRetryResult (Exception exception, bool isTransient, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Exception exception, bool isTransient, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.#ctor(System.Exception,System.Boolean,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult : Exception * bool * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * int -&gt; Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult (exception, isTransient, retrySettings, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="f3514-102">Die Ausnahme, die wiederholt werden muss.</span><span class="sxs-lookup"><span data-stu-id="f3514-102">The exception that needs to be retried.</span></span></param>
        <param name="isTransient">
            <span data-ttu-id="f3514-103">Gibt an, ob dies eine vorübergehende wiederholbar Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="f3514-103">Indicates if this is a transient retriable exception.</span></span>
            <span data-ttu-id="f3514-104">Vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen die Kommunikationskanals vom Client zum Dienst noch vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="f3514-104">Transient retriable exceptions are those where the communication channel from client to service still exists.</span></span>
            <span data-ttu-id="f3514-105">Nicht vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen wir müssen den Dienstendpunkt erneut zu beheben, bevor es versucht.</span><span class="sxs-lookup"><span data-stu-id="f3514-105">Non transient retriable exceptions are those where we need to re-resolve the service endpoint before we retry.</span></span>
            </param>
        <param name="retrySettings"><span data-ttu-id="f3514-106">Die RetrySettings, von denen das Wartezeitintervall Herstellung herausgefunden ist.</span><span class="sxs-lookup"><span data-stu-id="f3514-106">The retrySettings from which the interval to wait before retrying is figured out.</span></span></param>
        <param name="maxRetryCount"><span data-ttu-id="f3514-107">Die maximale Anzahl der Häufigkeit, mit der die Ausnahme, die durch den ExceptionId-Parameter identifizierte für wiederholt werden muss.</span><span class="sxs-lookup"><span data-stu-id="f3514-107">The maximum number of times the exception identified by the exceptionId parameter needs to be retried for.</span></span></param>
        <summary>
            <span data-ttu-id="f3514-108">Instanziiert die ExceptionHandlingRetryResult mit den angegebenen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="f3514-108">Instantiates the ExceptionHandlingRetryResult using the given arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionHandlingRetryResult (Exception exception, bool isTransient, TimeSpan retryDelay, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Exception exception, bool isTransient, valuetype System.TimeSpan retryDelay, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.#ctor(System.Exception,System.Boolean,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult : Exception * bool * TimeSpan * int -&gt; Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult (exception, isTransient, retryDelay, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="retryDelay" Type="System.TimeSpan" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="f3514-109">Die Ausnahme, die wiederholt werden muss.</span><span class="sxs-lookup"><span data-stu-id="f3514-109">The exception that needs to be retried.</span></span></param>
        <param name="isTransient">
            <span data-ttu-id="f3514-110">Gibt an, ob dies eine vorübergehende wiederholbar Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="f3514-110">Indicates if this is a transient retriable exception.</span></span>
            <span data-ttu-id="f3514-111">Vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen die Kommunikationskanals vom Client zum Dienst noch vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="f3514-111">Transient retriable exceptions are those where the communication channel from client to service still exists.</span></span>
            <span data-ttu-id="f3514-112">Nicht vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen wir müssen den Dienstendpunkt erneut zu beheben, bevor es versucht.</span><span class="sxs-lookup"><span data-stu-id="f3514-112">Non transient retriable exceptions are those where we need to re-resolve the service endpoint before we retry.</span></span>
            </param>
        <param name="retryDelay"><span data-ttu-id="f3514-113">Das Wartezeitintervall Herstellung</span><span class="sxs-lookup"><span data-stu-id="f3514-113">The interval to wait before retrying</span></span></param>
        <param name="maxRetryCount"><span data-ttu-id="f3514-114">Die maximale Anzahl der Häufigkeit, mit der die Ausnahme, die in der Ausnahmeparameter angegebenen für wiederholt werden muss.</span><span class="sxs-lookup"><span data-stu-id="f3514-114">The maximum number of times the exception given in the exception parameter needs to be retried for.</span></span></param>
        <summary>
            <span data-ttu-id="f3514-115">Instanziiert die ExceptionHandlingRetryResult mit den angegebenen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="f3514-115">Instantiates the ExceptionHandlingRetryResult using the given arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionHandlingRetryResult (string exceptionId, bool isTransient, TimeSpan retryDelay, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string exceptionId, bool isTransient, valuetype System.TimeSpan retryDelay, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.#ctor(System.String,System.Boolean,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (exceptionId As String, isTransient As Boolean, retryDelay As TimeSpan, maxRetryCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult : string * bool * TimeSpan * int -&gt; Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult (exceptionId, isTransient, retryDelay, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exceptionId" Type="System.String" />
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="retryDelay" Type="System.TimeSpan" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="exceptionId"><span data-ttu-id="f3514-116">Ein Bezeichner für die Ausnahme, die wiederholt werden muss.</span><span class="sxs-lookup"><span data-stu-id="f3514-116">An identifier for the exception that needs to be retried.</span></span></param>
        <param name="isTransient">
            <span data-ttu-id="f3514-117">Gibt an, ob dies eine vorübergehende wiederholbar Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="f3514-117">Indicates if this is a transient retriable exception.</span></span>
            <span data-ttu-id="f3514-118">Vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen die Kommunikationskanals vom Client zum Dienst noch vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="f3514-118">Transient retriable exceptions are those where the communication channel from client to service still exists.</span></span>
            <span data-ttu-id="f3514-119">Nicht vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen wir müssen den Dienstendpunkt erneut zu beheben, bevor es versucht.</span><span class="sxs-lookup"><span data-stu-id="f3514-119">Non transient retriable exceptions are those where we need to re-resolve the service endpoint before we retry.</span></span>
            </param>
        <param name="retryDelay"><span data-ttu-id="f3514-120">Das Wartezeitintervall Herstellung</span><span class="sxs-lookup"><span data-stu-id="f3514-120">The interval to wait before retrying</span></span></param>
        <param name="maxRetryCount"><span data-ttu-id="f3514-121">Die maximale Anzahl der Häufigkeit, mit der die Ausnahme, die durch den ExceptionId-Parameter identifizierte für wiederholt werden muss.</span><span class="sxs-lookup"><span data-stu-id="f3514-121">The maximum number of times the exception identified by the exceptionId parameter needs to be retried for.</span></span></param>
        <summary>
            <span data-ttu-id="f3514-122">Instanziiert die ExceptionHandlingRetryResult mit den angegebenen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="f3514-122">Instantiates the ExceptionHandlingRetryResult using the given arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionId">
      <MemberSignature Language="C#" Value="public string ExceptionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExceptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.ExceptionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExceptionId As String" />
      <MemberSignature Language="F#" Value="member this.ExceptionId : string" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.ExceptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3514-123">Eine Zeichenfolge, die eindeutig den Typ der Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="f3514-123">String that uniquely identifies the exception type.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f3514-124">Eindeutige Id für diese Ausnahme ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="f3514-124">Unique id for this exception.</span></span> <span data-ttu-id="f3514-125">Diese Id wird verwendet, um zu verfolgen die Anzahl der Male, die diese Ausnahme wird wiederholt</span><span class="sxs-lookup"><span data-stu-id="f3514-125">This id is used to keep track of the number of times this exception is retried</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsTransient">
      <MemberSignature Language="C#" Value="public bool IsTransient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsTransient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsTransient As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsTransient : bool" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3514-126">Vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen die Kommunikationskanals vom Client zum Dienst noch vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="f3514-126">Transient retriable exceptions are those where the communication channel from client to service still exists.</span></span>
            <span data-ttu-id="f3514-127">Nicht vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen wir müssen den Dienstendpunkt erneut zu beheben, bevor es versucht.</span><span class="sxs-lookup"><span data-stu-id="f3514-127">Non transient retriable exceptions are those where we need to re-resolve the service endpoint before we retry.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f3514-128">"true" gibt an, dass dies eine vorübergehende wiederholbar Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="f3514-128">true indicates that this is a transient retriable exception.</span></span>
            <span data-ttu-id="f3514-129">False gibt an, dass dies ein nicht vorübergehender wiederholbar Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="f3514-129">false indicates that this is a non transient retriable exception.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryCount">
      <MemberSignature Language="C#" Value="public int MaxRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryCount : int" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3514-130">Höchstzahl der Versuche muss dieses Ausnahmetyps Netzwerkvorgängen wiederholt werden.</span><span class="sxs-lookup"><span data-stu-id="f3514-130">Maximum number of times this exception type needs to be retried before giving up.</span></span>
            <span data-ttu-id="f3514-131">Der Standardwert ist "int". "MaxValue"</span><span class="sxs-lookup"><span data-stu-id="f3514-131">The default value is int.MaxValue</span></span>
            </summary>
        <value><span data-ttu-id="f3514-132">Max-Wiederholungsanzahl</span><span class="sxs-lookup"><span data-stu-id="f3514-132">Max retry count</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryDelay">
      <MemberSignature Language="C#" Value="public TimeSpan RetryDelay { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RetryDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetryDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RetryDelay : TimeSpan" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3514-133">Nach dieser Verzögerung soll der Vorgang wiederholt werden.</span><span class="sxs-lookup"><span data-stu-id="f3514-133">The operation should be retried after this delay.</span></span>
            </summary>
        <value><span data-ttu-id="f3514-134">Die Verzögerung, die nach dem der Vorgang wiederholt werden sollte</span><span class="sxs-lookup"><span data-stu-id="f3514-134">Time delay after which the operation should be retried</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>