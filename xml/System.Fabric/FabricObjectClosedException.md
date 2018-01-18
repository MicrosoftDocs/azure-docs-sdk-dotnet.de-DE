<Type Name="FabricObjectClosedException" FullName="System.Fabric.FabricObjectClosedException">
  <TypeSignature Language="C#" Value="public class FabricObjectClosedException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricObjectClosedException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricObjectClosedException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricObjectClosedException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricObjectClosedException = class&#xA;    inherit FabricException" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.MaintainabilityRules", "SA1402:FileMayOnlyContainASingleClass", Justification="Exception")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="943a4-101">Die Ausnahme, die ausgelöst wird, wenn das Service Fabric Objekt derzeit im Zustand "geschlossen" eine der folgenden Bedingungen zutrifft:</span><span class="sxs-lookup"><span data-stu-id="943a4-101">The exception that is thrown when the Service Fabric object is currently in a closed state due to one of the following conditions:</span></span>
                1. <span data-ttu-id="943a4-102">Der Service Fabric-Objekt wird gelöscht.</span><span class="sxs-lookup"><span data-stu-id="943a4-102">The Service Fabric object is being deleted.</span></span>
                2. <span data-ttu-id="943a4-103">Der Service Fabric-Objekt ist nicht erreichbar, weil ein Failover.</span><span class="sxs-lookup"><span data-stu-id="943a4-103">The Service Fabric object is not reachable due to a failover.</span></span>
            </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="943a4-104">Beispielsweise diese Ausnahme kann beobachtet werden, wenn ein Dienst versucht, zum Ausführen eines Vorgangs in einem Fabric-Dienst oder <see cref="T:System.Fabric.FabricReplicator" /> Objekt sich im Zustand "abgeschlossen" befindet.</span><span class="sxs-lookup"><span data-stu-id="943a4-104">For example, this exception can be observed when a service attempts to perform an operation on a Service Fabric or <see cref="T:System.Fabric.FabricReplicator" /> object while it is in the closed state.</span></span> <span data-ttu-id="943a4-105">Ein weiteres Beispiel ist eine API aufgerufen wird, auf ein <see cref="T:System.Fabric.FabricClient" /> Objekt, wenn es sich im Zustand "abgeschlossen" befindet.</span><span class="sxs-lookup"><span data-stu-id="943a4-105">Another example is when an API is invoked on a <see cref="T:System.Fabric.FabricClient" /> object when it is in the closed state.</span></span></para>
      <para>
            <span data-ttu-id="943a4-106">Behandlung von <see cref="T:System.Fabric.FabricObjectClosedException" /> für <see cref="T:System.Fabric.FabricClient" /> Aufrufe: Wenn ein Aufruf FabricClient sieht <see cref="T:System.Fabric.FabricObjectClosedException" />, finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions">FabricClient Exception Handling</see> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="943a4-106">Handling <see cref="T:System.Fabric.FabricObjectClosedException" /> for <see cref="T:System.Fabric.FabricClient" /> calls: If a FabricClient call sees <see cref="T:System.Fabric.FabricObjectClosedException" />, see <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions">FabricClient Exception Handling</see> for handling common FabricClient failures.</span></span>
                </para>
      <para>
            <span data-ttu-id="943a4-107">Behandlung von <see cref="T:System.Fabric.FabricObjectClosedException" /> für <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">zuverlässige Sammlungen</see> :</span><span class="sxs-lookup"><span data-stu-id="943a4-107">Handling <see cref="T:System.Fabric.FabricObjectClosedException" /> for <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">Reliable Collections</see> :</span></span>
                1. <span data-ttu-id="943a4-108">Wenn der Dienst erkennt <see cref="T:System.Fabric.FabricObjectClosedException" /> in <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">Coredispatcher</see>, sollten sie die Ausnahmen abfangen und Zurückgeben von <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">Coredispatcher</see>.</span><span class="sxs-lookup"><span data-stu-id="943a4-108">If the service sees <see cref="T:System.Fabric.FabricObjectClosedException" /> in <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see>, it should catch the exception and return from <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see>.</span></span>
                    <span data-ttu-id="943a4-109">Die <see cref="T:System.Threading.CancellationToken" /> übergeben <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">Coredispatcher</see> signalisiert werden würde.</span><span class="sxs-lookup"><span data-stu-id="943a4-109">The <see cref="T:System.Threading.CancellationToken" /> passed to <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see> would be signalled.</span></span> <span data-ttu-id="943a4-110">Alle Hintergrundaufgaben sollte die Ausführung abgeschlossen, wenn dieser Abbruch signalisiert wird.</span><span class="sxs-lookup"><span data-stu-id="943a4-110">All background tasks should complete execution when this cancellation is signalled.</span></span>
                    2. <span data-ttu-id="943a4-111">Wenn der Dienst erkennt <see cref="T:System.Fabric.FabricObjectClosedException" /> während der Verarbeitung einer Clientanforderung (z. B. über ihre Kommunikation Listener), der Dienst sollte die Ausnahme an dem Client auf dem Client sollte es den Dienst erneut aufzulösen, um das neue primäre suchen zu signalisieren.</span><span class="sxs-lookup"><span data-stu-id="943a4-111">If the service sees <see cref="T:System.Fabric.FabricObjectClosedException" /> while processing a client request (e.g. via their communication listener), the service should throw the exception to the client to signal the client that it should re-resolve the service in order to locate the new Primary.</span></span>
                
            <span data-ttu-id="943a4-112">[HINWEIS] Wenn ein <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> entfernt wurde, über <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestatemanager.removeasync?view=azure-dotnet#Microsoft_ServiceFabric_Data_IReliableStateManager_RemoveAsync_Microsoft_ServiceFabric_Data_ITransaction_System_Uri_System_TimeSpan_">IReliableStateManager.RemoveAsync()</see>, alle Aufrufe, die versuchen, den Zugriff auf dieses <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> sehen <see cref="T:System.Fabric.FabricObjectClosedException" />.</span><span class="sxs-lookup"><span data-stu-id="943a4-112">[NOTE] If an <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> was removed via <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestatemanager.removeasync?view=azure-dotnet#Microsoft_ServiceFabric_Data_IReliableStateManager_RemoveAsync_Microsoft_ServiceFabric_Data_ITransaction_System_Uri_System_TimeSpan_">IReliableStateManager.RemoveAsync()</see>, any calls trying to access this <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> would see <see cref="T:System.Fabric.FabricObjectClosedException" />.</span></span> <span data-ttu-id="943a4-113">Diese Aufrufe mit synchronisiert werden, muss die <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestatemanager.removeasync?view=azure-dotnet#Microsoft_ServiceFabric_Data_IReliableStateManager_RemoveAsync_Microsoft_ServiceFabric_Data_ITransaction_System_Uri_System_TimeSpan_">IReliableStateManager.RemoveAsync()</see> aufrufen und sollten wissen, dass die <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="943a4-113">These calls needs to be synchronized with the <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestatemanager.removeasync?view=azure-dotnet#Microsoft_ServiceFabric_Data_IReliableStateManager_RemoveAsync_Microsoft_ServiceFabric_Data_ITransaction_System_Uri_System_TimeSpan_">IReliableStateManager.RemoveAsync()</see> call and should know that the <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> has been removed.</span></span>
            <span data-ttu-id="943a4-114">Die Vorgehensweisen in diesem Fall sind:</span><span class="sxs-lookup"><span data-stu-id="943a4-114">Possible ways to handle this case are:</span></span>
            1. <span data-ttu-id="943a4-115">Erstellen der <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> Wenn es entfernt wurde, und wiederholen Sie den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="943a4-115">Recreate the <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> if it was removed and retry the operation.</span></span>
            2. <span data-ttu-id="943a4-116">Ignorieren der <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> und Verarbeiten von anderen <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> im Dienst.</span><span class="sxs-lookup"><span data-stu-id="943a4-116">Ignore the <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> and process other <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> in the service.</span></span>
                3. <span data-ttu-id="943a4-117">Verwenden Sie sperren, um die Racebedingung zu vermeiden.</span><span class="sxs-lookup"><span data-stu-id="943a4-117">Use locks to avoid the race.</span></span> <span data-ttu-id="943a4-118">Daher innerhalb ein Remove-Aufruf der Benutzer kann beendet die Verarbeitung der <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> weiter.</span><span class="sxs-lookup"><span data-stu-id="943a4-118">Hence if a remove call comes in, the user can stop processing the <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> further.</span></span>
                </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="943a4-119">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricObjectClosedException" /> Klasse mit dem Fehlercode <see cref="F:System.Fabric.FabricErrorCode.Unknown" />.</span><span class="sxs-lookup"><span data-stu-id="943a4-119">Initializes a new instance of <see cref="T:System.Fabric.FabricObjectClosedException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.Unknown" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException errorCode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="errorCode">
          <para><span data-ttu-id="943a4-120">Der Fehlercode, der der Ausnahme zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="943a4-120">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="943a4-121">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricObjectClosedException" /> -Klasse mit einem angegebenen Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="943a4-121">Initializes a new instance of <see cref="T:System.Fabric.FabricObjectClosedException" /> class with a specified error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : string -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="943a4-122">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="943a4-122">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="943a4-123">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricObjectClosedException" /> Klasse mit dem Fehlercode <see cref="F:System.Fabric.FabricErrorCode.Unknown" /> und einer angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="943a4-123">Initializes a new instance of <see cref="T:System.Fabric.FabricObjectClosedException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.Unknown" /> and a specified error message.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricObjectClosedException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
          <para><span data-ttu-id="943a4-124">Die <see cref="T:System.Runtime.Serialization.SerializationInfo" /> -Objekt mit serialisierten Objektdaten für die ausgelöste Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="943a4-124">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="943a4-125">Das <see cref="T:System.Runtime.Serialization.StreamingContext" />-Objekt, das die Kontextinformationen für die Quelle oder das Ziel enthält.</span><span class="sxs-lookup"><span data-stu-id="943a4-125">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="943a4-126">Der Kontextparameter ist für die zukünftige Verwendung reserviert und kann null sein.</span><span class="sxs-lookup"><span data-stu-id="943a4-126">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="943a4-127">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricObjectClosedException" /> Klasse aus einem serialisierten Objekt, mit einem angegebenen Kontext.</span><span class="sxs-lookup"><span data-stu-id="943a4-127">Initializes a new instance of <see cref="T:System.Fabric.FabricObjectClosedException" /> class from a serialized object data, with a specified context.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : string * Exception -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="943a4-128">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="943a4-128">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="943a4-129">Die Ausnahme, die die Ursache der aktuellen Ausnahme oder Null ist, wenn keine innere Ausnahme angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="943a4-129">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="943a4-130">Die <see cref="T:System.Exception" /> Klasse erhalten Sie weitere Informationen zur inneren Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="943a4-130">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="943a4-131">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricObjectClosedException" /> Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="943a4-131">Initializes a new instance of <see cref="T:System.Fabric.FabricObjectClosedException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (message, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="943a4-132">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="943a4-132">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="943a4-133">Der Fehlercode, der der Ausnahme zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="943a4-133">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="943a4-134">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricObjectClosedException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="943a4-134">Initializes a new instance of <see cref="T:System.Fabric.FabricObjectClosedException" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricObjectClosedException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (info, context, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="info">
          <para><span data-ttu-id="943a4-135">Die <see cref="T:System.Runtime.Serialization.SerializationInfo" /> -Objekt mit serialisierten Objektdaten für die ausgelöste Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="943a4-135">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="943a4-136">Das <see cref="T:System.Runtime.Serialization.StreamingContext" />-Objekt, das die Kontextinformationen für die Quelle oder das Ziel enthält.</span><span class="sxs-lookup"><span data-stu-id="943a4-136">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="943a4-137">Der Kontextparameter ist für die zukünftige Verwendung reserviert und kann null sein.</span><span class="sxs-lookup"><span data-stu-id="943a4-137">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="943a4-138">Der Fehlercode, der der Ausnahme zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="943a4-138">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="943a4-139">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricObjectClosedException" /> -Klasse aus einem serialisierten Objektdaten mit angegebenen Kontext und Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="943a4-139">Initializes a new instance of <see cref="T:System.Fabric.FabricObjectClosedException" /> class from a serialized object data, with specified context and error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (message, inner, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="943a4-140">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="943a4-140">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="943a4-141">Die Ausnahme, die die Ursache der aktuellen Ausnahme oder Null ist, wenn keine innere Ausnahme angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="943a4-141">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="943a4-142">Die <see cref="T:System.Exception" /> Klasse erhalten Sie weitere Informationen zur inneren Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="943a4-142">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="943a4-143">Der Fehlercode, der der Ausnahme zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="943a4-143">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="943a4-144">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricObjectClosedException" /> Nachricht Klasse mit einer angegebenen Fehlermeldung, der einen Verweis auf die innere Ausnahme, die die Ursache dieser Ausnahme und eine angegebene Fehlercode ist.</span><span class="sxs-lookup"><span data-stu-id="943a4-144">Initializes a new instance of <see cref="T:System.Fabric.FabricObjectClosedException" /> class with a specified error message, a reference to the inner exception that is the cause of this exception, and a specified error code.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>