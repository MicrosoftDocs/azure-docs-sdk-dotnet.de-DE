<Type Name="RequestOptions" FullName="Microsoft.Azure.Documents.Client.RequestOptions">
  <TypeSignature Language="C#" Value="public sealed class RequestOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RequestOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.RequestOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RequestOptions" />
  <TypeSignature Language="F#" Value="type RequestOptions = class" />
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
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Kapselt die Optionen, die für unterschiedliche Anforderungen an den Azure-Cosmos-DB-Dienst ausgegebenen angegeben werden können.
            </summary>
    <remarks>
            Einige dieser Optionen sind für einen bestimmten Vorgang nur gültig. Beispielsweise <para>PreTriggerInclude kann verwendet werden, nur auf erstellen, ersetzen und Löschvorgängen für einen <see cref="T:Microsoft.Azure.Documents.Document" /> oder <see cref="T:Microsoft.Azure.Documents.Attachment" />. </para><para>ETag, während für ersetzen * und * Delete-Vorgänge gültig wäre haben keine Auswirkung auf ein Lesevorgang*, CreateQuery* oder Create * Vorgänge.</para></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.RequestOptions.#ctor" />
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
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessCondition">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Client.AccessCondition AccessCondition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Client.AccessCondition AccessCondition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.AccessCondition" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessCondition As AccessCondition" />
      <MemberSignature Language="F#" Value="member this.AccessCondition : Microsoft.Azure.Documents.Client.AccessCondition with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.AccessCondition" />
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
        <ReturnType>Microsoft.Azure.Documents.Client.AccessCondition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Bedingung (ETag), die die Anforderung im Azure-Cosmos-DB-Dienst zugeordnet ist.
            </summary>
        <value>
            Die Bedingung (ETag) der Anforderung zugeordnet ist.
            </value>
        <remarks>
            Die Methoden Delete * und * ersetzen, der am häufigsten verwendeten <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> wie z. B. <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReplaceDocumentAsync(Microsoft.Azure.Documents.Document,Microsoft.Azure.Documents.Client.RequestOptions)" /> oder <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReplaceDocumentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" /> Methoden, aber kann verwendet werden, mit anderen Methoden wie <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadDocumentAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" /> zum Zwischenspeichern von Szenarios. 
            </remarks>
        <see cref="T:Microsoft.Azure.Documents.Client.AccessCondition" />
        <example>
            Das folgende Beispiel zeigt, wie Sie RequestOptions mit <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReplaceDocumentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" /> an den Satz von <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.AccessCondition" /> verwendet werden, wenn ein Dokument aktualisieren
            <code language="c#"><![CDATA[
            // If ETag is current, then this will succeed. Otherwise the request will fail with HTTP 412 Precondition Failure
            await client.ReplaceDocumentAsync(
            readCopyOfBook.SelfLink, 
                new Book { Title = "Moby Dick", Price = 14.99 },
                new RequestOptions 
                { 
                AccessCondition = new AccessCondition 
                    { 
                    Condition = readCopyOfBook.ETag, 
                        Type = AccessConditionType.IfMatch 
                        } 
                    });
                 ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="ConsistencyLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Documents.ConsistencyLevel&gt; ConsistencyLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Documents.ConsistencyLevel&gt; ConsistencyLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.ConsistencyLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsistencyLevel As Nullable(Of ConsistencyLevel)" />
      <MemberSignature Language="F#" Value="member this.ConsistencyLevel : Nullable&lt;Microsoft.Azure.Documents.ConsistencyLevel&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.ConsistencyLevel" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Documents.ConsistencyLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die konsistenzebene für die Anforderung im Azure-Cosmos-DB-Dienst erforderlich.
            </summary>
        <value>
            Die konsistenzebene für die Anforderung erforderlich sind.
            </value>
        <remarks>
            Azure Cosmos-Datenbank bietet 4 unterschiedliche konsistenzebenen. Strong, Bounded Staleness, Sitzungs- und Eventual – in der Reihenfolge der stärksten zu schwächste Konsistenz.
            <para>Während dieses Konto auf der Ebene festgelegt ist, ermöglicht Azure Cosmos-Datenbank ein Entwickler, die Konsistenz Standardebene für jede einzelne Anforderung Schwächen.</para></remarks>
        <altmember cref="P:Microsoft.Azure.Documents.Client.RequestOptions.ConsistencyLevel" />
        <example>
            Dieses Beispiel verwendet die RequestOptions die konsistenzebene auf Eventual für diese einzelnen Vorgang zu senken. 
            <code language="c#"><![CDATA[
            Document doc = client.ReadDocumentAsync(documentLink, new RequestOptions { ConsistencyLevel = ConsistencyLevel.Eventual });
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="DisableRUPerMinuteUsage">
      <MemberSignature Language="C#" Value="public bool DisableRUPerMinuteUsage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DisableRUPerMinuteUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.DisableRUPerMinuteUsage" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableRUPerMinuteUsage As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableRUPerMinuteUsage : bool with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.DisableRUPerMinuteUsage" />
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
             Ruft ab oder legt die <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.DisableRUPerMinuteUsage" /> für die aktuelle Anforderung im Azure-Cosmos-DB-Dienst.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            DisableRUPerMinuteUsage dient zum Aktivieren/Deaktivieren von Anforderungseinheiten (RUs) / Minute Kapazität für die Anforderung dienen, wenn reguläre RUs/Sekunde bereitgestellt erschöpft ist.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableScriptLogging">
      <MemberSignature Language="C#" Value="public bool EnableScriptLogging { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableScriptLogging" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableScriptLogging As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableScriptLogging : bool with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" />
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
             Ruft ab oder legt die <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" /> für die aktuelle Anforderung im Azure-Cosmos-DB-Dienst.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            EnableScriptLogging dient zum Aktivieren/Deaktivieren der Protokollierung in JavaScript, die gespeicherten Prozeduren.
            Standardskript ist die Protokollierung deaktiviert.
            Das Protokoll kann auch im Antwortheader (x-ms-documentdb-script-log-results) zugänglich sein.
            </para>
        </remarks>
        <altmember cref="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.ScriptLog" />
        <example>
            Im folgende Beispiel wird gezeigt, wie die Protokollierung in gespeicherten Prozeduren, die mit <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" />.
            <code language="c#"><![CDATA[
            var response = await client.ExecuteStoredProcedureAsync(
                document.SelfLink,
                new RequestOptions { EnableScriptLogging = true } );
            Console.WriteLine(response.ScriptLog);
            ]]></code>Um zu protokollieren, verwenden Sie die folgende in Store-Prozedur aus:<code language="JavaScript"><![CDATA[
            console.log("This is trace log");
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="IndexingDirective">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Documents.IndexingDirective&gt; IndexingDirective { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Documents.IndexingDirective&gt; IndexingDirective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.IndexingDirective" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexingDirective As Nullable(Of IndexingDirective)" />
      <MemberSignature Language="F#" Value="member this.IndexingDirective : Nullable&lt;Microsoft.Azure.Documents.IndexingDirective&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.IndexingDirective" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Documents.IndexingDirective&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Volltextindizierung-Direktive (Include oder Exclude) für die Anforderung im Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Die Volltextindizierung Direktive zur Verwendung mit einer Anforderung.
            </value>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.IndexingPolicy" />
        <altmember cref="P:Microsoft.Azure.Documents.Client.RequestOptions.IndexingDirective" />
        <example>
            Das folgende Beispiel zeigt, wie explizit Index ein Dokument in einer Sammlung mit der automatischen Indizierung deaktiviert.
            <code language="c#"><![CDATA[
            client.CreateDocumentAsync(defaultCollection.SelfLink,
            new { id = "AndersenFamily", isRegistered = true },
                new RequestOptions { IndexingDirective = IndexingDirective.Include });
                ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="OfferEnableRUPerMinuteThroughput">
      <MemberSignature Language="C#" Value="public bool OfferEnableRUPerMinuteThroughput { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool OfferEnableRUPerMinuteThroughput" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.OfferEnableRUPerMinuteThroughput" />
      <MemberSignature Language="VB.NET" Value="Public Property OfferEnableRUPerMinuteThroughput As Boolean" />
      <MemberSignature Language="F#" Value="member this.OfferEnableRUPerMinuteThroughput : bool with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.OfferEnableRUPerMinuteThroughput" />
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
            Ruft ab oder legt die <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.OfferEnableRUPerMinuteThroughput" /> für eine Sammlung in der Azure-Cosmos-DB-Dienst
            </summary>
        <value>
            Anfordern von Einheiten (RU) stellt / Minute Durchsatz wird aktiviert oder deaktiviert für eine Sammlung in der Azure-Cosmos-DB-Dienst.
            </value>
        <remarks>
            Diese Option ist nur gültig, beim Erstellen einer Dokumentsammlung.
            </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <altmember cref="T:Microsoft.Azure.Documents.OfferV2" />
        <example>
            Im folgenden Beispiel wird veranschaulicht, wie zum Erstellen einer Sammlung mit RU/Minute Durchsatz Angebot.
            <code language="c#"><![CDATA[
            await client.CreateDocumentCollectionAsync(
                database.SelfLink, 
                new DocumentCollection { Id = "newcoll" }, 
                new RequestOptions { OfferThroughput = 4000, OfferEnableRUPerMinuteThroughput  = true });
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="OfferThroughput">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; OfferThroughput { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; OfferThroughput" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.OfferThroughput" />
      <MemberSignature Language="VB.NET" Value="Public Property OfferThroughput As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.OfferThroughput : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.OfferThroughput" />
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
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Angebot Durchsatz für eine Sammlung in der Messung der Anforderungen pro Einheit in der Azure-Cosmos-DB-Dienst bereitgestellt.
            </summary>
        <value>
            Die bereitgestellte hostzwischenspeicherungsrichtlinie für dieses Angebot.
            </value>
        <remarks>
            Diese Option ist nur gültig, beim Erstellen einer Dokumentsammlung.
            <para>Verweisen Sie auf http://azure.microsoft.com/documentation/articles/documentdb-performance-levels/ ausführliche Informationen für die Bereitstellung Angebot Durchsatz.</para></remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <altmember cref="T:Microsoft.Azure.Documents.OfferV2" />
        <example>
            Im folgenden Beispiel wird veranschaulicht, wie eine Sammlung mit Angebot hostzwischenspeicherungsrichtlinie erstellt.
            <code language="c#"><![CDATA[
            await client.CreateDocumentCollectionAsync(
                database.SelfLink, 
                new DocumentCollection { Id = "newcoll" }, 
                new RequestOptions { OfferThroughput = 50000 });
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="OfferType">
      <MemberSignature Language="C#" Value="public string OfferType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OfferType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.OfferType" />
      <MemberSignature Language="VB.NET" Value="Public Property OfferType As String" />
      <MemberSignature Language="F#" Value="member this.OfferType : string with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.OfferType" />
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
            Ruft ab oder legt den Angebotstyp für die Ressource im Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Der Wert des Angebots.
            </value>
        <remarks>
            Diese Option ist nur gültig, beim Erstellen einer Dokumentsammlung.
            <para>Finden Sie in der Liste der gültigen Angebotstypen http://azure.microsoft.comdocumentation/articles/documentdb-performance-levels/.</para></remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <altmember cref="T:Microsoft.Azure.Documents.Offer" />
        <example>
            Im folgenden Beispiel wird veranschaulicht, wie zum Erstellen einer Sammlung mit dem S2-Angebot.
            <code language="c#"><![CDATA[
            await client.CreateDocumentCollectionAsync(
                database.SelfLink, 
                new DocumentCollection { Id = "newcoll" }, 
                new RequestOptions { OfferType = "S2" });
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.PartitionKey PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.PartitionKey PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As PartitionKey" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : Microsoft.Azure.Documents.PartitionKey with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.PartitionKey" />
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
        <ReturnType>Microsoft.Azure.Documents.PartitionKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.PartitionKey" /> für die aktuelle Anforderung im Azure-Cosmos-DB-Dienst.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            Partitionsschlüssel wird verwendet, um die Zielpartition für diese Anforderung zu identifizieren.  Es muss auf Lesen festgelegt und delete-Operationen für alle dokumentanforderungen; Erstellen, lesen, aktualisieren und delete-Vorgänge für alle Anforderungen der Dokument-Anlage; und -Vorgang auf gespeicherte Producedures ausführen.
            
            Für Create und Update-Vorgängen für Dokumente ist der Partitionsschlüssel optional.  Wenn nicht vorhanden, die Clientbibliothek wird den Partitionsschlüssel aus dem Dokument extrahieren Sie vor dem Senden der Anforderungs an den Server.
            </para>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <altmember cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />
        <example>
            Im folgende Beispiel wird gezeigt, wie zum Lesen eines Dokuments in eine partitionierte Sammlung mit <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.PartitionKey" />.
            Das Beispiel setzt voraus, Erstellen der Auflistung mit einem <see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" /> der Eigenschaft "Id" in allen Dokumenten.
            <code language="c#"><![CDATA[
            await client.ReadDocumentAsync(
                document.SelfLink, 
                new RequestOptions { PartitionKey = new PartitionKey(document.Id) } );
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="PopulateQuotaInfo">
      <MemberSignature Language="C#" Value="public bool PopulateQuotaInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool PopulateQuotaInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.PopulateQuotaInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property PopulateQuotaInfo As Boolean" />
      <MemberSignature Language="F#" Value="member this.PopulateQuotaInfo : bool with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.PopulateQuotaInfo" />
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
             Ruft ab oder legt die <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.PopulateQuotaInfo" /> Dokumentationsreihe Anforderungen in der Azure-Cosmos-DB-Dienst lesen.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            PopulateQuotaInfo dient zum Aktivieren/Deaktivieren von abrufen Dokumentationsreihe Kontingent bezogene Statistiken für Dokumentationsreihe leseanforderungen.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PostTriggerInclude">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; PostTriggerInclude { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; PostTriggerInclude" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.PostTriggerInclude" />
      <MemberSignature Language="VB.NET" Value="Public Property PostTriggerInclude As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PostTriggerInclude : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.PostTriggerInclude" />
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
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Trigger, nach Abschluss des Vorgangs im Azure-Cosmos-DB-Dienst aufgerufen werden soll.
            </summary>
        <value>
            Der Trigger, nach Abschluss des Vorgangs aufgerufen werden soll.
            </value>
        <remarks>
            Nur gültig, wenn in Create "," ersetzen "und" Delete-Methoden für Dokumente verwendet.
            Derzeit nur ein PreTrigger pro Vorgang zulässig ist.
            </remarks>
        <see cref="T:Microsoft.Azure.Documents.Trigger" />
        <example>
            Im folgende Beispiel wird gezeigt, wie werden RequestOptions eine PostTrigger, ausgeführt wird, nachdem das Dokument beibehalten eingefügt wird.
            <code language="c#"><![CDATA[
            client.CreateDocumentAsync(collection.SelfLink, 
            new { id = "AndersenFamily", isRegistered = true },
            new RequestOptions { PostTriggerInclude = new List<string> { "updateMetadata" } });
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="PreTriggerInclude">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; PreTriggerInclude { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; PreTriggerInclude" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.PreTriggerInclude" />
      <MemberSignature Language="VB.NET" Value="Public Property PreTriggerInclude As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PreTriggerInclude : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.PreTriggerInclude" />
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
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Trigger, bevor Sie den Vorgang im Azure-Cosmos-DB-Dienst aufgerufen werden soll.
            </summary>
        <value> 
            Der Trigger, bevor der Vorgang aufgerufen werden soll.
            </value>
        <remarks>
            Nur gültig, wenn in Create "," ersetzen "und" Delete-Methoden für Dokumente verwendet.
            Derzeit nur ein PreTrigger pro Vorgang zulässig ist.
            </remarks>
        <see cref="T:Microsoft.Azure.Documents.Trigger" />
        <see cref="T:System.Collections.Generic.IList`1" />
        <example>
            Im folgende Beispiel wird gezeigt, wie werden RequestOptions eine PreTrigger auszuführende vor dem Speichern des Dokuments eingefügt werden.
            <code language="c#"><![CDATA[
            client.CreateDocumentAsync(collection.SelfLink, 
                new { id = "AndersenFamily", isRegistered = true },
                new RequestOptions { PreTriggerInclude = new List<string> { "validateDocumentContents" } });
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="ResourceTokenExpirySeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ResourceTokenExpirySeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ResourceTokenExpirySeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.ResourceTokenExpirySeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceTokenExpirySeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ResourceTokenExpirySeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.ResourceTokenExpirySeconds" />
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
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Ablaufzeit für Ressourcentoken. Wird verwendet, wenn erstellen/aktualisieren/lesen Berechtigungen im Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Die Ablaufzeit in Sekunden für das Ressourcentoken.
            </value>
        <remarks>
            Beim Arbeiten mit Azure-Cosmos-DB-Benutzer und Berechtigungen, die Möglichkeit zum Instanziieren einer Instanz von <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> ist das Abrufen der <see cref="P:Microsoft.Azure.Documents.Permission.Token" /> für die Ressource der <see cref="T:Microsoft.Azure.Documents.User" /> möchte Zugriff auf und übergeben das auf den Parameter AuthKeyOrResourceToken <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> Konstruktor <para> Wenn dieses Token angefordert wird, kann eine RequestOption für ResourceTokenExpirySeconds, legen Sie die Zeitspanne ab, bevor das Token abgelaufen ist. Dieser Wert reichen von 10 Sekunden, 5 Stunden (oder 18.000 Sekunden) der Standardwert, kann keiner werden sollte 1 Stunde (oder 3.600 Sekunden) ist.</para></remarks>
        <altmember cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />
        <altmember cref="T:Microsoft.Azure.Documents.Permission" />
        <altmember cref="T:Microsoft.Azure.Documents.User" />
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.SessionToken" />
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
             Ruft ab oder legt das Token für die Verwendung mit sitzungskonsistenz im Azure-Cosmos-DB-Dienst.
             </summary>
        <value>
             Das Token für die Verwendung mit sitzungskonsistenz.
             </value>
        <remarks>
             Eines der <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.ConsistencyLevel" /> für Azure-Cosmos-DB Sitzung ist. Tatsächlich ist dies die Deault-Ebene, die auf Benutzerkonten angewendet. 
             <para>Bei der Arbeit mit sitzungskonsistenz wird jede neue schreibanforderung an Azure Cosmos-Datenbank eine neue SessionToken zugewiesen.
             Die DocumentClient verwendet dieses Token intern mit jeder Anforderung Lese-/Abfragen, stellen Sie sicher, dass die Set-konsistenzebene beibehalten wird.
             
              <para>In einigen Szenarien müssen Sie diese Sitzung selbst verwalten. Betrachten Sie eine Webanwendung mit mehreren Knoten, wird jeder Knoten eine eigene Instanz des <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> mussten Sie diese Knoten zur Teilnahme an der gleichen Sitzungs (in der Lage sein gelesen eigene Schreibvorgänge konsistent über Webebenen) müssen Sie die SessionToken senden aus <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> der Schreibvorgang auf einen Knoten, die die Clientebene, für die Verwendung eines Cookies oder eines anderen Mechanismus, und diese tokenfluss zurück an die Webebene für nachfolgende Lesevorgänge.
             Wenn Sie einen Roundrobin-Lastenausgleich der sitzungsaffinität zwischen Anforderungen, z. B. Azure-Lastenausgleichs nicht verwaltet mithilfe,  
             die schreibgeschützte konnte potenziell transformationsschritten in einem anderen Knoten auf die schreibanforderung, in dem die Sitzung erstellt wurde. 
             </para><para>Wenn Sie die Azure Cosmos DB SessionToken über erst übernommen, wie oben beschrieben, konnte Sie inkonsistente gelesenen Ergebnisse für eine bestimmte Zeitspanne zum Schluss.</para></para></remarks>
        <altmember cref="P:Microsoft.Azure.Documents.Client.RequestOptions.ConsistencyLevel" />
        <example>
             In diesem Beispiel wird gezeigt, wie Sie die SessionToken aus abrufen können eine <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> und verwenden sie Sie dann auf eine andere Instanz von <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> in <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> in diesem Beispiel wird davon ausgegangen, dass jede Instanz des Clients von Code in einer anderen Anwendungsdomäne aus ausgeführt wird , z. B. auf verschiedenen Knoten im Fall von mehreren Knoten Web-Anwendung
             <code language="c#"><![CDATA[
             string sessionToken;
             string docSelfLink;
             
             using (DocumentClient client = new DocumentClient(new Uri(""), ""))
            {
             ResourceResponse<Document> response = client.CreateDocumentAsync(collection.SelfLink, new { id = "an id", value = "some value" }).Result;
             sessionToken = response.SessionToken;
                 Document created = response.Resource;
                 docSelfLink = created.SelfLink;
                 }
                 
             using (DocumentClient client = new DocumentClient(new Uri(""), ""))
                {
             ResourceResponse<Document> read = client.ReadDocumentAsync(docSelfLink, new RequestOptions { SessionToken = sessionToken }).Result; 
             }
                 ]]></code></example>
      </Docs>
    </Member>
  </Members>
</Type>