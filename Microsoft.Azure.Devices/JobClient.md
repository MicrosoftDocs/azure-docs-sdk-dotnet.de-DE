<Type Name="JobClient" FullName="Microsoft.Azure.Devices.JobClient">
  <TypeSignature Language="C#" Value="public abstract class JobClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit JobClient extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.JobClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class JobClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type JobClient = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <summary>
            Auftragsverwaltung
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected JobClient ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; CancelJobAsync (string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; CancelJobAsync(string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CancelJobAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CancelJobAsync (jobId As String) As Task(Of JobResponse)" />
      <MemberSignature Language="F#" Value="abstract member CancelJobAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.CancelJobAsync jobId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId">ID des Auftrags auf "Abbrechen"</param>
        <summary>
            Bricht/löscht den Auftrag mit der angegebenen ID.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; CancelJobAsync (string jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; CancelJobAsync(string jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CancelJobAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CancelJobAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.CancelJobAsync (jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">ID des Auftrags auf "Abbrechen"</param>
        <param name="cancellationToken">Aufgabenabbruchtoken</param>
        <summary>
            Bricht/löscht den Auftrag mit der angegebenen ID.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="jobClient.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Schließt die JobClient-Instanz, und seine Ressourcen frei.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.JobClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.JobClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As JobClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.Devices.JobClient" Usage="Microsoft.Azure.Devices.JobClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"> Der Iot Hub-Verbindungszeichenfolge.</param>
        <summary>
            Erstellt eine JobClient aus der Iot Hub-Verbindungszeichenfolge an.
            </summary>
        <returns> Eine JobClient-Instanz. </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CreateQuery" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery () As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : unit -&gt; Microsoft.Azure.Devices.IQuery" Usage="jobClient.CreateQuery " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Abrufen von IQuery mit welcher Auftrag die Antworten für alle Auftragstypen und Statusangaben Seite abgerufen werden
            </summary>
        <returns>IQuery</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery (Nullable&lt;int&gt; pageSize);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery(valuetype System.Nullable`1&lt;int32&gt; pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CreateQuery(System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery (pageSize As Nullable(Of Integer)) As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : Nullable&lt;int&gt; -&gt; Microsoft.Azure.Devices.IQuery" Usage="jobClient.CreateQuery pageSize" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pageSize" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="pageSize">Anzahl von Auftragsantworten auf einer Seite</param>
        <summary>
            Abrufen von IQuery durch den Auftragsantworten Seite abgerufen werden und die Seitengröße angeben
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery (Nullable&lt;Microsoft.Azure.Devices.JobType&gt; jobType, Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt; jobStatus);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Devices.JobType&gt; jobType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Devices.JobStatus&gt; jobStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CreateQuery(System.Nullable{Microsoft.Azure.Devices.JobType},System.Nullable{Microsoft.Azure.Devices.JobStatus})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery (jobType As Nullable(Of JobType), jobStatus As Nullable(Of JobStatus)) As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : Nullable&lt;Microsoft.Azure.Devices.JobType&gt; * Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt; -&gt; Microsoft.Azure.Devices.IQuery" Usage="jobClient.CreateQuery (jobType, jobStatus)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobType" Type="System.Nullable&lt;Microsoft.Azure.Devices.JobType&gt;" />
        <Parameter Name="jobStatus" Type="System.Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="jobType">Der abzufragende Auftragstyp. Kann bei Abfragen nicht null sein.</param>
        <param name="jobStatus">Die abzufragende Auftragsstatus. Kann bei Abfragen nicht null sein.</param>
        <summary>
            Abrufen von IQuery mit welcher Auftrag Antworten für den angegebenen JobType und JobStatus Seite abgerufen werden
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery (Nullable&lt;Microsoft.Azure.Devices.JobType&gt; jobType, Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt; jobStatus, Nullable&lt;int&gt; pageSize);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Devices.JobType&gt; jobType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Devices.JobStatus&gt; jobStatus, valuetype System.Nullable`1&lt;int32&gt; pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CreateQuery(System.Nullable{Microsoft.Azure.Devices.JobType},System.Nullable{Microsoft.Azure.Devices.JobStatus},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery (jobType As Nullable(Of JobType), jobStatus As Nullable(Of JobStatus), pageSize As Nullable(Of Integer)) As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : Nullable&lt;Microsoft.Azure.Devices.JobType&gt; * Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Devices.IQuery" Usage="jobClient.CreateQuery (jobType, jobStatus, pageSize)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobType" Type="System.Nullable&lt;Microsoft.Azure.Devices.JobType&gt;" />
        <Parameter Name="jobStatus" Type="System.Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt;" />
        <Parameter Name="pageSize" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="jobType">Der abzufragende Auftragstyp. Kann bei Abfragen nicht null sein.</param>
        <param name="jobStatus">Die abzufragende Auftragsstatus. Kann bei Abfragen nicht null sein.</param>
        <param name="pageSize">Anzahl von Auftragsantworten auf einer Seite</param>
        <summary>
            Welcher Auftrag Antworten für angegebene JobType und JobStatus Seite abgerufen, und geben Sie die Seitengröße IQuery abrufen
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="jobClient.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="jobClient.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">
          <c>"true"</c> um sowohl verwaltete als auch nicht verwaltete Ressourcen freizugeben <c>"false"</c> um ausschließlich nicht verwaltete Ressourcen freizugeben.</param>
        <summary>
            Nicht verwaltete und optional verwaltete Ressourcen frei.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; GetJobAsync (string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; GetJobAsync(string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.GetJobAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetJobAsync (jobId As String) As Task(Of JobResponse)" />
      <MemberSignature Language="F#" Value="abstract member GetJobAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.GetJobAsync jobId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId">ID des Auftrags, der abgerufen werden</param>
        <summary>
            Ruft den Auftrag mit der angegebenen ID.
            </summary>
        <returns>Das übereinstimmende JobResponse-Objekt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; GetJobAsync (string jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; GetJobAsync(string jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.GetJobAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetJobAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.GetJobAsync (jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">ID des Auftrags, der abgerufen werden</param>
        <param name="cancellationToken">Aufgabenabbruchtoken</param>
        <summary>
            Ruft den Auftrag mit der angegebenen ID.
            </summary>
        <returns>Das übereinstimmende JobResponse-Objekt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task OpenAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OpenAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.OpenAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function OpenAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : unit -&gt; System.Threading.Tasks.Task" Usage="jobClient.OpenAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Öffnen Sie explizit die JobClient-Instanz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleDeviceMethodAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; ScheduleDeviceMethodAsync (string jobId, string queryCondition, Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod, DateTime startTimeUtc, long maxExecutionTimeInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; ScheduleDeviceMethodAsync(string jobId, string queryCondition, class Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod, valuetype System.DateTime startTimeUtc, int64 maxExecutionTimeInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.ScheduleDeviceMethodAsync(System.String,System.String,Microsoft.Azure.Devices.CloudToDeviceMethod,System.DateTime,System.Int64)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleDeviceMethodAsync : string * string * Microsoft.Azure.Devices.CloudToDeviceMethod * DateTime * int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.ScheduleDeviceMethodAsync (jobId, queryCondition, cloudToDeviceMethod, startTimeUtc, maxExecutionTimeInSeconds)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="queryCondition" Type="System.String" />
        <Parameter Name="cloudToDeviceMethod" Type="Microsoft.Azure.Devices.CloudToDeviceMethod" />
        <Parameter Name="startTimeUtc" Type="System.DateTime" />
        <Parameter Name="maxExecutionTimeInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="jobId">Eindeutige Auftrags-Id für diesen Auftrag</param>
        <param name="queryCondition">Fragen Sie die Geräte aus, um die Ausführung des Auftrags auf auszuwertenden Bedingung</param>
        <param name="cloudToDeviceMethod">Aufruf Methodenparameter</param>
        <param name="startTimeUtc">Datum-Zeit (UTC), um den Auftrag zu starten</param>
        <param name="maxExecutionTimeInSeconds">Maximale Ausführungszeit in Sekunden an, d. h. Ttl-Dauer an, die der Auftrag ausgeführt werden kann</param>
        <summary>
            Erstellt einen neuen Auftrag zum Ausführen einer Geräte-Methode auf einem oder mehreren Geräten
            </summary>
        <returns>Ein JobResponse-Objekt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleDeviceMethodAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; ScheduleDeviceMethodAsync (string jobId, string queryCondition, Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod, DateTime startTimeUtc, long maxExecutionTimeInSeconds, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; ScheduleDeviceMethodAsync(string jobId, string queryCondition, class Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod, valuetype System.DateTime startTimeUtc, int64 maxExecutionTimeInSeconds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.ScheduleDeviceMethodAsync(System.String,System.String,Microsoft.Azure.Devices.CloudToDeviceMethod,System.DateTime,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleDeviceMethodAsync : string * string * Microsoft.Azure.Devices.CloudToDeviceMethod * DateTime * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.ScheduleDeviceMethodAsync (jobId, queryCondition, cloudToDeviceMethod, startTimeUtc, maxExecutionTimeInSeconds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="queryCondition" Type="System.String" />
        <Parameter Name="cloudToDeviceMethod" Type="Microsoft.Azure.Devices.CloudToDeviceMethod" />
        <Parameter Name="startTimeUtc" Type="System.DateTime" />
        <Parameter Name="maxExecutionTimeInSeconds" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">Eindeutige Auftrags-Id für diesen Auftrag</param>
        <param name="queryCondition">Fragen Sie die Geräte aus, um die Ausführung des Auftrags auf auszuwertenden Bedingung</param>
        <param name="cloudToDeviceMethod">Aufruf Methodenparameter</param>
        <param name="startTimeUtc">Datum-Zeit (UTC), um den Auftrag zu starten</param>
        <param name="maxExecutionTimeInSeconds">Maximale Ausführungszeit in Sekunden an, d. h. Ttl-Dauer an, die der Auftrag ausgeführt werden kann</param>
        <param name="cancellationToken">Aufgabenabbruchtoken</param>
        <summary>
            Erstellt einen neuen Auftrag zum Ausführen einer Geräte-Methode auf einem oder mehreren Geräten
            </summary>
        <returns>Ein JobResponse-Objekt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleTwinUpdateAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; ScheduleTwinUpdateAsync (string jobId, string queryCondition, Microsoft.Azure.Devices.Shared.Twin twin, DateTime startTimeUtc, long maxExecutionTimeInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; ScheduleTwinUpdateAsync(string jobId, string queryCondition, class Microsoft.Azure.Devices.Shared.Twin twin, valuetype System.DateTime startTimeUtc, int64 maxExecutionTimeInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.ScheduleTwinUpdateAsync(System.String,System.String,Microsoft.Azure.Devices.Shared.Twin,System.DateTime,System.Int64)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleTwinUpdateAsync : string * string * Microsoft.Azure.Devices.Shared.Twin * DateTime * int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.ScheduleTwinUpdateAsync (jobId, queryCondition, twin, startTimeUtc, maxExecutionTimeInSeconds)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="queryCondition" Type="System.String" />
        <Parameter Name="twin" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="startTimeUtc" Type="System.DateTime" />
        <Parameter Name="maxExecutionTimeInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="jobId">Eindeutige Auftrags-Id für diesen Auftrag</param>
        <param name="queryCondition">Fragen Sie die Geräte aus, um die Ausführung des Auftrags auf auszuwertenden Bedingung</param>
        <param name="twin">Ziel-Objekt, das für die Aktualisierung verwendet</param>
        <param name="startTimeUtc">Datum-Zeit (UTC), um den Auftrag zu starten</param>
        <param name="maxExecutionTimeInSeconds">Maximale Ausführungszeit in Sekunden an, d. h. Ttl-Dauer an, die der Auftrag ausgeführt werden kann</param>
        <summary>
            Erstellt einen neuen Auftrag, um zwei Tags und die gewünschten Eigenschaften, die auf einem oder mehreren Geräten zu aktualisieren.
            </summary>
        <returns>Ein JobResponse-Objekt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleTwinUpdateAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; ScheduleTwinUpdateAsync (string jobId, string queryCondition, Microsoft.Azure.Devices.Shared.Twin twin, DateTime startTimeUtc, long maxExecutionTimeInSeconds, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; ScheduleTwinUpdateAsync(string jobId, string queryCondition, class Microsoft.Azure.Devices.Shared.Twin twin, valuetype System.DateTime startTimeUtc, int64 maxExecutionTimeInSeconds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.ScheduleTwinUpdateAsync(System.String,System.String,Microsoft.Azure.Devices.Shared.Twin,System.DateTime,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleTwinUpdateAsync : string * string * Microsoft.Azure.Devices.Shared.Twin * DateTime * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.ScheduleTwinUpdateAsync (jobId, queryCondition, twin, startTimeUtc, maxExecutionTimeInSeconds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="queryCondition" Type="System.String" />
        <Parameter Name="twin" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="startTimeUtc" Type="System.DateTime" />
        <Parameter Name="maxExecutionTimeInSeconds" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">Eindeutige Auftrags-Id für diesen Auftrag</param>
        <param name="queryCondition">Fragen Sie die Geräte aus, um die Ausführung des Auftrags auf auszuwertenden Bedingung</param>
        <param name="twin">Ziel-Objekt, das für die Aktualisierung verwendet</param>
        <param name="startTimeUtc">Datum-Zeit (UTC), um den Auftrag zu starten</param>
        <param name="maxExecutionTimeInSeconds">Maximale Ausführungszeit in Sekunden an, d. h. Ttl-Dauer an, die der Auftrag ausgeführt werden kann</param>
        <param name="cancellationToken">Aufgabenabbruchtoken</param>
        <summary>
            Erstellt einen neuen Auftrag, um zwei Tags und die gewünschten Eigenschaften, die auf einem oder mehreren Geräten zu aktualisieren.
            </summary>
        <returns>Ein JobResponse-Objekt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>