<Type Name="EventDataBatch" FullName="Microsoft.ServiceBus.Messaging.EventDataBatch">
  <TypeSignature Language="C#" Value="public sealed class EventDataBatch : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventDataBatch extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventDataBatch" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventDataBatch&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type EventDataBatch = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            Eine Hilfsklasse zum Erstellen eines Batches von EventData-Objekten, die für SendBatch oder SendBatchAsync Aufruf verwendet werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventDataBatch (long maxSizeInBytes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 maxSizeInBytes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventDataBatch.#ctor(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxSizeInBytes As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventDataBatch : int64 -&gt; Microsoft.ServiceBus.Messaging.EventDataBatch" Usage="new Microsoft.ServiceBus.Messaging.EventDataBatch maxSizeInBytes" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxSizeInBytes" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="maxSizeInBytes">Die maximale Größe der serialisierten batchnachricht.</param>
        <summary>
            Erstellt einen Batch mit der angegebenen maximalen Größe in Bytes an.
            </summary>
        <remarks>
            Es wird empfohlen, rufen Sie <see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateBatch" /> oder <see cref="M:Microsoft.ServiceBus.Messaging.EventHubSender.CreateBatch" /> auf eine Instanz dieser Klasse erstellt werden, da er die maximale Nachrichtengröße, die mit dem Dienst ausgehandelt verwendet.
            Wenn die Anwendung einen Batch mit dem Konstruktor erstellt, ist es dafür verantwortlich, sicherzustellen, dass die "maxSizeInBytes" durch den Dienst zulässig ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventDataBatch.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.ServiceBus.Messaging.EventDataBatch.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die aktuelle Ereignisanzahl im Batch ab.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventDataBatch.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="eventDataBatch.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Verwirft die EventData-Objekte, die in diesem Batch enthalten sind.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToEnumerable">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; ToEnumerable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; ToEnumerable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventDataBatch.ToEnumerable" />
      <MemberSignature Language="VB.NET" Value="Public Function ToEnumerable () As IEnumerable(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.ToEnumerable : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventDataBatch.ToEnumerable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Konvertiert den Batch auf ein IEnumerable von EventData-Objekte, die von der Methode SendBatch oder SendBatchAsync akzeptiert werden können.</summary>
        <returns>Gibt ein IEnumerable von EventData-Objekte zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryAdd">
      <MemberSignature Language="C#" Value="public bool TryAdd (Microsoft.ServiceBus.Messaging.EventData eventData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryAdd(class Microsoft.ServiceBus.Messaging.EventData eventData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventDataBatch.TryAdd(Microsoft.ServiceBus.Messaging.EventData)" />
      <MemberSignature Language="F#" Value="member this.TryAdd : Microsoft.ServiceBus.Messaging.EventData -&gt; bool" Usage="eventDataBatch.TryAdd eventData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventData" Type="Microsoft.ServiceBus.Messaging.EventData" />
      </Parameters>
      <Docs>
        <param name="eventData">Das hinzuzufügende <see cref="T:Microsoft.ServiceBus.Messaging.EventData" />.</param>
        <summary>Versucht, Hinzufügen von Ereignisdaten, die dem Batch, wenn der Batch-Größenlimit zulässig.</summary>
        <returns>Ein boolescher Wert, der angibt, ob die Ereignisdaten an den Batch oder nicht hinzugefügt wurde.</returns>
        <remarks>
            Diese Methode überprüft die Größe des Batches, die EventData-Objekt, den festgelegten Grenzwert um festzustellen, ob der EventData-Objekt hinzugefügt werden kann. Es führt keine weiteren Überprüfungen auf den aktuellen Batch und die EventData-Objekt. Es ist möglich, dass die Anwendung Ausnahmen aus dem Sendeaufruf erhalten kann, wenn die im Batchmodus EventData-Objekte in einem Batch gesendet werden können. Angenommen, sie enthält verschiedene <see cref="P:Microsoft.ServiceBus.Messaging.EventData.PartitionKey" /> Werte.
            </remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn die EventData null ist.</exception>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn der Batch bereits freigegeben ist.</exception>
      </Docs>
    </Member>
  </Members>
</Type>