<Type Name="JobPreparationTask" FullName="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask">
  <TypeSignature Language="C#" Value="public class JobPreparationTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPreparationTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPreparationTask" />
  <TypeSignature Language="F#" Value="type JobPreparationTask = class" />
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
            Ein Auftrag zur Vorbereitung Task ausführen, bevor alle Aufgaben des Auftrags auf einem gegebenen Knoten zu berechnen.
            </summary>
    <remarks>
            Auftrag zur Vorbereitung können Sie einen Serverknoten zum Ausführen von Aufgaben für den Auftrag vorbereiten. Auftrag zur Vorbereitung häufig ausgeführte Aktivitäten umfassen: Herunterladen von allgemeinen Ressourcendateien aller Aufgaben im Auftrag verwendet. Der Task Auftrag zur Vorbereitung kann diese allgemeine Ressourcendateien in den freigegebenen Speicherort auf den Computeknoten herunterladen. (AZ_BATCH_NODE_ROOT_DIR\shared), oder starten Sie einen lokalen Dienst auf den Serverknoten, damit alle Aufgaben dieses Auftrags mit ihm kommunizieren können. Wenn der Auftrag Vorbereitung task ein Fehler auftritt (d. h. der Wiederholungsversuche vor dem Beenden mit Exitcode 0 zählen seitliches), wird der Batch nicht Aufgaben des Auftrags auf den Computeknoten ausgeführt. Der Knoten bleibt zum Ausführen von Aufgaben des Auftrags, bis ein reimaging ausgeführt wird. Der Knoten aktiv bleibt und für andere Aufträge verwendet werden kann. Der Auftrag zur Vorbereitung-Task kann mehrere Male auf dem gleichen Computeknoten ausgeführt werden. Aus diesem Grund sollten Sie den Auftrag zur Vorbereitung-Task, um die erneute Ausführung behandeln schreiben. Wenn der Computeknoten neu gestartet wird, wird der Auftrag zur Vorbereitung Task erneut ausgeführt auf dem Knoten vor allen anderen Aufgaben des Auftrags, Planung, wenn RerunOnNodeRebootAfterSuccess auf "true" festgelegt ist oder wenn der Auftrag zur Vorbereitung Task zuvor nicht abgeschlossen wurde. Wenn der Computeknoten ein reimaging ausgeführt wird, wird der Auftrag zur Vorbereitung Task ausgeführt, erneut ausführen, bevor jede Aufgabe des Auftrags planen.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparationTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.#ctor" />
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
            Initialisiert eine neue Instanz der JobPreparationTask-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparationTask (string commandLine, string id = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings = null, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Nullable&lt;bool&gt; waitForSuccess = null, Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity = null, Nullable&lt;bool&gt; rerunOnNodeRebootAfterSuccess = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string commandLine, string id, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, valuetype System.Nullable`1&lt;bool&gt; waitForSuccess, class Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity, valuetype System.Nullable`1&lt;bool&gt; rerunOnNodeRebootAfterSuccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.#ctor(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.UserIdentity,System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.UserIdentity * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask (commandLine, id, containerSettings, resourceFiles, environmentSettings, constraints, waitForSuccess, userIdentity, rerunOnNodeRebootAfterSuccess)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="commandLine" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="containerSettings" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings" />
        <Parameter Name="resourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;" />
        <Parameter Name="environmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="waitForSuccess" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Batch.Protocol.Models.UserIdentity" />
        <Parameter Name="rerunOnNodeRebootAfterSuccess" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="commandLine">Die Befehlszeile des Tasks "Auftrag zur Vorbereitung".</param>
        <param name="id">Eine Zeichenfolge, die den Auftrag zur Vorbereitung Aufgabe im Auftrag eindeutig identifiziert.</param>
        <param name="containerSettings">Die Einstellungen für den Container unter dem der Auftrag zur Vorbereitung Task ausgeführt wird.</param>
        <param name="resourceFiles">Eine Liste der Dateien, die der Batch-Dienst vor dem Ausführen der Befehlszeile mit dem Computeknoten heruntergeladen wird.</param>
        <param name="environmentSettings">Eine Liste von umgebungsvariableneinstellungen für den Auftrag zur Vorbereitung-Task.</param>
        <param name="constraints">Einschränkungen, die für den Auftrag zur Vorbereitung Task gelten.</param>
        <param name="waitForSuccess">Gibt an, ob der Batch-Dienst für den Auftrag zur Vorbereitung Task erfolgreich abgeschlossen wird, vor dem Planen aller anderen Aufgaben des Auftrags auf dem Computeknoten warten soll. Ein Auftrag zur Vorbereitung Task wurde erfolgreich abgeschlossen, wenn er mit dem Exitcode 0 beendet wird.</param>
        <param name="userIdentity">Die Benutzeridentität, unter der der Auftrag zur Vorbereitung Task ausgeführt wird.</param>
        <param name="rerunOnNodeRebootAfterSuccess">Gibt an, ob der Batch-Dienst den Auftrag zur Vorbereitung Task solange erneut auszuführen sollte nach dem Neustart von eines Serverknotens.</param>
        <summary>
            Initialisiert eine neue Instanz der JobPreparationTask-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.CommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commandLine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert die Befehlszeile des Tasks "Auftrag zur Vorbereitung".
            </summary>
        <value>To be added.</value>
        <remarks>
            Die Befehlszeile wird nicht unter einer Shell ausgeführt, und daher kann nicht nutzen Shell-Funktionen, z. B. umgebungsvariablenerweiterung. Wenn Sie solche Funktionen nutzen möchten, Sie sollten rufen Sie die Befehlsshell in der Befehlszeile z. B. mit "Cmd/c MyCommand" in Windows oder "/ Bin/sh - C MyCommand" unter Linux.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As TaskConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.TaskConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="constraints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest, die für den Auftrag zur Vorbereitung Task gelten Einschränkungen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.ContainerSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Einstellungen für den Container unter dem der Auftrag zur Vorbereitung Task ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn dies angegeben wird, alle Verzeichnisse rekursiv unterhalb der AZ_BATCH_NODE_ROOT_DIR (der Stamm der Azure Batch-Verzeichnisse auf dem Knoten) in den Container zugeordnet sind, alle Umgebungsvariablen für die Aufgabe in den Container zugeordnet sind und die Befehlszeile der Aufgabe ist in den Container ausgeführt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.EnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="environmentSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste von umgebungsvariableneinstellungen für den Auftrag zur Vorbereitung-Task.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Id" />
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
            Ruft ab oder legt eine Zeichenfolge, die den Auftrag zur Vorbereitung Aufgabe im Auftrag eindeutig identifiziert.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die ID kann eine beliebige Kombination von alphanumerischen Zeichen, einschließlich der Bindestriche und Unterstriche enthalten und darf nicht mehr als 64 Zeichen enthalten. Wenn Sie diese Eigenschaft nicht angeben, weist der Batch-Dienst den Standardwert "Jobpreparation". Keine andere Aufgabe im Auftrag kann die gleiche ID wie der Auftrag zur Vorbereitung Task verfügen. Wenn Sie versuchen, eine Aufgabe mit der gleichen Id senden, lehnt Sie ab der Batch-Dienst den Fehlercode TaskIdSameAsJobPreparationTask; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 409 (Konflikt).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RerunOnNodeRebootAfterSuccess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RerunOnNodeRebootAfterSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RerunOnNodeRebootAfterSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.RerunOnNodeRebootAfterSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property RerunOnNodeRebootAfterSuccess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RerunOnNodeRebootAfterSuccess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.RerunOnNodeRebootAfterSuccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rerunOnNodeRebootAfterSuccess")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob der Batch-Dienst den Auftrag zur Vorbereitung Task solange erneut auszuführen sollte nach dem Neustart von eines Serverknotens.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Auftrag zur Vorbereitung Task immer erneut ausgeführt, wenn ein reimaging ein Compute-Knoten ausgeführt wird oder wenn die Auftrag zur Vorbereitung Aufgabe nicht abgeschlossen wurde (z. B. weil der Neustart ist aufgetreten, während die Aufgabe ausgeführt wurde). Aus diesem Grund sollten Sie immer einen Auftrag zur Vorbereitung Task Idempotent sein und ordnungsgemäß verhält, wenn mehrere Male ausführen schreiben. Der Standardwert lautet „true“.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.ResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Dateien, die der Batch-Dienst auf den Serverknoten herunterlädt, vor dem Ausführen der Befehlszeile.
            </summary>
        <value>To be added.</value>
        <remarks>
            Unter diesem Element aufgelisteten Dateien befinden sich im Arbeitsverzeichnis für den Task.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.Protocol.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.UserIdentity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userIdentity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.UserIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Identität des Benutzers, unter der der Auftrag zur Vorbereitung Task ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn nicht angegeben, der Task ausgeführt wird als eine eindeutige Benutzer ohne Administratorrechte für den Task auf Windows-Knoten oder ein Benutzer ohne Administratorrechte für den Pool auf Linux-Knoten eindeutig.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobPreparationTask.Validate " />
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
    <Member MemberName="WaitForSuccess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; WaitForSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; WaitForSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.WaitForSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitForSuccess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.WaitForSuccess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.WaitForSuccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="waitForSuccess")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob der Batch-Dienst für den Auftrag zur Vorbereitung Task erfolgreich abgeschlossen wird, vor dem Planen aller anderen Aufgaben des Auftrags auf dem Computeknoten warten soll. Ein Auftrag zur Vorbereitung Task wurde erfolgreich abgeschlossen, wenn er mit dem Exitcode 0 beendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn "true" und der Auftrag zur Vorbereitung Task ein Fehler auftritt, auf einen Serverknoten, wiederholt der Batch-Dienst den Auftrag zur Vorbereitung Aufgabe bis zu die maximale Anzahl von Wiederholungsversuchen (gemäß den Einschränkungen-Element). Wenn die Aufgabe noch nicht abgeschlossen wurde erfolgreich nachdem alle Wiederholungsversuche, und der Batch-Dienst wird nicht Planen von Aufgaben des Auftrags auf den Serverknoten. Die Serverknoten bleibt aktiv und auszuführenden Aufgaben von anderen Aufträgen geeignet. Wenn "false" wird der Batch-Dienst nicht für Auftrag Vorbereitung Abschluss der Aufgabe zu warten. In diesem Fall können andere Aufgaben des Auftrags starten auf dem Computeknoten ausgeführt werden, während die Auftrag zur Vorbereitung Aufgabe noch ausgeführt wird; und auch wenn der Auftrag zur Vorbereitung Task fehlschlägt, neue Aufgaben weiterhin auf dem Knoten geplant werden. Der Standardwert lautet „true“.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>