<Type Name="IRecordSetsOperations" FullName="Microsoft.Azure.Management.Dns.IRecordSetsOperations">
  <TypeSignature Language="C#" Value="public interface IRecordSetsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRecordSetsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.IRecordSetsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRecordSetsOperations" />
  <TypeSignature Language="F#" Value="type IRecordSetsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            RecordSetsOperations-Vorgänge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.IRecordSetsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,Microsoft.Azure.Management.Dns.Models.RecordSet,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Microsoft.Azure.Management.Dns.Models.RecordSet * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;" Usage="iRecordSetsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.RecordSet" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="zoneName">
            Der Name der DNS-Zone (ohne einen abschließenden Punkt).
            </param>
        <param name="relativeRecordSetName">
            Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.
            </param>
        <param name="recordType">
            Der Typ des DNS-Eintrags in diesen Datensatz. Zeichnen Sie Sätze von Typ SOA aktualisiert, aber nicht erstellt werden kann (sie werden erstellt, wenn die DNS-Zone erstellt wird). Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
            </param>
        <param name="parameters">
            Parameter für die CreateOrUpdate zur Verfügung gestellt.
            </param>
        <param name="ifMatch">
            Das Etag des Datensatzes festgelegt. Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben. Geben Sie die letzten gesehen Etag-Wert, um versehentlich Overwritting keine gleichzeitigen geändert werden können.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" damit wird einen neuen Datensatz erstellt werden festgelegt, aber um zu verhindern, aktualisieren eine vorhandene Satz aufzeichnen. Andere Werte werden ignoriert.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert einen Datensatz in einer DNS-Zone festgelegt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.IRecordSetsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRecordSetsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, zoneName, relativeRecordSetName, recordType, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="zoneName">
            Der Name der DNS-Zone (ohne einen abschließenden Punkt).
            </param>
        <param name="relativeRecordSetName">
            Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.
            </param>
        <param name="recordType">
            Der Typ des DNS-Eintrags in diesen Datensatz. Zeichnen Sie Sätze von Typ SOA kann nicht gelöscht werden (werden gelöscht, sobald die DNS-Zone gelöscht wird).
            Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
            </param>
        <param name="ifMatch">
            Das Etag des Datensatzes festgelegt. Lassen Sie diesen Wert, um stets aktuelle Ressourceneintragssatz löschen. Geben Sie den letzten gesehen Etag-Wert, um zu verhindern, dass versehentliches Löschen von gleichzeitigen Änderungen.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen Datensatz aus einer DNS-Zone festgelegt. Dieser Vorgang kann nicht rückgängig gemacht werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.IRecordSetsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;" Usage="iRecordSetsOperations.GetWithHttpMessagesAsync (resourceGroupName, zoneName, relativeRecordSetName, recordType, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="zoneName">
            Der Name der DNS-Zone (ohne einen abschließenden Punkt).
            </param>
        <param name="relativeRecordSetName">
            Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.
            </param>
        <param name="recordType">
            Der Typ des DNS-Eintrags in diesen Datensatz. Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft einen Ressourceneintragssatz ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;&gt; ListByDnsZoneNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;&gt; ListByDnsZoneNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.IRecordSetsOperations.ListByDnsZoneNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDnsZoneNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;&gt;" Usage="iRecordSetsOperations.ListByDnsZoneNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle Datensatzgruppen in einer DNS-Zone.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;&gt; ListByDnsZoneWithHttpMessagesAsync (string resourceGroupName, string zoneName, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;&gt; ListByDnsZoneWithHttpMessagesAsync(string resourceGroupName, string zoneName, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.IRecordSetsOperations.ListByDnsZoneWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDnsZoneWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;&gt;" Usage="iRecordSetsOperations.ListByDnsZoneWithHttpMessagesAsync (resourceGroupName, zoneName, top, recordsetnamesuffix, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="zoneName">
            Der Name der DNS-Zone (ohne einen abschließenden Punkt).
            </param>
        <param name="top">
            Die maximale Anzahl der zurückzugebenden Datensätze. Wenn nicht angegeben, gibt bis zu 100 Datensatzgruppen zurück.
            </param>
        <param name="recordsetnamesuffix">
            Die suffixbezeichnung des Namen der Datensatzgruppe, die verwendet werden, um den Datensatz Filtern festlegen Enumerationen. Wenn dieser Parameter angegeben wird, gibt die Enumeration nur Datensätze zurück, die mit enden. &lt;RecordSetNameSuffix&gt;
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle Datensatzgruppen in einer DNS-Zone.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;&gt; ListByTypeNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;&gt; ListByTypeNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.IRecordSetsOperations.ListByTypeNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByTypeNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;&gt;" Usage="iRecordSetsOperations.ListByTypeNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Datensatzgruppen eines angegebenen Typs in einer DNS-Zone.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;&gt; ListByTypeWithHttpMessagesAsync (string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;&gt; ListByTypeWithHttpMessagesAsync(string resourceGroupName, string zoneName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.IRecordSetsOperations.ListByTypeWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.Nullable{System.Int32},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByTypeWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Nullable&lt;int&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;&gt;" Usage="iRecordSetsOperations.ListByTypeWithHttpMessagesAsync (resourceGroupName, zoneName, recordType, top, recordsetnamesuffix, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="zoneName">
            Der Name der DNS-Zone (ohne einen abschließenden Punkt).
            </param>
        <param name="recordType">
            Der Typ der Datensatzgruppen aufgelistet werden. Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
            </param>
        <param name="top">
            Die maximale Anzahl der zurückzugebenden Datensätze. Wenn nicht angegeben, gibt bis zu 100 Datensatzgruppen zurück.
            </param>
        <param name="recordsetnamesuffix">
            Die suffixbezeichnung des Namen der Datensatzgruppe, die verwendet werden, um den Datensatz Filtern festlegen Enumerationen. Wenn dieser Parameter angegeben wird, gibt die Enumeration nur Datensätze zurück, die mit enden. &lt;RecordSetNameSuffix&gt;
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Datensatzgruppen eines angegebenen Typs in einer DNS-Zone.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.IRecordSetsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,Microsoft.Azure.Management.Dns.Models.RecordSet,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Microsoft.Azure.Management.Dns.Models.RecordSet * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;" Usage="iRecordSetsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.RecordSet" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="zoneName">
            Der Name der DNS-Zone (ohne einen abschließenden Punkt).
            </param>
        <param name="relativeRecordSetName">
            Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.
            </param>
        <param name="recordType">
            Der Typ des DNS-Eintrags in diesen Datensatz. Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
            </param>
        <param name="parameters">
            Parameter, die auf den Updatevorgang angegeben werden.
            </param>
        <param name="ifMatch">
            Das Etag des Datensatzes festgelegt. Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben. Geben Sie die letzten gesehen Etag-Wert, um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert einen Datensatz in einer DNS-Zone festgelegt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>