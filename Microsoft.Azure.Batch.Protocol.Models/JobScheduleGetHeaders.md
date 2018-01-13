<Type Name="JobScheduleGetHeaders" FullName="Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders">
  <TypeSignature Language="C#" Value="public class JobScheduleGetHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobScheduleGetHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class JobScheduleGetHeaders" />
  <TypeSignature Language="F#" Value="type JobScheduleGetHeaders = class" />
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
            Definiert die Header für die Get-Vorgang.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobScheduleGetHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders.#ctor" />
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
            Initialisiert eine neue Instanz der JobScheduleGetHeaders-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobScheduleGetHeaders (Nullable&lt;Guid&gt; clientRequestId = null, Nullable&lt;Guid&gt; requestId = null, string eTag = null, Nullable&lt;DateTime&gt; lastModified = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; clientRequestId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; requestId, string eTag, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders.#ctor(System.Nullable{System.Guid},System.Nullable{System.Guid},System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientRequestId As Nullable(Of Guid) = null, Optional requestId As Nullable(Of Guid) = null, Optional eTag As String = null, Optional lastModified As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders : Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders (clientRequestId, requestId, eTag, lastModified)" />
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
      </Parameters>
      <Docs>
        <param name="clientRequestId">Die Client-Request-Id vom Client bereitgestellt wird, während der Anforderung. Dies wird zurückgegeben, nur, wenn die Return-Client-Request-Id-Parameter festgelegt auf "true".</param>
        <param name="requestId">Ein eindeutiger Bezeichner für die Anforderung, die an der Batch-Dienst vorgenommen wurde. Wenn bei einer Anforderung kontinuierlich ein Fehler auftritt, obwohl die Anforderung ordnungsgemäß formuliert ist, können Sie den Fehler unter Angabe dieses Werts an Microsoft melden. Enthalten Sie in Ihrem Bericht dem Wert des diese Anforderungs-ID, die ungefähre Zeit, dass die Anforderung wurde versucht, das Batch-Konto für die die Anforderung gestellt wurde und die Region, der Konto befindet.</param>
        <param name="eTag">Der ETag-HTTP-Antwortheader. Dies ist eine nicht transparente Zeichenfolge. Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat. Insbesondere können Sie das ETag in eines der If-Modified-Since, If-Unmodified-Since, If-Match- oder If-None-Match-Header übergeben.</param>
        <param name="lastModified">Der Zeitpunkt der letzten Ressourcenänderung.</param>
        <summary>
            Initialisiert eine neue Instanz der JobScheduleGetHeaders-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders.ClientRequestId" />
      <MemberType>Property</MemberType>
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
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders.ETag" />
      <MemberType>Property</MemberType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders.LastModified" />
      <MemberType>Property</MemberType>
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
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders.RequestId" />
      <MemberType>Property</MemberType>
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