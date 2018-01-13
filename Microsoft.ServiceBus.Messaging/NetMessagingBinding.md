<Type Name="NetMessagingBinding" FullName="Microsoft.ServiceBus.Messaging.NetMessagingBinding">
  <TypeSignature Language="C#" Value="public sealed class NetMessagingBinding : System.ServiceModel.Channels.Binding" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetMessagingBinding extends System.ServiceModel.Channels.Binding" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.NetMessagingBinding" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetMessagingBinding&#xA;Inherits Binding" />
  <TypeSignature Language="F#" Value="type NetMessagingBinding = class&#xA;    inherit Binding" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Channels.Binding</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="63f70-101">Stellt die Bindung, die für net-messaging verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="63f70-101">Represents the binding that is used for net messaging.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetMessagingBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="63f70-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingBinding" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="63f70-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingBinding" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetMessagingBinding (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingBinding.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configurationName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.NetMessagingBinding : string -&gt; Microsoft.ServiceBus.Messaging.NetMessagingBinding" Usage="new Microsoft.ServiceBus.Messaging.NetMessagingBinding configurationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configurationName"><span data-ttu-id="63f70-103">Die Konfiguration für die Initialisierung verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="63f70-103">The configuration to use for the initialization.</span></span></param>
        <summary><span data-ttu-id="63f70-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingBinding" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="63f70-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingBinding" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBindingElements">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElementCollection CreateBindingElements ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElementCollection CreateBindingElements() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingBinding.CreateBindingElements" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateBindingElements () As BindingElementCollection" />
      <MemberSignature Language="F#" Value="override this.CreateBindingElements : unit -&gt; System.ServiceModel.Channels.BindingElementCollection" Usage="netMessagingBinding.CreateBindingElements " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.BindingElementCollection</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="63f70-105">Gibt eine geordnete Auflistung von Bindungselementen zurück, die in der aktuellen Bindung enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="63f70-105">Returns an ordered collection of binding elements contained in the current binding.</span></span></summary>
        <returns><span data-ttu-id="63f70-106">Die <see cref="T:System.ServiceModel.Channels.BindingElementCollection" /> Objekt, das den geordneten Stapel von Bindungselementen, die durch beschrieben enthält die <see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingBinding" />.</span><span class="sxs-lookup"><span data-stu-id="63f70-106">The <see cref="T:System.ServiceModel.Channels.BindingElementCollection" /> object which contains the ordered stack of binding elements described by the <see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingBinding" />.</span></span> <span data-ttu-id="63f70-107">Die Reihenfolge der Bindungselemente von unten ist die Transport-, Codierungs- und Sicherheit.</span><span class="sxs-lookup"><span data-stu-id="63f70-107">The order of the binding elements starting from the bottom is transport, encoding, and security.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingBinding.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingBinding.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(524288)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="63f70-108">Ruft die maximal zulässige Größe für einen Pufferpool ab, der TCP-Meldungen speichert, die von der Bindung verarbeitet werden, oder legt diese Größe fest.</span><span class="sxs-lookup"><span data-stu-id="63f70-108">Gets or sets the maximum size allowed for a buffer pool that stores TCP messages processed by the binding.</span></span></summary>
        <value><span data-ttu-id="63f70-109">Die maximal zulässige Größe für einen Pufferpool, der TCP-Meldungen speichert, die von der Bindung verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="63f70-109">The maximum size allowed for a buffer pool that stores TCP messages processed by the binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingBinding.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingBinding.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(-1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="63f70-110">Ruft ab oder legt die Anzahl der Nachrichten, die der Empfänger einer Nachricht im Voraus abgerufen werden kann.</span><span class="sxs-lookup"><span data-stu-id="63f70-110">Gets or sets the number of messages that the message receiver can fetch in advance.</span></span></summary>
        <value><span data-ttu-id="63f70-111">Die Anzahl der Nachrichten, die der Empfänger einer Nachricht im Voraus abgerufen werden kann.</span><span class="sxs-lookup"><span data-stu-id="63f70-111">The number of messages that the message receiver can fetch in advance.</span></span></value>
        <remarks> <span data-ttu-id="63f70-112">Wird für die nächste empfangsaufruf an den Server wirksam.</span><span class="sxs-lookup"><span data-stu-id="63f70-112">Takes effect on the next receive call to the server.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingBinding.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.Messaging.NetMessagingBinding.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="63f70-113">Ruft das URI-Transportschema für die Kanäle und die Listener ab, die mit dieser Bindung konfiguriert werden.</span><span class="sxs-lookup"><span data-stu-id="63f70-113">Gets the URI transport scheme for the channels and listeners that are configured with this binding.</span></span></summary>
        <value><span data-ttu-id="63f70-114">Das URI-Transportschema für die Kanäle und Listener, die mit dieser Bindung konfiguriert sind.</span><span class="sxs-lookup"><span data-stu-id="63f70-114">The URI transport scheme for the channels and listeners that are configured with this binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionIdleTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan SessionIdleTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan SessionIdleTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingBinding.SessionIdleTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionIdleTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.SessionIdleTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingBinding.SessionIdleTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(typeof(System.TimeSpan), "00:01:00")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="63f70-115">Ruft ab oder legt den Timespan-Wert, der Zeitraum der Inaktivität angibt, die die Sitzung, bevor ein Timeout auftritt wartet.</span><span class="sxs-lookup"><span data-stu-id="63f70-115">Gets or sets the timespan value that specifies period of inactivity that the session waits before timing out.</span></span></summary>
        <value><span data-ttu-id="63f70-116">Der Timespan-Wert, der Zeitraum der Inaktivität angibt, die die Sitzung, bevor ein Timeout auftritt wartet.</span><span class="sxs-lookup"><span data-stu-id="63f70-116">The timespan value that specifies period of inactivity that the session waits before timing out.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransportSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings TransportSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings TransportSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingBinding.TransportSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property TransportSettings As NetMessagingTransportSettings" />
      <MemberSignature Language="F#" Value="member this.TransportSettings : Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingBinding.TransportSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="63f70-117">Ruft ab oder legt die transporteinstellungen für die net-messaging.</span><span class="sxs-lookup"><span data-stu-id="63f70-117">Gets or sets the transport settings for the net messaging.</span></span></summary>
        <value><span data-ttu-id="63f70-118">Die transporteinstellungen für die net-messaging.</span><span class="sxs-lookup"><span data-stu-id="63f70-118">The transport settings for the net messaging.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>