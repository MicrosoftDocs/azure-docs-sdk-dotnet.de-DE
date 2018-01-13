<Type Name="TaskOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TaskOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TaskOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TaskOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TaskOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für TaskOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders Add (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders Add(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, class Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Add(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter,Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter * Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Add (operations, jobId, task, taskAddOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="task" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" />
        <Parameter Name="taskAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, zu dem die Aufgabe ist, hinzugefügt werden.
            </param>
        <param name="task">
            Die Aufgabe hinzugefügt werden.
            </param>
        <param name="taskAddOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Fügt eine Aufgabe zum angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Die maximale Lebensdauer einer Aufgabe vom hinzufügen bis zum Abschluss beträgt 7 Tage. Wenn eine Aufgabe nicht abgeschlossen wurde, innerhalb von 7 Tagen hinzugefügt wird, dass durch die Batch-Dienst und der linken Seite beendet werden, wurde in unabhängig von Ihrem Status er zu diesem Zeitpunkt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt; AddAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt; AddAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, class Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter,Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter * Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddAsync (operations, jobId, task, taskAddOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;AddAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="task" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" />
        <Parameter Name="taskAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, zu dem die Aufgabe ist, hinzugefügt werden.
            </param>
        <param name="task">
            Die Aufgabe hinzugefügt werden.
            </param>
        <param name="taskAddOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Fügt eine Aufgabe zum angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Die maximale Lebensdauer einer Aufgabe vom hinzufügen bis zum Abschluss beträgt 7 Tage. Wenn eine Aufgabe nicht abgeschlossen wurde, innerhalb von 7 Tagen hinzugefügt wird, dass durch die Batch-Dienst und der linken Seite beendet werden, wurde in unabhängig von Ihrem Status er zu diesem Zeitpunkt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddCollection">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult AddCollection (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult AddCollection(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddCollection(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter},Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions)" />
      <MemberSignature Language="F#" Value="static member AddCollection : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddCollection (operations, jobId, value, taskAddCollectionOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;" />
        <Parameter Name="taskAddCollectionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der die Auflistung der ist, hinzugefügt werden.
            </param>
        <param name="value">
            Die Auflistung von Aufgaben hinzufügen. Die serialisierte Gesamtgröße dieser Auflistung muss kleiner als 4 MB sein. Ist er größer als 4MB (z. B., wenn jede Aufgabe 100 Ressourcendateien oder Umgebungsvariablen verfügt), wird die Anforderung schlägt fehl mit Code "RequestBodyTooLarge" und mit weniger Vorgänge erneut wiederholt werden sollen.
            </param>
        <param name="taskAddCollectionOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Fügt eine Auflistung von Aufgaben an den angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Beachten Sie, dass jede Aufgabe eine eindeutige ID aufweisen muss Der Batch-Dienst möglicherweise nicht die Ergebnisse für jede Aufgabe in der gleichen Reihenfolge zurück, die die Aufgaben in dieser Anforderung gesendet wurden. Wenn der Server ein Timeout eintritt, oder die Verbindung, während der Anforderung geschlossen wird, die Anforderung teilweise oder vollständig verarbeitet war möglicherweise oder überhaupt nicht. In solchen Fällen sollte der Benutzer die Anforderung erneut senden. Beachten Sie, dass es bis zu dem Benutzer, Fehler richtig zu behandeln, wenn eine Anforderung erneut gesendet wird.
            Beispielsweise sollten Sie die gleichen Aufgaben-IDs bei einer Wiederholung verwenden, damit, dass wenn der vorherige Vorgang erfolgreich war, die Wiederholung nicht unerwartet zusätzliche Aufgaben erstellt wird. Wenn die Antwort alle Aufgaben, die Fehler beim Hinzufügen enthält, kann ein Client die Anforderung erneut ausführen. In einer Wiederholung ist es am effizientesten, nur Vorgänge, die nicht hinzufügen, und klicken Sie, um Aufgaben zu unterdrücken, die beim ersten Versuch erfolgreich hinzugefügt wurden, erneut zu senden. Die maximale Lebensdauer einer Aufgabe vom hinzufügen bis zum Abschluss beträgt 7 Tage. Wenn eine Aufgabe nicht abgeschlossen wurde, innerhalb von 7 Tagen hinzugefügt wird, dass durch die Batch-Dienst und der linken Seite beendet werden, wurde in unabhängig von Ihrem Status er zu diesem Zeitpunkt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddCollectionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult&gt; AddCollectionAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult&gt; AddCollectionAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddCollectionAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter},Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddCollectionAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddCollectionAsync (operations, jobId, value, taskAddCollectionOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;AddCollectionAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;" />
        <Parameter Name="taskAddCollectionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der die Auflistung der ist, hinzugefügt werden.
            </param>
        <param name="value">
            Die Auflistung von Aufgaben hinzufügen. Die serialisierte Gesamtgröße dieser Auflistung muss kleiner als 4 MB sein. Ist er größer als 4MB (z. B., wenn jede Aufgabe 100 Ressourcendateien oder Umgebungsvariablen verfügt), wird die Anforderung schlägt fehl mit Code "RequestBodyTooLarge" und mit weniger Vorgänge erneut wiederholt werden sollen.
            </param>
        <param name="taskAddCollectionOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Fügt eine Auflistung von Aufgaben an den angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Beachten Sie, dass jede Aufgabe eine eindeutige ID aufweisen muss Der Batch-Dienst möglicherweise nicht die Ergebnisse für jede Aufgabe in der gleichen Reihenfolge zurück, die die Aufgaben in dieser Anforderung gesendet wurden. Wenn der Server ein Timeout eintritt, oder die Verbindung, während der Anforderung geschlossen wird, die Anforderung teilweise oder vollständig verarbeitet war möglicherweise oder überhaupt nicht. In solchen Fällen sollte der Benutzer die Anforderung erneut senden. Beachten Sie, dass es bis zu dem Benutzer, Fehler richtig zu behandeln, wenn eine Anforderung erneut gesendet wird.
            Beispielsweise sollten Sie die gleichen Aufgaben-IDs bei einer Wiederholung verwenden, damit, dass wenn der vorherige Vorgang erfolgreich war, die Wiederholung nicht unerwartet zusätzliche Aufgaben erstellt wird. Wenn die Antwort alle Aufgaben, die Fehler beim Hinzufügen enthält, kann ein Client die Anforderung erneut ausführen. In einer Wiederholung ist es am effizientesten, nur Vorgänge, die nicht hinzufügen, und klicken Sie, um Aufgaben zu unterdrücken, die beim ersten Versuch erfolgreich hinzugefügt wurden, erneut zu senden. Die maximale Lebensdauer einer Aufgabe vom hinzufügen bis zum Abschluss beträgt 7 Tage. Wenn eine Aufgabe nicht abgeschlossen wurde, innerhalb von 7 Tagen hinzugefügt wird, dass durch die Batch-Dienst und der linken Seite beendet werden, wurde in unabhängig von Ihrem Status er zu diesem Zeitpunkt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders Delete (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders Delete(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Delete(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Delete (operations, jobId, taskId, taskDeleteOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, aus dem die Aufgabe zu löschen.
            </param>
        <param name="taskId">
            Die ID des Vorgangs zu löschen.
            </param>
        <param name="taskDeleteOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Löscht eine Aufgabe aus dem angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn eine Aufgabe gelöscht wird, werden alle Dateien im Verzeichnis auf den Computeknoten, in dem es ausgeführt wurde (unabhängig von der Aufbewahrungsdauer) ebenfalls gelöscht. Für Vorgänge mit mehreren Instanzen gilt der Löschvorgang für den Task synchron an die primäre Aufgabe; Unteraufgaben und die Dateien werden asynchron im Hintergrund gelöscht.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.DeleteAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.DeleteAsync (operations, jobId, taskId, taskDeleteOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, aus dem die Aufgabe zu löschen.
            </param>
        <param name="taskId">
            Die ID des Vorgangs zu löschen.
            </param>
        <param name="taskDeleteOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine Aufgabe aus dem angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn eine Aufgabe gelöscht wird, werden alle Dateien im Verzeichnis auf den Computeknoten, in dem es ausgeführt wurde (unabhängig von der Aufbewahrungsdauer) ebenfalls gelöscht. Für Vorgänge mit mehreren Instanzen gilt der Löschvorgang für den Task synchron an die primäre Aufgabe; Unteraufgaben und die Dateien werden asynchron im Hintergrund gelöscht.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CloudTask Get (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CloudTask Get(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudTask" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Get (operations, jobId, taskId, taskGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudTask</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID des Tasks, zu dem Informationen abgerufen werden sollen.
            </param>
        <param name="taskGetOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft Informationen über den angegebenen Vorgang ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe. Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.GetAsync (operations, jobId, taskId, taskGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID des Tasks, zu dem Informationen abgerufen werden sollen.
            </param>
        <param name="taskGetOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über den angegebenen Vorgang ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe. Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; List (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; List(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.List (operations, jobId, taskListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags.
            </param>
        <param name="taskListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Zeigt eine Liste aller Aufgaben, die dem angegebenen Auftrag zugeordnet sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe. Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListAsync (operations, jobId, taskListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags.
            </param>
        <param name="taskListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Aufgaben, die dem angegebenen Auftrag zugeordnet sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe. Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; ListNext (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; ListNext(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListNext (operations, nextPageLink, taskListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="taskListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="taskListNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Zeigt eine Liste aller Aufgaben, die dem angegebenen Auftrag zugeordnet sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe. Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListNextAsync (operations, nextPageLink, taskListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;ListNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="taskListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="taskListNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Aufgaben, die dem angegebenen Auftrag zugeordnet sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe. Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSubtasks">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult ListSubtasks (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult ListSubtasks(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListSubtasks(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions)" />
      <MemberSignature Language="F#" Value="static member ListSubtasks : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListSubtasks (operations, jobId, taskId, taskListSubtasksOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskListSubtasksOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags.
            </param>
        <param name="taskId">
            Die ID des Tasks.
            </param>
        <param name="taskListSubtasksOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Zeigt eine Liste aller die Unteraufgaben an, die der Aufgabe angegebenen mit mehreren Instanzen zugeordnet sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn der Vorgang nicht um eine Aufgabe mit mehreren Instanzen ist zurück dies eine leere Auflistung.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSubtasksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult&gt; ListSubtasksAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult&gt; ListSubtasksAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListSubtasksAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSubtasksAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListSubtasksAsync (operations, jobId, taskId, taskListSubtasksOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;ListSubtasksAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskListSubtasksOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags.
            </param>
        <param name="taskId">
            Die ID des Tasks.
            </param>
        <param name="taskListSubtasksOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller die Unteraufgaben an, die der Aufgabe angegebenen mit mehreren Instanzen zugeordnet sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn der Vorgang nicht um eine Aufgabe mit mehreren Instanzen ist zurück dies eine leere Auflistung.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Reactivate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders Reactivate (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders Reactivate(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Reactivate(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions)" />
      <MemberSignature Language="F#" Value="static member Reactivate : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Reactivate (operations, jobId, taskId, taskReactivateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskReactivateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID des Tasks zu reaktivieren.
            </param>
        <param name="taskReactivateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Reaktiviert eine Aufgabe, sodass es erneut ausführen, auch wenn die Anzahl der Wiederholungsversuche ausgeschöpft ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Reaktivierung wird eine Aufgabe berechtigt ist, bis die maximale Anzahl von Wiederholungsversuchen zum Vorgang wiederholt werden. Der Status der Aufgabe wird in aktiv geändert. Wie die Aufgabe nicht mehr in den Zustand abgeschlossen ist, ist keine vorherigen beenden Code oder das Fehlschlagen der Informationen nach der Reaktivierung nicht mehr verfügbar. Jedes Mal, wenn eine Aufgabe erneut aktiviert wird, wird die Wiederholungsanzahl auf 0 zurückgesetzt. Reaktivierung fehl für Aufgaben, die nicht abgeschlossen oder zuvor erfolgreich (mit Exitcode 0) abgeschlossen. Darüber hinaus schlägt er fehl, wenn der Auftrag abgeschlossen wurde (oder beenden oder löschen).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReactivateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt; ReactivateAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt; ReactivateAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ReactivateAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReactivateAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ReactivateAsync (operations, jobId, taskId, taskReactivateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;ReactivateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskReactivateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID des Tasks zu reaktivieren.
            </param>
        <param name="taskReactivateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Reaktiviert eine Aufgabe, sodass es erneut ausführen, auch wenn die Anzahl der Wiederholungsversuche ausgeschöpft ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Reaktivierung wird eine Aufgabe berechtigt ist, bis die maximale Anzahl von Wiederholungsversuchen zum Vorgang wiederholt werden. Der Status der Aufgabe wird in aktiv geändert. Wie die Aufgabe nicht mehr in den Zustand abgeschlossen ist, ist keine vorherigen beenden Code oder das Fehlschlagen der Informationen nach der Reaktivierung nicht mehr verfügbar. Jedes Mal, wenn eine Aufgabe erneut aktiviert wird, wird die Wiederholungsanzahl auf 0 zurückgesetzt. Reaktivierung fehl für Aufgaben, die nicht abgeschlossen oder zuvor erfolgreich (mit Exitcode 0) abgeschlossen. Darüber hinaus schlägt er fehl, wenn der Auftrag abgeschlossen wurde (oder beenden oder löschen).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders Terminate (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders Terminate(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Terminate(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions)" />
      <MemberSignature Language="F#" Value="static member Terminate : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Terminate (operations, jobId, taskId, taskTerminateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID des Tasks beendet werden soll.
            </param>
        <param name="taskTerminateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Beendet die angegebene Aufgabe an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn die Aufgabe beendet wurde, wird in den abgeschlossenen Zustand verschoben. Für Vorgänge mit mehreren Instanzen gilt der Vorgang "Beenden" Task synchron an die primäre Aufgabe. Unteraufgaben werden dann asynchron im Hintergrund beendet.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt; TerminateAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt; TerminateAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.TerminateAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TerminateAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.TerminateAsync (operations, jobId, taskId, taskTerminateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;TerminateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID des Tasks beendet werden soll.
            </param>
        <param name="taskTerminateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Beendet die angegebene Aufgabe an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn die Aufgabe beendet wurde, wird in den abgeschlossenen Zustand verschoben. Für Vorgänge mit mehreren Instanzen gilt der Vorgang "Beenden" Task synchron an die primäre Aufgabe. Unteraufgaben werden dann asynchron im Hintergrund beendet.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders Update (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders Update(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Update(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Update (operations, jobId, taskId, constraints, taskUpdateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="taskUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID des Tasks aktualisiert.
            </param>
        <param name="constraints">
            Einschränkungen, die für diese Aufgabe gelten. Wenn nicht angegeben, wird die Aufgabe das Default-Einschränkungen angegeben. Für Vorgänge mit mehreren Instanzen aktualisieren die Aufbewahrungsdauer gilt nur für die primäre Aufgabe und Teilvorgänge nicht.
            </param>
        <param name="taskUpdateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Aktualisiert die Eigenschaften der angegebenen Aufgabe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt; UpdateAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt; UpdateAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.UpdateAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.UpdateAsync (operations, jobId, taskId, constraints, taskUpdateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;UpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="taskUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID des Tasks aktualisiert.
            </param>
        <param name="constraints">
            Einschränkungen, die für diese Aufgabe gelten. Wenn nicht angegeben, wird die Aufgabe das Default-Einschränkungen angegeben. Für Vorgänge mit mehreren Instanzen aktualisieren die Aufbewahrungsdauer gilt nur für die primäre Aufgabe und Teilvorgänge nicht.
            </param>
        <param name="taskUpdateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Eigenschaften der angegebenen Aufgabe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>