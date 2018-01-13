<Type Name="JobReleaseTaskExecutionInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation">
  <TypeSignature Language="C#" Value="public class JobReleaseTaskExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobReleaseTaskExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobReleaseTaskExecutionInformation" />
  <TypeSignature Language="F#" Value="type JobReleaseTaskExecutionInformation = class" />
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
            Enthält Informationen zur Ausführung eines Auftrags Version Tasks auf einem Serverknoten an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobReleaseTaskExecutionInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der JobReleaseTaskExecutionInformation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobReleaseTaskExecutionInformation (DateTime startTime, Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskState state, Nullable&lt;DateTime&gt; endTime = null, string taskRootDirectory = null, string taskRootDirectoryUrl = null, Nullable&lt;int&gt; exitCode = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation containerInfo = null, Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation failureInfo = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; result = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime startTime, valuetype Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskState state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string taskRootDirectory, string taskRootDirectoryUrl, valuetype System.Nullable`1&lt;int32&gt; exitCode, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation containerInfo, class Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation failureInfo, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.#ctor(System.DateTime,Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskState,System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation,Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startTime As DateTime, state As JobReleaseTaskState, Optional endTime As Nullable(Of DateTime) = null, Optional taskRootDirectory As String = null, Optional taskRootDirectoryUrl As String = null, Optional exitCode As Nullable(Of Integer) = null, Optional containerInfo As TaskContainerExecutionInformation = null, Optional failureInfo As TaskFailureInformation = null, Optional result As Nullable(Of TaskExecutionResult) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation : DateTime * Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskState * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation * Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation (startTime, state, endTime, taskRootDirectory, taskRootDirectoryUrl, exitCode, containerInfo, failureInfo, result)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="state" Type="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskState" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="taskRootDirectory" Type="System.String" />
        <Parameter Name="taskRootDirectoryUrl" Type="System.String" />
        <Parameter Name="exitCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="containerInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation" />
        <Parameter Name="failureInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation" />
        <Parameter Name="result" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt;" />
      </Parameters>
      <Docs>
        <param name="startTime">Der Zeitpunkt, an dem die Ausführung des Tasks gestartet wurde.</param>
        <param name="state">Der aktuelle Status des Tasks Auftrag Version auf den Computeknoten.</param>
        <param name="endTime">Der Zeitpunkt, zu dem der Auftrag Version Aufgabe abgeschlossen wurde.</param>
        <param name="taskRootDirectory">Das Stammverzeichnis des Tasks Auftrag Version auf den Computeknoten. Sie können diesen Pfad verwenden, zum Abrufen von Dateien, die von der Aufgabe, wie z. B. Protokolldateien erstellt.</param>
        <param name="taskRootDirectoryUrl">Die URL in das Stammverzeichnis des Tasks Auftrag Version auf den Computeknoten.</param>
        <param name="exitCode">Der Exitcode des Programms in der Befehlszeile der Aufgabe angegeben.</param>
        <param name="containerInfo">Informationen über den Container, die unter dem die Aufgabe ausgeführt wird.</param>
        <param name="failureInfo">Informationen, die den Aufgabenfehler beschreibt, sofern vorhanden.</param>
        <param name="result">Das Ergebnis der Taskausführung.</param>
        <summary>
            Initialisiert eine neue Instanz der JobReleaseTaskExecutionInformation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation ContainerInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation ContainerInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.ContainerInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerInfo As TaskContainerExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ContainerInfo : Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.ContainerInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Informationen über den Container unter dem die Aufgabe ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird festgelegt, nur dann, wenn die Aufgabe in einem Container-Kontext ausgeführt wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit, zu dem der Auftrag Version Aufgabe abgeschlossen wurde.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird festgelegt, nur dann, wenn der Task in den Status "Completed" befindet.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.ExitCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Exitcode des Programms in der Befehlszeile der Aufgabe angegeben.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dieser Parameter wird zurückgegeben, nur dann, wenn der Task in den abgeschlossenen Zustand befindet. Der Exitcode für einen Prozess spiegelt wider, die spezifische Konvention, die vom Anwendungsentwickler für diesen Prozess implementiert wird. Wenn Sie den Exitcodewert für Entscheidungen in Ihrem Code verwenden, achten Sie darauf, dass Sie wissen, dass die Exit Code Konvention, die von der Anwendungsprozess verwendet. Beachten Sie, dass der Exitcode von Compute Knoten ausgeführt wird, z. B. wenn ein Prozess abgebrochen wird ebenfalls generiert werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation FailureInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation FailureInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.FailureInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureInfo As TaskFailureInformation" />
      <MemberSignature Language="F#" Value="member this.FailureInfo : Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.FailureInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failureInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, die den Taskfehler beschreibt ggf.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird festgelegt, wenn der Task in den abgeschlossenen Zustand befindet und hat einen Fehler festgestellt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; Result { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.Result" />
      <MemberSignature Language="VB.NET" Value="Public Property Result As Nullable(Of TaskExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="result")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Ergebnis der Taskausführung fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn der Wert "fehlgeschlagen", können die Details des Fehlers in der Eigenschaft FailureInfo gefunden werden. Folgende Werte sind möglich: "Success", "Fehler"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit, an dem der Task die Ausführung gestartet wurde.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn der Task neu gestartet oder wiederholt wurde, ist dies der letzte Zeitpunkt, an dem die Ausführung des Tasks gestartet wurde.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskState State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As JobReleaseTaskState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskState with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den aktuellen Status des Tasks "Auftrag Version" auf den Computeknoten.
            </summary>
        <value>To be added.</value>
        <remarks>
            Folgende Werte sind möglich: "wird ausgeführt", "abgeschlossen"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskRootDirectory">
      <MemberSignature Language="C#" Value="public string TaskRootDirectory { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskRootDirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.TaskRootDirectory" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskRootDirectory As String" />
      <MemberSignature Language="F#" Value="member this.TaskRootDirectory : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.TaskRootDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskRootDirectory")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Stammverzeichnis des Tasks "Auftrag Version" auf den Computeknoten. Sie können diesen Pfad verwenden, zum Abrufen von Dateien, die von der Aufgabe, wie z. B. Protokolldateien erstellt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskRootDirectoryUrl">
      <MemberSignature Language="C#" Value="public string TaskRootDirectoryUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskRootDirectoryUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.TaskRootDirectoryUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskRootDirectoryUrl As String" />
      <MemberSignature Language="F#" Value="member this.TaskRootDirectoryUrl : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.TaskRootDirectoryUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskRootDirectoryUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die URL in das Stammverzeichnis des Tasks "Auftrag Release" fest, auf den Computeknoten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobReleaseTaskExecutionInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>