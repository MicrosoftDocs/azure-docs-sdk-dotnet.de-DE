<Type Name="EventData" FullName="Microsoft.Azure.EventHubs.EventData">
  <TypeSignature Language="C#" Value="public class EventData : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventData extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventData" />
  <TypeSignature Language="VB.NET" Value="Public Class EventData&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type EventData = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="8e15c-101">Die Datenstruktur, die das Ereignis wird gesendet an und Empfangen von EventHubs kapseln.</span><span class="sxs-lookup"><span data-stu-id="8e15c-101">The data structure encapsulating the Event being sent-to and received-from EventHubs.</span></span>
            <span data-ttu-id="8e15c-102">Jede Partition EventHubs kann als Datenstrom von EventData visuell dargestellt werden.</span><span class="sxs-lookup"><span data-stu-id="8e15c-102">Each EventHubs partition can be visualized as a Stream of EventData.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (ArraySegment&lt;byte&gt; arraySegment);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.ArraySegment`1&lt;unsigned int8&gt; arraySegment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventData.#ctor(System.ArraySegment{System.Byte})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (arraySegment As ArraySegment(Of Byte))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventData : ArraySegment&lt;byte&gt; -&gt; Microsoft.Azure.EventHubs.EventData" Usage="new Microsoft.Azure.EventHubs.EventData arraySegment" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="arraySegment" Type="System.ArraySegment&lt;System.Byte&gt;" />
      </Parameters>
      <Docs>
        <param name="arraySegment"><span data-ttu-id="8e15c-103">Die Nutzlast Bytes, die Offset und die Länge, die an den Event Hub gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="8e15c-103">The payload bytes, offset and length to be sent to the EventHub.</span></span></param>
        <summary>
            <span data-ttu-id="8e15c-104">Erstellen von EventData an Event Hub senden.</span><span class="sxs-lookup"><span data-stu-id="8e15c-104">Construct EventData to send to EventHub.</span></span>
            <span data-ttu-id="8e15c-105">Ist der normale Muster zum Erstellen einer EventData senden: <para>ich.  Serialisieren Sie die sendende ApplicationEvent in Bytes an Event Hub gesendet werden. </para> <para>Ii. Wenn komplexe Serialisierungslogik beteiligt ist (z. B.: mehrere Typen von Daten)-Hinzufügen einer Verwendung des Hinweises die <see cref="P:Microsoft.Azure.EventHubs.EventData.Properties" /> für den Consumer.</para></span><span class="sxs-lookup"><span data-stu-id="8e15c-105">Typical pattern to create a Sending EventData is: <para>i.  Serialize the sending ApplicationEvent to be sent to EventHub into bytes.</para><para>ii. If complex serialization logic is involved (for example: multiple types of data) - add a Hint using the <see cref="P:Microsoft.Azure.EventHubs.EventData.Properties" /> for the Consumer.</para></span></span></summary>
        <remarks>To be added.</remarks>
        <example><span data-ttu-id="8e15c-106">Beispielcode:</span><span class="sxs-lookup"><span data-stu-id="8e15c-106">Sample Code:</span></span>
            <code>
            EventData eventData = new EventData(new ArraySegment&lt;byte&gt;(eventBytes, offset, count));
            eventData.Properties["eventType"] = "com.microsoft.azure.monitoring.EtlEvent";
            await partitionSender.SendAsync(eventData);
            </code></example>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (byte[] array);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] array) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventData.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (array As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventData : byte[] -&gt; Microsoft.Azure.EventHubs.EventData" Usage="new Microsoft.Azure.EventHubs.EventData array" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="array" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="array"><span data-ttu-id="8e15c-107">Die tatsächliche Nutzlast von Daten in Bytes, die an den Event Hub gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="8e15c-107">The actual payload of data in bytes to be sent to the EventHub.</span></span></param>
        <summary>
            <span data-ttu-id="8e15c-108">Erstellen von EventData an Event Hub senden.</span><span class="sxs-lookup"><span data-stu-id="8e15c-108">Construct EventData to send to EventHub.</span></span>
            <span data-ttu-id="8e15c-109">Ist der normale Muster zum Erstellen einer EventData senden: <para>ich. Serialisieren Sie die sendende ApplicationEvent an EventHubs gesendet werden, in Bytes. </para> <para>Ii. Wenn komplexe Serialisierungslogik beteiligt ist (z. B.: mehrere Typen von Daten)-Hinzufügen einer Verwendung des Hinweises die <see cref="P:Microsoft.Azure.EventHubs.EventData.Properties" /> für den Consumer.</para></span><span class="sxs-lookup"><span data-stu-id="8e15c-109">Typical pattern to create a Sending EventData is: <para>i. Serialize the sending ApplicationEvent to be sent to EventHubs into bytes.</para><para>ii. If complex serialization logic is involved (for example: multiple types of data) - add a Hint using the <see cref="P:Microsoft.Azure.EventHubs.EventData.Properties" /> for the Consumer.</para></span></span></summary>
        <remarks>To be added.</remarks>
        <example><span data-ttu-id="8e15c-110">Beispielcode:</span><span class="sxs-lookup"><span data-stu-id="8e15c-110">Sample Code:</span></span>
            <code>
            EventData eventData = new EventData(telemetryEventBytes);
            eventData.Properties["eventType"] = "com.microsoft.azure.monitoring.EtlEvent";
            await partitionSender.SendAsync(eventData);
            </code></example>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public ArraySegment&lt;byte&gt; Body { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ArraySegment`1&lt;unsigned int8&gt; Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventData.Body" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Body As ArraySegment(Of Byte)" />
      <MemberSignature Language="F#" Value="member this.Body : ArraySegment&lt;byte&gt;" Usage="Microsoft.Azure.EventHubs.EventData.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ArraySegment&lt;System.Byte&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e15c-111">Rufen Sie tatsächliche Nutzlast/Daten von EventData umschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="8e15c-111">Get the actual Payload/Data wrapped by EventData.</span></span>
            <span data-ttu-id="8e15c-112">Dies sollte verwendet werden, nach dem Empfang von EventData mit <see cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="8e15c-112">This is intended to be used after receiving EventData using <see cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventData.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="eventData.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8e15c-113">Gibt die Ressourcen, die an der Ereignisdaten frei</span><span class="sxs-lookup"><span data-stu-id="8e15c-113">Disposes resources attached to an Event Data</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventData.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.EventHubs.EventData.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e15c-114">Eigenschaftenbehälter für die Anwendung</span><span class="sxs-lookup"><span data-stu-id="8e15c-114">Application property bag</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemProperties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection SystemProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.EventHubs.EventData/SystemPropertiesCollection SystemProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventData.SystemProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SystemProperties As EventData.SystemPropertiesCollection" />
      <MemberSignature Language="F#" Value="member this.SystemProperties : Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection" Usage="Microsoft.Azure.EventHubs.EventData.SystemProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventData+SystemPropertiesCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e15c-115">SystemProperties, die vom EventHubService aufgefüllt werden.</span><span class="sxs-lookup"><span data-stu-id="8e15c-115">SystemProperties that are populated by EventHubService.</span></span>
            <span data-ttu-id="8e15c-116">Wie diese vom Dienst aufgefüllt werden, sind sie nur auf eine empfangene EventData vorhanden.</span><span class="sxs-lookup"><span data-stu-id="8e15c-116">As these are populated by Service, they are only present on a Received EventData.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>