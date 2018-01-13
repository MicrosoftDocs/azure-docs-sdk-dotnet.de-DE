<Type Name="StatelessService" FullName="Microsoft.ServiceFabric.Services.Runtime.StatelessService">
  <TypeSignature Language="C#" Value="public abstract class StatelessService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit StatelessService extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Runtime.StatelessService" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class StatelessService" />
  <TypeSignature Language="F#" Value="type StatelessService = class&#xA;    interface IStatelessUserServiceInstance" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2acc9-101">Stellt die Microsoft Service Fabric basierend zustandslose zuverlässigen Dienst-Basisklasse.</span><span class="sxs-lookup"><span data-stu-id="2acc9-101">Represents the Microsoft Service Fabric based stateless reliable service base class.</span></span> <span data-ttu-id="2acc9-102">Ableiten von dieser Klasse zum Implementieren eines Microsoft Service Fabric-basierten zustandslosen zuverlässige-Diensts.</span><span class="sxs-lookup"><span data-stu-id="2acc9-102">Derive from this class to implement a Microsoft Service Fabric based stateless reliable service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StatelessService (System.Fabric.StatelessServiceContext serviceContext);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.StatelessServiceContext serviceContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.#ctor(System.Fabric.StatelessServiceContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (serviceContext As StatelessServiceContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Runtime.StatelessService : System.Fabric.StatelessServiceContext -&gt; Microsoft.ServiceFabric.Services.Runtime.StatelessService" Usage="new Microsoft.ServiceFabric.Services.Runtime.StatelessService serviceContext" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.StatelessServiceContext" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
            <span data-ttu-id="2acc9-103">Ein <see cref="T:System.Fabric.StatelessServiceContext" /> , beschreibt der Kontext.</span><span class="sxs-lookup"><span data-stu-id="2acc9-103">A <see cref="T:System.Fabric.StatelessServiceContext" /> that describes the service context.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2acc9-104">Erstellt eine neue <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatelessService" />-Instanz.</span><span class="sxs-lookup"><span data-stu-id="2acc9-104">Creates a new <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatelessService" /> instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException" />
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public System.Fabric.StatelessServiceContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.StatelessServiceContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatelessService.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As StatelessServiceContext" />
      <MemberSignature Language="F#" Value="member this.Context : System.Fabric.StatelessServiceContext" Usage="Microsoft.ServiceFabric.Services.Runtime.StatelessService.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.StatelessServiceContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2acc9-105">Ruft den Dienstkontext, in denen diese statusfreien Dienst unter ab.</span><span class="sxs-lookup"><span data-stu-id="2acc9-105">Gets the service context that this stateless service is operating under.</span></span> <span data-ttu-id="2acc9-106">Es enthält Informationen wie InstanceId, PartitionId usw. ServiceName.</span><span class="sxs-lookup"><span data-stu-id="2acc9-106">It provides information like InstanceId, PartitionId, ServiceName etc.</span></span>
            </summary>
        <value>
            <span data-ttu-id="2acc9-107">Ein <see cref="T:System.Fabric.StatelessServiceContext" /> , beschreibt der Kontext.</span><span class="sxs-lookup"><span data-stu-id="2acc9-107">A <see cref="T:System.Fabric.StatelessServiceContext" /> that describes the service context.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceInstanceListeners">
      <MemberSignature Language="C#" Value="protected virtual System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt; CreateServiceInstanceListeners ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt; CreateServiceInstanceListeners() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.CreateServiceInstanceListeners" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateServiceInstanceListeners () As IEnumerable(Of ServiceInstanceListener)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceInstanceListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt;&#xA;override this.CreateServiceInstanceListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt;" Usage="statelessService.CreateServiceInstanceListeners " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.CreateServiceInstanceListeners</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2acc9-108">Überschreiben Sie diese Methode, um die kommunikationsüberwachungen für die Instanz angeben.</span><span class="sxs-lookup"><span data-stu-id="2acc9-108">Override this method to supply the communication listeners for the service instance.</span></span> <span data-ttu-id="2acc9-109">Die Endpunkte zurückgegeben, die für die Kommunikation des Listeners als JSON-Zeichenfolge der ListenerName gespeichert sind, wie Zeichenfolgenpaar Endpunkt {"Endpunkte": {"Listener1": "Endpoint1", "Listener2": "Endpoint2"...}}</span><span class="sxs-lookup"><span data-stu-id="2acc9-109">The endpoints returned by the communication listener's are stored as a JSON string of ListenerName, Endpoint string pairs like {"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</span></span>
            <span data-ttu-id="2acc9-110"><para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="2acc9-110"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns><span data-ttu-id="2acc9-111">Liste der ServiceInstanceListeners</span><span class="sxs-lookup"><span data-stu-id="2acc9-111">List of ServiceInstanceListeners</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAddresses">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; GetAddresses ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; GetAddresses() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.GetAddresses" />
      <MemberSignature Language="VB.NET" Value="Protected Function GetAddresses () As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.GetAddresses : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="statelessService.GetAddresses " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2acc9-112">Ruft die Liste der alle Adressen für diese Dienstinstanz als (ListenerName Endpunkt) Schlüssel-Wert-Paar.</span><span class="sxs-lookup"><span data-stu-id="2acc9-112">Gets the list of all the addresses for this service instance as (ListenerName, Endpoint) key-value pair.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2acc9-113">Ein <see cref="T:System.Collections.Generic.IReadOnlyDictionary`2" /> Liste der Adressen als (ListenerName Endpunkt) mit Schlüssel / Wert-Paar.</span><span class="sxs-lookup"><span data-stu-id="2acc9-113">An <see cref="T:System.Collections.Generic.IReadOnlyDictionary`2" /> containing list of addresses as (ListenerName, Endpoint) key-value pair.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected virtual void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="abstract member OnAbort : unit -&gt; unit&#xA;override this.OnAbort : unit -&gt; unit" Usage="statelessService.OnAbort " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.OnAbort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2acc9-114">Benachrichtigung, dass der Dienst abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="2acc9-114">Notification that the service is being aborted.</span></span>  <span data-ttu-id="2acc9-115">Coredispatcher möglicherweise wie der Abbruch nicht im Pfad Abbruch gewartet wird gleichzeitig mit der Ausführung dieser Methode wird ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="2acc9-115">RunAsync MAY be running concurrently with the execution of this method, as cancellation is not awaited on the abort path.</span></span>
            <span data-ttu-id="2acc9-116"><para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="2acc9-116"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.OnCloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statelessService.OnCloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.OnCloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="2acc9-117">Abbruchtoken, das zum Überwachen von abbruchanforderungen bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="2acc9-117">Cancellation token provided to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="2acc9-118">Diese Methode wird als abschließenden Schritt schließen Sie den Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="2acc9-118">This method is called as the final step of closing the service.</span></span>
            <span data-ttu-id="2acc9-119">Überschreiben Sie diese Methode, um benachrichtigt zu werden, dass für diese Instanz interne Komponenten schließen abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="2acc9-119">Override this method to be notified that Close has completed for this instance's internal components.</span></span>
            <span data-ttu-id="2acc9-120"><para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="2acc9-120"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns>
            <span data-ttu-id="2acc9-121">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2acc9-121">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnOpenAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnOpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnOpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.OnOpenAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnOpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnOpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statelessService.OnOpenAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.OnOpenAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="2acc9-122">Abbruchtoken, das zum Überwachen von abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="2acc9-122">Cancellation token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="2acc9-123">Diese Methode wird als abschließenden Schritt des Öffnens des Diensts aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="2acc9-123">This method is called as the final step of opening the service.</span></span>
            <span data-ttu-id="2acc9-124">Überschreiben Sie diese Methode, um benachrichtigt zu werden, die für diese Instanz interne Komponenten öffnen abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2acc9-124">Override this method to be notified that Open has completed for this instance's internal components.</span></span>
            <span data-ttu-id="2acc9-125"><para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="2acc9-125"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns>
            <span data-ttu-id="2acc9-126">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2acc9-126">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Partition">
      <MemberSignature Language="C#" Value="protected System.Fabric.IStatelessServicePartition Partition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.IStatelessServicePartition Partition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatelessService.Partition" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property Partition As IStatelessServicePartition" />
      <MemberSignature Language="F#" Value="member this.Partition : System.Fabric.IStatelessServicePartition" Usage="Microsoft.ServiceFabric.Services.Runtime.StatelessService.Partition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IStatelessServicePartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2acc9-127">Dienstpartition auf dem aktuellen Dienst Instanz gehört.</span><span class="sxs-lookup"><span data-stu-id="2acc9-127">Service partition to which current service instance belongs.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="2acc9-128">Ein <see cref="T:System.Fabric.IStatelessServicePartition" /> , der die Partition, zu der dieser Dienst Replikat gehört, darstellt.</span><span class="sxs-lookup"><span data-stu-id="2acc9-128">An <see cref="T:System.Fabric.IStatelessServicePartition" /> that represents the partition to which this service replica belongs.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task RunAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task RunAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statelessService.RunAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.RunAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="2acc9-129">Abbruchtoken, das zum Überwachen von abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="2acc9-129">Cancellation token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="2acc9-130">Dienste, die einen Hintergrundtask aus, die ausgeführt wird, wenn der Dienst hochgefahren, zu implementieren möchten, sollten diese Methode mit ihrer Logik überschreiben.</span><span class="sxs-lookup"><span data-stu-id="2acc9-130">Services that want to implement a background task, which runs when the service comes up, should override this method with their logic.</span></span>
            <span data-ttu-id="2acc9-131"><para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="2acc9-131"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns>
            <span data-ttu-id="2acc9-132">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2acc9-132">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="2acc9-133">Vergewissern Sie sich überschreiben, gelten folgende Richtlinien <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />: <list type="bullet"> <item> <description> stellen Sie sicher, dass <paramref name="cancellationToken" /> übergeben <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> berücksichtigt wird und nachdem es signalisiert worden ist, <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> als ordnungsgemäß beendet So bald wie möglich. Bitte beachten Sie, dass bei <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> hat die vorgesehene Arbeit, er muss nicht warten <paramref name="cancellationToken" /> auf die Signalisierung und ordnungsgemäß zurückgeben kann. </description></item><item><description>Service Fabric-Laufzeit behandelt nicht alle Escapezeichen aus Ausnahme(n) <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />. Wenn eine nicht behandelte Ausnahme aus Escapevorgang <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />, dauert Service Fabric-Laufzeit folgende Aktionen aus: <list type="bullet"> <item> <description> Wenn eine <see cref="T:System.Fabric.FabricException" /> (oder eines seiner abgeleiteten Ausnahme) schützt aus <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />, Service Fabric Common Language Runtime löscht diese Instanz und eine neue Instanz erstellt werden. Eine Warnung Health werden im Service Fabric-Explorer enthält Informationen zu nicht behandelte Ausnahme angezeigt werden. </description></item><item><description>Wenn ein <see cref="T:System.OperationCanceledException" /> schützt aus <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> und Service Fabric Runtime Abbruch angefordert hat, durch Signalisieren <paramref name="cancellationToken" /> übergeben <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />, Service Fabric Runtime diese Ausnahme behandelt und betrachtet er als ordnungsgemäße Beendigung von <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />. </description></item><item><description>Wenn ein <see cref="T:System.OperationCanceledException" /> schützt aus <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> und Service Fabric-Laufzeit nicht Abbruch durch Signalisieren angefordert hat <paramref name="cancellationToken" /> übergeben <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />, der Prozess, der dieser Dienstinstanz hostet unten geschaltet wird. Dies wirkt sich alle Dienstinstanzen, die vom gleichen Prozess gehostet werden. Die Details von nicht behandelten Ausnahmen können in der Windows-Ereignisanzeige angezeigt werden. </description></item><item><description>Wenn eine Ausnahme eines anderen Typs von Escapevorgang <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> und klicken Sie dann der Prozess, der dieser Dienstinstanz hostet heruntergefahren wird. Dies wirkt sich alle Dienstinstanzen, die vom gleichen Prozess gehostet werden. Die Details von nicht behandelten Ausnahmen können in der Windows-Ereignisanzeige angezeigt werden. </description></item></list></description></item></list><para>Wegen eines Fehlers beim entsprechen, diese Richtlinien können dazu führen, dass ein Failover, Neukonfiguration oder Aktualisierung des Diensts bei hängen bleiben und Verfügbarkeit Ihres Diensts auswirken können.</para></span><span class="sxs-lookup"><span data-stu-id="2acc9-133">Please ensure you follow these guidelines when overriding <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />: <list type="bullet"><item><description> Make sure <paramref name="cancellationToken" /> passed to <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> is honored and once it has been signaled, <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> exits gracefully as soon as possible. Please note that if <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> has finished its intended work, it does not need to wait for <paramref name="cancellationToken" /> to be signaled and can return gracefully. </description></item><item><description> Service Fabric runtime does not handle all exception(s) escaping from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />. If an unhandled exception escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />, then Service Fabric runtime takes following action(s): <list type="bullet"><item><description> If a <see cref="T:System.Fabric.FabricException" /> (or one of its derived exception) escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />, Service Fabric runtime will drop this service instance and a new instance will be created. A health warning will be appear in Service Fabric Explorer containing details about unhandled exception. </description></item><item><description> If an <see cref="T:System.OperationCanceledException" /> escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> and Service Fabric runtime has requested cancellation by signaling <paramref name="cancellationToken" /> passed to <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />, Service Fabric runtime handles this exception and considers it as graceful completion of <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />. </description></item><item><description> If an <see cref="T:System.OperationCanceledException" /> escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> and Service Fabric runtime has NOT requested cancellation by signaling <paramref name="cancellationToken" /> passed to <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />, the process that is hosting this service instance is brought down. This will impact all other service instances that are hosted by the same process. The details about unhandled exceptions can be viewed in Windows Event Viewer. </description></item><item><description> If an exception of any other type escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> then the process that is hosting this service instance is brought down. This will impact all other service instances that are hosted by the same process. The details about unhandled exceptions can be viewed in Windows Event Viewer. </description></item></list></description></item></list><para> Failing to conform to these guidelines can cause fail-over, reconfiguration or upgrade of your service to get stuck and can impact availability of your service. </para></span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>