<Type Name="StreamingJobsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StreamingJobsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StreamingJobsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StreamingJobsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StreamingJobsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für StreamingJobsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob BeginCreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob BeginCreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginCreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginCreateOrReplace (operations, streamingJob, resourceGroupName, jobName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="streamingJob">
            Die Definition des streamingauftrags, die zum Erstellen eines neuen streamingauftrags oder Ersetzen der vorhandenen Dateigruppe verwendet werden.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="ifMatch">
            Das ETag des streamingauftrags. Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" damit wird eine neue streamingauftrag erstellt werden, aber um zu verhindern, aktualisieren eine vorhandene Satz aufzeichnen. Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.
            </param>
        <summary>
            Ein streaming-Auftrags erstellt oder eine bereits vorhandene streamingauftrag ersetzt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; BeginCreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; BeginCreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginCreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginCreateOrReplaceAsync (operations, streamingJob, resourceGroupName, jobName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;BeginCreateOrReplaceAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="streamingJob">
            Die Definition des streamingauftrags, die zum Erstellen eines neuen streamingauftrags oder Ersetzen der vorhandenen Dateigruppe verwendet werden.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="ifMatch">
            Das ETag des streamingauftrags. Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" damit wird eine neue streamingauftrag erstellt werden, aber um zu verhindern, aktualisieren eine vorhandene Satz aufzeichnen. Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ein streaming-Auftrags erstellt oder eine bereits vorhandene streamingauftrag ersetzt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginDelete (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <summary>
            Löscht eine streaming-Auftrags an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine streaming-Auftrags an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStart">
      <MemberSignature Language="C#" Value="public static void BeginStart (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginStart(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStart(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginStart (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String, Optional startJobParameters As StartStreamingJobParameters = null)" />
      <MemberSignature Language="F#" Value="static member BeginStart : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStart (operations, resourceGroupName, jobName, startJobParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="startJobParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="startJobParameters">
            Parameter für einen Einstieg streaming Job-Vorgang.
            </param>
        <summary>
            Startet eine streaming-Auftrags an. Nachdem ein Auftrag gestartet wird sie beginnt mit der Verarbeitung der Eingabeereignisse und Ausgabe erzeugt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStartAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStartAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStartAsync (operations, resourceGroupName, jobName, startJobParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;BeginStartAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="startJobParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="startJobParameters">
            Parameter für einen Einstieg streaming Job-Vorgang.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Startet eine streaming-Auftrags an. Nachdem ein Auftrag gestartet wird sie beginnt mit der Verarbeitung der Eingabeereignisse und Ausgabe erzeugt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStop">
      <MemberSignature Language="C#" Value="public static void BeginStop (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginStop(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStop(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginStop (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member BeginStop : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStop (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <summary>
            Beendet einen laufenden streaming-Auftrags an. Dies bewirkt einen gerade ausgeführten streaming-Auftrag zum Beenden der Verarbeitung der Eingabeereignisse und Ausgabe.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStopAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStopAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStopAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStopAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStopAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;BeginStopAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Beendet einen laufenden streaming-Auftrags an. Dies bewirkt einen gerade ausgeführten streaming-Auftrag zum Beenden der Verarbeitung der Eingabeereignisse und Ausgabe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.CreateOrReplace (operations, streamingJob, resourceGroupName, jobName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="streamingJob">
            Die Definition des streamingauftrags, die zum Erstellen eines neuen streamingauftrags oder Ersetzen der vorhandenen Dateigruppe verwendet werden.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="ifMatch">
            Das ETag des streamingauftrags. Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" damit wird eine neue streamingauftrag erstellt werden, aber um zu verhindern, aktualisieren eine vorhandene Satz aufzeichnen. Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.
            </param>
        <summary>
            Ein streaming-Auftrags erstellt oder eine bereits vorhandene streamingauftrag ersetzt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.CreateOrReplaceAsync (operations, streamingJob, resourceGroupName, jobName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="streamingJob">
            Die Definition des streamingauftrags, die zum Erstellen eines neuen streamingauftrags oder Ersetzen der vorhandenen Dateigruppe verwendet werden.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="ifMatch">
            Das ETag des streamingauftrags. Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" damit wird eine neue streamingauftrag erstellt werden, aber um zu verhindern, aktualisieren eine vorhandene Satz aufzeichnen. Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ein streaming-Auftrags erstellt oder eine bereits vorhandene streamingauftrag ersetzt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Delete(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Delete (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <summary>
            Löscht eine streaming-Auftrags an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.DeleteAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine streaming-Auftrags an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob Get (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob Get(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String, Optional expand As String = null) As StreamingJob" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Get (operations, resourceGroupName, jobName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="expand">
            Die $expand-OData-Abfrageparameter. Dies ist eine durch Trennzeichen getrennte Liste der zusätzlichen streaming Auftragseigenschaften einschließen, die in der Antwort, jenseits der Standardgrenze zurückgegebenen festgelegt, wenn dieser Parameter nicht vorhanden ist. Standardmäßig ist streaming Auftragseigenschaften als "Eingaben", "Transformation", "Ausgaben" und "Funktionen".
            </param>
        <summary>
            Ruft Details zu dem angegebenen streaming-Auftrags ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="expand">
            Die $expand-OData-Abfrageparameter. Dies ist eine durch Trennzeichen getrennte Liste der zusätzlichen streaming Auftragseigenschaften einschließen, die in der Antwort, jenseits der Standardgrenze zurückgegebenen festgelegt, wenn dieser Parameter nicht vorhanden ist. Standardmäßig ist streaming Auftragseigenschaften als "Eingaben", "Transformation", "Ausgaben" und "Funktionen".
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Details zu dem angegebenen streaming-Auftrags ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; List (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; List(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.List(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IStreamingJobsOperations, Optional expand As String = null) As IPage(Of StreamingJob)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.List (operations, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="expand">
            Die $expand-OData-Abfrageparameter. Dies ist eine durch Trennzeichen getrennte Liste der zusätzlichen streaming Auftragseigenschaften einschließen, die in der Antwort, jenseits der Standardgrenze zurückgegebenen festgelegt, wenn dieser Parameter nicht vorhanden ist. Standardmäßig ist streaming Auftragseigenschaften als "Eingaben", "Transformation", "Ausgaben" und "Funktionen".
            </param>
        <summary>
            Zeigt eine Liste aller der datenstromauftrag im angegebenen Abonnement.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListAsync (operations, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="expand">
            Die $expand-OData-Abfrageparameter. Dies ist eine durch Trennzeichen getrennte Liste der zusätzlichen streaming Auftragseigenschaften einschließen, die in der Antwort, jenseits der Standardgrenze zurückgegebenen festgelegt, wenn dieser Parameter nicht vorhanden ist. Standardmäßig ist streaming Auftragseigenschaften als "Eingaben", "Transformation", "Ausgaben" und "Funktionen".
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller der datenstromauftrag im angegebenen Abonnement.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListByResourceGroup (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListByResourceGroup(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IStreamingJobsOperations, resourceGroupName As String, Optional expand As String = null) As IPage(Of StreamingJob)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="expand">
            Die $expand-OData-Abfrageparameter. Dies ist eine durch Trennzeichen getrennte Liste der zusätzlichen streaming Auftragseigenschaften einschließen, die in der Antwort, jenseits der Standardgrenze zurückgegebenen festgelegt, wenn dieser Parameter nicht vorhanden ist. Standardmäßig ist streaming Auftragseigenschaften als "Eingaben", "Transformation", "Ausgaben" und "Funktionen".
            </param>
        <summary>
            Zeigt eine Liste aller streaming Aufträge in der angegebenen Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="expand">
            Die $expand-OData-Abfrageparameter. Dies ist eine durch Trennzeichen getrennte Liste der zusätzlichen streaming Auftragseigenschaften einschließen, die in der Antwort, jenseits der Standardgrenze zurückgegebenen festgelegt, wenn dieser Parameter nicht vorhanden ist. Standardmäßig ist streaming Auftragseigenschaften als "Eingaben", "Transformation", "Ausgaben" und "Funktionen".
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller streaming Aufträge in der angegebenen Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IStreamingJobsOperations, nextPageLink As String) As IPage(Of StreamingJob)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Zeigt eine Liste aller streaming Aufträge in der angegebenen Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller streaming Aufträge in der angegebenen Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListNext (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListNext(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListNext(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IStreamingJobsOperations, nextPageLink As String) As IPage(Of StreamingJob)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Zeigt eine Liste aller der datenstromauftrag im angegebenen Abonnement.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;ListNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller der datenstromauftrag im angegebenen Abonnement.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public static void Start (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Start(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Start(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Start (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String, Optional startJobParameters As StartStreamingJobParameters = null)" />
      <MemberSignature Language="F#" Value="static member Start : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Start (operations, resourceGroupName, jobName, startJobParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="startJobParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="startJobParameters">
            Parameter für einen Einstieg streaming Job-Vorgang.
            </param>
        <summary>
            Startet eine streaming-Auftrags an. Nachdem ein Auftrag gestartet wird sie beginnt mit der Verarbeitung der Eingabeereignisse und Ausgabe erzeugt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StartAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StartAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.StartAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.StartAsync (operations, resourceGroupName, jobName, startJobParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;StartAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="startJobParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="startJobParameters">
            Parameter für einen Einstieg streaming Job-Vorgang.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Startet eine streaming-Auftrags an. Nachdem ein Auftrag gestartet wird sie beginnt mit der Verarbeitung der Eingabeereignisse und Ausgabe erzeugt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public static void Stop (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Stop(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Stop(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Stop (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member Stop : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Stop (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <summary>
            Beendet einen laufenden streaming-Auftrags an. Dies bewirkt einen gerade ausgeführten streaming-Auftrag zum Beenden der Verarbeitung der Eingabeereignisse und Ausgabe.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StopAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StopAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.StopAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.StopAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;StopAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Beendet einen laufenden streaming-Auftrags an. Dies bewirkt einen gerade ausgeführten streaming-Auftrag zum Beenden der Verarbeitung der Eingabeereignisse und Ausgabe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob Update (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob Update(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Update (operations, streamingJob, resourceGroupName, jobName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="streamingJob">
            Ein streaming Job-Objekt. Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in der vorhandenen streamingauftrag (d. h. Diese Eigenschaften werden aktualisiert). Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in der vorhandenen Eingabe identisch bleibt und nicht als Ergebnis dieser PATCH-Vorgang geändert.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="ifMatch">
            Das ETag des streamingauftrags. Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <summary>
            Aktualisiert eine vorhandene streaming-Auftrags an. Dies kann verwendet werden, aktualisieren Sie teilweise (d. h. Aktualisieren Sie eine oder zwei Eigenschaften) einen streamingauftrag ohne den Rest der Auftragsdefinition.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.UpdateAsync (operations, streamingJob, resourceGroupName, jobName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="streamingJob">
            Ein streaming Job-Objekt. Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in der vorhandenen streamingauftrag (d. h. Diese Eigenschaften werden aktualisiert). Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in der vorhandenen Eingabe identisch bleibt und nicht als Ergebnis dieser PATCH-Vorgang geändert.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="ifMatch">
            Das ETag des streamingauftrags. Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert eine vorhandene streaming-Auftrags an. Dies kann verwendet werden, aktualisieren Sie teilweise (d. h. Aktualisieren Sie eine oder zwei Eigenschaften) einen streamingauftrag ohne den Rest der Auftragsdefinition.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>