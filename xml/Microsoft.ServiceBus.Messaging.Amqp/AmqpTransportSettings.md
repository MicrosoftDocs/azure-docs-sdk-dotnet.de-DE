<Type Name="AmqpTransportSettings" FullName="Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings">
  <TypeSignature Language="C#" Value="public sealed class AmqpTransportSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AmqpTransportSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AmqpTransportSettings" />
  <TypeSignature Language="F#" Value="type AmqpTransportSettings = class&#xA;    interface ITransportSettings&#xA;    interface IServiceBusSecuritySettings" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="2d152-101">Stellt für das Advanced Message Queuing Protocol-Transport dar.</span><span class="sxs-lookup"><span data-stu-id="2d152-101">Represents the Advanced Message Queuing Protocol transport settings.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmqpTransportSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="2d152-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2d152-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchFlushInterval">
      <MemberSignature Language="C#" Value="public TimeSpan BatchFlushInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan BatchFlushInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.BatchFlushInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchFlushInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.BatchFlushInterval : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.BatchFlushInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2d152-103">Ruft ab, oder legt ihn fest batchleerungsintervall, der dem Transport zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="2d152-103">Gets or sets the batch flush interval associated with the transport.</span></span></summary>
        <value><span data-ttu-id="2d152-104">Die batchleerungsintervall dem Transport zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="2d152-104">The batch flush interval associated with the transport.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public object Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Object" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; obj&#xA;override this.Clone : unit -&gt; obj" Usage="amqpTransportSettings.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.ITransportSettings.Clone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="2d152-105">Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz darstellt.</span><span class="sxs-lookup"><span data-stu-id="2d152-105">Creates a new object that is a copy of the current instance.</span></span></summary>
        <returns><span data-ttu-id="2d152-106">Ein neues Objekt, das eine Kopie dieser Instanz ist.</span><span class="sxs-lookup"><span data-stu-id="2d152-106">A new object that is a copy of this instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableLinkRedirect">
      <MemberSignature Language="C#" Value="public bool EnableLinkRedirect { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableLinkRedirect" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.EnableLinkRedirect" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableLinkRedirect As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableLinkRedirect : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.EnableLinkRedirect" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> <span data-ttu-id="2d152-107">Ruft ab oder legt einen Wert, der angibt, ob dieser Transport an die Back-End-Server-umgeleitet werden kann.</span><span class="sxs-lookup"><span data-stu-id="2d152-107">Gets or sets a value indicating whether this transport is ready to be redirected to the server backend.</span></span> </summary>
        <value> <span data-ttu-id="2d152-108">"true", wenn dieser Transport Umleitung, die vom Server zugelassen teilnehmen möchte.</span><span class="sxs-lookup"><span data-stu-id="2d152-108">true if this transport wants to participate in redirect allowed by the server.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableReceiverRuntimeMetric">
      <MemberSignature Language="C#" Value="public bool EnableReceiverRuntimeMetric { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableReceiverRuntimeMetric" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.EnableReceiverRuntimeMetric" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableReceiverRuntimeMetric As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableReceiverRuntimeMetric : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.EnableReceiverRuntimeMetric" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> <span data-ttu-id="2d152-109">Ruft ab oder legt einen Wert, der angibt, ob der Empfänger die Common Language Runtime-Metrik aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="2d152-109">Gets or sets a value indicating whether the runtime metric of a receiver is enabled.</span></span> </summary>
        <value> <span data-ttu-id="2d152-110">"true", wenn ein Client zugreifen möchte <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" /> mit <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="2d152-110">true if a client wants to access <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" /> using <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxFrameSize">
      <MemberSignature Language="C#" Value="public int MaxFrameSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxFrameSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.MaxFrameSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxFrameSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxFrameSize : int with get, set" Usage="Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.MaxFrameSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2d152-111">Ruft ab oder legt die maximale Größe fest.</span><span class="sxs-lookup"><span data-stu-id="2d152-111">Gets or sets the maximum frame size.</span></span></summary>
        <value><span data-ttu-id="2d152-112">Die maximale Größe.</span><span class="sxs-lookup"><span data-stu-id="2d152-112">The maximum frame size.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseSslStreamSecurity">
      <MemberSignature Language="C#" Value="public bool UseSslStreamSecurity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseSslStreamSecurity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.UseSslStreamSecurity" />
      <MemberSignature Language="VB.NET" Value="Public Property UseSslStreamSecurity As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseSslStreamSecurity : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.UseSslStreamSecurity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2d152-113">Ruft einen Wert, der angibt, ob die SSL-Datenstroms ein benutzerdefiniertes Bindungselement verwendet.</span><span class="sxs-lookup"><span data-stu-id="2d152-113">Gets a value that indicates whether the SSL stream uses a custom binding element.</span></span></summary>
        <value><span data-ttu-id="2d152-114">"true", wenn die SSL-Datenstroms ein benutzerdefiniertes Bindungselement verwendet; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="2d152-114">true if the SSL stream uses a custom binding element; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>