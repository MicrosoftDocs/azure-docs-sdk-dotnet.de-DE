<Type Name="ITrackedSaveOperation" FullName="Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation">
  <TypeSignature Language="C#" Value="public interface ITrackedSaveOperation : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITrackedSaveOperation implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITrackedSaveOperation&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ITrackedSaveOperation = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="283ee-101">Speichern einer nachverfolgten darstellt, in dem in regelmäßigen Abständen eine Hintergrundoperation kopiert fügt in einer Datei, die entsprechenden Anhang-Blob im Azure-Speicher.</span><span class="sxs-lookup"><span data-stu-id="283ee-101">Represents a tracked save, in which a background operation periodically copies appends to a file to the corresponding append blob in Azure Storage.</span></span>
            </summary>
    <remarks>To be added.</remarks>
    <altmember cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveTrackedAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.TimeSpan)" />
  </Docs>
  <Members>
    <Member MemberName="FlushError">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Exception&gt; FlushError;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Exception&gt; FlushError" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation.FlushError" />
      <MemberSignature Language="VB.NET" Value="Event FlushError As EventHandler(Of Exception) " />
      <MemberSignature Language="F#" Value="member this.FlushError : EventHandler&lt;Exception&gt; " Usage="member this.FlushError : System.EventHandler&lt;System.Exception&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Exception&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="283ee-102">Tritt auf, wenn ein Fehler aufgetreten, beim Ausführen eines Hintergrunds ist in das Blob im Azure-Speicher anfügen.</span><span class="sxs-lookup"><span data-stu-id="283ee-102">Occurs when there is an error while performing a background append to the blob in Azure Storage.</span></span>
            </summary>
        <remarks>
          <para>
            <span data-ttu-id="283ee-103">Wenn ein Fehler auftritt, während Daten angefügt, wird die letzte Position nicht aktualisiert, damit die Daten, die nicht angefügt werden konnte die nächste Leerung eingeschlossen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="283ee-103">If an error occurs while appending, the 'last position' is not updated, so the data that could not be appended will be included in the next flush.</span></span>
            </para>
          <para>
            <span data-ttu-id="283ee-104">Dieses Ereignis wird nicht ausgelöst, wenn ein Fehler, während der auftritt <see cref="M:System.IDisposable.Dispose" />; stattdessen die Methode Dispose-Methode löst erneut die Ausnahme direkt.</span><span class="sxs-lookup"><span data-stu-id="283ee-104">This event is not raised if an error occurs during <see cref="M:System.IDisposable.Dispose" />; instead, the Dispose method method re-throws the exception directly.</span></span> <span data-ttu-id="283ee-105">In diesem Fall fügt der Hintergrund sind nicht mehr ausgeführt, es liegt daher entscheiden, ob und wie der aufrufende Code zum Speichern der unflushed Daten (z. B. erneutes Speichern der Datei, die mithilfe der Methoden nicht nachverfolgen).</span><span class="sxs-lookup"><span data-stu-id="283ee-105">In this case, the background appends are no longer running, so it is up to the calling code to decide whether and how to save the unflushed data (for example, re-saving the file using the non-tracking methods).</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>