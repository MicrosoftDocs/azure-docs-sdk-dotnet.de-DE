<Type Name="JobOperations" FullName="Microsoft.Azure.Batch.JobOperations">
  <TypeSignature Language="C#" Value="public class JobOperations : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobOperations extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Class JobOperations&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type JobOperations = class&#xA;    interface IInheritedBehaviors" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Führt Vorgänge für Azure Batch-Aufträge.
            </summary>
    <remarks>To be added.</remarks>
    <altmember cref="T:Microsoft.Azure.Batch.CloudJob" />
  </Docs>
  <Members>
    <Member MemberName="AddTask">
      <MemberSignature Language="C#" Value="public System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt; AddTask (string jobId, Microsoft.Azure.Batch.CloudTask taskToAdd, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt; AddTask(string jobId, class Microsoft.Azure.Batch.CloudTask taskToAdd, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,Microsoft.Azure.Batch.CloudTask,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddTask (jobId As String, taskToAdd As CloudTask, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As ConcurrentDictionary(Of Type, IFileStagingArtifact)" />
      <MemberSignature Language="F#" Value="member this.AddTask : string * Microsoft.Azure.Batch.CloudTask * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;" Usage="jobOperations.AddTask (jobId, taskToAdd, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskToAdd" Type="Microsoft.Azure.Batch.CloudTask" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags, dem die Aufgabe hinzugefügt werden soll.</param>
        <param name="taskToAdd">Das hinzuzufügende <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <summary>
            Fügt eine einzelne Aufgabe auf einen Auftrag an.  Verwenden Sie zum Hinzufügen von mehreren Aufgaben <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>.
            </summary>
        <returns>Eine Auflistung von Informationen über die Datei mit dem Stagingprozess (siehe <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).
            Weitere Informationen finden Sie unter <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</returns>
        <remarks>
          <para>Jeder Aufruf dieser Methode verursacht eine Anforderung an den Batch-Dienst. Aus diesem Grund verwenden diese Methode zum Hinzufügen von mehreren Aufgaben ist weniger effizient als die Verwendung einer Bulk add-Methode, und HTTP-Verbindung Einschränkungen verursachen können.
            Wenn Sie viele dieser Vorgänge parallel ausgeführt werden und clientseitigen Timeouts angezeigt werden, finden Sie unter http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx, oder verwenden Sie die Multiple-Aufgabe die Überladung der AddTask.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddTask">
      <MemberSignature Language="C#" Value="public void AddTask (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions = null, System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts = null, Nullable&lt;TimeSpan&gt; timeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddTask(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, class Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions, class System.Collections.Concurrent.ConcurrentBag`1&lt;class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddTask (jobId As String, tasksToAdd As IEnumerable(Of CloudTask), Optional parallelOptions As BatchClientParallelOptions = null, Optional fileStagingArtifacts As ConcurrentBag(Of ConcurrentDictionary(Of Type, IFileStagingArtifact)) = null, Optional timeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.AddTask : string * seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.BatchClientParallelOptions * System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.AddTask (jobId, tasksToAdd, parallelOptions, fileStagingArtifacts, timeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="tasksToAdd" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="parallelOptions" Type="Microsoft.Azure.Batch.BatchClientParallelOptions" />
        <Parameter Name="fileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt;" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags, der die Tasks hinzugefügt werden soll.</param>
        <param name="tasksToAdd">Die <see cref="T:Microsoft.Azure.Batch.CloudTask" />s hinzufügen.</param>
        <param name="parallelOptions">
            Steuert die Anzahl gleichzeitiger parallele AddTaskCollection-Anforderungen an die Batch-Dienst ausgegeben.  Jede Anforderung AddTaskCollection enthält höchstens <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" /> Aufgaben darin.
            Steuert auch das Abbruchtoken, das für den Vorgang.
            Bei Auslassung wird die Standardeinstellung verwendet (siehe <see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />.)
            </param>
        <param name="fileStagingArtifacts">Eine optionale Auflistung zum Empfangen von Informationen über die Datei mit dem Stagingprozess (siehe <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).
            Wird ein Eintrag hinzugefügt, um die <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" /> für jeden Satz von Aufgaben, die für die Übermittlung an den Batch-Dienst gruppiert.
            Im Gegensatz zu einzelnen Aufgabe hinzufügt, Sie können nicht diesen Parameter verwenden, um die Datei mit dem Stagingprozess anzupassen.
            Weitere Informationen zum Format von jeder Eintrag finden Sie unter <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</param>
        <param name="timeout">Die Zeitspanne, nach dem Timeout des Vorgangs.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <summary>
            Tasks hinzugefügt zu einem Auftrag.
            </summary>
        <remarks>
          <para>Dies ist ein Blockierungsvorgang; eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</para>
          <para>Diese Methode ist nicht atomaren; Es ist also möglich, dass die Methode zum Hinzufügen von Aufgaben starten und schlagen dann fehl. Die Auflistung von Aufgaben hinzuzufügende ist unterteilt in Blöcke unterteilt, Größe darf höchstens <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />, und eine Anforderung AddTaskCollection für jedes Blocks ausgegeben.  Anforderungen können ausgegeben werden, parallel gemäß der <paramref name="parallelOptions" />.</para>
          <para>Ausstellen von eine große Anzahl gleichzeitiger Anforderungen für die Batch-Dienst kann die HTTP-Verbindung Einschränkungen entstehen.
            Wenn Sie viele dieser Vorgänge parallel ausgeführt werden (oder eine große MaxDegreeOfParallelism in ParallelOptions angegeben haben) und sehen clientseitigen Timeouts, http://msdn.microsoft.com/en-us/library/ finden Sie unter System.NET.ServicePointManager.DefaultConnectionLimit%28v=VS.110%29.aspx.</para>
          <para>Der Status des Vorgangs bei Fehlern richtet sich nach <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" /> Verhalten.
            Normalerweise ist es nicht müssen an dieses Verhalten als Batch Client den Standardwert verwendet, die unter normalen Umständen funktioniert.
            Wenn Sie dieses Verhalten anpassen möchten, geben Sie eine AddTaskCollectionResultHandler in der <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> oder <paramref name="additionalBehaviors" /> Sammlungen.</para>
        </remarks>
        <exception cref="T:Microsoft.Azure.Batch.ParallelOperationsException">Wird ausgelöst, wenn eine oder mehrere Anforderungen an die Batch-Dienst ein Fehler auftritt.</exception>
      </Docs>
    </Member>
    <Member MemberName="AddTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddTaskAsync (string jobId, Microsoft.Azure.Batch.CloudTask taskToAdd, System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt; allFileStagingArtifacts = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddTaskAsync(string jobId, class Microsoft.Azure.Batch.CloudTask taskToAdd, class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt; allFileStagingArtifacts, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.AddTaskAsync : string * Microsoft.Azure.Batch.CloudTask * System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.AddTaskAsync (jobId, taskToAdd, allFileStagingArtifacts, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskToAdd" Type="Microsoft.Azure.Batch.CloudTask" />
        <Parameter Name="allFileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags, dem die Aufgabe hinzugefügt werden soll.</param>
        <param name="taskToAdd">Das hinzuzufügende <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</param>
        <param name="allFileStagingArtifacts">Eine optionale Auflistung zum Anpassen und Empfangen von Informationen über die Datei mit dem Stagingprozess (siehe <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).
            Weitere Informationen finden Sie unter <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Fügt eine einzelne Aufgabe auf einen Auftrag an.  Verwenden Sie zum Hinzufügen von mehreren Aufgaben <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Jeder Aufruf dieser Methode verursacht eine Anforderung an den Batch-Dienst. Aus diesem Grund verwenden diese Methode zum Hinzufügen von mehreren Aufgaben ist weniger effizient als die Verwendung einer Bulk add-Methode, und HTTP-Verbindung Einschränkungen verursachen können.
            Wenn Sie viele dieser Vorgänge parallel ausgeführt werden und clientseitigen Timeouts angezeigt werden, finden Sie unter http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx, oder verwenden Sie die Multiple-Aufgabe die Überladung der AddTaskAsync.</para>
          <para>Der Vorgang des Agentverwaltungstasks hinzufügen wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddTaskAsync (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions = null, System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts = null, Nullable&lt;TimeSpan&gt; timeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddTaskAsync(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, class Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions, class System.Collections.Concurrent.ConcurrentBag`1&lt;class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddTaskAsync (jobId As String, tasksToAdd As IEnumerable(Of CloudTask), Optional parallelOptions As BatchClientParallelOptions = null, Optional fileStagingArtifacts As ConcurrentBag(Of ConcurrentDictionary(Of Type, IFileStagingArtifact)) = null, Optional timeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As Task" />
      <MemberSignature Language="F#" Value="member this.AddTaskAsync : string * seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.BatchClientParallelOptions * System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="jobOperations.AddTaskAsync (jobId, tasksToAdd, parallelOptions, fileStagingArtifacts, timeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;AddTaskAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="tasksToAdd" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="parallelOptions" Type="Microsoft.Azure.Batch.BatchClientParallelOptions" />
        <Parameter Name="fileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt;" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags, der die Tasks hinzugefügt werden soll.</param>
        <param name="tasksToAdd">Die <see cref="T:Microsoft.Azure.Batch.CloudTask" />s hinzufügen.</param>
        <param name="parallelOptions">
            Steuert die Anzahl gleichzeitiger parallele AddTaskCollection-Anforderungen an die Batch-Dienst ausgegeben.  Jede Anforderung AddTaskCollection enthält höchstens <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" /> Aufgaben darin.
            Steuert auch das Abbruchtoken, das für den Vorgang.
            Bei Auslassung wird die Standardeinstellung verwendet (siehe <see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />.)
            </param>
        <param name="fileStagingArtifacts">Eine optionale Auflistung zum Empfangen von Informationen über die Datei mit dem Stagingprozess (siehe <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).
            Wird ein Eintrag hinzugefügt, um die <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" /> für jeden Satz von Aufgaben, die für die Übermittlung an den Batch-Dienst gruppiert.
            Im Gegensatz zu einzelnen Aufgabe hinzufügt, Sie können nicht diesen Parameter verwenden, um die Datei mit dem Stagingprozess anzupassen.
            Weitere Informationen zum Format von jeder Eintrag finden Sie unter <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</param>
        <param name="timeout">Die Zeitspanne, nach dem Timeout des Vorgangs.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <summary>
            Tasks hinzugefügt zu einem Auftrag.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Der Vorgang des Agentverwaltungstasks hinzufügen wird asynchron ausgeführt.</para>
          <para>Diese Methode ist nicht atomaren; Es ist also möglich, dass die Methode zum Hinzufügen von Aufgaben starten und schlagen dann fehl. Die Auflistung von Aufgaben hinzuzufügende ist unterteilt in Blöcke unterteilt, Größe darf höchstens <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />, und eine Anforderung AddTaskCollection für jedes Blocks ausgegeben.  Anforderungen können ausgegeben werden, parallel gemäß der <paramref name="parallelOptions" />.</para>
          <para>Ausstellen von eine große Anzahl gleichzeitiger Anforderungen für die Batch-Dienst kann die HTTP-Verbindung Einschränkungen entstehen.
            Wenn Sie viele dieser Vorgänge parallel ausgeführt werden (oder eine große MaxDegreeOfParallelism in ParallelOptions angegeben haben) und sehen clientseitigen Timeouts, http://msdn.microsoft.com/en-us/library/ finden Sie unter System.NET.ServicePointManager.DefaultConnectionLimit%28v=VS.110%29.aspx.</para>
          <para>Der Status des Vorgangs bei Fehlern richtet sich nach <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" /> Verhalten.
            Normalerweise ist es nicht müssen an dieses Verhalten als Batch Client den Standardwert verwendet, die unter normalen Umständen funktioniert.
            Wenn Sie dieses Verhalten anpassen möchten, geben Sie eine AddTaskCollectionResultHandler in der <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> oder <paramref name="additionalBehaviors" /> Sammlungen.</para>
        </remarks>
        <exception cref="T:Microsoft.Azure.Batch.ParallelOperationsException">Wird ausgelöst, wenn eine oder mehrere Anforderungen an die Batch-Dienst ein Fehler auftritt.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateJob">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudJob CreateJob ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudJob CreateJob() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.CreateJob" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateJob () As CloudJob" />
      <MemberSignature Language="F#" Value="member this.CreateJob : unit -&gt; Microsoft.Azure.Batch.CloudJob" Usage="jobOperations.CreateJob " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudJob</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine Instanz des CloudJob, die entfernt wird, und verfügt nicht über eine Beziehung Konsistenz auf einen beliebigen Auftrag in der Batch-Dienst.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.CloudJob" /> , einen neuen Auftrag, die nicht übermittelt wurden, des Batch-Diensts darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateJob">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudJob CreateJob (string jobId, Microsoft.Azure.Batch.PoolInformation poolInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudJob CreateJob(string jobId, class Microsoft.Azure.Batch.PoolInformation poolInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.CreateJob(System.String,Microsoft.Azure.Batch.PoolInformation)" />
      <MemberSignature Language="F#" Value="member this.CreateJob : string * Microsoft.Azure.Batch.PoolInformation -&gt; Microsoft.Azure.Batch.CloudJob" Usage="jobOperations.CreateJob (jobId, poolInformation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="poolInformation" Type="Microsoft.Azure.Batch.PoolInformation" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags.</param>
        <param name="poolInformation">Die Informationen zu dem Pool wird der Auftrag ausgeführt.</param>
        <summary>
            Erstellt eine Instanz des CloudJob, die entfernt wird, und verfügt nicht über eine Beziehung Konsistenz auf einen beliebigen Auftrag in der Batch-Dienst.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.CloudJob" /> , einen neuen Auftrag, die nicht übermittelt wurden, des Batch-Diensts darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst, die über dieses <see cref="T:Microsoft.Azure.Batch.JobOperations" />.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</para>
          <para>Änderungen werden in der Reihenfolge der Auflistung angewendet. Der letzte write Wins.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteJob">
      <MemberSignature Language="C#" Value="public void DeleteJob (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteJob(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteJob(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteJob (jobId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteJob : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.DeleteJob (jobId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <summary>
            Löscht den angegebenen Auftrag.
            </summary>
        <remarks>
          <para>Der Löschvorgang fordert, dass der Auftrag gelöscht werden.  Die Anforderung setzt den Auftrag in der <see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" /> Zustand.
            Der Batch-Dienst beendet alle ausgeführten Aufgaben und das tatsächliche Auftrag löschen, ohne weitere Clientaktion ausführen.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobOperations.DeleteJobAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteJobAsync (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteJobAsync(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteJobAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteJobAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.DeleteJobAsync (jobId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;DeleteJobAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Löscht den angegebenen Auftrag.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Der Löschvorgang fordert, dass der Auftrag gelöscht werden.  Die Anforderung setzt den Auftrag in der <see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" /> Zustand.
            Der Batch-Dienst beendet alle ausgeführten Aufgaben und das tatsächliche Auftrag löschen, ohne weitere Clientaktion ausführen.</para>
          <para>Der Löschvorgang wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNodeFile">
      <MemberSignature Language="C#" Value="public void DeleteNodeFile (string jobId, string taskId, string filePath, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteNodeFile(string jobId, string taskId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteNodeFile(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteNodeFile (jobId As String, taskId As String, filePath As String, Optional recursive As Nullable(Of Boolean) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteNodeFile : string * string * string * Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.DeleteNodeFile (jobId, taskId, filePath, recursive, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die ID des Auftrags, der den Task enthält.</param>
        <param name="taskId">Die ID des Tasks.</param>
        <param name="filePath">Der Pfad der zu löschenden Datei.</param>
        <param name="recursive">
            Wenn die Datei-Path-Parameter ein Verzeichnis anstelle einer Datei darstellt, können Sie den Parameter optional, rekursive auf "true" Löschen des Verzeichnisses und aller Dateien und Unterverzeichnisse darin festlegen. Wenn rekursiv "false" ist das Verzeichnis muss leer sein, oder Löschvorgang fehl.
            </param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <summary>
            Löscht die angegebene Datei aus der Task-Verzeichnis für die Serverknoten an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>Dies ist ein blockierender Vorgang.  Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNodeFileAsync (string jobId, string taskId, string filePath, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNodeFileAsync(string jobId, string taskId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteNodeFileAsync : string * string * string * Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.DeleteNodeFileAsync (jobId, taskId, filePath, recursive, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;DeleteNodeFileAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">Die ID des Auftrags, der den Task enthält.</param>
        <param name="taskId">Die ID des Tasks.</param>
        <param name="filePath">Der Pfad der zu löschenden Datei.</param>
        <param name="recursive">
            Wenn die Datei-Path-Parameter ein Verzeichnis anstelle einer Datei darstellt, können Sie den Parameter optional, rekursive auf "true" Löschen des Verzeichnisses und aller Dateien und Unterverzeichnisse darin festlegen. Wenn rekursiv "false" ist das Verzeichnis muss leer sein, oder Löschvorgang fehl.
            </param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Löscht die angegebene Datei aus der Task-Verzeichnis für die Serverknoten an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>Der Löschvorgang wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteTask">
      <MemberSignature Language="C#" Value="public void DeleteTask (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteTask(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteTask(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteTask (jobId As String, taskId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteTask : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.DeleteTask (jobId, taskId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die ID des Auftrags, der den Task enthält.</param>
        <param name="taskId">Die ID des Tasks.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <summary>
            Löscht den angegebenen Task an.
            </summary>
        <remarks>Dies ist ein blockierender Vorgang.  Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobOperations.DeleteTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteTaskAsync (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteTaskAsync(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteTaskAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.DeleteTaskAsync (jobId, taskId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">Die ID des Auftrags, der den Task enthält.</param>
        <param name="taskId">Die ID des Tasks.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Löscht den angegebenen Task an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>Der Löschvorgang wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableJob">
      <MemberSignature Language="C#" Value="public void DisableJob (string jobId, Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableJob(string jobId, valuetype Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DisableJob(System.String,Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.DisableJob : string * Microsoft.Azure.Batch.Common.DisableJobOption * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.DisableJob (jobId, disableJobOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="disableJobOption" Type="Microsoft.Azure.Batch.Common.DisableJobOption" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags.</param>
        <param name="disableJobOption">Gibt an, was mit aktiven Aufgaben, die dem Auftrag zugeordnet sind.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <summary>
            Deaktiviert den angegebenen Auftrag.  Deaktivierte Aufträge neue Aufgaben nicht ausführen, aber möglicherweise erneut aktiviert werden weiter unten.
            </summary>
        <remarks>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobOperations.DisableJobAsync(System.String,Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableJobAsync (string jobId, Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableJobAsync(string jobId, valuetype Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DisableJobAsync(System.String,Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableJobAsync : string * Microsoft.Azure.Batch.Common.DisableJobOption * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.DisableJobAsync (jobId, disableJobOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;DisableJobAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="disableJobOption" Type="Microsoft.Azure.Batch.Common.DisableJobOption" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags.</param>
        <param name="disableJobOption">Gibt an, was mit aktiven Aufgaben, die dem Auftrag zugeordnet sind.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Deaktiviert den angegebenen Auftrag.  Deaktivierte Aufträge neue Aufgaben nicht ausführen, aber möglicherweise erneut aktiviert werden weiter unten.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>Der Deaktivierungsvorgang wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableJob">
      <MemberSignature Language="C#" Value="public void EnableJob (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableJob(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.EnableJob(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableJob (jobId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableJob : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.EnableJob (jobId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <summary>
            Aktiviert den angegebenen Auftrag, neue Aufgaben ausführen.
            </summary>
        <remarks>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobOperations.EnableJobAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableJobAsync (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableJobAsync(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.EnableJobAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableJobAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.EnableJobAsync (jobId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;EnableJobAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Aktiviert den angegebenen Auftrag, neue Aufgaben ausführen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>Der Aktivierungsvorgang wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobStatistics GetAllLifetimeStatistics (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.JobStatistics GetAllLifetimeStatistics(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetAllLifetimeStatistics(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllLifetimeStatistics (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As JobStatistics" />
      <MemberSignature Language="F#" Value="member this.GetAllLifetimeStatistics : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.JobStatistics" Usage="jobOperations.GetAllLifetimeStatistics additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <summary>
            Zusammenfassung lebensdauerstatistiken für alle Aufträge im aktuellen Konto abgerufen.  
            Statistiken werden für alle Aufträge aggregiert, die jemals im Konto, von der kontoerstellung bis zum letzten Zeitpunkt des Updates der Statistik vorhanden waren. 
            </summary>
        <returns>Der aggregierte Auftragsstatistik.</returns>
        <remarks>Dies ist ein Blockierungsvorgang; eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatisticsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.JobStatistics&gt; GetAllLifetimeStatisticsAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.JobStatistics&gt; GetAllLifetimeStatisticsAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetAllLifetimeStatisticsAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.JobStatistics&gt;" Usage="jobOperations.GetAllLifetimeStatisticsAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;GetAllLifetimeStatisticsAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.JobStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Zusammenfassung lebensdauerstatistiken für alle Aufträge im aktuellen Konto abgerufen.  
            Statistiken werden für alle Aufträge aggregiert, die jemals im Konto, von der kontoerstellung bis zum letzten Zeitpunkt des Updates der Statistik vorhanden waren. 
            </summary>
        <returns>Der aggregierte Auftragsstatistik.</returns>
        <remarks>Der Abrufvorgang für die Statistik wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJob">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudJob GetJob (string jobId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudJob GetJob(string jobId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetJob(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetJob : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.CloudJob" Usage="jobOperations.GetJob (jobId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags, der abgerufen werden soll.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <summary>
            Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.CloudJob" /> ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.CloudJob" /> mit Informationen über den angegebenen Azure Batch-Auftrag.</returns>
        <remarks>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobOperations.GetJobAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudJob&gt; GetJobAsync (string jobId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.CloudJob&gt; GetJobAsync(string jobId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetJobAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetJobAsync : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudJob&gt;" Usage="jobOperations.GetJobAsync (jobId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;GetJobAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags, der abgerufen werden soll.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.CloudJob" /> ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.CloudJob" /> mit Informationen über den angegebenen Azure Batch-Auftrag.</returns>
        <remarks>Get Job-Vorgang wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobTaskCounts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskCounts GetJobTaskCounts (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.TaskCounts GetJobTaskCounts(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetJobTaskCounts(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetJobTaskCounts (jobId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As TaskCounts" />
      <MemberSignature Language="F#" Value="member this.GetJobTaskCounts : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.TaskCounts" Usage="jobOperations.GetJobTaskCounts (jobId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskCounts</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <summary>
            Ruft die Anzahl der Task für den angegebenen Auftrag.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.TaskCounts" /> Objekt mit dem Task für den Auftrag zählt.</returns>
        <remarks>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobOperations.GetJobTaskCountsAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobTaskCountsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt; GetJobTaskCountsAsync (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.TaskCounts&gt; GetJobTaskCountsAsync(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetJobTaskCountsAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetJobTaskCountsAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt;" Usage="jobOperations.GetJobTaskCountsAsync (jobId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;GetJobTaskCountsAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ruft die Anzahl der Task für den angegebenen Auftrag.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.TaskCounts" /> Objekt mit dem Task für den Auftrag zählt.</returns>
        <remarks>Die Get-Auftragstasks zählt Vorgang ausgeführt wird asynchron aus.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.NodeFile GetNodeFile (string jobId, string taskId, string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.NodeFile GetNodeFile(string jobId, string taskId, string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetNodeFile(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeFile (jobId As String, taskId As String, filePath As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As NodeFile" />
      <MemberSignature Language="F#" Value="member this.GetNodeFile : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.NodeFile" Usage="jobOperations.GetNodeFile (jobId, taskId, filePath, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.NodeFile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die ID des Auftrags, der den Task enthält.</param>
        <param name="taskId">Die ID des Tasks.</param>
        <param name="filePath">Der Pfad der Datei abgerufen werden soll.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <summary>
            Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.NodeFile" /> aus den angegebenen Task Verzeichnis auf dem Computeknoten.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.NodeFile" /> , das die angegebene Datei darstellt.</returns>
        <remarks>Dies ist ein blockierender Vorgang.  Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync (string jobId, string taskId, string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync(string jobId, string taskId, string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeFileAsync : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="jobOperations.GetNodeFileAsync (jobId, taskId, filePath, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">Die ID des Auftrags, der den Task enthält.</param>
        <param name="taskId">Die ID des Tasks.</param>
        <param name="filePath">Der Pfad der Datei abgerufen werden soll.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.NodeFile" /> aus den angegebenen Task Verzeichnis auf dem Computeknoten.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.NodeFile" /> , das die angegebene Datei darstellt.</returns>
        <remarks>Der Abrufvorgang für die Datei wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudTask GetTask (string jobId, string taskId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudTask GetTask(string jobId, string taskId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetTask(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetTask : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.CloudTask" Usage="jobOperations.GetTask (jobId, taskId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudTask</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags, aus dem den Task abgerufen werden soll.</param>
        <param name="taskId">Die Id des Tasks abgerufen werden soll.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <summary>
            Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.CloudTask" /> ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.CloudTask" /> mit Informationen über die angegebene Azure Batch-Aufgabe.</returns>
        <remarks>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobOperations.GetTaskAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt; GetTaskAsync (string jobId, string taskId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; GetTaskAsync(string jobId, string taskId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetTaskAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTaskAsync : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt;" Usage="jobOperations.GetTaskAsync (jobId, taskId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags, aus dem den Task abgerufen werden soll.</param>
        <param name="taskId">Die Id des Tasks abgerufen werden soll.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.CloudTask" /> ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.CloudTask" /> mit Informationen über die angegebene Azure Batch-Aufgabe.</returns>
        <remarks>Der Abrufvorgang für die Aufgabe wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobPreparationAndReleaseTaskStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation&gt; ListJobPreparationAndReleaseTaskStatus (string jobId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation&gt; ListJobPreparationAndReleaseTaskStatus(string jobId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ListJobPreparationAndReleaseTaskStatus(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListJobPreparationAndReleaseTaskStatus : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation&gt;" Usage="jobOperations.ListJobPreparationAndReleaseTaskStatus (jobId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <summary>
            Listet den Status der <see cref="P:Microsoft.Azure.Batch.CloudJob.JobPreparationTask" /> und <see cref="P:Microsoft.Azure.Batch.CloudJob.JobReleaseTask" /> Aufgaben für den angegebenen Auftrag.
            </summary>
        <returns>Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die zum Aufzählen von Status synchron oder asynchron verwendet werden kann.</returns>
        <remarks>Diese Methode gibt sofort zurück. die Statuswerte werden aus der Batch-Dienst abgerufen werden, nur, wenn die Auflistung aufgezählt wird.
            Datenabruf ist nicht atomaren; Status werden in Seiten während der Enumeration der Auflistung abgerufen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt; ListJobs (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudJob&gt; ListJobs(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ListJobs(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListJobs : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt;" Usage="jobOperations.ListJobs (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <summary>
            Listet die <see cref="T:Microsoft.Azure.Batch.CloudJob">Aufträge</see> in dem Batch-Konto.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , Aufträge aufgelistet werden, synchron oder asynchron verwendet werden kann.</returns>
        <remarks>Diese Methode gibt sofort zurück. nur, wenn die Auflistung aufgezählt wird, werden die Aufträge aus der Batch-Dienst abgerufen.
            Datenabruf ist nicht atomaren; Aufträge werden in Seiten während der Enumeration der Auflistung abgerufen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeFiles">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles (string jobId, string taskId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles(string jobId, string taskId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ListNodeFiles(System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListNodeFiles : string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="jobOperations.ListNodeFiles (jobId, taskId, recursive, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags.</param>
        <param name="taskId">Die ID des Tasks.</param>
        <param name="recursive">Bei "true", führt eine rekursive Liste aller Dateien der Aufgabe. Wenn "false" gibt nur die Dateien in das Stammverzeichnis für die Aufgabe zurück.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <summary>
            Listet die <see cref="T:Microsoft.Azure.Batch.NodeFile">NodeFiles</see> in den angegebenen Task Verzeichnis auf dem Computeknoten.
            </summary>
        <returns>Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die zum Aufzählen von Dateien asynchron oder synchron verwendet werden kann.</returns>
        <remarks>Diese Methode gibt sofort zurück. die Daten einer Datei werden aus der Batch-Dienst abgerufen, nur, wenn die Auflistung aufgezählt wird.
            Datenabruf ist nicht atomaren; Dateidaten werden in Seiten während der Enumeration der Auflistung abgerufen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSubtasks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.SubtaskInformation&gt; ListSubtasks (string jobId, string taskId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.SubtaskInformation&gt; ListSubtasks(string jobId, string taskId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ListSubtasks(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListSubtasks : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.SubtaskInformation&gt;" Usage="jobOperations.ListSubtasks (jobId, taskId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.SubtaskInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags.</param>
        <param name="taskId">Die Id des Tasks abgerufen werden soll.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <summary>
            Listet die <see cref="T:Microsoft.Azure.Batch.SubtaskInformation">Teilvorgang Informationen</see> der angegebenen Aufgabe.
            </summary>
        <returns>Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die zum Aufzählen von Unteraufgaben synchron oder asynchron verwendet werden kann.</returns>
        <remarks>Diese Methode gibt sofort zurück. nur, wenn die Auflistung aufgezählt wird, werden die Aufgaben aus dem Batch-Dienst abgerufen.
            Datenabruf ist nicht atomaren; Aufgaben werden in Seiten während der Enumeration der Auflistung abgerufen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTasks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; ListTasks (string jobId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; ListTasks(string jobId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ListTasks(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListTasks : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" Usage="jobOperations.ListTasks (jobId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <summary>
            Listet die <see cref="T:Microsoft.Azure.Batch.CloudTask">Aufgaben</see> des angegebenen Auftrags.
            </summary>
        <returns>Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die Aufgaben auflisten, synchron oder asynchron verwendet werden kann.</returns>
        <remarks>Diese Methode gibt sofort zurück. nur, wenn die Auflistung aufgezählt wird, werden die Aufgaben aus dem Batch-Dienst abgerufen.
            Datenabruf ist nicht atomaren; Aufgaben werden in Seiten während der Enumeration der Auflistung abgerufen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReactivateTask">
      <MemberSignature Language="C#" Value="public void ReactivateTask (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ReactivateTask(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ReactivateTask(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReactivateTask (jobId As String, taskId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.ReactivateTask : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.ReactivateTask (jobId, taskId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die ID des Auftrags, der den Task enthält.</param>
        <param name="taskId">Die ID des Tasks.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <summary>
            Reaktiviert eine Aufgabe, sodass es erneut ausführen, auch wenn die Anzahl der Wiederholungsversuche ausgeschöpft ist.
            </summary>
        <remarks>
          <para>
            Reaktivierung wird eine Aufgabe berechtigt ist, bis die maximale Anzahl von Wiederholungsversuchen zum Vorgang wiederholt werden.
            </para>
          <para>
            Dieser Vorgang schlägt fehl, für die Aufgaben, die nicht abgeschlossen oder zuvor erfolgreich (mit Exitcode 0) abgeschlossen.
            </para>
          <para>
            Darüber hinaus schlägt dies fehl, wenn der Auftrag befindet sich in der <see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" /> oder <see cref="F:Microsoft.Azure.Batch.Common.JobState.Terminating" /> oder <see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" /> Zustand.
            Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobOperations.ReactivateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReactivateTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReactivateTaskAsync (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ReactivateTaskAsync(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ReactivateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ReactivateTaskAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.ReactivateTaskAsync (jobId, taskId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">Die ID des Auftrags, der den Task enthält.</param>
        <param name="taskId">Die ID des Tasks.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Reaktiviert eine Aufgabe, sodass es erneut ausführen, auch wenn die Anzahl der Wiederholungsversuche ausgeschöpft ist.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>
            Reaktivierung wird eine Aufgabe berechtigt ist, bis die maximale Anzahl von Wiederholungsversuchen zum Vorgang wiederholt werden.
            </para>
          <para>
            Darüber hinaus schlägt dies fehl, wenn der Auftrag befindet sich in der <see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" /> oder <see cref="F:Microsoft.Azure.Batch.Common.JobState.Terminating" /> oder <see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" /> Zustand.
            Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobOperations.ReactivateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.
            </para>
          <para>
            Der Vorgang der erneuten Aktivierung wird asynchron ausgeführt.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateJob">
      <MemberSignature Language="C#" Value="public void TerminateJob (string jobId, string terminateReason = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TerminateJob(string jobId, string terminateReason, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.TerminateJob(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub TerminateJob (jobId As String, Optional terminateReason As String = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.TerminateJob : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.TerminateJob (jobId, terminateReason, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags.</param>
        <param name="terminateReason">Der Text, der als des Auftrags angezeigt werden sollen <see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <summary>
            Beendet den angegebenen Auftrag als abgeschlossen gekennzeichnet.
            </summary>
        <remarks>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobOperations.TerminateJobAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task TerminateJobAsync (string jobId, string terminateReason = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task TerminateJobAsync(string jobId, string terminateReason, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.TerminateJobAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.TerminateJobAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.TerminateJobAsync (jobId, terminateReason, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;TerminateJobAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">Die Id des Auftrags.</param>
        <param name="terminateReason">Der Text, der als des Auftrags angezeigt werden sollen <see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Beendet den angegebenen Auftrag als abgeschlossen gekennzeichnet.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>Der Vorgang "Beenden" wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateTask">
      <MemberSignature Language="C#" Value="public void TerminateTask (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TerminateTask(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.TerminateTask(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub TerminateTask (jobId As String, taskId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.TerminateTask : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.TerminateTask (jobId, taskId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">Die ID des Auftrags, der den Task enthält.</param>
        <param name="taskId">Die ID des Tasks.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <summary>
            Beendet die angegebene Aufgabe an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>Dies ist ein blockierender Vorgang.  Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobOperations.TerminateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task TerminateTaskAsync (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task TerminateTaskAsync(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.TerminateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.TerminateTaskAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.TerminateTaskAsync (jobId, taskId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">Die ID des Auftrags, der den Task enthält.</param>
        <param name="taskId">Die ID des Tasks.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Beendet die angegebene Aufgabe an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>Der Vorgang "Beenden" wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>