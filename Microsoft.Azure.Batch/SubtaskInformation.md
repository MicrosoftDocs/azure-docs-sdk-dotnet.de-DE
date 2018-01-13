<Type Name="SubtaskInformation" FullName="Microsoft.Azure.Batch.SubtaskInformation">
  <TypeSignature Language="C#" Value="public class SubtaskInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubtaskInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.SubtaskInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class SubtaskInformation" />
  <TypeSignature Language="F#" Value="type SubtaskInformation = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Informationen über ein Azure Batch-Teilvorgang.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ComputeNodeInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNodeInformation ComputeNodeInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ComputeNodeInformation ComputeNodeInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.ComputeNodeInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputeNodeInformation As ComputeNodeInformation" />
      <MemberSignature Language="F#" Value="member this.ComputeNodeInformation : Microsoft.Azure.Batch.ComputeNodeInformation" Usage="Microsoft.Azure.Batch.SubtaskInformation.ComputeNodeInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNodeInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Informationen zu den Compute-Knoten, auf dem die Unteraufgabe ausgeführt wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskContainerExecutionInformation ContainerInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskContainerExecutionInformation ContainerInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.ContainerInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerInformation As TaskContainerExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ContainerInformation : Microsoft.Azure.Batch.TaskContainerExecutionInformation" Usage="Microsoft.Azure.Batch.SubtaskInformation.ContainerInformation" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.EndTime" />
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
            Ruft den Zeitpunkt, an dem die Unteraufgabe abgeschlossen war. Diese Eigenschaft wird festgelegt, nur, wenn in der Fall ist die <see cref="F:Microsoft.Azure.Batch.Common.SubtaskState.Completed" /> Zustand.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.ExitCode" />
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
            Ruft den Exitcode des Programms angegeben, in der Befehlszeile für die Unteraufgaben an.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird nur zurückgegeben, wenn in der Fall ist die <see cref="F:Microsoft.Azure.Batch.Common.SubtaskState.Completed" /> Zustand. Der Exitcode für einen Prozess spiegelt wider, die spezifische Konvention, die vom Anwendungsentwickler für diesen Prozess implementiert wird. Wenn Sie den Exitcodewert für Entscheidungen in Ihrem Code verwenden, achten Sie darauf, dass Sie wissen, dass die Exit Code Konvention, die von der Anwendungsprozess verwendet. Beachten Sie, dass der Exitcode von Compute Knoten ausgeführt wird, z. B. wenn ein Prozess abgebrochen wird ebenfalls generiert werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskFailureInformation FailureInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskFailureInformation FailureInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.FailureInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureInformation As TaskFailureInformation" />
      <MemberSignature Language="F#" Value="member this.FailureInformation : Microsoft.Azure.Batch.TaskFailureInformation" Usage="Microsoft.Azure.Batch.SubtaskInformation.FailureInformation" />
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
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Id : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.Id" />
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
            Ruft die Id für die Unteraufgaben an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.SubtaskState&gt; PreviousState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.SubtaskState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousState As Nullable(Of SubtaskState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Common.SubtaskState&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.PreviousState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.SubtaskState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den vorherigen Zustand für die Unteraufgaben an. Diese Eigenschaft ist nicht festgelegt, ist der Fall in die erste <see cref="F:Microsoft.Azure.Batch.Common.SubtaskState.Running" /> Zustand.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.PreviousStateTransitionTime" />
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
            Ruft den Zeitpunkt, zu dem der Teilvorgang den vorherigen Zustand angenommen hat. Diese Eigenschaft ist nicht festgelegt, ist der Fall in die erste <see cref="F:Microsoft.Azure.Batch.Common.SubtaskState.Running" /> Zustand.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt; Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.TaskExecutionResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As Nullable(Of TaskExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.Result" />
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
            Wenn der Wert <see cref="F:Microsoft.Azure.Batch.Common.TaskExecutionResult.Failure" />, und klicken Sie dann die Details des Fehlers können, in gefunden werden der <see cref="P:Microsoft.Azure.Batch.SubtaskInformation.FailureInformation" /> Eigenschaft.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.StartTime" />
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
            Ruft den Zeitpunkt, zu dem die Unteraufgabe Ausführung gestartet wurde. Wenn die Unteraufgabe neu gestartet oder wiederholt wurde, ist dies der letzte Zeitpunkt, zu dem die Unteraufgabe Ausführung gestartet wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.SubtaskState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.SubtaskState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of SubtaskState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Common.SubtaskState&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.SubtaskState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den aktuellen Status für die Unteraufgaben an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.StateTransitionTime" />
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
            Ruft den Zeitpunkt, zu dem die Unteraufgabe seinem aktuellen Status erlangt hat.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>