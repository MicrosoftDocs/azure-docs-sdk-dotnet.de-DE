<Type Name="StoredProcedureResponse&lt;TValue&gt;" FullName="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;">
  <TypeSignature Language="C#" Value="public class StoredProcedureResponse&lt;TValue&gt; : Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;TValue&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StoredProcedureResponse`1&lt;TValue&gt; extends System.Object implements class Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1&lt;!TValue&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1" />
  <TypeSignature Language="VB.NET" Value="Public Class StoredProcedureResponse(Of TValue)&#xA;Implements IStoredProcedureResponse(Of TValue)" />
  <TypeSignature Language="F#" Value="type StoredProcedureResponse&lt;'Value&gt; = class&#xA;    interface IStoredProcedureResponse&lt;'Value&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TValue" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;TValue&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TValue">Der Typ der Rückgabewert der gespeicherten Prozedur.</typeparam>
    <summary>
            Stellt die Antwort aus einer Datenbank gespeicherte Prozedur in der Azure-Cosmos-DB-Dienst zurückgegeben. Umschließt den Antworttext und Headern.
            </summary>
    <remarks>
            Gespeicherte Prozeduren können keine Zeichenfolgenausgabe über die getContext().getResponse().setBody()-Methode zurückgeben.
            Dieses Antworttexts kann es sich um ein serialisiertes JSON-Objekt oder eines anderen Typs sein.
            In .NET SDK kann die Antwort in einen entsprechenden TValue Typ deserialisiert werden.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StoredProcedureResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Der Konstruktor für imitieren Zwecke im Azure-Cosmos-DB-Dienst verfügbar gemacht.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityId">
      <MemberSignature Language="C#" Value="public string ActivityId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.ActivityId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityId As String" />
      <MemberSignature Language="F#" Value="member this.ActivityId : string" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.ActivityId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.ActivityId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Aktivitäts-ID der Anforderung aus dem Azure-Cosmos-DB-Dienst ab.
            </summary>
        <value>
            Die Aktivitäts-ID der Anforderung.
            </value>
        <remarks>Jede Anforderung wird mit einem global eindeutigen ID verfolgt. Enthalten Sie Aktivitäts-ID, in die Verfolgung von Anwendungsfehlern und bei der Kontaktaufnahme zu Azure-Cosmos-DB-Unterstützung</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentResourceQuotaUsage">
      <MemberSignature Language="C#" Value="public string CurrentResourceQuotaUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentResourceQuotaUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.CurrentResourceQuotaUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentResourceQuotaUsage As String" />
      <MemberSignature Language="F#" Value="member this.CurrentResourceQuotaUsage : string" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.CurrentResourceQuotaUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.CurrentResourceQuotaUsage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die durch Trennzeichen getrennte Zeichenfolge, die die Verwendung der einzelnen Ressourcentypen innerhalb der Auflistung aus dem Azure-Cosmos-DB-Dienst enthält.
            </summary>
        <value>Die durch Trennzeichen getrennte Zeichenfolge, die die Anzahl der verwendeten Einheiten pro Ressourcentyp innerhalb der Auflistung enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRUPerMinuteUsed">
      <MemberSignature Language="C#" Value="public bool IsRUPerMinuteUsed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRUPerMinuteUsed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.IsRUPerMinuteUsed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsRUPerMinuteUsed As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRUPerMinuteUsed : bool" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.IsRUPerMinuteUsed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Flag, das der Antwort aus dem Azure-Cosmos-Datenbank zugeordnet, ob diese gespeicherte Prozedur Anforderung Anforderungseinheiten (RUs) Clientorganisation service / minute Kapazität oder nicht.
            </summary>
        <value>
            "True", wenn diese Anforderung aus RUs/Minute Kapazität verarbeitet wird. Andernfalls "false".
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResourceQuota">
      <MemberSignature Language="C#" Value="public string MaxResourceQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxResourceQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.MaxResourceQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResourceQuota As String" />
      <MemberSignature Language="F#" Value="member this.MaxResourceQuota : string" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.MaxResourceQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.MaxResourceQuota</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die durch Trennzeichen getrennte Zeichenfolge, die das Kontingent der einzelnen Ressourcentypen innerhalb der Auflistung aus dem Azure-Cosmos-DB-Dienst enthält.
            </summary>
        <value>Die durch Trennzeichen getrennte Zeichenfolge, die die Anzahl der verwendeten Einheiten pro Ressourcentyp innerhalb der Auflistung enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator TValue (Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt; source);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname !TValue op_Implicit(class Microsoft.Azure.Documents.Client.StoredProcedureResponse`1&lt;!TValue&gt; source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.op_Implicit(Microsoft.Azure.Documents.Client.StoredProcedureResponse{`0})~`0" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (source As StoredProcedureResponse(Of TValue)) As TValue" />
      <MemberSignature Language="F#" Value="static member op_Implicit : Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt; -&gt; 'Value" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.op_Implicit source" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;" />
      </Parameters>
      <Docs>
        <param name="source">Gespeicherte Prozedur-Antwort.</param>
        <summary>
            Ruft die Ressource, die implizit von Azure-Cosmos-DB-Dienst ab.
            </summary>
        <returns>Die zurückgegebene Ressource.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestCharge">
      <MemberSignature Language="C#" Value="public double RequestCharge { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 RequestCharge" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.RequestCharge" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestCharge As Double" />
      <MemberSignature Language="F#" Value="member this.RequestCharge : double" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.RequestCharge" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.RequestCharge</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der normalisierte Azure Cosmos-DB anforderungseinheiten (RUs) in Rechnung gestellt, von Azure-Cosmos-DB-Dienst ab.
            </summary>
        <value>
            Die Anzahl der normalisierte Azure Cosmos-DB-anforderungseinheiten (RUs) in Rechnung gestellt.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="public TValue Response { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TValue Response" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.Response" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Response As TValue" />
      <MemberSignature Language="F#" Value="member this.Response : 'Value" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.Response" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.Response</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Antwort einer gespeicherten Prozedur, die in den angegebenen Typ aus dem Azure-Cosmos-DB-Dienst serialisiert.
            </summary>
        <value>Die Antwort einer gespeicherten Prozedur, die in den angegebenen Typ serialisiert werden soll.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Specialized.NameValueCollection ResponseHeaders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Specialized.NameValueCollection ResponseHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.ResponseHeaders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseHeaders As NameValueCollection" />
      <MemberSignature Language="F#" Value="member this.ResponseHeaders : System.Collections.Specialized.NameValueCollection" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.ResponseHeaders" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.ResponseHeaders</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Specialized.NameValueCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Header der Antwort vom Dienst Azure-Cosmos-Datenbank zugeordnet.
            </summary>
        <value>
            Die Header der Antwort zugeordnet.
            </value>
        <remarks>
            Bietet Zugriff auf alle HTTP-Antwortheader, die von der Azure-Cosmos-DB-API zurückgegeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptLog">
      <MemberSignature Language="C#" Value="public string ScriptLog { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptLog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.ScriptLog" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScriptLog As String" />
      <MemberSignature Language="F#" Value="member this.ScriptLog : string" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.ScriptLog" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.ScriptLog</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ausgabe von einer gespeicherten Prozedur console.log() Anweisungen ab.
            </summary>
        <value>
            Die Ausgabe von console.log()-Anweisungen in einer gespeicherten Prozedur.
            </value>
        <remarks>To be added.</remarks>
        <altmember cref="P:Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" />
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.SessionToken" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.SessionToken</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Token für die Verwendung mit der Sitzung Konsistenz Anforderungen aus dem Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Das Token für die Verwendung mit sitzungsanforderungen für Konsistenz.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public System.Net.HttpStatusCode StatusCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.HttpStatusCode StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusCode As HttpStatusCode" />
      <MemberSignature Language="F#" Value="member this.StatusCode : System.Net.HttpStatusCode" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.StatusCode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.StatusCode</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpStatusCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Statuscode der Anforderung Abschluss aus der Azure-Cosmos-DB-Dienst ab.
            </summary>
        <value>Der Statuscode der Anforderung abgeschlossen</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>