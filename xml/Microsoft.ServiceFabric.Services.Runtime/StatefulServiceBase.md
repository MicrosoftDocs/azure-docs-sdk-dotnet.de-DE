<Type Name="StatefulServiceBase" FullName="Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase">
  <TypeSignature Language="C#" Value="public abstract class StatefulServiceBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit StatefulServiceBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class StatefulServiceBase" />
  <TypeSignature Language="F#" Value="type StatefulServiceBase = class&#xA;    interface IStatefulUserServiceReplica" />
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
            <span data-ttu-id="b530c-101">Stellt die Basisklasse für statusbehaftete zuverlässige Dienst Microsoft Service Fabric-basiert.</span><span class="sxs-lookup"><span data-stu-id="b530c-101">Represents the base class for Microsoft Service Fabric based stateful reliable service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StatefulServiceBase (System.Fabric.StatefulServiceContext serviceContext, Microsoft.ServiceFabric.Data.IStateProviderReplica2 stateProviderReplica);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.StatefulServiceContext serviceContext, class Microsoft.ServiceFabric.Data.IStateProviderReplica2 stateProviderReplica) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.#ctor(System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Data.IStateProviderReplica2)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (serviceContext As StatefulServiceContext, stateProviderReplica As IStateProviderReplica2)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase : System.Fabric.StatefulServiceContext * Microsoft.ServiceFabric.Data.IStateProviderReplica2 -&gt; Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" Usage="new Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase (serviceContext, stateProviderReplica)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.StatefulServiceContext" />
        <Parameter Name="stateProviderReplica" Type="Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
            <span data-ttu-id="b530c-102">Ein <see cref="T:System.Fabric.StatefulServiceContext" /> beschreibt den Dienstkontext, der er Informationen wie Replikat-ID, Partitions-ID und Name des Diensts bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="b530c-102">A <see cref="T:System.Fabric.StatefulServiceContext" /> describes the service context, which it provides information like replica ID, partition ID, and service name.</span></span>
            </param>
        <param name="stateProviderReplica">
            <span data-ttu-id="b530c-103">Ein <see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica2" /> einem zuverlässigen Zustand Anbieter Replikat darstellt.</span><span class="sxs-lookup"><span data-stu-id="b530c-103">A <see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica2" /> represents a reliable state provider replica.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b530c-104">Erstellt einen neuen zustandsbehafteten Dienst.</span><span class="sxs-lookup"><span data-stu-id="b530c-104">Creates a new stateful service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException" />
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Microsoft.ServiceFabric.Data.BackupDescription backupDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupDescription backupDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.BackupAsync(Microsoft.ServiceFabric.Data.BackupDescription)" />
      <MemberSignature Language="F#" Value="member this.BackupAsync : Microsoft.ServiceFabric.Data.BackupDescription -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.BackupAsync backupDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDescription" Type="Microsoft.ServiceFabric.Data.BackupDescription" />
      </Parameters>
      <Docs>
        <param name="backupDescription">
            <span data-ttu-id="b530c-105">Ein <see cref="T:Microsoft.ServiceFabric.Data.BackupDescription" /> , beschreibt die Anforderung für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="b530c-105">A <see cref="T:Microsoft.ServiceFabric.Data.BackupDescription" /> describing the backup request.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b530c-106">Führt eine Sicherung alle zuverlässige Status, die von diesem verwaltet <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />.</span><span class="sxs-lookup"><span data-stu-id="b530c-106">Performs a backup of all reliable state managed by this <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />.</span></span>
            </summary>
        <returns><span data-ttu-id="b530c-107">Eine Aufgabe, die den asynchronen backup-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b530c-107">Task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Microsoft.ServiceFabric.Data.BackupDescription backupDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupDescription backupDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.BackupAsync(Microsoft.ServiceFabric.Data.BackupDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.BackupAsync : Microsoft.ServiceFabric.Data.BackupDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.BackupAsync (backupDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDescription" Type="Microsoft.ServiceFabric.Data.BackupDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupDescription"><span data-ttu-id="b530c-108">Ein <see cref="T:Microsoft.ServiceFabric.Data.BackupDescription" /> , beschreibt die Anforderung für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="b530c-108">A <see cref="T:Microsoft.ServiceFabric.Data.BackupDescription" /> describing the backup request.</span></span></param>
        <param name="timeout"><span data-ttu-id="b530c-109">Das Timeout für diesen Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b530c-109">The timeout for this operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b530c-110">Das Abbruchtoken, das dient zum Überwachen von abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="b530c-110">The cancellation token is used to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b530c-111">Führt eine Sicherung alle zuverlässige Status, die von diesem verwaltet <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />.</span><span class="sxs-lookup"><span data-stu-id="b530c-111">Performs a backup of all reliable state managed by this <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />.</span></span>
            </summary>
        <returns><span data-ttu-id="b530c-112">Eine Aufgabe, die den asynchronen backup-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b530c-112">Task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="b530c-113">Boolescher Wert zurückgegeben, die für die BackupCallback Geben Sie an, ob der Dienst konnte erfolgreich den Sicherungsordner in einem externen Speicherort zu verschieben.</span><span class="sxs-lookup"><span data-stu-id="b530c-113">Boolean returned by the backupCallback indicate whether the service was able to successfully move the backup folder to an external location.</span></span>
            <span data-ttu-id="b530c-114">Wenn "false" zurückgegeben wird, löst BackupAsync InvalidOperationException aus der entsprechenden Fehlermeldung BackupCallback "false" zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="b530c-114">If false is returned, BackupAsync throws InvalidOperationException with the relevant message indicating backupCallback returned false.</span></span>
            <span data-ttu-id="b530c-115">Darüber hinaus wird Sicherung als fehlgeschlagen markiert.</span><span class="sxs-lookup"><span data-stu-id="b530c-115">Also, backup will be marked as unsuccessful.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public System.Fabric.StatefulServiceContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.StatefulServiceContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As StatefulServiceContext" />
      <MemberSignature Language="F#" Value="member this.Context : System.Fabric.StatefulServiceContext" Usage="Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.StatefulServiceContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b530c-116">Ruft den Dienstkontext, in denen dieses zustandsbehafteten Dienst unter ab.</span><span class="sxs-lookup"><span data-stu-id="b530c-116">Gets the service context that this stateful service is operating under.</span></span>
            <span data-ttu-id="b530c-117">Es enthält Informationen wie die Replikat-ID, Partitions-ID, Name des Diensts usw.</span><span class="sxs-lookup"><span data-stu-id="b530c-117">It provides information like replica ID, partition ID, service name etc.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b530c-118">Ein <see cref="T:System.Fabric.StatefulServiceContext" /> beschreibt den Dienstkontext, der er Informationen wie Replikat-ID, Partitions-ID und Name des Diensts bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="b530c-118">A <see cref="T:System.Fabric.StatefulServiceContext" /> describes the service context, which it provides information like replica ID, partition ID, and service name.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceReplicaListeners">
      <MemberSignature Language="C#" Value="protected virtual System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; CreateServiceReplicaListeners ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; CreateServiceReplicaListeners() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.CreateServiceReplicaListeners" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateServiceReplicaListeners () As IEnumerable(Of ServiceReplicaListener)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceReplicaListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;&#xA;override this.CreateServiceReplicaListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;" Usage="statefulServiceBase.CreateServiceReplicaListeners " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.CreateServiceReplicaListeners</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b530c-119">Überschreiben Sie diese Methode, um die kommunikationsüberwachungen für das Replikat Service angeben.</span><span class="sxs-lookup"><span data-stu-id="b530c-119">Override this method to supply the communication listeners for the service replica.</span></span> <span data-ttu-id="b530c-120">Die Endpunkte, die vom Listener Kommunikation zurückgegeben werden als JSON-Zeichenfolge der ListenerName, Endpunkt Zeichenfolgenpaare wie gespeichert.</span><span class="sxs-lookup"><span data-stu-id="b530c-120">The endpoints returned by the communication listener are stored as a JSON string of ListenerName, Endpoint string pairs like</span></span> 
            <span data-ttu-id="b530c-121"><code>{"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</code><para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="b530c-121"><code>{"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</code><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns><span data-ttu-id="b530c-122">Liste der<see cref="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener" /></span><span class="sxs-lookup"><span data-stu-id="b530c-122">List of <see cref="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener" /></span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAddresses">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; GetAddresses ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; GetAddresses() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.GetAddresses" />
      <MemberSignature Language="VB.NET" Value="Protected Function GetAddresses () As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.GetAddresses : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="statefulServiceBase.GetAddresses " />
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
            <span data-ttu-id="b530c-123">Ruft die Liste der alle Adressen für diese dienstreplikats als (ListenerName Endpunkt) Schlüssel-Wert-Paar.</span><span class="sxs-lookup"><span data-stu-id="b530c-123">Gets the list of all the addresses for this service replica as (ListenerName, Endpoint) key-value pair.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b530c-124">Ein <see cref="T:System.Collections.Generic.IReadOnlyDictionary`2" /> Liste der Adressen als (ListenerName Endpunkt) mit Schlüssel / Wert-Paar.</span><span class="sxs-lookup"><span data-stu-id="b530c-124">An <see cref="T:System.Collections.Generic.IReadOnlyDictionary`2" /> containing list of addresses as (ListenerName, Endpoint) key-value pair.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected virtual void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="abstract member OnAbort : unit -&gt; unit&#xA;override this.OnAbort : unit -&gt; unit" Usage="statefulServiceBase.OnAbort " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.OnAbort</InterfaceMember>
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
            <span data-ttu-id="b530c-125">Die Benachrichtigung, dass der Dienst abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="b530c-125">The notification that the service is being aborted.</span></span> <span data-ttu-id="b530c-126">Coredispatcher möglicherweise wie der Abbruch nicht im Pfad Abbruch gewartet wird gleichzeitig mit der Ausführung dieser Methode wird ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="b530c-126">RunAsync MAY be running concurrently with the execution of this method, as cancellation is not awaited on the abort path.</span></span> 
            <span data-ttu-id="b530c-127"><para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="b530c-127"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnChangeRoleAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.OnChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole"><span data-ttu-id="b530c-128">Neue <see cref="T:System.Fabric.ReplicaRole" /> für dieses Replikat Dienst.</span><span class="sxs-lookup"><span data-stu-id="b530c-128">New <see cref="T:System.Fabric.ReplicaRole" /> for this service replica.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b530c-129">Abbruchtoken, das zum Überwachen von abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="b530c-129">Cancellation token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b530c-130">Diese Methode wird aufgerufen, wenn die Rolle des Replikats ändert, und es ist der letzte Schritt vor dem Abschluss <see cref="M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="b530c-130">This method is called when role of the replica is changing and it is the final step before completing <see cref="M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />.</span></span>
            <span data-ttu-id="b530c-131">Überschreiben Sie diese Methode, um benachrichtigt zu werden, dass ChangeRole für dieses Replikat interne Komponenten abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="b530c-131">Override this method to be notified that ChangeRole has completed for this replica's internal components.</span></span>
            <span data-ttu-id="b530c-132"><para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="b530c-132"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns>
            <span data-ttu-id="b530c-133">Ein <see cref="T:System.Threading.Tasks.Task" /> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b530c-133">A <see cref="T:System.Threading.Tasks.Task" /> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnCloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.OnCloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.OnCloseAsync(System.Threading.CancellationToken)</InterfaceMember>
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
        <param name="cancellationToken"><span data-ttu-id="b530c-134">Abbruchtoken, das zum Überwachen von abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="b530c-134">Cancellation token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b530c-135">Diese Methode wird als abschließenden Schritt schließen Sie den Dienst ordnungsgemäß aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="b530c-135">This method is called as the final step of closing the service gracefully.</span></span>
            <span data-ttu-id="b530c-136">Überschreiben Sie diese Methode, um benachrichtigt zu werden, dass für dieses Replikat interne Komponenten schließen abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="b530c-136">Override this method to be notified that Close has completed for this replica's internal components.</span></span>
            <span data-ttu-id="b530c-137"><para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="b530c-137"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns>
            <span data-ttu-id="b530c-138">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b530c-138">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;bool&gt; OnDataLossAsync (Microsoft.ServiceFabric.Data.RestoreContext restoreCtx, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; OnDataLossAsync(valuetype Microsoft.ServiceFabric.Data.RestoreContext restoreCtx, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnDataLossAsync(Microsoft.ServiceFabric.Data.RestoreContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDataLossAsync : Microsoft.ServiceFabric.Data.RestoreContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.OnDataLossAsync : Microsoft.ServiceFabric.Data.RestoreContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="statefulServiceBase.OnDataLossAsync (restoreCtx, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restoreCtx" Type="Microsoft.ServiceFabric.Data.RestoreContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="restoreCtx">
            <span data-ttu-id="b530c-139">Ein <see cref="T:Microsoft.ServiceFabric.Data.RestoreContext" /> zum Wiederherstellen des Diensts verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="b530c-139">A <see cref="T:Microsoft.ServiceFabric.Data.RestoreContext" /> to be used to restore the service.</span></span>
            </param>
        <param name="cancellationToken">
          <span data-ttu-id="b530c-140"><see cref="T:System.Threading.CancellationToken" />zum Überwachen von abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="b530c-140"><see cref="T:System.Threading.CancellationToken" /> to monitor for cancellation requests.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b530c-141">Diese Methode wird während der potenziellen Datenverlust aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="b530c-141">This method is called during suspected data loss.</span></span> <span data-ttu-id="b530c-142">Sie können diese Methode, um den Dienst bei einem Datenverlust wiederherzustellen überschreiben.</span><span class="sxs-lookup"><span data-stu-id="b530c-142">You can override this method to restore the service in case of data loss.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b530c-143">Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b530c-143">A Task that represents the asynchronous restore operation.</span></span>
            <span data-ttu-id="b530c-144">"True" gibt an, dass der Zustand wiederhergestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="b530c-144">True indicates that the state has been restored.</span></span>
            <span data-ttu-id="b530c-145">False gibt an, dass das Replikat Zustand nicht geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="b530c-145">False indicates that the replica's state has not been modified.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnOpenAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnOpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnOpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnOpenAsync(System.Fabric.ReplicaOpenMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnOpenAsync : System.Fabric.ReplicaOpenMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnOpenAsync : System.Fabric.ReplicaOpenMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.OnOpenAsync (openMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.OnOpenAsync(System.Fabric.ReplicaOpenMode,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode">
          <span data-ttu-id="b530c-146"><see cref="T:System.Fabric.ReplicaOpenMode" />für dieses Replikat Dienst.</span><span class="sxs-lookup"><span data-stu-id="b530c-146"><see cref="T:System.Fabric.ReplicaOpenMode" /> for this service replica.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b530c-147">Abbruchtoken, das zum Überwachen von abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="b530c-147">Cancellation token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b530c-148">Diese Methode wird aufgerufen, wenn das Replikat wurde geöffnet, und es der letzte Schritt ist des Öffnens des Diensts.</span><span class="sxs-lookup"><span data-stu-id="b530c-148">This method is called when the replica is being opened and it is the final step of opening the service.</span></span>
            <span data-ttu-id="b530c-149">Überschreiben Sie diese Methode, um benachrichtigt zu werden, dass für dieses Replikat interne Komponenten öffnen abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="b530c-149">Override this method to be notified that Open has completed for this replica's internal components.</span></span>
            <span data-ttu-id="b530c-150"><para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="b530c-150"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns>
            <span data-ttu-id="b530c-151">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b530c-151">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnRestoreCompletedAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnRestoreCompletedAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnRestoreCompletedAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnRestoreCompletedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnRestoreCompletedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.OnRestoreCompletedAsync cancellationToken" />
      <MemberType>Method</MemberType>
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
        <param name="cancellationToken">
          <span data-ttu-id="b530c-152"><see cref="T:System.Threading.CancellationToken" />zum Überwachen von abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="b530c-152"><see cref="T:System.Threading.CancellationToken" /> to monitor for cancellation requests.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b530c-153">Diese Methode wird aufgerufen, wenn der Replikatstatus über den Service Wiederherstellung erfolgreich wiederhergestellt wurde</span><span class="sxs-lookup"><span data-stu-id="b530c-153">This method is called when replica's state has been restored successfully via the Backup Restore service</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b530c-154">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b530c-154">A Task that represents the asynchronous operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Partition">
      <MemberSignature Language="C#" Value="protected System.Fabric.IStatefulServicePartition Partition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.IStatefulServicePartition Partition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.Partition" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property Partition As IStatefulServicePartition" />
      <MemberSignature Language="F#" Value="member this.Partition : System.Fabric.IStatefulServicePartition" Usage="Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.Partition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IStatefulServicePartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b530c-155">Die Dienstpartition, welche aktuellen Dienst Replikat gehört.</span><span class="sxs-lookup"><span data-stu-id="b530c-155">The service partition to which current service replica belongs.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="b530c-156">Ein <see cref="T:System.Fabric.IStatefulServicePartition" /> , der die Partition, zu der dieser Dienst Replikat gehört, darstellt.</span><span class="sxs-lookup"><span data-stu-id="b530c-156">An <see cref="T:System.Fabric.IStatefulServicePartition" /> that represents the partition to which this service replica belongs.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task RunAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task RunAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.RunAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.RunAsync(System.Threading.CancellationToken)</InterfaceMember>
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
        <param name="cancellationToken"><span data-ttu-id="b530c-157">Abbruchtoken, das zum Überwachen von abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="b530c-157">Cancellation token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b530c-158">Diese Methode wird als eine Verarbeitungsschleife implementiert und wird nur aufgerufen werden, wenn das Replikat Primär mit Schreibstatus ist.</span><span class="sxs-lookup"><span data-stu-id="b530c-158">This method is implemented as a processing loop and will only be called when the replica is primary with write status.</span></span>
            <span data-ttu-id="b530c-159">Überschreiben Sie diese Methode mit der Anwendungslogik.</span><span class="sxs-lookup"><span data-stu-id="b530c-159">Override this method with the application logic.</span></span> 
            <span data-ttu-id="b530c-160"><para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="b530c-160"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns>
            <span data-ttu-id="b530c-161">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b530c-161">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="b530c-162">Vergewissern Sie sich überschreiben, gelten folgende Richtlinien <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />: <list type="bullet"> <item> <description> stellen Sie sicher, dass <paramref name="cancellationToken" /> übergeben <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> berücksichtigt wird und nachdem es signalisiert worden ist, <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> als ordnungsgemäß beendet So bald wie möglich. Bitte beachten Sie, dass bei <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> hat die vorgesehene Arbeit, er muss nicht warten <paramref name="cancellationToken" /> auf die Signalisierung und ordnungsgemäß zurückgeben kann. </description></item><item><description>Service Fabric-Laufzeit behandelt nicht alle Escapezeichen aus Ausnahme(n) <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />. Wenn eine nicht behandelte Ausnahme aus Escapevorgang <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />, dauert Service Fabric-Laufzeit folgende Aktionen aus: <list type="bullet"> <item> <description> Wenn eine <see cref="T:System.Fabric.FabricException" /> (oder eines seiner abgeleiteten Ausnahme) schützt aus <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />, Service Fabric Common Language Runtime wird dieses Replikat Dienst neu gestartet. Eine Warnung Health werden im Service Fabric-Explorer enthält Informationen zu nicht behandelte Ausnahme angezeigt werden. </description></item><item><description>Wenn ein <see cref="T:System.OperationCanceledException" /> schützt aus <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> und Service Fabric Runtime Abbruch angefordert hat, durch Signalisieren <paramref name="cancellationToken" /> übergeben <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />, Service Fabric Runtime diese Ausnahme behandelt und betrachtet er als ordnungsgemäße Beendigung von <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />. </description></item><item><description>Wenn ein <see cref="T:System.OperationCanceledException" /> schützt aus <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> und Service Fabric-Laufzeit nicht Abbruch durch Signalisieren angefordert hat <paramref name="cancellationToken" /> übergeben <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />, wird der Prozess, der diesem Dienst Replikat gehostet wird nach unten versetzt. Dadurch wird anderen dienstreplikate beeinträchtigt, die vom gleichen Prozess gehostet werden. Die Details von nicht behandelten Ausnahmen können in der Windows-Ereignisanzeige angezeigt werden. </description></item><item><description>Wenn eine Ausnahme eines anderen Typs von Escapevorgang <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> und klicken Sie dann der Prozess, der diesem Dienst Replikat gehostet wird heruntergefahren wird. Dadurch wird anderen dienstreplikate beeinträchtigt, die vom gleichen Prozess gehostet werden. Die Details von nicht behandelten Ausnahmen können in der Windows-Ereignisanzeige angezeigt werden. </description></item></list></description></item></list><para>Wegen eines Fehlers beim entsprechen, diese Richtlinien können dazu führen, dass ein Failover, Neukonfiguration oder Aktualisierung des Diensts bei hängen bleiben und Verfügbarkeit Ihres Diensts auswirken können.</para></span><span class="sxs-lookup"><span data-stu-id="b530c-162">Please ensure you follow these guidelines when overriding <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />: <list type="bullet"><item><description> Make sure <paramref name="cancellationToken" /> passed to <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> is honored and once it has been signaled, <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> exits gracefully as soon as possible. Please note that if <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> has finished its intended work, it does not need to wait for <paramref name="cancellationToken" /> to be signaled and can return gracefully. </description></item><item><description> Service Fabric runtime does not handle all exception(s) escaping from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />. If an unhandled exception escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />, then Service Fabric runtime takes following action(s): <list type="bullet"><item><description> If a <see cref="T:System.Fabric.FabricException" /> (or one of its derived exception) escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />, Service Fabric runtime will restart this service replica. A health warning will be appear in Service Fabric Explorer containing details about unhandled exception. </description></item><item><description> If an <see cref="T:System.OperationCanceledException" /> escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> and Service Fabric runtime has requested cancellation by signaling <paramref name="cancellationToken" /> passed to <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />, Service Fabric runtime handles this exception and considers it as graceful completion of <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />. </description></item><item><description> If an <see cref="T:System.OperationCanceledException" /> escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> and Service Fabric runtime has NOT requested cancellation by signaling <paramref name="cancellationToken" /> passed to <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />, the process that is hosting this service replica is brought down. This will impact all other service replicas that are hosted by the same process. The details about unhandled exceptions can be viewed in Windows Event Viewer. </description></item><item><description> If an exception of any other type escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> then the process that is hosting this service replica is brought down. This will impact all other service replicas that are hosted by the same process. The details about unhandled exceptions can be viewed in Windows Event Viewer. </description></item></list></description></item></list><para> Failing to conform to these guidelines can cause fail-over, reconfiguration or upgrade of your service to get stuck and can impact availability of your service. </para></span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>