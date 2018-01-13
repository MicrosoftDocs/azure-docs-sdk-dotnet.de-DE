<Type Name="JobManagerTask" FullName="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask">
  <TypeSignature Language="C#" Value="public class JobManagerTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobManagerTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask" />
  <TypeSignature Language="VB.NET" Value="Public Class JobManagerTask" />
  <TypeSignature Language="F#" Value="type JobManagerTask = class" />
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
            Gibt Details einer Auftrags-Manager-Aufgabe an.
            </summary>
    <remarks>
            Die Auftrags-Manager-Aufgabe wird automatisch gestartet, wenn der Auftrag erstellt wird.
            Der Batch-Dienst versucht, die Auftrags-Manager-Aufgabe vor alle anderen Aufgaben im Auftrag zu planen. Wenn ein Pool verkleinert wird, versucht der Batch-Dienst Serverknoten beizubehalten, Auftrags-Manager-Aufgaben ausgeführt werden, so lange als möglich (d. h. Knoten ausgeführten 'normale' Aufgaben vor dem Knoten ausgeführten Auftrags-Manager-Tasks entfernt werden). Wenn eine Auftrags-Manager-Aufgabe fehlschlägt und neu gestartet werden muss, versucht das System mit der höchsten Priorität zu planen. Wenn keine im Leerlauf Knoten vorhanden sind, kann das System Beenden eines aktiven Aufgaben im Pool und an die Warteschlange zurückgegeben werden, um Platz für die Auftrags-Manager-Aufgabe, neu zu starten. Beachten Sie, dass eine Auftrags-Manager-Aufgabe in einem Auftrag keine Priorität über Aufgaben in anderen Aufträgen verfügt. Über Aufträge hinweg werden nur Prioritäten auf Auftragsebene berücksichtigt. Z. B. wenn ein Auftrags-Manager in einem Auftrag Priorität 0 neu gestartet werden muss, wird es nicht Aufgaben eines Auftrags Priorität 1 versetzen.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobManagerTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.#ctor" />
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
            Initialisiert eine neue Instanz der JobManagerTask-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobManagerTask (string id, string commandLine, string displayName = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; outputFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings = null, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Nullable&lt;bool&gt; killJobOnCompletion = null, Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity = null, Nullable&lt;bool&gt; runExclusive = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences = null, Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings authenticationTokenSettings = null, Nullable&lt;bool&gt; allowLowPriorityNode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string commandLine, string displayName, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; outputFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, valuetype System.Nullable`1&lt;bool&gt; killJobOnCompletion, class Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity, valuetype System.Nullable`1&lt;bool&gt; runExclusive, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences, class Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings authenticationTokenSettings, valuetype System.Nullable`1&lt;bool&gt; allowLowPriorityNode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.#ctor(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.OutputFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.UserIdentity,System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference},Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings,System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobManagerTask : string * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.UserIdentity * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; * Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobManagerTask" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobManagerTask (id, commandLine, displayName, containerSettings, resourceFiles, outputFiles, environmentSettings, constraints, killJobOnCompletion, userIdentity, runExclusive, applicationPackageReferences, authenticationTokenSettings, allowLowPriorityNode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="commandLine" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="containerSettings" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings" />
        <Parameter Name="resourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;" />
        <Parameter Name="outputFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt;" />
        <Parameter Name="environmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="killJobOnCompletion" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Batch.Protocol.Models.UserIdentity" />
        <Parameter Name="runExclusive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="applicationPackageReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="authenticationTokenSettings" Type="Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings" />
        <Parameter Name="allowLowPriorityNode" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id">Eine Zeichenfolge, die die Auftrags-Manager-Aufgabe im Auftrag eindeutig identifiziert.</param>
        <param name="commandLine">Die Befehlszeile der Auftrags-Manager-Aufgabe.</param>
        <param name="displayName">Der Anzeigename der Auftrags-Manager-Aufgabe.</param>
        <param name="containerSettings">Die Einstellungen für den Container unter dem die Auftrags-Manager-Aufgabe ausgeführt wird.</param>
        <param name="resourceFiles">Eine Liste der Dateien, die der Batch-Dienst vor dem Ausführen der Befehlszeile mit dem Computeknoten heruntergeladen wird.</param>
        <param name="outputFiles">Eine Liste der Dateien, die der Batch-Dienst nach dem Ausführen der Befehlszeile aus dem Computeknoten hochladen.</param>
        <param name="environmentSettings">Eine Liste von umgebungsvariableneinstellungen für die Auftrags-Manager-Aufgabe.</param>
        <param name="constraints">Einschränkungen, die für die Auftrags-Manager-Aufgabe gelten.</param>
        <param name="killJobOnCompletion">Gibt an, ob der Auftrags-Manager-Task abgeschlossen Abschluss des gesamten Auftrags gibt.</param>
        <param name="userIdentity">Die Benutzeridentität, unter der die Auftrags-Manager-Aufgabe ausgeführt wird.</param>
        <param name="runExclusive">Gibt an, ob der Auftrags-Manager-Task exklusive Verwendung des Serverknotens erfordert, in dem er ausgeführt wird.</param>
        <param name="applicationPackageReferences">Eine Liste der Anwendungspakete, die der Batch-Dienst vor dem Ausführen der Befehlszeile auf den Serverknoten bereitstellen.</param>
        <param name="authenticationTokenSettings">Die Einstellungen für ein Authentifizierungstoken, die die Aufgabe zum Ausführen von Batchvorgängen-Dienst verwenden können.</param>
        <param name="allowLowPriorityNode">Gibt an, ob die Auftrags-Manager-Aufgabe auf einem Serverknoten mit niedriger Priorität führen kann.</param>
        <summary>
            Initialisiert eine neue Instanz der JobManagerTask-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowLowPriorityNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AllowLowPriorityNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AllowLowPriorityNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.AllowLowPriorityNode" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowLowPriorityNode As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AllowLowPriorityNode : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.AllowLowPriorityNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allowLowPriorityNode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, ob der Auftrags-Manager-Vorgang auf einem Serverknoten mit niedriger Priorität ausgeführt werden kann.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert ist „false“.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ApplicationPackageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationPackageReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Anwendungspakete, die der Batch-Dienst vor dem Ausführen der Befehlszeile auf den Serverknoten bereitstellen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Anwendungspakete heruntergeladen und in ein freigegebenes Verzeichnis, nicht die Arbeitsverzeichnis Aufgabe bereitgestellt. Aus diesem Grund, wenn ein Referenziertes Paket befindet sich bereits auf dem Computeknoten und auf dem neuesten Stand ist, wird dann sie nicht erneut heruntergeladen; die vorhandene Kopie auf dem Computeknoten verwendet wird. Wenn ein Paket verwiesen wird, z. B. installiert werden kann, da das Paket gelöscht wurde oder weil Fehler beim Herunterladen der Task fehlschlägt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationTokenSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings AuthenticationTokenSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings AuthenticationTokenSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.AuthenticationTokenSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationTokenSettings As AuthenticationTokenSettings" />
      <MemberSignature Language="F#" Value="member this.AuthenticationTokenSettings : Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.AuthenticationTokenSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authenticationTokenSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Einstellungen für ein Authentifizierungstoken, die die Aufgabe zum Ausführen von Batchvorgängen-Dienst verwenden können.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn diese Eigenschaft festgelegt ist, enthält der Batch-Dienst die Aufgabe mit der ein Authentifizierungstoken der Batch-Dienstvorgänge zu authentifizieren, ohne einen Zugriffsschlüssel verwendet werden kann. Das Token wird über die Umgebungsvariable AZ_BATCH_AUTHENTICATION_TOKEN bereitgestellt. Die Vorgänge, die mit dem Token die Aufgabe ausführen kann, hängen von den Einstellungen ab. Ein Task kann z. B. Auftrag verfügen, um andere Aufgaben hinzufügen, um den Auftrag, oder Überprüfen Sie den Status des Auftrags oder von anderen Aufgaben unter dem Auftrag anfordern.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.CommandLine" />
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
            Ruft ab oder legt die Befehlszeile der Auftrags-Manager-Aufgabe.
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As TaskConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.TaskConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.Constraints" />
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
            Ruft ab, oder legt ihn fest, die für die Auftrags-Manager-Aufgabe gelten Einschränkungen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ContainerSettings" />
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
            Ruft ab oder legt die Einstellungen für den Container unter dem die Auftrags-Manager-Aufgabe ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn Pools, den diese Aufgabe ausgeführt wird ContainerConfiguration festgelegt hat, muss diese ebenfalls festgelegt werden. Wenn der Pool, der diese Aufgabe ausgeführt wird keine ContainerConfiguration festgelegt hat, muss dies nicht festgelegt werden. Wenn dies angegeben wird, alle Verzeichnisse rekursiv unterhalb der AZ_BATCH_NODE_ROOT_DIR (der Stamm der Azure Batch-Verzeichnisse auf dem Knoten) in den Container zugeordnet sind, alle Umgebungsvariablen für die Aufgabe in den Container zugeordnet sind und die Befehlszeile der Aufgabe ist in den Container ausgeführt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.DisplayName" />
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
            Ruft ab oder legt den Anzeigenamen des Tasks "Auftrags-Manager".
            </summary>
        <value>To be added.</value>
        <remarks>
            Sie müssen nicht eindeutig sein und darf keine Unicode-Zeichen bis zu einer maximalen Länge von 1024.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.EnvironmentSettings" />
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
            Ruft ab oder legt eine Liste von umgebungsvariableneinstellungen für die Auftrags-Manager-Aufgabe.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.Id" />
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
            Ruft ab oder legt eine Zeichenfolge, die die Auftrags-Manager-Aufgabe im Auftrag eindeutig identifiziert.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die ID kann eine beliebige Kombination von alphanumerischen Zeichen, einschließlich der Bindestriche und Unterstriche enthalten und darf nicht mehr als 64 Zeichen enthalten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="KillJobOnCompletion">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; KillJobOnCompletion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; KillJobOnCompletion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.KillJobOnCompletion" />
      <MemberSignature Language="VB.NET" Value="Public Property KillJobOnCompletion As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.KillJobOnCompletion : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.KillJobOnCompletion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="killJobOnCompletion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob es sich bei Abschluss der Aufgabe Auftrags-Manager gibt Abschluss des gesamten Auftrags an.
            </summary>
        <value>To be added.</value>
        <remarks>
            Bei "true", wenn die Auftrags-Manager-Aufgabe abgeschlossen ist, der Batch-Dienst markiert den Auftrag als abzuschließen. Wenn alle Aufgaben noch zu diesem Zeitpunkt (mit Ausnahme des Auftrags Version) ausgeführt werden, werden diese Aufgaben beendet. Wenn "false" beeinflusst der Abschluss des Auftrags-Manager-Tasks nicht der Status des Auftrags. In diesem Fall sollte entweder mithilfe des Attributs OnAllTasksComplete den Auftrag beenden oder haben von einem Client oder Benutzer, die den Auftrag explizit beenden. Ein Beispiel hierfür ist, wenn die Auftrags-Manager einen Satz von Aufgaben erstellt jedoch dann keine weiteren Rolle in ihrer Ausführung übernimmt. Der Standardwert lautet „true“. Wenn Sie die Attribute OnAllTasksComplete und OnTaskFailure Steuerelement Auftrag Lebensdauer und mit der Auftrags-Manager-Task nur zum Erstellen von Aufgaben für den Auftrag (nicht zu überwachen) verwenden, ist es wichtig, KillJobOnCompletion auf "false" festgelegt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; OutputFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; OutputFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.OutputFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputFiles As IList(Of OutputFile)" />
      <MemberSignature Language="F#" Value="member this.OutputFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.OutputFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Dateien, die der Batch-Dienst nach dem Ausführen der Befehlszeile aus dem Computeknoten hochladen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Für Vorgänge mit mehreren Instanzen werden die Dateien nur aus dem Computeknoten hochgeladen werden auf denen die primäre Aufgabe ausgeführt wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ResourceFiles" />
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
    <Member MemberName="RunExclusive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RunExclusive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RunExclusive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.RunExclusive" />
      <MemberSignature Language="VB.NET" Value="Public Property RunExclusive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RunExclusive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.RunExclusive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runExclusive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob die Auftrags-Manager-Aufgabe erfordert die exklusive Verwendung des Serverknotens, wo es ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Bei "true", werden auf dem gleichen Computeknoten für keine anderen Aufgaben ausgeführt, solange der Auftrags-Manager ausgeführt wird. Wenn "false", können andere Tasks gleichzeitig mit der Auftrags-Manager auf einem Serverknoten ausführen. Die Auftrags-Manager-Aufgabe zählt normalerweise anhand des Knotens gleichzeitige Taskgrenze, damit dies nur relevant ist, wenn der Knoten mehrere gleichzeitige Aufgaben ermöglicht. Der Standardwert lautet „true“.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.Protocol.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.UserIdentity" />
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
            Ruft ab oder legt die Identität des Benutzers, unter der die Auftrags-Manager-Aufgabe ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn nicht angegeben, der Task als Nichtadministrator-eindeutige Benutzer an die Aufgabe ausgeführt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobManagerTask.Validate " />
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