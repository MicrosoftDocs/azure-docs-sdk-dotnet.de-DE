<Type Name="JobProperties" FullName="Microsoft.Azure.Devices.JobProperties">
  <TypeSignature Language="C#" Value="public class JobProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.JobProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class JobProperties" />
  <TypeSignature Language="F#" Value="type JobProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Enthält die Eigenschaften eines Auftrags.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Standardkonstruktor, der ein leeres JobProperties-Objekt erstellt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.EndTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTimeUtc : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Devices.JobProperties.EndTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="endTimeUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vom System generiert.  Bei der Erstellung ignoriert.
            Stellt die Zeit, die Verarbeitung des Auftrags beendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeKeysInExport">
      <MemberSignature Language="C#" Value="public bool ExcludeKeysInExport { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeKeysInExport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.ExcludeKeysInExport" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeKeysInExport As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeKeysInExport : bool with get, set" Usage="Microsoft.Azure.Devices.JobProperties.ExcludeKeysInExport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="excludeKeysInExport")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            für Exportaufträge optional. für andere Aufträge ignoriert.  Standardwert: false.  Wenn "false" sind Autorisierung Schlüssel im Export-Ausgabe enthalten.  Schlüssel werden als null andernfalls exportiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureReason">
      <MemberSignature Language="C#" Value="public string FailureReason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FailureReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.FailureReason" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureReason As String" />
      <MemberSignature Language="F#" Value="member this.FailureReason : string with get, set" Usage="Microsoft.Azure.Devices.JobProperties.FailureReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="failureReason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            System-Genereated.  Bei der Erstellung ignoriert.
            Wenn Status == Fehler auftritt, wird dieser stellt eine Zeichenfolge mit dem Grund.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputBlobContainerUri">
      <MemberSignature Language="C#" Value="public string InputBlobContainerUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InputBlobContainerUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.InputBlobContainerUri" />
      <MemberSignature Language="VB.NET" Value="Public Property InputBlobContainerUri As String" />
      <MemberSignature Language="F#" Value="member this.InputBlobContainerUri : string with get, set" Usage="Microsoft.Azure.Devices.JobProperties.InputBlobContainerUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="inputBlobContainerUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der URI mit SAS-Token zu einem blobcontainer, der, die zu synchronisierenden Registrierungsdaten enthält.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputBlobName">
      <MemberSignature Language="C#" Value="public string InputBlobName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InputBlobName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.InputBlobName" />
      <MemberSignature Language="VB.NET" Value="Public Property InputBlobName As String" />
      <MemberSignature Language="F#" Value="member this.InputBlobName : string with get, set" Usage="Microsoft.Azure.Devices.JobProperties.InputBlobName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="inputBlobName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Blob-Name beim Importieren aus der bereitgestellten Eingabe-Blob-Container verwendet werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public string JobId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.JobId" />
      <MemberSignature Language="VB.NET" Value="Public Property JobId As String" />
      <MemberSignature Language="F#" Value="member this.JobId : string with get, set" Usage="Microsoft.Azure.Devices.JobProperties.JobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="jobId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vom System generiert.  Bei der Erstellung ignoriert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputBlobContainerUri">
      <MemberSignature Language="C#" Value="public string OutputBlobContainerUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutputBlobContainerUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.OutputBlobContainerUri" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputBlobContainerUri As String" />
      <MemberSignature Language="F#" Value="member this.OutputBlobContainerUri : string with get, set" Usage="Microsoft.Azure.Devices.JobProperties.OutputBlobContainerUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputBlobContainerUri", Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der URI, die SAS-Token zu einem blobcontainer enthält.  Dies wird verwendet, um den Status des Auftrags und die Ergebnisse ausgeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputBlobName">
      <MemberSignature Language="C#" Value="public string OutputBlobName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutputBlobName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.OutputBlobName" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputBlobName As String" />
      <MemberSignature Language="F#" Value="member this.OutputBlobName : string with get, set" Usage="Microsoft.Azure.Devices.JobProperties.OutputBlobName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="outputBlobName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Name des BLOBs, die in die bereitgestellte Ausgabe-Blob-Container erstellt wird.  Dieses Blob enthält Registrierungsinformationen für den IoT Hub exportierten Geräte.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Progress">
      <MemberSignature Language="C#" Value="public int Progress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Progress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.Progress" />
      <MemberSignature Language="VB.NET" Value="Public Property Progress As Integer" />
      <MemberSignature Language="F#" Value="member this.Progress : int with get, set" Usage="Microsoft.Azure.Devices.JobProperties.Progress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="progress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vom System generiert.  Bei der Erstellung ignoriert.
            Gibt den Prozentsatz der Fertigstellung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.StartTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTimeUtc : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Devices.JobProperties.StartTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="startTimeUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vom System generiert.  Bei der Erstellung ignoriert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.JobStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Devices.JobStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As JobStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Devices.JobStatus with get, set" Usage="Microsoft.Azure.Devices.JobProperties.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vom System generiert.  Bei der Erstellung ignoriert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.JobType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Devices.JobType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As JobType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Devices.JobType with get, set" Usage="Microsoft.Azure.Devices.JobProperties.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type", Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich.
            Der Typ des auszuführenden Auftrag.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>