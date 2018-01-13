<Type Name="FileGetFromTaskHeaders" FullName="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders">
  <TypeSignature Language="C#" Value="public class FileGetFromTaskHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileGetFromTaskHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class FileGetFromTaskHeaders" />
  <TypeSignature Language="F#" Value="type FileGetFromTaskHeaders = class&#xA;    interface IProtocolNodeFile" />
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
            Definiert die Header für GetFromTask-Vorgang.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileGetFromTaskHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.#ctor" />
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
            Initialisiert eine neue Instanz der FileGetFromTaskHeaders-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileGetFromTaskHeaders (Nullable&lt;Guid&gt; clientRequestId = null, Nullable&lt;Guid&gt; requestId = null, string eTag = null, Nullable&lt;DateTime&gt; lastModified = null, Nullable&lt;DateTime&gt; ocpCreationTime = null, Nullable&lt;bool&gt; ocpBatchFileIsdirectory = null, string ocpBatchFileUrl = null, string ocpBatchFileMode = null, string contentType = null, Nullable&lt;long&gt; contentLength = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; clientRequestId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; requestId, string eTag, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ocpCreationTime, valuetype System.Nullable`1&lt;bool&gt; ocpBatchFileIsdirectory, string ocpBatchFileUrl, string ocpBatchFileMode, string contentType, valuetype System.Nullable`1&lt;int64&gt; contentLength) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.#ctor(System.Nullable{System.Guid},System.Nullable{System.Guid},System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Boolean},System.String,System.String,System.String,System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientRequestId As Nullable(Of Guid) = null, Optional requestId As Nullable(Of Guid) = null, Optional eTag As String = null, Optional lastModified As Nullable(Of DateTime) = null, Optional ocpCreationTime As Nullable(Of DateTime) = null, Optional ocpBatchFileIsdirectory As Nullable(Of Boolean) = null, Optional ocpBatchFileUrl As String = null, Optional ocpBatchFileMode As String = null, Optional contentType As String = null, Optional contentLength As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders : Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;bool&gt; * string * string * string * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders" Usage="new Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders (clientRequestId, requestId, eTag, lastModified, ocpCreationTime, ocpBatchFileIsdirectory, ocpBatchFileUrl, ocpBatchFileMode, contentType, contentLength)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientRequestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="requestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ocpCreationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ocpBatchFileIsdirectory" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ocpBatchFileUrl" Type="System.String" />
        <Parameter Name="ocpBatchFileMode" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="contentLength" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="clientRequestId">Die Client-Request-Id vom Client bereitgestellt wird, während der Anforderung. Dies wird zurückgegeben, nur, wenn die Return-Client-Request-Id-Parameter festgelegt auf "true".</param>
        <param name="requestId">Ein eindeutiger Bezeichner für die Anforderung, die an der Batch-Dienst vorgenommen wurde. Wenn bei einer Anforderung kontinuierlich ein Fehler auftritt, obwohl die Anforderung ordnungsgemäß formuliert ist, können Sie den Fehler unter Angabe dieses Werts an Microsoft melden. Enthalten Sie in Ihrem Bericht dem Wert des diese Anforderungs-ID, die ungefähre Zeit, dass die Anforderung wurde versucht, das Batch-Konto für die die Anforderung gestellt wurde und die Region, der Konto befindet.</param>
        <param name="eTag">Der ETag-HTTP-Antwortheader. Dies ist eine nicht transparente Zeichenfolge. Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat. Insbesondere können Sie das ETag in eines der If-Modified-Since, If-Unmodified-Since, If-Match- oder If-None-Match-Header übergeben.</param>
        <param name="lastModified">Der Zeitpunkt der letzten Ressourcenänderung.</param>
        <param name="ocpCreationTime">Die Erstellungszeit der Datei.</param>
        <param name="ocpBatchFileIsdirectory">Gibt an, ob das Objekt ein Verzeichnis darstellt.</param>
        <param name="ocpBatchFileUrl">Die URL der Datei.</param>
        <param name="ocpBatchFileMode">Die Datei Mode-Attribut im Oktalformat.</param>
        <param name="contentType">Der Inhaltstyp der Datei.</param>
        <param name="contentLength">Die Länge der Datei.</param>
        <summary>
            Initialisiert eine neue Instanz der FileGetFromTaskHeaders-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.ClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.ClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="client-request-id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die vom Client bei der Anforderung angegebene Client-Request-Id. Dies wird zurückgegeben, nur, wenn die Return-Client-Request-Id-Parameter festgelegt auf "true".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLength">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ContentLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ContentLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.ContentLength" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentLength As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ContentLength : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.ContentLength" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.ContentLength</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Content-Length")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Länge der Datei fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.ContentType" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.ContentType</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Content-Type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Inhaltstyp der Datei.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.ETag" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.ETag</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ETag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den ETag-HTTP-Antwortheader. Dies ist eine nicht transparente Zeichenfolge. Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat. Insbesondere können Sie das ETag in eines der If-Modified-Since, If-Unmodified-Since, If-Match- oder If-None-Match-Header übergeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.LastModified" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.LastModified</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Last-Modified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit, zu der die Ressource zuletzt geändert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpBatchFileIsdirectory">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OcpBatchFileIsdirectory { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OcpBatchFileIsdirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.OcpBatchFileIsdirectory" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpBatchFileIsdirectory As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OcpBatchFileIsdirectory : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.OcpBatchFileIsdirectory" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.OcpBatchFileIsdirectory</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ocp-batch-file-isdirectory")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob das Objekt ein Verzeichnis darstellt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpBatchFileMode">
      <MemberSignature Language="C#" Value="public string OcpBatchFileMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OcpBatchFileMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.OcpBatchFileMode" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpBatchFileMode As String" />
      <MemberSignature Language="F#" Value="member this.OcpBatchFileMode : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.OcpBatchFileMode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.OcpBatchFileMode</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ocp-batch-file-mode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Datei Mode-Attribut im Oktalformat.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpBatchFileUrl">
      <MemberSignature Language="C#" Value="public string OcpBatchFileUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OcpBatchFileUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.OcpBatchFileUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpBatchFileUrl As String" />
      <MemberSignature Language="F#" Value="member this.OcpBatchFileUrl : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.OcpBatchFileUrl" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.OcpBatchFileUrl</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ocp-batch-file-url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die URL der Datei fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpCreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OcpCreationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OcpCreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.OcpCreationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpCreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OcpCreationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.OcpCreationTime" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.OcpCreationTime</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ocp-creation-time")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Dateizeit für die Erstellung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.RequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.RequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="request-id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert einen eindeutigen Bezeichner für die Anforderung, die an der Batch-Dienst vorgenommen wurde. Wenn bei einer Anforderung kontinuierlich ein Fehler auftritt, obwohl die Anforderung ordnungsgemäß formuliert ist, können Sie den Fehler unter Angabe dieses Werts an Microsoft melden. Enthalten Sie in Ihrem Bericht dem Wert des diese Anforderungs-ID, die ungefähre Zeit, dass die Anforderung wurde versucht, das Batch-Konto für die die Anforderung gestellt wurde und die Region, der Konto befindet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>