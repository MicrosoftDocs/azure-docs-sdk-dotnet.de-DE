<Type Name="InMemoryChannel" FullName="Microsoft.ApplicationInsights.Channel.InMemoryChannel">
  <TypeSignature Language="C#" Value="public class InMemoryChannel : IDisposable, Microsoft.ApplicationInsights.Channel.ITelemetryChannel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InMemoryChannel extends System.Object implements class Microsoft.ApplicationInsights.Channel.ITelemetryChannel, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Channel.InMemoryChannel" />
  <TypeSignature Language="VB.NET" Value="Public Class InMemoryChannel&#xA;Implements IDisposable, ITelemetryChannel" />
  <TypeSignature Language="F#" Value="type InMemoryChannel = class&#xA;    interface ITelemetryChannel&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.Channel.ITelemetryChannel</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="b190f-101">Stellt einen Kommunikationskanal zum Senden von Telemetriedaten an Application Insights über HTTPS.</span><span class="sxs-lookup"><span data-stu-id="b190f-101">Represents a communication channel for sending telemetry to Application Insights via HTTPS.</span></span> <span data-ttu-id="b190f-102">Ein Puffer, der nicht persistent ist um die Elemente in der Warteschlange Telemetrie gesendet werden, zu erzwingen, werden <see cref="M:Microsoft.ApplicationInsights.Channel.ITelemetryChannel.Flush" /> aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="b190f-102">There will be a buffer that will not be persisted, to enforce the queued telemetry items to be sent, <see cref="M:Microsoft.ApplicationInsights.Channel.ITelemetryChannel.Flush" /> should be called.</span></span>    
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InMemoryChannel ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.InMemoryChannel.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b190f-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ApplicationInsights.Channel.InMemoryChannel" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b190f-103">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.Channel.InMemoryChannel" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BacklogSize">
      <MemberSignature Language="C#" Value="public int BacklogSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 BacklogSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.InMemoryChannel.BacklogSize" />
      <MemberSignature Language="VB.NET" Value="Public Property BacklogSize As Integer" />
      <MemberSignature Language="F#" Value="member this.BacklogSize : int with get, set" Usage="Microsoft.ApplicationInsights.Channel.InMemoryChannel.BacklogSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b190f-104">Ruft ab oder legt die maximale Anzahl der Telemetrie-Elemente, die im Backlog gesendet werden können.</span><span class="sxs-lookup"><span data-stu-id="b190f-104">Gets or sets the maximum number of telemetry items that can be in the backlog to send.</span></span> <span data-ttu-id="b190f-105">Dies ist eine harte Grenze und Elemente gelöscht werden durch die <see cref="T:Microsoft.ApplicationInsights.Channel.InMemoryChannel" /> sobald dieser Grenzwert erreicht wird, bis Sie Elemente aus dem Puffer entladen werden.</span><span class="sxs-lookup"><span data-stu-id="b190f-105">This is a hard limit and Items will be dropped by the <see cref="T:Microsoft.ApplicationInsights.Channel.InMemoryChannel" /> once this limit is hit until items are drained from the buffer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeveloperMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DeveloperMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DeveloperMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.InMemoryChannel.DeveloperMode" />
      <MemberSignature Language="VB.NET" Value="Public Property DeveloperMode As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DeveloperMode : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.ApplicationInsights.Channel.InMemoryChannel.DeveloperMode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetryChannel.DeveloperMode</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b190f-106">Ruft ab oder legt einen Wert, der angibt, ob der telemetrieübertragung Entwicklermodus aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="b190f-106">Gets or sets a value indicating whether developer mode of telemetry transmission is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.InMemoryChannel.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="inMemoryChannel.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b190f-107">Löschen den Kanal.</span><span class="sxs-lookup"><span data-stu-id="b190f-107">Disposing the channel.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointAddress">
      <MemberSignature Language="C#" Value="public string EndpointAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndpointAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.InMemoryChannel.EndpointAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointAddress As String" />
      <MemberSignature Language="F#" Value="member this.EndpointAddress : string with get, set" Usage="Microsoft.ApplicationInsights.Channel.InMemoryChannel.EndpointAddress" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetryChannel.EndpointAddress</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b190f-108">Ruft ab oder legt die HTTP-Adresse, an die Telemetrie gesendet.</span><span class="sxs-lookup"><span data-stu-id="b190f-108">Gets or sets the HTTP address where the telemetry is sent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flush">
      <MemberSignature Language="C#" Value="public void Flush ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Flush() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.InMemoryChannel.Flush" />
      <MemberSignature Language="VB.NET" Value="Public Sub Flush ()" />
      <MemberSignature Language="F#" Value="abstract member Flush : unit -&gt; unit&#xA;override this.Flush : unit -&gt; unit" Usage="inMemoryChannel.Flush " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ApplicationInsights.Channel.ITelemetryChannel.Flush</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b190f-109">Sendet alle Telemetrie-Elemente, die im Arbeitsspeicher gespeichert.</span><span class="sxs-lookup"><span data-stu-id="b190f-109">Will send all the telemetry items stored in the memory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flush">
      <MemberSignature Language="C#" Value="public void Flush (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Flush(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.InMemoryChannel.Flush(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Flush (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.Flush : TimeSpan -&gt; unit" Usage="inMemoryChannel.Flush timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="b190f-110">Timeout-Intervall zum Senden von Abbrechen.</span><span class="sxs-lookup"><span data-stu-id="b190f-110">Timeout interval to abort sending.</span></span></param>
        <summary>
            <span data-ttu-id="b190f-111">Sendet alle Telemetrie-Elemente, die im Arbeitsspeicher gespeichert.</span><span class="sxs-lookup"><span data-stu-id="b190f-111">Will send all the telemetry items stored in the memory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTelemetryBufferCapacity">
      <MemberSignature Language="C#" Value="public int MaxTelemetryBufferCapacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxTelemetryBufferCapacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.InMemoryChannel.MaxTelemetryBufferCapacity" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTelemetryBufferCapacity As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxTelemetryBufferCapacity : int with get, set" Usage="Microsoft.ApplicationInsights.Channel.InMemoryChannel.MaxTelemetryBufferCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b190f-112">Ruft ab oder legt die maximale Anzahl von Elementen der Telemetrie sammeln sich in einem Speicher vor der <see cref="T:Microsoft.ApplicationInsights.Channel.InMemoryChannel" /> serialisieren sie für die Übertragung an Application Insights.</span><span class="sxs-lookup"><span data-stu-id="b190f-112">Gets or sets the maximum number of telemetry items will accumulate in a memory before the <see cref="T:Microsoft.ApplicationInsights.Channel.InMemoryChannel" /> serializing them for transmission to Application Insights.</span></span>
            <span data-ttu-id="b190f-113">Dies ist eine harte Grenze für wie viele nicht gesendete Elemente im Puffer werden kann.</span><span class="sxs-lookup"><span data-stu-id="b190f-113">This is not a hard limit on how many unsent items can be in the buffer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Send">
      <MemberSignature Language="C#" Value="public void Send (Microsoft.ApplicationInsights.Channel.ITelemetry item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Send(class Microsoft.ApplicationInsights.Channel.ITelemetry item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.InMemoryChannel.Send(Microsoft.ApplicationInsights.Channel.ITelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Send (item As ITelemetry)" />
      <MemberSignature Language="F#" Value="abstract member Send : Microsoft.ApplicationInsights.Channel.ITelemetry -&gt; unit&#xA;override this.Send : Microsoft.ApplicationInsights.Channel.ITelemetry -&gt; unit" Usage="inMemoryChannel.Send item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ApplicationInsights.Channel.ITelemetryChannel.Send(Microsoft.ApplicationInsights.Channel.ITelemetry)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.ApplicationInsights.Channel.ITelemetry" />
      </Parameters>
      <Docs>
        <param name="item">To be added.</param>
        <summary>
            <span data-ttu-id="b190f-114">Sendet eine Instanz des ITelemetry über diesen Kanal.</span><span class="sxs-lookup"><span data-stu-id="b190f-114">Sends an instance of ITelemetry through the channel.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendingInterval">
      <MemberSignature Language="C#" Value="public TimeSpan SendingInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan SendingInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.InMemoryChannel.SendingInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property SendingInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.SendingInterval : TimeSpan with get, set" Usage="Microsoft.ApplicationInsights.Channel.InMemoryChannel.SendingInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b190f-115">Abrufen oder Festlegen des Intervalls gesendet.</span><span class="sxs-lookup"><span data-stu-id="b190f-115">Gets or sets the sending interval.</span></span> <span data-ttu-id="b190f-116">Nach Ablauf des Intervalls <see cref="T:Microsoft.ApplicationInsights.Channel.InMemoryChannel" /> die akkumulierten Telemetrie-Elemente für die Übertragung serialisiert und unverschlüsselt gesendet.</span><span class="sxs-lookup"><span data-stu-id="b190f-116">Once the interval expires, <see cref="T:Microsoft.ApplicationInsights.Channel.InMemoryChannel" /> serializes the accumulated telemetry items for transmission and sends it over the wire.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>