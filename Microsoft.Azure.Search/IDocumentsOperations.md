<Type Name="IDocumentsOperations" FullName="Microsoft.Azure.Search.IDocumentsOperations">
  <TypeSignature Language="C#" Value="public interface IDocumentsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDocumentsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.IDocumentsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDocumentsOperations" />
  <TypeSignature Language="F#" Value="type IDocumentsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Definiert die Vorgänge zum Abfragen von Index und hochladen, Zusammenführen und Löschen von Dokumenten.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Document-operations" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinueSearchWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt; ContinueSearchWithHttpMessagesAsync (Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt; ContinueSearchWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.ContinueSearchWithHttpMessagesAsync(Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContinueSearchWithHttpMessagesAsync : Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt;" Usage="iDocumentsOperations.ContinueSearchWithHttpMessagesAsync (continuationToken, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="continuationToken">
            Kapselt den Zustand erforderlich, um die nächste Seite der Suchergebnisse aus dem Index abrufen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die nächste Seite der Suchergebnisse aus dem Azure-Suchindex ab.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            Die Antwort mit den Dokumenten, die mit der Abfrage übereinstimmen.
            </returns>
        <remarks>
          <para>
            Nicht generische Überladungen der Methoden ContinueSearch ContinueSearchAsync und ContinueSearchWithHttpMessagesAsync stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen. Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .
            </para>
          <para>
            Wenn Azure Search alle Ergebnisse in einer einzelnen Antwort enthalten kann, umfasst die Antwort zurückgegeben wird ein Fortsetzungstoken ContinueSearch zum Abrufen von mehr Ergebnissen übergeben werden kann.
            Finden Sie unter <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> für Weitere Informationen.
            </para>
          <para>
            Beachten Sie, dass diese Methode nicht vorgesehen ist, können Sie die Auslagerung von Suchergebnissen zu implementieren. Implementieren Sie mithilfe von Paging der <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">oben</c> und <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">überspringen</c> Parameter für die <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Suche</c> Methode.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueSearchWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;&gt; ContinueSearchWithHttpMessagesAsync&lt;T&gt; (Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt;&gt;&gt; ContinueSearchWithHttpMessagesAsync&lt;class T&gt;(class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.ContinueSearchWithHttpMessagesAsync``1(Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContinueSearchWithHttpMessagesAsync : Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T&gt;&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.ContinueSearchWithHttpMessagesAsync (continuationToken, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.
            </typeparam>
        <param name="continuationToken">
            Kapselt den Zustand erforderlich, um die nächste Seite der Suchergebnisse aus dem Index abrufen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die nächste Seite der Suchergebnisse aus dem Azure-Suchindex ab.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            Die Antwort mit den Dokumenten, die mit der Abfrage übereinstimmen.
            </returns>
        <remarks>
          <para>
            Generische Überladungen der Methoden ContinueSearch ContinueSearchAsync und ContinueSearchWithHttpMessagesAsync unterstützen die Zuordnung von Feldtypen für Azure Search .NET Typen über der Typparameter T. Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.
            </para>
          <para>
            Wenn Azure Search alle Ergebnisse in einer einzelnen Antwort enthalten kann, umfasst die Antwort zurückgegeben wird ein Fortsetzungstoken ContinueSearch zum Abrufen von mehr Ergebnissen übergeben werden kann.
            Finden Sie unter <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> für Weitere Informationen.
            </para>
          <para>
            Beachten Sie, dass diese Methode nicht vorgesehen ist, können Sie die Auslagerung von Suchergebnissen zu implementieren. Implementieren Sie mithilfe von Paging der <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">oben</c> und <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">überspringen</c> Parameter für die <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Suche</c> Methode.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;long&gt;&gt; CountWithHttpMessagesAsync (Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;int64&gt;&gt; CountWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.CountWithHttpMessagesAsync(Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CountWithHttpMessagesAsync : Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;int64&gt;&gt;" Usage="iDocumentsOperations.CountWithHttpMessagesAsync (searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Int64&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Fragt die Anzahl der Dokumente in der Azure Search-Index.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Document&gt;&gt; GetWithHttpMessagesAsync (string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.Document&gt;&gt; GetWithHttpMessagesAsync(string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Document&gt;&gt;" Usage="iDocumentsOperations.GetWithHttpMessagesAsync (key, selectedFields, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="key">
            Der Schlüssel des abzurufenden Dokuments; Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> für die Regeln zum Erstellen von gültigen Dokumentschlüssel.
            </param>
        <param name="selectedFields">
            Liste von Feldnamen für das Dokument abgerufen; Jedes Feld nicht abgerufen werden aus dem zurückgegebenen Dokument fehlt.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft ein Dokument aus dem Azure-Suchindex ab.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            Die Antwort mit dem Dokument.
            </returns>
        <remarks>
            Die nicht generische Überladungen der Methoden Get, GetAsync und GetWithHttpMessagesAsync stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen. Diese Zuordnung verfügt nicht über den Vorteil, dass Ausdrucksdatentyp Informationen aus dem Index, damit die Zuordnung nicht immer korrekt ist. Insbesondere werden von den folgenden Fällen beachten: <list type="bullet"> <item> <description> einer beliebigen numerischen Wert ohne ein Dezimaltrennzeichen an. Int64 (Long in c#) deserialisiert werden. </description></item><item><description>Als Typ "System.String statt System.Double" werden besondere Gleitkommawerte mit doppelter Genauigkeit hinsichtlich Ihrer z. B. "NaN" und unendlich deserialisiert. </description></item><item><description>Jedes Zeichenfolgenfeld mit einem Wert, der formatiert wird, wie ein "DateTimeOffset" wird nicht ordnungsgemäß deserialisiert werden. Es wird empfohlen, solche Werte in Edm.DateTimeOffset Felder statt Edm.String Felder zu speichern. </description></item><item><description>Jedes Feld Edm.DateTimeOffset wird als eine System.DateTimeOffset, nicht System.DateTime deserialisiert werden.</description></item></list></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;T&gt;&gt; GetWithHttpMessagesAsync&lt;T&gt; (string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;!!T&gt;&gt; GetWithHttpMessagesAsync&lt;class T&gt;(string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;'T&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.GetWithHttpMessagesAsync (key, selectedFields, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.
            </typeparam>
        <param name="key">
            Der Schlüssel des abzurufenden Dokuments; Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> für die Regeln zum Erstellen von gültigen Dokumentschlüssel.
            </param>
        <param name="selectedFields">
            Liste von Feldnamen für das Dokument abgerufen; Jedes Feld nicht abgerufen müssen Null oder Default als die entsprechenden Eigenschaftswert im zurückgegebenen Objekt.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft ein Dokument aus dem Azure-Suchindex ab.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            Die Antwort mit dem Dokument.
            </returns>
        <remarks>
            Die generische Überladungen der Methoden Get, GetAsync und GetWithHttpMessagesAsync unterstützen die Zuordnung von Feldtypen, .NET-oder Schematypen über der Typparameter T. Beachten Sie, dass alle Typen von Azure Search-Feld außer Sammlungen NULL-Werte zulässt, daher empfehlen wir mit Azure Search primitive Typen für die Eigenschaften des Typs t Die Typzuordnung lautet wie folgt: <list type="table"> <listheader> <term>Azure Search-Feldtyp</term><description>.NET Typ</description></listheader><item><term>Edm.String</term> <description> System.String (String in c#)</description></item><item><term>Collection(Edm.String)</term><description>IEnumerable&lt;System.String&gt; </description> </item> <item> <term>Edm.Boolean</term><description>System.Nullable&lt;System.Boolean&gt; (Bool? in c#)</description> </item> <item> <term>"Edm.Double"</term><description>System.Nullable&lt;System.Double&gt; (double? in c#)</description></item><item><term>Int32</term> <description>System.Nullable&lt;System. Int32&gt; (Int? in c#)</description></item><item><term>Int64</term><description>System.Nullable&lt; System. Int64&gt; (lange? in c#)</description></item><item><term>Edm.DateTimeOffset</term> <description> System.Nullable&lt; System.DateTimeOffset&gt; ("DateTimeOffset"? in c#) oder System.Nullable&lt;System.DateTime&gt; ("DateTime"? in c#). Beide Typen verwendet werden, obwohl es wird empfohlen, "DateTimeOffset". Wenn Sie Dokumente abrufen, wird "DateTime" Werte immer UTC. Beim Indizieren von Dokumenten werden DateTime-Werte wie folgt interpretiert: <list type="table"> <item> <term>UTC-DateTime</term><description>als gesendet – bis zum Index ist.</description> </item> <item> <term>Lokalen DateTime</term><description>vor dem senden, die dem Index in UTC konvertiert.</description> </item> <item> <term>"DateTime" mit nicht spezifizierten Zeitzone</term><description>davon ausgegangen, dass UTC und als gesendet – bis zum Index ist.</description> </item> </list> </description> </item> <item> <term>"Edm.geographypoint"</term><description><c cref="T:Microsoft.Spatial.GeographyPoint">Microsoft.Spatial.GeographyPoint</c></description></item></list></remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; IndexWithHttpMessagesAsync (Microsoft.Azure.Search.Models.IndexBatch batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; IndexWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.IndexBatch batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.IndexWithHttpMessagesAsync(Microsoft.Azure.Search.Models.IndexBatch,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member IndexWithHttpMessagesAsync : Microsoft.Azure.Search.Models.IndexBatch * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt;" Usage="iDocumentsOperations.IndexWithHttpMessagesAsync (batch, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="batch">
            Der Batch, der indexaktionen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Sendet einen Batch von hochladen, Zusammenführen und/oder löschen-Aktionen auf den Azure Search-Index.
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            Die Antwort enthält den Status von Vorgängen für alle Aktionen im Batch.
            </returns>
        <remarks>
            Die nicht generische Überladungen der Index, IndexAsync und IndexWithHttpMessagesAsync Methoden stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen. Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            Wird ausgelöst, wenn einige der Volltextindizierung Aktionen Fehler, aber andere Aktionen erfolgreich ausgeführt wurde und der Status des Indexes geändert. Dies kann geschehen, wenn der Suchdienst Indizierung ausgelastet ist. Es ist wichtig, explizit diese Ausnahme abfangen und überprüfen Sie ihre <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> Eigenschaft. Diese Eigenschaft gibt den Status der einzelnen Indizierung Aktionen im Batch, wodurch den Status des Indexes nach einem Fehler, teilweise zu bestimmen.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="IndexWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; IndexWithHttpMessagesAsync&lt;T&gt; (Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; IndexWithHttpMessagesAsync&lt;class T&gt;(class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.IndexWithHttpMessagesAsync``1(Microsoft.Azure.Search.Models.IndexBatch{``0},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member IndexWithHttpMessagesAsync : Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.IndexWithHttpMessagesAsync (batch, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente im Index gespeichert werden.
            </typeparam>
        <param name="batch">
            Der Batch, der indexaktionen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Sendet einen Batch von hochladen, Zusammenführen und/oder löschen-Aktionen auf den Azure Search-Index.
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            Die Antwort enthält den Status von Vorgängen für alle Aktionen im Batch.
            </returns>
        <remarks>
            Generische Überladungen der Index, IndexAsync und IndexWithHttpMessagesAsync Methoden unterstützen die Zuordnung von Azure Search-Feld-Typen, die .NET-oder Schematypen über der Typparameter t Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            Wird ausgelöst, wenn einige der Volltextindizierung Aktionen Fehler, aber andere Aktionen erfolgreich ausgeführt wurde und der Status des Indexes geändert. Dies kann geschehen, wenn der Suchdienst Indizierung ausgelastet ist. Es ist wichtig, explizit diese Ausnahme abfangen und überprüfen Sie ihre <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> Eigenschaft. Diese Eigenschaft gibt den Status der einzelnen Indizierung Aktionen im Batch, wodurch den Status des Indexes nach einem Fehler, teilweise zu bestimmen.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SearchWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt; SearchWithHttpMessagesAsync (string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt; SearchWithHttpMessagesAsync(string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SearchWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt;" Usage="iDocumentsOperations.SearchWithHttpMessagesAsync (searchText, searchParameters, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="searchText">
            Ein Abfrageausdruck für die Volltextsuche; Verwenden Sie Null oder "*" alle Dokumente übereinstimmen. Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> Weitere Informationen zur Abfragesyntax für die Suche.
            </param>
        <param name="searchParameters">
            Parameter für die Suchabfrage verfeinern.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Sucht nach Dokumenten in Azure Search-Index.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            Die Antwort mit den Dokumenten, die mit der Abfrage übereinstimmen.
            </returns>
        <remarks>
          <para>
            Nicht generische Überladungen der Suche, SearchAsync und SearchWithHttpMessagesAsync Methoden stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen. Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .
            </para>
          <para>
            Wenn Azure Search alle Ergebnisse in einer einzelnen Antwort enthalten kann, umfasst die Antwort zurückgegeben wird ein Fortsetzungstoken ContinueSearch zum Abrufen von mehr Ergebnissen übergeben werden kann.
            Finden Sie unter <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> für Weitere Informationen.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;&gt; SearchWithHttpMessagesAsync&lt;T&gt; (string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt;&gt;&gt; SearchWithHttpMessagesAsync&lt;class T&gt;(string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SearchWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T&gt;&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.SearchWithHttpMessagesAsync (searchText, searchParameters, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.
            </typeparam>
        <param name="searchText">
            Ein Abfrageausdruck für die Volltextsuche; Verwenden Sie Null oder "*" alle Dokumente übereinstimmen. Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> Weitere Informationen zur Abfragesyntax für die Suche.
            </param>
        <param name="searchParameters">
            Parameter für die Suchabfrage verfeinern.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Sucht nach Dokumenten in Azure Search-Index.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            Die Antwort mit den Dokumenten, die mit der Abfrage übereinstimmen.
            </returns>
        <remarks>
          <para>
            Generische Überladungen der Methoden suchen, SearchAsync und SearchWithHttpMessagesAsync unterstützen die Zuordnung von Feldtypen, .NET-oder Schematypen über der Typparameter t Azure Search Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.
            </para>
          <para>
            Wenn Azure Search alle Ergebnisse in einer einzelnen Antwort enthalten kann, umfasst die Antwort zurückgegeben wird ein Fortsetzungstoken ContinueSearch zum Abrufen von mehr Ergebnissen übergeben werden kann.
            Finden Sie unter <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> für Weitere Informationen.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuggestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;&gt; SuggestWithHttpMessagesAsync (string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;&gt; SuggestWithHttpMessagesAsync(string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.SuggestWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuggestWithHttpMessagesAsync : string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;&gt;" Usage="iDocumentsOperations.SuggestWithHttpMessagesAsync (searchText, suggesterName, suggestParameters, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="searchText">
            Das Suchen von Text auf der Vorschläge basieren.
            </param>
        <param name="suggesterName">
            Der Name des suggesters gemäß Angabe in der suggester-Auflistung, die Teil der Indexdefinition ist.
            </param>
        <param name="suggestParameters">
            Parameter, die die vorschlagsabfrage weiter zu verfeinern.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Wird basierend auf dem Eingabetext und Vergleich von Dokumenten in der Azure-Suchindex Abfrageausdrücke vorgeschlagen.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            Die Antwort mit der vorgeschlagene Text und Dokumente, die mit der Abfrage übereinstimmen.
            </returns>
        <remarks>
            Die nichtgenerischen Überladungen der Methoden vorschlagen, SuggestAsync und SuggestWithHttpMessagesAsync stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen. Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuggestWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;&gt;&gt; SuggestWithHttpMessagesAsync&lt;T&gt; (string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSuggestResult`1&lt;!!T&gt;&gt;&gt; SuggestWithHttpMessagesAsync&lt;class T&gt;(string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.SuggestWithHttpMessagesAsync``1(System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuggestWithHttpMessagesAsync : string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;'T&gt;&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.SuggestWithHttpMessagesAsync (searchText, suggesterName, suggestParameters, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.
            </typeparam>
        <param name="searchText">
            Das Suchen von Text auf der Vorschläge basieren.
            </param>
        <param name="suggesterName">
            Der Name des suggesters gemäß Angabe in der suggester-Auflistung, die Teil der Indexdefinition ist.
            </param>
        <param name="suggestParameters">
            Parameter, die die vorschlagsabfrage weiter zu verfeinern.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Wird basierend auf dem Eingabetext und Vergleich von Dokumenten in der Azure-Suchindex Abfrageausdrücke vorgeschlagen.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            Die Antwort mit der vorgeschlagene Text und Dokumente, die mit der Abfrage übereinstimmen.
            </returns>
        <remarks>
            Generische Überladungen der Methoden vorschlagen, SuggestAsync und SuggestWithHttpMessagesAsync unterstützen die Zuordnung von Azure Search-Feld-Typen, die .NET-oder Schematypen über der Typparameter T. Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>