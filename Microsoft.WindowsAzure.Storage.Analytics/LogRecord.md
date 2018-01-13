<Type Name="LogRecord" FullName="Microsoft.WindowsAzure.Storage.Analytics.LogRecord">
  <TypeSignature Language="C#" Value="public class LogRecord" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit LogRecord extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" />
  <TypeSignature Language="VB.NET" Value="Public Class LogRecord" />
  <TypeSignature Language="F#" Value="type LogRecord = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt einen Protokolleintrag für die Speicheranalyse an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob die Anforderung über gemeinsam verwendete Schlüssel oder eine Shared Access Signature (SAS) authentifiziert wurde, oder es anonyme wurde.
            </summary>
        <value>Ein <see cref="T:System.String" /> , der angibt, des Authentifizierungsschemas.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public string ClientRequestId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientRequestId As String" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Wert der X-ms-Client-Request-Id-Header, die in der Anforderung als eine codierte Zeichenfolge enthalten.
            </summary>
        <value>Ein <see cref="T:System.String" /> , enthält die Client-Anforderungs-ID.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConditionsUsed">
      <MemberSignature Language="C#" Value="public string ConditionsUsed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConditionsUsed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ConditionsUsed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConditionsUsed As String" />
      <MemberSignature Language="F#" Value="member this.ConditionsUsed : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ConditionsUsed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Eine durch Semikolons getrennte Liste, in Form von ConditionName = Wert, wie eine codierte Zeichenfolge.
            </summary>
        <value>Ein <see cref="T:System.String" /> , enthält die Bedingungen für die Anforderung verwendet.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndToEndLatency">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; EndToEndLatency { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; EndToEndLatency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.EndToEndLatency" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndToEndLatency As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.EndToEndLatency : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.EndToEndLatency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Gesamtzeit in Millisekunden für den angeforderten Vorgang, z. B. die erforderliche Zeit zum Lesen der eingehenden Anforderung und Senden der Antwort an den anforderer.
            </summary>
        <value>Ein <see cref="T:System.TimeSpan" /> , der angibt, der End-to-End-Latenzzeit für den Vorgang.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETagIdentifier">
      <MemberSignature Language="C#" Value="public string ETagIdentifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETagIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ETagIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETagIdentifier As String" />
      <MemberSignature Language="F#" Value="member this.ETagIdentifier : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ETagIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der ETag-Bezeichner für das zurückgegebene Objekt als eine codierte Zeichenfolge.
            </summary>
        <value>Ein <see cref="T:System.String" /> mit dem ETag für die Ressource.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatusCode">
      <MemberSignature Language="C#" Value="public string HttpStatusCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HttpStatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.HttpStatusCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HttpStatusCode As String" />
      <MemberSignature Language="F#" Value="member this.HttpStatusCode : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.HttpStatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der HTTP-Statuscode für die Anforderung. Wenn die Anforderung unterbrochen wird, kann dieser Wert zu Unknown festgelegt werden.
            </summary>
        <value>Ein <see cref="T:System.String" /> , enthält den HTTP-Statuscode.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; LastModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; LastModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.LastModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.LastModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die letzte Änderung Zeit (LMT) für das zurückgegebene Objekt als eine codierte Zeichenfolge. Dieses Feld ist <c>null</c> für Vorgänge, die mehrere Objekte zurückgeben.
            </summary>
        <value>Ein <see cref="T:System.DateTimeOffset" /> Zeitpunkt der letzten Änderung angeben.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; OperationCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; OperationCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.OperationCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.OperationCount : Nullable&lt;int&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.OperationCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Anzahl der Vorgänge, die für eine Anforderung, beginnend am Index 0 (null) protokolliert. Manche Anforderungen erfordern mehrere Vorgänge, z. B. Copy Blob, obwohl die meisten nur einen Vorgang ausführen.
            </summary>
        <value>Eine ganze Zahl, die die Anzahl der Vorgänge enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationType">
      <MemberSignature Language="C#" Value="public string OperationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.OperationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationType As String" />
      <MemberSignature Language="F#" Value="member this.OperationType : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.OperationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Typ des REST-Vorgang ausgeführt wurde. 
            </summary>
        <value>Ein <see cref="T:System.String" /> den Vorgangstyp angeben.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OwnerAccountName">
      <MemberSignature Language="C#" Value="public string OwnerAccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OwnerAccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.OwnerAccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OwnerAccountName As String" />
      <MemberSignature Language="F#" Value="member this.OwnerAccountName : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.OwnerAccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Kontoname für den Besitzer des Diensts.
            </summary>
        <value>Ein <see cref="T:System.String" /> den Namen des Speicherkontos angeben.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReferrerHeader">
      <MemberSignature Language="C#" Value="public string ReferrerHeader { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReferrerHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ReferrerHeader" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReferrerHeader As String" />
      <MemberSignature Language="F#" Value="member this.ReferrerHeader : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ReferrerHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Verweiser Headerwert als eine codierte Zeichenfolge.
            </summary>
        <value>Ein <see cref="T:System.String" /> mit dem Wert des Headers Referrer.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestContentLength">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; RequestContentLength { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; RequestContentLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestContentLength" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestContentLength As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RequestContentLength : Nullable&lt;int64&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestContentLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Wert des Content-Length-Headers für die an den Speicherdienst gesendete Anforderung. Wenn die Anforderung erfolgreich war, ist dieser Wert gleich Anforderungsgröße-Paket. Wenn eine Anforderung nicht erfolgreich ist, dieser Wert möglicherweise nicht gleich bei der Anforderung der Paketgröße möglicherweise <c>null</c>.
            </summary>
        <value>Ein Long-Wert, die die anforderungsinhaltslänge in Bytes enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedObjectKey">
      <MemberSignature Language="C#" Value="public string RequestedObjectKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedObjectKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestedObjectKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedObjectKey As String" />
      <MemberSignature Language="F#" Value="member this.RequestedObjectKey : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestedObjectKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Schlüssel des angeforderten Objekts, wie eine codierte Zeichenfolge. Dieses Feld wird immer der Kontoname verwendet, auch wenn ein benutzerdefinierter Domänenname konfiguriert wurde.
            </summary>
        <value>Ein <see cref="T:System.String" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequesterAccountName">
      <MemberSignature Language="C#" Value="public string RequesterAccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequesterAccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequesterAccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequesterAccountName As String" />
      <MemberSignature Language="F#" Value="member this.RequesterAccountName : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequesterAccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Name des Speicherkontos an, von dem die Anforderung stammt, wenn die Anforderung über einen gemeinsamen Schlüssel authentifiziert wird. Dieses Feld ist <c>null</c> für anonyme Anforderungen und Anforderungen, die über eine shared Access Signature (SAS).
            </summary>
        <value>Ein <see cref="T:System.String" /> den Namen des Speicherkontos angeben.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequesterIPAddress">
      <MemberSignature Language="C#" Value="public string RequesterIPAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequesterIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequesterIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequesterIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.RequesterIPAddress : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequesterIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die IP-Adresse des anforderers einschließlich der Portnummer.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestHeaderSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; RequestHeaderSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; RequestHeaderSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestHeaderSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestHeaderSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RequestHeaderSize : Nullable&lt;int64&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestHeaderSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Größe des Anforderungsheaders in Bytes. Wenn eine Anforderung nicht erfolgreich ist, ist dieser Wert möglicherweise <c>null</c>.
            </summary>
        <value>Ein Long-Wert, die die Headergröße Anforderung enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestIdHeader">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RequestIdHeader { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RequestIdHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestIdHeader" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestIdHeader As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RequestIdHeader : Nullable&lt;Guid&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestIdHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vom Speicherdienst zugewiesene Anforderungs-ID. Dies entspricht dem Wert des X-ms-Request-Id-Headers.
            </summary>
        <value>Ein <see cref="T:System.Guid" /> , enthält die Anforderungs-ID.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestMD5">
      <MemberSignature Language="C#" Value="public string RequestMD5 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestMD5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestMD5" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestMD5 As String" />
      <MemberSignature Language="F#" Value="member this.RequestMD5 : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestMD5" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Wert des Content-MD5-Header oder die X-ms-Content-md5-Header in der Anforderung als eine codierte Zeichenfolge.
            Der MD5-Hashwert, der in diesem Feld angegebenen stellt den Inhalt in der Anforderung. Dieses Feld kann <c>null</c>.
            </summary>
        <value>Ein <see cref="T:System.String" /> , die die Anforderung MD5-Wert enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestPacketSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; RequestPacketSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; RequestPacketSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestPacketSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestPacketSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RequestPacketSize : Nullable&lt;int64&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestPacketSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Größe des vom Speicherdienst in Byte gelesenen Anforderungspakete. Wenn eine Anforderung nicht erfolgreich ist, ist dieser Wert möglicherweise <c>null</c>.
            </summary>
        <value>Ein Long-Wert, der die Paketgröße für die Anforderung enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; RequestStartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; RequestStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestStartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestStartTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.RequestStartTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Zeit, zu der die Anforderung vom Dienst, im UTC-Format empfangen wurde.
            </summary>
        <value>Ein <see cref="T:System.DateTimeOffset" /> Startzeit für die Anforderung angeben.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestStatus">
      <MemberSignature Language="C#" Value="public string RequestStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestStatus As String" />
      <MemberSignature Language="F#" Value="member this.RequestStatus : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Status des angeforderten Vorgangs.
            </summary>
        <value>Ein <see cref="T:System.String" /> , der angibt, des Anforderungsstatus.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestUrl">
      <MemberSignature Language="C#" Value="public Uri RequestUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri RequestUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestUrl As Uri" />
      <MemberSignature Language="F#" Value="member this.RequestUrl : Uri" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die vollständige URL der Anforderung.
            </summary>
        <value>Ein <see cref="T:System.Uri" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestVersionHeader">
      <MemberSignature Language="C#" Value="public string RequestVersionHeader { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestVersionHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestVersionHeader" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestVersionHeader As String" />
      <MemberSignature Language="F#" Value="member this.RequestVersionHeader : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestVersionHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die speicherdienstversion angegeben, wenn die Anforderung gestellt wurde. Dies entspricht dem Wert des Headers X-ms-Version.
            </summary>
        <value>Ein <see cref="T:System.String" /> , die die Anforderung Version-Header enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseHeaderSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ResponseHeaderSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ResponseHeaderSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ResponseHeaderSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseHeaderSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ResponseHeaderSize : Nullable&lt;int64&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ResponseHeaderSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Größe des Antwortheaders in Bytes. Wenn eine Anforderung nicht erfolgreich ist, ist dieser Wert möglicherweise <c>null</c>.
            </summary>
        <value>Ein Long-Wert, der die Größe des Antwortheaders in Bytes enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponsePacketSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ResponsePacketSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ResponsePacketSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ResponsePacketSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponsePacketSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ResponsePacketSize : Nullable&lt;int64&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ResponsePacketSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Größe des vom Speicherdienst in Byte geschriebenen Antwortpakete. Wenn eine Anforderung nicht erfolgreich ist, ist dieser Wert möglicherweise <c>null</c>.
            </summary>
        <value>Ein Long-Wert, der die Paketgröße des Antwortheaders in Bytes enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerLatency">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ServerLatency { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ServerLatency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ServerLatency" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerLatency As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ServerLatency : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ServerLatency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Gesamtzeit in Millisekunden zum Ausführen des angeforderten Vorgangs. Dieser Wert umfasst nicht die netzwerklatenzzeit (die erforderliche Zeit zum Lesen der eingehenden Anforderung und Senden der Antwort an die anfordernde Person).
            </summary>
        <value>Ein <see cref="T:System.TimeSpan" /> , der angibt, die Server-Wartezeit für den Vorgang.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerMD5">
      <MemberSignature Language="C#" Value="public string ServerMD5 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerMD5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ServerMD5" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerMD5 As String" />
      <MemberSignature Language="F#" Value="member this.ServerMD5 : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ServerMD5" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Wert von der MD5-Hash berechnet, indem der Speicherdienst als eine codierte Zeichenfolge.
            </summary>
        <value>Ein <see cref="T:System.String" /> mit dem Server MD5-Hash.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceType">
      <MemberSignature Language="C#" Value="public string ServiceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ServiceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceType As String" />
      <MemberSignature Language="F#" Value="member this.ServiceType : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ServiceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Speicherdienst, für die die Anforderung eingegangen: Blob, Tabelle oder Warteschlange.
            </summary>
        <value>Ein <see cref="T:System.String" /> , der angibt, für welchen Dienst die Anforderung gestellt wurde.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAgentHeader">
      <MemberSignature Language="C#" Value="public string UserAgentHeader { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserAgentHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.UserAgentHeader" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserAgentHeader As String" />
      <MemberSignature Language="F#" Value="member this.UserAgentHeader : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.UserAgentHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Benutzer-Agent-Header-Wert als eine codierte Zeichenfolge.
            </summary>
        <value>Ein <see cref="T:System.String" /> mit dem Wert des Headers User-Agent.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VersionNumber">
      <MemberSignature Language="C#" Value="public string VersionNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VersionNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.VersionNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VersionNumber As String" />
      <MemberSignature Language="F#" Value="member this.VersionNumber : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.VersionNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Version der Speicheranalyse-Protokollierung verwendet, um den Eintrag aufzuzeichnen.
            </summary>
        <value>Ein <see cref="T:System.String" /> mit der Versionsnummer.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>