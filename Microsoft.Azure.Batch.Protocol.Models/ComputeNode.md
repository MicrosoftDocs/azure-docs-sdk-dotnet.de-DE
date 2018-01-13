<Type Name="ComputeNode" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNode">
  <TypeSignature Language="C#" Value="public class ComputeNode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNode extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNode" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNode" />
  <TypeSignature Language="F#" Value="type ComputeNode = class" />
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
            Compute-Knoten in der Batch-Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.#ctor" />
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
            Initialisiert eine neue Instanz der ComputeNode-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNode (string id = null, string url = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; state = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; schedulingState = null, Nullable&lt;DateTime&gt; stateTransitionTime = null, Nullable&lt;DateTime&gt; lastBootTime = null, Nullable&lt;DateTime&gt; allocationTime = null, string ipAddress = null, string affinityId = null, string vmSize = null, Nullable&lt;int&gt; totalTasksRun = null, Nullable&lt;int&gt; runningTasksCount = null, Nullable&lt;int&gt; totalTasksSucceeded = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; recentTasks = null, Microsoft.Azure.Batch.Protocol.Models.StartTask startTask = null, Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation startTaskInfo = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; errors = null, Nullable&lt;bool&gt; isDedicated = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration endpointConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string url, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; state, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; schedulingState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; stateTransitionTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastBootTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; allocationTime, string ipAddress, string affinityId, string vmSize, valuetype System.Nullable`1&lt;int32&gt; totalTasksRun, valuetype System.Nullable`1&lt;int32&gt; runningTasksCount, valuetype System.Nullable`1&lt;int32&gt; totalTasksSucceeded, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; recentTasks, class Microsoft.Azure.Batch.Protocol.Models.StartTask startTask, class Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation startTaskInfo, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; errors, valuetype System.Nullable`1&lt;bool&gt; isDedicated, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration endpointConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.SchedulingState},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskInformation},Microsoft.Azure.Batch.Protocol.Models.StartTask,Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.CertificateReference},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError},System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ComputeNode : string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; * Microsoft.Azure.Batch.Protocol.Models.StartTask * Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNode" Usage="new Microsoft.Azure.Batch.Protocol.Models.ComputeNode (id, url, state, schedulingState, stateTransitionTime, lastBootTime, allocationTime, ipAddress, affinityId, vmSize, totalTasksRun, runningTasksCount, totalTasksSucceeded, recentTasks, startTask, startTaskInfo, certificateReferences, errors, isDedicated, endpointConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt;" />
        <Parameter Name="schedulingState" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt;" />
        <Parameter Name="stateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastBootTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="allocationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ipAddress" Type="System.String" />
        <Parameter Name="affinityId" Type="System.String" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="totalTasksRun" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="runningTasksCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="totalTasksSucceeded" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recentTasks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt;" />
        <Parameter Name="startTask" Type="Microsoft.Azure.Batch.Protocol.Models.StartTask" />
        <Parameter Name="startTaskInfo" Type="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation" />
        <Parameter Name="certificateReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;" />
        <Parameter Name="errors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt;" />
        <Parameter Name="isDedicated" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="endpointConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration" />
      </Parameters>
      <Docs>
        <param name="id">Die ID des Serverknotens.</param>
        <param name="url">Die URL des Serverknotens.</param>
        <param name="state">Der aktuelle Status des Serverknotens.</param>
        <param name="schedulingState">Gibt an, ob der Computeknoten für die aufgabenplanung verfügbar ist.</param>
        <param name="stateTransitionTime">Der Zeitpunkt, zu dem die Serverknoten seinem aktuellen Status erlangt hat.</param>
        <param name="lastBootTime">Die Zeit, an der die Serverknoten gestartet wurde.</param>
        <param name="allocationTime">Der Zeitpunkt, zu dem dieser Serverknoten dem Pool zugewiesen wurde.</param>
        <param name="ipAddress">Die IP-Adresse, die andere Serverknoten verwenden können, für die Kommunikation mit diesem Computeknoten.</param>
        <param name="affinityId">Ein Bezeichner, der für die Hinzufügen einer Aufgabe anfordern, die der Aufgabe geplant werden auf diesem Knoten übergeben werden kann.</param>
        <param name="vmSize">Die Größe des virtuellen Computers die Compute-Knoten gehostet.</param>
        <param name="totalTasksRun">Die Gesamtanzahl der Auftragsaufgaben auf den Computeknoten abgeschlossen. Dies schließt die Auftrags-Manager-Aufgaben und normale Vorgänge jedoch Auftrag Vorbereitung Auftrag freigeben, oder Starten von Aufgaben nicht.</param>
        <param name="runningTasksCount">Die Gesamtanzahl der aktuell ausgeführten Aufgaben auf den Computeknoten. Dies schließt die Auftrags-Manager-Aufgaben und normale Vorgänge jedoch Auftrag Vorbereitung Auftrag freigeben, oder Starten von Aufgaben nicht.</param>
        <param name="totalTasksSucceeded">Die Gesamtanzahl der Auftragsaufgaben die (mit ExitCode 0) wurde erfolgreich abgeschlossen auf dem Computeknoten.
            Dies schließt die Auftrags-Manager-Aufgaben und normale Vorgänge jedoch Auftrag Vorbereitung Auftrag freigeben, oder Starten von Aufgaben nicht.</param>
        <param name="recentTasks">Eine Liste der Aufgaben, deren Status zuletzt geändert wurde.</param>
        <param name="startTask">Der Task auf den Computeknoten ausgeführt wird, wie sie den Pool verknüpft.</param>
        <param name="startTaskInfo">Common Language Runtime Informationen über die Ausführung des Tasks "Start" auf den Computeknoten.</param>
        <param name="certificateReferences">Die Liste der Zertifikate auf dem Computeknoten installiert.</param>
        <param name="errors">Die Liste der Fehler, die derzeit von der Computeknoten auftreten.</param>
        <param name="isDedicated">Gibt an, ob diese Computeknoten einen dedizierten Knoten ist. Wenn "false" ist der Knoten eines Knotens mit niedriger Priorität.</param>
        <param name="endpointConfiguration">Die Endpunktkonfiguration für den Computeknoten.</param>
        <summary>
            Initialisiert eine neue Instanz der ComputeNode-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityId">
      <MemberSignature Language="C#" Value="public string AffinityId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AffinityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.AffinityId" />
      <MemberSignature Language="VB.NET" Value="Public Property AffinityId As String" />
      <MemberSignature Language="F#" Value="member this.AffinityId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.AffinityId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="affinityId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Bezeichner die übergeben werden kann, wenn eine Aufgabe, um anzufordern, dass die Aufgabe geplant werden, auf diesem Knoten hinzufügen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Beachten Sie, dass dies nur ein weicher Affinität ist. Wenn der Zielknoten ausgelastet ist oder nicht verfügbar, die zum Zeitpunkt der Task geplant ist, wird die Aufgabe an anderer Stelle geplant werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AllocationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AllocationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.AllocationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property AllocationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AllocationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.AllocationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allocationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit, zu der diese Compute-Knoten belegt wurde, an den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateReferences As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.CertificateReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Zertifikate auf dem Computeknoten installiert.
            </summary>
        <value>To be added.</value>
        <remarks>
            Für Serverknoten für Windows, installiert der Batch-Dienst die Zertifikate auf den angegebenen Zertifikatspeicher und den Speicherort an. Für Linux-Serverknoten werden die Zertifikate gespeichert, in einem Verzeichnis in das Arbeitsverzeichnis für die Aufgabe und eine Umgebung aus, die Variable AZ_BATCH_CERTIFICATES_DIR für den Task zum Abfragen von diesem Speicherort angegeben wird. Für Zertifikate mit der Sichtbarkeit der "RemoteUser" ein "Zertifikate"-Verzeichnis im Basisverzeichnis des Benutzers erstellt wird (z. B. /home/ {Benutzername} / Zertifikaten) und Zertifikate in diesem Verzeichnis abgelegt werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration EndpointConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration EndpointConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.EndpointConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointConfiguration As ComputeNodeEndpointConfiguration" />
      <MemberSignature Language="F#" Value="member this.EndpointConfiguration : Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.EndpointConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endpointConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Endpunktkonfiguration für die Serverknoten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; Errors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Errors" />
      <MemberSignature Language="VB.NET" Value="Public Property Errors As IList(Of ComputeNodeError)" />
      <MemberSignature Language="F#" Value="member this.Errors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Fehler, die derzeit von der Computeknoten auftreten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ID des Serverknotens fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Jeder Knoten, die einem Pool hinzugefügt werden, wird eine eindeutige ID zugewiesen.
            Wenn ein Knoten aus einem Pool entfernt wird, werden alle seine lokalen Dateien gelöscht, und die ID wieder zugänglich gemacht wird und für neue Knoten wiederverwendet werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddress">
      <MemberSignature Language="C#" Value="public string IpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.IpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property IpAddress As String" />
      <MemberSignature Language="F#" Value="member this.IpAddress : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.IpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die IP-Adresse, die andere Serverknoten verwenden können, für die Kommunikation mit diesem Computeknoten.
            </summary>
        <value>To be added.</value>
        <remarks>
            Jeder Knoten, der zu einem Pool hinzugefügt wird, wird eine eindeutige IP-Adresse zugewiesen.
            Wenn ein Knoten aus einem Pool entfernt wird, werden alle seine lokalen Dateien gelöscht, und die IP-Adresse wieder zugänglich gemacht wird und für neue Knoten wiederverwendet werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDedicated">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDedicated { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDedicated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.IsDedicated" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDedicated As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDedicated : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.IsDedicated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isDedicated")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob diese Computeknoten einen dedizierten Knoten ist. Wenn "false" ist der Knoten eines Knotens mit niedriger Priorität.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBootTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastBootTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastBootTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.LastBootTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastBootTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastBootTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.LastBootTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastBootTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit, an der die Serverknoten gestartet wurde.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft möglicherweise nicht vorhanden, wenn der Zustand des Knotens nicht verwendbar ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RecentTasks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; RecentTasks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; RecentTasks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.RecentTasks" />
      <MemberSignature Language="VB.NET" Value="Public Property RecentTasks As IList(Of TaskInformation)" />
      <MemberSignature Language="F#" Value="member this.RecentTasks : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.RecentTasks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recentTasks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Aufgaben, deren Status zuletzt geändert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft ist nur vorhanden, wenn mindestens eine Aufgabe auf diesem Knoten ausgeführt wurde, da er dem Pool zugewiesen wurde.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RunningTasksCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RunningTasksCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RunningTasksCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.RunningTasksCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RunningTasksCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RunningTasksCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.RunningTasksCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runningTasksCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Gesamtanzahl der aktuell ausgeführten Aufgaben auf den Computeknoten fest. Dies schließt die Auftrags-Manager-Aufgaben und normale Vorgänge jedoch Auftrag Vorbereitung Auftrag freigeben, oder Starten von Aufgaben nicht.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchedulingState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; SchedulingState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; SchedulingState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.SchedulingState" />
      <MemberSignature Language="VB.NET" Value="Public Property SchedulingState As Nullable(Of SchedulingState)" />
      <MemberSignature Language="F#" Value="member this.SchedulingState : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.SchedulingState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schedulingState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob der Computeknoten zum Planen von Task verfügbar ist.
            </summary>
        <value>To be added.</value>
        <remarks>
            Folgende Werte sind möglich: "enabled", "disabled"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.Protocol.Models.StartTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Task auf den Computeknoten ausgeführt wird, wie sie den Pool verknüpft.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTaskInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation StartTaskInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation StartTaskInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StartTaskInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTaskInfo As StartTaskInformation" />
      <MemberSignature Language="F#" Value="member this.StartTaskInfo : Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StartTaskInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTaskInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt Sie Laufzeitinformationen über die Ausführung des Tasks "Start" auf den Computeknoten fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As Nullable(Of ComputeNodeState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.State" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den aktuellen Zustand des Compute-Knoten.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Knoten mit niedriger Priorität wurde unterbrochen. Aufgaben, die auf den Knoten ausgeführt wurden, verhindert wurde werden neu geplant werden, wenn Sie einen anderen Knoten verfügbar ist. Folgende Werte sind möglich: "Leerlauf", "neu gestartet", "reimaging", "wird ausgeführt", "nicht verwendbar", "erstellen", "starten", "WaitingForStartTask", "StartTaskFailed", "unknown", "LeavingPool", "offline", "unterbrochen"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit, zu der die Serverknoten seinem aktuellen Status erlangt hat.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalTasksRun">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalTasksRun { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalTasksRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.TotalTasksRun" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalTasksRun As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalTasksRun : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.TotalTasksRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalTasksRun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Gesamtanzahl der Auftragsaufgaben auf den Computeknoten abgeschlossen. Dies schließt die Auftrags-Manager-Aufgaben und normale Vorgänge jedoch Auftrag Vorbereitung Auftrag freigeben, oder Starten von Aufgaben nicht.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalTasksSucceeded">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalTasksSucceeded { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalTasksSucceeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.TotalTasksSucceeded" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalTasksSucceeded As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalTasksSucceeded : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.TotalTasksSucceeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalTasksSucceeded")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Gesamtanzahl der Auftragsaufgaben die (mit ExitCode 0) wurde erfolgreich abgeschlossen auf dem Computeknoten. Dies schließt die Auftrags-Manager-Aufgaben und normale Vorgänge jedoch Auftrag Vorbereitung Auftrag freigeben, oder Starten von Aufgaben nicht.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die URL des Serverknotens fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="computeNode.Validate " />
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
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Größe des virtuellen Computers die Compute-Knoten gehostet.
            </summary>
        <value>To be added.</value>
        <remarks>
            Informationen zu den verfügbaren Größen von virtuellen Maschinen für Cloud-Dienste-Pools (Pools mit CloudServiceConfiguration erstellt) finden Sie unter Größen für Cloud-Dienste (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/).
            Batch unterstützt alle Cloud-Dienste-VM-Größen außer sind ExtraSmall, A1V2 und A2V2. Informationen zu den verfügbaren VM-Größen für Anwendungspools, die mithilfe von Images aus dem virtuellen Computer Marketplace (Pools mit VirtualMachineConfiguration erstellt) finden Sie unter Größen für virtuelle Maschinen (Linux) (https://azure.microsoft.com/documentation/articles/ virtuelle Maschinen-Linux-Größen /) oder Größen für virtuelle Computer (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/).
            Batch unterstützt alle Azure-VM-Größen außer STANDARD_A0 und die mit Premium-Speicher (STANDARD_GS STANDARD_DS und STANDARD_DSV2-Serie).
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>