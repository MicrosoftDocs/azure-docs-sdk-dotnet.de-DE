<Type Name="PartitionContext" FullName="Microsoft.ServiceBus.Messaging.PartitionContext">
  <TypeSignature Language="C#" Value="public class PartitionContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PartitionContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.PartitionContext" />
  <TypeSignature Language="VB.NET" Value="Public Class PartitionContext" />
  <TypeSignature Language="F#" Value="type PartitionContext = class&#xA;    interface ICheckpointer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="b7546-101">Kapselt Informationen, die im Zusammenhang mit einer Event Hubs-Partition verwendeten <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span><span class="sxs-lookup"><span data-stu-id="b7546-101">Encapsulates information related to an Event Hubs partition used by <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PartitionContext.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b7546-102">Dies wird hauptsächlich für Komponententests IEventProcessor Logik bereit, damit verschiedene Mockframeworks verwendet werden können, um ein Mock für PartitionContext übergeben erstellt.</span><span class="sxs-lookup"><span data-stu-id="b7546-102">This is mainly created for unit testing IEventProcessor logic so various mocking frameworks can be used to pass in a mock for PartitionContext.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CheckpointAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CheckpointAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CheckpointAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CheckpointAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.CheckpointAsync : unit -&gt; System.Threading.Tasks.Task" Usage="partitionContext.CheckpointAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.ICheckpointer.CheckpointAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="b7546-103">Prüfpunkte Fortschritt einen Nachrichtenstream Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="b7546-103">Checkpoints progress of an Event Hubs message stream.</span></span> <span data-ttu-id="b7546-104">Stellen Sie sicher, dass diese Methode aufrufen, nachdem alle Nachrichten in einem Batch verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="b7546-104">Make sure to call this method once all the messages in a batch are processed.</span></span></summary>
        <returns><span data-ttu-id="b7546-105">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b7546-105">The task representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CheckpointAsync (Microsoft.ServiceBus.Messaging.EventData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CheckpointAsync(class Microsoft.ServiceBus.Messaging.EventData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />
      <MemberSignature Language="VB.NET" Value="Public Function CheckpointAsync (data As EventData) As Task" />
      <MemberSignature Language="F#" Value="abstract member CheckpointAsync : Microsoft.ServiceBus.Messaging.EventData -&gt; System.Threading.Tasks.Task&#xA;override this.CheckpointAsync : Microsoft.ServiceBus.Messaging.EventData -&gt; System.Threading.Tasks.Task" Usage="partitionContext.CheckpointAsync data" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.ICheckpointer.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="Microsoft.ServiceBus.Messaging.EventData" />
      </Parameters>
      <Docs>
        <param name="data"><span data-ttu-id="b7546-106">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> Objekt, für die Prüfung der Zustand des Streams verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="b7546-106">An <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> object to use for checkpointing the state of the stream.</span></span></param>
        <summary><span data-ttu-id="b7546-107">Prüfpunkte Status des Ereignis-Hubs Nachrichten Stream mit dem angegebenen Offset.</span><span class="sxs-lookup"><span data-stu-id="b7546-107">Checkpoints progress of an Event Hubs message stream with the specified offset.</span></span></summary>
        <returns><span data-ttu-id="b7546-108">Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b7546-108">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsumerGroupName">
      <MemberSignature Language="C#" Value="public string ConsumerGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsumerGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionContext.ConsumerGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsumerGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ConsumerGroupName : string with get, set" Usage="Microsoft.ServiceBus.Messaging.PartitionContext.ConsumerGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="b7546-109">Ruft ab oder legt den Namen der Gruppe "Consumer".</span><span class="sxs-lookup"><span data-stu-id="b7546-109">Gets or sets the name of the consumer group.</span></span></summary>
        <value><span data-ttu-id="b7546-110">Der Name der Gruppe "Consumer".</span><span class="sxs-lookup"><span data-stu-id="b7546-110">The name of the consumer group.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubPath">
      <MemberSignature Language="C#" Value="public string EventHubPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionContext.EventHubPath" />
      <MemberSignature Language="VB.NET" Value="Public Property EventHubPath As String" />
      <MemberSignature Language="F#" Value="member this.EventHubPath : string with get, set" Usage="Microsoft.ServiceBus.Messaging.PartitionContext.EventHubPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="b7546-111">Ruft ab oder legt den Pfad des Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="b7546-111">Gets or sets the path of the event hub.</span></span></summary>
        <value><span data-ttu-id="b7546-112">Der Pfad des Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="b7546-112">The path of the event hub.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lease">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.Lease Lease { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.Lease Lease" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionContext.Lease" />
      <MemberSignature Language="VB.NET" Value="Public Property Lease As Lease" />
      <MemberSignature Language="F#" Value="member this.Lease : Microsoft.ServiceBus.Messaging.Lease with get, set" Usage="Microsoft.ServiceBus.Messaging.PartitionContext.Lease" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.Lease</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="b7546-113">Abrufen oder festlegen die messaging-Lease.</span><span class="sxs-lookup"><span data-stu-id="b7546-113">Gets or sets the messaging lease.</span></span></summary>
        <value><span data-ttu-id="b7546-114">Die messaging-Lease.</span><span class="sxs-lookup"><span data-stu-id="b7546-114">The messaging lease.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeInfo">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo RuntimeInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo RuntimeInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionContext.RuntimeInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RuntimeInfo As ReceiverRuntimeInfo" />
      <MemberSignature Language="F#" Value="member this.RuntimeInfo : Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" Usage="Microsoft.ServiceBus.Messaging.PartitionContext.RuntimeInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7546-115">Ruft die ungefähre Empfänger Laufzeitinformationen für eine logische Partition einen Event Hub ab.</span><span class="sxs-lookup"><span data-stu-id="b7546-115">Gets the approximate receiver runtime information for a logical partition of an Event Hub.</span></span>
            <span data-ttu-id="b7546-116">Um die Einstellung zu aktivieren, finden Sie unter<see cref="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.EnableReceiverRuntimeMetric" /></span><span class="sxs-lookup"><span data-stu-id="b7546-116">To enable the setting, refer to <see cref="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.EnableReceiverRuntimeMetric" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>