<Type Name="OnMessageOptions" FullName="Microsoft.ServiceBus.Messaging.OnMessageOptions">
  <TypeSignature Language="C#" Value="public sealed class OnMessageOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit OnMessageOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class OnMessageOptions" />
  <TypeSignature Language="F#" Value="type OnMessageOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Bietet Optionen, die Nachricht Datapump Verarbeitung mit zugeordneten <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage})" /> und <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OnMessageOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.OnMessageOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoComplete">
      <MemberSignature Language="C#" Value="public bool AutoComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.OnMessageOptions.AutoComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoComplete As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoComplete : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.OnMessageOptions.AutoComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob die Meldungsverteilschleife aufrufen sollte <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.Complete(System.Guid)" /> oder <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Complete(System.Guid)" /> für Nachrichten nach der Verarbeitung der Rückruf.</summary>
        <value>"true", die automatisch bei erfolgreicher Ausführung des Vorgangs die Verarbeitung der Nachricht abgeschlossen; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoRenewTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan AutoRenewTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AutoRenewTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.OnMessageOptions.AutoRenewTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoRenewTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AutoRenewTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.OnMessageOptions.AutoRenewTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die maximale Dauer, anhand derer die Sperre automatisch erneuert wird. Dieser Wert muss größer als die längste Dauer der nachrichtensperre sein; z. B. die LockDuration-Eigenschaft. </summary>
        <value>Die maximale Zeitspanne, während die Sperren automatisch verlängert werden. Der Standardwert ist 5 Minuten, und wenn Sie diesen Wert, um festlegen <see cref="F:System.TimeSpan.Zero" /> die Sperre nicht automatisch erneuert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionReceived">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; ExceptionReceived;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; ExceptionReceived" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.Messaging.OnMessageOptions.ExceptionReceived" />
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
        <summary>Tritt auf, wenn eine Ausnahme empfangen wird. Ermöglicht es Ihnen gefundenen Fehlern von der Meldungsverteilschleife benachrichtigt zu werden.
            Beim Empfang von Fehlern werden Anrufe automatisch wiederholt werden also nur zu Informationszwecken. </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentCalls">
      <MemberSignature Language="C#" Value="public int MaxConcurrentCalls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConcurrentCalls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.OnMessageOptions.MaxConcurrentCalls" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentCalls As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentCalls : int with get, set" Usage="Microsoft.ServiceBus.Messaging.OnMessageOptions.MaxConcurrentCalls" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
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