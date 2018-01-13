<Type Name="IPartitionReceiveHandler" FullName="Microsoft.Azure.EventHubs.IPartitionReceiveHandler">
  <TypeSignature Language="C#" Value="public interface IPartitionReceiveHandler" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPartitionReceiveHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.IPartitionReceiveHandler" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPartitionReceiveHandler" />
  <TypeSignature Language="F#" Value="type IPartitionReceiveHandler = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b81cd-101">Eine Ereignishandler-Schnittstelle für den Empfangsvorgang.</span><span class="sxs-lookup"><span data-stu-id="b81cd-101">A handler interface for the receive operation.</span></span> <span data-ttu-id="b81cd-102">Verwenden Sie Implementierung dieser Schnittstelle Handlung des Benutzers an, wenn mit <see cref="M:Microsoft.Azure.EventHubs.PartitionReceiver.SetReceiveHandler(Microsoft.Azure.EventHubs.IPartitionReceiveHandler)" />.</span><span class="sxs-lookup"><span data-stu-id="b81cd-102">Use any implementation of this interface to specify user action when using <see cref="M:Microsoft.Azure.EventHubs.PartitionReceiver.SetReceiveHandler(Microsoft.Azure.EventHubs.IPartitionReceiveHandler)" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MaxBatchSize">
      <MemberSignature Language="C#" Value="public int MaxBatchSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBatchSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.IPartitionReceiveHandler.MaxBatchSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxBatchSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBatchSize : int" Usage="Microsoft.Azure.EventHubs.IPartitionReceiveHandler.MaxBatchSize" />
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
        <summary>
            <span data-ttu-id="b81cd-103">Ruft die maximale Batchgröße ab.</span><span class="sxs-lookup"><span data-stu-id="b81cd-103">Gets the maximum batch size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessErrorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProcessErrorAsync (Exception error);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ProcessErrorAsync(class System.Exception error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.IPartitionReceiveHandler.ProcessErrorAsync(System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Function ProcessErrorAsync (error As Exception) As Task" />
      <MemberSignature Language="F#" Value="abstract member ProcessErrorAsync : Exception -&gt; System.Threading.Tasks.Task" Usage="iPartitionReceiveHandler.ProcessErrorAsync error" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="error" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="error"><span data-ttu-id="b81cd-104">Die <see cref="T:System.Exception" /> verarbeitet werden</span><span class="sxs-lookup"><span data-stu-id="b81cd-104">The <see cref="T:System.Exception" /> to be processed</span></span></param>
        <summary>
            <span data-ttu-id="b81cd-105">Implementieren Sie, um Ausnahmen zu behandeln, die während der Empfang von Ereignissen ausgelöst werden.</span><span class="sxs-lookup"><span data-stu-id="b81cd-105">Implement in order to handle exceptions that are thrown during receipt of events.</span></span>
            </summary>
        <returns><span data-ttu-id="b81cd-106">Ein Vorgang asynchronour</span><span class="sxs-lookup"><span data-stu-id="b81cd-106">An asynchronour operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessEventsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProcessEventsAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt; events);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ProcessEventsAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt; events) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.IPartitionReceiveHandler.ProcessEventsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Function ProcessEventsAsync (events As IEnumerable(Of EventData)) As Task" />
      <MemberSignature Language="F#" Value="abstract member ProcessEventsAsync : seq&lt;Microsoft.Azure.EventHubs.EventData&gt; -&gt; System.Threading.Tasks.Task" Usage="iPartitionReceiveHandler.ProcessEventsAsync events" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="events" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="events"><span data-ttu-id="b81cd-107">Die Liste der abgerufenen Ereignisse aus der entsprechenden PartitionReceiver.</span><span class="sxs-lookup"><span data-stu-id="b81cd-107">The list of fetched events from the corresponding PartitionReceiver.</span></span></param>
        <summary>
            <span data-ttu-id="b81cd-108">Benutzer sollten diese Methode, um die Aktion, die auf die empfangenen Ereignisse geben implementieren.</span><span class="sxs-lookup"><span data-stu-id="b81cd-108">Users should implement this method to specify the action to be performed on the received events.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.EventHubs.PartitionReceiver.ReceiveAsync(System.Int32)" />
      </Docs>
    </Member>
  </Members>
</Type>