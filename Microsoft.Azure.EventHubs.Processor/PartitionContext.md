<Type Name="PartitionContext" FullName="Microsoft.Azure.EventHubs.Processor.PartitionContext">
  <TypeSignature Language="C#" Value="public class PartitionContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PartitionContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.PartitionContext" />
  <TypeSignature Language="VB.NET" Value="Public Class PartitionContext" />
  <TypeSignature Language="F#" Value="type PartitionContext = class" />
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
            <span data-ttu-id="ba7b3-101">Kapselt Informationen, die im Zusammenhang mit einer Event Hubs-Partition verwendeten <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />.</span><span class="sxs-lookup"><span data-stu-id="ba7b3-101">Encapsulates information related to an Event Hubs partition used by <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CheckpointAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CheckpointAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.PartitionContext.CheckpointAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CheckpointAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CheckpointAsync : unit -&gt; System.Threading.Tasks.Task" Usage="partitionContext.CheckpointAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ba7b3-102">Schreibt den aktuellen Offset und SequenceNumber auf den Prüfpunkt Store über die Checkpoint-Manager.</span><span class="sxs-lookup"><span data-stu-id="ba7b3-102">Writes the current offset and sequenceNumber to the checkpoint store via the checkpoint manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CheckpointAsync (Microsoft.Azure.EventHubs.EventData eventData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CheckpointAsync(class Microsoft.Azure.EventHubs.EventData eventData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.PartitionContext.CheckpointAsync(Microsoft.Azure.EventHubs.EventData)" />
      <MemberSignature Language="F#" Value="member this.CheckpointAsync : Microsoft.Azure.EventHubs.EventData -&gt; System.Threading.Tasks.Task" Usage="partitionContext.CheckpointAsync eventData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventData" Type="Microsoft.Azure.EventHubs.EventData" />
      </Parameters>
      <Docs>
        <param name="eventData"><span data-ttu-id="ba7b3-103">Eine empfangene EventData mit gültigen Offset und einer sequenceNumber</span><span class="sxs-lookup"><span data-stu-id="ba7b3-103">A received EventData with valid offset and sequenceNumber</span></span></param>
        <summary>
            <span data-ttu-id="ba7b3-104">Speichert den Offset und SequenceNumber aus der angegebenen empfangenen EventData-Instanz, und klicken Sie dann diese Werte in den Prüfpunkt Store über die Checkpoint-Manager schreibt.</span><span class="sxs-lookup"><span data-stu-id="ba7b3-104">Stores the offset and sequenceNumber from the provided received EventData instance, then writes those values to the checkpoint store via the checkpoint manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="ba7b3-105">Wenn EventData festgelegten null ist.</span><span class="sxs-lookup"><span data-stu-id="ba7b3-105">If suplied eventData is null</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="ba7b3-106">Wenn die SequenceNumber kleiner als der letzte Wert des geprüften ist</span><span class="sxs-lookup"><span data-stu-id="ba7b3-106">If the sequenceNumber is less than the last checkpointed value</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ConsumerGroupName">
      <MemberSignature Language="C#" Value="public string ConsumerGroupName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsumerGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.PartitionContext.ConsumerGroupName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsumerGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ConsumerGroupName : string" Usage="Microsoft.Azure.EventHubs.Processor.PartitionContext.ConsumerGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba7b3-107">Ruft den Namen der Gruppe "Consumer".</span><span class="sxs-lookup"><span data-stu-id="ba7b3-107">Gets the name of the consumer group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubPath">
      <MemberSignature Language="C#" Value="public string EventHubPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.PartitionContext.EventHubPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubPath As String" />
      <MemberSignature Language="F#" Value="member this.EventHubPath : string" Usage="Microsoft.Azure.EventHubs.Processor.PartitionContext.EventHubPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba7b3-108">Ruft den Pfad des Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="ba7b3-108">Gets the path of the event hub.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Owner">
      <MemberSignature Language="C#" Value="public string Owner { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Owner" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.PartitionContext.Owner" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Owner As String" />
      <MemberSignature Language="F#" Value="member this.Owner : string" Usage="Microsoft.Azure.EventHubs.Processor.PartitionContext.Owner" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba7b3-109">Ruft den Host-Besitzer für die Partition ab.</span><span class="sxs-lookup"><span data-stu-id="ba7b3-109">Gets the host owner for the partition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.PartitionContext.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.Azure.EventHubs.Processor.PartitionContext.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba7b3-110">Ruft die Partitions-ID für den Kontext ab.</span><span class="sxs-lookup"><span data-stu-id="ba7b3-110">Gets the partition ID for the context.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.ReceiverRuntimeInformation RuntimeInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.EventHubs.ReceiverRuntimeInformation RuntimeInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.PartitionContext.RuntimeInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RuntimeInformation As ReceiverRuntimeInformation" />
      <MemberSignature Language="F#" Value="member this.RuntimeInformation : Microsoft.Azure.EventHubs.ReceiverRuntimeInformation" Usage="Microsoft.Azure.EventHubs.Processor.PartitionContext.RuntimeInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.ReceiverRuntimeInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba7b3-111">Ruft die ungefähre Empfänger Laufzeitinformationen für eine logische Partition einen Event Hub ab.</span><span class="sxs-lookup"><span data-stu-id="ba7b3-111">Gets the approximate receiver runtime information for a logical partition of an Event Hub.</span></span>
            <span data-ttu-id="ba7b3-112">Um die Einstellung zu aktivieren, finden Sie unter<see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.EnableReceiverRuntimeMetric" /></span><span class="sxs-lookup"><span data-stu-id="ba7b3-112">To enable the setting, refer to <see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.EnableReceiverRuntimeMetric" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.PartitionContext.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionContext.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ba7b3-113">Stellt den Kontext der Partition in der folgenden format:"PartitionContext({EventHubPath}/{ConsumerGroupName}/{PartitionId}/{SequenceNumber})"</span><span class="sxs-lookup"><span data-stu-id="ba7b3-113">Provides the parition context in the following format:"PartitionContext({EventHubPath}/{ConsumerGroupName}/{PartitionId}/{SequenceNumber})"</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>