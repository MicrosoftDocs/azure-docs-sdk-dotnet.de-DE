<Type Name="MessageHandlerOptions" FullName="Microsoft.Azure.ServiceBus.MessageHandlerOptions">
  <TypeSignature Language="C#" Value="public sealed class MessageHandlerOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MessageHandlerOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.MessageHandlerOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessageHandlerOptions" />
  <TypeSignature Language="F#" Value="type MessageHandlerOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Bietet Optionen, die Nachricht Datapump Verarbeitung mit zugeordneten <see cref="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" /> und <see cref="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageHandlerOptions (Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.MessageHandlerOptions.#ctor(System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.MessageHandlerOptions : Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; Microsoft.Azure.ServiceBus.MessageHandlerOptions" Usage="new Microsoft.Azure.ServiceBus.MessageHandlerOptions exceptionReceivedHandler" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exceptionReceivedHandler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="exceptionReceivedHandler">Ein <see cref="T:System.Func`2" /> , die während der Ausnahmen aufgerufen wird.
            <see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />die Kontextinformationen hinsichtlich der Ausnahme enthält.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.ServiceBus.MessageHandlerOptions" />-Klasse.
            Standardwerte: <see cref="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.MaxConcurrentCalls" /> = 1 <see cref="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.AutoComplete" /> = "true" <see cref="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.ReceiveTimeOut" /> = 1 Minute <see cref="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.MaxAutoRenewDuration" /> = 5 Minuten
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoComplete">
      <MemberSignature Language="C#" Value="public bool AutoComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.AutoComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoComplete As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoComplete : bool with get, set" Usage="Microsoft.Azure.ServiceBus.MessageHandlerOptions.AutoComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob die Meldungsverteilschleife aufrufen sollte <see cref="M:Microsoft.Azure.ServiceBus.QueueClient.CompleteAsync(System.String)" /> oder <see cref="M:Microsoft.Azure.ServiceBus.SubscriptionClient.CompleteAsync(System.String)" /> für Nachrichten nach der Verarbeitung der Rückruf.</summary>
        <value>"true", die automatisch bei erfolgreicher Ausführung des Vorgangs die Verarbeitung der Nachricht abgeschlossen; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionReceivedHandler">
      <MemberSignature Language="C#" Value="public Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; ExceptionReceivedHandler { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; ExceptionReceivedHandler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.ExceptionReceivedHandler" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task)" />
      <MemberSignature Language="F#" Value="member this.ExceptionReceivedHandler : Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt;" Usage="Microsoft.Azure.ServiceBus.MessageHandlerOptions.ExceptionReceivedHandler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Tritt auf, wenn eine Ausnahme empfangen wird. Ermöglicht es Ihnen gefundenen Fehlern von der Meldungsverteilschleife benachrichtigt zu werden.
            Beim Empfang von Fehlern werden Anrufe automatisch wiederholt werden also nur zu Informationszwecken. </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAutoRenewDuration">
      <MemberSignature Language="C#" Value="public TimeSpan MaxAutoRenewDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxAutoRenewDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.MaxAutoRenewDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAutoRenewDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxAutoRenewDuration : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.MessageHandlerOptions.MaxAutoRenewDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die maximale Dauer, anhand derer die Sperre automatisch erneuert wird. Dieser Wert muss größer als die längste Dauer der nachrichtensperre sein; z. B. die LockDuration-Eigenschaft. </summary>
        <value>Die maximale Zeitspanne, während die Sperren automatisch verlängert werden.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentCalls">
      <MemberSignature Language="C#" Value="public int MaxConcurrentCalls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConcurrentCalls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.MaxConcurrentCalls" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentCalls As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentCalls : int with get, set" Usage="Microsoft.Azure.ServiceBus.MessageHandlerOptions.MaxConcurrentCalls" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die maximale Anzahl gleichzeitiger Aufrufe an den Rückruf, den die Meldungsverteilschleife initiieren soll.</summary>
        <value>Die maximale Anzahl gleichzeitiger Aufrufe an den Rückruf.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>