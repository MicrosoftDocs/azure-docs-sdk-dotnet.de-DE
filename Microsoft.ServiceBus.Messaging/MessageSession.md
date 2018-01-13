<Type Name="MessageSession" FullName="Microsoft.ServiceBus.Messaging.MessageSession">
  <TypeSignature Language="C#" Value="public abstract class MessageSession : Microsoft.ServiceBus.Messaging.MessageReceiver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MessageSession extends Microsoft.ServiceBus.Messaging.MessageReceiver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessageSession" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MessageSession&#xA;Inherits MessageReceiver" />
  <TypeSignature Language="F#" Value="type MessageSession = class&#xA;    inherit MessageReceiver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessageReceiver</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="ce010-101">Stellt eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="ce010-101">Represents a message session that allows grouping of related messages for processing in a single transaction.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetState">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetState ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IO.Stream GetState() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.GetState" />
      <MemberSignature Language="VB.NET" Value="Public Function GetState () As Stream" />
      <MemberSignature Language="F#" Value="member this.GetState : unit -&gt; System.IO.Stream" Usage="messageSession.GetState " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="ce010-102">Ruft den Zustand der meldungssitzung ab.</span><span class="sxs-lookup"><span data-stu-id="ce010-102">Gets the state of the message session.</span></span></summary>
        <returns><span data-ttu-id="ce010-103">Der Stream, aus dem Informationen über den Zustand beibehalten wird.</span><span class="sxs-lookup"><span data-stu-id="ce010-103">The stream from which the state information is persisted.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.IO.Stream&gt; GetStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; GetStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.GetStateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetStateAsync () As Task(Of Stream)" />
      <MemberSignature Language="F#" Value="member this.GetStateAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="messageSession.GetStateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="ce010-104">Ruft asynchron den Status der meldungssitzung ab.</span><span class="sxs-lookup"><span data-stu-id="ce010-104">Asynchronously gets the state of the message session.</span></span></summary>
        <returns><span data-ttu-id="ce010-105">Der Stream, aus dem Informationen über den Zustand beibehalten wird.</span><span class="sxs-lookup"><span data-stu-id="ce010-105">The stream from which the state information is persisted.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsExclusiveMode">
      <MemberSignature Language="C#" Value="public bool IsExclusiveMode { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsExclusiveMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.IsExclusiveMode" />
      <MemberSignature Language="VB.NET" Value="Public Property IsExclusiveMode As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsExclusiveMode : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.IsExclusiveMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastPeekedSequenceNumber">
      <MemberSignature Language="C#" Value="public override long LastPeekedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastPeekedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.LastPeekedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property LastPeekedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastPeekedSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.MessageSession.LastPeekedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ce010-106">Ruft ab oder legt die letzte eingesehenen Sequenznummer in der Sitzung.</span><span class="sxs-lookup"><span data-stu-id="ce010-106">Gets or sets the last peeked sequence number in the session.</span></span></summary>
        <value><span data-ttu-id="ce010-107">Die Anzahl der zuletzt eingesehenen Sequenz, in der Sitzung.</span><span class="sxs-lookup"><span data-stu-id="ce010-107">The last peeked sequence number in the session.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ce010-108">Ruft ab oder legt das Datum und Uhrzeit, an dem die nachrichtensitzung entsperrt wird.</span><span class="sxs-lookup"><span data-stu-id="ce010-108">Gets or sets the date and time at which the message session is unlocked.</span></span></summary>
        <value><span data-ttu-id="ce010-109">Das Datum und die Uhrzeit für die nachrichtensitzung gesperrt werden.</span><span class="sxs-lookup"><span data-stu-id="ce010-109">The date and time for the message session to be locked.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; LockToken { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public Property LockToken As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.LockToken : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value><span data-ttu-id="ce010-110">Das Sperrtoken</span><span class="sxs-lookup"><span data-stu-id="ce010-110">The lock token</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbandon">
      <MemberSignature Language="C#" Value="protected override void OnAbandon (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbandon(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnAbandon(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit" Usage="messageSession.OnAbandon (trackingContext, lockTokens, propertiesToModify, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ce010-111">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ce010-111">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ce010-112">Die Lock-Token.</span><span class="sxs-lookup"><span data-stu-id="ce010-112">The lock tokens.</span></span> </param>
        <param name="propertiesToModify"></param>
        <param name="timeout"> <span data-ttu-id="ce010-113">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ce010-113">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="ce010-114">Verwirft eine Peek gesperrt Nachricht.</span><span class="sxs-lookup"><span data-stu-id="ce010-114">Abandons a peek locked message.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="messageSession.OnAbort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="ce010-115">Bricht die nachrichtensitzung ab.</span><span class="sxs-lookup"><span data-stu-id="ce010-115">Aborts the message session.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAbandon">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginAbandon (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginAbandon(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginAbandon(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginAbandon (trackingContext, lockTokens, propertiesToModify, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"></param>
        <param name="lockTokens"> <span data-ttu-id="ce010-116">Die Lock-Token.</span><span class="sxs-lookup"><span data-stu-id="ce010-116">The lock tokens.</span></span> </param>
        <param name="propertiesToModify"> <span data-ttu-id="ce010-117">Die Eigenschaften für die Abandon-Aktion hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="ce010-117">The properties to add for the abandon action.</span></span></param>
        <param name="fromSync"></param>
        <param name="timeout">    <span data-ttu-id="ce010-118">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ce010-118">The timeout.</span></span> </param>
        <param name="callback">   <span data-ttu-id="ce010-119">Der Rückruf.</span><span class="sxs-lookup"><span data-stu-id="ce010-119">The callback.</span></span> </param>
        <param name="state">      <span data-ttu-id="ce010-120">Der Zustand.</span><span class="sxs-lookup"><span data-stu-id="ce010-120">The state.</span></span> </param>
        <summary>
            <span data-ttu-id="ce010-121">Führt eine Aktion kann beginnen.</span><span class="sxs-lookup"><span data-stu-id="ce010-121">Executes the begin abandon action.</span></span> 
            </summary>
        <returns> <span data-ttu-id="ce010-122">zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="ce010-122">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginClose (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="ce010-123">Die Zeitspanne Intervall der Vorgang wartet, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ce010-123">The time span interval the operation waits before it times out.</span></span></param>
        <param name="callback"><span data-ttu-id="ce010-124">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ce010-124">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="ce010-125">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="ce010-125">A user-defined object that contains state information about the asynchronous operation.</span></span> </param>
        <summary><span data-ttu-id="ce010-126">Startet einen asynchronen Vorgang, um das Kommunikationsobjekt für die Message-Sitzung zu schließen.</span><span class="sxs-lookup"><span data-stu-id="ce010-126">Begins an asynchronous operation to close the communication object for the message session.</span></span></summary>
        <returns><span data-ttu-id="ce010-127">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Schließen Sie des Kommunikationsobjekts für die nachrichtensitzung verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-127">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to close the communication object for the message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginComplete">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt; deliveryTags, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; deliveryTags, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.ArraySegment{System.Byte}},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;ArraySegment&lt;byte&gt;&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginComplete (trackingContext, deliveryTags, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="deliveryTags" Type="System.Collections.Generic.IEnumerable&lt;System.ArraySegment&lt;System.Byte&gt;&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="ce010-128">Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</span><span class="sxs-lookup"><span data-stu-id="ce010-128">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="deliveryTags"> <span data-ttu-id="ce010-129">Eine Auflistung von Übermittlung Tags.</span><span class="sxs-lookup"><span data-stu-id="ce010-129">A collection of delivery tags.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="ce010-130">Der Beginn der Synchronisierung.</span><span class="sxs-lookup"><span data-stu-id="ce010-130">The start of the synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="ce010-131">Die Zeitspanne Intervall der Vorgang wartet, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ce010-131">The time span interval the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="ce010-132">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ce010-132">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="ce010-133">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="ce010-133">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="ce010-134">Führt beim Aufrufen des Vorgangs OnComplete oder BeginComplete.</span><span class="sxs-lookup"><span data-stu-id="ce010-134">Executes upon calling the OnComplete or BeginComplete operation.</span></span></summary>
        <returns><span data-ttu-id="ce010-135">Ein<see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Schließen Sie des Kommunikationsobjekts für die nachrichtensitzung verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-135">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to close the communication object for the message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginComplete">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginComplete (trackingContext, lockTokens, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="ce010-136">Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</span><span class="sxs-lookup"><span data-stu-id="ce010-136">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ce010-137">Die Auflistung der Lock-Token an den gesperrten Nachrichteninstanzen gebunden.</span><span class="sxs-lookup"><span data-stu-id="ce010-137">The collection of lock tokens bound to the locked message instances.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="ce010-138">Der Beginn der Synchronisierung.</span><span class="sxs-lookup"><span data-stu-id="ce010-138">The start of the synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="ce010-139">Die Zeitspanne Intervall der Vorgang wartet, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ce010-139">The time span interval the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="ce010-140">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ce010-140">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="ce010-141">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="ce010-141">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="ce010-142">Führt beim Aufrufen des Vorgangs OnComplete oder BeginComplete.</span><span class="sxs-lookup"><span data-stu-id="ce010-142">Executes upon calling the OnComplete or BeginComplete operation.</span></span></summary>
        <returns><span data-ttu-id="ce010-143">Ein<see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Schließen Sie des Kommunikationsobjekts für die nachrichtensitzung verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-143">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to close the communication object for the message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginDeadLetter">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginDeadLetter (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginDeadLetter(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginDeadLetter(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginDeadLetter (trackingContext, lockTokens, propertiesToModify, deadLetterReason, deadLetterErrorDescription, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ce010-144">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ce010-144">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ce010-145">Die Lock-Token.</span><span class="sxs-lookup"><span data-stu-id="ce010-145">The lock tokens.</span></span> </param>
        <param name="propertiesToModify"> <span data-ttu-id="ce010-146">Nachrichteneigenschaften ändern.</span><span class="sxs-lookup"><span data-stu-id="ce010-146">message properties to modify.</span></span> </param>
        <param name="deadLetterReason">  <span data-ttu-id="ce010-147">Der Grund für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="ce010-147">The reason for deadlettering the message.</span></span> </param>
        <param name="deadLetterErrorDescription">  <span data-ttu-id="ce010-148">Die Beschreibungsinformationen für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="ce010-148">The description information for deadlettering the message.</span></span> </param>
        <param name="fromSync"> <span data-ttu-id="ce010-149">"true", wenn dies von einer Synchronisierungsmethode aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="ce010-149">true if this was called from a sync method.</span></span></param>
        <param name="timeout">    <span data-ttu-id="ce010-150">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ce010-150">The timeout.</span></span> </param>
        <param name="callback">   <span data-ttu-id="ce010-151">Der Rückruf.</span><span class="sxs-lookup"><span data-stu-id="ce010-151">The callback.</span></span> </param>
        <param name="state">      <span data-ttu-id="ce010-152">Der Zustand.</span><span class="sxs-lookup"><span data-stu-id="ce010-152">The state.</span></span> </param>
        <summary> <span data-ttu-id="ce010-153">Führt den Anfang verschoben werden soll unzustellbare speicherwarteschlangen-Aktion an.</span><span class="sxs-lookup"><span data-stu-id="ce010-153">Executes the begin move to dead letter queue action.</span></span> </summary>
        <returns> <span data-ttu-id="ce010-154">zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="ce010-154">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginDefer">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginDefer (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginDefer(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginDefer(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginDefer (trackingContext, lockTokens, propertiesToModify, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ce010-155">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ce010-155">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ce010-156">Die Lock-Token.</span><span class="sxs-lookup"><span data-stu-id="ce010-156">The lock tokens.</span></span> </param>
        <param name="propertiesToModify"> <span data-ttu-id="ce010-157">Nachrichteneigenschaften ändern.</span><span class="sxs-lookup"><span data-stu-id="ce010-157">message properties to modify.</span></span> </param>
        <param name="fromSync"></param>
        <param name="timeout">    <span data-ttu-id="ce010-158">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ce010-158">The timeout.</span></span> </param>
        <param name="callback">   <span data-ttu-id="ce010-159">Der Rückruf.</span><span class="sxs-lookup"><span data-stu-id="ce010-159">The callback.</span></span> </param>
        <param name="state">      <span data-ttu-id="ce010-160">Der Zustand.</span><span class="sxs-lookup"><span data-stu-id="ce010-160">The state.</span></span> </param>
        <summary> <span data-ttu-id="ce010-161">Führt die Begin Aktion verzögern.</span><span class="sxs-lookup"><span data-stu-id="ce010-161">Executes the begin defer action.</span></span> </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetState">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetState (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetState(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginGetState(Microsoft.ServiceBus.Tracing.TrackingContext,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetState : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginGetState (trackingContext, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">  <span data-ttu-id="ce010-162">Die TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ce010-162">The TrackingContext to use.</span></span> </param>
        <param name="timeout">  <span data-ttu-id="ce010-163">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ce010-163">The timeout.</span></span> </param>
        <param name="callback"> <span data-ttu-id="ce010-164">Der Rückruf.</span><span class="sxs-lookup"><span data-stu-id="ce010-164">The callback.</span></span> </param>
        <param name="state">    <span data-ttu-id="ce010-165">Der Zustand.</span><span class="sxs-lookup"><span data-stu-id="ce010-165">The state.</span></span> </param>
        <summary> <span data-ttu-id="ce010-166">Führt die Begin-Get-Status-Aktion.</span><span class="sxs-lookup"><span data-stu-id="ce010-166">Executes the begin get state action.</span></span> </summary>
        <returns> <span data-ttu-id="ce010-167">zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="ce010-167">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginOpen">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginOpen (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginOpen(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginOpen(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginOpen (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginOpen : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginOpen (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="ce010-168">Die Zeitspanne Intervall der Vorgang wartet, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ce010-168">The time span interval the operation waits before it times out.</span></span></param>
        <param name="callback"><span data-ttu-id="ce010-169">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ce010-169">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="ce010-170">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="ce010-170">A user-defined object that contains state information about the asynchronous operation.</span></span> </param>
        <summary><span data-ttu-id="ce010-171">Führt beim Aufrufen des Vorgangs OnOpen des Nachrichtenempfängers.</span><span class="sxs-lookup"><span data-stu-id="ce010-171">Executes upon calling the OnOpen operation of the message receiver.</span></span></summary>
        <returns><span data-ttu-id="ce010-172">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang, um ein Kommunikationsobjekt zu öffnen, für die nachrichtensitzung verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-172">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to open a communication object for the message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginPeek">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginPeek (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, long fromSequenceNumber, int messageCount, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginPeek(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int64 fromSequenceNumber, int32 messageCount, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginPeek(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int64,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginPeek : Microsoft.ServiceBus.Tracing.TrackingContext * int64 * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginPeek (trackingContext, fromSequenceNumber, messageCount, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="ce010-173">Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</span><span class="sxs-lookup"><span data-stu-id="ce010-173">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="fromSequenceNumber"> <span data-ttu-id="ce010-174">Die Sequenznummer der Sitzung einsehen.</span><span class="sxs-lookup"><span data-stu-id="ce010-174">The sequence number to peek from the session.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="ce010-175">Die Anzahl der Nachricht in den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ce010-175">The number of message in the operation.</span></span></param>
        <param name="timeout"> <span data-ttu-id="ce010-176">Die Zeitspanne Intervall der Vorgang wartet, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ce010-176">The time span interval the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="ce010-177">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ce010-177">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="ce010-178">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="ce010-178">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="ce010-179">Beim Aufrufen des Vorgangs OnPeek oder BeginPeek führt.</span><span class="sxs-lookup"><span data-stu-id="ce010-179">Executes upon calling the OnPeek or BeginPeek operation.</span></span></summary>
        <returns><span data-ttu-id="ce010-180">Ein<see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Einsehen einer Kommunikation der meldungssitzung verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-180">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to peek a communication of the message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRenewLock">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginRenewLock (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginRenewLock(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginRenewLock(Microsoft.ServiceBus.Tracing.TrackingContext,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginRenewLock : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginRenewLock (trackingContext, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="ce010-181">Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</span><span class="sxs-lookup"><span data-stu-id="ce010-181">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="timeout"> <span data-ttu-id="ce010-182">Die Zeitspanne Intervall der Vorgang wartet, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ce010-182">The time span interval the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="ce010-183">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ce010-183">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="ce010-184">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="ce010-184">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="ce010-185">Führt beim Aufrufen des Vorgangs RenewLock oder BeginRenewLock.</span><span class="sxs-lookup"><span data-stu-id="ce010-185">Executes upon calling the RenewLock or BeginRenewLock operation.</span></span></summary>
        <returns><span data-ttu-id="ce010-186">Ein<see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Abrufen des Status des Vorgangs verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-186">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to get the state of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginRenewMessageLocks (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginRenewMessageLocks(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginRenewMessageLocks(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginRenewMessageLocks : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginRenewMessageLocks (trackingContext, lockTokens, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="ce010-187">Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</span><span class="sxs-lookup"><span data-stu-id="ce010-187">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ce010-188">Die Auflistung der Lock-Token an den gesperrten Nachrichteninstanzen gebunden.</span><span class="sxs-lookup"><span data-stu-id="ce010-188">The collection of lock tokens bound to the locked message instances.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="ce010-189">Der Beginn der Synchronisierung.</span><span class="sxs-lookup"><span data-stu-id="ce010-189">The start of the synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="ce010-190">Die Zeitspanne des Vorgangs warten soll, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ce010-190">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="ce010-191">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ce010-191">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="ce010-192">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="ce010-192">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="ce010-193">Führt beim Aufrufen des Vorgangs OnBegin für Sperren von Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ce010-193">Executes upon calling the OnBegin operation for lock messages.</span></span></summary>
        <returns><span data-ttu-id="ce010-194">Ein<see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Erneuern Sie die Verarbeitung von Nachrichten Sperre verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-194">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to renew processing of lock messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginSetState">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginSetState (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.IO.Stream sessionState, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginSetState(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.IO.Stream sessionState, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginSetState(Microsoft.ServiceBus.Tracing.TrackingContext,System.IO.Stream,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginSetState : Microsoft.ServiceBus.Tracing.TrackingContext * System.IO.Stream * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginSetState (trackingContext, sessionState, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="sessionState" Type="System.IO.Stream" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">  <span data-ttu-id="ce010-195">Die TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ce010-195">The TrackingContext to use.</span></span> </param>
        <param name="sessionState">   <span data-ttu-id="ce010-196">Der Zustand.</span><span class="sxs-lookup"><span data-stu-id="ce010-196">The state.</span></span> </param>
        <param name="timeout">  <span data-ttu-id="ce010-197">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ce010-197">The timeout.</span></span> </param>
        <param name="callback"> <span data-ttu-id="ce010-198">Der Rückruf.</span><span class="sxs-lookup"><span data-stu-id="ce010-198">The callback.</span></span> </param>
        <param name="state">    <span data-ttu-id="ce010-199">Der Zustand.</span><span class="sxs-lookup"><span data-stu-id="ce010-199">The state.</span></span> </param>
        <summary> <span data-ttu-id="ce010-200">Führt die Begin die Aktion.</span><span class="sxs-lookup"><span data-stu-id="ce010-200">Executes the begin set state action.</span></span> </summary>
        <returns> <span data-ttu-id="ce010-201">zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="ce010-201">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;long&gt; receipts, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;int64&gt; receipts, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Int64},System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginTryReceive (trackingContext, receipts, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="receipts" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ce010-202">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ce010-202">TrackingContext to use.</span></span></param>
        <param name="receipts"> <span data-ttu-id="ce010-203">Die eingehenden Bestätigungen.</span><span class="sxs-lookup"><span data-stu-id="ce010-203">The receipts.</span></span> </param>
        <param name="timeout">  <span data-ttu-id="ce010-204">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ce010-204">The timeout.</span></span> </param>
        <param name="callback"> <span data-ttu-id="ce010-205">Der Rückruf.</span><span class="sxs-lookup"><span data-stu-id="ce010-205">The callback.</span></span> </param>
        <param name="state">    <span data-ttu-id="ce010-206">Der Zustand.</span><span class="sxs-lookup"><span data-stu-id="ce010-206">The state.</span></span> </param>
        <summary> <span data-ttu-id="ce010-207">Führt die Begin Try Empfangsaktion.</span><span class="sxs-lookup"><span data-stu-id="ce010-207">Executes the begin try receive action.</span></span> </summary>
        <returns> <span data-ttu-id="ce010-208">zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="ce010-208">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginTryReceive (trackingContext, messageCount, serverWaitTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ce010-209">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ce010-209">TrackingContext to use.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="ce010-210">Anzahl der Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ce010-210">Number of messages.</span></span> </param>
        <param name="serverWaitTime"> <span data-ttu-id="ce010-211">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ce010-211">The timeout.</span></span> </param>
        <param name="callback">     <span data-ttu-id="ce010-212">Der Rückruf.</span><span class="sxs-lookup"><span data-stu-id="ce010-212">The callback.</span></span> </param>
        <param name="state">        <span data-ttu-id="ce010-213">Der Zustand.</span><span class="sxs-lookup"><span data-stu-id="ce010-213">The state.</span></span> </param>
        <summary> <span data-ttu-id="ce010-214">Führt die Begin Try Empfangsaktion.</span><span class="sxs-lookup"><span data-stu-id="ce010-214">Executes the begin try receive action.</span></span> </summary>
        <returns> <span data-ttu-id="ce010-215">zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="ce010-215">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive2">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginTryReceive2 (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginTryReceive2(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginTryReceive2(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginTryReceive2 : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginTryReceive2 (trackingContext, messageCount, serverWaitTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ce010-216">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ce010-216">TrackingContext to use.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="ce010-217">Anzahl der Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ce010-217">Number of messages.</span></span> </param>
        <param name="serverWaitTime"> <span data-ttu-id="ce010-218">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ce010-218">The timeout.</span></span> </param>
        <param name="callback">     <span data-ttu-id="ce010-219">Der Rückruf.</span><span class="sxs-lookup"><span data-stu-id="ce010-219">The callback.</span></span> </param>
        <param name="state">        <span data-ttu-id="ce010-220">Der Zustand.</span><span class="sxs-lookup"><span data-stu-id="ce010-220">The state.</span></span> </param>
        <summary> <span data-ttu-id="ce010-221">Führt die Begin Try Empfangsaktion.</span><span class="sxs-lookup"><span data-stu-id="ce010-221">Executes the begin try receive action.</span></span> </summary>
        <returns> <span data-ttu-id="ce010-222">zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="ce010-222">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnComplete">
      <MemberSignature Language="C#" Value="protected override void OnComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * TimeSpan -&gt; unit" Usage="messageSession.OnComplete (trackingContext, lockTokens, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ce010-223">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ce010-223">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ce010-224">Die Lock-Token.</span><span class="sxs-lookup"><span data-stu-id="ce010-224">The lock tokens.</span></span> </param>
        <param name="timeout"> <span data-ttu-id="ce010-225">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ce010-225">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="ce010-226">Schließt eine Peek gesperrten Nachricht ab.</span><span class="sxs-lookup"><span data-stu-id="ce010-226">Completes a peek locked message.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeadLetter">
      <MemberSignature Language="C#" Value="protected override void OnDeadLetter (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnDeadLetter(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnDeadLetter(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * TimeSpan -&gt; unit" Usage="messageSession.OnDeadLetter (trackingContext, lockTokens, propertiesToModify, deadLetterReason, deadLetterErrorDescription, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">To be added.</param>
        <param name="lockTokens">To be added.</param>
        <param name="propertiesToModify">To be added.</param>
        <param name="deadLetterReason">To be added.</param>
        <param name="deadLetterErrorDescription">To be added.</param>
        <param name="timeout">To be added.</param>
        <summary> <span data-ttu-id="ce010-227">Verschiebt eine Nachricht an die Dead Letter-Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="ce010-227">Moves a message to the dead letter queue.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDefer">
      <MemberSignature Language="C#" Value="protected override void OnDefer (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnDefer(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnDefer(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit" Usage="messageSession.OnDefer (trackingContext, lockTokens, propertiesToModify, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ce010-228">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ce010-228">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ce010-229">Die Lock-Token.</span><span class="sxs-lookup"><span data-stu-id="ce010-229">The lock tokens.</span></span> </param>
        <param name="propertiesToModify"> <span data-ttu-id="ce010-230">Nachrichteneigenschaften ändern.</span><span class="sxs-lookup"><span data-stu-id="ce010-230">message properties to modify.</span></span> </param>
        <param name="timeout">    <span data-ttu-id="ce010-231">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ce010-231">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="ce010-232">Eine Nachricht wird verzögert.</span><span class="sxs-lookup"><span data-stu-id="ce010-232">Defers a message.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAbandon">
      <MemberSignature Language="C#" Value="protected override void OnEndAbandon (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndAbandon(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndAbandon(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndAbandon (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndAbandon : IAsyncResult -&gt; unit" Usage="messageSession.OnEndAbandon result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ce010-233">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Abbrechen von Nachrichten und seine Sperre abgeben verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-233">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to abandon the messages and relinquish its lock.</span></span></param>
        <summary><span data-ttu-id="ce010-234">Beendet einen asynchronen Vorgang zum Verwerfen der Nachrichteninhalts und dessen Sperre abgeben.</span><span class="sxs-lookup"><span data-stu-id="ce010-234">Ends an asynchronous operation to abandon the message and relinquish its lock.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="messageSession.OnEndClose result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ce010-235">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Schließen Sie des Kommunikationsobjekts für die nachrichtensitzung verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-235">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to close the communication object for the message session.</span></span></param>
        <summary><span data-ttu-id="ce010-236">Beendet einen asynchronen Vorgang, um das Kommunikationsobjekt für die Message-Sitzung zu schließen.</span><span class="sxs-lookup"><span data-stu-id="ce010-236">Ends an asynchronous operation to close the communication object for the message session.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndComplete">
      <MemberSignature Language="C#" Value="protected override void OnEndComplete (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndComplete(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndComplete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndComplete (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndComplete : IAsyncResult -&gt; unit" Usage="messageSession.OnEndComplete result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ce010-237">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Empfangen von Nachrichten abschließen verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-237">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to complete receiving of messages.</span></span></param>
        <summary><span data-ttu-id="ce010-238">Führt die vollständige End-Vorgang des Nachrichtenempfängers an.</span><span class="sxs-lookup"><span data-stu-id="ce010-238">Executes the end complete operation of the message receiver.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndDeadLetter">
      <MemberSignature Language="C#" Value="protected override void OnEndDeadLetter (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndDeadLetter(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndDeadLetter(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndDeadLetter (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndDeadLetter : IAsyncResult -&gt; unit" Usage="messageSession.OnEndDeadLetter result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ce010-239">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang nicht zugestellte Nachrichten an die Warteschlange für unzustellbare Nachrichten verschieben verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-239">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to move undelivered messages to the deadletter queue.</span></span></param>
        <summary><span data-ttu-id="ce010-240">Führt den Vorgang des End-Warteschlange für unzustellbare Nachrichten des Nachrichtenempfängers.</span><span class="sxs-lookup"><span data-stu-id="ce010-240">Executes the end deadletter operation of the message receiver.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndDefer">
      <MemberSignature Language="C#" Value="protected override void OnEndDefer (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndDefer(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndDefer(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndDefer (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndDefer : IAsyncResult -&gt; unit" Usage="messageSession.OnEndDefer result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ce010-241">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Anhalten der Verarbeitung von Nachrichten verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-241">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to suspend processing of messages.</span></span></param>
        <summary><span data-ttu-id="ce010-242">Führt das Ende des Nachrichtenempfängers Vorgang aufschieben.</span><span class="sxs-lookup"><span data-stu-id="ce010-242">Executes the end defer operation of the message receiver.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetState">
      <MemberSignature Language="C#" Value="protected abstract System.IO.Stream OnEndGetState (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IO.Stream OnEndGetState(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndGetState(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetState (result As IAsyncResult) As Stream" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetState : IAsyncResult -&gt; System.IO.Stream" Usage="messageSession.OnEndGetState result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ce010-243">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Abrufen des Status der meldungssitzung verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-243">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to get the state of the message session.</span></span></param>
        <summary><span data-ttu-id="ce010-244">Führt beim Aufrufen des Vorgangs OnGetState oder EndGetState.</span><span class="sxs-lookup"><span data-stu-id="ce010-244">Executes upon calling the OnGetState or EndGetState operation.</span></span></summary>
        <returns><span data-ttu-id="ce010-245">Der Stream, aus dem Informationen über den Zustand beibehalten wird.</span><span class="sxs-lookup"><span data-stu-id="ce010-245">The stream from which the state information is persisted.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndOpen">
      <MemberSignature Language="C#" Value="protected override void OnEndOpen (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndOpen(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndOpen(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndOpen (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndOpen : IAsyncResult -&gt; unit" Usage="messageSession.OnEndOpen result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ce010-246">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang, um ein Kommunikationsobjekt zu öffnen, für die nachrichtensitzung verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-246">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to open a communication object for the message session.</span></span></param>
        <summary><span data-ttu-id="ce010-247">Beendet den asynchronen Vorgang, um ein Kommunikationsobjekt für die Message-Sitzung zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="ce010-247">Ends the asynchronous operation to open a communication object for the message session.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndPeek">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnEndPeek (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnEndPeek(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndPeek(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndPeek (result As IAsyncResult) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="override this.OnEndPeek : IAsyncResult -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageSession.OnEndPeek result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ce010-248">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Einsehen einer Kommunikation der meldungssitzung verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-248">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to peek a communication of the message session.</span></span></param>
        <summary><span data-ttu-id="ce010-249">Führt beim Aufrufen des EndPeek-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ce010-249">Executes upon calling the EndPeek operation.</span></span></summary>
        <returns><span data-ttu-id="ce010-250">Die Liste der Nachricht aus der Sitzung.</span><span class="sxs-lookup"><span data-stu-id="ce010-250">The list of message from the session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRenewLock">
      <MemberSignature Language="C#" Value="protected abstract DateTime OnEndRenewLock (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance valuetype System.DateTime OnEndRenewLock(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndRenewLock(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndRenewLock (result As IAsyncResult) As DateTime" />
      <MemberSignature Language="F#" Value="abstract member OnEndRenewLock : IAsyncResult -&gt; DateTime" Usage="messageSession.OnEndRenewLock result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ce010-251">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Abrufen des Status der meldungssitzung verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-251">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to get the state of the message session.</span></span></param>
        <summary><span data-ttu-id="ce010-252">Führt den Vorgang EndRenewLock des Nachrichtenempfängers an.</span><span class="sxs-lookup"><span data-stu-id="ce010-252">Executes the EndRenewLock operation of the message receiver.</span></span></summary>
        <returns><span data-ttu-id="ce010-253">Das Datum und Uhrzeit, zu das Erneuerung der Sperre endet.</span><span class="sxs-lookup"><span data-stu-id="ce010-253">The date and time when the renewal of lock ends.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;DateTime&gt; OnEndRenewMessageLocks (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;valuetype System.DateTime&gt; OnEndRenewMessageLocks(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndRenewMessageLocks(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndRenewMessageLocks (result As IAsyncResult) As IEnumerable(Of DateTime)" />
      <MemberSignature Language="F#" Value="override this.OnEndRenewMessageLocks : IAsyncResult -&gt; seq&lt;DateTime&gt;" Usage="messageSession.OnEndRenewMessageLocks result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ce010-254">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ce010-254">The result of the operation.</span></span></param>
        <summary><span data-ttu-id="ce010-255">Führt eine Aktion EndRenew für nachrichtensperren.</span><span class="sxs-lookup"><span data-stu-id="ce010-255">Executes the EndRenew action for message locks.</span></span></summary>
        <returns><span data-ttu-id="ce010-256">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> von gesperrten Nachrichten...</span><span class="sxs-lookup"><span data-stu-id="ce010-256">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> of locked messages..</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndSetState">
      <MemberSignature Language="C#" Value="protected abstract void OnEndSetState (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndSetState(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndSetState(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndSetState (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndSetState : IAsyncResult -&gt; unit" Usage="messageSession.OnEndSetState result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ce010-257">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Festlegen des Status der meldungssitzung verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-257">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to set the state of the message session.</span></span></param>
        <summary><span data-ttu-id="ce010-258">Beendet den asynchronen Vorgang zum Festlegen des Status der meldungssitzung an.</span><span class="sxs-lookup"><span data-stu-id="ce010-258">Ends the asynchronous operation to set the state of the message session.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceive">
      <MemberSignature Language="C#" Value="protected override bool OnEndTryReceive (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnEndTryReceive(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndTryReceive(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndTryReceive (result As IAsyncResult, ByRef messages As IEnumerable(Of BrokeredMessage)) As Boolean" />
      <MemberSignature Language="F#" Value="override this.OnEndTryReceive : IAsyncResult *  -&gt; bool" Usage="messageSession.OnEndTryReceive (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ce010-259">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang, um zu versuchen, Nachrichten zu empfangen verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-259">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to try to receive messages.</span></span></param>
        <param name="messages"><span data-ttu-id="ce010-260">Wenn diese Methode zurückgibt, enthält die empfangene Nachricht-Auflistung.</span><span class="sxs-lookup"><span data-stu-id="ce010-260">When this method returns, contains the received message collection.</span></span></param>
        <summary><span data-ttu-id="ce010-261">Führt das Ende wiederholen Sie den Vorgang, der den Empfänger einer Nachricht zu empfangen.</span><span class="sxs-lookup"><span data-stu-id="ce010-261">Executes the end try receive operation of the message receiver.</span></span></summary>
        <returns><span data-ttu-id="ce010-262">"true", wenn er erfolgreich abgeschlossen wurde; "false", wenn ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="ce010-262">true if it succeeds; false if it fails.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceive2">
      <MemberSignature Language="C#" Value="protected override bool OnEndTryReceive2 (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnEndTryReceive2(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndTryReceive2(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndTryReceive2 (result As IAsyncResult, ByRef messages As IEnumerable(Of BrokeredMessage)) As Boolean" />
      <MemberSignature Language="F#" Value="override this.OnEndTryReceive2 : IAsyncResult *  -&gt; bool" Usage="messageSession.OnEndTryReceive2 (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ce010-263">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang, um zu versuchen, Nachrichten zu empfangen verweist.</span><span class="sxs-lookup"><span data-stu-id="ce010-263">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to try to receive messages.</span></span></param>
        <param name="messages"><span data-ttu-id="ce010-264">Wenn diese Methode zurückgibt, enthält die empfangene Nachricht-Auflistung.</span><span class="sxs-lookup"><span data-stu-id="ce010-264">When this method returns, contains the received message collection.</span></span></param>
        <summary><span data-ttu-id="ce010-265">Führt das Ende wiederholen Sie den Vorgang, der den Empfänger einer Nachricht zu empfangen.</span><span class="sxs-lookup"><span data-stu-id="ce010-265">Executes the end try receive operation of the message receiver.</span></span></summary>
        <returns><span data-ttu-id="ce010-266">"true", wenn er erfolgreich abgeschlossen wurde; "false", wenn ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="ce010-266">true if it succeeds; false if it fails.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnGetState">
      <MemberSignature Language="C#" Value="protected virtual System.IO.Stream OnGetState (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IO.Stream OnGetState(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnGetState(Microsoft.ServiceBus.Tracing.TrackingContext,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnGetState : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan -&gt; System.IO.Stream&#xA;override this.OnGetState : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan -&gt; System.IO.Stream" Usage="messageSession.OnGetState (trackingContext, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">  <span data-ttu-id="ce010-267">Die TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ce010-267">The TrackingContext to use.</span></span> </param>
        <param name="timeout"> <span data-ttu-id="ce010-268">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ce010-268">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="ce010-269">Führt die Aktion zum Abrufen des Status an.</span><span class="sxs-lookup"><span data-stu-id="ce010-269">Executes the get state action.</span></span> </summary>
        <returns> <span data-ttu-id="ce010-270">zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="ce010-270">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRenewLock">
      <MemberSignature Language="C#" Value="protected virtual DateTime OnRenewLock (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance valuetype System.DateTime OnRenewLock(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnRenewLock(Microsoft.ServiceBus.Tracing.TrackingContext,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnRenewLock : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan -&gt; DateTime&#xA;override this.OnRenewLock : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan -&gt; DateTime" Usage="messageSession.OnRenewLock (trackingContext, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="ce010-271">Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</span><span class="sxs-lookup"><span data-stu-id="ce010-271">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="timeout"> <span data-ttu-id="ce010-272">Die Zeitspanne Intervall der Vorgang wartet, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ce010-272">The time span interval the operation waits before it times out.</span></span></param>
        <summary><span data-ttu-id="ce010-273">Führt eine Aktion RenewLock für nachrichtensperren.</span><span class="sxs-lookup"><span data-stu-id="ce010-273">Executes the RenewLock action for message locks.</span></span></summary>
        <returns><span data-ttu-id="ce010-274">Die Zeitspanne des Vorgangs warten soll, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ce010-274">The time span the operation waits before it times out.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnSetState">
      <MemberSignature Language="C#" Value="protected virtual void OnSetState (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.IO.Stream stream, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnSetState(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.IO.Stream stream, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnSetState(Microsoft.ServiceBus.Tracing.TrackingContext,System.IO.Stream,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnSetState : Microsoft.ServiceBus.Tracing.TrackingContext * System.IO.Stream * TimeSpan -&gt; unit&#xA;override this.OnSetState : Microsoft.ServiceBus.Tracing.TrackingContext * System.IO.Stream * TimeSpan -&gt; unit" Usage="messageSession.OnSetState (trackingContext, stream, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="stream" Type="System.IO.Stream" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">  <span data-ttu-id="ce010-275">Die TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ce010-275">The TrackingContext to use.</span></span> </param>
        <param name="stream">  <span data-ttu-id="ce010-276">Der Stream (Datenstrom).</span><span class="sxs-lookup"><span data-stu-id="ce010-276">The stream.</span></span> </param>
        <param name="timeout"> <span data-ttu-id="ce010-277">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ce010-277">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="ce010-278">Führt die Aktion an.</span><span class="sxs-lookup"><span data-stu-id="ce010-278">Executes the set state action.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTryReceive">
      <MemberSignature Language="C#" Value="protected override bool OnTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;long&gt; receipts, TimeSpan timeout, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;int64&gt; receipts, valuetype System.TimeSpan timeout, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Int64},System.TimeSpan,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="F#" Value="override this.OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan *  -&gt; bool" Usage="messageSession.OnTryReceive (trackingContext, receipts, timeout, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="receipts" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ce010-279">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ce010-279">TrackingContext to use.</span></span></param>
        <param name="receipts"> <span data-ttu-id="ce010-280">Die eingehenden Bestätigungen.</span><span class="sxs-lookup"><span data-stu-id="ce010-280">The receipts.</span></span> </param>
        <param name="timeout">  <span data-ttu-id="ce010-281">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ce010-281">The timeout.</span></span> </param>
        <param name="messages"> <span data-ttu-id="ce010-282">die Ausgabenachricht (ausgehend)</span><span class="sxs-lookup"><span data-stu-id="ce010-282">the output message (out)</span></span></param>
        <summary> <span data-ttu-id="ce010-283">Wiederholen Sie dann führt Empfangsaktion.</span><span class="sxs-lookup"><span data-stu-id="ce010-283">Executes the try receive action.</span></span> </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTryReceive">
      <MemberSignature Language="C#" Value="protected override bool OnTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="F#" Value="override this.OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan *  -&gt; bool" Usage="messageSession.OnTryReceive (trackingContext, messageCount, serverWaitTime, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ce010-284">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ce010-284">TrackingContext to use.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="ce010-285">Die Anzahl der Meldungen.</span><span class="sxs-lookup"><span data-stu-id="ce010-285">The number of messages.</span></span> </param>
        <param name="serverWaitTime">  <span data-ttu-id="ce010-286">Der Server-Wartezeit aus, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ce010-286">The server wait time before it times out.</span></span> </param>
        <param name="messages">  <span data-ttu-id="ce010-287">zurückgegebenen Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ce010-287">returned messages.</span></span> </param>
        <summary> <span data-ttu-id="ce010-288">Wiederholen Sie dann führt Empfangsaktion.</span><span class="sxs-lookup"><span data-stu-id="ce010-288">Executes the try receive action.</span></span> </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public override string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.Path" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.MessageSession.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ce010-289">Ruft den Pfad der Warteschlange bzw. Thema relativ zu den <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Basisadresse.</span><span class="sxs-lookup"><span data-stu-id="ce010-289">Gets the path of the queue or topic, relative to the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> base address.</span></span></summary>
        <value><span data-ttu-id="ce010-290">Eine Zeichenfolge, die den Pfad der Warteschlange bzw. Thema darstellt.</span><span class="sxs-lookup"><span data-stu-id="ce010-290">A string representing the path of the queue or topic.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public override int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ce010-291">Ruft ab oder legt die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="ce010-291">Gets or sets the number of messages that the message receiver can simultaneously request.</span></span></summary>
        <value><span data-ttu-id="ce010-292">Die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="ce010-292">The number of messages that the message receiver can simultaneously request.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessException">
      <MemberSignature Language="C#" Value="protected Exception ProcessException (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Exception ProcessException(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.ProcessException(System.Exception)" />
      <MemberSignature Language="F#" Value="member this.ProcessException : Exception -&gt; Exception" Usage="messageSession.ProcessException exception" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="exception"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLock">
      <MemberSignature Language="C#" Value="public void RenewLock ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RenewLock() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.RenewLock" />
      <MemberSignature Language="VB.NET" Value="Public Sub RenewLock ()" />
      <MemberSignature Language="F#" Value="member this.RenewLock : unit -&gt; unit" Usage="messageSession.RenewLock " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="ce010-293">Gibt den Zeitraum fest, innerhalb dessen der Host seine Sperre für eine Nachricht erneuert.</span><span class="sxs-lookup"><span data-stu-id="ce010-293">Specifies the time period within which the host renews its lock on a message.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="ce010-294">Wenn <see cref="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" /> ist "true", können Sie den Vorgang sofort wiederholen.</span><span class="sxs-lookup"><span data-stu-id="ce010-294">If <see cref="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" /> is true, you can retry the operation immediately.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="ce010-295">Sie können sofort den Vorgang wiederholen.</span><span class="sxs-lookup"><span data-stu-id="ce010-295">You can retry the operation immediately.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="ce010-296">Sie können sofort den Vorgang wiederholen.</span><span class="sxs-lookup"><span data-stu-id="ce010-296">You can retry the operation immediately.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException"><span data-ttu-id="ce010-297">Wird ausgelöst, anstelle von <see cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException" /> ist die Nachricht aus einer <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />.</span><span class="sxs-lookup"><span data-stu-id="ce010-297">Thrown instead of <see cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException" /> if the message is from a <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewLockAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RenewLockAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.RenewLockAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewLockAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RenewLockAsync : unit -&gt; System.Threading.Tasks.Task" Usage="messageSession.RenewLockAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="ce010-298">Gibt den Zeitraum fest, innerhalb dessen der Host seine Sperre für eine Nachricht erneuert.</span><span class="sxs-lookup"><span data-stu-id="ce010-298">Specifies the time period within which the host renews its lock on a message.</span></span></summary>
        <returns><span data-ttu-id="ce010-299">Der Host, der gesperrt wird.</span><span class="sxs-lookup"><span data-stu-id="ce010-299">The host that is being locked.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public virtual string SessionId { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ce010-300">Abrufen oder festlegen den Nachricht Sitzungsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="ce010-300">Gets or sets the message session identifier.</span></span></summary>
        <value><span data-ttu-id="ce010-301">Die Sitzungs-ID der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="ce010-301">The message session identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetState">
      <MemberSignature Language="C#" Value="public void SetState (System.IO.Stream sessionState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetState(class System.IO.Stream sessionState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.SetState(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetState (sessionState As Stream)" />
      <MemberSignature Language="F#" Value="member this.SetState : System.IO.Stream -&gt; unit" Usage="messageSession.SetState sessionState" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionState" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="sessionState"><span data-ttu-id="ce010-302">Der Stream, in dem Informationen über den Zustand beibehalten wird.</span><span class="sxs-lookup"><span data-stu-id="ce010-302">The stream to which the state information is persisted.</span></span></param>
        <summary><span data-ttu-id="ce010-303">Legt den Zustand der meldungssitzung.</span><span class="sxs-lookup"><span data-stu-id="ce010-303">Sets the state of the message session.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetStateAsync (System.IO.Stream sessionState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SetStateAsync(class System.IO.Stream sessionState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.SetStateAsync(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetStateAsync (sessionState As Stream) As Task" />
      <MemberSignature Language="F#" Value="member this.SetStateAsync : System.IO.Stream -&gt; System.Threading.Tasks.Task" Usage="messageSession.SetStateAsync sessionState" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionState" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="sessionState"><span data-ttu-id="ce010-304">Der Stream, in dem Informationen über den Zustand beibehalten wird.</span><span class="sxs-lookup"><span data-stu-id="ce010-304">The stream to which the state information is persisted.</span></span></param>
        <summary><span data-ttu-id="ce010-305">Legt asynchron den Status der meldungssitzung fest.</span><span class="sxs-lookup"><span data-stu-id="ce010-305">Asynchronously sets the state of the message session.</span></span></summary>
        <returns><span data-ttu-id="ce010-306">Der Status der meldungssitzung.</span><span class="sxs-lookup"><span data-stu-id="ce010-306">The state of the message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportsGetRuntimeEntityDescription">
      <MemberSignature Language="C#" Value="protected internal override bool SupportsGetRuntimeEntityDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overrides ReadOnly Property SupportsGetRuntimeEntityDescription As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportsGetRuntimeEntityDescription : bool" Usage="Microsoft.ServiceBus.Messaging.MessageSession.SupportsGetRuntimeEntityDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>