<Type Name="JobExecutionInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation">
  <TypeSignature Language="C#" Value="public class JobExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobExecutionInformation" />
  <TypeSignature Language="F#" Value="type JobExecutionInformation = class" />
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
            Enthält Informationen zur Ausführung eines Auftrags in der Azure Batch-Dienst an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobExecutionInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.#ctor" />
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
            Initialisiert eine neue Instanz der JobExecutionInformation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobExecutionInformation (DateTime startTime, Nullable&lt;DateTime&gt; endTime = null, string poolId = null, Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError schedulingError = null, string terminateReason = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string poolId, class Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError schedulingError, string terminateReason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.#ctor(System.DateTime,System.Nullable{System.DateTime},System.String,Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startTime As DateTime, Optional endTime As Nullable(Of DateTime) = null, Optional poolId As String = null, Optional schedulingError As JobSchedulingError = null, Optional terminateReason As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation : DateTime * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError * string -&gt; Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation (startTime, endTime, poolId, schedulingError, terminateReason)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="schedulingError" Type="Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError" />
        <Parameter Name="terminateReason" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="startTime">Die Startzeit des Auftrags.</param>
        <param name="endTime">Die Ausführungszeit des Auftrags.</param>
        <param name="poolId">Die ID des Pools, der dieser Auftrag zugewiesen wird.</param>
        <param name="schedulingError">Details zu jeder Fehler, die vom Dienst beim Starten des Auftrags.</param>
        <param name="terminateReason">Eine Zeichenfolge, die Beschreibung der Ursache für den Auftrag wurde beendet.</param>
        <summary>
            Initialisiert eine neue Instanz der JobExecutionInformation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.EndTime" />
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
            Ruft ab oder legt die Ausführungszeit des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird festgelegt, nur dann, wenn der Auftrag im abgeschlossenen Zustand befindet.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.PoolId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ID des Pools, der dieser Auftrag zugewiesen wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dieses Element enthält den tatsächlichen Pool, auf dem der Auftrag zugewiesen ist.
            Wenn Sie die Auftragsdetails aus dem Dienst erhalten, enthalten sie auch eine PoolInfo Element, das die Pool-Konfigurationsdaten aus der Auftrag hinzugefügt oder aktualisiert wurde. Dieses Element PoolInfo kann auch ein PoolId-Element enthalten. Wenn dies der Fall ist, sind die beiden IDs identisch. Wenn dies nicht der Fall ist, bedeutet dies der Auftrag ausgeführt wurde, auf ein automatischer Pool, und diese Eigenschaft enthält die ID der dieser automatischen Pool an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SchedulingError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError SchedulingError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError SchedulingError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.SchedulingError" />
      <MemberSignature Language="VB.NET" Value="Public Property SchedulingError As JobSchedulingError" />
      <MemberSignature Language="F#" Value="member this.SchedulingError : Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.SchedulingError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schedulingError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert Details für alle Fehler vom Dienst beim Starten des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft ist nicht festgelegt, wenn kein Fehler den Auftrag ab.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.StartTime" />
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
            Ruft ab oder legt die Startzeit des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies ist die Zeit, zu der der Auftrag erstellt wurde.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateReason">
      <MemberSignature Language="C#" Value="public string TerminateReason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TerminateReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.TerminateReason" />
      <MemberSignature Language="VB.NET" Value="Public Property TerminateReason As String" />
      <MemberSignature Language="F#" Value="member this.TerminateReason : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.TerminateReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="terminateReason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Zeichenfolge, die Beschreibung der Ursache für den Auftrag wurde beendet.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird festgelegt, nur dann, wenn der Auftrag im abgeschlossenen Zustand befindet. Wenn der Batch-Dienst den Auftrag beendet wird, legt er den Grund wie folgt: JMComplete - die Auftrags-Manager-Aufgabe abgeschlossen und KillJobOnCompletion festgelegt wurde auf "true". MaxWallClockTimeExpiry - der Auftrag erreicht ihre MaxWallClockTime-Einschränkung. TerminateJobSchedule - der Auftrag ausgeführt wurde, im Rahmen eines Zeitplans und der Zeitplan beendet.
            AllTasksComplete - der Auftrag OnAllTasksComplete-Attribut auf TerminateJob festgelegt ist, und alle Aufgaben im Auftrag abgeschlossen sind. TaskFailed - ist der Auftrag OnTaskFailure-Attributsatz zur PerformExitOptionsJobAction und einer Aufgabe im Auftrag, bei der eine beenden-Bedingung, die eine JobAction von TerminateJob angegeben. Eine beliebige andere Zeichenfolge ist ein benutzerdefinierter Grund, die in einem Aufruf des Vorgangs "Beenden ein Auftrags" angegeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobExecutionInformation.Validate " />
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