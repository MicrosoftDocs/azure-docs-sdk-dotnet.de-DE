<Type Name="EventProcessorOptions" FullName="Microsoft.ServiceBus.Messaging.EventProcessorOptions">
  <TypeSignature Language="C#" Value="public class EventProcessorOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventProcessorOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class EventProcessorOptions" />
  <TypeSignature Language="F#" Value="type EventProcessorOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Definiert die Common Language Runtime-Optionen bei der Registrierung einer <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> eine Verbindung mit einer <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />. Dies ist auch der Mechanismus zum Abfangen von Ausnahmen von einem <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> Instanz, die von einem EventProcessorHost-Objekt verwendet.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultOptions">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventProcessorOptions DefaultOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.ServiceBus.Messaging.EventProcessorOptions DefaultOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.DefaultOptions" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DefaultOptions As EventProcessorOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultOptions : Microsoft.ServiceBus.Messaging.EventProcessorOptions" Usage="Microsoft.ServiceBus.Messaging.EventProcessorOptions.DefaultOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventProcessorOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Standardoptionen, also 10 für die <see cref="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.MaxBatchSize" />, und 1 Minute für die <see cref="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.ReceiveTimeOut" /> Eigenschaft.</summary>
        <value>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" />zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableReceiverRuntimeMetric">
      <MemberSignature Language="C#" Value="public bool EnableReceiverRuntimeMetric { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableReceiverRuntimeMetric" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.EnableReceiverRuntimeMetric" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableReceiverRuntimeMetric As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableReceiverRuntimeMetric : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.EventProcessorOptions.EnableReceiverRuntimeMetric" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> Ruft ab oder legt einen Wert, der angibt, ob der Empfänger die Common Language Runtime-Metrik aktiviert ist. </summary>
        <value> "true", wenn ein Client zugreifen möchte <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" /> mit <see cref="T:Microsoft.ServiceBus.Messaging.PartitionContext" />. </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionReceived">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; ExceptionReceived;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; ExceptionReceived" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.Messaging.EventProcessorOptions.ExceptionReceived" />
      <MemberSignature Language="VB.NET" Value="Public Event ExceptionReceived As EventHandler(Of ExceptionReceivedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.ExceptionReceived : EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; " Usage="member this.ExceptionReceived : System.EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Dieses Ereignis wird ausgelöst, wenn eine Ausnahme festgestellt wird, bei der Verarbeitung von Ereignissen. Benutzer kann einen Handler für dieses Ereignis für die erste Benachrichtigung zu registrieren.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialOffsetProvider">
      <MemberSignature Language="C#" Value="public Func&lt;string,object&gt; InitialOffsetProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;string, object&gt; InitialOffsetProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.InitialOffsetProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialOffsetProvider As Func(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.InitialOffsetProvider : Func&lt;string, obj&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.EventProcessorOptions.InitialOffsetProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Delegaten dient zum Abrufen des ersten Offsets für eine bestimmte Partition erstellen <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.
            Delegat wird aufgerufen, indem PartitionId übergeben, und Benutzer kann dann zurück, Startoffset als Zeichenfolge oder UTC-Zeit zum Empfangen von Nachrichten ab.
            Dies wird nur verwendet, wenn <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" /> nicht angegeben und Empfänger zum ersten Mal erstellt wird.
            <remarks>Dies entspricht entweder <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> oder <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.DateTime,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> je nach dem Rückgabewert von Delegaten.</remarks></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeProcessorAfterReceiveTimeout">
      <MemberSignature Language="C#" Value="public bool InvokeProcessorAfterReceiveTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool InvokeProcessorAfterReceiveTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.InvokeProcessorAfterReceiveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property InvokeProcessorAfterReceiveTimeout As Boolean" />
      <MemberSignature Language="F#" Value="member this.InvokeProcessorAfterReceiveTimeout : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.EventProcessorOptions.InvokeProcessorAfterReceiveTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Aktivierung dieser Option führt dazu, dass <see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.ProcessEventsAsync(Microsoft.ServiceBus.Messaging.PartitionContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" /> , nach jedem ReceiveTimeout aufgerufen werden soll, wenn keine weiteren Nachrichten in den Stream für eine Partition vorhanden sind.
            </summary>
        <value>To be added.</value>
        <remarks>Diese Option ist standardmäßig deaktiviert.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBatchSize">
      <MemberSignature Language="C#" Value="public int MaxBatchSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBatchSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.MaxBatchSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBatchSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBatchSize : int with get, set" Usage="Microsoft.ServiceBus.Messaging.EventProcessorOptions.MaxBatchSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Anzahl der Höchstdauer des Ereignisses, die ein Benutzer für die Verarbeitung pro Empfangsschleife akzeptiert wird. Diese Anzahl wird auf einer pro-Event Hub-Partitionsebene.</summary>
        <value>Gibt <see cref="T:System.Int32" />zurück.</value>
        <remarks>Dies entspricht dem Argument MaxCount in<see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.EventProcessorOptions.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Anzahl der Ereignisse, die Empfänger in der zurzeit zugehörige Partition aktiv zwischengespeichert werden. Der Standardwert für diese Eigenschaft ist 300.</summary>
        <value>Gibt <see cref="T:System.Int32" />zurück.</value>
        <remarks>Diese Eigenschaft wird verwendet, um festgelegt <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactory.PrefetchCount" /> Eigenschaft auf die zugrunde liegenden MessagingFactory erstellt vom Host</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveTimeOut">
      <MemberSignature Language="C#" Value="public TimeSpan ReceiveTimeOut { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ReceiveTimeOut" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.ReceiveTimeOut" />
      <MemberSignature Language="VB.NET" Value="Public Property ReceiveTimeOut As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ReceiveTimeOut : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.EventProcessorOptions.ReceiveTimeOut" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Zeitraum, in dem der Benutzer möchte, warten Sie, wenn der Ereignisprozessor einen Empfangsvorgang ausführt wird.</summary>
        <value>Gibt <see cref="T:System.TimeSpan" />zurück.</value>
        <remarks>Diese entsprechen dem WaitTime-Argument in<see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" /></remarks>
      </Docs>
    </Member>
  </Members>
</Type>