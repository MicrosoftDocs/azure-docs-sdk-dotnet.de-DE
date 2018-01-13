<Type Name="FeedOptions" FullName="Microsoft.Azure.Documents.Client.FeedOptions">
  <TypeSignature Language="C#" Value="public sealed class FeedOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FeedOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.FeedOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FeedOptions" />
  <TypeSignature Language="F#" Value="type FeedOptions = class" />
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
            Gibt die Optionen, die feed-Methoden (enumerationsvorgängen) im Azure-Cosmos-DB-Dienst zugeordnet.
            </summary>
    <remarks>
            Zum Verwalten von Abfrage- und ReadFeed Ausführung verwendet. Können FeedOptions Seitengröße (MaxItemCount) festlegen.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FeedOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.FeedOptions.#ctor" />
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
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> Klasse für den Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableRUPerMinuteUsage">
      <MemberSignature Language="C#" Value="public bool DisableRUPerMinuteUsage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DisableRUPerMinuteUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.DisableRUPerMinuteUsage" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableRUPerMinuteUsage As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableRUPerMinuteUsage : bool with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.DisableRUPerMinuteUsage" />
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
            Ruft ab oder legt die <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.DisableRUPerMinuteUsage" /> Option für die aktuelle Abfrage im Azure-Cosmos-DB-Dienst.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            DisableRUPerMinuteUsage dient zum Aktivieren/Deaktivieren von anfordern Einheiten (RUs) / Minute Kapazität für die Abfrage dienen, wenn reguläre RUs/Sekunde bereitgestellt erschöpft ist.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableCrossPartitionQuery">
      <MemberSignature Language="C#" Value="public bool EnableCrossPartitionQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableCrossPartitionQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.EnableCrossPartitionQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableCrossPartitionQuery As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableCrossPartitionQuery : bool with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.EnableCrossPartitionQuery" />
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
            Ruft ab oder legt einen Wert, der angibt, ob Benutzer aktiviert sind, um mehr als eine Anforderung zum Ausführen der Abfrage im Azure-Cosmos-DB-Dienst zu senden. Mehr als eine Anforderung ist erforderlich, wenn die Abfrage nicht auf einzelne partitionsschlüsselwert begrenzt ist.
            </summary>
        <value>
            Option ist "true", wenn die Ausführung von partitionsübergreifenden Abfragen aktiviert ist. andernfalls "false".
            </value>
        <remarks>
          <para>
            Diese Option gilt nur für Abfragen für Dokumente und Dokumentanlagen.
            </para>
        </remarks>
        <example>
          <code language="c#"><![CDATA[
            // Enable cross partition query.
            var queryable = client.CreateDocumentQuery<Book>(
                collectionLink, new FeedOptions { EnableCrossPartitionQuery = true }).Where(b => b.Price > 1000);
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="EnableLowPrecisionOrderBy">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableLowPrecisionOrderBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableLowPrecisionOrderBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.EnableLowPrecisionOrderBy" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableLowPrecisionOrderBy As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableLowPrecisionOrderBy : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.EnableLowPrecisionOrderBy" />
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
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert die Möglichkeit, niedrige Genauigkeit Reihenfolge von im Azure-Cosmos-DB-Dienst zu aktivieren.
            </summary>
        <value>
            Die Option aus, um mit einfacher Genauigkeit mit Order by-aktivieren.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableScanInQuery">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableScanInQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableScanInQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.EnableScanInQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableScanInQuery As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableScanInQuery : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.EnableScanInQuery" />
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
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, war die Option zum Aktivieren von Scans für die Abfragen als Indizierung zustellbaren konnte nicht, abgewählt auf die angeforderte Pfade in der Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Option ist "true", wenn die Überprüfung auf Abfragen aktiviert ist. andernfalls "false".
            </value>
        <remarks>To be added.</remarks>
        <example>
          <code language="c#"><![CDATA[
            // Enable scan when Range index is not specified.
            var queryable = client.CreateDocumentQuery<Book>(
                collectionLink, new FeedOptions { EnableScanInQuery = true }).Where(b => b.Price > 1000);
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferedItemCount">
      <MemberSignature Language="C#" Value="public int MaxBufferedItemCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferedItemCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.MaxBufferedItemCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferedItemCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferedItemCount : int with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.MaxBufferedItemCount" />
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
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest, die die maximale Anzahl von Elementen, die möglich Clientseite während gepuffert parallele Ausführung von Abfragen in der Azure-Cosmos-DB-Dienst. Ein positive Eigenschaftswert schränkt die Anzahl der gepufferten Elemente, die den festgelegten Wert. Wenn sie auf kleiner als 0 festgelegt ist, entscheidet das System automatisch die Anzahl der Elemente in Puffer.
            </summary>
        <value>
            Die maximale Anzahl von Elementen, die während der parallelen abfrageausführung gepuffert werden können.
            </value>
        <remarks>
            Dies ist nur sinnvolle und kann nicht in bestimmten Fällen von abided sein.
            </remarks>
        <example>
          <code language="c#"><![CDATA[
            var queryable = client.CreateDocumentQuery<Book>(collectionLink, new FeedOptions { 
            MaximumBufferSize = 10, MaxDegreeOfParallelism = 2 });
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="MaxDegreeOfParallelism">
      <MemberSignature Language="C#" Value="public int MaxDegreeOfParallelism { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.MaxDegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDegreeOfParallelism As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDegreeOfParallelism : int with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.MaxDegreeOfParallelism" />
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
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der gleichzeitigen Vorgänge, die Clientseite werden während der parallelen abfrageausführung im Azure-Cosmos-DB-Dienst ausgeführt. Ein positiver Eigenschaftswert beschränkt die Anzahl der gleichzeitigen Vorgänge auf den festgelegten Wert. Wenn ein kleinerer Wert als 0 festgelegt wird, wird die Anzahl der gleichzeitig auszuführenden Vorgänge automatisch vom System festgelegt.
            </summary>
        <value>
            Die maximale Anzahl gleichzeitiger Vorgänge während der parallelen Ausführung. Der Standardwert ist 0.
            </value>
        <remarks>To be added.</remarks>
        <example>
          <code language="c#"><![CDATA[
            var queryable = client.CreateDocumentQuery<Book>(collectionLink, new FeedOptions { 
            MaxDegreeOfParallelism = 5});
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="MaxItemCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxItemCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxItemCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.MaxItemCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxItemCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxItemCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.MaxItemCount" />
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
            Ruft ab oder legt die maximale Anzahl von Elementen, die in der Enumerationsvorgang im Azure-Cosmos-DB-Dienst zurückgegeben werden.
            </summary>
        <value>
            Die maximale Anzahl von Elementen, die in der Enumerationsvorgang zurückgegeben werden.
            </value>
        <remarks>
            Für die abfragenpaginierung verwendet.
            "-1" wird für dynamische Seitengröße verwendet.
            </remarks>
        <example>
          <code language="c#"><![CDATA[
            // Fetch query results 10 at a time.
            using (var queryable = client.CreateDocumentQuery<Book>(collectionLink, new FeedOptions { MaxItemCount = 10 }))
            {
                while (queryable.HasResults)
                {
                    FeedResponse<Book> response = await queryable.ExecuteNext<Book>();
                }
            }
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.PartitionKey PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.PartitionKey PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As PartitionKey" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : Microsoft.Azure.Documents.PartitionKey with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" />
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
            Ruft ab oder legt die <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" /> für die aktuelle Anforderung im Azure-Cosmos-DB-Dienst.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            Partitionsschlüssel ist erforderlich, wenn Sie Dokumente oder Anlagen in eine partitionierte Sammlung feed gelesen. Insbesondere Partitionsschlüssel ist erforderlich für: <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadDocumentFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />, <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadAttachmentFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" /> und <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadConflictFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />.  
            Nur Dokumente zurück in Partitionen, die die <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" /> wird im Resultset zurückgegeben.
                </para>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <altmember cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />
        <example>
            Das folgende Beispiel zeigt, wie ein Dokument in einem partitionierten Auflistung von feed gelesen <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" />.
            Das Beispiel setzt voraus, Erstellen der Auflistung mit einem <see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" /> für die Eigenschaft "Country" in allen Dokumenten.
            <code language="c#"><![CDATA[
            await client.ReadDocumentFeedAsync(
                collection.SelfLink, 
                new RequestOptions { PartitionKey = new PartitionKey("USA") } );
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyRangeId">
      <MemberSignature Language="C#" Value="public string PartitionKeyRangeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyRangeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKeyRangeId" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKeyRangeId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyRangeId : string with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.PartitionKeyRangeId" />
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
            Ruft ab oder legt den Schlüsselbereich Partitions-Id für die aktuelle Anforderung.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            ReadFeed Anforderungen können diese Anforderung auf bestimmten Bereich weiterzuleiten.
            Hierbei handelt es sich um Hilfsprogramms bei Bulk-Export-Szenarien.
            </para>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <example>
            Im folgende Beispiel wird gezeigt, wie ein Dokument in eine partitionierte Sammlung von partitionsschlüsselbereichs "20" feed gelesen werden.
            <code language="c#"><![CDATA[
            await client.ReadDocumentFeedAsync(
                collection.SelfLink, 
                new RequestOptions { PartitionKeyRangeId = "20" } );
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="PopulateQueryMetrics">
      <MemberSignature Language="C#" Value="public bool PopulateQueryMetrics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool PopulateQueryMetrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.PopulateQueryMetrics" />
      <MemberSignature Language="VB.NET" Value="Public Property PopulateQueryMetrics As Boolean" />
      <MemberSignature Language="F#" Value="member this.PopulateQueryMetrics : bool with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.PopulateQueryMetrics" />
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
             Ruft ab oder legt die <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PopulateQueryMetrics" /> Option für die Abfrage dokumentanforderungen im Azure-Cosmos-DB-Dienst anfordern.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            PopulateQueryMetrics dient zum Aktivieren/Deaktivieren von abrufen Metriken, die im Zusammenhang mit der Ausführung von Abfragen auf Dokument abfrageanforderungen.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestContinuation">
      <MemberSignature Language="C#" Value="public string RequestContinuation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestContinuation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.RequestContinuation" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestContinuation As String" />
      <MemberSignature Language="F#" Value="member this.RequestContinuation : string with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.RequestContinuation" />
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
            Ruft ab oder legt das Fortsetzungstoken für die Anforderung im Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Das Fortsetzungstoken für die Anforderung.
            </value>
        <remarks>To be added.</remarks>
        <example>
          <code language="c#"><![CDATA[
            // Resume query execution using the continuation from the previous query
            var queryable = client.CreateDocumentQuery<Book>(collectionLink, new FeedOptions { RequestContinuation = prevQuery.ResponseContinuation });
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="ResponseContinuationTokenLimitInKb">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ResponseContinuationTokenLimitInKb { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ResponseContinuationTokenLimitInKb" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.ResponseContinuationTokenLimitInKb" />
      <MemberSignature Language="VB.NET" Value="Public Property ResponseContinuationTokenLimitInKb As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ResponseContinuationTokenLimitInKb : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.ResponseContinuationTokenLimitInKb" />
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
             Ruft ab oder legt die <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.ResponseContinuationTokenLimitInKb" /> Option für die Abfrage dokumentanforderungen im Azure-Cosmos-DB-Dienst anfordern.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            ResponseContinuationTokenLimitInKb wird verwendet, um die Länge des Fortsetzungstokens in der Abfrageantwort zu beschränken. Gültige Werte sind &gt;= 0.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.SessionToken" />
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
            Ruft ab oder legt das Sitzungstoken für die Verwendung mit sitzungskonsistenz im Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Das Sitzungstoken für die Verwendung mit sitzungskonsistenz.
            </value>
        <remarks>
            Bei Anwendungen nützlich, die einen Lastenausgleich über mehrere Microsoft.Azure.Documents.Client.DocumentClient-Instanzen sind. In diesem Fall Roundtrip des Tokens aus Endbenutzer die Anwendung, und dann zurück zum Azure-Cosmos-Datenbank, damit eine Sitzung über Server hinweg beibehalten werden kann.
            </remarks>
        <example>
          <code language="c#"><![CDATA[
            var queryable = client.CreateDocumentQuery<Book>(
                collectionLink, new FeedOptions { SessionToken = lastSessionToken });
            ]]></code>
        </example>
      </Docs>
    </Member>
  </Members>
</Type>