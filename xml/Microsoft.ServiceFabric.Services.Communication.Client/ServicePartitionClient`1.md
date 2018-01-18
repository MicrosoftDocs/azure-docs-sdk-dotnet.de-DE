<Type Name="ServicePartitionClient&lt;TCommunicationClient&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;TCommunicationClient&gt;">
  <TypeSignature Language="C#" Value="public class ServicePartitionClient&lt;TCommunicationClient&gt; : Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient&lt;TCommunicationClient&gt; where TCommunicationClient : ICommunicationClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServicePartitionClient`1&lt;(class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient) TCommunicationClient&gt; extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1&lt;!TCommunicationClient&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1" />
  <TypeSignature Language="VB.NET" Value="Public Class ServicePartitionClient(Of TCommunicationClient)&#xA;Implements IServicePartitionClient(Of TCommunicationClient)" />
  <TypeSignature Language="F#" Value="type ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; ICommunicationClient)&gt; = class&#xA;    interface IServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; ICommunicationClient)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TCommunicationClient">
      <Constraints>
        <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient&lt;TCommunicationClient&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TCommunicationClient"><span data-ttu-id="7b529-101">Kommunikation-Clienttyp</span><span class="sxs-lookup"><span data-stu-id="7b529-101">type of Communication client</span></span></typeparam>
    <summary>
            <span data-ttu-id="7b529-102">Gibt eine Instanz der Kommunikation zwischen Client, der kommunizieren kann mit den Replikaten einer bestimmten Partition an.</span><span class="sxs-lookup"><span data-stu-id="7b529-102">Specifies an instance of the communication client that can communicate with the replicas of a particular partition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionClient (Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt; communicationClientFactory, Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey = null, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector = Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica, string listenerName = null, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1&lt;!TCommunicationClient&gt; communicationClientFactory, class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.#ctor(Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory{`0},System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; : Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; * Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; (communicationClientFactory, serviceUri, partitionKey, targetReplicaSelector, listenerName, retrySettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="communicationClientFactory" Type="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt;" />
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="targetReplicaSelector" Type="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="communicationClientFactory"><span data-ttu-id="7b529-103">Client-Kommunikation-factory</span><span class="sxs-lookup"><span data-stu-id="7b529-103">Communication client factory</span></span></param>
        <param name="serviceUri"><span data-ttu-id="7b529-104">Name des Diensts</span><span class="sxs-lookup"><span data-stu-id="7b529-104">Name of the service</span></span></param>
        <param name="partitionKey"><span data-ttu-id="7b529-105">Der Partitionsschlüssel verwendet, um die Partition in den Dienst zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="7b529-105">The partition key used to identify the partition within the service.</span></span></param>
        <param name="targetReplicaSelector"><span data-ttu-id="7b529-106">Informationen zum Replikat</span><span class="sxs-lookup"><span data-stu-id="7b529-106">Target replica information</span></span></param>
        <param name="listenerName"><span data-ttu-id="7b529-107">Listener im Replikat, zu dem der Client eine eine Verbindung herstellen soll</span><span class="sxs-lookup"><span data-stu-id="7b529-107">Listener in the replica to which the client should connect to</span></span></param>
        <param name="retrySettings"><span data-ttu-id="7b529-108">Wiederholungsrichtlinie für Ausnahmen, die während der Kommunikation angezeigt</span><span class="sxs-lookup"><span data-stu-id="7b529-108">Retry policy for exceptions seen during communication</span></span></param>
        <summary>
            <span data-ttu-id="7b529-109">Instanziiert einen Dienstclient für die Partition, der die angegebene Client-Factory verwendet, erstellen Sie einen Client zum Kommunizieren mit den Dienstendpunkt, der durch den Dienst-Uri, Partitionkey, Replikat und Listener Argumente identifiziert verwendet.</span><span class="sxs-lookup"><span data-stu-id="7b529-109">Instantiates a service partition client that uses the specified communication client factory to create a client to talk to the service endpoint identified by the service uri, partitionkey, replica and listener arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Factory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt; Factory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1&lt;!TCommunicationClient&gt; Factory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.Factory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Factory As ICommunicationClientFactory(Of TCommunicationClient)" />
      <MemberSignature Language="F#" Value="member this.Factory : Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.Factory" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.Factory</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7b529-110">Ruft die Kommunikation zwischen Client Factory ab</span><span class="sxs-lookup"><span data-stu-id="7b529-110">Gets the communication client factory</span></span>
            </summary>
        <value><span data-ttu-id="7b529-111">Client-Kommunikation-factory</span><span class="sxs-lookup"><span data-stu-id="7b529-111">Communication client factory</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeWithRetry">
      <MemberSignature Language="C#" Value="public void InvokeWithRetry (Action&lt;TCommunicationClient&gt; func, params Type[] doNotRetryExceptionTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void InvokeWithRetry(class System.Action`1&lt;!TCommunicationClient&gt; func, class System.Type[] doNotRetryExceptionTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.InvokeWithRetry(System.Action{`0},System.Type[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub InvokeWithRetry (func As Action(Of TCommunicationClient), ParamArray doNotRetryExceptionTypes As Type())" />
      <MemberSignature Language="F#" Value="member this.InvokeWithRetry : Action&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; * Type[] -&gt; unit" Usage="servicePartitionClient.InvokeWithRetry (func, doNotRetryExceptionTypes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="func" Type="System.Action&lt;TCommunicationClient&gt;" />
        <Parameter Name="doNotRetryExceptionTypes" Type="System.Type[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="func"><span data-ttu-id="7b529-112">Die aufgerufene Funktion</span><span class="sxs-lookup"><span data-stu-id="7b529-112">Function being invoked</span></span></param>
        <param name="doNotRetryExceptionTypes"><span data-ttu-id="7b529-113">Ausnahmen, die für die der Dienstclient für die Partition nicht den wiederholen soll</span><span class="sxs-lookup"><span data-stu-id="7b529-113">Exceptions for which the service partition client should not retry</span></span></param>
        <summary>
            <span data-ttu-id="7b529-114">Ruft die angegebene Funktion auf, und wiederholen Sie dann für andere als die Ausnahmen in der DoNotRetryExceptionTypes ausgelösten Ausnahmen.</span><span class="sxs-lookup"><span data-stu-id="7b529-114">Invokes the given Function, retrying for exceptions thrown other than the exceptions in the doNotRetryExceptionTypes.</span></span>
            <span data-ttu-id="7b529-115">Ausnahmen, die nicht in DoNotRetryExceptionTypes enthalten sind, steuert CommunicationClientFactorys ReportOperationExceptionAsync()-Methode, wenn die Ausnahme oder nicht wiederholt werden soll.</span><span class="sxs-lookup"><span data-stu-id="7b529-115">For exceptions that are not in doNotRetryExceptionTypes, CommunicationClientFactory's ReportOperationExceptionAsync() method controls if the exception should be retried or not.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeWithRetry&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public TResult InvokeWithRetry&lt;TResult&gt; (Func&lt;TCommunicationClient,TResult&gt; func, params Type[] doNotRetryExceptionTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!TResult InvokeWithRetry&lt;TResult&gt;(class System.Func`2&lt;!TCommunicationClient, !!TResult&gt; func, class System.Type[] doNotRetryExceptionTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.InvokeWithRetry``1(System.Func{`0,``0},System.Type[])" />
      <MemberSignature Language="VB.NET" Value="Public Function InvokeWithRetry(Of TResult) (func As Func(Of TCommunicationClient, TResult), ParamArray doNotRetryExceptionTypes As Type()) As TResult" />
      <MemberSignature Language="F#" Value="member this.InvokeWithRetry : Func&lt;'CommunicationClient, 'Result (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; * Type[] -&gt; 'Result" Usage="servicePartitionClient.InvokeWithRetry (func, doNotRetryExceptionTypes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="func" Type="System.Func&lt;TCommunicationClient,TResult&gt;" />
        <Parameter Name="doNotRetryExceptionTypes" Type="System.Type[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="7b529-116">Führen Sie von der aufgerufenen Funktion</span><span class="sxs-lookup"><span data-stu-id="7b529-116">Result from the function being invoked</span></span></typeparam>
        <param name="func"><span data-ttu-id="7b529-117">Die aufgerufene Funktion</span><span class="sxs-lookup"><span data-stu-id="7b529-117">Function being invoked</span></span></param>
        <param name="doNotRetryExceptionTypes"><span data-ttu-id="7b529-118">Ausnahmen, die für die der Dienstclient für die Partition nicht den wiederholen soll</span><span class="sxs-lookup"><span data-stu-id="7b529-118">Exceptions for which the service partition client should not retry</span></span></param>
        <summary>
            <span data-ttu-id="7b529-119">Ruft die angegebene Funktion auf, und wiederholen Sie dann für andere als die Ausnahmen in der DoNotRetryExceptionTypes ausgelösten Ausnahmen.</span><span class="sxs-lookup"><span data-stu-id="7b529-119">Invokes the given Function, retrying for exceptions thrown other than the exceptions in the doNotRetryExceptionTypes.</span></span>
            <span data-ttu-id="7b529-120">Ausnahmen, die nicht in DoNotRetryExceptionTypes enthalten sind, steuert CommunicationClientFactorys ReportOperationExceptionAsync()-Methode, wenn die Ausnahme oder nicht wiederholt werden soll.</span><span class="sxs-lookup"><span data-stu-id="7b529-120">For exceptions that are not in doNotRetryExceptionTypes, CommunicationClientFactory's ReportOperationExceptionAsync() method controls if the exception should be retried or not.</span></span>
            </summary>
        <returns><span data-ttu-id="7b529-121">Die Funktion, die im Argument angegebene Optimierungsfehler</span><span class="sxs-lookup"><span data-stu-id="7b529-121">Result from the function given in the argument</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeWithRetryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InvokeWithRetryAsync (Func&lt;TCommunicationClient,System.Threading.Tasks.Task&gt; func, params Type[] doNotRetryExceptionTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task InvokeWithRetryAsync(class System.Func`2&lt;!TCommunicationClient, class System.Threading.Tasks.Task&gt; func, class System.Type[] doNotRetryExceptionTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.InvokeWithRetryAsync(System.Func{`0,System.Threading.Tasks.Task},System.Type[])" />
      <MemberSignature Language="VB.NET" Value="Public Function InvokeWithRetryAsync (func As Func(Of TCommunicationClient, Task), ParamArray doNotRetryExceptionTypes As Type()) As Task" />
      <MemberSignature Language="F#" Value="member this.InvokeWithRetryAsync : Func&lt;'CommunicationClient, System.Threading.Tasks.Task (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; * Type[] -&gt; System.Threading.Tasks.Task" Usage="servicePartitionClient.InvokeWithRetryAsync (func, doNotRetryExceptionTypes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="func" Type="System.Func&lt;TCommunicationClient,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="doNotRetryExceptionTypes" Type="System.Type[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="func"><span data-ttu-id="7b529-122">Die aufgerufene Funktion</span><span class="sxs-lookup"><span data-stu-id="7b529-122">Function being invoked</span></span></param>
        <param name="doNotRetryExceptionTypes"><span data-ttu-id="7b529-123">Ausnahmen, die für die der Dienstclient für die Partition nicht den wiederholen soll</span><span class="sxs-lookup"><span data-stu-id="7b529-123">Exceptions for which the service partition client should not retry</span></span></param>
        <summary>
            <span data-ttu-id="7b529-124">Ruft die angegebene Funktion auf, und wiederholen Sie dann für andere als die Ausnahmen in der DoNotRetryExceptionTypes ausgelösten Ausnahmen.</span><span class="sxs-lookup"><span data-stu-id="7b529-124">Invokes the given Function, retrying for exceptions thrown other than the exceptions in the doNotRetryExceptionTypes.</span></span>
            <span data-ttu-id="7b529-125">Ausnahmen, die nicht in DoNotRetryExceptionTypes enthalten sind, steuert CommunicationClientFactorys ReportOperationExceptionAsync()-Methode, wenn die Ausnahme oder nicht wiederholt werden soll.</span><span class="sxs-lookup"><span data-stu-id="7b529-125">For exceptions that are not in doNotRetryExceptionTypes, CommunicationClientFactory's ReportOperationExceptionAsync() method controls if the exception should be retried or not.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7b529-126">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="7b529-126">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeWithRetryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InvokeWithRetryAsync (Func&lt;TCommunicationClient,System.Threading.Tasks.Task&gt; func, System.Threading.CancellationToken cancellationToken, params Type[] doNotRetryExceptionTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task InvokeWithRetryAsync(class System.Func`2&lt;!TCommunicationClient, class System.Threading.Tasks.Task&gt; func, valuetype System.Threading.CancellationToken cancellationToken, class System.Type[] doNotRetryExceptionTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.InvokeWithRetryAsync(System.Func{`0,System.Threading.Tasks.Task},System.Threading.CancellationToken,System.Type[])" />
      <MemberSignature Language="F#" Value="member this.InvokeWithRetryAsync : Func&lt;'CommunicationClient, System.Threading.Tasks.Task (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; * System.Threading.CancellationToken * Type[] -&gt; System.Threading.Tasks.Task" Usage="servicePartitionClient.InvokeWithRetryAsync (func, cancellationToken, doNotRetryExceptionTypes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1/&lt;InvokeWithRetryAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="func" Type="System.Func&lt;TCommunicationClient,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="doNotRetryExceptionTypes" Type="System.Type[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="func"><span data-ttu-id="7b529-127">Die aufgerufene Funktion</span><span class="sxs-lookup"><span data-stu-id="7b529-127">Function being invoked</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="7b529-128">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="7b529-128">Cancellation token</span></span></param>
        <param name="doNotRetryExceptionTypes"><span data-ttu-id="7b529-129">Ausnahmen, die für die der Dienstclient für die Partition nicht den wiederholen soll</span><span class="sxs-lookup"><span data-stu-id="7b529-129">Exceptions for which the service partition client should not retry</span></span></param>
        <summary>
            <span data-ttu-id="7b529-130">Ruft die angegebene Funktion auf, und wiederholen Sie dann für andere als die Ausnahmen in der DoNotRetryExceptionTypes ausgelösten Ausnahmen.</span><span class="sxs-lookup"><span data-stu-id="7b529-130">Invokes the given Function, retrying for exceptions thrown other than the exceptions in the doNotRetryExceptionTypes.</span></span>
            <span data-ttu-id="7b529-131">Ausnahmen, die nicht in DoNotRetryExceptionTypes enthalten sind, steuert CommunicationClientFactorys ReportOperationExceptionAsync()-Methode, wenn die Ausnahme oder nicht wiederholt werden soll.</span><span class="sxs-lookup"><span data-stu-id="7b529-131">For exceptions that are not in doNotRetryExceptionTypes, CommunicationClientFactory's ReportOperationExceptionAsync() method controls if the exception should be retried or not.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7b529-132">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="7b529-132">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeWithRetryAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TResult&gt; InvokeWithRetryAsync&lt;TResult&gt; (Func&lt;TCommunicationClient,System.Threading.Tasks.Task&lt;TResult&gt;&gt; func, params Type[] doNotRetryExceptionTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!!TResult&gt; InvokeWithRetryAsync&lt;TResult&gt;(class System.Func`2&lt;!TCommunicationClient, class System.Threading.Tasks.Task`1&lt;!!TResult&gt;&gt; func, class System.Type[] doNotRetryExceptionTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.InvokeWithRetryAsync``1(System.Func{`0,System.Threading.Tasks.Task{``0}},System.Type[])" />
      <MemberSignature Language="VB.NET" Value="Public Function InvokeWithRetryAsync(Of TResult) (func As Func(Of TCommunicationClient, Task(Of TResult)), ParamArray doNotRetryExceptionTypes As Type()) As Task(Of TResult)" />
      <MemberSignature Language="F#" Value="member this.InvokeWithRetryAsync : Func&lt;'CommunicationClient, System.Threading.Tasks.Task&lt;'Result&gt; (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; * Type[] -&gt; System.Threading.Tasks.Task&lt;'Result&gt;" Usage="servicePartitionClient.InvokeWithRetryAsync (func, doNotRetryExceptionTypes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1/&lt;InvokeWithRetryAsync&gt;d__23`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="func" Type="System.Func&lt;TCommunicationClient,System.Threading.Tasks.Task&lt;TResult&gt;&gt;" />
        <Parameter Name="doNotRetryExceptionTypes" Type="System.Type[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="7b529-133">Führen Sie von der aufgerufenen Funktion</span><span class="sxs-lookup"><span data-stu-id="7b529-133">Result from the function being invoked</span></span></typeparam>
        <param name="func"><span data-ttu-id="7b529-134">Die aufgerufene Funktion</span><span class="sxs-lookup"><span data-stu-id="7b529-134">Function being invoked</span></span></param>
        <param name="doNotRetryExceptionTypes"><span data-ttu-id="7b529-135">Ausnahmen, die für die der Dienstclient für die Partition nicht den wiederholen soll</span><span class="sxs-lookup"><span data-stu-id="7b529-135">Exceptions for which the service partition client should not retry</span></span></param>
        <summary>
            <span data-ttu-id="7b529-136">Ruft die angegebene Funktion auf, und wiederholen Sie dann für andere als die Ausnahmen in der DoNotRetryExceptionTypes ausgelösten Ausnahmen.</span><span class="sxs-lookup"><span data-stu-id="7b529-136">Invokes the given Function, retrying for exceptions thrown other than the exceptions in the doNotRetryExceptionTypes.</span></span>
            <span data-ttu-id="7b529-137">Ausnahmen, die nicht in DoNotRetryExceptionTypes enthalten sind, steuert CommunicationClientFactorys ReportOperationExceptionAsync()-Methode, wenn die Ausnahme oder nicht wiederholt werden soll.</span><span class="sxs-lookup"><span data-stu-id="7b529-137">For exceptions that are not in doNotRetryExceptionTypes, CommunicationClientFactory's ReportOperationExceptionAsync() method controls if the exception should be retried or not.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7b529-138">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="7b529-138">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="7b529-139">Das Ergebnis der Aufgabe ist das Ergebnis von der Funktion im Argument angegeben.</span><span class="sxs-lookup"><span data-stu-id="7b529-139">The result of the Task is the result from the function given in the argument.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeWithRetryAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TResult&gt; InvokeWithRetryAsync&lt;TResult&gt; (Func&lt;TCommunicationClient,System.Threading.Tasks.Task&lt;TResult&gt;&gt; func, System.Threading.CancellationToken cancellationToken, params Type[] doNotRetryExceptionTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!!TResult&gt; InvokeWithRetryAsync&lt;TResult&gt;(class System.Func`2&lt;!TCommunicationClient, class System.Threading.Tasks.Task`1&lt;!!TResult&gt;&gt; func, valuetype System.Threading.CancellationToken cancellationToken, class System.Type[] doNotRetryExceptionTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.InvokeWithRetryAsync``1(System.Func{`0,System.Threading.Tasks.Task{``0}},System.Threading.CancellationToken,System.Type[])" />
      <MemberSignature Language="F#" Value="member this.InvokeWithRetryAsync : Func&lt;'CommunicationClient, System.Threading.Tasks.Task&lt;'Result&gt; (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; * System.Threading.CancellationToken * Type[] -&gt; System.Threading.Tasks.Task&lt;'Result&gt;" Usage="servicePartitionClient.InvokeWithRetryAsync (func, cancellationToken, doNotRetryExceptionTypes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1/&lt;InvokeWithRetryAsync&gt;d__24`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="func" Type="System.Func&lt;TCommunicationClient,System.Threading.Tasks.Task&lt;TResult&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="doNotRetryExceptionTypes" Type="System.Type[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="7b529-140">Führen Sie von der aufgerufenen Funktion</span><span class="sxs-lookup"><span data-stu-id="7b529-140">Result from the function being invoked</span></span></typeparam>
        <param name="func"><span data-ttu-id="7b529-141">Die aufgerufene Funktion</span><span class="sxs-lookup"><span data-stu-id="7b529-141">Function being invoked</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="7b529-142">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="7b529-142">Cancellation token</span></span></param>
        <param name="doNotRetryExceptionTypes"><span data-ttu-id="7b529-143">Ausnahmen, die für die der Dienstclient für die Partition nicht den wiederholen soll</span><span class="sxs-lookup"><span data-stu-id="7b529-143">Exceptions for which the service partition client should not retry</span></span></param>
        <summary>
            <span data-ttu-id="7b529-144">Ruft die angegebene Funktion auf, und wiederholen Sie dann für andere als die Ausnahmen in der DoNotRetryExceptionTypes ausgelösten Ausnahmen.</span><span class="sxs-lookup"><span data-stu-id="7b529-144">Invokes the given Function, retrying for exceptions thrown other than the exceptions in the doNotRetryExceptionTypes.</span></span>
            <span data-ttu-id="7b529-145">Ausnahmen, die nicht in DoNotRetryExceptionTypes enthalten sind, steuert CommunicationClientFactorys ReportOperationExceptionAsync()-Methode, wenn die Ausnahme oder nicht wiederholt werden soll.</span><span class="sxs-lookup"><span data-stu-id="7b529-145">For exceptions that are not in doNotRetryExceptionTypes, CommunicationClientFactory's ReportOperationExceptionAsync() method controls if the exception should be retried or not.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7b529-146">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="7b529-146">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="7b529-147">Das Ergebnis der Aufgabe ist das Ergebnis von der Funktion im Argument angegeben.</span><span class="sxs-lookup"><span data-stu-id="7b529-147">The result of the Task is the result from the function given in the argument.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenerName">
      <MemberSignature Language="C#" Value="public string ListenerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ListenerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.ListenerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListenerName As String" />
      <MemberSignature Language="F#" Value="member this.ListenerName : string" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.ListenerName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.ListenerName</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7b529-148">Ruft den Namen des Listeners im Replikat, zu dem der Client eine eine Verbindung herstellen soll.</span><span class="sxs-lookup"><span data-stu-id="7b529-148">Gets the name of the listener in the replica to which the client should connect to.</span></span>
            </summary>
        <value><span data-ttu-id="7b529-149">Name des Listeners</span><span class="sxs-lookup"><span data-stu-id="7b529-149">Listener name</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Client.ServicePartitionKey PartitionKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKey As ServicePartitionKey" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.PartitionKey" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.PartitionKey</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Client.ServicePartitionKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7b529-150">Ruft den Partitionsschlüssel ab.</span><span class="sxs-lookup"><span data-stu-id="7b529-150">Gets the partition key.</span></span>
            </summary>
        <value><span data-ttu-id="7b529-151">Partitionsschlüssel</span><span class="sxs-lookup"><span data-stu-id="7b529-151">Partition key</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceUri">
      <MemberSignature Language="C#" Value="public Uri ServiceUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.ServiceUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceUri As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceUri : Uri" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.ServiceUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.ServiceUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7b529-152">Ruft den Namen des Diensts ab</span><span class="sxs-lookup"><span data-stu-id="7b529-152">Gets the name of the service</span></span>
            </summary>
        <value><span data-ttu-id="7b529-153">Name des Diensts</span><span class="sxs-lookup"><span data-stu-id="7b529-153">Name of the service</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetReplicaSelector">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector TargetReplicaSelector { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector TargetReplicaSelector" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.TargetReplicaSelector" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetReplicaSelector As TargetReplicaSelector" />
      <MemberSignature Language="F#" Value="member this.TargetReplicaSelector : Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.TargetReplicaSelector" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.TargetReplicaSelector</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7b529-154">Ruft die Informationen über welches, der Replikat in der Partition der Client eine eine Verbindung herstellen soll.</span><span class="sxs-lookup"><span data-stu-id="7b529-154">Gets the information about which replica in the partition the client should connect to.</span></span>
            </summary>
        <value><span data-ttu-id="7b529-155">Eine <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" /></span><span class="sxs-lookup"><span data-stu-id="7b529-155">A <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" /></span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetLastResolvedServicePartition">
      <MemberSignature Language="C#" Value="public bool TryGetLastResolvedServicePartition (out System.Fabric.ResolvedServicePartition resolvedServicePartition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryGetLastResolvedServicePartition([out] class System.Fabric.ResolvedServicePartition&amp; resolvedServicePartition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.TryGetLastResolvedServicePartition(System.Fabric.ResolvedServicePartition@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetLastResolvedServicePartition (ByRef resolvedServicePartition As ResolvedServicePartition) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryGetLastResolvedServicePartition :  -&gt; bool&#xA;override this.TryGetLastResolvedServicePartition :  -&gt; bool" Usage="servicePartitionClient.TryGetLastResolvedServicePartition resolvedServicePartition" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.TryGetLastResolvedServicePartition(System.Fabric.ResolvedServicePartition@)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resolvedServicePartition" Type="System.Fabric.ResolvedServicePartition&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="resolvedServicePartition"><span data-ttu-id="7b529-156">Vorherige ResolvedServicePartition</span><span class="sxs-lookup"><span data-stu-id="7b529-156">previous ResolvedServicePartition</span></span></param>
        <summary>
            <span data-ttu-id="7b529-157">Ruft den aufgelösten Dienstpartition, der auf dem Client festgelegt wurde.</span><span class="sxs-lookup"><span data-stu-id="7b529-157">Gets the resolved service partition that was set on the client.</span></span>
            </summary>
        <returns><span data-ttu-id="7b529-158">True, wenn eine ResolvedServicePartition wurde festgelegt.</span><span class="sxs-lookup"><span data-stu-id="7b529-158">true if a ResolvedServicePartition was set</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>