<Type Name="JobScheduleExecutionInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation">
  <TypeSignature Language="C#" Value="public class JobScheduleExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobScheduleExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobScheduleExecutionInformation" />
  <TypeSignature Language="F#" Value="type JobScheduleExecutionInformation = class" />
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
            Enthält Informationen zu den Aufträgen, die Waren und wird unter einem Auftragszeitplan ausgeführt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobScheduleExecutionInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation.#ctor" />
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
            Initialisiert eine neue Instanz der JobScheduleExecutionInformation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobScheduleExecutionInformation (Nullable&lt;DateTime&gt; nextRunTime = null, Microsoft.Azure.Batch.Protocol.Models.RecentJob recentJob = null, Nullable&lt;DateTime&gt; endTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; nextRunTime, class Microsoft.Azure.Batch.Protocol.Models.RecentJob recentJob, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation.#ctor(System.Nullable{System.DateTime},Microsoft.Azure.Batch.Protocol.Models.RecentJob,System.Nullable{System.DateTime})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation : Nullable&lt;DateTime&gt; * Microsoft.Azure.Batch.Protocol.Models.RecentJob * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation (nextRunTime, recentJob, endTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nextRunTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="recentJob" Type="Microsoft.Azure.Batch.Protocol.Models.RecentJob" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="nextRunTime">Das nächste Mal an dem ein Auftrag unter diesem Plan erstellt wird.</param>
        <param name="recentJob">Informationen zu den aktuellen Auftrag unter der Auftragszeitplan.</param>
        <param name="endTime">Der Zeitpunkt, zu dem der Zeitplan beendet wurde.</param>
        <summary>
            Initialisiert eine neue Instanz der JobScheduleExecutionInformation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation.EndTime" />
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
            Ruft ab oder legt die Zeit, zu dem der Zeitplan beendet wurde.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird festgelegt, nur dann, wenn der Zeitplan für Aufträge in den abgeschlossenen Zustand versetzt wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NextRunTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NextRunTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NextRunTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation.NextRunTime" />
      <MemberSignature Language="VB.NET" Value="Public Property NextRunTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NextRunTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation.NextRunTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextRunTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das nächste Mal an dem ein Auftrag unter diesem Plan erstellt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft ist nur sinnvoll, wenn der Zeitplan im aktiven Zustand ist, wenn die Zeit, um eingeht. Z. B. wenn der Zeitplan deaktiviert ist, wird kein Auftrag auf NextRunTime-Objekt erstellt werden, wenn der Auftrag vorher aktiviert ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RecentJob">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.RecentJob RecentJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.RecentJob RecentJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation.RecentJob" />
      <MemberSignature Language="VB.NET" Value="Public Property RecentJob As RecentJob" />
      <MemberSignature Language="F#" Value="member this.RecentJob : Microsoft.Azure.Batch.Protocol.Models.RecentJob with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation.RecentJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recentJob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.RecentJob</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Informationen zum neuesten Auftrag unter der Auftragszeitplan.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft ist nur vorhanden, wenn mindestens ein Auftrag unter dem Zeitplan ausgeführt wurde.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>