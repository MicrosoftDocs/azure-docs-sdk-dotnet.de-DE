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
    <summary><span data-ttu-id="d8ca1-101">Bietet Optionen, die Nachricht Datapump Verarbeitung mit zugeordneten <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage})" /> und <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />.</span><span class="sxs-lookup"><span data-stu-id="d8ca1-101">Provides options associated with message pump processing using <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage})" /> and <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />.</span></span></summary>
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
        <summary><span data-ttu-id="d8ca1-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d8ca1-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" /> class.</span></span></summary>
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
        <summary><span data-ttu-id="d8ca1-103">Ruft ab oder legt einen Wert, der angibt, ob die Meldungsverteilschleife aufrufen sollte <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.Complete(System.Guid)" /> oder <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Complete(System.Guid)" /> für Nachrichten nach der Verarbeitung der Rückruf.</span><span class="sxs-lookup"><span data-stu-id="d8ca1-103">Gets or sets a value that indicates whether the message-pump should call <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.Complete(System.Guid)" /> or <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Complete(System.Guid)" /> on messages after the callback has completed processing.</span></span></summary>
        <value><span data-ttu-id="d8ca1-104">"true", die automatisch bei erfolgreicher Ausführung des Vorgangs die Verarbeitung der Nachricht abgeschlossen; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="d8ca1-104">true to complete the message processing automatically on successful execution of the operation; otherwise, false.</span></span></value>
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
        <summary><span data-ttu-id="d8ca1-105">Ruft ab oder legt die maximale Dauer, anhand derer die Sperre automatisch erneuert wird.</span><span class="sxs-lookup"><span data-stu-id="d8ca1-105">Gets or sets the maximum duration within which the lock will be renewed automatically.</span></span> <span data-ttu-id="d8ca1-106">Dieser Wert muss größer als die längste Dauer der nachrichtensperre sein; z. B. die LockDuration-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="d8ca1-106">This value should be greater than the longest message lock duration; for example, the LockDuration Property.</span></span> </summary>
        <value><span data-ttu-id="d8ca1-107">Die maximale Zeitspanne, während die Sperren automatisch verlängert werden.</span><span class="sxs-lookup"><span data-stu-id="d8ca1-107">The maximum duration during which locks are automatically renewed.</span></span> <span data-ttu-id="d8ca1-108">Der Standardwert ist 5 Minuten, und wenn Sie diesen Wert, um festlegen <see cref="F:System.TimeSpan.Zero" /> die Sperre nicht automatisch erneuert.</span><span class="sxs-lookup"><span data-stu-id="d8ca1-108">The default value is 5 minutes, and if you set this value to <see cref="F:System.TimeSpan.Zero" /> the lock will not be automatically renewed.</span></span></value>
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
        <summary><span data-ttu-id="d8ca1-109">Tritt auf, wenn eine Ausnahme empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="d8ca1-109">Occurs when an exception is received.</span></span> <span data-ttu-id="d8ca1-110">Ermöglicht es Ihnen gefundenen Fehlern von der Meldungsverteilschleife benachrichtigt zu werden.</span><span class="sxs-lookup"><span data-stu-id="d8ca1-110">Enables you to be notified of any errors encountered by the message pump.</span></span>
            <span data-ttu-id="d8ca1-111">Beim Empfang von Fehlern werden Anrufe automatisch wiederholt werden also nur zu Informationszwecken.</span><span class="sxs-lookup"><span data-stu-id="d8ca1-111">When errors are received calls will automatically be retried, so this is informational.</span></span> </summary>
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
        <summary><span data-ttu-id="d8ca1-112">Ruft ab oder legt die maximale Anzahl gleichzeitiger Aufrufe an den Rückruf, den die Meldungsverteilschleife initiieren soll.</span><span class="sxs-lookup"><span data-stu-id="d8ca1-112">Gets or sets the maximum number of concurrent calls to the callback the message pump should initiate.</span></span></summary>
        <value><span data-ttu-id="d8ca1-113">Die maximale Anzahl gleichzeitiger Aufrufe an den Rückruf.</span><span class="sxs-lookup"><span data-stu-id="d8ca1-113">The maximum number of concurrent calls to the callback.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>