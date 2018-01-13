<Type Name="JobGetOptions" FullName="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions">
  <TypeSignature Language="C#" Value="public class JobGetOptions : Microsoft.Azure.Batch.Protocol.Models.IODataExpand, Microsoft.Azure.Batch.Protocol.Models.IODataSelect, Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobGetOptions extends System.Object implements class Microsoft.Azure.Batch.Protocol.Models.IODataExpand, class Microsoft.Azure.Batch.Protocol.Models.IODataSelect, class Microsoft.Azure.Batch.Protocol.Models.IOptions, class Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobGetOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class JobGetOptions&#xA;Implements IODataExpand, IODataSelect, ITimeoutOptions" />
  <TypeSignature Language="F#" Value="type JobGetOptions = class&#xA;    interface ITimeoutOptions&#xA;    interface IOptions&#xA;    interface IODataSelect&#xA;    interface IODataExpand" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.Protocol.Models.IODataExpand</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.Protocol.Models.IODataSelect</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Zusätzliche Parameter für Get-Vorgang.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobGetOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.#ctor" />
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
            Initialisiert eine neue Instanz der JobGetOptions-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobGetOptions (string select = null, string expand = null, Nullable&lt;int&gt; timeout = null, Nullable&lt;Guid&gt; clientRequestId = null, Nullable&lt;bool&gt; returnClientRequestId = null, Nullable&lt;DateTime&gt; ocpDate = null, string ifMatch = null, string ifNoneMatch = null, Nullable&lt;DateTime&gt; ifModifiedSince = null, Nullable&lt;DateTime&gt; ifUnmodifiedSince = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string select, string expand, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; clientRequestId, valuetype System.Nullable`1&lt;bool&gt; returnClientRequestId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ocpDate, string ifMatch, string ifNoneMatch, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ifModifiedSince, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ifUnmodifiedSince) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.#ctor(System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Guid},System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional select As String = null, Optional expand As String = null, Optional timeout As Nullable(Of Integer) = null, Optional clientRequestId As Nullable(Of Guid) = null, Optional returnClientRequestId As Nullable(Of Boolean) = null, Optional ocpDate As Nullable(Of DateTime) = null, Optional ifMatch As String = null, Optional ifNoneMatch As String = null, Optional ifModifiedSince As Nullable(Of DateTime) = null, Optional ifUnmodifiedSince As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobGetOptions : string * string * Nullable&lt;int&gt; * Nullable&lt;Guid&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobGetOptions" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobGetOptions (select, expand, timeout, clientRequestId, returnClientRequestId, ocpDate, ifMatch, ifNoneMatch, ifModifiedSince, ifUnmodifiedSince)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="clientRequestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="returnClientRequestId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ocpDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="ifModifiedSince" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ifUnmodifiedSince" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="select">Eine OData-$select-Klausel.</param>
        <param name="expand">Ein OData-$expand-Klausel.</param>
        <param name="timeout">Die maximale Zeit, die der Server verarbeitet die Anforderung in Sekunden aufwenden kann. Der Standardwert ist 30 Sekunden.</param>
        <param name="clientRequestId">Die vom Aufrufer generierte Anforderungsidentität in Form einer GUID ohne Dekoration wie etwa geschweifte Klammern ein, z. B. 9C4D50EE 2-d 56-CD 3-8152-34347DC9F2B0 4.</param>
        <param name="returnClientRequestId">Gibt an, ob der Server die Client-Request-Id in der Antwort zurückgeben soll.</param>
        <param name="ocpDate">Die Zeit, die die Anforderung ausgegeben wurde. Clientbibliotheken festlegen, in der Regel um die aktuelle Systemuhrzeit; Legen Sie sie explizit die REST-API direkt aufrufen.</param>
        <param name="ifMatch">Ein ETag-Wert, der Version der Ressource dem Client bekannt zugeordnet. Der Vorgang wird ausgeführt werden, nur dann, wenn das aktuelle ETag der Ressource für den Dienst genau dem vom Client angegebenen Wert entspricht.</param>
        <param name="ifNoneMatch">Ein ETag-Wert, der Version der Ressource dem Client bekannt zugeordnet. Der Vorgang wird ausgeführt werden, nur dann, wenn das aktuelle ETag der Ressource für den Dienst nicht mit den vom Client angegebenen Wert übereinstimmt.</param>
        <param name="ifModifiedSince">Ein Zeitstempel, der angibt, den Zeitpunkt des letzten Änderung der Ressource an den Client bezeichnet. Der Vorgang wird ausgeführt werden, nur, wenn die Ressource für den Dienst seit dem angegebenen Uhrzeit geändert wurde.</param>
        <param name="ifUnmodifiedSince">Ein Zeitstempel, der angibt, den Zeitpunkt des letzten Änderung der Ressource an den Client bezeichnet. Der Vorgang wird ausgeführt werden, nur dann, wenn die Ressource für den Dienst nicht seit dem angegebenen Uhrzeit geändert wurde.</param>
        <summary>
            Initialisiert eine neue Instanz der JobGetOptions-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.ClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die vom Aufrufer generierte Anforderungsidentität in Form einer GUID ohne Dekoration wie etwa geschweifte Klammern ein, z. B. 9C4D50EE 2-d 56-CD 3-8152-34347DC9F2B0 4.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expand">
      <MemberSignature Language="C#" Value="public string Expand { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Expand" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.Expand" />
      <MemberSignature Language="VB.NET" Value="Public Property Expand As String" />
      <MemberSignature Language="F#" Value="member this.Expand : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.Expand" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IODataExpand.Expand</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen OData $expand-Klausel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfMatch">
      <MemberSignature Language="C#" Value="public string IfMatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IfMatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.IfMatch" />
      <MemberSignature Language="VB.NET" Value="Public Property IfMatch As String" />
      <MemberSignature Language="F#" Value="member this.IfMatch : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.IfMatch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen ETag-Wert, der die Version der Ressource dem Client bekannt zugeordnet. Der Vorgang wird ausgeführt werden, nur dann, wenn das aktuelle ETag der Ressource für den Dienst genau dem vom Client angegebenen Wert entspricht.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfModifiedSince">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; IfModifiedSince { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; IfModifiedSince" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.IfModifiedSince" />
      <MemberSignature Language="VB.NET" Value="Public Property IfModifiedSince As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.IfModifiedSince : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.IfModifiedSince" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert einen Zeitstempel, der angibt, den Zeitpunkt des letzten Änderung der Ressource an den Client bezeichnet. Der Vorgang wird ausgeführt werden, nur, wenn die Ressource für den Dienst seit dem angegebenen Uhrzeit geändert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfNoneMatch">
      <MemberSignature Language="C#" Value="public string IfNoneMatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IfNoneMatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.IfNoneMatch" />
      <MemberSignature Language="VB.NET" Value="Public Property IfNoneMatch As String" />
      <MemberSignature Language="F#" Value="member this.IfNoneMatch : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.IfNoneMatch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen ETag-Wert, der die Version der Ressource dem Client bekannt zugeordnet. Der Vorgang wird ausgeführt werden, nur dann, wenn das aktuelle ETag der Ressource für den Dienst nicht mit den vom Client angegebenen Wert übereinstimmt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfUnmodifiedSince">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; IfUnmodifiedSince { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; IfUnmodifiedSince" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.IfUnmodifiedSince" />
      <MemberSignature Language="VB.NET" Value="Public Property IfUnmodifiedSince As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.IfUnmodifiedSince : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.IfUnmodifiedSince" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert einen Zeitstempel, der angibt, den Zeitpunkt des letzten Änderung der Ressource an den Client bezeichnet. Der Vorgang wird ausgeführt werden, nur dann, wenn die Ressource für den Dienst nicht seit dem angegebenen Uhrzeit geändert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OcpDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OcpDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.OcpDate" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OcpDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.OcpDate" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit, die die Anforderung ausgegeben wurde. Clientbibliotheken festlegen, in der Regel um die aktuelle Systemuhrzeit; Legen Sie sie explizit die REST-API direkt aufrufen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReturnClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReturnClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.ReturnClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReturnClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReturnClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.ReturnClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ReturnClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, ob der Server die Client-Request-Id in der Antwort zurückgeben soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public string Select { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Select" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.Select" />
      <MemberSignature Language="VB.NET" Value="Public Property Select As String" />
      <MemberSignature Language="F#" Value="member this.Select : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.Select" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IODataSelect.Select</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine OData-$select-Klausel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Timeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Timeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.Timeout" />
      <MemberSignature Language="VB.NET" Value="Public Property Timeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Timeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions.Timeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions.Timeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Zeit, dass der Server konsolenmeldungen Verarbeitung der Anforderung in Sekunden fest. Der Standardwert ist 30 Sekunden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>