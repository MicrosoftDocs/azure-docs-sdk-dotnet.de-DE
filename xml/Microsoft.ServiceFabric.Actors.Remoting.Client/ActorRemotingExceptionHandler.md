<Type Name="ActorRemotingExceptionHandler" FullName="Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler">
  <TypeSignature Language="C#" Value="public class ActorRemotingExceptionHandler : Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActorRemotingExceptionHandler extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorRemotingExceptionHandler&#xA;Implements IExceptionHandler" />
  <TypeSignature Language="F#" Value="type ActorRemotingExceptionHandler = class&#xA;    interface IExceptionHandler" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="10522-101">Diese Klasse bereitstellen, Behandlung von Ausnahmen, die bei der Kommunikation mit Service Fabric Akteure über Remote Akteur Schnittstellen gefunden wird.</span><span class="sxs-lookup"><span data-stu-id="10522-101">This class provide handling of exceptions encountered in communicating with service fabric actors over remoted actor interfaces.</span></span>
            </summary>
    <remarks>
      <para>
                <span data-ttu-id="10522-102">Dieser Ausnahmehandler behandelt Ausnahmen, die im Zusammenhang mit den folgenden Szenarien.</span><span class="sxs-lookup"><span data-stu-id="10522-102">This exception handler handles exceptions related to the following scenarios.</span></span>
            </para>
      <list type="list">
        <item>
          <term>
                <span data-ttu-id="10522-103">Doppelte Nachrichten:</span><span class="sxs-lookup"><span data-stu-id="10522-103">Duplicate Messages:</span></span>
            </term>
          <description>
            <para>
                <span data-ttu-id="10522-104">Vorgänge für der Akteur werden vom Client basierend auf der Logik zur Ausnahmebehandlung wiederholt.</span><span class="sxs-lookup"><span data-stu-id="10522-104">Operations performed on the actor are retried from the client based on the exception handling logic.</span></span> <span data-ttu-id="10522-105">Diese Ausnahmen stellen verschiedene Fehlerzustand Dienstfailover dar.</span><span class="sxs-lookup"><span data-stu-id="10522-105">These exceptions represent various error condition including service failover.</span></span> <span data-ttu-id="10522-106">Aus diesem Grund ist es möglich, dass die Akteure mit doppelten Nachrichten zu empfangen.</span><span class="sxs-lookup"><span data-stu-id="10522-106">Therefore it is possible for the actors to receive duplicate messages.</span></span> <span data-ttu-id="10522-107">Wenn eine doppelte Nachricht empfangen wird, während vorherige Nachricht von der Akteur verarbeitet wird, Common Language Runtime eine interne Ausnahme an den Client zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="10522-107">If a duplicate message is received while previous message is being processed by the actor, runtime return an internal exception to the client.</span></span> <span data-ttu-id="10522-108">Anschließend wiederholt der Client den Vorgang, um das Ergebnis aus der Akteur abzurufen.</span><span class="sxs-lookup"><span data-stu-id="10522-108">The client then retries the operation to get the result back from the actor.</span></span> <span data-ttu-id="10522-109">Aus Sicht der Akteur doppelt vorhandenen Vorgang wird von den Clients ausgeführt werden, und er sollte es auf ähnliche Weise behandeln, als ob der Vorgang wurde bereits verarbeitet, und klicken Sie dann eine Nachricht traf doppelt ein.</span><span class="sxs-lookup"><span data-stu-id="10522-109">From the actor's perspective duplicate operation will be performed by the clients and it should handle it in the similar manner as if the operation was already processed and then a duplicate message arrived.</span></span> 
                </para>
            <para>
                <span data-ttu-id="10522-110">Ausnahme im Zusammenhang mit doppelt vorhandenen Vorgang verarbeiteten erfolgt durch Rückgabe <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> aus der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="10522-110">Exception related to duplicate operation being processed is handled by returning <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> from the <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> method.</span></span>
                <span data-ttu-id="10522-111">Die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" /> Eigenschaft von der <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> festgelegt ist auf "true", die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" /> Eigenschaft wird auf einen Zufallswert festgelegt, bis zu <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" /> und <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" /> -Eigenschaftensatz auf <see cref="F:System.Int32.MaxValue" />.</span><span class="sxs-lookup"><span data-stu-id="10522-111">The <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" /> property of the <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> is set to true, the <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />  property is set to a random value up to <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" /> and <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" /> property is set to <see cref="F:System.Int32.MaxValue" />.</span></span>
                </para>
          </description>
        </item>
        <item>
          <term>
            <span data-ttu-id="10522-112"><see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" />:</span><span class="sxs-lookup"><span data-stu-id="10522-112"><see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" />:</span></span>
            </term>
          <description>
            <para>
                <span data-ttu-id="10522-113">Vorgänge für die Akteure dokumentdienstrollen erfolgt mithilfe von eine Basis aktivieren Concurrency Sperre (<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings" />), die logische Aufruf Kontext Grundlage Reentranz unterstützt.</span><span class="sxs-lookup"><span data-stu-id="10522-113">Operations on the actors are performed using a turn based concurrency lock (<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings" />) that supports logical call context based reentrancy.</span></span> <span data-ttu-id="10522-114">Im Falle der Vorgänge mit langer Akteur ist es möglich, dass der Erhalt dieser Sperre zu einem Timeout führen. Die Übernahme der Sperre können auch einem Timeout bei einem Deadlocksituationen (Akteur A und Akteur B miteinander fast zur selben Zeit aufrufen).</span><span class="sxs-lookup"><span data-stu-id="10522-114">In case of the long running actor operations it is possible for acquisition of this lock to time out. The acquisition of the lock can also time out in case of the deadlock situations (actor A and actor B calling each other almost at the same time).</span></span> 
                </para>
            <para>
                <span data-ttu-id="10522-115">Die Ausnahme, die im Zusammenhang mit der Parallelität Sperrtimeout erfolgt durch Rückgabe <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> aus der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> Methode, wenn der Client den Vorgang nicht auf einen anderen Akteur ist.</span><span class="sxs-lookup"><span data-stu-id="10522-115">The exception related to concurrency lock timeout is handled by returning <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> from the <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> method if the client performing the operation is not another actor.</span></span>
                <span data-ttu-id="10522-116">Die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" /> Eigenschaft von der <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> festgelegt ist auf "true", die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" /> Eigenschaft wird auf einen Zufallswert festgelegt, bis zu <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" /> und <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" /> -Eigenschaftensatz auf <see cref="F:System.Int32.MaxValue" />.</span><span class="sxs-lookup"><span data-stu-id="10522-116">The <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" /> property of the <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> is set to true, the <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />  property is set to a random value up to <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" /> and <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" /> property is set to <see cref="F:System.Int32.MaxValue" />.</span></span>
                </para>
            <para>
                <span data-ttu-id="10522-117">Die Ausnahme, die im Zusammenhang mit der Parallelität Sperrtimeout erfolgt durch Rückgabe <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingThrowResult" /> aus der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> -Methode, wenn der Client den Vorgang ausführt, einen anderen Akteur ist.</span><span class="sxs-lookup"><span data-stu-id="10522-117">The exception related to concurrency lock timeout is handled by returning <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingThrowResult" /> from the <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> method, if the client performing the operation is another actor.</span></span> <span data-ttu-id="10522-118">In den Deadlocksituationen, die Dies ermöglicht eine Aufrufkette ganz entladen, zurück an den ursprünglichen Client und der Vorgang dann von dort wiederholt wird.</span><span class="sxs-lookup"><span data-stu-id="10522-118">In the deadlock situations this allows the call chain to unwind all the way back to the original client and the operation is then retried from there.</span></span>
                </para>
          </description>
        </item>
      </list>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorRemotingExceptionHandler ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
                <span data-ttu-id="10522-119">Instanziiert eine neue <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler" /> die Behandeln von Ausnahmen, die bei der Kommunikation mit Service Fabric Akteure über Remote Akteur Schnittstellen gefunden verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="10522-119">Instantiates a new <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler" /> which can be used to handle exceptions encountered in communicating with service fabric actors over remoted actor interfaces.</span></span>
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException">
      <MemberSignature Language="C#" Value="bool IExceptionHandler.TryHandleException (Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, out Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult result);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance bool Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, [out] class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult&amp; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler.Microsoft#ServiceFabric#Services#Communication#Client#IExceptionHandler#TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exceptionInformation" Type="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="result" Type="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="exceptionInformation"><span data-ttu-id="10522-120">Informationen zur Ausnahme</span><span class="sxs-lookup"><span data-stu-id="10522-120">Information about the exception</span></span></param>
        <param name="retrySettings"><span data-ttu-id="10522-121">Die Voreinstellungen des Vorgang wiederholen.</span><span class="sxs-lookup"><span data-stu-id="10522-121">The operation retry preferences.</span></span></param>
        <param name="result"><span data-ttu-id="10522-122">Ergebnis der Behandlung von Ausnahmen</span><span class="sxs-lookup"><span data-stu-id="10522-122">Result of the exception handling</span></span></param>
        <summary>
            <span data-ttu-id="10522-123">Methode, die die Ausnahme überprüft und bestimmt, wie die Ausnahme behandelt werden kann.</span><span class="sxs-lookup"><span data-stu-id="10522-123">Method that examines the exception and determines how that exception can be handled.</span></span> 
            </summary>
        <returns><span data-ttu-id="10522-124">"true", wenn die Ausnahme behandelt "false" ist, andernfalls</span><span class="sxs-lookup"><span data-stu-id="10522-124">true if the exception is handled, false otherwise</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>