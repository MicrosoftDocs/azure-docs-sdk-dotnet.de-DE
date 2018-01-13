<Type Name="Pool" FullName="Microsoft.Azure.Management.Batch.Models.Pool">
  <TypeSignature Language="C#" Value="public class Pool : Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Pool extends Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.Pool" />
  <TypeSignature Language="VB.NET" Value="Public Class Pool&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type Pool = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Batch.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Enthält Informationen zu einem Pool an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Pool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Pool.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse Pool an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Pool (string id = null, string name = null, string type = null, string etag = null, string displayName = null, Nullable&lt;DateTime&gt; lastModified = null, Nullable&lt;DateTime&gt; creationTime = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; provisioningState = null, Nullable&lt;DateTime&gt; provisioningStateTransitionTime = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt; allocationState = null, Nullable&lt;DateTime&gt; allocationStateTransitionTime = null, string vmSize = null, Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration deploymentConfiguration = null, Nullable&lt;int&gt; currentDedicatedNodes = null, Nullable&lt;int&gt; currentLowPriorityNodes = null, Microsoft.Azure.Management.Batch.Models.ScaleSettings scaleSettings = null, Microsoft.Azure.Management.Batch.Models.AutoScaleRun autoScaleRun = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; interNodeCommunication = null, Microsoft.Azure.Management.Batch.Models.NetworkConfiguration networkConfiguration = null, Nullable&lt;int&gt; maxTasksPerNode = null, Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy taskSchedulingPolicy = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt; userAccounts = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; metadata = null, Microsoft.Azure.Management.Batch.Models.StartTask startTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; certificates = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; applicationPackages = null, System.Collections.Generic.IList&lt;string&gt; applicationLicenses = null, Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus resizeOperationStatus = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string etag, string displayName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; provisioningStateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.AllocationState&gt; allocationState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; allocationStateTransitionTime, string vmSize, class Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration deploymentConfiguration, valuetype System.Nullable`1&lt;int32&gt; currentDedicatedNodes, valuetype System.Nullable`1&lt;int32&gt; currentLowPriorityNodes, class Microsoft.Azure.Management.Batch.Models.ScaleSettings scaleSettings, class Microsoft.Azure.Management.Batch.Models.AutoScaleRun autoScaleRun, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; interNodeCommunication, class Microsoft.Azure.Management.Batch.Models.NetworkConfiguration networkConfiguration, valuetype System.Nullable`1&lt;int32&gt; maxTasksPerNode, class Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy taskSchedulingPolicy, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.UserAccount&gt; userAccounts, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; metadata, class Microsoft.Azure.Management.Batch.Models.StartTask startTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; certificates, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; applicationPackages, class System.Collections.Generic.IList`1&lt;string&gt; applicationLicenses, class Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus resizeOperationStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Pool.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.Batch.Models.PoolProvisioningState},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.Batch.Models.AllocationState},System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.Azure.Management.Batch.Models.ScaleSettings,Microsoft.Azure.Management.Batch.Models.AutoScaleRun,System.Nullable{Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState},Microsoft.Azure.Management.Batch.Models.NetworkConfiguration,System.Nullable{System.Int32},Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.UserAccount},System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.MetadataItem},Microsoft.Azure.Management.Batch.Models.StartTask,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.CertificateReference},System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.Pool : string * string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt; * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Batch.Models.ScaleSettings * Microsoft.Azure.Management.Batch.Models.AutoScaleRun * Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; * Microsoft.Azure.Management.Batch.Models.NetworkConfiguration * Nullable&lt;int&gt; * Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; * Microsoft.Azure.Management.Batch.Models.StartTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus -&gt; Microsoft.Azure.Management.Batch.Models.Pool" Usage="new Microsoft.Azure.Management.Batch.Models.Pool (id, name, type, etag, displayName, lastModified, creationTime, provisioningState, provisioningStateTransitionTime, allocationState, allocationStateTransitionTime, vmSize, deploymentConfiguration, currentDedicatedNodes, currentLowPriorityNodes, scaleSettings, autoScaleRun, interNodeCommunication, networkConfiguration, maxTasksPerNode, taskSchedulingPolicy, userAccounts, metadata, startTask, certificates, applicationPackages, applicationLicenses, resizeOperationStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt;" />
        <Parameter Name="provisioningStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="allocationState" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt;" />
        <Parameter Name="allocationStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="deploymentConfiguration" Type="Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration" />
        <Parameter Name="currentDedicatedNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentLowPriorityNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="scaleSettings" Type="Microsoft.Azure.Management.Batch.Models.ScaleSettings" />
        <Parameter Name="autoScaleRun" Type="Microsoft.Azure.Management.Batch.Models.AutoScaleRun" />
        <Parameter Name="interNodeCommunication" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt;" />
        <Parameter Name="networkConfiguration" Type="Microsoft.Azure.Management.Batch.Models.NetworkConfiguration" />
        <Parameter Name="maxTasksPerNode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="taskSchedulingPolicy" Type="Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy" />
        <Parameter Name="userAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt;" />
        <Parameter Name="startTask" Type="Microsoft.Azure.Management.Batch.Models.StartTask" />
        <Parameter Name="certificates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt;" />
        <Parameter Name="applicationPackages" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="applicationLicenses" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="resizeOperationStatus" Type="Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus" />
      </Parameters>
      <Docs>
        <param name="id">Die ID der Ressource.</param>
        <param name="name">Der Name der Ressource.</param>
        <param name="type">Der Typ der Ressource.</param>
        <param name="etag">Das ETag der Ressource, für Parallelität-Anweisungen verwendet werden soll.</param>
        <param name="displayName">Der Anzeigename für den Pool.</param>
        <param name="lastModified">Uhrzeit des Pools wird von der letzten Änderung.</param>
        <param name="creationTime">Die Erstellungszeit des Pools.</param>
        <param name="provisioningState">Der aktuelle Status des Pools.</param>
        <param name="provisioningStateTransitionTime">Der Zeitpunkt, an dem der Pool seinem aktuellen Status erlangt hat.</param>
        <param name="allocationState">Gibt an, ob der Pool Größe ist.</param>
        <param name="allocationStateTransitionTime">Der Zeitpunkt, an dem der Pool seinen aktuellen Zuordnungsstatus erlangt hat.</param>
        <param name="vmSize">Die Größe der virtuellen Maschinen in den Pool. Alle virtuellen Computer in einem Pool haben die gleiche Größe.</param>
        <param name="deploymentConfiguration">Diese Eigenschaft beschreibt, wie die Pool-Knoten werden mit Cloud-Dienste oder virtuelle Computer - bereitgestellt.</param>
        <param name="currentDedicatedNodes">Die Anzahl der Serverknoten derzeit im Pool.</param>
        <param name="currentLowPriorityNodes">Die Anzahl der mit niedriger Priorität Serverknoten derzeit im Pool.</param>
        <param name="scaleSettings">Einstellungen, die die Anzahl der Knoten im Pool zu konfigurieren.</param>
        <param name="autoScaleRun">Die Ergebnisse und Fehler von der letzten Ausführung der Formel für automatische Skalierung.</param>
        <param name="interNodeCommunication">Gibt an, ob der Pool für direkte Kommunikation zwischen Knoten ermöglicht.</param>
        <param name="networkConfiguration">Die Netzwerkkonfiguration des Pools.</param>
        <param name="maxTasksPerNode">Die maximale Anzahl von Tasks, die gleichzeitig auf einem einzelnen Computeknoten im Pool ausgeführt werden können.</param>
        <param name="taskSchedulingPolicy">Wie Aufgaben auf Serverknoten in einem Pool verteilt werden.</param>
        <param name="userAccounts">Die Liste der Benutzerkonten auf jedem Knoten im Pool erstellt werden.</param>
        <param name="metadata">Eine Liste von Name / Wert-Paaren, die dem Pool als Metadaten zugeordnet.</param>
        <param name="startTask">Eine Aufgabe, die auf den einzelnen Computeknoten ausgeführt wird, wie den Pool hinzufügen.</param>
        <param name="certificates">Die Liste der Zertifikate auf jeder Serverknoten im Pool installiert werden.</param>
        <param name="applicationPackages">Die Liste der Anwendungspakete auf jeder Serverknoten im Pool installiert werden.</param>
        <param name="applicationLicenses">Die Liste der Anwendung Lizenz zur Nutzung der Batch-Dienst auf jeder Serverknoten im Pool verfügbar gemacht werden.</param>
        <param name="resizeOperationStatus">Enthält Details über die aktuellen oder letzten abgeschlossenen Größenänderung.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse Pool an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt; AllocationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.AllocationState&gt; AllocationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.AllocationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationState As Nullable(Of AllocationState)" />
      <MemberSignature Language="F#" Value="member this.AllocationState : Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.AllocationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allocationState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             Ruft ab, ob die Größe der Pool ändert.
             </summary>
        <value>To be added.</value>
        <remarks>
             Gültige Werte:
            
             Steady - ist der Pool nicht vergrößern/verkleinern. Es sind keine Änderungen auf die Anzahl der Knoten im Pool ausgeführt. Ein Pool geht in diesen Zustand, bei der Erstellung und keine Vorgänge für den Pool so ändern Sie die Anzahl der dedizierten Knoten ausgeführt werden.
             Ändern der Größe - Pool ist Größenänderung; d. h. berechnen Knoten werden hinzugefügt oder aus dem Pool entfernt.
             Beenden - Pool wurde ihre Größe ändern, aber der Benutzer hat angefordert, dass die Größenänderung beendet wird, aber die beendigungsanforderung wurde noch nicht abgeschlossen. Folgende Werte sind möglich: "Stetige", "Größe", "Beenden"
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AllocationStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AllocationStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.AllocationStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AllocationStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.AllocationStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allocationStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitpunkt, an dem der Pool seinen aktuellen Zuordnungsstatus erlangt hat.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLicenses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApplicationLicenses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApplicationLicenses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ApplicationLicenses" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationLicenses As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLicenses : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ApplicationLicenses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationLicenses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Anwendungslizenzen der Batch-Dienst auf jeder Serverknoten im Pool verfügbar gemacht werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die Liste der Anwendungslizenzen muss es sich um eine Teilmenge der verfügbaren Batch Dienstlizenzen Anwendung sein. Pool-Erstellung schlägt fehl, wenn eine Lizenz angefordert wird, die nicht unterstützt wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; ApplicationPackages { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; ApplicationPackages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ApplicationPackages" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackages As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackages : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ApplicationPackages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationPackages")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Anwendungspakete auf jeder Serverknoten im Pool installiert werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Änderungen an Anwendungspakete Auswirkungen auf alle neuen Serverknoten verknüpfen den Pool, aber wirken sich nicht auf die Serverknoten, die bereits im Pool befinden, bis er neu gestartet oder ein reimaging ausgeführt werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleRun">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.AutoScaleRun AutoScaleRun { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.AutoScaleRun AutoScaleRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.AutoScaleRun" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoScaleRun As AutoScaleRun" />
      <MemberSignature Language="F#" Value="member this.AutoScaleRun : Microsoft.Azure.Management.Batch.Models.AutoScaleRun" Usage="Microsoft.Azure.Management.Batch.Models.Pool.AutoScaleRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoScaleRun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.AutoScaleRun</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ergebnisse und Fehler aus der letzten Ausführung der Formel für automatische Skalierung ab.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird festgelegt, nur wenn der Pool automatisch skaliert, d. h. AutoScaleSettings verwendet werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; Certificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; Certificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.Certificates" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificates As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.Certificates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.Certificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.certificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Zertifikate auf jeder Serverknoten im Pool installiert werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Für Serverknoten für Windows, installiert der Batch-Dienst die Zertifikate auf den angegebenen Zertifikatspeicher und den Speicherort an. Für Linux-Serverknoten werden die Zertifikate gespeichert, in einem Verzeichnis in das Arbeitsverzeichnis für die Aufgabe und eine Umgebung aus, die Variable AZ_BATCH_CERTIFICATES_DIR für den Task zum Abfragen von diesem Speicherort angegeben wird. Für Zertifikate mit der Sichtbarkeit der "RemoteUser" ein "Zertifikate"-Verzeichnis im Basisverzeichnis des Benutzers erstellt wird (z. B. /home/ {Benutzername} / Zertifikaten) und Zertifikate in diesem Verzeichnis abgelegt werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Erstellungszeit des Pools an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentDedicatedNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentDedicatedNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentDedicatedNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.CurrentDedicatedNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentDedicatedNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentDedicatedNodes : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.CurrentDedicatedNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentDedicatedNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl von Serverknoten, die derzeit im Pool ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentLowPriorityNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentLowPriorityNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentLowPriorityNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.CurrentLowPriorityNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentLowPriorityNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentLowPriorityNodes : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.CurrentLowPriorityNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentLowPriorityNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der mit niedriger Priorität Serverknoten derzeit im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration DeploymentConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration DeploymentConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.DeploymentConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property DeploymentConfiguration As DeploymentConfiguration" />
      <MemberSignature Language="F#" Value="member this.DeploymentConfiguration : Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.DeploymentConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deploymentConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt diese Eigenschaft beschreibt, wie die Pool-Knoten bereitgestellt werden – mit Cloud-Dienste oder virtuelle Computer.
            </summary>
        <value>To be added.</value>
        <remarks>
            Mit CloudServiceConfiguration gibt an, dass die Knoten mithilfe einer Azure-Cloud-Dienste (PaaS), während VirtualMachineConfiguration Azure Virtual Machines (IaaS) verwendet erstellt werden soll.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Anzeigenamen für den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Anzeigename muss nicht eindeutig sein und darf keine Unicode-Zeichen bis zu einer maximalen Länge von 1024.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="InterNodeCommunication">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; InterNodeCommunication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; InterNodeCommunication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.InterNodeCommunication" />
      <MemberSignature Language="VB.NET" Value="Public Property InterNodeCommunication As Nullable(Of InterNodeCommunicationState)" />
      <MemberSignature Language="F#" Value="member this.InterNodeCommunication : Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.InterNodeCommunication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.interNodeCommunication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob der Pool direkten Kommunikation zwischen Knoten ermöglicht.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies schränkt ein, auf dem Knoten, die dem Pool zugewiesen werden können. Aktivieren diesen Wert reduzieren die Wahrscheinlichkeit für die angeforderte Anzahl von Knoten in den Pool zugeordnet werden soll. Wenn nicht angegeben, dieser Wert wird standardmäßig auf "Deaktiviert". Folgende Werte sind möglich: "Enabled", "Disabled"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitpunkt den letzten Änderung des Pools an.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies ist der letzten Ausführung bei der die Ebene Pool-Daten, z. B. die TargetDedicatedNodes oder AutoScaleSettings, geändert wurde. Es ist nicht auf Knotenebene Änderungen wie z. B. einem Serverknoten Ändern des Status berücksichtigen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTasksPerNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTasksPerNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTasksPerNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.MaxTasksPerNode" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTasksPerNode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTasksPerNode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.MaxTasksPerNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxTasksPerNode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl von Aufgaben, die gleichzeitig auf einem einzelnen Serverknoten im Pool ausgeführt werden können.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste von Name / Wert-Paaren, die dem Pool als Metadaten zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Batch-Dienst weist keine Bedeutung zu Metadaten; Es ist ausschließlich für die Verwendung von Benutzercode.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.NetworkConfiguration NetworkConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.NetworkConfiguration NetworkConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.NetworkConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkConfiguration As NetworkConfiguration" />
      <MemberSignature Language="F#" Value="member this.NetworkConfiguration : Microsoft.Azure.Management.Batch.Models.NetworkConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.NetworkConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.NetworkConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Netzwerkkonfiguration für den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of PoolProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             Ruft den aktuellen Status des Pools an.
             </summary>
        <value>To be added.</value>
        <remarks>
             Gültige Werte:
            
             Erfolgreich - ist Pool zum Ausführen von Aufgaben nach der Verfügbarkeit von Serverknoten verfügbar.
             wird gelöscht – der Benutzer hat angefordert, dass der Pool gelöscht werden, aber der Delete-Vorgang wurde noch nicht abgeschlossen. Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Löschen"
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ProvisioningStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ProvisioningStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ProvisioningStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ProvisioningStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitpunkt, an dem der Pool seinem aktuellen Status erlangt hat.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeOperationStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus ResizeOperationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus ResizeOperationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ResizeOperationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResizeOperationStatus As ResizeOperationStatus" />
      <MemberSignature Language="F#" Value="member this.ResizeOperationStatus : Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ResizeOperationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resizeOperationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft enthält Details zu den aktuellen oder letzten abgeschlossenen Resize-Vorgang.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScaleSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.ScaleSettings ScaleSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.ScaleSettings ScaleSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ScaleSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ScaleSettings As ScaleSettings" />
      <MemberSignature Language="F#" Value="member this.ScaleSettings : Microsoft.Azure.Management.Batch.Models.ScaleSettings with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ScaleSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scaleSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.ScaleSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen von Einstellungen, die die Anzahl der Knoten im Pool zu konfigurieren.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Management.Batch.Models.StartTask with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert ein Task auf jeder Compute-Knoten ausgeführt wird, wie den Pool hinzufügen.
            </summary>
        <value>To be added.</value>
        <remarks>
            In einem Patchvorgang (Update) kann diese Eigenschaft auf ein leeres Objekt festgelegt werden, die Startaufgabe aus dem Pool entfernen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskSchedulingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy TaskSchedulingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy TaskSchedulingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.TaskSchedulingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskSchedulingPolicy As TaskSchedulingPolicy" />
      <MemberSignature Language="F#" Value="member this.TaskSchedulingPolicy : Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.TaskSchedulingPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.taskSchedulingPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, wie Aufgaben auf Serverknoten in einem Pool verteilt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt; UserAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.UserAccount&gt; UserAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.UserAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccounts As IList(Of UserAccount)" />
      <MemberSignature Language="F#" Value="member this.UserAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.UserAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.userAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Benutzerkonten auf jedem Knoten im Pool erstellt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Pool.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="pool.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Größe der virtuellen Computer im Pool. Alle virtuellen Computer in einem Pool haben die gleiche Größe.
            </summary>
        <value>To be added.</value>
        <remarks>
            Informationen zu den verfügbaren Größen von virtuellen Maschinen für Cloud-Dienste-Pools (Pools mit CloudServiceConfiguration erstellt) finden Sie unter Größen für Cloud-Dienste (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/).
            Batch unterstützt alle Cloud-Dienste VM-Größen sind ExtraSmall mit Ausnahme von. Informationen zu den verfügbaren VM-Größen für Anwendungspools, die mithilfe von Images aus dem virtuellen Computer Marketplace (Pools mit VirtualMachineConfiguration erstellt) finden Sie unter Größen für virtuelle Maschinen (Linux) (https://azure.microsoft.com/documentation/articles/ virtuelle Maschinen-Linux-Größen /) oder Größen für virtuelle Computer (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/).
            Batch unterstützt alle Azure-VM-Größen außer STANDARD_A0 und die mit Premium-Speicher (STANDARD_GS STANDARD_DS und STANDARD_DSV2-Serie).
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>