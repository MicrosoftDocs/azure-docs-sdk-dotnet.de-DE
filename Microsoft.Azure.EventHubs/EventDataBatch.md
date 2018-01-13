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
    <summary>Eine Hilfsklasse zum Erstellen eines Batches von EventData-Objekten, die für SendBatch oder SendBatchAsync Aufruf verwendet werden.</summary>
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
        <param name="maxSizeInBytes">Die maximal zulässige Größe für den batch</param>
        <summary>
            Erstellt einen neuen <see cref="T:Microsoft.Azure.EventHubs.EventDataBatch" />.
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
        <summary>Ruft die aktuelle Ereignisanzahl im Batch ab.</summary>
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
            Verwirft Ressourcen, die an eine EventDataBatch angefügt.
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
        <summary>Konvertiert den Batch auf ein IEnumerable von EventData-Objekte, die von der Methode SendBatchAsync akzeptiert werden können.</summary>
        <returns>Gibt ein IEnumerable von EventData-Objekte zurück.</returns>
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
        <param name="eventData">Das hinzuzufügende <see cref="T:Microsoft.Azure.EventHubs.EventData" />.</param>
        <summary>Versucht, Hinzufügen von Ereignisdaten, die dem Batch, wenn der Batch-Größenlimit zulässig.</summary>
        <returns>Ein boolescher Wert, der angibt, ob die Ereignisdaten an den Batch oder nicht hinzugefügt wurde.</returns>
        <remarks>
            Diese Methode überprüft die Größe des Batches, die EventData-Objekt, den festgelegten Grenzwert um festzustellen, ob der EventData-Objekt hinzugefügt werden kann.
            </remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn die EventData null ist.</exception>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn der Batch bereits freigegeben ist.</exception>
      </Docs>
    </Member>
  </Members>
</Type>