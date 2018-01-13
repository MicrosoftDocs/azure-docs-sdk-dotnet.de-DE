<Type Name="JobResponse" FullName="Microsoft.Azure.Management.IotHub.Models.JobResponse">
  <TypeSignature Language="C#" Value="public class JobResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.JobResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class JobResponse" />
  <TypeSignature Language="F#" Value="type JobResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Eigenschaften des Objekts Auftragsantwort.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.JobResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der JobResponse-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobResponse (string jobId = null, Nullable&lt;DateTime&gt; startTimeUtc = null, Nullable&lt;DateTime&gt; endTimeUtc = null, string type = null, Nullable&lt;Microsoft.Azure.Management.IotHub.Models.JobStatus&gt; status = null, string failureReason = null, string statusMessage = null, string parentJobId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string jobId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTimeUtc, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTimeUtc, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.IotHub.Models.JobStatus&gt; status, string failureReason, string statusMessage, string parentJobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.JobResponse.#ctor(System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{Microsoft.Azure.Management.IotHub.Models.JobStatus},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional jobId As String = null, Optional startTimeUtc As Nullable(Of DateTime) = null, Optional endTimeUtc As Nullable(Of DateTime) = null, Optional type As String = null, Optional status As Nullable(Of JobStatus) = null, Optional failureReason As String = null, Optional statusMessage As String = null, Optional parentJobId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.JobResponse : string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;Microsoft.Azure.Management.IotHub.Models.JobStatus&gt; * string * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.JobResponse" Usage="new Microsoft.Azure.Management.IotHub.Models.JobResponse (jobId, startTimeUtc, endTimeUtc, type, status, failureReason, statusMessage, parentJobId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="startTimeUtc" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTimeUtc" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.IotHub.Models.JobStatus&gt;" />
        <Parameter Name="failureReason" Type="System.String" />
        <Parameter Name="statusMessage" Type="System.String" />
        <Parameter Name="parentJobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId">Der Auftragsbezeichner.</param>
        <param name="startTimeUtc">Die Startzeit des Auftrags.</param>
        <param name="endTimeUtc">Die Zeit, die Verarbeitung des Auftrags beendet.</param>
        <param name="type">Der Typ des Auftrags. Folgende Werte sind möglich: "unknown", "Exportieren", "import", "backup", "ReadDeviceProperties", "WriteDeviceProperties", "UpdateDeviceConfiguration", "RebootDevice", "FactoryResetDevice", "FirmwareUpdate"</param>
        <param name="status">Der Status des Auftrags. Folgende Werte sind möglich: "Unbekannt", "in Warteschlange", "wird ausgeführt", "abgeschlossen", "fehlgeschlagen", "abgebrochen"</param>
        <param name="failureReason">Wenn Status == fehlgeschlagen ist, handelt es sich bei dieser Zeichenfolge, die die Ursache des Fehlers enthält.</param>
        <param name="statusMessage">Die Statusmeldung für den Auftrag.</param>
        <param name="parentJobId">Die Auftrags-ID des übergeordneten Auftrags, sofern vorhanden.</param>
        <summary>
            Initialisiert eine neue Instanz der JobResponse-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.JobResponse.EndTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.JobResponse.EndTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTimeUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Zeit, die Verarbeitung des Auftrags beendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureReason">
      <MemberSignature Language="C#" Value="public string FailureReason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FailureReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.JobResponse.FailureReason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureReason As String" />
      <MemberSignature Language="F#" Value="member this.FailureReason : string" Usage="Microsoft.Azure.Management.IotHub.Models.JobResponse.FailureReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failureReason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, wenn Status == fehlgeschlagen ist, handelt es sich bei dieser Zeichenfolge, die die Ursache des Fehlers enthält.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public string JobId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.JobResponse.JobId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobId As String" />
      <MemberSignature Language="F#" Value="member this.JobId : string" Usage="Microsoft.Azure.Management.IotHub.Models.JobResponse.JobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Auftrags-ID ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParentJobId">
      <MemberSignature Language="C#" Value="public string ParentJobId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ParentJobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.JobResponse.ParentJobId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ParentJobId As String" />
      <MemberSignature Language="F#" Value="member this.ParentJobId : string" Usage="Microsoft.Azure.Management.IotHub.Models.JobResponse.ParentJobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parentJobId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Auftrags-ID des Auftrags übergeordneten ab, sofern vorhanden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.JobResponse.StartTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.JobResponse.StartTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTimeUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Startzeit des Auftrags ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.IotHub.Models.JobStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.IotHub.Models.JobStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.JobResponse.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of JobStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.IotHub.Models.JobStatus&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.JobResponse.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.IotHub.Models.JobStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status des Auftrags ab. Folgende Werte sind möglich: "Unbekannt", "in Warteschlange", "wird ausgeführt", "abgeschlossen", "fehlgeschlagen", "abgebrochen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusMessage">
      <MemberSignature Language="C#" Value="public string StatusMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.JobResponse.StatusMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusMessage As String" />
      <MemberSignature Language="F#" Value="member this.StatusMessage : string" Usage="Microsoft.Azure.Management.IotHub.Models.JobResponse.StatusMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statusMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Statusmeldung für den Auftrag ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.JobResponse.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.IotHub.Models.JobResponse.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ des Auftrags ab. Folgende Werte sind möglich: "unknown", "Exportieren", "import", "backup", "ReadDeviceProperties", "WriteDeviceProperties", "UpdateDeviceConfiguration", "RebootDevice", "FactoryResetDevice", "FirmwareUpdate"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>