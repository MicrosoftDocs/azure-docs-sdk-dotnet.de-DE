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
            Definiert die Common Language Runtime-Optionen bei der Registrierung einer <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> Schnittstelle mit einer EventHubConsumerGroup. Dies ist auch der Mechanismus zum Abfangen von Ausnahmen aus einer IEventProcessor-Instanz anhand einer <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" /> Objekt.
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
            Erstellt ein neues <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions" />-Objekt.
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
            Gibt eine EventProcessorOptions-Instanz mit allen Optionen, die auf die Standardwerte festgelegt.
            Die Standardwerte sind: <para>MaxBatchSize: 10</para><para>ReceiveTimeOut: 1 Minute</para><para>PrefetchCount: 300</para><para>InitialOffsetProvider: verwendet den letzten Offset geprüften, oder StartOfStream</para><para>InvokeProcessorAfterReceiveTimeout: "false"</para></summary>
        <value>eine EventProcessorOptions-Instanz mit allen Optionen auf die Standardwerte festgelegt</value>
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
        <summary> Ruft ab oder legt einen Wert, der angibt, ob der Empfänger die Common Language Runtime-Metrik aktiviert ist. </summary>
        <value> "true", wenn ein Client zugreifen möchte <see cref="T:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation" /> mit <see cref="T:Microsoft.Azure.EventHubs.Processor.PartitionContext" />.</value>
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
            Ruft ab oder legt die aktuelle Funktion verwendet, um den ersten offset, an dem mit dem Empfang von Ereignissen für eine Partition zu bestimmen.
            <para>Eine Rückgabe null gibt an, dass er die interne-Anbieter, der den letzten Wert des geprüften Offset (falls vorhanden) verwendet oder StartOfSTream (sofern nicht).</para></summary>
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
            Gibt zurück, ob die EventProcessorHost IEventProcessor.OnEvents(null) aufgerufen wird, wenn ein Empfangs-Timeout (true) oder nicht auftritt (false).
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
            Gibt die maximale Größe eines Ereignis-Batches, die mit IEventProcessor.ProcessEventsAsync aufgerufen werden
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
            Ruft ab oder legt die aktuelle Prefetch-Anzahl für den zugrunde liegenden Client.
            Der Standardwert ist 300.
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
            Ruft ab oder legt das Timeout Länge für Empfangsvorgänge.
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
        <param name="exceptionHandler">Handler, der aufgerufen wird, wenn eine Ausnahme auftritt. Legen Sie auf die null-Behandlung beendet.</param>
        <summary>
            Legt einen Ereignishandler, der Benachrichtigung über allgemeine Ausnahmen empfängt.
            <para>Ausnahmen, die auftreten, während der Verarbeitung von Ereignissen aus einer bestimmten Event Hub-Partition an der OnError-Methode von der Ereignisprozessor für diese Partition übermittelt werden. Dieser Handler wird aufgerufen, in Fällen, wenn kein Ereignisprozessor, der auslösende Aktivität zugeordneten vorhanden ist, oder der Ereignisprozessor konnte nicht erstellt werden.</para></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>