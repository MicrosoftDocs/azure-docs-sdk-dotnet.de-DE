<Type Name="OnShardMessageOptions" FullName="Microsoft.ServiceBus.Messaging.OnShardMessageOptions">
  <TypeSignature Language="C#" Value="public sealed class OnShardMessageOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit OnShardMessageOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.OnShardMessageOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class OnShardMessageOptions" />
  <TypeSignature Language="F#" Value="type OnShardMessageOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="a45e9-101">Stellt die verfügbaren Optionen für die Shard-Nachricht dar.</span><span class="sxs-lookup"><span data-stu-id="a45e9-101">Represents the available options for the shard message.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OnShardMessageOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.OnShardMessageOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="a45e9-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.OnShardMessageOptions" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a45e9-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.OnShardMessageOptions" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoCheckpointTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan AutoCheckpointTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AutoCheckpointTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.OnShardMessageOptions.AutoCheckpointTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoCheckpointTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AutoCheckpointTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.OnShardMessageOptions.AutoCheckpointTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a45e9-103">Ruft ab oder legt die Dauer des Prüfpunkts automatisch fest.</span><span class="sxs-lookup"><span data-stu-id="a45e9-103">Gets or sets the duration of the auto checkpoint.</span></span></summary>
        <value><span data-ttu-id="a45e9-104">Die Dauer des Prüfpunkts automatisch.</span><span class="sxs-lookup"><span data-stu-id="a45e9-104">The duration of the auto checkpoint.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionReceived">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; ExceptionReceived;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; ExceptionReceived" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.Messaging.OnShardMessageOptions.ExceptionReceived" />
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
        <summary><span data-ttu-id="a45e9-105">Tritt auf, wenn eine Ausnahme empfangen wurde.</span><span class="sxs-lookup"><span data-stu-id="a45e9-105">Occurs when an exception was received.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentCalls">
      <MemberSignature Language="C#" Value="public int MaxConcurrentCalls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConcurrentCalls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.OnShardMessageOptions.MaxConcurrentCalls" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentCalls As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentCalls : int with get, set" Usage="Microsoft.ServiceBus.Messaging.OnShardMessageOptions.MaxConcurrentCalls" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a45e9-106">Ruft ab oder legt die maximale Anzahl die maximale Anzahl gleichzeitiger Aufrufe.</span><span class="sxs-lookup"><span data-stu-id="a45e9-106">Gets or sets the maximum number of the maximum concurrent calls.</span></span></summary>
        <value><span data-ttu-id="a45e9-107">Die maximale Anzahl die maximale Anzahl gleichzeitiger Aufrufe.</span><span class="sxs-lookup"><span data-stu-id="a45e9-107">The maximum number of the maximum concurrent calls.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>