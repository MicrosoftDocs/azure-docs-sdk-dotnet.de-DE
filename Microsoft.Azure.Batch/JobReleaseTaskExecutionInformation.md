<Type Name="JobReleaseTaskExecutionInformation" FullName="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation">
  <TypeSignature Language="C#" Value="public class JobReleaseTaskExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobReleaseTaskExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobReleaseTaskExecutionInformation" />
  <TypeSignature Language="F#" Value="type JobReleaseTaskExecutionInformation = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Details über die Ausführung einer <see cref="P:Microsoft.Azure.Batch.CloudJob.JobReleaseTask">Task Auftrag freigeben</see> auf einem Serverknoten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContainerInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskContainerExecutionInformation ContainerInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskContainerExecutionInformation ContainerInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.ContainerInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerInformation As TaskContainerExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ContainerInformation : Microsoft.Azure.Batch.TaskContainerExecutionInformation" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.ContainerInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskContainerExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Informationen über den Container unter dem die Aufgabe ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird festgelegt, nur dann, wenn die Aufgabe in einem Container-Kontext ausgeführt wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitpunkt, zu dem die Aufgabe abgeschlossen wurde.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird nur zurückgegeben, wenn die Aufgabe in der <see cref="F:Microsoft.Azure.Batch.Common.JobReleaseTaskState.Completed" /> Zustand.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.ExitCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Exitcode des Programms angegeben, in der Befehlszeile der Aufgabe ab.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird nur zurückgegeben, wenn die Aufgabe in der <see cref="F:Microsoft.Azure.Batch.Common.JobReleaseTaskState.Completed" /> Zustand. Der Exitcode für einen Prozess spiegelt wider, die spezifische Konvention, die vom Anwendungsentwickler für diesen Prozess implementiert wird. Wenn Sie den Exitcodewert für Entscheidungen in Ihrem Code verwenden, achten Sie darauf, dass Sie wissen, dass die Exit Code Konvention, die von der Anwendungsprozess verwendet. Beachten Sie, dass der Exitcode von Compute Knoten ausgeführt wird, z. B. wenn ein Prozess abgebrochen wird ebenfalls generiert werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskFailureInformation FailureInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskFailureInformation FailureInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.FailureInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureInformation As TaskFailureInformation" />
      <MemberSignature Language="F#" Value="member this.FailureInformation : Microsoft.Azure.Batch.TaskFailureInformation" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.FailureInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskFailureInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Informationen den Taskfehler ggf., beschreiben.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird festgelegt, nur dann, wenn die Aufgabe ist die <see cref="F:Microsoft.Azure.Batch.Common.JobReleaseTaskState.Completed" /> Status und hat einen Fehler festgestellt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt; Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.TaskExecutionResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As Nullable(Of TaskExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt;" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Ergebnis der Taskausführung ab.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn der Wert <see cref="F:Microsoft.Azure.Batch.Common.TaskExecutionResult.Failure" />, und klicken Sie dann die Details des Fehlers können, in gefunden werden der <see cref="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.FailureInformation" /> Eigenschaft.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitpunkt, an dem der Task die Ausführung gestartet wurde. Beachten Sie, dass jedes Mal, wenn der Task neu gestartet wird, diesen Wert aktualisiert wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.JobReleaseTaskState State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.JobReleaseTaskState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As JobReleaseTaskState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.Batch.Common.JobReleaseTaskState" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobReleaseTaskState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den aktuellen Status der Aufgabe ab.
            </summary>
        <value>To be added.</value>
        <remarks>
            Ausführen bedeutet, dass die Aufgabe gerade ausgeführt wird. Abgeschlossen bedeutet, dass die Aufgabe abgeschlossen wurde. Der Status "Completed" enthält die Groß-/Kleinschreibung, in dem die Aufgabe wurde erfolgreich mit Exitcode 0 beendet wird, sowie die Fälle, in denen das System zum Starten des Prozesses Vorgang wegen planungsfehlern oder nach zahlreiche verursacht das Wiederholungslimit erreicht wurde. 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskRootDirectory">
      <MemberSignature Language="C#" Value="public string TaskRootDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskRootDirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.TaskRootDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskRootDirectory As String" />
      <MemberSignature Language="F#" Value="member this.TaskRootDirectory : string" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.TaskRootDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Stammverzeichnis des Tasks "Auftrag Version" auf den Computeknoten ab. Sie können diesen Pfad verwenden, zum Abrufen von Dateien, die von der Aufgabe, wie z. B. Protokolldateien erstellt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskRootDirectoryUrl">
      <MemberSignature Language="C#" Value="public string TaskRootDirectoryUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskRootDirectoryUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.TaskRootDirectoryUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskRootDirectoryUrl As String" />
      <MemberSignature Language="F#" Value="member this.TaskRootDirectoryUrl : string" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.TaskRootDirectoryUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die URL in das Stammverzeichnis des Tasks "Auftrag Version" auf den Computeknoten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>