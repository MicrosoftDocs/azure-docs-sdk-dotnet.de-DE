<Type Name="EventDataBatch" FullName="Microsoft.Azure.EventHubs.EventDataBatch">
  <TypeSignature Language="C#" Value="public class EventDataBatch : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventDataBatch extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventDataBatch" />
  <TypeSignature Language="VB.NET" Value="Public Class EventDataBatch&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type EventDataBatch = class&#xA;    interface IDisposable" />
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
    <summary><span data-ttu-id="b1a6f-101">Eine Hilfsklasse zum Erstellen eines Batches von EventData-Objekten, die für SendBatch oder SendBatchAsync Aufruf verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="b1a6f-101">A helper class for creating a batch of EventData objects to be used for SendBatch or SendBatchAsync call.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventDataBatch (long maxSizeInBytes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 maxSizeInBytes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventDataBatch.#ctor(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxSizeInBytes As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventDataBatch : int64 -&gt; Microsoft.Azure.EventHubs.EventDataBatch" Usage="new Microsoft.Azure.EventHubs.EventDataBatch maxSizeInBytes" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxSizeInBytes" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="maxSizeInBytes"><span data-ttu-id="b1a6f-102">Die maximal zulässige Größe für den batch</span><span class="sxs-lookup"><span data-stu-id="b1a6f-102">The maximum size allowed for the batch</span></span></param>
        <summary>
            <span data-ttu-id="b1a6f-103">Erstellt einen neuen <see cref="T:Microsoft.Azure.EventHubs.EventDataBatch" />.</span><span class="sxs-lookup"><span data-stu-id="b1a6f-103">Creates a new <see cref="T:Microsoft.Azure.EventHubs.EventDataBatch" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventDataBatch.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.Azure.EventHubs.EventDataBatch.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="b1a6f-104">Ruft die aktuelle Ereignisanzahl im Batch ab.</span><span class="sxs-lookup"><span data-stu-id="b1a6f-104">Gets the current event count in the batch.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventDataBatch.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="eventDataBatch.Dispose " />
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
            <span data-ttu-id="b1a6f-105">Verwirft Ressourcen, die an eine EventDataBatch angefügt.</span><span class="sxs-lookup"><span data-stu-id="b1a6f-105">Disposes resources attached to an EventDataBatch.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToEnumerable">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt; ToEnumerable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt; ToEnumerable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventDataBatch.ToEnumerable" />
      <MemberSignature Language="VB.NET" Value="Public Function ToEnumerable () As IEnumerable(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.ToEnumerable : unit -&gt; seq&lt;Microsoft.Azure.EventHubs.EventData&gt;" Usage="eventDataBatch.ToEnumerable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="b1a6f-106">Konvertiert den Batch auf ein IEnumerable von EventData-Objekte, die von der Methode SendBatchAsync akzeptiert werden können.</span><span class="sxs-lookup"><span data-stu-id="b1a6f-106">Converts the batch to an IEnumerable of EventData objects that can be accepted by the SendBatchAsync method.</span></span></summary>
        <returns><span data-ttu-id="b1a6f-107">Gibt ein IEnumerable von EventData-Objekte zurück.</span><span class="sxs-lookup"><span data-stu-id="b1a6f-107">Returns an IEnumerable of EventData objects.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryAdd">
      <MemberSignature Language="C#" Value="public bool TryAdd (Microsoft.Azure.EventHubs.EventData eventData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryAdd(class Microsoft.Azure.EventHubs.EventData eventData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventDataBatch.TryAdd(Microsoft.Azure.EventHubs.EventData)" />
      <MemberSignature Language="F#" Value="member this.TryAdd : Microsoft.Azure.EventHubs.EventData -&gt; bool" Usage="eventDataBatch.TryAdd eventData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventData" Type="Microsoft.Azure.EventHubs.EventData" />
      </Parameters>
      <Docs>
        <param name="eventData"><span data-ttu-id="b1a6f-108">Das hinzuzufügende <see cref="T:Microsoft.Azure.EventHubs.EventData" />.</span><span class="sxs-lookup"><span data-stu-id="b1a6f-108">The <see cref="T:Microsoft.Azure.EventHubs.EventData" /> to add.</span></span></param>
        <summary><span data-ttu-id="b1a6f-109">Versucht, Hinzufügen von Ereignisdaten, die dem Batch, wenn der Batch-Größenlimit zulässig.</span><span class="sxs-lookup"><span data-stu-id="b1a6f-109">Tries to add an event data to the batch if permitted by the batch's size limit.</span></span></summary>
        <returns><span data-ttu-id="b1a6f-110">Ein boolescher Wert, der angibt, ob die Ereignisdaten an den Batch oder nicht hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="b1a6f-110">A boolean value indicating if the event data has been added to the batch or not.</span></span></returns>
        <remarks>
            <span data-ttu-id="b1a6f-111">Diese Methode überprüft die Größe des Batches, die EventData-Objekt, den festgelegten Grenzwert um festzustellen, ob der EventData-Objekt hinzugefügt werden kann.</span><span class="sxs-lookup"><span data-stu-id="b1a6f-111">This method checks the sizes of the batch, the EventData object and the specified limit to determine if the EventData object can be added.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="b1a6f-112">Wird ausgelöst, wenn die EventData null ist.</span><span class="sxs-lookup"><span data-stu-id="b1a6f-112">Thrown when the EventData is null.</span></span></exception>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="b1a6f-113">Wird ausgelöst, wenn der Batch bereits freigegeben ist.</span><span class="sxs-lookup"><span data-stu-id="b1a6f-113">Thrown when the batch is already disposed.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>