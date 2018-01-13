<Type Name="IDocumentClient" FullName="Microsoft.Azure.Documents.IDocumentClient">
  <TypeSignature Language="C#" Value="public interface IDocumentClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDocumentClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.IDocumentClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDocumentClient" />
  <TypeSignature Language="F#" Value="type IDocumentClient = interface" />
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
  <Interfaces />
  <Docs>
    <summary>
            Die Schnittstelle IDocumentClient erfasst die Signaturen der API des Azure-Cosmos-DB .NET SDK-Diensts.
            Finden Sie unter <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> Details zur Implementierung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthKey">
      <MemberSignature Language="C#" Value="public System.Security.SecureString AuthKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Security.SecureString AuthKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IDocumentClient.AuthKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthKey As SecureString" />
      <MemberSignature Language="F#" Value="member this.AuthKey : System.Security.SecureString" Usage="Microsoft.Azure.Documents.IDocumentClient.AuthKey" />
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
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die vom Client in der Azure-Cosmos-DB-Dienst verwendete AuthKey ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Client.ConnectionPolicy ConnectionPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Client.ConnectionPolicy ConnectionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IDocumentClient.ConnectionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionPolicy As ConnectionPolicy" />
      <MemberSignature Language="F#" Value="member this.ConnectionPolicy : Microsoft.Azure.Documents.Client.ConnectionPolicy" Usage="Microsoft.Azure.Documents.IDocumentClient.ConnectionPolicy" />
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
        <ReturnType>Microsoft.Azure.Documents.Client.ConnectionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <see cref="T:Microsoft.Azure.Documents.Client.ConnectionPolicy" /> vom Client in der Azure-Cosmos-DB-Dienst verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsistencyLevel">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.ConsistencyLevel ConsistencyLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.ConsistencyLevel ConsistencyLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IDocumentClient.ConsistencyLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsistencyLevel As ConsistencyLevel" />
      <MemberSignature Language="F#" Value="member this.ConsistencyLevel : Microsoft.Azure.Documents.ConsistencyLevel" Usage="Microsoft.Azure.Documents.IDocumentClient.ConsistencyLevel" />
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
        <ReturnType>Microsoft.Azure.Documents.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die konfigurierte <see cref="T:Microsoft.Azure.Documents.ConsistencyLevel" /> des Clients in der Azure-Cosmos-DB-Dienst. 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; CreateAttachmentAsync (string documentLink, object attachment, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; CreateAttachmentAsync(string documentLink, object attachment, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAttachmentAsync (documentLink As String, attachment As Object, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentAsync : string * obj * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.CreateAttachmentAsync (documentLink, attachment, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="attachment" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">Der Link, der das übergeordnete Dokument für diese neue Anlage. Beispiel: DBS/Db_rid/colls/Col_rid/Dokumente/Doc_rid / </param>
        <param name="attachment">Die Attachment-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Erstellt eine Anlage als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>
            Die <see cref="T:System.Threading.Tasks.Task" /> Objekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; CreateAttachmentAsync (Uri documentUri, object attachment, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; CreateAttachmentAsync(class System.Uri documentUri, object attachment, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentAsync(System.Uri,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAttachmentAsync (documentUri As Uri, attachment As Object, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentAsync : Uri * obj * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.CreateAttachmentAsync (documentUri, attachment, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="attachment" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">Der URI des Dokuments eine Anlage für erstellen.</param>
        <param name="attachment">Die Attachment-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Erstellt eine Anlage als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; CreateAttachmentAsync (string documentLink, System.IO.Stream mediaStream, Microsoft.Azure.Documents.Client.MediaOptions options = null, Microsoft.Azure.Documents.Client.RequestOptions requestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; CreateAttachmentAsync(string documentLink, class System.IO.Stream mediaStream, class Microsoft.Azure.Documents.Client.MediaOptions options, class Microsoft.Azure.Documents.Client.RequestOptions requestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentAsync(System.String,System.IO.Stream,Microsoft.Azure.Documents.Client.MediaOptions,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentAsync : string * System.IO.Stream * Microsoft.Azure.Documents.Client.MediaOptions * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.CreateAttachmentAsync (documentLink, mediaStream, options, requestOptions)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="mediaStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.MediaOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">Der Link, der das übergeordnete Dokument für diese neue Anlage. Beispiel: DBS/Db_rid/colls/Col_rid/Dokumente/Doc_rid / </param>
        <param name="mediaStream">Die <see cref="T:System.IO.Stream" /> der Medien anfügen.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.MediaOptions" /> für die Anforderung.</param>
        <param name="requestOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Erstellt eine Anlage mit dem Inhalt des bereitgestellten <paramref name="mediaStream" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn entweder <paramref name="documentLink" /> oder <paramref name="mediaStream" /> ist nicht festgelegt.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; CreateAttachmentAsync (Uri documentUri, System.IO.Stream mediaStream, Microsoft.Azure.Documents.Client.MediaOptions options = null, Microsoft.Azure.Documents.Client.RequestOptions requestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; CreateAttachmentAsync(class System.Uri documentUri, class System.IO.Stream mediaStream, class Microsoft.Azure.Documents.Client.MediaOptions options, class Microsoft.Azure.Documents.Client.RequestOptions requestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentAsync(System.Uri,System.IO.Stream,Microsoft.Azure.Documents.Client.MediaOptions,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentAsync : Uri * System.IO.Stream * Microsoft.Azure.Documents.Client.MediaOptions * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.CreateAttachmentAsync (documentUri, mediaStream, options, requestOptions)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="mediaStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.MediaOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">Der URI des Dokuments eine Anlage für erstellen.</param>
        <param name="mediaStream">Der Datenstrom der Medien anfügen.</param>
        <param name="options">Die Media-Optionen für die Anforderung.</param>
        <param name="requestOptions">Die Anforderungsoptionen für die Anforderung.</param>
        <summary>
            Erstellt eine Anlage als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Attachment&gt; CreateAttachmentQuery (string documentLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Attachment&gt; CreateAttachmentQuery(string documentLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Attachment&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentLink, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Attachment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">Den Link, um das übergeordnete Dokument</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Anlagen in der Azure-Cosmos-DB-Dienst. Es gibt eine IOrderedQueryable {Anlage} zurück.
            </summary>
        <returns>Ein IOrderedQueryable {Anlagen}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Attachment&gt; CreateAttachmentQuery (Uri documentUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Attachment&gt; CreateAttachmentQuery(class System.Uri documentUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Attachment&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentUri, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Attachment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">Der URI, der das übergeordnete Dokument.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Die Methode zum Erstellen einer Abfrage für Anlagen in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateAttachmentQuery (string documentLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateAttachmentQuery(string documentLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentLink, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">Der Link auf die übergeordnete dokumentressource.</param>
        <param name="querySpec">Die SqlQuerySpec-Instanz, die die SQL-Ausdruck enthält.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
             Überladen. Diese Methode erstellt eine Abfrage für Anlagen parametrisierte Werte im Azure-Cosmos-DB-Dienst mit einer SQL-Anweisung. Es gibt eine IQueryable {Dynamic} zurück.
             Weitere Informationen zum Vorbereiten von SQL-Anweisungen mit parametrisierte Werte finden Sie unter <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />.
            </summary>
        <returns>Ein IQueryable {Dynamic}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateAttachmentQuery (string documentLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateAttachmentQuery(string documentLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentLink, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">Der Link, um das übergeordnete Dokument.</param>
        <param name="sqlExpression">Die SQL-Anweisung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Anlagen mithilfe einer SQL-Anweisung in der Azure-Cosmos-DB-Dienst. Es gibt eine IQueryable {Dynamic} zurück.
            </summary>
        <returns>Ein IQueryable {Dynamic}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateAttachmentQuery (Uri documentUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateAttachmentQuery(class System.Uri documentUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentUri, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">Der URI, der das übergeordnete Dokument.</param>
        <param name="querySpec">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Die Methode zum Erstellen einer Abfrage für Anlagen in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateAttachmentQuery (Uri documentUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateAttachmentQuery(class System.Uri documentUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentUri, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">Der URI, der das übergeordnete Dokument.</param>
        <param name="sqlExpression">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Die Methode zum Erstellen einer Abfrage für Anlagen in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;T&gt; CreateAttachmentQuery&lt;T&gt; (string documentLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;!!T&gt; CreateAttachmentQuery&lt;T&gt;(string documentLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery``1(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentLink, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">Der Typ des Objekts Abfragen.</typeparam>
        <param name="documentLink">Der Link, der das übergeordnete Dokument.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Anlagen in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein IOrderedQueryable {T}, die die Abfrage ausgewertet werden kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;T&gt; CreateAttachmentQuery&lt;T&gt; (Uri documentUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;!!T&gt; CreateAttachmentQuery&lt;T&gt;(class System.Uri documentUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery``1(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentUri, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">Der Typ des Objekts Abfragen.</typeparam>
        <param name="documentUri">Der URI, der das übergeordnete Dokument.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Die Methode zum Erstellen einer Abfrage für Anlagen in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; CreateAttachmentQuery&lt;T&gt; (string documentLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!T&gt; CreateAttachmentQuery&lt;T&gt;(string documentLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery``1(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentLink, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="documentLink">Der Link, der das übergeordnete Dokument.</param>
        <param name="querySpec">Die SqlQuerySpec-Instanz, die die SQL-Ausdruck enthält.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
             Überladen. Diese Methode erstellt eine Abfrage für Anlagen parametrisierte Werte im Azure-Cosmos-DB-Dienst mit einer SQL-Anweisung.
             Weitere Informationen zum Vorbereiten von SQL-Anweisungen mit parametrisierte Werte finden Sie unter <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />.
            </summary>
        <returns>Ein IQueryable {T}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; CreateAttachmentQuery&lt;T&gt; (string documentLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!T&gt; CreateAttachmentQuery&lt;T&gt;(string documentLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery``1(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentLink, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="documentLink">Der Link, der das übergeordnete Dokument.</param>
        <param name="sqlExpression">Die SQL-Anweisung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Anlagen mithilfe einer SQL-Anweisung in der Azure-Cosmos-DB-Dienst. 
            </summary>
        <returns>Ein IQueryable {T}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; CreateAttachmentQuery&lt;T&gt; (Uri documentUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!T&gt; CreateAttachmentQuery&lt;T&gt;(class System.Uri documentUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery``1(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentUri, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="documentUri">Der URI, der das übergeordnete Dokument.</param>
        <param name="querySpec">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Die Methode zum Erstellen einer Abfrage für Anlagen in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; CreateAttachmentQuery&lt;T&gt; (Uri documentUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!T&gt; CreateAttachmentQuery&lt;T&gt;(class System.Uri documentUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery``1(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentUri, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="documentUri">Der URI, der das übergeordnete Dokument.</param>
        <param name="sqlExpression">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Die Methode zum Erstellen einer Abfrage für Anlagen in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConflictQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Conflict&gt; CreateConflictQuery (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Conflict&gt; CreateConflictQuery(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateConflictQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateConflictQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Conflict&gt;" Usage="iDocumentClient.CreateConflictQuery (collectionLink, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Conflict&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link auf die Ressource der übergeordneten Auflistung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Konflikte unter einer Auflistung im Azure-Cosmos-DB-Dienst. Es gibt ein IOrderedQueryable {Konflikt} zurück.
            </summary>
        <returns>Ein IOrderedQueryable {Konflikt}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConflictQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Conflict&gt; CreateConflictQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Conflict&gt; CreateConflictQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateConflictQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateConflictQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Conflict&gt;" Usage="iDocumentClient.CreateConflictQuery (documentCollectionUri, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Conflict&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Die Methode zum Erstellen einer Abfrage für Konflikte in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConflictQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateConflictQuery (string collectionLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateConflictQuery(string collectionLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateConflictQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateConflictQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateConflictQuery (collectionLink, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link auf die Ressource der übergeordneten Auflistung.</param>
        <param name="querySpec">Die SqlQuerySpec-Instanz, die die SQL-Ausdruck enthält.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Konflikte unter einer Auflistung in der Azure-Cosmos-DB-Dienst mit parametrisierte Werte. Es gibt eine IQueryable {Dynamic} zurück.
             Weitere Informationen zum Vorbereiten von SQL-Anweisungen mit parametrisierte Werte finden Sie unter <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />.
            </summary>
        <returns>Ein IQueryable {Dynamic}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConflictQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateConflictQuery (string collectionLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateConflictQuery(string collectionLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateConflictQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateConflictQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateConflictQuery (collectionLink, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link auf die Ressource der übergeordneten Auflistung.</param>
        <param name="sqlExpression">Die SQL-Anweisung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Konflikte unter einer Auflistung im Azure-Cosmos-DB-Dienst. Es gibt eine IQueryable {Konflikt} zurück.
            </summary>
        <returns>Ein IQueryable {Dynamic}, die die Abfrage mit ergeben, kann die bereitgestellten SQL-Anweisung.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConflictQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateConflictQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateConflictQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateConflictQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateConflictQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateConflictQuery (documentCollectionUri, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="querySpec">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Die Methode zum Erstellen einer Abfrage für Konflikte in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConflictQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateConflictQuery (Uri documentCollectionUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateConflictQuery(class System.Uri documentCollectionUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateConflictQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateConflictQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateConflictQuery (documentCollectionUri, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="sqlExpression">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Die Methode zum Erstellen einer Abfrage für Konflikte in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDatabaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt; CreateDatabaseAsync (Microsoft.Azure.Documents.Database database, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Database&gt;&gt; CreateDatabaseAsync(class Microsoft.Azure.Documents.Database database, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDatabaseAsync(Microsoft.Azure.Documents.Database,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDatabaseAsync : Microsoft.Azure.Documents.Database * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;" Usage="iDocumentClient.CreateDatabaseAsync (database, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="database" Type="Microsoft.Azure.Documents.Database" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="database">Die Spezifikation für die <see cref="T:Microsoft.Azure.Documents.Database" /> zu erstellen.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Erstellt eine Datenbankressource als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Die <see cref="T:Microsoft.Azure.Documents.Database" /> , erstellt wurde, in einem Taskobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDatabaseQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Database&gt; CreateDatabaseQuery (Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Database&gt; CreateDatabaseQuery(class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDatabaseQuery(Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDatabaseQuery : Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Database&gt;" Usage="iDocumentClient.CreateDatabaseQuery feedOptions" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Database&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Datenbankressourcen unter einem Konto im Azure-Cosmos-DB-Dienst. Gibt ein IOrderedQueryable {Datenbank&gt;.
            </summary>
        <returns>Ein IOrderedQueryable {Datenbank}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDatabaseQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDatabaseQuery (Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDatabaseQuery(class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDatabaseQuery(Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDatabaseQuery : Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDatabaseQuery (querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="querySpec">Die SqlQuerySpec-Instanz, die die SQL-Ausdruck enthält.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Datenbankressourcen unter einem Konto mit einer SQL-Anweisung mit parametrisierte Werte im Azure-Cosmos-DB-Dienst. Es gibt eine IQueryable {Dynamic} zurück.
             Weitere Informationen zum Vorbereiten von SQL-Anweisungen mit parametrisierte Werte finden Sie unter <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />.
            </summary>
        <returns>Ein IQueryable {Dynamic}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDatabaseQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDatabaseQuery (string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDatabaseQuery(string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDatabaseQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDatabaseQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDatabaseQuery (sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="sqlExpression">Die SQL-Anweisung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Datenbankressourcen unter einem Konto mit einer SQL­Anweisung im Azure-Cosmos-DB-Dienst. Es gibt eine IQueryable {Dynamic} zurück.
            </summary>
        <returns>Ein IQueryable {Dynamic}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; CreateDocumentAsync (string collectionLink, object document, Microsoft.Azure.Documents.Client.RequestOptions options = null, bool disableAutomaticIdGeneration = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; CreateDocumentAsync(string collectionLink, object document, class Microsoft.Azure.Documents.Client.RequestOptions options, bool disableAutomaticIdGeneration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateDocumentAsync (collectionLink As String, document As Object, Optional options As RequestOptions = null, Optional disableAutomaticIdGeneration As Boolean = false) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentAsync : string * obj * Microsoft.Azure.Documents.Client.RequestOptions * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.CreateDocumentAsync (collectionLink, document, options, disableAutomaticIdGeneration)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="document" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
        <Parameter Name="disableAutomaticIdGeneration" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Die Verknüpfung der <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> das Dokument zu erstellen. Beispiel: DBS/Db_rid/colls/Coll_rid / </param>
        <param name="document">Das Document-Objekt zu erstellen.</param>
        <param name="options">(Optional) Die Anforderungsoptionen, die Sie festlegen möchten. Beispiel: Angeben eines Triggers ausgeführt wird, wenn das Dokument zu erstellen. <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /></param>
        <param name="disableAutomaticIdGeneration">(Optional) Deaktiviert die automatische Id-Generierung, ist dies "true" das System löst eine Ausnahme aus, wenn die Id-Eigenschaft aus dem Dokument nicht vorhanden ist.</param>
        <summary>
            Erstellt ein Dokument als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; CreateDocumentAsync (Uri documentCollectionUri, object document, Microsoft.Azure.Documents.Client.RequestOptions options = null, bool disableAutomaticIdGeneration = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; CreateDocumentAsync(class System.Uri documentCollectionUri, object document, class Microsoft.Azure.Documents.Client.RequestOptions options, bool disableAutomaticIdGeneration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentAsync(System.Uri,System.Object,Microsoft.Azure.Documents.Client.RequestOptions,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateDocumentAsync (documentCollectionUri As Uri, document As Object, Optional options As RequestOptions = null, Optional disableAutomaticIdGeneration As Boolean = false) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentAsync : Uri * obj * Microsoft.Azure.Documents.Client.RequestOptions * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.CreateDocumentAsync (documentCollectionUri, document, options, disableAutomaticIdGeneration)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="document" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
        <Parameter Name="disableAutomaticIdGeneration" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der Dokument-Auflistung des Dokuments in.</param>
        <param name="document">Das Document-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <param name="disableAutomaticIdGeneration">Ein Flag automatische Id Generierung zu deaktivieren.</param>
        <summary>
            Erstellt ein Dokument als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; CreateDocumentCollectionAsync (string databaseLink, Microsoft.Azure.Documents.DocumentCollection documentCollection, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; CreateDocumentCollectionAsync(string databaseLink, class Microsoft.Azure.Documents.DocumentCollection documentCollection, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentCollectionAsync(System.String,Microsoft.Azure.Documents.DocumentCollection,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentCollectionAsync : string * Microsoft.Azure.Documents.DocumentCollection * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.CreateDocumentCollectionAsync (databaseLink, documentCollection, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="documentCollection" Type="Microsoft.Azure.Documents.DocumentCollection" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">Die Verknüpfung der Datenbank, die die Sammlung zu erstellen. Beispiel: DBS/Db_rid /</param>
        <param name="documentCollection">Das <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> Sie beim Erstellen einer Sammlung bereitstellen möchten. Beispiel: RequestOptions.OfferThroughput=400. </param>
        <summary>
            Erstellt eine Auflistung als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Die <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> erstellte innerhalb einer <see cref="T:System.Threading.Tasks.Task" /> Objekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; CreateDocumentCollectionAsync (Uri databaseUri, Microsoft.Azure.Documents.DocumentCollection documentCollection, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; CreateDocumentCollectionAsync(class System.Uri databaseUri, class Microsoft.Azure.Documents.DocumentCollection documentCollection, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentCollectionAsync(System.Uri,Microsoft.Azure.Documents.DocumentCollection,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentCollectionAsync : Uri * Microsoft.Azure.Documents.DocumentCollection * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.CreateDocumentCollectionAsync (databaseUri, documentCollection, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="documentCollection" Type="Microsoft.Azure.Documents.DocumentCollection" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">Der URI der Datenbank auf die Sammlung zu erstellen.</param>
        <param name="documentCollection">Das <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Erstellt eine Auflistung als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.DocumentCollection&gt; CreateDocumentCollectionQuery (string databaseLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt; CreateDocumentCollectionQuery(string databaseLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentCollectionQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentCollectionQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.DocumentCollection&gt;" Usage="iDocumentClient.CreateDocumentCollectionQuery (databaseLink, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.DocumentCollection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">Der Link auf die Ressource der übergeordneten Datenbank.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Auflistungen unter einem Azure-Cosmos-DB-Dienst. Gibt ein IOrderedQueryable {DocumentCollection&gt;.
            </summary>
        <returns>Ein IOrderedQueryable {DocumentCollection}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.DocumentCollection&gt; CreateDocumentCollectionQuery (Uri databaseUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt; CreateDocumentCollectionQuery(class System.Uri databaseUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentCollectionQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentCollectionQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.DocumentCollection&gt;" Usage="iDocumentClient.CreateDocumentCollectionQuery (databaseUri, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.DocumentCollection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">Der URI der übergeordneten Datenbank.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die eine Abfrage für dokumentauflistungen im Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDocumentCollectionQuery (string databaseLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDocumentCollectionQuery(string databaseLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentCollectionQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentCollectionQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDocumentCollectionQuery (databaseLink, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">Der Link auf die Ressource der übergeordneten Datenbank.</param>
        <param name="querySpec">Die SqlQuerySpec-Instanz, die die SQL-Ausdruck enthält.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Auflistungen unter einer Azure-Cosmos-DB-Datenbank, die parametrisierte Werte mit einer SQL-Anweisung. Es gibt eine IQueryable {Dynamic} zurück.
             Weitere Informationen zum Vorbereiten von SQL-Anweisungen mit parametrisierte Werte finden Sie unter <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />.
            </summary>
        <returns>Ein IQueryable {Dynamic}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDocumentCollectionQuery (string databaseLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDocumentCollectionQuery(string databaseLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentCollectionQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentCollectionQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDocumentCollectionQuery (databaseLink, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">Der Link auf die Ressource der übergeordneten Datenbank.</param>
        <param name="sqlExpression">Die SQL-Anweisung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Auflistungen unter einer Azure-Cosmos-DB-Datenbank mit einer SQL­Anweisung.   Es gibt eine IQueryable {DocumentCollection} zurück.
            </summary>
        <returns>Ein IQueryable {Dynamic}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDocumentCollectionQuery (Uri databaseUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDocumentCollectionQuery(class System.Uri databaseUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentCollectionQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentCollectionQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDocumentCollectionQuery (databaseUri, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">Der URI mit der Datenbank.</param>
        <param name="querySpec">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die eine Abfrage für dokumentauflistungen im Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDocumentCollectionQuery (Uri databaseUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDocumentCollectionQuery(class System.Uri databaseUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentCollectionQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentCollectionQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDocumentCollectionQuery (databaseUri, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">Der URI mit der Datenbank.</param>
        <param name="sqlExpression">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die eine Abfrage für dokumentauflistungen im Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Document&gt; CreateDocumentQuery (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Document&gt; CreateDocumentQuery(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Document&gt;" Usage="iDocumentClient.CreateDocumentQuery (collectionLink, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Document&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">der Link auf die übergeordnete Dokument-Auflistung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Dokumente unter einer Auflistung im Azure-Cosmos-DB-Dienst. Es gibt IOrderedQueryable {Dokument} zurück.
            </summary>
        <returns>Ein IOrderedQueryable {Dokument}, die die Abfrage ausgewertet werden kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Document&gt; CreateDocumentQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Document&gt; CreateDocumentQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Document&gt;" Usage="iDocumentClient.CreateDocumentQuery (documentCollectionUri, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Document&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der Dokument-Auflistung.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die eine Abfrage für Dokumente im Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDocumentQuery (string collectionLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDocumentQuery(string collectionLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDocumentQuery (collectionLink, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">der Link auf die übergeordnete Dokument-Auflistung.</param>
        <param name="querySpec">Die SqlQuerySpec-Instanz, die die SQL-Ausdruck enthält.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Dokumente unter einer Auflistung in der Azure-Cosmos-DB-Dienst mit einer SQL-Anweisung, die parametrisierte Werte. Es gibt eine IQueryable {Dynamic} zurück.
            Weitere Informationen zum Vorbereiten von SQL-Anweisungen mit parametrisierte Werte finden Sie unter <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />.
            </summary>
        <returns>ein IQueryable {dynamische&gt; können, die die Abfrage ausgewertet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDocumentQuery (string collectionLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDocumentQuery(string collectionLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDocumentQuery (collectionLink, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">der Link auf die übergeordnete Dokument-Auflistung.</param>
        <param name="sqlExpression">Die SQL-Anweisung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Dokumente unter einer Auflistung in der Azure-Cosmos-DB-Dienst mit einer SQL­Anweisung. Es gibt eine IQueryable {Dynamic} zurück.
            </summary>
        <returns>ein IQueryable {dynamische&gt; können, die die Abfrage ausgewertet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDocumentQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDocumentQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDocumentQuery (documentCollectionUri, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der Dokument-Auflistung.</param>
        <param name="querySpec">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die eine Abfrage für Dokumente im Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDocumentQuery (Uri documentCollectionUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDocumentQuery(class System.Uri documentCollectionUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDocumentQuery (documentCollectionUri, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der Dokument-Auflistung.</param>
        <param name="sqlExpression">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die eine Abfrage für Dokumente im Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;T&gt; CreateDocumentQuery&lt;T&gt; (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;!!T&gt; CreateDocumentQuery&lt;T&gt;(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery``1(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateDocumentQuery (collectionLink, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">Der Typ des Objekts Abfragen.</typeparam>
        <param name="collectionLink">Der Link auf die Ressource der übergeordneten Auflistung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Dokumente unter einer Auflistung im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein IOrderedQueryable {T}, die die Abfrage ausgewertet werden kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;T&gt; CreateDocumentQuery&lt;T&gt; (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;!!T&gt; CreateDocumentQuery&lt;T&gt;(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery``1(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateDocumentQuery (documentCollectionUri, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">Der Typ des Objekts Abfragen.</typeparam>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die eine Abfrage für Dokumente im Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; CreateDocumentQuery&lt;T&gt; (string collectionLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!T&gt; CreateDocumentQuery&lt;T&gt;(string collectionLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery``1(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateDocumentQuery (collectionLink, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">Der Typ des Objekts Abfragen.</typeparam>
        <param name="collectionLink">der Link auf die übergeordnete Dokument-Auflistung.</param>
        <param name="querySpec">Die SqlQuerySpec-Instanz, die die SQL-Ausdruck enthält.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Dokumente unter einer Auflistung in der Azure-Cosmos-DB-Dienst mit einer SQL-Anweisung, die parametrisierte Werte. Es gibt eine IQueryable {T} zurück.
             Weitere Informationen zum Vorbereiten von SQL-Anweisungen mit parametrisierte Werte finden Sie unter <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />.
            </summary>
        <returns>Ein IQueryable {T}, die die Abfrage ausgewertet werden kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; CreateDocumentQuery&lt;T&gt; (string collectionLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!T&gt; CreateDocumentQuery&lt;T&gt;(string collectionLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery``1(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateDocumentQuery (collectionLink, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">Der Typ des Objekts Abfragen.</typeparam>
        <param name="collectionLink">Die Verknüpfung der übergeordneten Auflistung.</param>
        <param name="sqlExpression">Die SQL-Anweisung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Dokumente unter einer Auflistung in der Azure-Cosmos-DB-Dienst mit einer SQL­Anweisung. Es gibt eine IQueryable {T} zurück.
            </summary>
        <returns>Ein IQueryable {T}, die die Abfrage ausgewertet werden kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; CreateDocumentQuery&lt;T&gt; (Uri documentCollectionUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!T&gt; CreateDocumentQuery&lt;T&gt;(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery``1(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateDocumentQuery (documentCollectionUri, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">Der Typ des Objekts Abfragen.</typeparam>
        <param name="documentCollectionUri">Der URI der Dokument-Auflistung.</param>
        <param name="querySpec">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die eine Abfrage für Dokumente im Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; CreateDocumentQuery&lt;T&gt; (Uri documentCollectionUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!T&gt; CreateDocumentQuery&lt;T&gt;(class System.Uri documentCollectionUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery``1(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateDocumentQuery (documentCollectionUri, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">Der Typ des Objekts Abfragen.</typeparam>
        <param name="documentCollectionUri">Der URI der Dokument-Auflistung.</param>
        <param name="sqlExpression">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die eine Abfrage für Dokumente im Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOfferQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Offer&gt; CreateOfferQuery (Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Offer&gt; CreateOfferQuery(class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateOfferQuery(Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateOfferQuery : Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Offer&gt;" Usage="iDocumentClient.CreateOfferQuery feedOptions" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Offer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Angebote unter einem Azure-Cosmos-DB-Dienstkonto. Es gibt IOrderedQueryable {Offer} zurück.
            </summary>
        <returns>Ein IOrderedQueryable {Offer}, die die Abfrage ausgewertet werden kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOfferQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateOfferQuery (Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateOfferQuery(class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateOfferQuery(Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateOfferQuery : Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateOfferQuery (querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="querySpec">Die SqlQuerySpec-Instanz, die die SQL-Ausdruck enthält.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Angebote unter einem Azure-Cosmos-DB-Dienstkonto parametrisierte Werte mit einer SQL-Anweisung. Es gibt eine IQueryable {Dynamic} zurück.
            Weitere Informationen zum Vorbereiten von SQL-Anweisungen mit parametrisierte Werte finden Sie unter <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />.
            </summary>
        <returns>ein IQueryable {Dynamic}, die die Abfrage ausgewertet werden kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOfferQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateOfferQuery (string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateOfferQuery(string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateOfferQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateOfferQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateOfferQuery (sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="sqlExpression">Die SQL-Anweisung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Angebote unter einem Azure-Cosmos-DB-Dienstkonto mit einer SQL­Anweisung. Es gibt IQueryable {dynamische} zurück.
            </summary>
        <returns>ein IQueryable {Dynamic}, die die Abfrage ausgewertet werden kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; CreatePermissionAsync (string userLink, Microsoft.Azure.Documents.Permission permission, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; CreatePermissionAsync(string userLink, class Microsoft.Azure.Documents.Permission permission, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreatePermissionAsync(System.String,Microsoft.Azure.Documents.Permission,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreatePermissionAsync : string * Microsoft.Azure.Documents.Permission * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.CreatePermissionAsync (userLink, permission, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userLink" Type="System.String" />
        <Parameter Name="permission" Type="Microsoft.Azure.Documents.Permission" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userLink">Die Verbindung des Benutzers, der die Berechtigung für erstellen. Beispiel: DBS/Db_rid/Benutzer/User_rid / </param>
        <param name="permission">Das <see cref="T:Microsoft.Azure.Documents.Permission" />-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Erstellt eine Berechtigung für ein Benutzerobjekt als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang enthält der erstellte darstellt <see cref="T:Microsoft.Azure.Documents.Permission" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; CreatePermissionAsync (Uri userUri, Microsoft.Azure.Documents.Permission permission, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; CreatePermissionAsync(class System.Uri userUri, class Microsoft.Azure.Documents.Permission permission, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreatePermissionAsync(System.Uri,Microsoft.Azure.Documents.Permission,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreatePermissionAsync : Uri * Microsoft.Azure.Documents.Permission * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.CreatePermissionAsync (userUri, permission, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="permission" Type="Microsoft.Azure.Documents.Permission" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">Der URI des Benutzers, der die Berechtigung für erstellen.</param>
        <param name="permission">Das <see cref="T:Microsoft.Azure.Documents.Permission" />-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Erstellt eine Berechtigung als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Permission&gt; CreatePermissionQuery (string permissionsLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Permission&gt; CreatePermissionQuery(string permissionsLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreatePermissionQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreatePermissionQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Permission&gt;" Usage="iDocumentClient.CreatePermissionQuery (permissionsLink, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Permission&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissionsLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="permissionsLink">Die Pfad-Link, um die Berechtigungen unter einem Benutzerkonto, z. B. Dbs/Db_rid/Benutzer/User_rid/Berechtigungen /.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für die Berechtigungen unter einem Benutzerkonto in der Azure-Cosmos-DB-Dienst. Es gibt IOrderedQueryable {Permission} zurück.
            </summary>
        <returns>Ein IOrderedQueryable {Permission}, die die Abfrage ausgewertet werden kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Permission&gt; CreatePermissionQuery (Uri userUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Permission&gt; CreatePermissionQuery(class System.Uri userUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreatePermissionQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreatePermissionQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Permission&gt;" Usage="iDocumentClient.CreatePermissionQuery (userUri, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Permission&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">Der URI des übergeordneten Benutzers.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die eine Abfrage für Berechtigungen im Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreatePermissionQuery (string permissionsLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreatePermissionQuery(string permissionsLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreatePermissionQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreatePermissionQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreatePermissionQuery (permissionsLink, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissionsLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="permissionsLink">Die Pfad-Link, um die Berechtigungen unter einem Benutzerkonto, z. B. Dbs/Db_rid/Benutzer/User_rid/Berechtigungen /.</param>
        <param name="querySpec">Die SqlQuerySpec-Instanz, die die SQL-Ausdruck enthält.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für die Berechtigungen unter einem Benutzerkonto in der Azure-Cosmos-DB-Dienst mit einer SQL-Anweisung, die parametrisierte Werte. Es gibt eine IQueryable {Dynamic} zurück.
            Weitere Informationen zum Vorbereiten von SQL-Anweisungen mit parametrisierte Werte finden Sie unter <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />.
            </summary>
        <returns>ein IQueryable {Dynamic}, die die Abfrage ausgewertet werden kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreatePermissionQuery (string permissionsLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreatePermissionQuery(string permissionsLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreatePermissionQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreatePermissionQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreatePermissionQuery (permissionsLink, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissionsLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="permissionsLink">Die Pfad-Link, um die Berechtigungen unter einem Benutzerkonto, z. B. Dbs/Db_rid/Benutzer/User_rid/Berechtigungen /.</param>
        <param name="sqlExpression">Die SQL-Anweisung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für die Berechtigungen unter einem Benutzerkonto in der Azure-Cosmos-DB-Dienst mit einer SQL­Anweisung. Es gibt IQueryable {dynamische} zurück.
            </summary>
        <returns>ein IQueryable {Dynamic}, die die Abfrage ausgewertet werden kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreatePermissionQuery (Uri userUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreatePermissionQuery(class System.Uri userUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreatePermissionQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreatePermissionQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreatePermissionQuery (userUri, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">Der URI des übergeordneten Benutzers.</param>
        <param name="querySpec">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die eine Abfrage für Berechtigungen im Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreatePermissionQuery (Uri userUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreatePermissionQuery(class System.Uri userUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreatePermissionQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreatePermissionQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreatePermissionQuery (userUri, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">Der URI des übergeordneten Benutzers.</param>
        <param name="sqlExpression">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die eine Abfrage für Berechtigungen im Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; CreateStoredProcedureAsync (string collectionLink, Microsoft.Azure.Documents.StoredProcedure storedProcedure, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; CreateStoredProcedureAsync(string collectionLink, class Microsoft.Azure.Documents.StoredProcedure storedProcedure, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateStoredProcedureAsync(System.String,Microsoft.Azure.Documents.StoredProcedure,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateStoredProcedureAsync : string * Microsoft.Azure.Documents.StoredProcedure * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.CreateStoredProcedureAsync (collectionLink, storedProcedure, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="storedProcedure" Type="Microsoft.Azure.Documents.StoredProcedure" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link der Auflistung, die in die gespeicherte Prozedur zu erstellen. Beispiel: DBS/Db_rid/colls/Col_rid /</param>
        <param name="storedProcedure">Die <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> zu erstellenden Objekts.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Erstellt eine gespeicherte Prozedur als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Die <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> erstellte innerhalb einer <see cref="T:System.Threading.Tasks.Task" /> Objekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; CreateStoredProcedureAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.StoredProcedure storedProcedure, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; CreateStoredProcedureAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.StoredProcedure storedProcedure, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateStoredProcedureAsync(System.Uri,Microsoft.Azure.Documents.StoredProcedure,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateStoredProcedureAsync : Uri * Microsoft.Azure.Documents.StoredProcedure * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.CreateStoredProcedureAsync (documentCollectionUri, storedProcedure, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="storedProcedure" Type="Microsoft.Azure.Documents.StoredProcedure" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der Dokument-Auflistung in die gespeicherte Prozedur zu erstellen.</param>
        <param name="storedProcedure">Das <see cref="T:Microsoft.Azure.Documents.StoredProcedure" />-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Erstellt eine gespeicherte Prozedur als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.StoredProcedure&gt; CreateStoredProcedureQuery (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt; CreateStoredProcedureQuery(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateStoredProcedureQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateStoredProcedureQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.StoredProcedure&gt;" Usage="iDocumentClient.CreateStoredProcedureQuery (collectionLink, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.StoredProcedure&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link auf die Ressource der übergeordneten Auflistung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für gespeicherte Prozeduren unter einer Auflistung im Azure-Cosmos-DB-Dienst. Gibt ein IOrderedQueryable {StoredProcedure&gt;.
            </summary>
        <returns>Ein IOrderedQueryable {StoredProcedure}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.StoredProcedure&gt; CreateStoredProcedureQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt; CreateStoredProcedureQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateStoredProcedureQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateStoredProcedureQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.StoredProcedure&gt;" Usage="iDocumentClient.CreateStoredProcedureQuery (documentCollectionUri, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.StoredProcedure&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Die Methode zum Erstellen von Abfragen für gespeicherte Prozeduren in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateStoredProcedureQuery (string collectionLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateStoredProcedureQuery(string collectionLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateStoredProcedureQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateStoredProcedureQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateStoredProcedureQuery (collectionLink, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link auf die Ressource der übergeordneten Auflistung.</param>
        <param name="querySpec">Die SqlQuerySpec-Instanz, die die SQL-Ausdruck enthält.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für gespeicherte Prozeduren unter einer Auflistung in der Azure-Cosmos-DB-Dienst mit einer SQL­Anweisung, die parametrisierte Werte mit einer SQL-Anweisung. Es gibt eine IQueryable {Dynamic} zurück.
             Weitere Informationen zum Vorbereiten von SQL-Anweisungen mit parametrisierte Werte finden Sie unter <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />.
            </summary>
        <returns>Ein IQueryable {Dynamic}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateStoredProcedureQuery (string collectionLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateStoredProcedureQuery(string collectionLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateStoredProcedureQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateStoredProcedureQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateStoredProcedureQuery (collectionLink, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link auf die Ressource der übergeordneten Auflistung.</param>
        <param name="sqlExpression">Die SQL-Anweisung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für gespeicherte Prozeduren unter einer Auflistung in der Azure-Cosmos-DB-Dienst mit einer SQL­Anweisung. Es gibt eine IQueryable {Dynamic} zurück.
            </summary>
        <returns>Ein IQueryable {Dynamic}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateStoredProcedureQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateStoredProcedureQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateStoredProcedureQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateStoredProcedureQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateStoredProcedureQuery (documentCollectionUri, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="querySpec">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Die Methode zum Erstellen von Abfragen für gespeicherte Prozeduren in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateStoredProcedureQuery (Uri documentCollectionUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateStoredProcedureQuery(class System.Uri documentCollectionUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateStoredProcedureQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateStoredProcedureQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateStoredProcedureQuery (documentCollectionUri, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="sqlExpression">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Die Methode zum Erstellen von Abfragen für gespeicherte Prozeduren in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; CreateTriggerAsync (string collectionLink, Microsoft.Azure.Documents.Trigger trigger, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; CreateTriggerAsync(string collectionLink, class Microsoft.Azure.Documents.Trigger trigger, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateTriggerAsync(System.String,Microsoft.Azure.Documents.Trigger,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateTriggerAsync : string * Microsoft.Azure.Documents.Trigger * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.CreateTriggerAsync (collectionLink, trigger, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="trigger" Type="Microsoft.Azure.Documents.Trigger" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Die Verknüpfung der <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> in-Trigger erstellt. Beispiel: DBS/Db_rid/colls/Col_rid / </param>
        <param name="trigger">Die <see cref="T:Microsoft.Azure.Documents.Trigger" /> zu erstellenden Objekts.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Ein Trigger erstellt als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; CreateTriggerAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Trigger trigger, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; CreateTriggerAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Trigger trigger, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateTriggerAsync(System.Uri,Microsoft.Azure.Documents.Trigger,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateTriggerAsync : Uri * Microsoft.Azure.Documents.Trigger * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.CreateTriggerAsync (documentCollectionUri, trigger, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="trigger" Type="Microsoft.Azure.Documents.Trigger" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der Auflistung Dokument zur Erstellung des Triggers in.</param>
        <param name="trigger">Das <see cref="T:Microsoft.Azure.Documents.Trigger" />-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Ein Trigger erstellt als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Trigger&gt; CreateTriggerQuery (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Trigger&gt; CreateTriggerQuery(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateTriggerQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateTriggerQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Trigger&gt;" Usage="iDocumentClient.CreateTriggerQuery (collectionLink, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Trigger&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link auf die Ressource der übergeordneten Auflistung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Trigger unter einer Auflistung im Azure-Cosmos-DB-Dienst. Gibt ein IOrderedQueryable {Trigger&gt;.
            </summary>
        <returns>Ein IOrderedQueryable {Trigger}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Trigger&gt; CreateTriggerQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Trigger&gt; CreateTriggerQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateTriggerQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateTriggerQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Trigger&gt;" Usage="iDocumentClient.CreateTriggerQuery (documentCollectionUri, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Trigger&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die Abfrage für Trigger in der Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateTriggerQuery (string collectionLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateTriggerQuery(string collectionLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateTriggerQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateTriggerQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateTriggerQuery (collectionLink, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link auf die Ressource der übergeordneten Auflistung.</param>
        <param name="querySpec">Die SqlQuerySpec-Instanz, die die SQL-Ausdruck enthält.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Trigger unter einer Auflistung in der Azure-Cosmos-DB-Dienst mit einer SQL-Anweisung, die parametrisierte Werte. Es gibt eine IQueryable {Dynamic} zurück.
             Weitere Informationen zum Vorbereiten von SQL-Anweisungen mit parametrisierte Werte finden Sie unter <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />.
            </summary>
        <returns>Ein IQueryable {Trigger}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateTriggerQuery (string collectionLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateTriggerQuery(string collectionLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateTriggerQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateTriggerQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateTriggerQuery (collectionLink, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link auf die Ressource der übergeordneten Auflistung.</param>
        <param name="sqlExpression">Die SQL-Anweisung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Trigger unter einer Auflistung im Azure-Cosmos-DB-Dienst. Es gibt eine IQueryable {Dynamic} zurück.
            </summary>
        <returns>Ein IQueryable {Dynamic}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateTriggerQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateTriggerQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateTriggerQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateTriggerQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateTriggerQuery (documentCollectionUri, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="querySpec">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die Abfrage für Trigger in der Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateTriggerQuery (Uri documentCollectionUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateTriggerQuery(class System.Uri documentCollectionUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateTriggerQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateTriggerQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateTriggerQuery (documentCollectionUri, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="sqlExpression">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die Abfrage für Trigger in der Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; CreateUserAsync (string databaseLink, Microsoft.Azure.Documents.User user, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; CreateUserAsync(string databaseLink, class Microsoft.Azure.Documents.User user, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserAsync(System.String,Microsoft.Azure.Documents.User,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserAsync : string * Microsoft.Azure.Documents.User * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.CreateUserAsync (databaseLink, user, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="user" Type="Microsoft.Azure.Documents.User" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">Die Verknüpfung der Datenbank, die der Benutzer in erstellen. Beispiel: DBS/Db_rid / </param>
        <param name="user">Die <see cref="T:Microsoft.Azure.Documents.User" /> zu erstellenden Objekts.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Erstellt ein Benutzerobjekt als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Ein Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang enthält der erstellte darstellt <see cref="T:Microsoft.Azure.Documents.User" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; CreateUserAsync (Uri databaseUri, Microsoft.Azure.Documents.User user, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; CreateUserAsync(class System.Uri databaseUri, class Microsoft.Azure.Documents.User user, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserAsync(System.Uri,Microsoft.Azure.Documents.User,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserAsync : Uri * Microsoft.Azure.Documents.User * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.CreateUserAsync (databaseUri, user, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="user" Type="Microsoft.Azure.Documents.User" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">Der URI der Datenbank, die Benutzer in zu erstellen.</param>
        <param name="user">Das <see cref="T:Microsoft.Azure.Documents.User" />-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Erstellt einen Benutzer als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; CreateUserDefinedFunctionAsync (string collectionLink, Microsoft.Azure.Documents.UserDefinedFunction function, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; CreateUserDefinedFunctionAsync(string collectionLink, class Microsoft.Azure.Documents.UserDefinedFunction function, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserDefinedFunctionAsync(System.String,Microsoft.Azure.Documents.UserDefinedFunction,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateUserDefinedFunctionAsync (collectionLink As String, function As UserDefinedFunction, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member CreateUserDefinedFunctionAsync : string * Microsoft.Azure.Documents.UserDefinedFunction * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.CreateUserDefinedFunctionAsync (collectionLink, function, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Documents.UserDefinedFunction" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Die Verknüpfung der <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> zum Erstellen des Benutzers definierte Funktion in. Beispiel: DBS/Db_rid/colls/Col_rid / </param>
        <param name="function">Die <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> zu erstellenden Objekts.</param>
        <param name="options">(Optional) Alle <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Erstellt eine benutzerdefinierte Funktion als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Ein Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; CreateUserDefinedFunctionAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.UserDefinedFunction function, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; CreateUserDefinedFunctionAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.UserDefinedFunction function, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserDefinedFunctionAsync(System.Uri,Microsoft.Azure.Documents.UserDefinedFunction,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateUserDefinedFunctionAsync (documentCollectionUri As Uri, function As UserDefinedFunction, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member CreateUserDefinedFunctionAsync : Uri * Microsoft.Azure.Documents.UserDefinedFunction * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.CreateUserDefinedFunctionAsync (documentCollectionUri, function, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="function" Type="Microsoft.Azure.Documents.UserDefinedFunction" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der Auflistung Dokument zum Erstellen des Benutzers jeder benutzerdefinierten Funktion in.</param>
        <param name="function">Das <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Erstellt eine benutzerdefinierte Funktion als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt; CreateUserDefinedFunctionQuery (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt; CreateUserDefinedFunctionQuery(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserDefinedFunctionQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserDefinedFunctionQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;" Usage="iDocumentClient.CreateUserDefinedFunctionQuery (collectionLink, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link auf die Ressource der übergeordneten Auflistung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Udfs unter einer Auflistung im Azure-Cosmos-DB-Dienst. Gibt ein IOrderedQueryable {UserDefinedFunction&gt;.
            </summary>
        <returns>Ein IOrderedQueryable {UserDefinedFunction}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt; CreateUserDefinedFunctionQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt; CreateUserDefinedFunctionQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserDefinedFunctionQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserDefinedFunctionQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;" Usage="iDocumentClient.CreateUserDefinedFunctionQuery (documentCollectionUri, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die eine Abfrage für benutzerdefinierte Funktionen im Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateUserDefinedFunctionQuery (string collectionLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateUserDefinedFunctionQuery(string collectionLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserDefinedFunctionQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserDefinedFunctionQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateUserDefinedFunctionQuery (collectionLink, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link auf die Ressource der übergeordneten Auflistung.</param>
        <param name="querySpec">Die SqlQuerySpec-Instanz, die die SQL-Ausdruck enthält.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Udfs unter einer Auflistung in der Azure-Cosmos-DB-Dienst mit parametrisierte Werte. Es gibt eine IQueryable {Dynamic} zurück.
             Weitere Informationen zum Vorbereiten von SQL-Anweisungen mit parametrisierte Werte finden Sie unter <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />.
            </summary>
        <returns>Ein IQueryable {Dynamic}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>Verweisen Sie auf https://msdn.microsoft.com/en-us/library/azure/dn782250.aspx und http://azure.microsoft.com/documentation/articles/documentdb-sql-query/ Syntax und Beispiele.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />
        <altmember cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery" />
        <example>
            In diesem Beispiel unten Abfragen für benutzerdefinierte Funktionen von Id.
            <code language="c#"><![CDATA[
            var query = new SqlQuerySpec("SELECT * FROM udfs u WHERE u.id = @id", new SqlParameterCollection(new SqlParameter[] { new SqlParameter { Name = "@id", Value = "sqrt" }}));
            UserDefinedFunction udf = client.CreateUserDefinedFunctionQuery(collectionLink, query).AsEnumerable().FirstOrDefault();
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateUserDefinedFunctionQuery (string collectionLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateUserDefinedFunctionQuery(string collectionLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserDefinedFunctionQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserDefinedFunctionQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateUserDefinedFunctionQuery (collectionLink, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link auf die Ressource der übergeordneten Auflistung.</param>
        <param name="sqlExpression">Die SQL-Anweisung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Udfs unter einer Auflistung in der Azure-Cosmos-DB-Dienst mit einer SQL­Anweisung. Es gibt eine IQueryable {Dynamic} zurück.
            </summary>
        <returns>Ein IQueryable {Dynamic}, die die Abfrage mit der angegebenen SQL-Anweisung ergeben kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateUserDefinedFunctionQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateUserDefinedFunctionQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserDefinedFunctionQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserDefinedFunctionQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateUserDefinedFunctionQuery (documentCollectionUri, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="querySpec">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die eine Abfrage für benutzerdefinierte Funktionen im Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateUserDefinedFunctionQuery (Uri documentCollectionUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateUserDefinedFunctionQuery(class System.Uri documentCollectionUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserDefinedFunctionQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserDefinedFunctionQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateUserDefinedFunctionQuery (documentCollectionUri, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="sqlExpression">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Methode, die eine Abfrage für benutzerdefinierte Funktionen im Azure-Cosmos-DB-Dienst zu erstellen.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.User&gt; CreateUserQuery (string usersLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.User&gt; CreateUserQuery(string usersLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.User&gt;" Usage="iDocumentClient.CreateUserQuery (usersLink, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.User&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="usersLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="usersLink">Die Pfad-Link, um die Benutzer in einer Datenbank, z. B. Dbs/Db_rid/Benutzer /.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Benutzer unter einem Azure-Cosmos-DB-Dienst. Es gibt IOrderedQueryable {User} zurück.
            </summary>
        <returns>Ein IOrderedQueryable {User}, die die Abfrage ausgewertet werden kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.User&gt; CreateUserQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.User&gt; CreateUserQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.User&gt;" Usage="iDocumentClient.CreateUserQuery (documentCollectionUri, feedOptions)" />
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
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.User&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Die Methode zum Erstellen einer Abfrage für Benutzer in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateUserQuery (string usersLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateUserQuery(string usersLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateUserQuery (usersLink, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="usersLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="usersLink">Die Pfad-Link, um die Benutzer in einer Datenbank, z. B. Dbs/Db_rid/Benutzer /.</param>
        <param name="querySpec">Die SqlQuerySpec-Instanz, die die SQL-Ausdruck enthält.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Benutzer in einer Azure-Cosmos-DB-Datenbank, die parametrisierte Werte mit einer SQL-Anweisung. Es gibt eine IQueryable {Dynamic} zurück.
            Weitere Informationen zum Vorbereiten von SQL-Anweisungen mit parametrisierte Werte finden Sie unter <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />.
            </summary>
        <returns>ein IQueryable {dynamische&gt; können, die die Abfrage ausgewertet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateUserQuery (string usersLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateUserQuery(string usersLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateUserQuery (usersLink, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="usersLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="usersLink">Die Pfad-Link, um die Benutzer in einer Datenbank, z. B. Dbs/Db_rid/Benutzer /.</param>
        <param name="sqlExpression">Die SQL-Anweisung.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen finden Sie unter<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            Überladen. Diese Methode erstellt eine Abfrage für Benutzer unter einem Azure-Cosmos-DB-Dienst. Es gibt IQueryable {dynamisches} zurück.
            </summary>
        <returns>ein IQueryable {Dynamic}, die die Abfrage ausgewertet werden kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateUserQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateUserQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateUserQuery (documentCollectionUri, querySpec, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="querySpec">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Die Methode zum Erstellen einer Abfrage für Benutzer in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateUserQuery (Uri documentCollectionUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateUserQuery(class System.Uri documentCollectionUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateUserQuery (documentCollectionUri, sqlExpression, feedOptions)" />
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
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="sqlExpression">Die Sql-Abfrage.</param>
        <param name="feedOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für feed verarbeiten die Ergebnisse der Abfrage.</param>
        <summary>
            Die Methode zum Erstellen einer Abfrage für Benutzer in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Resultset der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; DeleteAttachmentAsync (string attachmentLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; DeleteAttachmentAsync(string attachmentLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteAttachmentAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAttachmentAsync (attachmentLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member DeleteAttachmentAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.DeleteAttachmentAsync (attachmentLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="attachmentLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="attachmentLink">Die Verknüpfung der <see cref="T:Microsoft.Azure.Documents.Attachment" /> zu löschen. Beispiel: DBS/Db_rid/colls/Col_rid/Dokumente/Doc_rid/Anlagen/Attachment_rid / </param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Löschen einer <see cref="T:Microsoft.Azure.Documents.Attachment" /> aus der Datenbank als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> enthält die Informationen über die Anforderung ausgegeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; DeleteAttachmentAsync (Uri attachmentUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; DeleteAttachmentAsync(class System.Uri attachmentUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteAttachmentAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAttachmentAsync (attachmentUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member DeleteAttachmentAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.DeleteAttachmentAsync (attachmentUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="attachmentUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="attachmentUri">Der URI der Anlage zu löschen.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Löschen einer Anlage als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteConflictAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt; DeleteConflictAsync (string conflictLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Conflict&gt;&gt; DeleteConflictAsync(string conflictLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteConflictAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteConflictAsync (conflictLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Conflict))" />
      <MemberSignature Language="F#" Value="abstract member DeleteConflictAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;" Usage="iDocumentClient.DeleteConflictAsync (conflictLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="conflictLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="conflictLink">Die Verknüpfung der <see cref="T:Microsoft.Azure.Documents.Conflict" /> zu löschen. Beispiel: DBS/Db_rid/colls/Coll_rid/Konflikte / </param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Löschen einer <see cref="T:Microsoft.Azure.Documents.Conflict" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> enthält die Informationen über die Anforderung ausgegeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteConflictAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt; DeleteConflictAsync (Uri conflictUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Conflict&gt;&gt; DeleteConflictAsync(class System.Uri conflictUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteConflictAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteConflictAsync (conflictUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Conflict))" />
      <MemberSignature Language="F#" Value="abstract member DeleteConflictAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;" Usage="iDocumentClient.DeleteConflictAsync (conflictUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="conflictUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="conflictUri">Der URI des Konflikts zu löschen.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Löschen eines Konflikts als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDatabaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt; DeleteDatabaseAsync (string databaseLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Database&gt;&gt; DeleteDatabaseAsync(string databaseLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteDatabaseAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteDatabaseAsync (databaseLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Database))" />
      <MemberSignature Language="F#" Value="abstract member DeleteDatabaseAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;" Usage="iDocumentClient.DeleteDatabaseAsync (databaseLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">Die Verknüpfung der <see cref="T:Microsoft.Azure.Documents.Database" /> zu löschen. Beispiel: DBS/Db_rid / </param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Löschen einer <see cref="T:Microsoft.Azure.Documents.Database" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> enthält die Informationen über die Anforderung ausgegeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDatabaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt; DeleteDatabaseAsync (Uri databaseUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Database&gt;&gt; DeleteDatabaseAsync(class System.Uri databaseUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteDatabaseAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteDatabaseAsync (databaseUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Database))" />
      <MemberSignature Language="F#" Value="abstract member DeleteDatabaseAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;" Usage="iDocumentClient.DeleteDatabaseAsync (databaseUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">Der URI der Datenbank zu löschen.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Löschen einer Datenbank als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; DeleteDocumentAsync (string documentLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; DeleteDocumentAsync(string documentLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteDocumentAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteDocumentAsync (documentLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member DeleteDocumentAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.DeleteDocumentAsync (documentLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">Die Verknüpfung der <see cref="T:Microsoft.Azure.Documents.Document" /> zu löschen. Beispiel: DBS/Db_rid/colls/Col_rid/Dokumente/Doc_rid / </param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Löschen einer <see cref="T:Microsoft.Azure.Documents.Document" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> enthält die Informationen über die Anforderung ausgegeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; DeleteDocumentAsync (Uri documentUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; DeleteDocumentAsync(class System.Uri documentUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteDocumentAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteDocumentAsync (documentUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member DeleteDocumentAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.DeleteDocumentAsync (documentUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">Der URI des Dokuments zu löschen.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Löschen eines Dokuments als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDocumentCollectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; DeleteDocumentCollectionAsync (string documentCollectionLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; DeleteDocumentCollectionAsync(string documentCollectionLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteDocumentCollectionAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteDocumentCollectionAsync (documentCollectionLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of DocumentCollection))" />
      <MemberSignature Language="F#" Value="abstract member DeleteDocumentCollectionAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.DeleteDocumentCollectionAsync (documentCollectionLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionLink">Die Verknüpfung der <see cref="T:Microsoft.Azure.Documents.Document" /> zu löschen. Beispiel: DBS/Db_rid/colls/Col_rid / </param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Löschen einer <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> enthält die Informationen über die Anforderung ausgegeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDocumentCollectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; DeleteDocumentCollectionAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; DeleteDocumentCollectionAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteDocumentCollectionAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteDocumentCollectionAsync (documentCollectionUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of DocumentCollection))" />
      <MemberSignature Language="F#" Value="abstract member DeleteDocumentCollectionAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.DeleteDocumentCollectionAsync (documentCollectionUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der Dokument-Auflistung gelöscht werden soll.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Eine Auflistung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst zu löschen.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletePermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; DeletePermissionAsync (string permissionLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; DeletePermissionAsync(string permissionLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeletePermissionAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeletePermissionAsync (permissionLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Permission))" />
      <MemberSignature Language="F#" Value="abstract member DeletePermissionAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.DeletePermissionAsync (permissionLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="permissionLink">Die Verknüpfung der <see cref="T:Microsoft.Azure.Documents.Permission" /> zu löschen. Beispiel: DBS/Db_rid/Benutzer/User_rid/Berechtigungen/Permission_rid / </param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Löschen einer <see cref="T:Microsoft.Azure.Documents.Permission" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> enthält die Informationen über die Anforderung ausgegeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletePermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; DeletePermissionAsync (Uri permissionUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; DeletePermissionAsync(class System.Uri permissionUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeletePermissionAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeletePermissionAsync (permissionUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Permission))" />
      <MemberSignature Language="F#" Value="abstract member DeletePermissionAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.DeletePermissionAsync (permissionUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="permissionUri">Der URI, der die Berechtigung zum Löschen.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Löschen Sie eine Berechtigung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; DeleteStoredProcedureAsync (string storedProcedureLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; DeleteStoredProcedureAsync(string storedProcedureLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteStoredProcedureAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteStoredProcedureAsync (storedProcedureLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of StoredProcedure))" />
      <MemberSignature Language="F#" Value="abstract member DeleteStoredProcedureAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.DeleteStoredProcedureAsync (storedProcedureLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storedProcedureLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="storedProcedureLink">Die Verknüpfung der <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> zu löschen. Beispiel: DBS/Db_rid/colls/Col_rid/Sprocs/Sproc_rid / </param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Löschen einer <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> enthält die Informationen über die Anforderung ausgegeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; DeleteStoredProcedureAsync (Uri storedProcedureUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; DeleteStoredProcedureAsync(class System.Uri storedProcedureUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteStoredProcedureAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteStoredProcedureAsync (storedProcedureUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of StoredProcedure))" />
      <MemberSignature Language="F#" Value="abstract member DeleteStoredProcedureAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.DeleteStoredProcedureAsync (storedProcedureUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storedProcedureUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="storedProcedureUri">Der URI der gespeicherten Prozedur zu löschen.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Löschen einer gespeicherten Prozedur als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; DeleteTriggerAsync (string triggerLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; DeleteTriggerAsync(string triggerLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteTriggerAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteTriggerAsync (triggerLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Trigger))" />
      <MemberSignature Language="F#" Value="abstract member DeleteTriggerAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.DeleteTriggerAsync (triggerLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="triggerLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="triggerLink">Die Verknüpfung der <see cref="T:Microsoft.Azure.Documents.Trigger" /> zu löschen. Beispiel: DBS/Db_rid/colls/Col_rid/Triggers/Trigger_rid / </param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Löschen einer <see cref="T:Microsoft.Azure.Documents.Trigger" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> enthält die Informationen über die Anforderung ausgegeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; DeleteTriggerAsync (Uri triggerUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; DeleteTriggerAsync(class System.Uri triggerUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteTriggerAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteTriggerAsync (triggerUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Trigger))" />
      <MemberSignature Language="F#" Value="abstract member DeleteTriggerAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.DeleteTriggerAsync (triggerUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="triggerUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="triggerUri">Der URI des Triggers zu löschen.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Löschen eines Triggers als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; DeleteUserAsync (string userLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; DeleteUserAsync(string userLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteUserAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteUserAsync (userLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of User))" />
      <MemberSignature Language="F#" Value="abstract member DeleteUserAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.DeleteUserAsync (userLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userLink">Die Verknüpfung der <see cref="T:Microsoft.Azure.Documents.User" /> zu löschen. Beispiel: DBS/Db_rid/Benutzer/User_rid / </param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Löschen einer <see cref="T:Microsoft.Azure.Documents.User" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> enthält die Informationen über die Anforderung ausgegeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; DeleteUserAsync (Uri userUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; DeleteUserAsync(class System.Uri userUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteUserAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteUserAsync (userUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of User))" />
      <MemberSignature Language="F#" Value="abstract member DeleteUserAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.DeleteUserAsync (userUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">Der URI des Benutzers zu löschen.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Löschen eines Benutzers als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; DeleteUserDefinedFunctionAsync (string functionLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; DeleteUserDefinedFunctionAsync(string functionLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteUserDefinedFunctionAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteUserDefinedFunctionAsync (functionLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member DeleteUserDefinedFunctionAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.DeleteUserDefinedFunctionAsync (functionLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="functionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="functionLink">Die Verknüpfung der <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> zu löschen. Beispiel: DBS/Db_rid/colls/Col_rid/UDF/Udf_rid / </param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Löschen einer <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> enthält die Informationen über die Anforderung ausgegeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; DeleteUserDefinedFunctionAsync (Uri functionUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; DeleteUserDefinedFunctionAsync(class System.Uri functionUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteUserDefinedFunctionAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteUserDefinedFunctionAsync (functionUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member DeleteUserDefinedFunctionAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.DeleteUserDefinedFunctionAsync (functionUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="functionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="functionUri">Der URI des Benutzers definiert Funktion löschen.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Löschen Sie eine benutzerdefinierte Funktion als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteStoredProcedureAsync&lt;TValue&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;&gt; ExecuteStoredProcedureAsync&lt;TValue&gt; (string storedProcedureLink, params object[] procedureParams);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.StoredProcedureResponse`1&lt;!!TValue&gt;&gt; ExecuteStoredProcedureAsync&lt;TValue&gt;(string storedProcedureLink, object[] procedureParams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ExecuteStoredProcedureAsync``1(System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteStoredProcedureAsync(Of TValue) (storedProcedureLink As String, ParamArray procedureParams As Object()) As Task(Of StoredProcedureResponse(Of TValue))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteStoredProcedureAsync : string * obj[] -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;&gt;" Usage="iDocumentClient.ExecuteStoredProcedureAsync (storedProcedureLink, procedureParams)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TValue" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="storedProcedureLink" Type="System.String" />
        <Parameter Name="procedureParams" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="TValue">Der Typ des Rückgabewerts der gespeicherten Prozedur.</typeparam>
        <param name="storedProcedureLink">Den Link, um die gespeicherte Prozedur ausgeführt werden soll.</param>
        <param name="procedureParams">(Optional) Ein Array von dynamischen Objekten, das die Parameter für die gespeicherte Prozedur darstellt.</param>
        <summary>
            Führt eine gespeicherte Prozedur für eine Auflistung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang, der alle Antworten enthalten würde darstellt, die in der gespeicherten Prozedur festgelegt werden.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="storedProcedureLink" /> nicht festgelegt ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="ExecuteStoredProcedureAsync&lt;TValue&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;&gt; ExecuteStoredProcedureAsync&lt;TValue&gt; (Uri storedProcedureUri, params object[] procedureParams);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.StoredProcedureResponse`1&lt;!!TValue&gt;&gt; ExecuteStoredProcedureAsync&lt;TValue&gt;(class System.Uri storedProcedureUri, object[] procedureParams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ExecuteStoredProcedureAsync``1(System.Uri,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteStoredProcedureAsync(Of TValue) (storedProcedureUri As Uri, ParamArray procedureParams As Object()) As Task(Of StoredProcedureResponse(Of TValue))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteStoredProcedureAsync : Uri * obj[] -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;&gt;" Usage="iDocumentClient.ExecuteStoredProcedureAsync (storedProcedureUri, procedureParams)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TValue" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="storedProcedureUri" Type="System.Uri" />
        <Parameter Name="procedureParams" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="TValue">Der Typ des Rückgabewerts der gespeicherten Prozedur.</typeparam>
        <param name="storedProcedureUri">Der URI der gespeicherten Prozedur ausgeführt werden.</param>
        <param name="procedureParams">Die Parameter für die Ausführung der gespeicherten Prozedur.</param>
        <summary>
            Führt eine gespeicherte Prozedur für eine Auflistung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteStoredProcedureAsync&lt;TValue&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;&gt; ExecuteStoredProcedureAsync&lt;TValue&gt; (string storedProcedureLink, Microsoft.Azure.Documents.Client.RequestOptions options, params object[] procedureParams);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.StoredProcedureResponse`1&lt;!!TValue&gt;&gt; ExecuteStoredProcedureAsync&lt;TValue&gt;(string storedProcedureLink, class Microsoft.Azure.Documents.Client.RequestOptions options, object[] procedureParams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ExecuteStoredProcedureAsync``1(System.String,Microsoft.Azure.Documents.Client.RequestOptions,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteStoredProcedureAsync(Of TValue) (storedProcedureLink As String, options As RequestOptions, ParamArray procedureParams As Object()) As Task(Of StoredProcedureResponse(Of TValue))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteStoredProcedureAsync : string * Microsoft.Azure.Documents.Client.RequestOptions * obj[] -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;&gt;" Usage="iDocumentClient.ExecuteStoredProcedureAsync (storedProcedureLink, options, procedureParams)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TValue" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="storedProcedureLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
        <Parameter Name="procedureParams" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="TValue">Der Typ des Rückgabewerts der gespeicherten Prozedur.</typeparam>
        <param name="storedProcedureLink">Den Link, um die gespeicherte Prozedur ausgeführt werden soll.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <param name="procedureParams">(Optional) Ein Array von dynamischen Objekten, das die Parameter für die gespeicherte Prozedur darstellt.</param>
        <summary>
            Führt eine gespeicherte Prozedur für eine partitionierte Sammlung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst die Angabe einer Zielpartition.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang, der alle Antworten enthalten würde darstellt, die in der gespeicherten Prozedur festgelegt werden.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="storedProcedureLink" /> nicht festgelegt ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="ExecuteStoredProcedureAsync&lt;TValue&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;&gt; ExecuteStoredProcedureAsync&lt;TValue&gt; (Uri storedProcedureUri, Microsoft.Azure.Documents.Client.RequestOptions options, params object[] procedureParams);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.StoredProcedureResponse`1&lt;!!TValue&gt;&gt; ExecuteStoredProcedureAsync&lt;TValue&gt;(class System.Uri storedProcedureUri, class Microsoft.Azure.Documents.Client.RequestOptions options, object[] procedureParams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ExecuteStoredProcedureAsync``1(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteStoredProcedureAsync(Of TValue) (storedProcedureUri As Uri, options As RequestOptions, ParamArray procedureParams As Object()) As Task(Of StoredProcedureResponse(Of TValue))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteStoredProcedureAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions * obj[] -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;&gt;" Usage="iDocumentClient.ExecuteStoredProcedureAsync (storedProcedureUri, options, procedureParams)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TValue" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="storedProcedureUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
        <Parameter Name="procedureParams" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="TValue">Der Typ des Rückgabewerts der gespeicherten Prozedur.</typeparam>
        <param name="storedProcedureUri">Der URI der gespeicherten Prozedur ausgeführt werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <param name="procedureParams">Die Parameter für die Ausführung der gespeicherten Prozedur.</param>
        <summary>
            Führt eine gespeicherte Prozedur für eine Auflistung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatabaseAccountAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.DatabaseAccount&gt; GetDatabaseAccountAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.DatabaseAccount&gt; GetDatabaseAccountAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.GetDatabaseAccountAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDatabaseAccountAsync () As Task(Of DatabaseAccount)" />
      <MemberSignature Language="F#" Value="abstract member GetDatabaseAccountAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.DatabaseAccount&gt;" Usage="iDocumentClient.GetDatabaseAccountAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.DatabaseAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Lesen der <see cref="T:Microsoft.Azure.Documents.DatabaseAccount" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="T:Microsoft.Azure.Documents.DatabaseAccount" /> eingebunden in eine <see cref="T:System.Threading.Tasks.Task" /> Objekt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; ReadAttachmentAsync (string attachmentLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; ReadAttachmentAsync(string attachmentLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadAttachmentAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAttachmentAsync (attachmentLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member ReadAttachmentAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.ReadAttachmentAsync (attachmentLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="attachmentLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="attachmentLink">Der Link auf die Anlage gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.Attachment" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Attachment" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; ReadAttachmentAsync (Uri attachmentUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; ReadAttachmentAsync(class System.Uri attachmentUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadAttachmentAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAttachmentAsync (attachmentUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member ReadAttachmentAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.ReadAttachmentAsync (attachmentUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="attachmentUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="attachmentUri">Ein URI, der die Attachment-Ressource gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.Attachment" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Attachment" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAttachmentFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; ReadAttachmentFeedAsync (string documentLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; ReadAttachmentFeedAsync(string documentLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadAttachmentFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAttachmentFeedAsync (documentLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member ReadAttachmentFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.ReadAttachmentFeedAsync (documentLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">Die Verknüpfung der Ressource übergeordnete Dokument.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />für diese Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) des <see cref="T:Microsoft.Azure.Documents.Attachment" /> für ein Dokument als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Attachment" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAttachmentFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; ReadAttachmentFeedAsync (Uri documentUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; ReadAttachmentFeedAsync(class System.Uri documentUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadAttachmentFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAttachmentFeedAsync (documentUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member ReadAttachmentFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.ReadAttachmentFeedAsync (documentUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">Der URI, der das übergeordnete Dokument.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für die Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) von Anlagen für ein Dokument als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadConflictAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt; ReadConflictAsync (string conflictLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Conflict&gt;&gt; ReadConflictAsync(string conflictLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadConflictAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadConflictAsync (conflictLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Conflict))" />
      <MemberSignature Language="F#" Value="abstract member ReadConflictAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;" Usage="iDocumentClient.ReadConflictAsync (conflictLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="conflictLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="conflictLink">Der Link zum Konflikt gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.Conflict" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Conflict" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadConflictAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt; ReadConflictAsync (Uri conflictUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Conflict&gt;&gt; ReadConflictAsync(class System.Uri conflictUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadConflictAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadConflictAsync (conflictUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Conflict))" />
      <MemberSignature Language="F#" Value="abstract member ReadConflictAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;" Usage="iDocumentClient.ReadConflictAsync (conflictUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="conflictUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="conflictUri">Ein URI mit der Konflikt Ressource gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.Conflict" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Conflict" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadConflictFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt; ReadConflictFeedAsync (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Conflict&gt;&gt; ReadConflictFeedAsync(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadConflictFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadConflictFeedAsync (collectionLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Conflict))" />
      <MemberSignature Language="F#" Value="abstract member ReadConflictFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;" Usage="iDocumentClient.ReadConflictFeedAsync (collectionLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link von der übergeordneten Auflistung dokumentressource.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />für diese Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) des <see cref="T:Microsoft.Azure.Documents.Conflict" /> für eine Auflistung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Conflict" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadConflictFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt; ReadConflictFeedAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Conflict&gt;&gt; ReadConflictFeedAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadConflictFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadConflictFeedAsync (documentCollectionUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Conflict))" />
      <MemberSignature Language="F#" Value="abstract member ReadConflictFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;" Usage="iDocumentClient.ReadConflictFeedAsync (documentCollectionUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für die Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) von Konflikten für eine Auflistung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDatabaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt; ReadDatabaseAsync (string databaseLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Database&gt;&gt; ReadDatabaseAsync(string databaseLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDatabaseAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDatabaseAsync (databaseLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Database))" />
      <MemberSignature Language="F#" Value="abstract member ReadDatabaseAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;" Usage="iDocumentClient.ReadDatabaseAsync (databaseLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">Die Verknüpfung der Ressource gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.Database" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Database" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDatabaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt; ReadDatabaseAsync (Uri databaseUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Database&gt;&gt; ReadDatabaseAsync(class System.Uri databaseUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDatabaseAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDatabaseAsync (databaseUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Database))" />
      <MemberSignature Language="F#" Value="abstract member ReadDatabaseAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;" Usage="iDocumentClient.ReadDatabaseAsync (databaseUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">Ein URI mit der Datenbank-Ressource gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.Database" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Database" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDatabaseFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt; ReadDatabaseFeedAsync (Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Database&gt;&gt; ReadDatabaseFeedAsync(class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDatabaseFeedAsync(Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDatabaseFeedAsync (Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Database))" />
      <MemberSignature Language="F#" Value="abstract member ReadDatabaseFeedAsync : Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;" Usage="iDocumentClient.ReadDatabaseFeedAsync options" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />für diese Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) des <see cref="T:Microsoft.Azure.Documents.Database" /> für ein Konto der Datenbank als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Database" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; ReadDocumentAsync (string documentLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; ReadDocumentAsync(string documentLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDocumentAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDocumentAsync (documentLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member ReadDocumentAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.ReadDocumentAsync (documentLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">Der Link für das Dokument gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.Document" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Document" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; ReadDocumentAsync (Uri documentUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; ReadDocumentAsync(class System.Uri documentUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDocumentAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDocumentAsync (documentUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member ReadDocumentAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.ReadDocumentAsync (documentUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">Ein URI, der dokumentressource gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.Document" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Document" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDocumentCollectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReadDocumentCollectionAsync (string documentCollectionLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReadDocumentCollectionAsync(string documentCollectionLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDocumentCollectionAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDocumentCollectionAsync (documentCollectionLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of DocumentCollection))" />
      <MemberSignature Language="F#" Value="abstract member ReadDocumentCollectionAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.ReadDocumentCollectionAsync (documentCollectionLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionLink">Der Link für die DocumentCollection gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDocumentCollectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReadDocumentCollectionAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReadDocumentCollectionAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDocumentCollectionAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDocumentCollectionAsync (documentCollectionUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of DocumentCollection))" />
      <MemberSignature Language="F#" Value="abstract member ReadDocumentCollectionAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.ReadDocumentCollectionAsync (documentCollectionUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Ein URI mit der Ressource DocumentCollection gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDocumentCollectionFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReadDocumentCollectionFeedAsync (string databaseLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReadDocumentCollectionFeedAsync(string databaseLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDocumentCollectionFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDocumentCollectionFeedAsync (databaseLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of DocumentCollection))" />
      <MemberSignature Language="F#" Value="abstract member ReadDocumentCollectionFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.ReadDocumentCollectionFeedAsync (databaseLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">Der Link für die Ressource der übergeordneten Datenbank.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />für diese Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) des <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> für eine Datenbank als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDocumentCollectionFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReadDocumentCollectionFeedAsync (Uri databaseUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReadDocumentCollectionFeedAsync(class System.Uri databaseUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDocumentCollectionFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDocumentCollectionFeedAsync (databaseUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of DocumentCollection))" />
      <MemberSignature Language="F#" Value="abstract member ReadDocumentCollectionFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.ReadDocumentCollectionFeedAsync (databaseUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">Der URI der übergeordneten Datenbank.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für die Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) von Sammlungen für eine Datenbank als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDocumentFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;dynamic&gt;&gt; ReadDocumentFeedAsync (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;object&gt;&gt; ReadDocumentFeedAsync(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDocumentFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDocumentFeedAsync (collectionLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Object))" />
      <MemberSignature Language="F#" Value="abstract member ReadDocumentFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;obj&gt;&gt;" Usage="iDocumentClient.ReadDocumentFeedAsync (collectionLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link von der übergeordneten Auflistung dokumentressource.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />für diese Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) von Dokumenten für eine angegebene Sammlung in der Azure-Cosmos-DB-Dienst an. Dies dauert gibt eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> eine aufzählbare Liste von dynamischen Objekten enthalten.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> mit dynamischen Objekten, die die Elemente im Feed darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDocumentFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;dynamic&gt;&gt; ReadDocumentFeedAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;object&gt;&gt; ReadDocumentFeedAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDocumentFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDocumentFeedAsync (documentCollectionUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Object))" />
      <MemberSignature Language="F#" Value="abstract member ReadDocumentFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;obj&gt;&gt;" Usage="iDocumentClient.ReadDocumentFeedAsync (documentCollectionUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für die Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) von Dokumenten für eine Auflistung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEndpoint">
      <MemberSignature Language="C#" Value="public Uri ReadEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ReadEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IDocumentClient.ReadEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadEndpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.ReadEndpoint : Uri" Usage="Microsoft.Azure.Documents.IDocumentClient.ReadEndpoint" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den aktuellen read-Endpunkt auf Grundlage der Verfügbarkeit und der Einstellung in der Azure-Cosmos-DB-Dienst ausgewählt wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadMediaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt; ReadMediaAsync (string mediaLink);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.MediaResponse&gt; ReadMediaAsync(string mediaLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadMediaAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadMediaAsync (mediaLink As String) As Task(Of MediaResponse)" />
      <MemberSignature Language="F#" Value="abstract member ReadMediaAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt;" Usage="iDocumentClient.ReadMediaAsync mediaLink" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mediaLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="mediaLink">Der Link für das Medium zu lesen. Beispiel: / Medien/media_rid</param>
        <summary>
            Ruft ab, der Inhalt der angegebenen Anlage (aka Medien) im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="mediaLink" /> nicht festgelegt ist.</exception>
        <exception cref="T:System.ArgumentException">Wenn <paramref name="mediaLink" /> befindet sich nicht in Form von /medias/ {MediaId}.</exception>
      </Docs>
    </Member>
    <Member MemberName="ReadMediaMetadataAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt; ReadMediaMetadataAsync (string mediaLink);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.MediaResponse&gt; ReadMediaMetadataAsync(string mediaLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadMediaMetadataAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadMediaMetadataAsync (mediaLink As String) As Task(Of MediaResponse)" />
      <MemberSignature Language="F#" Value="abstract member ReadMediaMetadataAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt;" Usage="iDocumentClient.ReadMediaMetadataAsync mediaLink" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mediaLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="mediaLink">Der Link für zum Lesen von Metadaten für das Medium. Beispiel: / Medien/media_rid </param>
        <summary>
            Ruft den Inhalt der angegebenen Anlage (aka Medien) zugeordneten Metadaten als asynchronen Vorgang im Azure-Cosmos-DB-Dienst ab.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="mediaLink" /> nicht festgelegt ist.</exception>
        <exception cref="T:System.ArgumentException">Wenn <paramref name="mediaLink" /> befindet sich nicht in Form von /medias/ {MediaId}.</exception>
      </Docs>
    </Member>
    <Member MemberName="ReadOfferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt; ReadOfferAsync (string offerLink);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Offer&gt;&gt; ReadOfferAsync(string offerLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadOfferAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadOfferAsync (offerLink As String) As Task(Of ResourceResponse(Of Offer))" />
      <MemberSignature Language="F#" Value="abstract member ReadOfferAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt;" Usage="iDocumentClient.ReadOfferAsync offerLink" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="offerLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="offerLink">Der Link, um das Angebot gelesen werden.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.Offer" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Offer" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadOffersFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt; ReadOffersFeedAsync (Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Offer&gt;&gt; ReadOffersFeedAsync(class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadOffersFeedAsync(Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadOffersFeedAsync (Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Offer))" />
      <MemberSignature Language="F#" Value="abstract member ReadOffersFeedAsync : Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt;" Usage="iDocumentClient.ReadOffersFeedAsync options" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />für diese Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) des <see cref="T:Microsoft.Azure.Documents.Offer" /> für ein Konto der Datenbank als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Offer" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadPermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; ReadPermissionAsync (string permissionLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; ReadPermissionAsync(string permissionLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadPermissionAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadPermissionAsync (permissionLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Permission))" />
      <MemberSignature Language="F#" Value="abstract member ReadPermissionAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.ReadPermissionAsync (permissionLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="permissionLink">Der Link für die Berechtigungsressource, die gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.Permission" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Permission" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadPermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; ReadPermissionAsync (Uri permissionUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; ReadPermissionAsync(class System.Uri permissionUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadPermissionAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadPermissionAsync (permissionUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Permission))" />
      <MemberSignature Language="F#" Value="abstract member ReadPermissionAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.ReadPermissionAsync (permissionUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="permissionUri">Ein URI mit der Berechtigungsressource gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.Permission" /> Ressource als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Permission" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadPermissionFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; ReadPermissionFeedAsync (string userLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; ReadPermissionFeedAsync(string userLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadPermissionFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadPermissionFeedAsync (userLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Permission))" />
      <MemberSignature Language="F#" Value="abstract member ReadPermissionFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.ReadPermissionFeedAsync (userLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="userLink">Der Link von der übergeordneten Ressource "User".</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />für diese Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) des <see cref="T:Microsoft.Azure.Documents.Permission" /> für einen Benutzer als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Permission" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadPermissionFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; ReadPermissionFeedAsync (Uri userUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; ReadPermissionFeedAsync(class System.Uri userUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadPermissionFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadPermissionFeedAsync (userUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Permission))" />
      <MemberSignature Language="F#" Value="abstract member ReadPermissionFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.ReadPermissionFeedAsync (userUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">Der URI des übergeordneten Benutzers.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für die Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) von Berechtigungen für einen Benutzer als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReadStoredProcedureAsync (string storedProcedureLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReadStoredProcedureAsync(string storedProcedureLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadStoredProcedureAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadStoredProcedureAsync (storedProcedureLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of StoredProcedure))" />
      <MemberSignature Language="F#" Value="abstract member ReadStoredProcedureAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.ReadStoredProcedureAsync (storedProcedureLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storedProcedureLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="storedProcedureLink">Der Link von der gespeicherten Prozedur gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReadStoredProcedureAsync (Uri storedProcedureUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReadStoredProcedureAsync(class System.Uri storedProcedureUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadStoredProcedureAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadStoredProcedureAsync (storedProcedureUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of StoredProcedure))" />
      <MemberSignature Language="F#" Value="abstract member ReadStoredProcedureAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.ReadStoredProcedureAsync (storedProcedureUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storedProcedureUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="storedProcedureUri">Ein URI für den StoredProcedure-Ressource gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStoredProcedureFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReadStoredProcedureFeedAsync (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReadStoredProcedureFeedAsync(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadStoredProcedureFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadStoredProcedureFeedAsync (collectionLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of StoredProcedure))" />
      <MemberSignature Language="F#" Value="abstract member ReadStoredProcedureFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.ReadStoredProcedureFeedAsync (collectionLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link von der übergeordneten Auflistung dokumentressource.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />für diese Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) des <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> für eine Auflistung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStoredProcedureFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReadStoredProcedureFeedAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReadStoredProcedureFeedAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadStoredProcedureFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadStoredProcedureFeedAsync (documentCollectionUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of StoredProcedure))" />
      <MemberSignature Language="F#" Value="abstract member ReadStoredProcedureFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.ReadStoredProcedureFeedAsync (documentCollectionUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für die Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) von gespeicherten Prozeduren für eine Sammlung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; ReadTriggerAsync (string triggerLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; ReadTriggerAsync(string triggerLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadTriggerAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadTriggerAsync (triggerLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Trigger))" />
      <MemberSignature Language="F#" Value="abstract member ReadTriggerAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.ReadTriggerAsync (triggerLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="triggerLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="triggerLink">Der Link für den Trigger gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.Trigger" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Trigger" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; ReadTriggerAsync (Uri triggerUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; ReadTriggerAsync(class System.Uri triggerUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadTriggerAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadTriggerAsync (triggerUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Trigger))" />
      <MemberSignature Language="F#" Value="abstract member ReadTriggerAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.ReadTriggerAsync (triggerUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="triggerUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="triggerUri">Ein URI, der Triggerressource gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.Trigger" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Trigger" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadTriggerFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; ReadTriggerFeedAsync (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; ReadTriggerFeedAsync(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadTriggerFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadTriggerFeedAsync (collectionLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Trigger))" />
      <MemberSignature Language="F#" Value="abstract member ReadTriggerFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.ReadTriggerFeedAsync (collectionLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link von der übergeordneten Auflistung dokumentressource.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />für diese Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) des <see cref="T:Microsoft.Azure.Documents.Trigger" /> für eine Auflistung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Trigger" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadTriggerFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; ReadTriggerFeedAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; ReadTriggerFeedAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadTriggerFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadTriggerFeedAsync (documentCollectionUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Trigger))" />
      <MemberSignature Language="F#" Value="abstract member ReadTriggerFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.ReadTriggerFeedAsync (documentCollectionUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für die Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) von Triggern für eine Sammlung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; ReadUserAsync (string userLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; ReadUserAsync(string userLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadUserAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadUserAsync (userLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of User))" />
      <MemberSignature Language="F#" Value="abstract member ReadUserAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.ReadUserAsync (userLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userLink">Der Link auf die Ressource "User" gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.User" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.User" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; ReadUserAsync (Uri userUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; ReadUserAsync(class System.Uri userUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadUserAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadUserAsync (userUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of User))" />
      <MemberSignature Language="F#" Value="abstract member ReadUserAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.ReadUserAsync (userUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">Ein URI, der die Ressource "User" gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.User" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.User" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReadUserDefinedFunctionAsync (string functionLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReadUserDefinedFunctionAsync(string functionLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadUserDefinedFunctionAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadUserDefinedFunctionAsync (functionLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member ReadUserDefinedFunctionAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.ReadUserDefinedFunctionAsync (functionLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="functionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="functionLink">Der Link, um die benutzerdefinierte Funktion gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReadUserDefinedFunctionAsync (Uri functionUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReadUserDefinedFunctionAsync(class System.Uri functionUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadUserDefinedFunctionAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadUserDefinedFunctionAsync (functionUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member ReadUserDefinedFunctionAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.ReadUserDefinedFunctionAsync (functionUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="functionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="functionUri">Ein URI für die benutzerdefinierte Funktion Ressource gelesen werden.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Liest eine <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserDefinedFunctionFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReadUserDefinedFunctionFeedAsync (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReadUserDefinedFunctionFeedAsync(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadUserDefinedFunctionFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadUserDefinedFunctionFeedAsync (collectionLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member ReadUserDefinedFunctionFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.ReadUserDefinedFunctionFeedAsync (collectionLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Der Link von der übergeordneten Auflistung dokumentressource.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />für diese Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) des <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> für eine Auflistung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserDefinedFunctionFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReadUserDefinedFunctionFeedAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReadUserDefinedFunctionFeedAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadUserDefinedFunctionFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadUserDefinedFunctionFeedAsync (documentCollectionUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member ReadUserDefinedFunctionFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.ReadUserDefinedFunctionFeedAsync (documentCollectionUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der übergeordneten Auflistung Dokument.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für die Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) eine benutzerdefinierte Funktionen für eine Sammlung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; ReadUserFeedAsync (string databaseLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; ReadUserFeedAsync(string databaseLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadUserFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadUserFeedAsync (databaseLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of User))" />
      <MemberSignature Language="F#" Value="abstract member ReadUserFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.ReadUserFeedAsync (databaseLink, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">Der Link für die Ressource der übergeordneten Datenbank.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />für diese Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) des <see cref="T:Microsoft.Azure.Documents.User" /> für eine Datenbank als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.User" /> , die den read-Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; ReadUserFeedAsync (Uri databaseUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; ReadUserFeedAsync(class System.Uri databaseUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadUserFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadUserFeedAsync (databaseUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of User))" />
      <MemberSignature Language="F#" Value="abstract member ReadUserFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.ReadUserFeedAsync (databaseUri, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">Der URI der übergeordneten Datenbank.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> für die Anforderung.</param>
        <summary>
            Liest den Feed (Sequenz) von Benutzern für eine Datenbank als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; ReplaceAttachmentAsync (Microsoft.Azure.Documents.Attachment attachment, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; ReplaceAttachmentAsync(class Microsoft.Azure.Documents.Attachment attachment, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceAttachmentAsync(Microsoft.Azure.Documents.Attachment,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceAttachmentAsync : Microsoft.Azure.Documents.Attachment * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.ReplaceAttachmentAsync (attachment, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="attachment" Type="Microsoft.Azure.Documents.Attachment" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="attachment">Die aktualisierte <see cref="T:Microsoft.Azure.Documents.Attachment" /> ersetzen die vorhandene Ressource mit.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Ersetzt ein <see cref="T:Microsoft.Azure.Documents.Attachment" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Attachment" /> , die den aktualisierten Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; ReplaceAttachmentAsync (Uri attachmentUri, Microsoft.Azure.Documents.Attachment attachment, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; ReplaceAttachmentAsync(class System.Uri attachmentUri, class Microsoft.Azure.Documents.Attachment attachment, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceAttachmentAsync(System.Uri,Microsoft.Azure.Documents.Attachment,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceAttachmentAsync : Uri * Microsoft.Azure.Documents.Attachment * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.ReplaceAttachmentAsync (attachmentUri, attachment, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="attachmentUri" Type="System.Uri" />
        <Parameter Name="attachment" Type="Microsoft.Azure.Documents.Attachment" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="attachmentUri">Der URI der Anlage aktualisiert werden.</param>
        <param name="attachment">Die Attachment-Ressource.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Ersetzt eine Anlage als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; ReplaceDocumentAsync (Microsoft.Azure.Documents.Document document, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; ReplaceDocumentAsync(class Microsoft.Azure.Documents.Document document, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceDocumentAsync(Microsoft.Azure.Documents.Document,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceDocumentAsync : Microsoft.Azure.Documents.Document * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.ReplaceDocumentAsync (document, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="Microsoft.Azure.Documents.Document" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="document">Die aktualisierte <see cref="T:Microsoft.Azure.Documents.Document" /> ersetzen die vorhandene Ressource mit.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Ersetzt ein <see cref="T:Microsoft.Azure.Documents.Document" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Document" /> , die den aktualisierten Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; ReplaceDocumentAsync (string documentLink, object document, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; ReplaceDocumentAsync(string documentLink, object document, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceDocumentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReplaceDocumentAsync (documentLink As String, document As Object, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member ReplaceDocumentAsync : string * obj * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.ReplaceDocumentAsync (documentLink, document, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="document" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">Die Verknüpfung des Dokuments aktualisiert werden. Beispiel: DBS/Db_rid/colls/Col_rid/Dokumente/Doc_rid / </param>
        <param name="document">Die aktualisierte <see cref="T:Microsoft.Azure.Documents.Document" /> ersetzen die vorhandene Ressource mit.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Ersetzt ein <see cref="T:Microsoft.Azure.Documents.Document" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Document" /> , die den aktualisierten Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; ReplaceDocumentAsync (Uri documentUri, object document, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; ReplaceDocumentAsync(class System.Uri documentUri, object document, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceDocumentAsync(System.Uri,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReplaceDocumentAsync (documentUri As Uri, document As Object, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member ReplaceDocumentAsync : Uri * obj * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.ReplaceDocumentAsync (documentUri, document, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="document" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">Der URI des Dokuments aktualisiert werden.</param>
        <param name="document">Das aktualisierte Dokument.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Ersetzt ein Dokument als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceDocumentCollectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReplaceDocumentCollectionAsync (Microsoft.Azure.Documents.DocumentCollection documentCollection, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReplaceDocumentCollectionAsync(class Microsoft.Azure.Documents.DocumentCollection documentCollection, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceDocumentCollectionAsync(Microsoft.Azure.Documents.DocumentCollection,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceDocumentCollectionAsync : Microsoft.Azure.Documents.DocumentCollection * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.ReplaceDocumentCollectionAsync (documentCollection, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollection" Type="Microsoft.Azure.Documents.DocumentCollection" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollection">Die aktualisierte Dokument-Auflistung.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Ersetzt eine Dokument-Auflistung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceDocumentCollectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReplaceDocumentCollectionAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.DocumentCollection documentCollection, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReplaceDocumentCollectionAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.DocumentCollection documentCollection, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceDocumentCollectionAsync(System.Uri,Microsoft.Azure.Documents.DocumentCollection,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceDocumentCollectionAsync : Uri * Microsoft.Azure.Documents.DocumentCollection * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.ReplaceDocumentCollectionAsync (documentCollectionUri, documentCollection, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="documentCollection" Type="Microsoft.Azure.Documents.DocumentCollection" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der Auflistung Dokument aktualisiert werden.</param>
        <param name="documentCollection">Die aktualisierte Dokument-Auflistung.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Ersetzt eine Dokument-Auflistung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceOfferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt; ReplaceOfferAsync (Microsoft.Azure.Documents.Offer offer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Offer&gt;&gt; ReplaceOfferAsync(class Microsoft.Azure.Documents.Offer offer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceOfferAsync(Microsoft.Azure.Documents.Offer)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceOfferAsync : Microsoft.Azure.Documents.Offer -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt;" Usage="iDocumentClient.ReplaceOfferAsync offer" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="offer" Type="Microsoft.Azure.Documents.Offer" />
      </Parameters>
      <Docs>
        <param name="offer">Die aktualisierte <see cref="T:Microsoft.Azure.Documents.Offer" /> ersetzen die vorhandene Ressource mit.</param>
        <summary>
            Ersetzt ein <see cref="T:Microsoft.Azure.Documents.Offer" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Offer" /> , die den aktualisierten Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplacePermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; ReplacePermissionAsync (Microsoft.Azure.Documents.Permission permission, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; ReplacePermissionAsync(class Microsoft.Azure.Documents.Permission permission, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplacePermissionAsync(Microsoft.Azure.Documents.Permission,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplacePermissionAsync : Microsoft.Azure.Documents.Permission * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.ReplacePermissionAsync (permission, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permission" Type="Microsoft.Azure.Documents.Permission" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="permission">Die aktualisierte <see cref="T:Microsoft.Azure.Documents.Permission" /> ersetzen die vorhandene Ressource mit.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Ersetzt ein <see cref="T:Microsoft.Azure.Documents.Permission" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Permission" /> , die den aktualisierten Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplacePermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; ReplacePermissionAsync (Uri permissionUri, Microsoft.Azure.Documents.Permission permission, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; ReplacePermissionAsync(class System.Uri permissionUri, class Microsoft.Azure.Documents.Permission permission, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplacePermissionAsync(System.Uri,Microsoft.Azure.Documents.Permission,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplacePermissionAsync : Uri * Microsoft.Azure.Documents.Permission * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.ReplacePermissionAsync (permissionUri, permission, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissionUri" Type="System.Uri" />
        <Parameter Name="permission" Type="Microsoft.Azure.Documents.Permission" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="permissionUri">Der URI für die Berechtigung, die aktualisiert werden.</param>
        <param name="permission">Die aktualisierte Berechtigung.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Ersetzt eine Berechtigung als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReplaceStoredProcedureAsync (Microsoft.Azure.Documents.StoredProcedure storedProcedure, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReplaceStoredProcedureAsync(class Microsoft.Azure.Documents.StoredProcedure storedProcedure, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceStoredProcedureAsync(Microsoft.Azure.Documents.StoredProcedure,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceStoredProcedureAsync : Microsoft.Azure.Documents.StoredProcedure * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.ReplaceStoredProcedureAsync (storedProcedure, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storedProcedure" Type="Microsoft.Azure.Documents.StoredProcedure" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="storedProcedure">Die aktualisierte <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> ersetzen die vorhandene Ressource mit.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Ersetzt ein <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> , die den aktualisierten Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReplaceStoredProcedureAsync (Uri storedProcedureUri, Microsoft.Azure.Documents.StoredProcedure storedProcedure, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReplaceStoredProcedureAsync(class System.Uri storedProcedureUri, class Microsoft.Azure.Documents.StoredProcedure storedProcedure, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceStoredProcedureAsync(System.Uri,Microsoft.Azure.Documents.StoredProcedure,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceStoredProcedureAsync : Uri * Microsoft.Azure.Documents.StoredProcedure * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.ReplaceStoredProcedureAsync (storedProcedureUri, storedProcedure, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storedProcedureUri" Type="System.Uri" />
        <Parameter Name="storedProcedure" Type="Microsoft.Azure.Documents.StoredProcedure" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="storedProcedureUri">Der URI für die gespeicherte Prozedur aktualisiert werden.</param>
        <param name="storedProcedure">Die aktualisierte gespeicherte Prozedur.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Ersetzen Sie die angegebene gespeicherte Prozedur in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; ReplaceTriggerAsync (Microsoft.Azure.Documents.Trigger trigger, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; ReplaceTriggerAsync(class Microsoft.Azure.Documents.Trigger trigger, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceTriggerAsync(Microsoft.Azure.Documents.Trigger,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceTriggerAsync : Microsoft.Azure.Documents.Trigger * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.ReplaceTriggerAsync (trigger, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trigger" Type="Microsoft.Azure.Documents.Trigger" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="trigger">Die aktualisierte <see cref="T:Microsoft.Azure.Documents.Trigger" /> ersetzen die vorhandene Ressource mit.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Ersetzt ein <see cref="T:Microsoft.Azure.Documents.Trigger" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.Trigger" /> , die den aktualisierten Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; ReplaceTriggerAsync (Uri triggerUri, Microsoft.Azure.Documents.Trigger trigger, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; ReplaceTriggerAsync(class System.Uri triggerUri, class Microsoft.Azure.Documents.Trigger trigger, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceTriggerAsync(System.Uri,Microsoft.Azure.Documents.Trigger,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceTriggerAsync : Uri * Microsoft.Azure.Documents.Trigger * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.ReplaceTriggerAsync (triggerUri, trigger, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="triggerUri" Type="System.Uri" />
        <Parameter Name="trigger" Type="Microsoft.Azure.Documents.Trigger" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="triggerUri">Der URI für den Trigger aktualisiert werden.</param>
        <param name="trigger">Der aktualisierte Trigger.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Ersetzt einen Trigger als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; ReplaceUserAsync (Microsoft.Azure.Documents.User user, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; ReplaceUserAsync(class Microsoft.Azure.Documents.User user, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceUserAsync(Microsoft.Azure.Documents.User,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceUserAsync : Microsoft.Azure.Documents.User * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.ReplaceUserAsync (user, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="user" Type="Microsoft.Azure.Documents.User" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="user">Die aktualisierte <see cref="T:Microsoft.Azure.Documents.User" /> ersetzen die vorhandene Ressource mit.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Ersetzt ein <see cref="T:Microsoft.Azure.Documents.User" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.User" /> , die den aktualisierten Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; ReplaceUserAsync (Uri userUri, Microsoft.Azure.Documents.User user, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; ReplaceUserAsync(class System.Uri userUri, class Microsoft.Azure.Documents.User user, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceUserAsync(System.Uri,Microsoft.Azure.Documents.User,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceUserAsync : Uri * Microsoft.Azure.Documents.User * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.ReplaceUserAsync (userUri, user, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="user" Type="Microsoft.Azure.Documents.User" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">Der URI für den Benutzer aktualisiert werden.</param>
        <param name="user">Der aktualisierte Benutzer.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Ersetzt einen Benutzer als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReplaceUserDefinedFunctionAsync (Microsoft.Azure.Documents.UserDefinedFunction function, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReplaceUserDefinedFunctionAsync(class Microsoft.Azure.Documents.UserDefinedFunction function, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceUserDefinedFunctionAsync(Microsoft.Azure.Documents.UserDefinedFunction,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReplaceUserDefinedFunctionAsync (function As UserDefinedFunction, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member ReplaceUserDefinedFunctionAsync : Microsoft.Azure.Documents.UserDefinedFunction * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.ReplaceUserDefinedFunctionAsync (function, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="function" Type="Microsoft.Azure.Documents.UserDefinedFunction" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="function">Die aktualisierte <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> ersetzen die vorhandene Ressource mit.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Ersetzt ein <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein <see cref="N:System.Threading.Tasks" /> , enthält eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> welche umschließt eine <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> , die den aktualisierten Ressourceneintrag enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReplaceUserDefinedFunctionAsync (Uri userDefinedFunctionUri, Microsoft.Azure.Documents.UserDefinedFunction function, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReplaceUserDefinedFunctionAsync(class System.Uri userDefinedFunctionUri, class Microsoft.Azure.Documents.UserDefinedFunction function, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceUserDefinedFunctionAsync(System.Uri,Microsoft.Azure.Documents.UserDefinedFunction,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReplaceUserDefinedFunctionAsync (userDefinedFunctionUri As Uri, function As UserDefinedFunction, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member ReplaceUserDefinedFunctionAsync : Uri * Microsoft.Azure.Documents.UserDefinedFunction * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.ReplaceUserDefinedFunctionAsync (userDefinedFunctionUri, function, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userDefinedFunctionUri" Type="System.Uri" />
        <Parameter Name="function" Type="Microsoft.Azure.Documents.UserDefinedFunction" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userDefinedFunctionUri">Der URI für den Benutzer definiert Funktion aktualisiert werden.</param>
        <param name="function">Die aktualisierte Benutzerkontoeigenschaften benutzerdefinierten Funktion.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Ersetzt einen benutzerdefinierten benutzerdefinierten Funktion als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceEndpoint">
      <MemberSignature Language="C#" Value="public Uri ServiceEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IDocumentClient.ServiceEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceEndpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceEndpoint : Uri" Usage="Microsoft.Azure.Documents.IDocumentClient.ServiceEndpoint" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Endpunkt-Uri für den Dienstendpunkt in der Azure-Cosmos-DB-Dienst ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Session">
      <MemberSignature Language="C#" Value="public object Session { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Session" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IDocumentClient.Session" />
      <MemberSignature Language="VB.NET" Value="Public Property Session As Object" />
      <MemberSignature Language="F#" Value="member this.Session : obj with get, set" Usage="Microsoft.Azure.Documents.IDocumentClient.Session" />
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
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Sitzungsobjekt für die Sitzung Konsistenz versionsüberwachung im Azure-Cosmos-DB-Dienst verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMediaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt; UpdateMediaAsync (string mediaLink, System.IO.Stream mediaStream, Microsoft.Azure.Documents.Client.MediaOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.MediaResponse&gt; UpdateMediaAsync(string mediaLink, class System.IO.Stream mediaStream, class Microsoft.Azure.Documents.Client.MediaOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpdateMediaAsync(System.String,System.IO.Stream,Microsoft.Azure.Documents.Client.MediaOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateMediaAsync (mediaLink As String, mediaStream As Stream, Optional options As MediaOptions = null) As Task(Of MediaResponse)" />
      <MemberSignature Language="F#" Value="abstract member UpdateMediaAsync : string * System.IO.Stream * Microsoft.Azure.Documents.Client.MediaOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt;" Usage="iDocumentClient.UpdateMediaAsync (mediaLink, mediaStream, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mediaLink" Type="System.String" />
        <Parameter Name="mediaStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.MediaOptions" />
      </Parameters>
      <Docs>
        <param name="mediaLink">Der Link für die Medien aktualisiert werden. / Medien/media_rid </param>
        <param name="mediaStream">Die <see cref="T:System.IO.Stream" /> der Medien anfügen.</param>
        <param name="options">Die <see cref="T:Microsoft.Azure.Documents.Client.MediaOptions" /> für die Anforderung.</param>
        <summary>
            Ersetzt den angegebenen Media-Inhalten als asynchronen Vorgang im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn entweder <paramref name="mediaLink" /> oder <paramref name="mediaStream" /> ist nicht festgelegt.</exception>
        <exception cref="T:System.ArgumentException">Wenn <paramref name="mediaLink" /> befindet sich nicht in Form von /medias/ {MediaId}.</exception>
      </Docs>
    </Member>
    <Member MemberName="UpsertAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; UpsertAttachmentAsync (string documentLink, object attachment, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; UpsertAttachmentAsync(string documentLink, object attachment, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertAttachmentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpsertAttachmentAsync (documentLink As String, attachment As Object, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member UpsertAttachmentAsync : string * obj * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.UpsertAttachmentAsync (documentLink, attachment, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="attachment" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">Der Link, der das übergeordnete Dokument für diese neue Anlage. Beispiel: DBS/Db_rid/colls/Col_rid/Dokumente/Doc_rid / </param>
        <param name="attachment">Die Attachment-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Upserts Anlage als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Die <see cref="T:System.Threading.Tasks.Task" /> Objekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; UpsertAttachmentAsync (Uri documentUri, object attachment, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; UpsertAttachmentAsync(class System.Uri documentUri, object attachment, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertAttachmentAsync(System.Uri,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpsertAttachmentAsync (documentUri As Uri, attachment As Object, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member UpsertAttachmentAsync : Uri * obj * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.UpsertAttachmentAsync (documentUri, attachment, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="attachment" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">Der URI des Dokuments, das eine Anlage für Upsert.</param>
        <param name="attachment">Das <see cref="T:Microsoft.Azure.Documents.Attachment" />-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Upserts Anlage als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; UpsertAttachmentAsync (string documentLink, System.IO.Stream mediaStream, Microsoft.Azure.Documents.Client.MediaOptions options = null, Microsoft.Azure.Documents.Client.RequestOptions requestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; UpsertAttachmentAsync(string documentLink, class System.IO.Stream mediaStream, class Microsoft.Azure.Documents.Client.MediaOptions options, class Microsoft.Azure.Documents.Client.RequestOptions requestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertAttachmentAsync(System.String,System.IO.Stream,Microsoft.Azure.Documents.Client.MediaOptions,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertAttachmentAsync : string * System.IO.Stream * Microsoft.Azure.Documents.Client.MediaOptions * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.UpsertAttachmentAsync (documentLink, mediaStream, options, requestOptions)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="mediaStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.MediaOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">Der Link, der das übergeordnete Dokument für diese neue Anlage. Beispiel: DBS/Db_rid/colls/Col_rid/Dokumente/Doc_rid / </param>
        <param name="mediaStream">Die <see cref="T:System.IO.Stream" /> der Medien anfügen.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.MediaOptions" /> für die Anforderung.</param>
        <param name="requestOptions">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Upserts Anlage mit dem Inhalt des bereitgestellten <paramref name="mediaStream" /> als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Die <see cref="T:System.Threading.Tasks.Task" /> Objekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; UpsertAttachmentAsync (Uri documentUri, System.IO.Stream mediaStream, Microsoft.Azure.Documents.Client.MediaOptions options = null, Microsoft.Azure.Documents.Client.RequestOptions requestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; UpsertAttachmentAsync(class System.Uri documentUri, class System.IO.Stream mediaStream, class Microsoft.Azure.Documents.Client.MediaOptions options, class Microsoft.Azure.Documents.Client.RequestOptions requestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertAttachmentAsync(System.Uri,System.IO.Stream,Microsoft.Azure.Documents.Client.MediaOptions,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertAttachmentAsync : Uri * System.IO.Stream * Microsoft.Azure.Documents.Client.MediaOptions * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.UpsertAttachmentAsync (documentUri, mediaStream, options, requestOptions)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="mediaStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.MediaOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">Der URI des Dokuments, das eine Anlage für Upsert.</param>
        <param name="mediaStream">Der Datenstrom der Medien anfügen.</param>
        <param name="options">Die <see cref="T:Microsoft.Azure.Documents.Client.MediaOptions" /> für die Anforderung.</param>
        <param name="requestOptions">Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Upserts Anlage als asynchronen Vorgang im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; UpsertDocumentAsync (string collectionLink, object document, Microsoft.Azure.Documents.Client.RequestOptions options = null, bool disableAutomaticIdGeneration = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; UpsertDocumentAsync(string collectionLink, object document, class Microsoft.Azure.Documents.Client.RequestOptions options, bool disableAutomaticIdGeneration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertDocumentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpsertDocumentAsync (collectionLink As String, document As Object, Optional options As RequestOptions = null, Optional disableAutomaticIdGeneration As Boolean = false) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member UpsertDocumentAsync : string * obj * Microsoft.Azure.Documents.Client.RequestOptions * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.UpsertDocumentAsync (collectionLink, document, options, disableAutomaticIdGeneration)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="document" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
        <Parameter Name="disableAutomaticIdGeneration" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Die Verknüpfung der <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> zu Upsert das Dokument in. Beispiel: DBS/Db_rid/colls/Coll_rid / </param>
        <param name="document">Um Upsert Document-Objekt.</param>
        <param name="options">(Optional) Alle Optionen, die Sie festlegen möchten. Beispiel: Angeben eines Triggers ausgeführt wird, wenn das Dokument zu erstellen. <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /></param>
        <param name="disableAutomaticIdGeneration">(Optional) Deaktiviert die automatische Id-Generierung, ist dies "true" das System löst eine Ausnahme aus, wenn die Id-Eigenschaft aus dem Dokument nicht vorhanden ist.</param>
        <summary>
            Upserts eines Dokuments als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Die <see cref="T:Microsoft.Azure.Documents.Document" /> , Upserted in enthalten war ein <see cref="T:System.Threading.Tasks.Task" /> Objekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; UpsertDocumentAsync (Uri documentCollectionUri, object document, Microsoft.Azure.Documents.Client.RequestOptions options = null, bool disableAutomaticIdGeneration = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; UpsertDocumentAsync(class System.Uri documentCollectionUri, object document, class Microsoft.Azure.Documents.Client.RequestOptions options, bool disableAutomaticIdGeneration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertDocumentAsync(System.Uri,System.Object,Microsoft.Azure.Documents.Client.RequestOptions,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpsertDocumentAsync (documentCollectionUri As Uri, document As Object, Optional options As RequestOptions = null, Optional disableAutomaticIdGeneration As Boolean = false) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member UpsertDocumentAsync : Uri * obj * Microsoft.Azure.Documents.Client.RequestOptions * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.UpsertDocumentAsync (documentCollectionUri, document, options, disableAutomaticIdGeneration)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="document" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
        <Parameter Name="disableAutomaticIdGeneration" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der Auflistung Dokument Upsert das Dokument in.</param>
        <param name="document">Das Document-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <param name="disableAutomaticIdGeneration">Ein Flag zum Deaktivieren der automatischen Id Generierung.</param>
        <summary>
            Upserts eines Dokuments als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertPermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; UpsertPermissionAsync (string userLink, Microsoft.Azure.Documents.Permission permission, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; UpsertPermissionAsync(string userLink, class Microsoft.Azure.Documents.Permission permission, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertPermissionAsync(System.String,Microsoft.Azure.Documents.Permission,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertPermissionAsync : string * Microsoft.Azure.Documents.Permission * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.UpsertPermissionAsync (userLink, permission, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userLink" Type="System.String" />
        <Parameter Name="permission" Type="Microsoft.Azure.Documents.Permission" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userLink">Die Verknüpfung des Benutzers, der Upsert die Berechtigung für. Beispiel: DBS/Db_rid/Benutzer/User_rid / </param>
        <param name="permission">Das <see cref="T:Microsoft.Azure.Documents.Permission" />-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Upserts eine Berechtigung für ein Benutzerobjekt als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang enthält den Upserted darstellt <see cref="T:Microsoft.Azure.Documents.Permission" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertPermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; UpsertPermissionAsync (Uri userUri, Microsoft.Azure.Documents.Permission permission, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; UpsertPermissionAsync(class System.Uri userUri, class Microsoft.Azure.Documents.Permission permission, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertPermissionAsync(System.Uri,Microsoft.Azure.Documents.Permission,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertPermissionAsync : Uri * Microsoft.Azure.Documents.Permission * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.UpsertPermissionAsync (userUri, permission, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="permission" Type="Microsoft.Azure.Documents.Permission" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">Der URI des Benutzers, der Upsert die Berechtigung für.</param>
        <param name="permission">Das <see cref="T:Microsoft.Azure.Documents.Permission" />-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Upserts eine Berechtigung als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; UpsertStoredProcedureAsync (string collectionLink, Microsoft.Azure.Documents.StoredProcedure storedProcedure, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; UpsertStoredProcedureAsync(string collectionLink, class Microsoft.Azure.Documents.StoredProcedure storedProcedure, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertStoredProcedureAsync(System.String,Microsoft.Azure.Documents.StoredProcedure,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertStoredProcedureAsync : string * Microsoft.Azure.Documents.StoredProcedure * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.UpsertStoredProcedureAsync (collectionLink, storedProcedure, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="storedProcedure" Type="Microsoft.Azure.Documents.StoredProcedure" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Den Link der Auflistung Upsert die gespeicherte Prozedur in. Beispiel: DBS/Db_rid/colls/Col_rid /</param>
        <param name="storedProcedure">Die <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> Upsert-Objekt.</param>
        <param name="options">(Optional) Alle <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Upserts einer gespeicherten Prozedur als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Die <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> , Upserted in enthalten war ein <see cref="T:System.Threading.Tasks.Task" /> Objekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; UpsertStoredProcedureAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.StoredProcedure storedProcedure, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; UpsertStoredProcedureAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.StoredProcedure storedProcedure, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertStoredProcedureAsync(System.Uri,Microsoft.Azure.Documents.StoredProcedure,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertStoredProcedureAsync : Uri * Microsoft.Azure.Documents.StoredProcedure * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.UpsertStoredProcedureAsync (documentCollectionUri, storedProcedure, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="storedProcedure" Type="Microsoft.Azure.Documents.StoredProcedure" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der Auflistung Dokument Upsert die gespeicherte Prozedur in.</param>
        <param name="storedProcedure">Das <see cref="T:Microsoft.Azure.Documents.StoredProcedure" />-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Upserts einer gespeicherten Prozedur als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; UpsertTriggerAsync (string collectionLink, Microsoft.Azure.Documents.Trigger trigger, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; UpsertTriggerAsync(string collectionLink, class Microsoft.Azure.Documents.Trigger trigger, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertTriggerAsync(System.String,Microsoft.Azure.Documents.Trigger,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertTriggerAsync : string * Microsoft.Azure.Documents.Trigger * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.UpsertTriggerAsync (collectionLink, trigger, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="trigger" Type="Microsoft.Azure.Documents.Trigger" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Die Verknüpfung der <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> zu Upsert-der Trigger in. Beispiel: DBS/Db_rid/colls/Col_rid / </param>
        <param name="trigger">Die <see cref="T:Microsoft.Azure.Documents.Trigger" /> Upsert-Objekt.</param>
        <param name="options">(Optional) Alle <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Upserts ein Trigger als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; UpsertTriggerAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Trigger trigger, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; UpsertTriggerAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Trigger trigger, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertTriggerAsync(System.Uri,Microsoft.Azure.Documents.Trigger,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertTriggerAsync : Uri * Microsoft.Azure.Documents.Trigger * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.UpsertTriggerAsync (documentCollectionUri, trigger, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="trigger" Type="Microsoft.Azure.Documents.Trigger" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der Auflistung Dokument Upsert-der Trigger in.</param>
        <param name="trigger">Das <see cref="T:Microsoft.Azure.Documents.Trigger" />-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Upserts ein Trigger als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; UpsertUserAsync (string databaseLink, Microsoft.Azure.Documents.User user, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; UpsertUserAsync(string databaseLink, class Microsoft.Azure.Documents.User user, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertUserAsync(System.String,Microsoft.Azure.Documents.User,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertUserAsync : string * Microsoft.Azure.Documents.User * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.UpsertUserAsync (databaseLink, user, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="user" Type="Microsoft.Azure.Documents.User" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">Die Verknüpfung der Datenbank, die Upsert der Benutzer in. Beispiel: DBS/Db_rid / </param>
        <param name="user">Die <see cref="T:Microsoft.Azure.Documents.User" /> Upsert-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Upserts eine Berechtigung für ein Benutzerobjekt als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang enthält den Upserted darstellt <see cref="T:Microsoft.Azure.Documents.User" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; UpsertUserAsync (Uri databaseUri, Microsoft.Azure.Documents.User user, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; UpsertUserAsync(class System.Uri databaseUri, class Microsoft.Azure.Documents.User user, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertUserAsync(System.Uri,Microsoft.Azure.Documents.User,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertUserAsync : Uri * Microsoft.Azure.Documents.User * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.UpsertUserAsync (databaseUri, user, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="user" Type="Microsoft.Azure.Documents.User" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">Der URI der Datenbank, die Upsert der Benutzer in.</param>
        <param name="user">Das <see cref="T:Microsoft.Azure.Documents.User" />-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Upserts ein Benutzer als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; UpsertUserDefinedFunctionAsync (string collectionLink, Microsoft.Azure.Documents.UserDefinedFunction function, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; UpsertUserDefinedFunctionAsync(string collectionLink, class Microsoft.Azure.Documents.UserDefinedFunction function, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertUserDefinedFunctionAsync(System.String,Microsoft.Azure.Documents.UserDefinedFunction,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpsertUserDefinedFunctionAsync (collectionLink As String, function As UserDefinedFunction, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member UpsertUserDefinedFunctionAsync : string * Microsoft.Azure.Documents.UserDefinedFunction * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.UpsertUserDefinedFunctionAsync (collectionLink, function, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Documents.UserDefinedFunction" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Die Verknüpfung der <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> zu Upsert die benutzerdefinierte Funktion in. Beispiel: DBS/Db_rid/colls/Col_rid / </param>
        <param name="function">Die <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> Upsert-Objekt.</param>
        <param name="options">(Optional) Alle <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />für diese Anforderung.</param>
        <summary>
            Upserts eines Benutzers benutzerdefinierten Funktion als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Ein Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; UpsertUserDefinedFunctionAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.UserDefinedFunction function, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; UpsertUserDefinedFunctionAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.UserDefinedFunction function, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertUserDefinedFunctionAsync(System.Uri,Microsoft.Azure.Documents.UserDefinedFunction,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpsertUserDefinedFunctionAsync (documentCollectionUri As Uri, function As UserDefinedFunction, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member UpsertUserDefinedFunctionAsync : Uri * Microsoft.Azure.Documents.UserDefinedFunction * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.UpsertUserDefinedFunctionAsync (documentCollectionUri, function, options)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="function" Type="Microsoft.Azure.Documents.UserDefinedFunction" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Der URI der Auflistung Dokument Upsert Benutzer jeder benutzerdefinierten Funktion in.</param>
        <param name="function">Das <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />-Objekt.</param>
        <param name="options">(Optional) Die <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> für die Anforderung.</param>
        <summary>
            Upserts eines Benutzers benutzerdefinierten Funktion als asynchrone Vorgang in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Das Aufgabenobjekt, das Antwort des Diensts für den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEndpoint">
      <MemberSignature Language="C#" Value="public Uri WriteEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri WriteEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IDocumentClient.WriteEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteEndpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.WriteEndpoint : Uri" Usage="Microsoft.Azure.Documents.IDocumentClient.WriteEndpoint" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den aktuellen Write-Endpunkt auf Grundlage der Verfügbarkeit und der Einstellung in der Azure-Cosmos-DB-Dienst ausgewählt wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>