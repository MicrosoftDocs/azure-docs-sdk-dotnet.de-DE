<Type Name="IOperationalInsightsDataClient" FullName="Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient">
  <TypeSignature Language="C#" Value="public interface IOperationalInsightsDataClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOperationalInsightsDataClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOperationalInsightsDataClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IOperationalInsightsDataClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>0.9.0.1</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Operational Insights-Data-Client
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AdditionalWorkspaces">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AdditionalWorkspaces { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AdditionalWorkspaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.AdditionalWorkspaces" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalWorkspaces As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AdditionalWorkspaces : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.AdditionalWorkspaces" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Zusätzliche Arbeitsbereiche, die in Abfragen mit Cross verwiesen wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Basis-URI des Diensts.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abonnementanmeldeinformationen, clientabonnement eindeutig identifiziert werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder Json-Deserialisierung Einstellungen definiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameHeader">
      <MemberSignature Language="C#" Value="public string NameHeader { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NameHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.NameHeader" />
      <MemberSignature Language="VB.NET" Value="Public Property NameHeader As String" />
      <MemberSignature Language="F#" Value="member this.NameHeader : string with get, set" Usage="Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.NameHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Eindeutiger Name für die aufrufende Anwendung. Dies dient lediglich zum Telemetrie und Debuggen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Preferences">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.OperationalInsights.Models.ApiPreferences Preferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.OperationalInsights.Models.ApiPreferences Preferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.Preferences" />
      <MemberSignature Language="VB.NET" Value="Public Property Preferences As ApiPreferences" />
      <MemberSignature Language="F#" Value="member this.Preferences : Microsoft.Azure.OperationalInsights.Models.ApiPreferences with get, set" Usage="Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.Preferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.OperationalInsights.Models.ApiPreferences</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Fragen Sie die Voreinstellungen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.Azure.OperationalInsights.Models.QueryResults&gt;&gt; QueryWithHttpMessagesAsync (string query, Nullable&lt;TimeSpan&gt; timespan = null, System.Collections.Generic.IList&lt;string&gt; workspaces = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.Azure.OperationalInsights.Models.QueryResults&gt;&gt; QueryWithHttpMessagesAsync(string query, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timespan, class System.Collections.Generic.IList`1&lt;string&gt; workspaces, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.QueryWithHttpMessagesAsync(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member QueryWithHttpMessagesAsync : string * Nullable&lt;TimeSpan&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.Azure.OperationalInsights.Models.QueryResults&gt;&gt;" Usage="iOperationalInsightsDataClient.QueryWithHttpMessagesAsync (query, timespan, workspaces, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.Azure.OperationalInsights.Models.QueryResults&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="timespan" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="workspaces" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query">
            Die auszuführende Abfrage.
            </param>
        <param name="timespan">
            Optional. Die Zeitspanne für die zum Abfragen von Daten. Dies ist ein Wert für den Zeitraum ISO8601.  Diese Zeitspanne wird zusätzlich zu anderen angewendet, die im Abfrageausdruck angegeben sind.
            </param>
        <param name="workspaces">
            Eine Liste der Arbeitsbereiche, die in der Abfrage enthalten sind.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Führen Sie eine Analyseabfrage
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Führt eine Analyseabfrage für Daten.
            [Hier](/documentation/2-Using-the-API/Query) ist ein Beispiel für eine Analyseabfrage mit POST.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public string RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As String" />
      <MemberSignature Language="F#" Value="member this.RequestId : string with get, set" Usage="Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.RequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Eine eindeutige ID pro Anforderung. Dies wird werden pro Anforderung generiert, wenn kein Wert angegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder Json-Serialisierungseinstellungen definiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkspaceId">
      <MemberSignature Language="C#" Value="public string WorkspaceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkspaceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.WorkspaceId" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkspaceId As String" />
      <MemberSignature Language="F#" Value="member this.WorkspaceId : string with get, set" Usage="Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.WorkspaceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die ID des Arbeitsbereichs. Dies ist die Arbeitsbereichs-ID aus dem Blatt "Eigenschaften" im Azure-Portal.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>