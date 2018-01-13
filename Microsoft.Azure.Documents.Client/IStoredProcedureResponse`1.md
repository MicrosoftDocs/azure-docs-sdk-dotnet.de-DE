<Type Name="IStoredProcedureResponse&lt;TValue&gt;" FullName="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;TValue&gt;">
  <TypeSignature Language="C#" Value="public interface IStoredProcedureResponse&lt;TValue&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStoredProcedureResponse`1&lt;TValue&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStoredProcedureResponse(Of TValue)" />
  <TypeSignature Language="F#" Value="type IStoredProcedureResponse&lt;'Value&gt; = interface" />
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
  <Interfaces />
  <Docs>
    <typeparam name="TValue">Der Typ der Rückgabewert der gespeicherten Prozedur.</typeparam>
    <summary>
            Schnittstelle zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ActivityId">
      <MemberSignature Language="C#" Value="public string ActivityId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.ActivityId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityId As String" />
      <MemberSignature Language="F#" Value="member this.ActivityId : string" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.ActivityId" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Aktivitäts-ID der Anforderung ab.
            </summary>
        <value>
            Die Aktivitäts-ID der Anforderung.
            </value>
        <remarks>Jede Anforderung wird mit einem global eindeutigen ID verfolgt. Enthalten Sie Aktivitäts-ID, in die Verfolgung von Anwendungsfehlern und bei der Kontaktaufnahme zu Azure-Cosmos-DB-Unterstützung.
            Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentResourceQuotaUsage">
      <MemberSignature Language="C#" Value="public string CurrentResourceQuotaUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentResourceQuotaUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.CurrentResourceQuotaUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentResourceQuotaUsage As String" />
      <MemberSignature Language="F#" Value="member this.CurrentResourceQuotaUsage : string" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.CurrentResourceQuotaUsage" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die durch Trennzeichen getrennte Zeichenfolge, die die Verwendung der einzelnen Ressourcentypen innerhalb der Auflistung enthält.
            </summary>
        <value>Die durch Trennzeichen getrennte Zeichenfolge, die die Anzahl der verwendeten Einheiten pro Ressourcentyp innerhalb der Auflistung enthält.</value>
        <remarks>
            Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResourceQuota">
      <MemberSignature Language="C#" Value="public string MaxResourceQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxResourceQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.MaxResourceQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResourceQuota As String" />
      <MemberSignature Language="F#" Value="member this.MaxResourceQuota : string" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.MaxResourceQuota" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die durch Trennzeichen getrennte Zeichenfolge, enthält das Kontingent der einzelnen Ressourcentypen innerhalb der Auflistung ab.
            </summary>
        <value>Die durch Trennzeichen getrennte Zeichenfolge, die die Anzahl der verwendeten Einheiten pro Ressourcentyp innerhalb der Auflistung enthält.</value>
        <remarks>
            Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestCharge">
      <MemberSignature Language="C#" Value="public double RequestCharge { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 RequestCharge" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.RequestCharge" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestCharge As Double" />
      <MemberSignature Language="F#" Value="member this.RequestCharge : double" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.RequestCharge" />
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
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der normalisierte anforderungseinheiten (RUs) in Rechnung gestellt.
            </summary>
        <value>
            Die Anzahl der normalisierte anforderungseinheiten (RUs) in Rechnung gestellt.
            </value>
        <remarks>
            Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="public TValue Response { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TValue Response" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.Response" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Response As TValue" />
      <MemberSignature Language="F#" Value="member this.Response : 'Value" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.Response" />
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
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Antwort einer gespeicherten Prozedur, die in den angegebenen Typ serialisiert.
            </summary>
        <value>Die Antwort einer gespeicherten Prozedur, die in den angegebenen Typ serialisiert werden soll.</value>
        <remarks>
            Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Specialized.NameValueCollection ResponseHeaders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Specialized.NameValueCollection ResponseHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.ResponseHeaders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseHeaders As NameValueCollection" />
      <MemberSignature Language="F#" Value="member this.ResponseHeaders : System.Collections.Specialized.NameValueCollection" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.ResponseHeaders" />
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
        <ReturnType>System.Collections.Specialized.NameValueCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Header der Antwort zugeordnet.
            </summary>
        <value>
            Die Header der Antwort zugeordnet.
            </value>
        <remarks>
            Bietet Zugriff auf alle HTTP-Antwortheader, die von der Azure-Cosmos-DB-API zurückgegeben.
            Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptLog">
      <MemberSignature Language="C#" Value="public string ScriptLog { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptLog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.ScriptLog" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScriptLog As String" />
      <MemberSignature Language="F#" Value="member this.ScriptLog : string" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.ScriptLog" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ausgabe von einer gespeicherten Prozedur console.log() Anweisungen ab.
            </summary>
        <value>
            Die Ausgabe von console.log()-Anweisungen in einer gespeicherten Prozedur.
            </value>
        <remarks>
            Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.
            </remarks>
        <altmember cref="P:Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" />
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.SessionToken" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Token für die Verwendung mit Konsistenz sitzungsanforderungen ab.
            </summary>
        <value>
            Das Token für die Verwendung mit sitzungsanforderungen für Konsistenz.
            </value>
        <remarks>
            Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public System.Net.HttpStatusCode StatusCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.HttpStatusCode StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusCode As HttpStatusCode" />
      <MemberSignature Language="F#" Value="member this.StatusCode : System.Net.HttpStatusCode" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.StatusCode" />
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
        <ReturnType>System.Net.HttpStatusCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Statuscode der Anforderung abgeschlossen.
            </summary>
        <value>Der Statuscode der Anforderung abgeschlossen</value>
        <remarks>
            Dies ist zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>