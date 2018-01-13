<Type Name="StartTaskInformation" FullName="Microsoft.Azure.Batch.StartTaskInformation">
  <TypeSignature Language="C#" Value="public class StartTaskInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StartTaskInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.StartTaskInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class StartTaskInformation" />
  <TypeSignature Language="F#" Value="type StartTaskInformation = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Gibt die ausführliche Laufzeitinformationen der Startaufgabe, einschließlich der aktuellen Status, Fehlerdetails, Exitcode, Startzeit, Endzeit usw. an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContainerInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskContainerExecutionInformation ContainerInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskContainerExecutionInformation ContainerInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.ContainerInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerInformation As TaskContainerExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ContainerInformation : Microsoft.Azure.Batch.TaskContainerExecutionInformation" Usage="Microsoft.Azure.Batch.StartTaskInformation.ContainerInformation" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.StartTaskInformation.EndTime" />
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
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.StartTaskInformation.ExitCode" />
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
            Diese Eigenschaft wird nur zurückgegeben, wenn die Aufgabe in der <see cref="F:Microsoft.Azure.Batch.Common.StartTaskState.Completed" /> Zustand. Der Exitcode für einen Prozess spiegelt wider, die spezifische Konvention, die vom Anwendungsentwickler für diesen Prozess implementiert wird. Wenn Sie den Exitcodewert für Entscheidungen in Ihrem Code verwenden, achten Sie darauf, dass Sie wissen, dass die Exit Code Konvention, die von der Anwendungsprozess verwendet. Beachten Sie, dass der Exitcode von Compute Knoten ausgeführt wird, z. B. wenn ein Prozess abgebrochen wird ebenfalls generiert werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskFailureInformation FailureInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskFailureInformation FailureInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.FailureInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureInformation As TaskFailureInformation" />
      <MemberSignature Language="F#" Value="member this.FailureInformation : Microsoft.Azure.Batch.TaskFailureInformation" Usage="Microsoft.Azure.Batch.StartTaskInformation.FailureInformation" />
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
            Diese Eigenschaft wird festgelegt, nur dann, wenn die Aufgabe ist die <see cref="F:Microsoft.Azure.Batch.Common.StartTaskState.Completed" /> Status und hat einen Fehler festgestellt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRetryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRetryTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRetryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.LastRetryTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastRetryTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRetryTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.StartTaskInformation.LastRetryTime" />
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
            Ruft ab, der letzte Zeitpunkt, an dem Ausführung der Startaufgabe vom batchdienst wiederholt wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt; Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.TaskExecutionResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As Nullable(Of TaskExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt;" Usage="Microsoft.Azure.Batch.StartTaskInformation.Result" />
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
            Wenn der Wert <see cref="F:Microsoft.Azure.Batch.Common.TaskExecutionResult.Failure" />, und klicken Sie dann die Details des Fehlers können, in gefunden werden der <see cref="P:Microsoft.Azure.Batch.StartTaskInformation.FailureInformation" /> Eigenschaft.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryCount">
      <MemberSignature Language="C#" Value="public int RetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.RetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.RetryCount : int" Usage="Microsoft.Azure.Batch.StartTaskInformation.RetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Häufigkeit, mit der die Startaufgabe vom System Batch wiederholt wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.StartTaskInformation.StartTime" />
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
            Ruft den Zeitpunkt, an dem der Task die Ausführung gestartet wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.StartTaskState State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.StartTaskState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As StartTaskState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.Batch.Common.StartTaskState" Usage="Microsoft.Azure.Batch.StartTaskInformation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.StartTaskState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den aktuellen Ausführungsstatus der Startaufgabe.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>