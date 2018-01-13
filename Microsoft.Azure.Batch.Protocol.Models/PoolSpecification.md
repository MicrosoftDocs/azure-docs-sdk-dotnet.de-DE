<Type Name="PoolSpecification" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification">
  <TypeSignature Language="C#" Value="public class PoolSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolSpecification" />
  <TypeSignature Language="F#" Value="type PoolSpecification = class" />
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
            Spezifikation für einen neuen Pool erstellen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.#ctor" />
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
            Initialisiert eine neue Instanz der PoolSpecification-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolSpecification (string vmSize, string displayName = null, Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration cloudServiceConfiguration = null, Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration virtualMachineConfiguration = null, Nullable&lt;int&gt; maxTasksPerNode = null, Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy taskSchedulingPolicy = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;int&gt; targetDedicatedNodes = null, Nullable&lt;int&gt; targetLowPriorityNodes = null, Nullable&lt;bool&gt; enableAutoScale = null, string autoScaleFormula = null, Nullable&lt;TimeSpan&gt; autoScaleEvaluationInterval = null, Nullable&lt;bool&gt; enableInterNodeCommunication = null, Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration networkConfiguration = null, Microsoft.Azure.Batch.Protocol.Models.StartTask startTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences = null, System.Collections.Generic.IList&lt;string&gt; applicationLicenses = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; userAccounts = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vmSize, string displayName, class Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration cloudServiceConfiguration, class Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration virtualMachineConfiguration, valuetype System.Nullable`1&lt;int32&gt; maxTasksPerNode, class Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy taskSchedulingPolicy, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityNodes, valuetype System.Nullable`1&lt;bool&gt; enableAutoScale, string autoScaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoScaleEvaluationInterval, valuetype System.Nullable`1&lt;bool&gt; enableInterNodeCommunication, class Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration networkConfiguration, class Microsoft.Azure.Batch.Protocol.Models.StartTask startTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences, class System.Collections.Generic.IList`1&lt;string&gt; applicationLicenses, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; userAccounts, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.#ctor(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration,Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration,System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy,System.Nullable{System.TimeSpan},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.String,System.Nullable{System.TimeSpan},System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration,Microsoft.Azure.Batch.Protocol.Models.StartTask,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.CertificateReference},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.UserAccount},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolSpecification : string * string * Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration * Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;TimeSpan&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration * Microsoft.Azure.Batch.Protocol.Models.StartTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolSpecification" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolSpecification (vmSize, displayName, cloudServiceConfiguration, virtualMachineConfiguration, maxTasksPerNode, taskSchedulingPolicy, resizeTimeout, targetDedicatedNodes, targetLowPriorityNodes, enableAutoScale, autoScaleFormula, autoScaleEvaluationInterval, enableInterNodeCommunication, networkConfiguration, startTask, certificateReferences, applicationPackageReferences, applicationLicenses, userAccounts, metadata)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="cloudServiceConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration" />
        <Parameter Name="virtualMachineConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration" />
        <Parameter Name="maxTasksPerNode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="taskSchedulingPolicy" Type="Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="targetDedicatedNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="enableAutoScale" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="autoScaleFormula" Type="System.String" />
        <Parameter Name="autoScaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enableInterNodeCommunication" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="networkConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration" />
        <Parameter Name="startTask" Type="Microsoft.Azure.Batch.Protocol.Models.StartTask" />
        <Parameter Name="certificateReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;" />
        <Parameter Name="applicationPackageReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="applicationLicenses" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="userAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
      </Parameters>
      <Docs>
        <param name="vmSize">Die Größe der virtuellen Computer im Pool.
            Alle virtuellen Computer in einem Pool haben die gleiche Größe.</param>
        <param name="displayName">Der Anzeigename für den Pool.</param>
        <param name="cloudServiceConfiguration">Die Clouddienstkonfiguration des Pools.</param>
        <param name="virtualMachineConfiguration">Die VM-Konfiguration des Pools.</param>
        <param name="maxTasksPerNode">Die maximale Anzahl von Tasks, die gleichzeitig auf einem einzelnen Computeknoten im Pool ausgeführt werden können.</param>
        <param name="taskSchedulingPolicy">Wie Aufgaben auf Serverknoten in einem Pool verteilt werden.</param>
        <param name="resizeTimeout">Das Timeout für die Zuweisung von Serverknoten in den Pool.</param>
        <param name="targetDedicatedNodes">Die gewünschte Anzahl von dedizierten Serverknoten im Pool.</param>
        <param name="targetLowPriorityNodes">Die gewünschte Anzahl von mit niedriger Priorität Serverknoten im Pool.</param>
        <param name="enableAutoScale">Gibt an, ob die Poolgröße automatisch mit der Zeit angepasst.</param>
        <param name="autoScaleFormula">Die Formel für die gewünschte Anzahl von Serverknoten im Pool.</param>
        <param name="autoScaleEvaluationInterval">Das Zeitintervall, an dem die Poolgröße gemäß Formel für automatische Skalierung automatisch angepasst werden soll.</param>
        <param name="enableInterNodeCommunication">Gibt an, ob der Pool für direkte Kommunikation zwischen Knoten ermöglicht.</param>
        <param name="networkConfiguration">Die Netzwerkkonfiguration des Pools.</param>
        <param name="startTask">Eine Aufgabe, die auf jedem Computeknoten ausgeführt wird, wie sie den Pool verknüpft werden soll. Der Task ausgeführt wird, wenn der Knoten hinzugefügt wird, an den Pool oder der Knoten neu gestartet wird.</param>
        <param name="certificateReferences">Eine Liste der Zertifikate auf jeder Serverknoten im Pool installiert werden.</param>
        <param name="applicationPackageReferences">Die Liste der Anwendungspakete auf jeder Serverknoten im Pool installiert werden.</param>
        <param name="applicationLicenses">Die Liste der Anwendung Lizenz zur Nutzung der Batch-Dienst auf jeder Serverknoten im Pool verfügbar gemacht werden.</param>
        <param name="userAccounts">Die Liste der Benutzerkonten auf jedem Knoten im Pool erstellt werden.</param>
        <param name="metadata">Eine Liste von Name / Wert-Paaren, die dem Pool als Metadaten zugeordnet.</param>
        <summary>
            Initialisiert eine neue Instanz der PoolSpecification-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLicenses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApplicationLicenses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApplicationLicenses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.ApplicationLicenses" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationLicenses As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLicenses : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.ApplicationLicenses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationLicenses")</AttributeName>
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
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.ApplicationPackageReferences" />
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
            Ruft ab oder legt die Liste der Anwendungspakete auf jeder Serverknoten im Pool installiert werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEvaluationInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoScaleEvaluationInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoScaleEvaluationInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.AutoScaleEvaluationInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEvaluationInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEvaluationInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.AutoScaleEvaluationInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScaleEvaluationInterval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Zeitintervall an, die Poolgröße gemäß Formel für automatische Skalierung automatisch angepasst.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert beträgt 15 Minuten. Die minimale und maximale Wert sind 5 Minuten und 168 Stunden. Wenn Sie einen Wert kleiner als 5 Minuten größer oder gleich 168 Stunden angeben, weist der Batch-Dienst die Anforderung mit einem Fehler der ungültige Eigenschaft-Wert; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleFormula">
      <MemberSignature Language="C#" Value="public string AutoScaleFormula { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoScaleFormula" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.AutoScaleFormula" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleFormula As String" />
      <MemberSignature Language="F#" Value="member this.AutoScaleFormula : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.AutoScaleFormula" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScaleFormula")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Formel für die gewünschte Anzahl von Serverknoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft muss angegeben werden, wenn "enableautoscale" auf "false" festgelegt ist. Es ist erforderlich, wenn "enableautoscale" festgelegt ist auf "true". Die Formel wird auf Gültigkeit überprüft, bevor der Pool erstellt wird. Wenn die Formel nicht gültig ist, weist der Batch-Dienst die Anforderung mit detaillierten Fehlerinformationen zurück.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateReferences As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.CertificateReferences" />
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
            Ruft ab oder legt eine Liste der Zertifikate auf jeder Serverknoten im Pool installiert werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Für Serverknoten für Windows, installiert der Batch-Dienst die Zertifikate auf den angegebenen Zertifikatspeicher und den Speicherort an. Für Linux-Serverknoten werden die Zertifikate gespeichert, in einem Verzeichnis in das Arbeitsverzeichnis für die Aufgabe und eine Umgebung aus, die Variable AZ_BATCH_CERTIFICATES_DIR für den Task zum Abfragen von diesem Speicherort angegeben wird. Für Zertifikate mit der Sichtbarkeit der "RemoteUser" ein "Zertifikate"-Verzeichnis im Basisverzeichnis des Benutzers erstellt wird (z. B. /home/ {Benutzername} / Zertifikaten) und Zertifikate in diesem Verzeichnis abgelegt werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudServiceConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration CloudServiceConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration CloudServiceConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.CloudServiceConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudServiceConfiguration As CloudServiceConfiguration" />
      <MemberSignature Language="F#" Value="member this.CloudServiceConfiguration : Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.CloudServiceConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cloudServiceConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Cloud-Dienstkonfiguration für den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft muss angegeben werden, wenn der Pool muss mit der Azure-PaaS-VMs erstellt werden. Diese Eigenschaft und die VirtualMachineConfiguration schließen sich gegenseitig aus, und eine der Eigenschaften muss angegeben werden.
            Wenn beides nicht angegeben ist, gibt der Batch-Dienst einen Fehler; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung). Diese Eigenschaft nicht angegeben wird, wenn das Batch-Konto, wobei seine PoolAllocationMode-Eigenschaft auf "UserSubscription" festgelegt erstellt wurde.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.DisplayName" />
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
            Ruft ab oder legt den Anzeigenamen für den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Anzeigename muss nicht eindeutig sein und darf keine Unicode-Zeichen bis zu einer maximalen Länge von 1024.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScale">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableAutoScale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableAutoScale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.EnableAutoScale" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableAutoScale As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScale : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.EnableAutoScale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableAutoScale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob die Größe des Pools mit der Zeit automatisch angepasst.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn "false" muss mindestens eine der TargetDedicateNodes und TargetLowPriorityNodes angegeben werden. Bei "true", ist das AutoScaleFormula-Element erforderlich. Der Pool wird automatisch entsprechend der Formel. Der Standardwert ist „false“.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableInterNodeCommunication">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableInterNodeCommunication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableInterNodeCommunication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.EnableInterNodeCommunication" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableInterNodeCommunication As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableInterNodeCommunication : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.EnableInterNodeCommunication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableInterNodeCommunication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob der Pool direkten Kommunikation zwischen Knoten ermöglicht.
            </summary>
        <value>To be added.</value>
        <remarks>
            Aktivieren der Kommunikation zwischen den Knoten schränkt die maximale Größe des Pools aufgrund von Einschränkungen der Bereitstellung auf den Knoten des Pools. Dies kann im Pool nicht die gewünschte Größe erreichen führen. Der Standardwert ist „false“.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTasksPerNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTasksPerNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTasksPerNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.MaxTasksPerNode" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTasksPerNode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTasksPerNode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.MaxTasksPerNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTasksPerNode")</AttributeName>
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
        <remarks>
            Der Standardwert ist 1. Der maximale Wert dieser Einstellung hängt von der Größe der Serverknoten im Pool (VmSize-Einstellung).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.Metadata" />
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
            Ruft ab oder legt eine Liste von Name / Wert-Paaren, die dem Pool als Metadaten zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Batch-Dienst weist keine Bedeutung zu Metadaten; Es ist ausschließlich für die Verwendung von Benutzercode.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration NetworkConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration NetworkConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.NetworkConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkConfiguration As NetworkConfiguration" />
      <MemberSignature Language="F#" Value="member this.NetworkConfiguration : Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.NetworkConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Netzwerkkonfiguration für den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ResizeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ResizeTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.ResizeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ResizeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.ResizeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resizeTimeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Timeout für die Zuweisung von Serverknoten in den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dieses Timeout gilt nur für die manuelle Skalierung. Sie hat keine Auswirkungen, wenn "enableautoscale" festgelegt ist auf "true". Der Standardwert beträgt 15 Minuten.
            Der Mindestwert ist 5 Minuten. Wenn Sie einen Wert kleiner als 5 Minuten angeben, weist der Batch-Dienst die Anforderung mit einem Fehler zurück; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.Protocol.Models.StartTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.StartTask" />
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
            Ruft ab oder legt einen Task auf jeder Compute-Knoten ausgeführt wird, wie den Pool hinzufügen. Der Task ausgeführt wird, wenn der Knoten hinzugefügt wird, an den Pool oder der Knoten neu gestartet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicatedNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicatedNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicatedNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.TargetDedicatedNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicatedNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicatedNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.TargetDedicatedNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetDedicatedNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die gewünschte Anzahl von dedizierten Serverknoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft muss angegeben werden, wenn "enableautoscale" festgelegt ist auf "true". Wenn "enableautoscale" auf "false" festgelegt ist, müssen Sie entweder TargetDedicatedNodes, TargetLowPriorityNodes oder beides festlegen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLowPriorityNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetLowPriorityNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetLowPriorityNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.TargetLowPriorityNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLowPriorityNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetLowPriorityNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.TargetLowPriorityNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetLowPriorityNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die gewünschte Anzahl von Serverknoten mit niedriger Priorität im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft muss angegeben werden, wenn "enableautoscale" festgelegt ist auf "true". Wenn "enableautoscale" auf "false" festgelegt ist, müssen Sie entweder TargetDedicatedNodes, TargetLowPriorityNodes oder beides festlegen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskSchedulingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy TaskSchedulingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy TaskSchedulingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.TaskSchedulingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskSchedulingPolicy As TaskSchedulingPolicy" />
      <MemberSignature Language="F#" Value="member this.TaskSchedulingPolicy : Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.TaskSchedulingPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskSchedulingPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy</ReturnType>
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
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; UserAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; UserAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.UserAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccounts As IList(Of UserAccount)" />
      <MemberSignature Language="F#" Value="member this.UserAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.UserAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt;</ReturnType>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolSpecification.Validate " />
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
    <Member MemberName="VirtualMachineConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration VirtualMachineConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration VirtualMachineConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.VirtualMachineConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineConfiguration As VirtualMachineConfiguration" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineConfiguration : Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.VirtualMachineConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Konfiguration der virtuellen Maschine für den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft muss angegeben werden, wenn der Pool muss mit der Azure-IaaS-VMs erstellt werden. Diese Eigenschaft und die CloudServiceConfiguration schließen sich gegenseitig aus, und eine der Eigenschaften muss angegeben werden.
            Wenn beides nicht angegeben ist, gibt der Batch-Dienst einen Fehler; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.VmSize" />
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
            Ruft ab oder legt die Größe der virtuellen Computer im Pool. Alle virtuellen Computer in einem Pool haben die gleiche Größe.
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