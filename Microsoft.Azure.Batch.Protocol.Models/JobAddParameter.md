<Type Name="JobAddParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter">
  <TypeSignature Language="C#" Value="public class JobAddParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobAddParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class JobAddParameter" />
  <TypeSignature Language="F#" Value="type JobAddParameter = class" />
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
            Ein hinzuzufügende Azure Batch-Auftrag.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobAddParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.#ctor" />
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
            Initialisiert eine neue Instanz der JobAddParameter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobAddParameter (string id, Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, string displayName = null, Nullable&lt;int&gt; priority = null, Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.JobManagerTask jobManagerTask = null, Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask jobPreparationTask = null, Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask jobReleaseTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; commonEnvironmentSettings = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; onTaskFailure = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null, Nullable&lt;bool&gt; usesTaskDependencies = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, string displayName, valuetype System.Nullable`1&lt;int32&gt; priority, class Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.JobManagerTask jobManagerTask, class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask jobPreparationTask, class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask jobReleaseTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; commonEnvironmentSettings, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; onTaskFailure, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata, valuetype System.Nullable`1&lt;bool&gt; usesTaskDependencies) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolInformation,System.String,System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.JobConstraints,Microsoft.Azure.Batch.Protocol.Models.JobManagerTask,Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask,Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem},System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobAddParameter : string * Microsoft.Azure.Batch.Protocol.Models.PoolInformation * string * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.JobConstraints * Microsoft.Azure.Batch.Protocol.Models.JobManagerTask * Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask * Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobAddParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobAddParameter (id, poolInfo, displayName, priority, constraints, jobManagerTask, jobPreparationTask, jobReleaseTask, commonEnvironmentSettings, onAllTasksComplete, onTaskFailure, metadata, usesTaskDependencies)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="poolInfo" Type="Microsoft.Azure.Batch.Protocol.Models.PoolInformation" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.JobConstraints" />
        <Parameter Name="jobManagerTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask" />
        <Parameter Name="jobPreparationTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask" />
        <Parameter Name="jobReleaseTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask" />
        <Parameter Name="commonEnvironmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="onAllTasksComplete" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;" />
        <Parameter Name="onTaskFailure" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
        <Parameter Name="usesTaskDependencies" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id">Eine Zeichenfolge, die den Auftrag im Konto eindeutig identifiziert.</param>
        <param name="poolInfo">Der Pool, auf dem der Batch-Dienst den Auftrag Aufgaben ausgeführt wird.</param>
        <param name="displayName">Der Anzeigename für den Auftrag.</param>
        <param name="priority">Die Priorität des Auftrags.</param>
        <param name="constraints">Die ausführungseinschränkungen für den Auftrag.</param>
        <param name="jobManagerTask">Die Details einer Auftrags-Manager-Aufgabe gestartet werden, wenn der Auftrag gestartet wird.</param>
        <param name="jobPreparationTask">Der Auftrag zur Vorbereitung-Task.</param>
        <param name="jobReleaseTask">Der Task Auftrag freigeben.</param>
        <param name="commonEnvironmentSettings">Die Liste der allgemeinen umgebungsvariableneinstellungen. Diese Umgebungsvariablen sind für alle Aufgaben im Auftrag (einschließlich der Auftrags-Manager "," Auftrag zur Vorbereitung "und" Auftrag Version Aufgaben) festgelegt.</param>
        <param name="onAllTasksComplete">Sollte der Batch-Dienst Maßnahmen, wenn alle Aufgaben im Auftrag in den Zustand abgeschlossen sind.</param>
        <param name="onTaskFailure">Sollte der Batch-Dienst Maßnahmen, wenn jede Aufgabe im Auftrag ein Fehler auftritt.</param>
        <param name="metadata">Eine Liste von Name / Wert-Paaren, die dem Auftrag als Metadaten zugeordnet.</param>
        <param name="usesTaskDependencies">Gibt an, ob Aufgaben im Auftrag Abhängigkeiten untereinander definieren können. Der Standardwert ist false.</param>
        <summary>
            Initialisiert eine neue Instanz der JobAddParameter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonEnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; CommonEnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; CommonEnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.CommonEnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonEnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.CommonEnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.CommonEnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commonEnvironmentSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der allgemeinen umgebungsvariableneinstellungen.
            Diese Umgebungsvariablen sind für alle Aufgaben im Auftrag (einschließlich der Auftrags-Manager "," Auftrag zur Vorbereitung "und" Auftrag Version Aufgaben) festgelegt.
            </summary>
        <value>To be added.</value>
        <remarks>
            Einzelne Vorgänge können eine umgebungseinstellung, die hier angegebene durch Angabe der gleiche Name der Einstellung mit einem anderen Wert überschreiben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.JobConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Constraints" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ausführungseinschränkungen für den Auftrag.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Anzeigenamen für den Auftrag.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Anzeigename muss nicht eindeutig sein und darf keine Unicode-Zeichen bis zu einer maximalen Länge von 1024.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Id" />
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
            Ruft ab oder legt eine Zeichenfolge, die den Auftrag im Konto eindeutig identifiziert.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die ID kann eine beliebige Kombination von alphanumerischen Zeichen, einschließlich der Bindestriche und Unterstriche enthalten und darf nicht mehr als 64 Zeichen enthalten. Die ID ist unter Beibehaltung von Groß-/Kleinschreibung und Groß-/Kleinschreibung (d. h., Sie verfügen nicht zwei IDs innerhalb eines Kontos, die sich nur in Groß-bzw. Kleinschreibung unterscheiden).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobManagerTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobManagerTask JobManagerTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobManagerTask JobManagerTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobManagerTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobManagerTask As JobManagerTask" />
      <MemberSignature Language="F#" Value="member this.JobManagerTask : Microsoft.Azure.Batch.Protocol.Models.JobManagerTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobManagerTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobManagerTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobManagerTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Details einer Auftrags-Manager-Aufgabe gestartet werden, wenn der Auftrag gestartet wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn der Auftrag nicht mit eine Auftrags-Manager-Aufgabe angegeben wird, muss der Benutzer Aufgaben explizit den Auftrag hinzufügen. Wenn der Auftrag eine Aufgabe des Auftrags-Manager angegeben ist, erstellt der Batch-Dienst die Auftrags-Manager-Aufgabe aus, wenn der Auftrag wird erstellt, und es versucht wird, den Auftrags-Manager-Task zu planen, bevor die Planung von anderen Aufgaben im Auftrag. Typische dient zum Steuerelement und/oder Monitor auftragsausführung, z. B. durch entscheiden, welche zusätzlichen Aufgaben ausführen, die bestimmen, wann die Arbeit abgeschlossen ist. "" usw. die Auftrags-Manager-Aufgabe. (Allerdings eine Auftrags-Manager-Aufgabe wird nicht darauf beschränkt, auf diese Aktivitäten – es ist eine fully-fledged Aufgabe im System, und führen Sie die Aktionen für den Auftrag erforderlich sind.) Z. B. kann eine Auftrags-Manager-Aufgabe Downloaden einer Datei, die als Parameter angegeben, analysieren den Inhalt dieser Datei und übermitteln zusätzliche Aufgaben basierend auf diesen Inhalt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparationTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask JobPreparationTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask JobPreparationTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobPreparationTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparationTask As JobPreparationTask" />
      <MemberSignature Language="F#" Value="member this.JobPreparationTask : Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobPreparationTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobPreparationTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Übernimmt oder bestimmt die Vorbereitung des Auftrags-Aufgabe.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn ein Auftrag eine Auftrag zur Vorbereitung-Aufgabe verfügt, wird der Batch-Dienst den Auftrag zur Vorbereitung Task vor dem Starten alle Aufgaben dieses Auftrags auf diesem Computeknoten auf einem Serverknoten ausgeführt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobReleaseTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask JobReleaseTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask JobReleaseTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobReleaseTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobReleaseTask As JobReleaseTask" />
      <MemberSignature Language="F#" Value="member this.JobReleaseTask : Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobReleaseTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobReleaseTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Version des Auftrags fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Eine Aufgabe Auftrag Version kann nicht angegeben werden, ohne dass auch eine Aufgabe Auftrag zur Vorbereitung für den Auftrag. Der Batch-Dienst führt den Auftrag Release-Task auf den Serverknoten, die die Auftrag zur Vorbereitung Aufgabe ausgeführt haben. Die Hauptaufgabe des Tasks "Auftrag Release" ist zum Rückgängigmachen von Änderungen zur Berechnung von Knoten, die von der Aufgabe des Auftrags Vorbereitung vorgenommen. Beispiel-Aktivitäten sind lokale Dateien löschen oder Herunterfahren von Diensten, die im Rahmen der Vorbereitung der Auftrag gestartet wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste von Name / Wert-Paaren, die dem Auftrag als Metadaten zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Batch-Dienst weist keine Bedeutung zu Metadaten; Es ist ausschließlich für die Verwendung von Benutzercode.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAllTasksComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.OnAllTasksComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property OnAllTasksComplete As Nullable(Of OnAllTasksComplete)" />
      <MemberSignature Language="F#" Value="member this.OnAllTasksComplete : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.OnAllTasksComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="onAllTasksComplete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die Aktion der Batch-Dienst ausgeführt werden sollen, wenn alle Aufgaben im Auftrag in den Zustand abgeschlossen sind.
            </summary>
        <value>To be added.</value>
        <remarks>
            Beachten Sie, dass wenn ein Auftrag keine Aufgaben enthält, klicken Sie dann alle Vorgänge als abgeschlossen betrachtet werden. Diese Option verwendet wird daher am häufigsten mit eine Auftrags-Manager-Aufgabe. Wenn Sie automatische Auftrag beenden, ohne eine Auftrags-Manager verwenden möchten, sollte zunächst OnAllTasksComplete "NoAction" festgelegt und Auftragseigenschaften TerminateJob OnAllTasksComplete festlegen, wenn Sie fertig sind, Hinzufügen von Tasks zu aktualisieren. Der Standardwert ist "NoAction". Folgende Werte sind möglich: 'NoAction', 'TerminateJob'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTaskFailure">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; OnTaskFailure { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; OnTaskFailure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.OnTaskFailure" />
      <MemberSignature Language="VB.NET" Value="Public Property OnTaskFailure As Nullable(Of OnTaskFailure)" />
      <MemberSignature Language="F#" Value="member this.OnTaskFailure : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.OnTaskFailure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="onTaskFailure")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die Aktion, die der Batch-Dienst ausführen sollten, wenn jede Aufgabe im Auftrag ein Fehler auftritt.
            </summary>
        <value>To be added.</value>
        <remarks>
            Eine Aufgabe wird als mit fehlerhaften If hat eine FailureInfo. Ein FailureInfo wird festgelegt, wenn die Aufgabe mit einem Exitcode ungleich 0 (null) abgeschlossen ist, nachdem die Wiederholungsanzahl für schwellenwertbenachrichtigungen oder wenn Fehler beim Starten der Aufgabe aufgetreten ist, z. B. aufgrund einer Ressourcendatei herunterladen Fehler. Der Standardwert ist "NoAction". Folgende Werte sind möglich: 'NoAction', 'PerformExitOptionsJobAction'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.PoolInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolInfo As PoolInformation" />
      <MemberSignature Language="F#" Value="member this.PoolInfo : Microsoft.Azure.Batch.Protocol.Models.PoolInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.PoolInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Pool, auf dem der Batch-Dienst den Auftrag Aufgaben ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Priorität des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>
            Priority-Werte reichen von-1000 bis 1000,-1000 wird die niedrigste Priorität und 1000 die höchste Priorität. Der Standardwert ist 0.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UsesTaskDependencies">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsesTaskDependencies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsesTaskDependencies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.UsesTaskDependencies" />
      <MemberSignature Language="VB.NET" Value="Public Property UsesTaskDependencies As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsesTaskDependencies : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.UsesTaskDependencies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="usesTaskDependencies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob die Aufgaben im Auftrag Abhängigkeiten untereinander definieren können. Der Standardwert ist false.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobAddParameter.Validate " />
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